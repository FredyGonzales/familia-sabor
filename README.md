# 🍽️ La Familia del Sabor — Sitio Web

> Landing page moderna, responsive y de alta conversión para un negocio gastronómico de comida criolla tradicional. Incluye la sub-marca **MilyTejas** (chocotejas artesanales).

![Paleta de colores](https://img.shields.io/badge/palette-lila%20%7C%20morado%20%7C%20rosa-blueviolet)
![Estado](https://img.shields.io/badge/estado-producción-brightgreen)
![Licencia](https://img.shields.io/badge/licencia-privada-red)

---

## 📋 Descripción

Sitio web **one-page** con múltiples secciones para el negocio gastronómico *La Familia del Sabor*, especializado en comida criolla tradicional con delivery en Lima, catering corporativo y la sub-marca de chocotejas artesanales **MilyTejas**.

---

## 🌐 Secciones del sitio

| Sección | Descripción |
|---|---|
| **Header / Navbar** | Navegación fija con logo, links anclados y botón CTA de WhatsApp |
| **Hero** | Portada impactante con gradiente morado-rosa, stats y CTA principal |
| **Platos Criollos** | Grid de tarjetas con filtros (todos / fondos / entradas), lightbox y botones por plato |
| **MilyTejas** | Sección diferenciada para chocotejas artesanales en 6 sabores |
| **Catering & Eventos** | Info de servicios corporativos + formulario que abre WhatsApp |
| **Cobertura** | Mapa embebido de Google Maps + cards de distritos + horarios |
| **Testimonios** | Reseñas de clientes con valoración ⭐⭐⭐⭐⭐ |
| **Contacto** | CTA final con número directo y redes sociales |
| **Footer** | Copyright, links de RRSS y botón flotante de WhatsApp |

---

## 🛠️ Stack tecnológico

- **HTML5** semántico y accesible
- **Tailwind CSS** via CDN (con configuración de tema personalizado)
- **JavaScript Vanilla** – sin dependencias adicionales
- **Font Awesome 6** – iconografía
- **Google Fonts** – Playfair Display + Inter
- **Google Maps Embed** – mapa interactivo de cobertura

---

## ✨ Características

- ✅ Diseño **mobile-first** 100% responsive
- ✅ Botón flotante de **WhatsApp** siempre visible
- ✅ **Lightbox** al hacer clic en platos del menú
- ✅ **Filtrado de menú** por categoría (fondos / entradas)
- ✅ Formulario de catering que arma el mensaje y **abre WhatsApp directo**
- ✅ **Scroll reveal** con IntersectionObserver
- ✅ **Microinteracciones** en hover de tarjetas y botones
- ✅ Navbar con efecto **scroll glassmorphism**
- ✅ Imágenes con `loading="lazy"` para carga rápida
- ✅ Mapa de cobertura embebido en distritos: Breña, Lince, La Victoria y Pueblo Libre

---

## 📂 Estructura del proyecto

```
familia-sabor/
├── index.html          # Sitio completo (one-page)
├── README.md           # Este archivo
└── instrucciones.md    # Brief original del proyecto
```

---

## 🚀 Uso

No requiere instalación ni servidor de desarrollo. Basta con abrir `index.html` en cualquier navegador moderno.

Para producción, se recomienda servir los archivos desde cualquier hosting estático:

- **GitHub Pages** – habilitando Pages en el repositorio
- **Netlify / Vercel** – drag & drop del folder
- **Cualquier servidor Apache/Nginx**

---

## 📞 Datos de contacto del negocio

| Canal | Detalle |
|---|---|
| WhatsApp | +51 934 587 734 |
| Delivery | Breña · Lince · La Victoria · Pueblo Libre |
| Horario L-V | 11:00 am – 8:00 pm |
| Horario Sáb | 10:00 am – 9:00 pm |
| Horario Dom | 10:00 am – 6:00 pm |

---

## 🎨 Paleta de colores

| Token | Hex | Uso |
|---|---|---|
| `lila` | `#E8DEFF` | Fondos suaves |
| `morado` | `#6B35A8` | Color principal, CTA, acentos |
| `rosa` | `#D6457A` | Botones secundarios, MilyTejas |
| `crema` | `#FBF7F0` | Fondo base |

---

## 📝 Notas de desarrollo

- Los emojis actúan como **placeholder visual** en las tarjetas de platos. Se recomienda reemplazar por fotos reales en formato **WebP**.
- El mapa de Google Maps muestra el centro geográfico aproximado de los distritos de cobertura.
- El formulario de catering **no requiere backend**: construye el mensaje y lo envía directamente vía `wa.me`.

---

*Desarrollado con ❤️ para La Familia del Sabor – Lima, Perú*
