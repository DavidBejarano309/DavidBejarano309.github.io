# 🚀 Guía Rápida de Personalización - David Bejarano

## ✅ Lo que ya está configurado:

- ✓ Nombre: David Bejarano
- ✓ Título: Ingeniero de Sistemas & Datos
- ✓ Universidad: Universidad El Bosque
- ✓ Enfoque: Análisis de datos, desarrollo de software
- ✓ Habilidades técnicas de ingeniero de datos
- ✓ Proyectos orientados a datos y desarrollo

## 📝 Lo que DEBES personalizar antes de subir:

### 1. Enlaces de Contacto (IMPORTANTE)

Abre `index.html` y busca la línea 130-133 aproximadamente:

```html
<a href="mailto:davidbejarano@ejemplo.com" class="contact-link">Email</a>
<a href="https://github.com/davidbejarano" class="contact-link">GitHub</a>
<a href="https://linkedin.com/in/davidbejarano" class="contact-link">LinkedIn</a>
```

Cambia por tus enlaces reales:
- **Email**: tu email personal o universitario
- **GitHub**: tu usuario real de GitHub
- **LinkedIn**: tu perfil real de LinkedIn
- **Twitter**: opcional, puedes eliminarlo si no lo usas

### 2. Proyectos

Las descripciones actuales son genéricas. Cámbialas por tus proyectos reales:

**Ejemplo de cómo editar:**

```html
<h3>Tu Proyecto Real</h3>
<p class="project-description">Descripción específica de lo que hiciste, tecnologías usadas, y resultados obtenidos.</p>
```

Ideas de proyectos para incluir:
- Proyectos de la universidad
- Análisis de datos que hayas hecho
- Aplicaciones web desarrolladas
- Scripts de automatización
- Trabajos de machine learning
- Cualquier código en GitHub

### 3. Agregar tu Foto (Opcional pero recomendado)

**Paso 1:** Guarda una foto profesional como `foto.jpg` en la misma carpeta que `index.html`

**Paso 2:** Busca en `index.html` la línea 47:
```html
<div class="about-image"></div>
```

**Paso 3:** Cámbiala por:
```html
<div class="about-image">
    <img src="foto.jpg" alt="David Bejarano" style="width:100%; height:100%; object-fit:cover;">
</div>
```

### 4. Imágenes de Proyectos (Opcional)

Si tienes capturas de tus proyectos:

1. Crea una carpeta `images` junto a `index.html`
2. Guarda las imágenes como `proyecto1.jpg`, `proyecto2.jpg`, etc.
3. En cada proyecto, busca:
   ```html
   <div class="project-image"></div>
   ```
4. Cámbialo por:
   ```html
   <div class="project-image">
       <img src="images/proyecto1.jpg" alt="Proyecto" style="width:100%; height:100%; object-fit:cover;">
   </div>
   ```

## 🎯 Sugerencias de Mejora

### Añade más secciones (opcional):

**1. Educación:**
```html
<section class="education" style="padding: 8rem 4rem; max-width: 1200px; margin: 0 auto;">
    <h2 class="section-title">Educación</h2>
    <div style="border-left: 2px solid var(--color-border); padding-left: 2rem; margin-top: 3rem;">
        <h3 style="font-family: var(--font-display); font-size: 1.5rem; margin-bottom: 0.5rem;">
            Ingeniería de Sistemas
        </h3>
        <p style="color: var(--color-text-muted); margin-bottom: 1rem;">
            Universidad El Bosque | 2020 - Presente
        </p>
        <p style="color: var(--color-text-muted);">
            Enfoque en análisis de datos, desarrollo de software y arquitectura de sistemas.
        </p>
    </div>
</section>
```

**2. Certificaciones:**
Si tienes certificaciones (Coursera, Udemy, etc.), añádelas:
```html
<section class="certifications" style="padding: 8rem 4rem; max-width: 1200px; margin: 0 auto;">
    <h2 class="section-title">Certificaciones</h2>
    <ul style="list-style: none; margin-top: 3rem;">
        <li style="padding: 1rem; border: 1px solid var(--color-border); margin-bottom: 1rem;">
            <strong>Python for Data Science</strong> - Coursera
        </li>
        <li style="padding: 1rem; border: 1px solid var(--color-border); margin-bottom: 1rem;">
            <strong>Machine Learning Specialization</strong> - Stanford Online
        </li>
    </ul>
</section>
```

## 🔗 Configurar el Repositorio de GitHub

Cuando crees el repositorio en GitHub, nómbralo:
```
tuusuariodegithub.github.io
```

Por ejemplo:
- Si tu usuario es `davidb123` → `davidb123.github.io`
- Si tu usuario es `dbejarano` → `dbejarano.github.io`

## ✨ Tips Finales

1. **Mantén tus proyectos actualizados**: Cada vez que termines un proyecto nuevo, añádelo
2. **Sube tu código a GitHub**: Los reclutadores buscarán tu GitHub
3. **Agrega links a proyectos**: Si tus proyectos están en GitHub, añade el link:
   ```html
   <a href="https://github.com/tuusuario/proyecto" target="_blank" style="color: var(--color-accent-bright); text-decoration: none;">
       Ver código →
   </a>
   ```
4. **Actualiza regularmente**: Cada semestre, revisa y actualiza tu portfolio
5. **LinkedIn**: Asegúrate de que tu LinkedIn esté completo antes de enlazarlo

## 📧 Ejemplo de Email Profesional

Para el portfolio, te recomiendo usar:
- Tu email universitario de El Bosque
- Un email profesional tipo: `david.bejarano@gmail.com` o `davidbejarano.dev@gmail.com`

Evita emails como: `el_tigrex123@hotmail.com`

---

**¡Tu portfolio está listo para impresionar reclutadores y empresas! 🚀**
