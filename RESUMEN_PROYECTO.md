# Sitio web — Jorge Trejos (Tattoo Artist)

Resumen de lo realizado y datos clave del proyecto. Úsalo para retomar el trabajo con cualquier IA.

## Carpeta del proyecto
- Ruta: `/home/jack/Escritorio/sitio-jorge-trejos/`
- Página principal: `index.html`
- Imágenes: `img/` (`logo.png`, `favicon.png`, `jorge.jpg`, `portafolio/`)
- Portafolio automático: `img/portafolio/obra1.jpg` … `obra30.jpg` (acepta .jpg, .png, .jpeg). Las fotos que agregues ahí aparecen solas en la web.

## Datos de contacto del cliente
- Correo del artista: **jtre301084@gmail.com**
- WhatsApp: **+506 7026 0263** (enlace: `https://wa.me/50670260263`)

## Formulario de contacto (Formspree)
- Servicio: Formspree (plan gratis, 50 envíos al mes)
- Enlace del formulario: **`https://formspree.io/f/mvkprwyr`**
- Cómo funciona: cuando alguien llena el formulario en la web, Formspree envía los datos al correo jtre301084@gmail.com. Los datos también se guardan en el navegador del visitante (localStorage, clave `clientes`) como respaldo.
- Para revisar envíos o activar notificaciones: entrar a https://formspree.io, formulario `mvkprwyr`, pestaña Forms.

## Marca y diseño
- Nombre: Jorge Trejos (tatuador, realismo black & grey, "alta gama")
- Propuesta de valor: "23 años de precisión, te llevas una obra original, solo existe una en el mundo"
- Slogan: "Diseño único, una sola edición"
- Paleta: `#0A0A0C` (negro) · `#55555C` (gris pizarra) · `#FAFAF7` (blanco) · `#5A1860` (morado acento) · `#C6C6CD` (plata)
- Tipografías: Manrope (títulos, instalada en `~/.fonts/Manrope-Variable.ttf`) y Poppins (texto)
- Logo: `img/logo.png` (versión optimizada de `logo_jorge_trejos_mejorado.png`); logo en header 72px, en hero 210px

## Secciones de la página
1. Header fijo con logo y navegación
2. Hero: logo + "REALISMO BLACK & GREY DE ALTA GAMA" + slogan + botón "Agenda tu cita"
3. Propuesta de valor
4. Fortalezas (6 fichas)
5. Portafolio (grilla automática)
6. Sobre mí (foto + texto)
7. Contacto (formulario captura nombre/correo)
8. Footer con WhatsApp y correo

## Pendiente / próximos pasos
- [ ] Subir la web a internet gratis (GitHub Pages o Netlify)
- [ ] Si se usa GitHub Pages, el repo debe llamarse `<usuario>.github.io` o activar Pages desde Settings
