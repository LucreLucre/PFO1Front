# Portafolio Personal — Lucrecia Vigo

Este proyecto es un **Trabajo Práctico (TP)** correspondiente a la **Práctica Formativa Obligatoria 1 (PFO1)** de la asignatura de Desarrollo Web (Frontend) en el IFTS N.º29.

Se trata de una **Landing Page de Portafolio Personal** desarrollada con HTML semántico y CSS. Incluye secciones de presentación, proyectos, habilidades, formulario de contacto y películas favoritas. Se usó IA para el desarrollo inicial de la misma.

🌐 **URL publicada (GitHub Pages):** 

https://lucrelucre.github.io/PFO1Front/

## Checklist — Práctica Formativa Obligatoria 1

### Estructura del Proyecto

- [x] Archivo `index.html` ubicado en la raíz.
- [x] Carpeta `css` que contenga el archivo `styles.css`.
- [x] (Opcional) Carpeta `img` para recursos gráficos.
- [x] Archivo `README.md` creado, que incluye una breve descripción del TP y este checklist.

### Repositorio y Publicación

- [x] Repositorio en GitHub creado.
- [x] Proyecto subido al repositorio.
- [x] Proyecto publicado utilizando GitHub Pages.
- [x] En el `README.md` se indica la URL de GitHub Pages.

### Uso de Google Fonts

- [x] Enlace a Google Fonts incluido en la sección `<head>` del HTML.
- [x] La tipografía importada se aplica en el sitio.
- [x] **¿Por qué elegiste esa fuente?**
  Se eligió la combinación **DM Serif Display** (títulos) + **DM Sans** (cuerpo). DM Serif Display aporta elegancia editorial y personalidad sin ser recargada, mientras que DM Sans garantiza excelente legibilidad en texto corrido. La combinación logra un look minimalista y profesional, coherente con el perfil de una desarrolladora.

### HTML

- [x] El documento inicia con la declaración `DOCTYPE` y usa el atributo `lang="es"`.
- [x] Se han incluido las metaetiquetas obligatorias: `charset` y `viewport`.
- [x] Se ha definido un título descriptivo.
- [x] Se han vinculado correctamente el archivo CSS y el enlace a Google Fonts.

**Secciones obligatorias en `main`:**

- [x] Barra de navegación (`<nav>`) presente y contiene al menos 3 enlaces.
- [x] Se han insertado al menos 4 comentarios explicativos en el código HTML.

### CSS

- [x] Existe el archivo `styles.css` con estilos personalizados.
- [x] Se utilizan selectores basados en clases e identificadores.
- [x] La tipografía importada desde Google Fonts se aplica correctamente en todos los elementos.

**Layout y Organización:**

- [x] Se ha organizado el layout (especialmente en la sección `tarjetas`) utilizando Flexbox o Grid.
- [x] Redacta: ¿Qué ventajas encontraste al utilizar Flexbox o Grid en tu proyecto?
   Flexbox simplificó la distribución de las tarjetas en columnas: las tarjetas se adaptan automáticamente a distintos tamaños de pantalla. También facilitó el alineado vertical del header y del footer.

**Estilización de Componentes:**

- [x] Se han personalizado los estilos de tablas, botones, enlaces y formularios.
- [x] Se han ajustado las dimensiones de imágenes y contenedores utilizando unidades relativas (`%`, `rem`, `vh`).
- [x] Se ha implementado al menos una animación o transición.
- [x] Redacta: ¿Qué animación o transición implementaste y por qué consideraste que era
adecuada para tu proyecto?
   Se implementaron transiciones CSS en las **tarjetas de proyectos y películas**: al hacer hover, se elevan con `transform: translateY(-6px)` y aumenta la sombra (`box-shadow`). Se eligió esta animación porque da feedback visual inmediato al usuario, mejora la percepción de interactividad y es lo suficientemente sutil para no distraer en un diseño minimalista.

### Consideraciones Adicionales

- [x] El diseño es responsivo y se visualiza correctamente en distintos dispositivos.
- [x] Se aplicaron buenas prácticas de accesibilidad (por ejemplo, uso adecuado de atributos alt en
las imágenes).
- [x] Se añadieron comentarios adicionales donde se describan decisiones de diseño o la lógica de
implementación.