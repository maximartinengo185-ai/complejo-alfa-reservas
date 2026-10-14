# Complejo Alfa • Sistema de Reservas Online

[![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com/deploy?repo=https://github.com/maximartinengo185-ai/complejo-alfa-reservas)

Plataforma oficial de reservas en tiempo real de **Complejo Alfa Pádel**, impulsada por [Fácil Reserva](https://facilreserva.com).

## 🚀 Despliegue en 1 Clic en Render
👉 **[Desplegar en Render](https://render.com/deploy?repo=https://github.com/maximartinengo185-ai/complejo-alfa-reservas)**

Render creará automáticamente el Static Site gracias al archivo `render.yaml`.

## 🌐 Configuración del Subdominio (alfa.facilreserva.com)
1. En Render: ve a **Settings** > **Custom Domains** y añade:
   `alfa.facilreserva.com`
2. En DonWeb: agrega el registro:
   - **Tipo**: `CNAME` (o `A`)
   - **Nombre**: `alfa`
   - **Destino**: `alfa-padel.onrender.com` (o la IP `216.24.57.1`)
