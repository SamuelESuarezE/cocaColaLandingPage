# Video de referencia

[![Alt text](https://img.youtube.com/vi/KP398UANzfw/0.jpg)](https://www.youtube.com/watch?v=KP398UANzfw)

# Glosario

**Posición (*posición*):**
La propiedad `position` en CSS controla cómo se posiciona un elemento en relación con su contenedor o con el documento en sí. Hay cinco valores principales para `position`:

- *static*: Este es el valor predeterminado. Los elementos con posición estática se colocan en el flujo normal del documento.
- *relative*: El elemento se posiciona de forma relativa a su posición normal. Esto significa que puedes moverlo usando las propiedades `top`, `right`, `bottom` y `left`.
- *absolute*: El elemento se posiciona en relación con su primer ancestro posicionado. Si no hay ninguno, se posicionará en relación con el documento.
- *fixed*: El elemento se posiciona en relación con la ventana del navegador, por lo que permanecerá en la misma posición incluso cuando se haga scroll.
- *sticky*: El elemento se comporta como relative hasta que alcanza cierto punto de desplazamiento (definido por la propiedad `top`, `right`, `bottom` o `left`), momento en el que se convierte en fixed y se "pega" a esa posición.

**Transición (*transición*):**
La propiedad `transition` permite especificar cómo se animan los cambios en las propiedades CSS. Esto significa que puedes suavizar la transición entre diferentes estados de un elemento, como cuando cambia su color, tamaño, posición, etc.

La sintaxis de `transition` es `transition: propiedad duración tipo-de-transición retraso;`.

- *propiedad*: La propiedad CSS que deseas animar.
- *duración*: El tiempo que tarda la transición en completarse, expresado en segundos (s) o milisegundos (ms).
- *tipo-de-transición*: Define cómo se calculan los valores intermedios de la transición. Algunos valores comunes son *ease* (suave), *linear* (lineal), *ease-in* (comienza lento), *ease-out* (termina lento), *ease-in-out* (comienza y termina lento).
- *retraso*: Opcional. Especifica un retraso antes de que comience la transición.
