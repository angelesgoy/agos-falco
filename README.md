# Agos Falco — Web Personal & Media Kit Interactivo

Sitio web oficial y Media Kit digital para **Agostina Falcone (@kydahh_)**, estratega de contenidos y creadora de contenido en TikTok (+8 años con Disney, Marvel, Star Wars y National Geographic).

---

## 🌟 Características Principales

1. **Ultra Liviano y Rápido:** Carga instantánea, sin servidores complejos ni consumo excesivo de almacenamiento en GitHub.
2. **Galería de Videos 9:16 (TikTok & Reels):** Visualización en formato vertical oficial con reproducción interactiva en modal y filtros por categorías (*Brand Collabs, Moda & SHEIN, Viajes & Japón, Storytelling*).
3. **Casos de Éxito & Estrategia:** Fichas interactivas con Desafío, Solución, Rol y Resultados (Disney LATAM, Star Wars, Toy Story, Always-On).
4. **Mi Proceso Editorial (01 al 05):** De la idea al contenido (Descubrir, Definir, Crear, Ejecutar, Optimizar).
5. **Catálogo de Servicios:** *Strategy Consultancy*, *Content Creation* y *Advisory*.
6. **Descarga de Media Kit en PDF:** Generación nativa y dinámica de PDF con un solo clic.
7. **Mobile Dock & Responsive Total:** Experiencia nativa y fluida en cualquier smartphone, tablet o computadora de escritorio.

---

## 🚀 Cómo Probar Localmente

Puedes abrir directamente el archivo `index.html` en tu navegador favorito haciendo doble clic, o levantando un servidor local ligero:

```bash
# Opción 1: Con npx
npx serve .

# Opción 2: Con Python
python -m http.server 3000
```

Luego abre tu navegador en `http://localhost:3000`.

---

## 🌐 Cómo Desplegar Gratis en GitHub Pages

1. Sube este proyecto a tu repositorio de GitHub (ejemplo: `https://github.com/tu-usuario/agos-falco`).
2. En GitHub, ve a **Settings** > **Pages**.
3. En la sección **Build and deployment**, selecciona:
   * **Source:** `Deploy from a branch`
   * **Branch:** `main` (o `master`) / `/ (root)`
4. Haz clic en **Save**. En un minuto, tu web estará online en `https://tu-usuario.github.io/agos-falco/`.

---

## 📹 Cómo Agregar o Modificar Videos de TikTok

En `index.html`, dentro de la sección `<div class="videos-grid" id="videosContainer">`, cada video está estructurado con el siguiente bloque:

```html
<div class="video-card-vertical" data-category="brand shein">
    <div class="video-preview-box">
        <img src="URL_DE_PORTADA" alt="Título" class="video-thumbnail">
        <div class="video-overlay-gradient">
            <span class="video-top-badge">Colaboración</span>
            <button onclick="playTikTokVideo('ID_DEL_VIDEO', 'Título')" class="video-play-btn-circle">
                <svg viewBox="0 0 24 24"><polygon points="5 3 19 12 5 21 5 3"></polygon></svg>
            </button>
            <div class="video-bottom-info">
                <span class="video-meta-tag">#Hashtag</span>
                <h4 class="video-caption-title">Descripción del video</h4>
            </div>
        </div>
    </div>
    <div class="video-card-footer">
        <a href="https://www.tiktok.com/@kydahh_/video/ID_DEL_VIDEO" target="_blank" rel="noopener" class="video-footer-link">
            Ver en TikTok
        </a>
    </div>
</div>
```

---

## 📬 Contacto
* **Email:** [hello.agosfalco@gmail.com](mailto:hello.agosfalco@gmail.com)
* **TikTok:** [@kydahh_](https://www.tiktok.com/@kydahh_)
* **Instagram:** [@agosfalco](https://www.instagram.com/agosfalco/)
* **LinkedIn:** [in/agostinafalcone](https://www.linkedin.com/in/agostinafalcone/)
