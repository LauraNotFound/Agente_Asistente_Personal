# 🤖 Personal AI Assistant 

[![Awesome Project](https://img.shields.io/badge/Awesome-Project-blue.svg)](https://github.com/LauraNotFound/Agente_Asistente_Personal)

**¡Transforma tu productividad con este asistente personal impulsado por IA!** 🚀

Este proyecto implementa un agente de IA versátil diseñado para simplificar tu vida digital. Integrado con Telegram, Google Sheets, OpenAI, Google Calendar y Gmail, este asistente automatiza tareas y te mantiene organizado.

## ✨ Características Principales

* **Integración Multicanal:** Interactúa con tu asistente a través de Telegram. 💬
* **Gestión Inteligente de Contactos:** Accede y gestiona información de contactos almacenada en Google Sheets. 🗂️
* **Automatización de Correo Electrónico:** Envía y recibe correos electrónicos sin esfuerzo. 📧
* **Planificación de Calendario:** Programa y gestiona eventos en tu Google Calendar. 📅
* **Procesamiento de Lenguaje Natural:** Comprende y responde a tus comandos gracias a la potencia de OpenAI.🧠
* **Soporte de Entrada de Voz:** Envía mensajes de voz y el asistente los transcribirá para procesarlos. 🎙️

## 🛠️ Tecnologías Utilizadas

* **n8n:** Para la orquestación del flujo de trabajo y la integración de servicios.
* **Telegram API:** Para la comunicación con el usuario.
* **Google Sheets API:** Para la gestión de contactos.
* **Gmail API:** Para la automatización de correos electrónicos.
* **Google Calendar API:** Para la gestión de eventos de calendario.
* **OpenAI API (GPT-4o):** Para el procesamiento del lenguaje natural y la toma de decisiones del agente.

## ⚙️ Flujo de Trabajo

1.  **Recepción de Mensajes:** El asistente recibe mensajes de texto o voz a través de Telegram. 📥
2.  **Procesamiento de Voz (Opcional):** Si el mensaje es de voz, se transcribe a texto utilizando OpenAI. 🗣️➡️📝
3.  **Análisis de Intención:** El agente de IA, impulsado por OpenAI, analiza la intención del usuario. 🤔
4.  **Ejecución de Tareas:** El agente utiliza las herramientas integradas para realizar las tareas solicitadas:
    * **Contactos:** Busca información en Google Sheets.
    * **agenteEmail:** Envía o recibe correos electrónicos.
    * **agenteCalendario:** Crea o modifica eventos en el calendario.
    * **agenteBusqueda:** Realiza búsquedas y responde preguntas generales. 
5.  **Envío de Respuesta:** El asistente envía una respuesta al usuario a través de Telegram. 📤

## 🚀  Cómo Empezar

1.  **Clona el repositorio:**

    ```bash
    git clone https://github.com/tu-usuario/tu-repo.git
    ```

2.  **Configura las credenciales:** Asegúrate de configurar las credenciales de Telegram, Google Sheets, Gmail, Google Calendar y OpenAI en n8n.
3.  **Importa el flujo de trabajo en n8n.**
4.  **¡Empieza a usar tu asistente personal!**

## 📄 Licencia

Este proyecto está bajo la Licencia [MIT](LICENSE).

---

**¡Espero que disfrutes de tu nuevo asistente personal!** 🌟

_**By LauraNotFound🍄**_
