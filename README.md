# Portfolio David Bejarano

Portfolio profesional de David Bejarano - Estudiante de Ingeniería de Sistemas en Universidad El Bosque, especializado en análisis de datos, desarrollo de software y soluciones tecnológicas.

## 🎨 Características

- **Diseño Dark Mode Premium**: Estética oscura sofisticada con gradientes animados
- **Fondos Dinámicos**: Efectos visuales con gradientes radiales y animaciones
- **Totalmente Responsive**: Adaptado para todos los dispositivos
- **Animaciones Avanzadas**: Parallax, hover effects, transiciones fluidas
- **CSS Externo**: Archivo style.css separado para fácil personalización
- **100% Estático**: No requiere backend ni dependencias
- **Optimizado**: Carga rápida y rendimiento excepcional
- **Efectos Visuales**: Shimmer effects, gradient text, glassmorphism

## 🚀 Cómo subir a GitHub y GitHub Pages

### Paso 1: Personaliza el contenido

Antes de subir, edita el archivo `index.html` y personaliza:

- **Línea 130-133**: Actualiza tus enlaces de contacto reales:
  - Email personal
  - Tu usuario de GitHub
  - Tu perfil de LinkedIn
  - Tu cuenta de Twitter/X (opcional)
- **Sección "Proyectos"**: Añade descripciones detalladas de tus proyectos reales
- **Agrega tu foto**: En la sección "Sobre mí" (ver instrucciones más abajo)

### Paso 2: Crear repositorio en GitHub

1. Ve a [GitHub](https://github.com) e inicia sesión
2. Haz clic en el botón **"+"** en la esquina superior derecha
3. Selecciona **"New repository"**
4. Nombra el repositorio: `davidbejarano.github.io` (reemplaza "davidbejarano" con tu usuario real de GitHub)
   - Por ejemplo, si tu usuario es "dbejarano", el repositorio debe llamarse: `dbejarano.github.io`
   - **Importante**: Debe ser exactamente tu usuario seguido de `.github.io`
5. Marca como **Public**
6. **NO** inicialices con README (ya tienes uno)
7. Haz clic en **"Create repository"**

### Paso 3: Subir los archivos

**Opción A: Usando Git (Recomendado)**

```bash
# En tu terminal, navega a la carpeta donde está tu index.html y style.css
cd /ruta/a/tu/portfolio

# Inicializa Git
git init

# Añade los archivos
git add .

# Haz el primer commit
git commit -m "Initial commit: Portfolio personal"

# Conecta con tu repositorio de GitHub (reemplaza TUUSUARIO con tu usuario)
git remote add origin https://github.com/TUUSUARIO/TUUSUARIO.github.io.git

# Sube los archivos
git branch -M main
git push -u origin main
```

**Opción B: Subir desde la web de GitHub**

1. En la página de tu repositorio nuevo, haz clic en **"uploading an existing file"**
2. Arrastra los archivos `index.html`, `style.css` y este `README.md`
3. Haz clic en **"Commit changes"**

### Paso 4: Activar GitHub Pages

1. En tu repositorio, ve a **Settings** (Configuración)
2. En el menú lateral, haz clic en **Pages**
3. En **Source**, selecciona la rama **main**
4. Haz clic en **Save**
5. Espera unos minutos (1-5 minutos aproximadamente)

### Paso 5: Visita tu portfolio

Tu portfolio estará disponible en:
```
https://tuusuario.github.io
```

¡Reemplaza "tuusuario" con tu nombre de usuario real de GitHub!

## 📝 Añadir imágenes

Para añadir tu foto y imágenes de proyectos:

1. Crea una carpeta `images` en tu repositorio
2. Sube tus imágenes
3. En el HTML, actualiza:
   - Línea 207: `<div class="about-image"></div>` → `<div class="about-image"><img src="images/tu-foto.jpg" alt="Tu nombre"></div>`
   - Líneas 261, 269, 277: Añade imágenes a los proyectos de manera similar

Ejemplo:
```html
<div class="project-image">
    <img src="images/proyecto1.jpg" alt="Proyecto 1" style="width:100%; height:100%; object-fit:cover;">
</div>
```

## 🎨 Personalización de colores

Edita las variables CSS en las líneas 1-12 del archivo `style.css`:

```css
:root {
    --color-bg: #0f0f0f;              /* Fondo principal oscuro */
    --color-bg-secondary: #1a1a1a;    /* Fondo secundario */
    --color-text: #f5f5f5;            /* Color del texto principal */
    --color-text-muted: #a3a3a3;      /* Texto secundario */
    --color-accent: #e5e5e5;          /* Color de acento */
    --color-accent-bright: #ffffff;   /* Acento brillante */
    --color-border: #2a2a2a;          /* Bordes */
}
```

**Esquemas de color alternativos:**

Modo claro elegante:
```css
--color-bg: #fafaf9;
--color-bg-secondary: #f5f5f4;
--color-text: #1a1a1a;
--color-text-muted: #525252;
--color-accent: #0a0a0a;
--color-accent-bright: #000000;
--color-border: #e5e5e5;
```

## 📱 Redes Sociales

Actualiza los enlaces en la sección de contacto (líneas 379-382):

```html
<a href="mailto:tu@email.com" class="contact-link">Email</a>
<a href="https://github.com/tuusuario" class="contact-link">GitHub</a>
<a href="https://linkedin.com/in/tuusuario" class="contact-link">LinkedIn</a>
<a href="https://twitter.com/tuusuario" class="contact-link">Twitter</a>
```

## 🔄 Actualizar el portfolio

Después de hacer cambios:

```bash
git add .
git commit -m "Descripción de los cambios"
git push
```

Los cambios aparecerán en tu sitio en 1-5 minutos.

## 🌟 Tips adicionales

- **Dominio personalizado**: Puedes usar tu propio dominio en Settings > Pages > Custom domain
- **Analytics**: Añade Google Analytics para ver las visitas
- **SEO**: Actualiza el `<title>` y añade meta tags para mejor posicionamiento
- **Favicon**: Añade un favicon.ico para personalizar el ícono de la pestaña

## 📄 Licencia

Este portfolio es de uso libre. Personalízalo y hazlo tuyo.

---
   ## Portfolio en línea


