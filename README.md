# Portfolio — Boris Baldominos

Portfolio personal de una sola página (`index.html`), listo para publicar con **GitHub Pages**.

## 📁 Estructura

```
portfolio/
├── index.html
└── assets/
    └── avatar.jpeg   ← tu logo personal
```

## 🚀 Publicarlo en GitHub Pages

1. Crea un repositorio nuevo en GitHub, por ejemplo `portfolio` (puede ser público).
2. Sube estos dos elementos (`index.html` y la carpeta `assets/`) a la raíz del repo:
   ```bash
   git init
   git add .
   git commit -m "Portfolio inicial"
   git branch -M main
   git remote add origin https://github.com/Borr88/portfolio.git
   git push -u origin main
   ```
3. En GitHub, entra al repo → **Settings → Pages**.
4. En "Build and deployment", selecciona **Deploy from a branch**, rama `main`, carpeta `/ (root)`. Guarda.
5. En un par de minutos tu portfolio estará en:
   `https://borr88.github.io/portfolio/`

Esa es la URL que puedes poner en tu CV o compartir como tarjeta de presentación.

## ✏️ Cosas que te recomiendo revisar/editar antes de publicar

- **Enlace de LinkedIn**: en la sección de contacto el botón apunta a `https://www.linkedin.com/`, sustitúyelo por tu URL real (`https://www.linkedin.com/in/tu-usuario`).
- **CV en PDF**: el botón "cv.pdf ↓" del menú apunta de momento a la sección de contacto. Si quieres que descargue tu CV real, sube el PDF a `assets/cv.pdf` y cambia el `href` del botón `.nav-cv` en `index.html` por `assets/cv.pdf` (con el atributo `download`).
- Revisa los textos de "Sobre mí" y "Experiencia" por si quieres matizar algo.

## 🎨 Sobre el diseño

Tema oscuro "tech/backend" inspirado en tu banner de LinkedIn (azul noche + acentos cian/lima), con detalles tipo terminal (`$ whoami`, `ls projects/`) que encajan con el perfil de back-end. Tu logo se muestra en un marco circular con un anillo animado en la cabecera.

## 💡 Ideas para renovar tu tarjeta de LinkedIn

Tu banner actual ya tiene una estética sólida (circuitos + figura tech + tu logo). Para refrescarla puedes:

1. **Añadir la URL del portfolio** directamente en el banner (debajo del email), en formato `tudominio.github.io/portfolio` — así cualquiera que vea tu perfil la ve sin tener que buscarla.
2. **Unificar la paleta** con la del portfolio (mismo azul noche + cian + lima) para que portfolio, banner y CV se perciban como una sola marca personal.
3. **Sustituir "Back-End Dev" por algo con tu stack concreto**, p. ej. *"Back-End Developer · Java · Spring Boot · Python"* — da más información de un vistazo a un reclutador.
4. **Versión reducida del logo como foto de perfil** (círculo), dejando el banner solo para el mensaje y el contacto — mismo recurso visual que ya usas, mejor repartido.
