# 🌟 Lumicore

**Lumicore** es una plataforma de comercio electrónico moderna desarrollada con **Next.js**, **MongoDB Atlas** y **Tailwind CSS**.  
Su objetivo es ofrecer una experiencia fluida, rápida y escalable tanto para usuarios como para vendedores, integrando herramientas de última generación como **Cloudinary** e **Inngest** para optimizar el rendimiento y la automatización de procesos.

---

## 🚀 Descripción general

Lumicore redefine la forma en que los usuarios interactúan con un e-commerce: combina diseño intuitivo, rendimiento de alto nivel y arquitectura modular.  
La aplicación permite explorar productos, gestionarlos desde un panel de vendedor, añadir artículos al carrito, realizar pedidos y hacer seguimiento de cada transacción.

Todo esto se apoya en APIs seguras y eficientes creadas con **Next.js App Router**, y una infraestructura pensada para escalar fácilmente con integraciones externas.

---

## 💎 Funcionalidades clave

- 🛍️ **Gestión de productos:** agregar, editar y listar artículos en tiempo real.
- 🛒 **Carrito inteligente:** persistencia de datos, actualización dinámica y cálculo automático.
- 📦 **Órdenes:** creación, consulta y seguimiento de pedidos en diferentes estados.
- 👤 **Usuarios y direcciones:** perfiles con múltiples direcciones y datos personales protegidos.
- 🏪 **Panel de vendedor:** gestión avanzada de productos, ventas y pedidos recibidos.
- ☁️ **Integraciones externas:**
  - **Cloudinary** → almacenamiento y optimización de imágenes.
  - **Inngest** → flujos de automatización y eventos backend.
  - **MongoDB Atlas** → base de datos segura y escalable.

---

## 🧰 Tecnologías principales

| Tipo                          | Tecnologías                   |
| ----------------------------- | ----------------------------- |
| **Frontend**                  | Next.js, React, Tailwind CSS  |
| **Backend**                   | Node.js, API Routes (Next.js) |
| **Base de datos**             | MongoDB Atlas                 |
| **Automatización**            | Inngest                       |
| **Almacenamiento multimedia** | Cloudinary                    |
| **Control de calidad**        | ESLint, PostCSS               |

---

## ⚙️ Configuración rápida

1️⃣ **Clona el proyecto**

```bash
git clone https://github.com/tuusuario/lumicore.git
cd lumicore
2️⃣ Instala las dependencias

bash
Copiar código
npm install
3️⃣ Crea un archivo .env

env
Copiar código
MONGODB_URI='mongodb+srv://<user>:<password>@cluster.mongodb.net/'
CLOUDINARY_CLOUD_NAME='tu_cloud_name'
CLOUDINARY_API_KEY='tu_api_key'
CLOUDINARY_API_SECRET='tu_api_secret'
INNGEST_SIGNING_KEY='tu_inngest_signing_key'
INNGEST_EVENT_KEY='tu_inngest_event_key'
4️⃣ Ejecuta el proyecto

bash
Copiar código
npm run dev
Accede a 👉 http://localhost:3000

🧩 Scripts disponibles
Comando	Acción
npm run dev	Inicia el entorno de desarrollo
npm run build	Genera la versión de producción
npm start	Ejecuta el servidor en modo producción
npm run lint	Analiza el código con ESLint

🧠 Integraciones destacadas
Cloudinary: gestiona imágenes de productos optimizadas en la nube.

Inngest: maneja tareas y flujos automatizados basados en eventos (por ejemplo, pedidos o notificaciones).

MongoDB Atlas: almacena todos los datos de productos, usuarios y órdenes de manera segura y escalable.

💡 Buenas prácticas
No compartas tu archivo .env.

Ejecuta npm run lint antes de cada commit.

Usa Vercel o Render para desplegar fácilmente el proyecto.

Activa HTTPS y variables seguras en producción.

📜 Licencia
Este proyecto está licenciado bajo MIT License.
Puedes usarlo y modificarlo libremente, siempre atribuyendo su origen.

✨ Autores
Proyecto desarrollado por el equipo de Lumicore.
Inspirado en una arquitectura modular y orientada a microservicios para ofrecer velocidad, seguridad y escalabilidad.

💬 “Lumicore: impulsando el comercio digital con innovación y simplicidad.”
```
