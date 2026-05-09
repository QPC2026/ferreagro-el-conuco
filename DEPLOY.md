# 🚀 Guía de Despliegue

## Opción 1: GitHub Pages (Recomendada — Gratis)

Sigue los pasos del README.md principal.

URL resultante: `https://TU_USUARIO.github.io/ferreagro-el-conuco`

---

## Opción 2: Netlify (Gratis, con HTTPS automático)

1. Ve a [netlify.com](https://netlify.com)
2. Arrastra la carpeta del proyecto al dashboard
3. Listo — Netlify te da una URL instantánea

---

## Opción 3: Vercel (Gratis)

1. Ve a [vercel.com](https://vercel.com)
2. Importa tu repositorio de GitHub
3. Selecciona "Other" como framework
4. Deploy

---

## Opción 4: Hosting tradicional (cPanel, FTP, etc.)

Simplemente sube el archivo `index.html` (y cualquier otro archivo) a la carpeta `public_html/` de tu hosting.

No requiere servidor Node.js ni base de datos — es HTML estático puro.

---

## ⚡ Tips de rendimiento

1. **Comprime las imágenes** antes de subirlas a Imgur/Cloudinary
2. **Usa Cloudinary** con parámetros `w=600,q=auto` para optimización automática
3. **Activa el cache** del navegador en tu hosting
4. Para GitHub Pages: considera usar un **CDN** como jsDelivr para assets externos

---

## 🔒 Seguridad en producción

| Nivel | Recomendación |
|---|---|
| Básico | Cambia la contraseña de admin en Configuración |
| Medio | Implementa autenticación con Firebase Auth |
| Avanzado | Mueve la lógica de negocio a un backend (Node.js + MongoDB) |
