# TP2-Desarrollo-De-Software
Descripción del Proyecto

Este proyecto es una demostración de diversas técnicas y propiedades de diseño web aplicadas a una página HTML utilizando CSS. A continuación se ofrece una explicación detallada de los elementos y estilos implementados.
1. Estilos de Texto

En la primera sección, se exploran las propiedades relacionadas con el texto:
Párrafo: Se ha aplicado un tamaño de fuente específico y una decoración de texto (tachado) para resaltar el contenido de manera visualmente distinta.
Cita: Se presenta una cita en un bloque estilizado. El bloque tiene un fondo gris claro y un borde a la izquierda en color gris, lo que lo distingue del resto del texto. La cita está alineada a la izquierda y tiene un tamaño de fuente más pequeño para enfatizar su carácter destacado.

2. Propiedades de Caja

Se han creado dos cajas para ilustrar diferentes estilos de contenedores:
Caja 1: Tiene un borde negro delgado y un estilo uniforme. Esta caja sirve como referencia básica para comparar con la siguiente.
Caja 2: Esta caja destaca por su borde más grueso, un sombreado que crea un efecto de profundidad, y un fondo de color amarillo claro. Aunque tiene el mismo radio de borde que la Caja 1, su apariencia es más distintiva debido a estos estilos adicionales.

3. Posicionamiento

Se exploran dos tipos de posicionamiento CSS:
Posición Relativa: Un contenedor con posición relativa se ajusta en relación con su ubicación original en el flujo del documento. Esto permite mover el contenido dentro de su contenedor sin afectar a otros elementos.
Posición Absoluta: Dentro del contenedor con posición relativa, se coloca un elemento con posición absoluta. Este elemento se posiciona en relación con su contenedor padre y se ubica usando coordenadas específicas (top y left), lo que le permite   situarse de manera precisa dentro del contenedor.

4. Diseño de Grid

Se utiliza CSS Grid para organizar elementos en una cuadrícula:
Cuadrícula de Elementos: Cuatro elementos están distribuidos en una cuadrícula flexible, utilizando la propiedad display: grid. Los elementos se ajustan automáticamente al ancho del contenedor y se alinean de manera ordenada gracias a la configuración de grid-template-columns y gap.

5. Animaciones y Transiciones

Se implementan animaciones y transiciones para mejorar la interacción del usuario:
Transición de Color: Un div cambia de color suavemente cuando el usuario pasa el cursor sobre él, gracias a la propiedad transition.
Animación: Otro div tiene una animación que lo mueve horizontalmente de manera continua. Esto se logra mediante la regla @keyframes, que define la animación y su comportamiento a lo largo del tiempo.

6. Diseño Adaptativo

Se emplean media queries para asegurar que el diseño se adapte a diferentes tamaños de pantalla:
Ajustes en Pantallas Pequeñas: Para dispositivos con un ancho máximo de 768px, se ajustan varios aspectos del diseño, como el tamaño de la fuente, los márgenes y las posiciones de los elementos. Esto garantiza que la página se visualice correctamente en dispositivos móviles y tablets.
