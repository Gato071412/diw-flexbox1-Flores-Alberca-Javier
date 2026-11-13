Inicialmente busque hacer las flexbox lo más parecidas a lo mencionado en la práctica, ajustando los menus para que estén en línea como es debido.

Una vez conseguido esto gracias a las propiedades del "display: Flex" busco la manera de hacer que el footer se mantenga abajo, modificando el texto principal (main) durante parte del proceso.
Logro hacer lo anterior modificando el body general para convertirlo en una columna "dividida" en tres partes, llevando el footer hacía el fondo.

Con las dos anteriores hechas prácticamente todo esta completado, solamente faltaría modificar la apariencia de los enlaces y las frases siendo esto más estetico. 
Iniciando por los enlaces, modificamos el como se ven cuando están "flotando" y cuando no, debido a que no habrá cambio cuando sean visitadas

Finalmente añadí más peso a la marca de cabecera y puse el texto del pie como variante de smalls caps aunque realmente no este así en el html por simple estetica
----------------------------------------------------------------------------------------------------------------

Vamos con la parte B, añadiendo primeramente esta al git
Con la explicación del profesor me doy cuenta que efectivamente hice cualquier cosa, por lo que cambio el html body que tenía y el principal de igual manera para poder tener todo recto.

Tras reajustar todo una vez más y hacer las bases de las clases "contenido" y "campo", decido ir a ajustar la clase de "hijos" con todos los hijos de esta clase, y continuo posteriormente con el diseño base de todos los grupos en si mismos.

Ahora avanzo con los campos en si para diseñar de manera individual los campos de formularios en si mismos, para plantar un diseño tal como se indica en la práctica antes de comenzar a plantear los grids.
Como haremos el diseño con consultas y orientado de 40em para adelante como pide la práctica, preparo y planteo todo lo que deben de salir en opciones y botones antes de hacer los grids

Ahora si, procedo a hacer todos los grids correspondientes
----------------------------------------------------------------------------------------------------------------

Añadimos paleta de colores en root y actualizamos todo el resto

Procedemos a añadir las sombras y relieves en formularios y cabecera
Ahora pasamos a botones añadiendo relieve y sombra directamente para el principal, mientras que en el secundario y dedicado a borrar hemos añadido el color de texto secundario añadido en las variables

Ahora vamos al degradado donde tal como se indica debemos de anotar el proceso de medición y demás aquí, por eso mismo iré por puntos:
- Primero darme cuenta que cabecera y pie son idénticos y agruparlos, también configuramos para que los enlaces sean blancos
- Colocamos la gradiente
- Abrimos la página y con la inspección de elementos en styles podemos ir al color de texto (#ffffff) y compararlo (contrast ratio) con otros colores de nuestro texto.
- En mi caso he comparado con el fondo en izquierda (Color más oscuro), medio (color intermedio) y derecho (Color más claro) dando los siguientes valores:
- - Izquierda: C.R 12.45, AA 4,5
- - Centro: C.R 10.23, AA 4,5
- - Derecha: C.R 8.19, AA 4,5
Por lo que es correcto el contraste

Y con esto finalmente pasamos a aumentar el tamaño de los círculos del aside, tan sencillo como usar un hover y un "transform scale" y modificar el original para añadir la transición de 0,2