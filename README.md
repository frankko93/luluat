# Landing Page Luluat - Joyería Premium

Landing page profesional diseñada para captar leads en el negocio de cadenas de oro 18K, optimizada para jóvenes influencers argentinos de 20-35 años.

## 🎯 Características Principales

- **Diseño responsivo** adaptado a móviles, tablets y desktop
- **Optimizada para conversión** con llamados a la acción claros
- **Formulario de captación de leads** con descuento exclusivo del 15%
- **Sección de video** para contenido de valor
- **Enlaces a tienda virtual** estratégicamente ubicados
- **Área "sobre nosotros"** con logo y descripción
- **Redes sociales** con el tamaño apropiado
- **Colores elegantes y actuales** (dorado premium)
- **Botón flotante de WhatsApp** con animación

## 🚀 Instalación y Uso

1. **Descarga los archivos:**
   - `index.html` - Estructura principal
   - `styles.css` - Estilos y diseño
   - `README.md` - Este archivo de instrucciones

2. **Abre la página:**
   - Simplemente abre `index.html` en tu navegador
   - La página está lista para usar sin instalaciones adicionales

## ✏️ Personalización

### 1. Reemplazar Contenido de Marca

#### Logo y Nombre de Empresa
En `index.html`, busca la sección del logo (líneas 17-20):
```html
<div class="logo">
    <h2>LULUAT</h2>
    <span class="logo-subtitle">Premium Jewelry</span>
</div>
```

#### Información de Contacto
Actualiza los datos de contacto en el footer (líneas 245-253):
```html
<div class="footer-section">
    <h4>Contacto</h4>
    <p>Email: info@luluat.com</p>
    <p>WhatsApp: +54 9 11 xxxx-xxxx</p>
</div>
```

### 2. Configurar Enlaces

#### Enlaces de Redes Sociales
Actualiza los enlaces en la sección social (líneas 211-230):
```html
<a href="https://instagram.com/tu_usuario" class="social-link instagram">
<a href="https://facebook.com/tu_pagina" class="social-link facebook">
<a href="https://tiktok.com/@tu_usuario" class="social-link tiktok">
```

#### WhatsApp Flotante
Cambia el número en el botón flotante (línea 264):
```html
<a href="https://wa.me/5491xxxxxxx" target="_blank">
```

#### Enlaces de Tienda
Reemplaza los "#" con las URLs reales de tu tienda en las secciones de shop.

### 3. Integrar Video

Reemplaza el placeholder del video (líneas 79-86) con tu video real:
```html
<!-- Opción YouTube -->
<iframe width="100%" height="450" src="https://www.youtube.com/embed/TU_VIDEO_ID" frameborder="0" allowfullscreen></iframe>

<!-- Opción Vimeo -->
<iframe src="https://player.vimeo.com/video/TU_VIDEO_ID" width="100%" height="450" frameborder="0" allowfullscreen></iframe>
```

### 4. Configurar Formulario de Leads

#### Integración con MailChimp, ConvertKit, etc.
Modifica el JavaScript al final del HTML (líneas 271-290) para conectar con tu servicio:

```javascript
// Ejemplo para MailChimp
document.getElementById('leadForm').addEventListener('submit', async function(e) {
    e.preventDefault();
    
    const formData = new FormData(this);
    const data = Object.fromEntries(formData);
    
    // Enviar a tu servicio de email marketing
    try {
        const response = await fetch('TU_ENDPOINT_API', {
            method: 'POST',
            headers: {'Content-Type': 'application/json'},
            body: JSON.stringify(data)
        });
        
        if (response.ok) {
            alert('¡Gracias! Te hemos enviado tu código de descuento.');
            this.reset();
        }
    } catch (error) {
        console.error('Error:', error);
    }
});
```

### 5. Personalizar Colores

En `styles.css`, modifica las variables de color (líneas 19-29):
```css
:root {
    --primary-gold: #d4af37;     /* Color dorado principal */
    --primary-dark: #b8941f;     /* Dorado oscuro */
    --accent-gold: #f4e4a6;      /* Dorado claro/accent */
    --text-dark: #2c2c2c;        /* Texto principal */
    --text-light: #6b6b6b;       /* Texto secundario */
    /* Cambia estos valores por tus colores de marca */
}
```

### 6. Añadir Font Awesome

Para que los iconos funcionen correctamente, reemplaza la línea 8 del HTML:
```html
<script src="https://kit.fontawesome.com/TU_KIT_ID.js" crossorigin="anonymous"></script>
```

Obtén tu kit gratuito en [fontawesome.com](https://fontawesome.com)

## 📱 Optimización Mobile

La página está completamente optimizada para móviles con:
- Diseño responsive que se adapta a cualquier pantalla
- Botones de tamaño táctil adecuado
- Formularios fáciles de completar en móvil
- Navegación simplificada

## 🎨 Paleta de Colores

- **Dorado Principal:** #d4af37 (elegante y premium)
- **Dorado Oscuro:** #b8941f (hover states)
- **Dorado Claro:** #f4e4a6 (acentos)
- **Gris Oscuro:** #2c2c2c (texto principal)
- **Gris Claro:** #6b6b6b (texto secundario)

## 📈 Optimizaciones para Conversión

### Elementos Implementados:
- ✅ Headline que llama la atención
- ✅ Propuesta de valor clara
- ✅ Prueba social implícita
- ✅ Urgencia y escasez (descuento limitado)
- ✅ Formulario simple y directo
- ✅ CTAs contrastantes y visibles
- ✅ Reducción de fricción en el formulario
- ✅ Diseño limpio sin distracciones

### Métricas a Monitorear:
- Tasa de conversión del formulario principal
- Tiempo en página
- Scroll depth
- Clics en botones CTA
- Rebote desde móviles

## 🔧 Soporte Técnico

### Compatibilidad de Navegadores:
- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

### Rendimiento:
- Peso total: ~15KB (sin imágenes)
- Tiempo de carga: <2 segundos
- Optimizada para Core Web Vitals

## 📞 Próximos Pasos Recomendados

1. **Configurar Analytics:** Añadir Google Analytics o similar
2. **Integrar CRM:** Conectar formulario con tu sistema CRM
3. **A/B Testing:** Probar diferentes headlines y CTAs
4. **Imágenes reales:** Reemplazar placeholders con fotos profesionales
5. **SEO:** Optimizar meta tags para búsquedas locales
6. **Certificado SSL:** Asegurar la página con HTTPS

---

**¿Necesitas ayuda con la configuración?** 
Contacta al desarrollador para soporte adicional o personalizaciones específicas. 