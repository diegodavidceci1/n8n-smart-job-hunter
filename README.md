# 💼 Cazador de Empleo Inteligente - Automatización 24/7 con n8n e IA

¡Bienvenido! Este es un sistema de automatización avanzado desarrollado de forma nativa en **n8n** y desplegado en la nube (**Render**). El robot trabaja en segundo plano las 24 horas del día buscando, filtrando y optimizando el proceso de postulación laboral en el mercado tecnológico global.

## 🚀 Características del Sistema
- **Rastreo Multiplataforma:** Conexión en paralelo vía API y RSS a fuentes globales como Remotive, Arbeitnow y We Work Remotely.
- **Filtro Inteligente:** Algoritmos de filtrado avanzado (lógica OR/AND) que eliminan ofertas irrelevantes (Senior/Lead) y priorizan palabras clave (n8n, Make, Zapier, Automation).
- **Redacción Automatizada con IA:** Integración con modelos de lenguaje para redactar una *Cover Letter* (carta de presentación) corta y personalizada según la descripción de cada puesto.
- **Notificaciones en Tiempo Real:** Envío de alertas estructuradas directo a un canal privado de **Telegram**.

## 🛠️ Tecnologías Utilizadas
- **n8n v1.111.0** (Motor de flujos de trabajo)
- **PostgreSQL (Neon.tech)** (Base de datos persistente en la nube)
- **UptimeRobot** (Sistema de monitoreo para garantizar disponibilidad 24/7)
- **Docker** (Contenedorización para despliegue en Render)

## 📦 Cómo replicar este flujo
1. Descarga el archivo `flujo.json` de este repositorio.
2. Impórtalo en tu instancia de n8n.
3. Configura tus credenciales de Telegram API y ¡listo!

