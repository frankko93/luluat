# Luluat Landing Page Template

Una landing page moderna y efectiva para joyas de plata artesanales, diseñada para maximizar conversiones con un flujo optimizado: captar atención → mostrar valor → generar acción → construir confianza → facilitar contacto.

## 🚀 Características

- **One-page design** con secciones optimizadas para conversión
- **Responsive design** con breakpoints en 1068px, 768px, 425px, 360px
- **Animaciones AOS** (Animate On Scroll) para efectos de entrada
- **Background fijo** con overlay y efectos parallax
- **Botón flotante de WhatsApp** con animación pulse
- **SEO optimizado** con meta tags completos
- **Google Analytics** integrado
- **Performance optimizada** con lazy loading y debouncing

## 📁 Estructura del Proyecto

```
Luluat/
├── index.html          # Archivo principal HTML
├── styles.css          # Estilos CSS completos
├── script.js           # Funcionalidades JavaScript
├── README.md           # Este archivo
├── logo.png            # Logo de la empresa (agregar)
└── favicon.ico         # Favicon (agregar)
```

## 🛠️ Instalación y Uso

1. **Clona o descarga** los archivos en tu servidor web
2. **Personaliza** el contenido según tu negocio (ver sección de personalización)
3. **Agrega** tu logo y favicon
4. **Configura** Google Analytics con tu ID de medición
5. **Actualiza** los enlaces de WhatsApp y redes sociales
6. **Sube** a tu servidor web

## 🎨 Personalización

### 1. Contenido Principal

Edita `index.html` para cambiar:

- **Título y descripción**: Líneas 6-8
- **Meta tags SEO**: Líneas 10-25
- **Hero section**: Líneas 50-65
- **Video de YouTube**: Línea 75 (reemplaza `dQw4w9WgXcQ` con tu video ID)
- **Texto del CTA**: Línea 85
- **Información de la empresa**: Líneas 95-105
- **Enlaces de redes sociales**: Líneas 115-135

### 2. Estilos Visuales

Edita `styles.css` para personalizar:

- **Colores principales**: Busca `#c0c0c0`, `#ffd700`, `#25d366`
- **Fuentes**: Cambia `'Questrial'` por tu fuente preferida
- **Background**: Línea 30 (reemplaza la URL de la imagen)
- **Tamaños y espaciados**: Ajusta valores de `padding`, `margin`, `font-size`

### 3. Funcionalidades

Edita `script.js` para:

- **Configurar AOS**: Líneas 3-10
- **Agregar tracking personalizado**: Líneas 60-70
- **Modificar animaciones**: Ajusta duraciones y efectos

## 📱 Secciones de la Landing

### 1. Hero Section
- **Propósito**: Captar atención inmediata
- **Elementos**: Título impactante con gradientes, iconos, subtítulo
- **Animación**: fade-down

### 2. Video Section
- **Propósito**: Mostrar valor y credibilidad
- **Elementos**: Video de YouTube con autoplay, aspect ratio 21:9
- **Animación**: zoom-in

### 3. CTA Section
- **Propósito**: Generar acción principal
- **Elementos**: Botón de WhatsApp con efectos hover
- **Animación**: fade-up

### 4. About Section
- **Propósito**: Construir confianza y credibilidad
- **Elementos**: Logo, descripción, firma
- **Animación**: fade-right (logo), fade-left (contenido)

### 5. Social Media Section
- **Propósito**: Facilitar contacto y seguimiento
- **Elementos**: 4 botones de redes sociales
- **Animación**: zoom-in escalonadas

### 6. Footer
- **Propósito**: Información legal
- **Elementos**: Copyright y créditos

## 🔧 Configuración Técnica

### Google Analytics
1. Reemplaza `GA_MEASUREMENT_ID` en `index.html` (línea 35) con tu ID real
2. O elimina las líneas 34-40 si no usas GA

### WhatsApp
1. Reemplaza `1234567890` en todos los enlaces de WhatsApp con tu número real
2. Personaliza el mensaje predefinido en los enlaces

### Video de YouTube
1. Reemplaza `dQw4w9WgXcQ` con el ID de tu video
2. Ajusta parámetros como `autoplay`, `mute`, `loop` según necesites

### Redes Sociales
Actualiza los enlaces en las líneas 115-135 con tus perfiles reales:
- Instagram: `https://instagram.com/tu-usuario`
- WhatsApp: `https://wa.me/tu-numero`
- TikTok: `https://tiktok.com/@tu-usuario`
- YouTube: `https://youtube.com/@tu-canal`

## 📊 Optimización SEO

La landing incluye:
- Meta tags completos (title, description, keywords)
- Open Graph tags para redes sociales
- Twitter Cards
- Estructura semántica HTML5
- URLs amigables (configurar en servidor)

## 🎯 Flujo de Conversión

1. **Captar atención**: Hero section impactante
2. **Mostrar valor**: Video demostrativo
3. **Generar acción**: CTA principal
4. **Construir confianza**: About section
5. **Facilitar contacto**: Social media + WhatsApp float

## 📱 Responsive Design

Breakpoints implementados:
- **Desktop**: > 1068px
- **Tablet**: 768px - 1068px
- **Mobile**: 425px - 768px
- **Small Mobile**: < 425px

## 🚀 Performance

Optimizaciones incluidas:
- Lazy loading para imágenes
- Debouncing en eventos de scroll
- Intersection Observer para animaciones
- Compresión de recursos (configurar en servidor)
- CDN para librerías externas

## 🛡️ Seguridad

- Enlaces externos con `target="_blank"`
- Validación de entrada (si se agregan formularios)
- HTTPS recomendado para producción

## 📈 Analytics y Tracking

Configurado para trackear:
- Clicks en CTAs
- Interacciones con botones sociales
- Scroll depth (configurable)
- Tiempo en página

## 🔄 Reutilización

Este template está diseñado para ser fácilmente reutilizable:

1. **Cambia contenido**: Textos, imágenes, enlaces
2. **Ajusta colores**: Variables CSS principales
3. **Modifica secciones**: Agrega o quita según necesites
4. **Personaliza animaciones**: Ajusta AOS según tu marca

## 📞 Soporte

Para personalizaciones avanzadas o soporte técnico, contacta al equipo de desarrollo.

---

**Nota**: Recuerda reemplazar todos los placeholders (números de teléfono, enlaces, IDs) con información real antes de publicar. 