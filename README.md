# instrucciones

## 1. utilización de recursos originales
- usa tus propias fotos, texto, colores, tipos de letra, etc.
- se valorará la originalidad y el diseño.

---

## 2. adaptación de columnas según breakpoints
- **sección de proyectos:** cambia el número de columnas dependiendo del tamaño de la pantalla:
  - **pantallas pequeñas (sm):** una sola columna.
  - **pantallas medianas (md):** dos columnas.
  - **pantallas grandes (lg):** tres columnas.
  - **pantallas extra grandes (xl):** tres columnas.

---

## 3. contenedor responsivo
- cambia el tamaño del contenedor según las medidas:
  - usa las clases de bootstrap: `container`, `container-sm`, `container-md`, `container-lg`, `container-xl`.
- ajusta el color de fondo según el tamaño de la pantalla:
  - **pantallas pequeñas:** `bg-light`.
  - **pantallas medianas y grandes:** cambia a `bg-dark` o un color más destacado.

---

## 4. tamaño de las letras responsivo
- ajusta el tamaño de los títulos y textos según la pantalla:
  - usa las clases `fs-*` (como `fs-1`, `fs-2`, etc.).
- cambia también el color del texto si has modificado los fondos.

---

## 5. márgenes y relleno
- mejora la apariencia ajustando márgenes y rellenos:
  - usa clases como `m-*`, `p-*`, `mt-*`, `mb-*`, etc.
- adapta según dispositivos grandes y pequeños.

---

## 6. imágenes en la sección de proyectos
- la imagen central debe ser más grande que las otras:
  - usa `max-width` y `max-height` en css.
  - asegúrate de que las imágenes sean responsivas con las clases `img-fluid` y `d-block`.
  - puedes añadir un marco decorativo a las fotos.

---

## 7. menú de navegación (navbar)
- **navbar responsivo:**
  - en pantallas pequeñas (sm), usa un botón de hamburguesa.
  - el menú debe expandirse en pantallas medianas y grandes (md, lg, xl).
  - el botón de hamburguesa debe estar alineado a la izquierda.
  - personaliza el `navbar-toggler-icon` en una hoja de estilo.

---

## 8. formulario responsivo
- ajusta el tamaño de los campos según el tamaño de la pantalla.
- incluye:
  - **placeholder.**
  - **iconos dentro de los campos.**
  - algún campo adicional que no esté en el ejemplo.

---

## 9. personalización de contenido
- **sección "sobre mí":**
  - añade una breve descripción personal.
- **sección "proyectos":**
  - detalla los proyectos realizados.
- **sección "contacto":**
  - proporciona formas de contacto.

---

## 10. icono en el nombre de la página
- agrega un ícono relacionado con tecnología o diseño web al nombre de la página:
  - usa la etiqueta `<link>` para el favicon.

---

## 11. sección "sobre mí"
- **distribución:**
  - **12 columnas:** pantallas pequeñas.
  - **6 columnas:** pantallas medianas y grandes.
- el texto debe cambiar de tamaño según la pantalla.
- la imagen debe estar redondeada.

---

## 12. pie de página
- incluye al menos un ícono:
  - ejemplo: github, css.
- centra el texto.
