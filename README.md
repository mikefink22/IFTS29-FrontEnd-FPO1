# Portafolio Personal — Mike

## Descripción del Proyecto

Este proyecto es la **Práctica Formativa Obligatoria 1 (PFO1)** de la materia Desarrollo Web. Consiste en una landing page de portafolio personal desarrollada únicamente con HTML5 y CSS3, sin frameworks ni librerías externas. El sitio presenta información personal, proyectos destacados, habilidades técnicas, películas favoritas y un formulario de contacto, aplicando buenas prácticas de maquetado semántico, diseño responsivo y accesibilidad.

- 🌐 **GitHub Pages:** [Ver Sitio Publicado](https://mikefink22.github.io/IFTS29-FrontEnd-FPO1/)
- 🚀 **Vercel:** [_Ver Sitio Publicado](https://portafoliomike.vercel.app/)

---

## Checklist — Práctica Formativa Obligatoria 1

### Estructura del Proyecto

- [x] Archivo `index.html` ubicado en la raíz.
- [x] Carpeta `css` que contenga el archivo `styles.css`.
- [x] Carpeta `img` para recursos gráficos.
- [x] Archivo `README.md` creado, que incluya una breve descripción del TP y este checklist.

### Repositorio y Publicación

- [x] Repositorio en GitHub creado.
- [x] Proyecto subido al repositorio.
- [x] Proyecto publicado utilizando GitHub Pages.
- [x] En el `README.md` se indica la URL de GitHub Pages.

### Uso de Google Fonts

- [x] Enlace a Google Fonts incluido en la sección `head` del HTML.
- [x] La tipografía importada se aplica en el sitio.
- [x] **¿Por qué elegiste esa fuente?**
  Se utilizaron dos fuentes: **JetBrains Mono** para títulos y elementos de código, aportando una estética técnica y de terminal acorde al perfil de desarrollador; y **Roboto** para el cuerpo del texto, por su alta legibilidad y neutralidad en pantalla.

### HTML

- [x] El documento inicia con la declaración `DOCTYPE` y usa el atributo `lang="es"`.
- [x] Se han incluido las metaetiquetas obligatorias: `charset` y `viewport`.
- [x] Se ha definido un título descriptivo.
- [x] Se han vinculado correctamente el archivo CSS y el enlace a Google Fonts.

**Secciones obligatorias en `main`:**

- [x] Sección `#sobre-mi` con párrafo descriptivo e imagen con atributo `alt`.
- [x] Sección `#tarjetas` con al menos dos tarjetas organizadas en Grid.
- [x] Sección `#habilidades` con listado de tecnologías y hobbies.
- [x] Sección `#contacto` con formulario (nombre, apellido, email, teléfono) y botón submit.
- [x] Sección `#peliculas` con tres películas, cada una con título, imagen y descripción.
- [x] Barra de navegación (`nav`) presente con al menos 3 enlaces.
- [x] Se han insertado al menos 4 comentarios explicativos en el código HTML.

### CSS

- [x] Existe el archivo `styles.css` con estilos personalizados.
- [x] Se utilizan selectores basados en clases e identificadores.
- [x] La tipografía importada desde Google Fonts se aplica correctamente en todos los elementos.

**Layout y Organización:**

- [x] Se ha organizado el layout utilizando CSS Grid en las secciones de tarjetas, habilidades y películas.
- [x] **¿Qué ventajas encontraste al utilizar Grid en tu proyecto?**
  Grid permitió lograr una adaptabilidad responsive con muy poco código, ajustando el número de columnas en cada breakpoint sin necesidad de cálculos manuales de anchos ni uso de float o position.

**Estilización de Componentes:**

- [x] Se han personalizado los estilos de botones, enlaces y formularios.
- [x] Se han ajustado las dimensiones de imágenes y contenedores utilizando unidades relativas (`%`, `rem`, `vh`).
- [x] Se ha implementado al menos una animación o transición.
- [x] **¿Qué animación o transición implementaste y por qué?**
  La transición principal es el slider de CSS puro en la sección de películas, que utiliza `transform: translateX` con una curva `cubic-bezier` para lograr un desplazamiento suave entre slides sin JavaScript. Se eligió porque demuestra el potencial de CSS para manejar interactividad sin dependencias externas. Complementariamente, se implementaron efectos hover en botones (`scale`), íconos del footer (`translateY`) y tarjetas de habilidades (acento de color por categoría).

### Consideraciones Adicionales

- [x] El diseño es responsivo y se visualiza correctamente en distintos dispositivos.
- [x] Se aplicaron buenas prácticas de accesibilidad (atributo `alt` en todas las imágenes, `aria-label` en íconos del footer, `label` asociado a cada campo del formulario).
- [x] Se añadieron comentarios en el HTML describiendo decisiones de diseño e ideas de mejora futura.