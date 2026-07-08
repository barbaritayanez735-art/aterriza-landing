# 🛫 Aterriza - Landing Page

## Sobre el Proyecto

**Aterriza** es una landing page dedicada a resolver el desafío del primer empleo formal para jóvenes profesionales recién graduados en Ecuador.

### El Problema
- 68% de graduados tienen dificultad encontrando empleo formal en su primer año
- 45% de ofertas junior exigen experiencia previa inexistente
- Muchos terminan en empleos informales, desperdiciando talento académico

### Nuestra Solución
Conectamos jóvenes profesionales ecuatorianos con oportunidades reales a través de:
- Validación de talento
- Mentorías personalizadas
- Bolsa de oportunidades exclusivas
- Acompañamiento integral

---

## 🚀 Características

✅ Diseño moderno y responsive
✅ Mobile-first approach
✅ Formulario de contacto interactivo
✅ Secciones estratégicas para conversión
✅ Animaciones suaves
✅ SEO optimizado
✅ Performance optimizado

---

## 📁 Estructura del Proyecto

```
aterriza-landing/
├── index.html          # Archivo principal HTML
├── styles.css          # Estilos CSS
├── script.js           # JavaScript interactivo
└── README.md           # Este archivo
```

---

## 🎨 Secciones

1. **Navbar** - Navegación sticky con móvil responsivo
2. **Hero** - Sección de impacto con CTA principal
3. **El Problema** - Tarjetas explicativas del desafío
4. **Solución** - 4 pasos del proceso Aterriza
5. **Estadísticas** - Datos clave del mercado laboral
6. **Testimonios** - Historias de éxito de usuarios
7. **Call to Action** - Formulario de registro
8. **Footer** - Información y enlaces

---

## 🛠 Cómo Usar

### Instalación
1. Clona el repositorio
2. Abre `index.html` en tu navegador
3. ¡Listo! No requiere dependencias adicionales

### Personalización

#### Cambiar Colores
Edita las variables CSS en `styles.css`:
```css
:root {
    --primary-color: #2563eb;      /* Azul principal */
    --secondary-color: #06b6d4;    /* Azul secundario */
    --accent-color: #f59e0b;       /* Color de acento */
    /* ... más variables */
}
```

#### Modificar Contenido
Todos los textos están en `index.html` y son fáciles de editar.

#### Conectar Formulario
En `script.js`, busca el evento de envío del formulario y reemplaza con tu endpoint:
```javascript
fetch('/api/contact', {
    method: 'POST',
    body: JSON.stringify(formData),
    headers: { 'Content-Type': 'application/json' }
})
```

---

## 📱 Responsive Design

- ✅ Desktop (1200px+)
- ✅ Tablet (768px - 1199px)
- ✅ Mobile (480px - 767px)
- ✅ Small Mobile (< 480px)

---

## 🎯 Funcionalidades JavaScript

- Menú móvil responsive
- Scroll suave entre secciones
- Validación de formulario
- Animaciones Intersection Observer
- Shadow dinámico en navbar

---

## 🌐 Deployment

### GitHub Pages
1. Habilita GitHub Pages en los settings del repo
2. Selecciona la rama `main`
3. Tu sitio estará en: `https://barbaritayanez735-art.github.io/aterriza-landing`

### Otros Hosting
- Vercel
- Netlify
- Hostinger
- Heroku

---

## 📊 SEO Básico

El proyecto incluye:
- Meta tags descriptivos
- Estructura HTML semántica
- Títulos y descripciones claras
- Mobile-friendly design

### Para mejorar SEO:
1. Agrega Google Analytics
2. Crea sitemap.xml
3. Configura robots.txt
4. Implementa Open Graph tags

---

## 🔗 Integración Futura

- Backend para gestión de registros
- Email notifications
- Dashboard de usuarios
- Sistema de mentorías
- Bolsa de empleos
- Blog de recursos

---

## 👥 Contribuciones

Las contribuciones son bienvenidas. Por favor:
1. Fork el proyecto
2. Crea una rama para tu feature
3. Haz commit de los cambios
4. Push a la rama
5. Abre un Pull Request

---

## 📄 Licencia

Este proyecto está bajo la licencia MIT.

---

## 📞 Contacto

- **Email:** hola@aterriza.ec
- **GitHub:** barbaritayanez735-art

---

## 🙏 Agradecimientos

Gracias por contribuir a la misión de conectar talento joven ecuatoriano con oportunidades reales.

✈️ **¡Que todos puedan aterrizar en su primer empleo!**