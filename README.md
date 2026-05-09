# 🌾 Ferreagro El Conuco

> Sistema de catálogo, carrito de compras y administración para venta de alimentos agrícolas y para animales.

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-green?style=flat-square&logo=github)](https://TU_USUARIO.github.io/ferreagro-el-conuco)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/es/docs/Web/HTML)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/es/docs/Web/JavaScript)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)](https://tailwindcss.com)

---

## ✨ Características

### 🛒 Catálogo Público
- Catálogo de productos con filtros por categoría, tipo de venta y búsqueda
- Tarjetas de producto con imágenes reales por categoría
- Carrito de compras con descuentos por puntos de fidelización
- Checkout con Pago Móvil (Bancrecer)
- Envío gratis en municipio García (compras > $20)

### 👤 Programa de Afiliados
- Registro gratuito de clientes
- Acumulación de puntos por compra
- Canje de puntos por descuentos ($5, $12, $30)
- Consulta de saldo por teléfono

### 🔐 Panel de Administración
- **Dashboard** con métricas de ventas, ganancias, clientes y stock
- **Inventario** con CRUD completo de productos
- **Libro de Ventas** con detalle de productos por orden
- **Libro de Compras** con registro de proveedores
- **Clientes Afiliados** con congelación/reactivación de cuentas
- **Promociones** con precios especiales
- **Balance G/P** con ganancias brutas, netas y gastos operativos
- **Nota de Despacho** generable como imagen, PDF, WhatsApp o email
- **Activar/Desactivar productos** para pausar ventas temporalmente

---

## 🚀 Despliegue en GitHub Pages

### Paso 1: Crear el repositorio

1. Ve a [github.com/new](https://github.com/new)
2. Nombre del repositorio: `ferreagro-el-conuco`
3. Visibilidad: **Público** (necesario para GitHub Pages gratuito)
4. Clic en **Create repository**

### Paso 2: Subir los archivos

Opción A — Por línea de comandos (recomendado):

```bash
git clone https://github.com/TU_USUARIO/ferreagro-el-conuco.git
cd ferreagro-el-conuco
# Copia aquí todos los archivos del proyecto
git add .
git commit -m "Initial commit: Ferreagro El Conuco v1.0"
git push origin main
```

Opción B — Por interfaz web:
1. En tu repositorio nuevo, clic en **"uploading an existing file"**
2. Arrastra los archivos o selecciona `index.html`
3. Clic en **Commit changes**

### Paso 3: Activar GitHub Pages

1. En tu repositorio, ve a **Settings** → **Pages**
2. En "Source", selecciona **Deploy from a branch**
3. Selecciona la rama `main` y carpeta `/ (root)`
4. Clic en **Save**
5. Espera 1-2 minutos y tu app estará en:
   ```
   https://TU_USUARIO.github.io/ferreagro-el-conuco
   ```

---

## 🔑 Acceso al Panel de Administración

- Contraseña por defecto: `PrismaCore2026`
- Puedes cambiarla en **Admin → Configuración**

---

## 📁 Estructura del Proyecto

```
ferreagro-el-conuco/
├── index.html          # Aplicación completa (HTML + CSS + JS)
├── README.md           # Este archivo
├── LICENSE             # Licencia MIT
└── .gitignore          # Archivos ignorados por Git
```

> **Nota:** Esta es una aplicación **Single File Application**. Todo el código (HTML, CSS, JavaScript, lógica de negocio y datos) vive en un solo archivo `index.html`. Los datos se almacenan en `localStorage` del navegador.

---

## 🛠️ Tecnologías

- **HTML5** — Estructura semántica
- **Tailwind CSS (CDN)** — Estilos utilitarios
- **Vanilla JavaScript** — Lógica de negocio completa
- **Font Awesome (CDN)** — Iconografía
- **html2canvas + jsPDF (CDN)** — Generación de notas de despacho
- **localStorage** — Persistencia de datos local

---

## ⚠️ Notas Importantes

### Persistencia de datos
Los datos (productos, órdenes, clientes, compras) se guardan en el **localStorage** del navegador. Esto significa:
- ✅ Los datos persisten entre sesiones en el mismo dispositivo/navegador
- ❌ Los datos **no se sincronizan** entre dispositivos automáticamente
- ❌ Si el usuario borra el caché del navegador, los datos se pierden

Para producción con múltiples dispositivos, considera:
- Firebase (backend gratuito de Google)
- Supabase (alternativa open source)
- JSONBin.io (API simple para JSON)

### Seguridad
- La contraseña de admin está en texto plano en el código (apropiado para uso local)
- Para producción pública, considera implementar autenticación real

---

## 📝 Changelog

### v1.0
- Catálogo con filtros y búsqueda
- Carrito de compras con checkout
- Panel de administración completo
- Programa de afiliados con puntos
- Nota de desapacho (imagen, PDF, WhatsApp, email)
- Gestión de activación/desactivación de productos
- Imágenes por categoría (Unsplash)
- Logo SVG minimalista propio

---

## 📞 Contacto

**Ferreagro El Conuco**
- 📱 +58 412-3521113
- 📧 ferreagroelconuco@gmail.com
- 📍 Municipio García, Venezuela

---

## 📄 Licencia

Este proyecto está bajo la licencia [MIT](LICENSE).

```
MIT License

Copyright (c) 2026 Ferreagro El Conuco

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND...
```
