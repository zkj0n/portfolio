# Instrucciones

## 1. Utilización de recursos originales
- Usa tus propias fotos, texto, colores, tipos de letra, etc.
- Se valorará la originalidad y el diseño.

---

## 2. Adaptación de columnas según breakpoints
- **Sección de proyectos:** Cambia el número de columnas dependiendo del tamaño de la pantalla:
  - **Pantallas pequeñas (sm):** Una sola columna.
  - **Pantallas medianas (md):** Dos columnas.
  - **Pantallas grandes (lg):** Tres columnas.
  - **Pantallas extra grandes (xl):** Tres columnas.

---

## 3. Contenedor responsivo
- Cambia el tamaño del contenedor según las medidas:
  - Usa las clases de Bootstrap: `container`, `container-sm`, `container-md`, `container-lg`, `container-xl`.
- Ajusta el color de fondo según el tamaño de la pantalla:
  - **Pantallas pequeñas:** `bg-light`.
  - **Pantallas medianas y grandes:** Cambia a `bg-dark` o un color más destacado.

---

## 4. Tamaño de las letras responsivo
- Ajusta el tamaño de los títulos y textos según la pantalla:
  - Usa las clases `fs-*` (como `fs-1`, `fs-2`, etc.).
- Cambia también el color del texto si has modificado los fondos.

---

## 5. Márgenes y relleno
- Mejora la apariencia ajustando márgenes y rellenos:
  - Usa clases como `m-*`, `p-*`, `mt-*`, `mb-*`, etc.
- Adapta según dispositivos grandes y pequeños.

---

## 6. Imágenes en la sección de proyectos
- La imagen central debe ser más grande que las otras:
  - Usa `max-width` y `max-height` en CSS.
  - Asegúrate de que las imágenes sean responsivas con las clases `img-fluid` y `d-block`.
  - Puedes añadir un marco decorativo a las fotos.

---

## 7. Menú de navegación (Navbar)
- **Navbar responsivo:**
  - En pantallas pequeñas (sm), usa un botón de hamburguesa.
  - El menú debe expandirse en pantallas medianas y grandes (md, lg, xl).
  - El botón de hamburguesa debe estar alineado a la izquierda.
  - Personaliza el `navbar-toggler-icon` en una hoja de estilo.

---

## 8. Formulario responsivo
- Ajusta el tamaño de los campos según el tamaño de la pantalla.
- Incluye:
  - **Placeholder.**
  - **Iconos dentro de los campos.**
  - Algún campo adicional que no esté en el ejemplo.

---

## 9. Personalización de contenido
- **Sección "Sobre mí":**
  - Añade una breve descripción personal.
- **Sección "Proyectos":**
  - Detalla los proyectos realizados.
- **Sección "Contacto":**
  - Proporciona formas de contacto.

---

## 10. Icono en el nombre de la página
- Agrega un ícono relacionado con tecnología o diseño web al nombre de la página:
  - Usa la etiqueta `<link>` para el favicon.

---

## 11. Sección "Sobre mí"
- **Distribución:**
  - **12 columnas:** Pantallas pequeñas.
  - **6 columnas:** Pantallas medianas y grandes.
- El texto debe cambiar de tamaño según la pantalla.
- La imagen debe estar redondeada.

---

## 12. Pie de página
- Incluye al menos un ícono:
  - Ejemplo: GitHub, CSS.
- Centra el texto.
