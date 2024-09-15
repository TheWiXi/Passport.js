# Autenticación con Passport.js (Facebook, Google, Discord)

Este repositorio contiene una implementación básica de autenticación usando Passport.js con estrategias para Facebook, Google y Discord.

## Requisitos previos

- Node.js y npm instalados
- Cuentas de desarrollador en Facebook, Google y Discord para obtener las credenciales de OAuth

## Instalación

1. Clona este repositorio:

   ```
   git clone URL
   ```
2. Instala las dependencias:

   ```
   npm install
   ```
3. Crea un archivo `.env` en la raíz del proyecto y añade tus credenciales:

   ```
   FACEBOOK_APP_ID=tu_app_id
   FACEBOOK_APP_SECRET=tu_app_secret
   GOOGLE_CLIENT_ID=tu_client_id
   GOOGLE_CLIENT_SECRET=tu_client_secret
   DISCORD_CLIENT_ID=tu_client_id
   DISCORD_CLIENT_SECRET=tu_client_secret
   SESSION_SECRET=una_clave_secreta_aleatoria
   ```

## Uso

1. Inicia el servidor:

   ```
   npm start
   ```
2. Abre tu navegador y ve a `http://localhost:3000`
3. Haz clic en los botones de inicio de sesión para autenticarte con Facebook, Google o Discord

## Estructura del proyecto

- `index.js`: Configuración del servidor y Passport.js
- `public/index.html`: Página de inicio de sesión
- `public/styles.css`: Estilos para la página de inicio de sesión

## Notas

- Este es un ejemplo básico y no debe usarse en producción sin las medidas de seguridad adecuadas
- Asegúrate de configurar las URLs de redirección en las consolas de desarrollador de Facebook, Google y Discord
