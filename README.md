🚀AquaClean App - Frontend

📌Descripción
Una Web Informativa sobre un proyecto IoT, desarrollado como una PWA.
Permite a los usuarios conocer el proyecto, acceder a información general y enviar formularios de contacto a la empresa.

🛠️Tecnologías utilizadas
-Framework: Next.js
-Estilos: Emotion Styled
-Iconos: FontAwesome
-Llamadas a API: Axios
-Gestor de paquetes: Yarn
-uuid: generar IDs únicos (ej. para registros temporales y notificaciones).
-web-push: compatibilidad con notificaciones push vía backend.

⚙️Instalación y ejecución

1.-Clonar el repositorio:
git clone https://github.com/EdannyDev/aquaclean-app.git

2.-Instalar dependencias:
yarn install

3.-Crear un archivo .env.local con:
NEXT_PUBLIC_VAPID_PUBLIC_KEY=<tu_vapid_public_key>

4.-Ejecutar la aplicación:
yarn dev

5.-Abrir en el navegador:
http://localhost:3000

✨Características principales:
-Sitio web informativo tipo PWA.
-Formulario de contacto conectado con el backend.
-Notificaciones push.
-Soporte offline con Service Worker.

🔗Enlaces útiles
Backend: https://github.com/EdannyDev/backend-aquaclean
Panel Administrativo: https://github.com/EdannyDev/admin-aquaclean-app