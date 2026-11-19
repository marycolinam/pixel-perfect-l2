# 🎨 Pixel Perfect Course Card · BEM + SASS

Componente de tarjeta de curso maquetado *pixel perfect* con HTML5, SCSS y metodología BEM.

> 🇬🇧 *Pixel-perfect course card component built with semantic HTML5, SCSS and the BEM methodology, with a modular SASS architecture.*

🔗 **[Ver demo](https://marycolinam.github.io/pixel-perfect-l2/)**

---

## 📖 Sobre el proyecto

Entregable del **Módulo 3: Desarrollo de la Interfaz de Usuario Web** (Análisis de Caso L2), para el caso *Pixel Perfect Studio*.

El objetivo fue replicar con precisión una tarjeta de curso, del estilo de las plataformas de e-learning, aplicando una nomenclatura de clases ordenada y escalable con BEM, y organizando los estilos en parciales de SASS.

La tarjeta incluye:

- Imagen del curso
- Título, instructora y resumen
- Calificación con estrellas (llenas y media estrella)
- Cantidad de reseñas, nivel, duración y número de clases
- Precio actual, precio anterior y badge de *Bestseller*
- Botón de llamada a la acción

## 🛠️ Tecnologías

- HTML5 semántico
- SCSS (SASS)
- Metodología BEM
- npm

## 🧩 Componente BEM

**Bloque:** `course-card`

**Elementos:**
`course-card__media` · `course-card__image` · `course-card__content` · `course-card__title` · `course-card__instructor` · `course-card__summary` · `course-card__rating` · `course-card__stars` · `course-card__star` · `course-card__reviews` · `course-card__meta` · `course-card__footer` · `course-card__price` · `course-card__badge` · `course-card__cta`

**Modificadores:**
- `course-card--bestseller`: variante destacada de la tarjeta
- `course-card__star--filled` / `course-card__star--half`: estrella llena o media estrella
- `course-card__badge--bestseller`: badge de curso más vendido

También incluye un texto `sr-only` para que los lectores de pantalla lean la calificación.

## 📁 Estructura

```
pixel-perfect-l2/
├── index.html
├── scss/
│   ├── main.scss                # Archivo principal que importa los parciales
│   ├── base/
│   │   ├── _variables.scss      # Colores, tipografías y medidas
│   │   ├── _mixins.scss         # Mixins reutilizables
│   │   ├── _normalize.scss      # Reset de estilos
│   │   └── _base.scss           # Estilos generales
│   └── components/
│       └── _course-card.scss    # Estilos del componente
├── assets/
│   ├── css/main.css             # CSS compilado
│   └── img/
└── docs/                        # Informe técnico (PDF)
```

## 🚀 Cómo ejecutarlo

```bash
git clone https://github.com/marycolinam/pixel-perfect-l2.git
cd pixel-perfect-l2
npm install
npm run sass
```

`npm run sass` compila `scss/main.scss` en `assets/css/main.css` y queda observando los cambios. Después abre `index.html` en el navegador.

## 📄 Documentación técnica

El análisis del problema, la justificación de la metodología, la documentación técnica y la reflexión final del proceso están en el **[Informe Técnico: Implementación de Metodología BEM y SASS](docs/Informe-T%C3%A9cnico-BEM-SASS-Pixel-Perfect%20Studio.pdf)**.

---

👩‍💻 Desarrollado por **Mariangel Colina** · [GitHub](https://github.com/marycolinam) · [LinkedIn](https://www.linkedin.com/in/marycolinam/)
