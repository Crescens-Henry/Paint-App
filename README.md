## PaintApp: Aplicación de Dibujo Básica

Este repositorio contiene una aplicación de dibujo básica implementada en Python utilizando la biblioteca de interfaz gráfica de usuario Tkinter, junto con las bibliotecas OpenCV y PIL (Python Imaging Library) para procesamiento de imágenes.

### Funcionalidades Principales

La clase `PaintApp` es la clase principal que maneja la lógica de la aplicación. Aquí hay un resumen de las principales funcionalidades implementadas:

- **Inicialización y Configuración**: En el método `__init__`, se inicializan variables y se configura la interfaz de usuario. Se crea un lienzo en blanco y se configuran botones para seleccionar herramientas de dibujo y colores.

- **Configuración de Herramientas y Colores**: El método `setup_tools` configura las herramientas de dibujo y los colores disponibles, creando botones para cada herramienta y un cuadro combinado para seleccionar el color.

- **Eventos del Ratón**: El método `setup_events` vincula eventos del ratón a métodos correspondientes, como el movimiento del ratón y el clic, para realizar acciones de dibujo.

- **Dibujo en el Lienzo**: El método `draw` realiza el dibujo en el lienzo dependiendo de la herramienta seleccionada, utilizando funciones de dibujo de OpenCV y actualizando el lienzo con la imagen dibujada.

- **Finalización del Dibujo**: El método `finalize_draw` se llama al soltar el botón del ratón, finalizando el dibujo y actualizando la imagen.

- **Actualización del Lienzo**: El método `redraw` se utiliza para actualizar el lienzo con la imagen dibujada.

### Uso

Para utilizar la aplicación de dibujo básica, simplemente ejecuta el script `main.py`. A continuación, puedes seleccionar la herramienta de dibujo y el color deseado, y empezar a dibujar en el lienzo.

### Contribuciones

Las contribuciones son bienvenidas. Si deseas mejorar esta aplicación de dibujo o agregar nuevas funcionalidades, siéntete libre de enviar un pull request.

### Notas

Este proyecto fue creado con el propósito de demostrar una aplicación básica de dibujo utilizando Tkinter, OpenCV y PIL. Se recomienda para fines educativos y de aprendizaje.
