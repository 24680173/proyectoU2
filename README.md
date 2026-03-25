# proyectoU2
## animacion 2d 
 Repositorio Base: Animación 2D en Blender
1. Preparación del Escenario
Antes de dibujar, necesitas tener tu guía a la mano dentro de Blender.
 * Importar la Referencia: En el Modo Objeto, presiona Shift + A > Image > Reference y selecciona tu imagen de los 8 pajaritos.
 * Ajustar Opacidad: En el panel de Propiedades de Datos del Objeto (icono de imagen), activa Opacity y bájala a 0.4. Esto te permitirá calcar sin que los colores te confundan.
 * Posicionamiento: Mueve la imagen hacia atrás en el eje Y para que no se interponga con tus trazos.
2. Configuración de Grease Pencil
 * Asegúrate de tener un objeto Grease Pencil (Blank o Stroke).
 * Crea Capas (Layers): En el panel de propiedades (icono de línea verde curva), crea al menos dos capas:
   * Lines: Para el contorno negro.
   * Fills: Para los colores (pásala debajo de 'Lines').
 * Materiales: Crea materiales tipo "Stroke" para el negro y tipo "Fill" para los colores (rojo de la cabeza, azul del cuerpo, etc.).
    Proceso de Animación Cuadro a Cuadro
El secreto para que el pájaro vuele bien es seguir el orden de tu referencia (del 1 al 8).
Paso A: Dibujar el primer fotograma (Keyframe)
 * Ve al fotograma 1 en la línea de tiempo.
 * Entra en Draw Mode.
 * Dibuja el pajarito siguiendo la pose 1 de tu referencia.
Paso B: Crear el siguiente dibujo
 * Avanza en la línea de tiempo (por ejemplo, al fotograma 3 para animar "a doses", que da un look más clásico).
 * Activa el Onion Skinning: Haz clic en el icono de las "capas superpuestas" junto al nombre de tu capa. Esto te permitirá ver una sombra transparente de tu dibujo anterior.
 * Dibuja la pose 2 de tu referencia. Blender creará automáticamente un nuevo Keyframe.
Paso C: Ciclo (Loop)
Repite el proceso hasta tener las 8 poses. Para que el vuelo sea infinito:
 * Selecciona todos tus fotogramas en el Dopesheet.
 * Presiona Shift + D para duplicarlos y muévelos justo después del último.
 * Tip Pro: Puedes usar un modificador llamado Time Offset en modo "Loop" para que se repita solo sin tener que copiar y pegar.
