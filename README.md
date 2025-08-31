# 🚀AquaClean App - Frontend  

## 📌Descripción  
**AquaClean App** es una **PWA informativa** sobre un proyecto IoT.  
Permite a los usuarios:  
- Conocer información general del proyecto.  
- Acceder a detalles relevantes de la solución IoT.  
- Enviar formularios de contacto a la empresa.  

**Este proyecto está diseñado para brindar una experiencia ligera, moderna y compatible con notificaciones push.**  

## 🛠️Tecnologías utilizadas  

- **Framework:** Next.js  
- **Estilos:** Emotion Styled  
- **Iconos:** FontAwesome  
- **Gestión de datos / API:** Axios  
- **Gestor de paquetes:** Yarn  
- **uuid:** Generación de IDs únicos (ej. para notificaciones o registros temporales).  
- **web-push:** Compatibilidad con notificaciones push vía backend.  

## ⚙️Instalación y ejecución  

```bash
# 1. Clonar el repositorio
git clone https://github.com/EdannyDev/aquaclean-app.git

# 2. Instalar dependencias
yarn install

# 3. Crear archivo de entorno
En la raíz del proyecto, crea .env.local con:
NEXT_PUBLIC_VAPID_PUBLIC_KEY=tu_vapid_public_key

# 4. Ejecutar la aplicación
yarn dev

# 5. Abrir en el navegador
http://localhost:3000

```

## ✨Características principales
- Sitio web informativo tipo PWA.
- Formulario de contacto conectado con el backend.
- Notificaciones push.
- Soporte offline con Service Worker.

## 🔗Enlaces útiles
Backend: https://github.com/EdannyDev/backend-aquaclean

Panel Administrativo: https://github.com/EdannyDev/admin-aquaclean-app
