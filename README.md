# 📍 Proximity — Directorio Comercial y Comunitario

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Google Maps](https://img.shields.io/badge/Google_Maps-4285F4?style=for-the-badge&logo=google-maps&logoColor=white)
![License: MIT](https://img.shields.io/badge/License-MIT-teal.svg?style=for-the-badge)

**Proximity** es una plataforma web moderna e interactiva diseñada para conectar a la comunidad de la Comuna 5 en Cali con el comercio local. Permite explorar, buscar y descubrir más de 38 locales de barrio mediante geolocalización en tiempo real, cálculo de distancia (a pie y en auto), búsqueda por etiquetas y recorridos virtuales 360° en Google Maps Street View.

---

## ✨ Características Principales

- 🏪 **Directorio de 38 locales comerciales**:
  - Información detallada: nombre, categoría, descripción completa, dirección, horarios de atención y hashtags temáticos.
  - Fachadas y banners fotográficos en alta resolución.
- 🗺️ **Integración precisa con Google Maps & Street View 360°**:
  - Cada local cuenta con su enlace directo a Street View 360° en su fachada real.
  - Generación dinámica de rutas paso a paso desde la ubicación del usuario hasta el local.
- 📍 **Geolocalización y cálculo de proximidad**:
  - Soporte para GPS en tiempo real o ingreso manual de dirección.
  - Cálculo de distancia euclidiana/Haversine con estimación de tiempo a pie (~min) y en auto.
- 🔍 **Búsqueda y filtros rápidos**:
  - Filtro por categorías comerciales (Restaurantes, Panaderías, Barberías, Ferreterías, Mascotas, etc.).
  - Filtro interactivo por etiquetas/hashtags dinámicos desde la página principal.
- 🎨 **Diseño Moderno & Glassmorphism**:
  - Interfaz visual basada en *glassmorphism* (desenfoque de fondo, transparencias, gradientes suaves y micro-animaciones).
  - Nuevo logotipo vectorial identitario representando comunidad y cercanía.
  - Diseño 100% responsivo para computadores, tablets y smartphones.

---

## 📁 Estructura del Proyecto

```plaintext
proximity/
├── index.html            # Página de inicio con buscador inteligente y accesos directos
├── locales.html          # Directorio completo de locales con filtros, GPS y modal interactivo
├── sobre-nosotros.html   # Historia, misión y equipo detrás de Proximity
├── images/               # Recursos multimedia de producción
│   ├── bg-cali.jpg       # Fondo panorámico de Cali con desenfoque dinámico
│   ├── equipo.jpg        # Fotografía del equipo fundador
│   ├── logo.svg          # Logotipo vectorial oficial (SVG)
│   └── locales/          # Fachadas y banners individuales de los 38 locales
├── .gitignore            # Archivos y carpetas excluidos del control de versiones
├── LICENSE               # Licencia de código abierto MIT
└── README.md             # Documentación oficial del proyecto
```

---

## 🚀 Cómo Ejecutar el Proyecto Localmente

No se requieren dependencias externas ni compiladores:

1. **Clonar el repositorio**:
   ```bash
   git clone https://github.com/TU-USUARIO/proximity.git
   cd proximity
   ```

2. **Abrir en el navegador**:
   - Puedes hacer doble clic sobre `index.html` para abrirlo directamente en Chrome, Edge, Firefox o Safari.
   - O usando la extensión **Live Server** en Visual Studio Code para recarga automática.

---

## 🌐 Publicación en GitHub Pages (Gratis)

Este proyecto está 100% optimizado para **GitHub Pages**:

1. Sube tu código a un repositorio público en GitHub.
2. En GitHub, dirígete a: **Settings** > **Pages** (menú izquierdo).
3. En **Build and deployment** > **Source**, selecciona `Deploy from a branch`.
4. Elige la rama `main` y la carpeta `/ (root)`. Haz clic en **Save**.
5. En unos instantes tu sitio estará disponible públicamente en:
   `https://TU-USUARIO.github.io/proximity/`

---

## 🛠️ Tecnologías Utilizadas

- **HTML5**: Estructura semántica accesible.
- **CSS3 Vanilla**: Sistema de diseño con variables CSS, animaciones fluidas, grid y flexbox responsivo.
- **JavaScript (ES6+)**: Lógica de cálculo de distancias, filtros por URL params, modales accesibles y geolocalización.
- **Google Maps API / Street View**: Integración de recorridos inmersivos en 360 grados y generación de rutas.

---

## 📄 Licencia

Este proyecto se distribuye bajo la licencia **MIT**. Consulta el archivo [LICENSE](LICENSE) para más información.
