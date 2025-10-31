# 🎨 Rojo Carmín - Proyecto Final CoderHouse

## 📋 Descripción del Proyecto

**Rojo Carmín** es un sitio web profesional de diseño y arquitectura desarrollado como proyecto final del curso de Desarrollo Web en CoderHouse. El sitio presenta una plataforma moderna y elegante dedicada al mundo del diseño contemporáneo, con secciones especializadas en noticias destacadas, charlas de diseño (Design Talks), galería interactiva y formulario de contacto.

## 🌐 Demo en Vivo

Puedes ver el sitio web en funcionamiento aquí: **[https://fipedruzzi97.github.io/Entrega-Final-CH-PedruzziFiamma/](https://fipedruzzi97.github.io/Entrega-Final-CH-PedruzziFiamma/)**

## ✨ Características Principales

- **🎯 Diseño Responsivo**: Perfecta adaptación a dispositivos móviles, tablets y desktop
- **🧭 Navegación Intuitiva**: Menú de navegación limpio con anclas internas funcionales
- **🎨 Secciones Especializadas**:
  - **Noticias Destacadas**: Contenido actualizado sobre arte y diseño
  - **Design Talks**: Perfiles detallados de diseñadores reconocidos (Patrick Jouin, Snøhetta, Estudio Campana, Aires Mateus)
  - **Galería Interactiva**: Proyectos organizados por categorías con offcanvas
  - **Formulario de Contacto**: Interfaz moderna para comunicación
- **🔍 Optimización SEO**: Meta tags específicos, títulos jerárquicos y estructura semántica
- **♿ Accesibilidad Web**: Atributos ARIA, roles semánticos y navegación por teclado
- **🎭 Tipografías Modernas**: Integración con Google Fonts (Bebas Neue, Poppins)
- **🔄 Animaciones Dinámicas**: Transiciones suaves y efectos hover profesionales

## 🛠️ Tecnologías Implementadas

- **HTML5**: Estructura semántica con etiquetas modernas
- **CSS3/SCSS**: Estilos avanzados con preprocesador SASS
- **Bootstrap 5.3.8**: Framework CSS para grid system y componentes
- **JavaScript**: Funcionalidades interactivas (offcanvas, navegación)
- **Google Fonts**: Tipografías personalizadas de alta calidad
- **Git & GitHub**: Control de versiones y deployment automático

## 📁 Estructura del Proyecto

```
📦 Entrega-Final-CH-PedruzziFiamma
├── 📄 index.html                 # Página principal
├── 📄 README.md                  # Documentación del proyecto
├── 📂 pages/                     # Páginas secundarias (minúsculas)
│   ├── 📄 contacto.html          # Formulario de contacto
│   ├── 📄 destacados.html        # Página de noticias destacadas
│   ├── 📄 galeria.html           # Galería interactiva
│   └── 📂 design-talks/          # Perfiles de diseñadores
│       ├── 📄 Airesmateus.html
│       ├── 📄 Estudiocampana.html
│       ├── 📄 PatrickJouin.html
│       └── 📄 Snøhetta.html
└── 📂 public_html/
    └── 📂 assets/
        ├── 📂 css/
        │   ├── 📄 style.css      # CSS compilado
        │   └── 📄 style.css.map  # Source map
        ├── 📂 scss/              # Archivos fuente SASS
        │   ├── 📄 style.scss     # Archivo principal
        │   ├── 📄 _variables.scss # Variables de colores y fuentes
        │   ├── 📄 _mixins.scss    # Mixins reutilizables
        │   └── 📄 _each.scss      # Loops para clases utilitarias
        └── 📂 img/               # Imágenes optimizadas
```

## 🎨 Paleta de Colores

El sitio utiliza una paleta de colores sofisticada y profesional:

- **🔴 Primary**: `#A2231D` (Rojo Carmín) - Color principal de la marca
- **🔵 Secondary**: `#00171F` (Azul Marino) - Acentos y elementos secundarios  
- **🤎 Tertiary**: `#3D0C11` (Marrón Oscuro) - Detalles y texturas
- **⚫ Dark**: `#000000` - Textos principales
- **⚪ Light**: `#FFFFFF` - Fondos y contraste
- **🔘 Gray**: `#D9D9D9` - Elementos neutros

## 📱 Responsive Design

El sitio está optimizado para:
- **📱 Mobile First**: Diseño prioritario para dispositivos móviles
- **📟 Tablets**: Adaptación perfecta a pantallas medianas
- **💻 Desktop**: Experiencia completa en pantallas grandes
- **🖥️ Large Screens**: Escalado apropiado para monitores amplios

## 🚀 Instalación y Uso

### Clonar el repositorio
```bash
git clone https://github.com/fipedruzzi97/Entrega-Final-CH-PedruzziFiamma.git
cd Entrega-Final-CH-PedruzziFiamma
```

### Para desarrollo con SCSS
```bash
# Instalar SASS (si no lo tienes)
npm install -g sass

# Compilar SCSS en modo watch
sass --watch public_html/assets/scss/style.scss:public_html/assets/css/style.css
```

### Para deployment
- El sitio está listo para cualquier servidor web
- GitHub Pages configurado automáticamente
- Todas las rutas son relativas

## ✅ Cumplimiento de Requisitos Académicos

### Estructura HTML (Óptimo)
- ✅ 8 páginas HTML (supera las 5 requeridas)
- ✅ Etiquetas semánticas (header, main, section, article, footer)
- ✅ H1 único en cada página
- ✅ Meta tags SEO completos
- ✅ Atributos ARIA para accesibilidad

### Estilos CSS (Óptimo)
- ✅ SASS con estructura modular
- ✅ Bootstrap 5.3.8 correctamente implementado
- ✅ Responsive design sin overflow-x
- ✅ Animaciones y transiciones suaves

### Contenido y Diseño (Óptimo)
- ✅ Identidad visual coherente
- ✅ Navegación intuitiva
- ✅ Contenido relevante y bien estructurado
- ✅ Imágenes optimizadas y funcionales

## 👤 Autor

**Fiamma Pedruzzi**
- 👩‍💻 GitHub: [@fipedruzzi97](https://github.com/fipedruzzi97)
- 📧 Email: fipedruzzi97@gmail.com
- 🎓 Estudiante: Desarrollo Web - CoderHouse

## 📚 Curso

Este proyecto fue desarrollado como **Proyecto Final** del curso de **Desarrollo Web** en **CoderHouse**, aplicando todas las tecnologías y mejores prácticas aprendidas durante el curso.

## 📄 Licencia

Este proyecto fue creado con fines educativos como parte del programa académico de CoderHouse.

## ⚠️ Aviso Legal

**Uso Educativo**: Este sitio web fue desarrollado únicamente con propósitos educativos y de aprendizaje. Las imágenes utilizadas pertenecen a sus respectivos propietarios y se emplean bajo el contexto de uso académico. No tiene fines comerciales.

**Inspiración**: El diseño toma inspiración de sitios profesionales como roomdiseno.com, adaptado completamente para fines educativos.

---

⭐ **Si te gustó este proyecto, no olvides darle una estrella en GitHub!**