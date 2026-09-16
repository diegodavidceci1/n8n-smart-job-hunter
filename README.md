# 💼 Cazador de Empleo Inteligente con IA - n8n v1.111.0

¡Bienvenido! Este es un sistema de automatización avanzado desarrollado de forma nativa en **n8n** y desplegado en la nube (**Render**). El robot trabaja en segundo plano rastreando, filtrando y optimizando el proceso de postulación laboral en el mercado tecnológico de habla hispana.

## 🚀 Características del Sistema
- **Rastreo Multiplataforma:** Conexión en paralelo vía canales RSS avanzados y APIs a fuentes líderes del mercado hispano (InfoJobs, Tecnoempleo, Computrabajo, Domestika y LinkedIn en español).
- **Filtro Inteligente de Oro:** Script avanzado en JavaScript que elimina duplicados por enlace, descarta de raíz puestos jerárquicos o inglés avanzado (Senior, Lead, Ingeniero, English Alto, B2) y prioriza vacantes 100% accesibles de nivel inicial (Junior, Trainee, Becario, Prácticas, Sin Experiencia, Low-Code, Soporte).
- **Redacción Automatizada con IA:** Integración directa con la API oficial de **Groq (openai/gpt-oss-120b)** para redactar cartas de presentación (Cover Letters) personalizadas de 2 párrafos en español, honestas y enfocadas en el dominio exclusivo de n8n.
- **Notificaciones en Tiempo Real:** Envío de alertas estructuradas y formateadas en Markdown directo a un canal privado de **Telegram**.
- **Blindaje contra Límites de Velocidad:** Configuración avanzada de reintentos automáticos (Retry on Fail) que espera 5 segundos (5000 ms) para gestionar de forma autónoma las cuotas y los límites de tokens por minuto (TPM) de la capa gratuita de Groq.

## 📦 Cómo replicar este flujo
1. Descarga el archivo `Mi flujo de trabajo.json` de este repositorio.
2. Impórtalo en tu instancia de n8n.
3. Configura tus credenciales de Telegram API y Groq, ¡y listo!



---

## 🛠️ Proyecto #2: Automatización de Leads (Formulario Web ➡️ Google Sheets ➡️ Telegram)
Este es un flujo de nivel comercial diseñado exclusivamente para clientes freelance (inmobiliarias, agencias de marketing o e-commerce) que necesitan capturar contactos en su sitio web de forma automatizada.

### ⚙️ Estructura del Flujo
1. **Captura en Tiempo Real:** Nodo **Webhook** que recibe los datos del formulario (Nombre, Email, Teléfono, Mensaje) al instante.
2. **Control de Calidad:** Nodo lógico **IF** que valida la estructura del correo electrónico para evitar datos falsos o spam.
3. **Persistencia de Datos:** Nodo **Google Sheets** que inserta de forma ordenada cada nuevo contacto con su respectiva fecha y hora de registro.
4. **Alerta de Venta Inmediata:** Nodo **Telegram** que le notifica al celular del dueño del negocio que tiene un nuevo cliente listo para ser atendido.

*El archivo de este flujo está disponible en este repositorio bajo el nombre `formulario-a-sheets.json`.*
