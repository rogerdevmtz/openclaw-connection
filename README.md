# Conecta tu Agente: Telegram, Google Docs y Calendario

Entrega del proyecto de integración de **OpenClaw (Atlas)** con **Telegram**, **Google Docs** y **Google Calendar**, mediante **Zapier MCP**.

## Resultado verificado

El flujo se ejecutó desde Telegram: solicitud → preguntas del agente para completar los datos → creación de un documento → reserva de tiempo para revisarlo → confirmación por Telegram. El historial de Zapier registra las dos acciones como **Success**.

- Documento: **Plan de estudio de OpenClaw — prueba de integración**, con cuatro apartados sobre canales, habilidades, seguridad y MCP.
- Evento: **Revisar plan de estudio de OpenClaw**, el **29 de octubre de 2026, de 10:00 a 10:30**, zona **Europe/Madrid**.
- El evento contiene el enlace al documento y se creó sin invitados.
- Atlas solicitó título, contenido, fecha, hora, duración, calendario y zona horaria antes de ejecutar.

## Evidencias

Las imágenes son capturas de las aplicaciones reales. Se muestran con contexto y se excluyen credenciales, códigos OAuth y datos personales. Los documentos y calendarios permanecen privados; las capturas permiten revisar la entrega sin acceder a la cuenta de prueba.

### 1. OpenClaw conectado al servidor MCP

![Cliente OpenClaw conectado](02-zapier-mcp-conectado.jpg)

### 2. Herramientas de Google Docs y Calendar

Se habilitaron únicamente **Create Document From Text** y **Create Detailed Event**.

![Herramientas configuradas](03-zapier-herramientas.jpg)

### 3. Solicitud por Telegram y preguntas del agente

![Solicitud y aclaraciones](04-telegram-solicitud-y-aclaraciones.jpg)

### 4. Confirmación de finalización por Telegram

![Confirmación de Atlas](05-telegram-confirmacion.jpg)

### 5. Documento creado en Google Docs

![Documento de estudio creado](06-documento-creado.jpg)

### 6. Evento creado en Google Calendar

![Reserva de revisión del documento](07-evento-creado.jpg)

### 7. Historial MCP con ambas ejecuciones exitosas

![Historial de Zapier](08-historial-zapier-exito.jpg)

## Notas de configuración

Las decisiones de configuración y los problemas resueltos se describen en [notes.md](notes.md). No se incluyen archivos de configuración del servidor, tokens ni claves API.
