# Aplicación de Exámenes OMR PWA

Aplicación web para crear exámenes tipo test, imprimir hojas de respuestas y corregirlas a partir de una fotografía. Permite configurar hasta 20 preguntas con cuatro opciones (A, B, C y D).

Video de muestra: https://youtu.be/bWXgWa9rZX4

## Español

### ¿Qué permite hacer?
- Crear formularios de examen y definir la respuesta correcta de cada pregunta.
- Guardar y volver a seleccionar formularios en el navegador.
- Generar e imprimir una hoja de respuestas en formato A4, con marcas de referencia para facilitar su lectura.
- Corregir una foto de la hoja y consultar la puntuación y el detalle de las respuestas.
- Compartir el enlace de la aplicación.

### Cómo usarla
1. En **Crear**, introduce el título y el número de preguntas (de 1 a 20), genera el formulario, marca las respuestas correctas y guarda el examen.
2. En **Imprimir**, selecciona el examen e imprime la hoja en A4.
3. Completa la hoja y toma una foto donde aparezca entera, incluidas sus cuatro marcas negras de referencia.
4. En **Corregir**, selecciona el mismo examen y carga la fotografía para ver el resultado.

### Requisitos y notas
- Se necesita un navegador moderno y conexión a Internet para cargar OpenCV.js desde jsDelivr.
- Para la corrección, la imagen debe tener al menos 1000 píxeles en su dimensión mayor y mostrar las cuatro marcas de la hoja con claridad.
- Los formularios se guardan en el almacenamiento local del navegador. No se sincronizan automáticamente con otros dispositivos ni navegadores.
- La aplicación procesa las hojas mediante OpenCV.js en el navegador; revisa visualmente el resultado si la foto está borrosa, inclinada o tiene marcas ambiguas.

## English

### What can it do?
- Create exam forms and set the correct answer for each question.
- Save forms in the browser and select them again later.
- Generate and print an A4 answer sheet with reference marks to help with image reading.
- Grade a photo of a completed sheet and view the score and answer details.
- Share the application link.

### How to use it
1. In **Create**, enter a title and the number of questions (1–20), generate the form, select the correct answers, and save the exam.
2. In **Print**, select the exam and print its answer sheet on A4 paper.
3. Fill in the sheet and take a photo of the entire page, including all four black reference marks.
4. In **Grade**, select the same exam and upload the photo to see the result.

### Requirements and notes
- A modern browser and an Internet connection are required to load OpenCV.js from jsDelivr.
- For grading, the image must be at least 1000 pixels along its longest dimension and clearly show all four reference marks.
- Exam forms are stored in the browser's local storage. They are not automatically synchronized across devices or browsers.
- The application processes answer sheets with OpenCV.js in the browser; visually check results when a photo is blurry, skewed, or contains ambiguous marks.

## Tecnología

- HTML, CSS y JavaScript.
- OpenCV.js para el procesamiento de imágenes.
- Almacenamiento local del navegador para conservar los formularios.

## Technology

- HTML, CSS, and JavaScript.
- OpenCV.js for image processing.
- Browser local storage for saving exam forms.
