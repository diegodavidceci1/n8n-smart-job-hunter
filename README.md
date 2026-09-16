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


