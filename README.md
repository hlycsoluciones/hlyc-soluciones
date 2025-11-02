# HLyC Soluciones — Web estática gratuita

Este paquete contiene una **web de una sola página** lista para publicar gratis con **GitHub Pages** o servicios similares (Netlify / Vercel).

## 📁 Estructura
- `index.html` — la página principal
- `styles.css` — estilos
- `logo.svg` — logotipo simple
- `README.md` — estas instrucciones

## 🚀 Publicar gratis con GitHub Pages (recomendado)
1. Crea una cuenta en https://github.com (si no tienes).
2. Crea un repositorio nuevo llamado, por ejemplo, `hlyc-soluciones`.
3. Sube estos archivos (`index.html`, `styles.css`, `logo.svg`, `README.md`).
4. Ve a **Settings → Pages** y en “Build and deployment” elige **Deploy from a branch**.
5. En “Branch” selecciona `main` y la carpeta raíz `/` y guarda.
6. Tu web estará disponible en una URL del tipo:  
   `https://TU-USUARIO.github.io/hlyc-soluciones`

> Para cambiar el dominio más adelante (por ejemplo, `hlyc.es` o `hlycsoluciones.es`), compra el dominio y configura un **CNAME** hacia tu GitHub Pages siguiendo la guía oficial de GitHub.

## 📨 Contacto por email
El formulario abre el **cliente de correo** con `mailto:`. Cambia el email provisional en `index.html` (sección Contacto) por tu dirección real, por ejemplo `info@hlyc.es` cuando la tengas.

## ✏️ Personalización rápida
- Cambia textos en `index.html` (servicios, proyectos, horarios).
- Ajusta colores desde `styles.css` (ver variables en cabecera de cada bloque).
- Sustituye `logo.svg` por tu logotipo cuando dispongas de uno definitivo.

## 🔒 Privacidad & cookies
Al ser una web estática **no instala cookies** ni rastreadores por defecto.

## 🧰 Alternativas de publicación
- **Netlify**: arrastra esta carpeta a https://app.netlify.com/drop y tendrás `https://algo.netlify.app`
- **Vercel**: sube el repositorio y despliega. Obtendrás `https://algo.vercel.app`

¡Listo! Edita el texto, súbelo y tendrás tu web pública en minutos.
