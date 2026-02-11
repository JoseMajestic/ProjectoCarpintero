# J.Suarez Carpintero – Sitio Web Corporativo

## Descripción general

Sitio web estático para el taller **J.Suarez Carpintero**, especializado en mobiliario a medida, instalación y restauración de piezas de madera. La web actúa como carta de presentación digital con navegación clara, banner principal con imagen de taller, detalle de servicios, filosofía del taller, footer con perfiles sociales y formulario de contacto con validación en cliente.

---

## Objetivos

- Comunicar el catálogo de servicios de carpintería de forma precisa y profesional.
- Mostrar la filosofía artesanal de José Suárez y su equipo, junto con imágenes reales de taller.
- Facilitar el contacto mediante un formulario validado con HTML5 + JS de Bootstrap.
- Mantener un diseño minimalista, responsive y alineado con la estética de carpintería contemporánea.

---

## Estructura del proyecto

```
/jsuarez-arquitecto
├── index.html
├── /html
│   ├── servicios.html
│   ├── sobrenosotros.html
│   └── contacto.html
├── /css
│   └── style.css
├── /js
│   └── form-validation.js
└── /assets
    └── /images
```

---

## Tecnologías

- **HTML5** para el marcado semántico.
- **Bootstrap 5 (CDN)** para layout y componentes.
- **CSS3** (archivo `css/style.css`) para ajustes de tipografía (fuentes locales Montserrat), banner principal e inputs con bordes rectos.
- **JavaScript vanilla** (`js/form-validation.js`) para validar nombre, email, teléfono, asunto y mensaje, mostrando estados `is-valid/is-invalid`.

---

## Contenido principal

- **Inicio**: banner principal con mensaje de carpintería, resumen de servicios y CTA hacia Servicios/Contacto.
- **Servicios**: grid de tarjetas con mobiliario residencial, carpintería comercial, restauración e instalación, usando imágenes locales.
- **Sobre nosotros**: descripción del taller, filosofía de trabajo y equipo.
- **Contacto**: formulario validado (nombre, email, teléfono, asunto, mensaje) + datos directos.

---

## Decisiones de diseño

El diseño es minimalista y propio de un taller de carpintería contemporáneo:

- Bordes rectos y sin sombras decorativas para resaltar las formas.
- Paleta neutra con tonos cálidos que acompañan las texturas de madera.
- Uso exclusivo de componentes Bootstrap para mantener consistencia y mantenimiento simple.
- Formulario centrado con validación HTML5 + JS para asegurar datos de contacto fiables.

---

## Responsive y accesibilidad

La web es totalmente responsive gracias al sistema de grid de Bootstrap, adaptándose correctamente a escritorio, tablet y móvil.

Se han tenido en cuenta buenas prácticas básicas de accesibilidad:
- Uso correcto de etiquetas semánticas.
- Formularios con labels asociados.
- Jerarquía clara de encabezados.
- Inputs con validación nativa del navegador.

---

## Formulario de contacto

El formulario de contacto implementa validación en el lado del cliente mediante HTML5 y Bootstrap:

- Campos obligatorios correctamente marcados.
- Validación de email y teléfono.
- Feedback visual de campos válidos e inválidos.
- El formulario no envía datos reales, ya que el proyecto no incluye backend.



---
