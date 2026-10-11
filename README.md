# Portafolio Web | Elias Talledo

Portafolio personal de **Elias Talledo**, desarrollador web full stack. Es un sitio estático de una sola página donde presento mis proyectos, habilidades, servicios y certificados.

🔗 **Demo:** [tu-usuario.github.io/my_portafoly](https://my-portafoly.pages.dev/) <!-- reemplaza con tu URL real -->

![Vista previa del portafolio](docs/preview.png) <!-- agrega una captura optimizada (WebP/PNG < 300 KB) -->

---

## Contenido

- [Características](#características)
- [Tecnologías](#tecnologías)
- [Estructura del proyecto](#estructura-del-proyecto)
- [Cómo ejecutarlo localmente](#cómo-ejecutarlo-localmente)
- [Despliegue](#despliegue)
- [Personalización](#personalización)
- [Mejoras pendientes](#mejoras-pendientes)
- [Contacto](#contacto)

---

## Características

- Diseño **responsive** (escritorio, tablet y móvil) con menú hamburguesa.
- Navegación con **scroll suave** y enlace activo según la sección visible.
- Secciones: Inicio, Acerca de, Servicios, Portafolio, Certificados y Contacto.
- Descarga directa del **CV en PDF**.
- Acceso rápido a **WhatsApp** y redes profesionales (LinkedIn, GitHub).
- Año del pie de página actualizado automáticamente.
- Sin frameworks ni proceso de build: HTML, CSS y JavaScript puros.

## Tecnologías

| Área | Herramientas |
| --- | --- |
| Estructura | HTML5 semántico |
| Estilos | CSS3 (variables, Flexbox, Grid, media queries) |
| Interactividad | JavaScript (vanilla) |
| Iconos | [Boxicons](https://boxicons.com/) |
| Tipografía | [Google Fonts](https://fonts.google.com/) (AR One Sans) |

## Estructura del proyecto

```
my_portafoly/
├── index.html          # Página principal (todas las secciones)
├── styles/
│   └── styles.css      # Estilos y variables de tema
├── images/             # Capturas de proyectos, foto de perfil e ilustraciones
│   └── certificates/   # Imágenes de certificados
├── resource/           # CV y certificados en PDF
└── README.md
```

## Cómo ejecutarlo localmente

No necesita instalación ni dependencias.

**Opción 1: abrir el archivo**

```bash
git clone https://github.com/Santrax211/my_portafoly.git
cd my_portafoly
```

Abre `index.html` en tu navegador.

**Opción 2: servidor local** (recomendado)

```bash
# con Python
python3 -m http.server 8000

# o con Node
npx serve .
```

Luego entra a `http://localhost:8000`.

## Despliegue

Al ser un sitio estático, se puede publicar gratis en:

- **GitHub Pages:** `Settings → Pages → Deploy from a branch → main / (root)`.
- **Vercel** o **Netlify:** importa el repositorio, sin comando de build y con la raíz como directorio de salida.

## Personalización

1. **Datos personales:** edita textos, enlaces sociales y número de WhatsApp en `index.html`.
2. **Colores y tema:** modifica las variables CSS al inicio de `styles/styles.css` (`--main-color`, `--bg-color`, etc.).
3. **Proyectos:** duplica un bloque `.portfolio-item` en la sección `#portfolio`, cambia título, descripción, enlace y captura (`images/`).
4. **Certificados:** agrega la imagen en `images/certificates/`, el PDF en `resource/` y duplica un bloque `.certificate-item`.
5. **CV:** reemplaza el archivo en `resource/` y actualiza el enlace del botón "Descargar CV".

## Mejoras pendientes

- [ ] Conectar el formulario de contacto a un servicio real (Formspree, Web3Forms o EmailJS).
- [ ] Optimizar imágenes (convertir a WebP, `loading="lazy"`, `width`/`height`).
- [ ] Añadir enlaces a demos desplegadas en cada proyecto.
- [ ] Incluir metadatos Open Graph/Twitter, `sitemap.xml` y `robots.txt`.
- [ ] Mejorar accesibilidad (contraste de color, estados de foco, `aria-expanded` en el menú).
- [ ] Separar el JavaScript en un archivo propio (`js/main.js`).

## Contacto

- **LinkedIn:** [Elias Samuel Talledo Vega](https://www.linkedin.com/in/samueltalledovega2025)
- **GitHub:** [@Santrax211](https://github.com/Santrax211)

---

© 2026 Elias Talledo. Todos los derechos reservados.
