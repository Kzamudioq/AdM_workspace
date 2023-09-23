@Kzamudio ¿Qué te parece el repositorio? ¡Está chido! :+1:


# :star: Lisa Simpson te guía: resolución del Cuestionario :star:


¡Hola a todos! Soy Lisa Simpson, estoy aquí para ayudarte a navegar por el fascinante mundo de los microprocesadores ARM y resolver este cuestionario. 

<div class="center">
  <img src="https://github.com/Kzamudioq/AdM_workspace/assets/138271936/67ba9f76-0e78-4c72-b221-bfcbd64c9453" width="500">
</div>

Vaya ! antes de sumergirnos en las diferencias entre las familias Cortex y todo lo relacionado a la acrquitectura de `micros`, primero entendamos la importancia de estos pequeños pero poderosos dispositivos 🤓🤓. Un microcontrolador es un pequeño dispositivo electrónico que integra un procesador, memoria y periféricos en un solo chip como se evidencia en la *Imagen de Esquema de bloques del microcontrolador*, su propósito principal es controlar, monitorear y ejecutar tareas en sistemas embebidos. 

<div class="center">
  <img src="https://github.com/Kzamudioq/AdM_workspace/assets/138271936/466c6c44-d85b-43ae-bdda-a748411061ca" width="400">
</div>

*Imagen de esquema de bloques del microcontrolador citada desde [este enlace](https://www.disca.upv.es/aperles/arm_cortex_m3/llibre/libro-ARM-Cortex-M.pdf).*

¿Qué significa eso? Bueno, los sistemas embebidos son sistemas informáticos especializados que están ocultos dentro de otros dispositivos, como electrodomésticos, automóviles, dispositivos médicos y más. Lo que hace que los microcontroladores sean especiales es su capacidad para ejecutar programas específicos y controlar dispositivos del mundo real, como sensores, actuadores, pantallas y más. Son como el cerebro de muchos dispositivos que usamos a diario.

<div class="center">
  <img src="https://github.com/Kzamudioq/AdM_workspace/assets/138271936/666df2f9-a260-4824-9562-23ff7f75a737" width="400">
</div>

*Imagen de aplicación de procesadores ARM citada desde [este enlace](https://www.kovair.com/blog/future-of-arm-software-development/).*

¡Vamos a comenzar! 🚀 Recurda que durante esta aventura, exploraremos juntos las respuestas a las preguntas orientadoras y aprenderemos más sobre los microprocesadores ARM. ¡Así que, prepárate para sumergirte en el conocimiento y la diversión de la `arquitectura de los microcontroladores`!

## Familias de Microprocesadores 🅰️🆁🅼


Estoy emocionada de ayudarte a comprender las familias de microprocesadores de 🅰️🆁🅼. Las familias principales son `Cortex-A`, `Cortex-R` y `Cortex-M`, cada una tiene un propósito distinto, en `Cortex-A` se destaca en el rendimiento y se encuentra en dispositivos como smartphones, para `Cortex-R` el enfoca es dado en aplicaciones en tiempo real, como sistemas de control, por último, `Cortex-M` es ideal para sistemas embebidos de baja potencia, como sensores y dispositivos IoT. De esta manera, es favorable indicar que las diferencias clave incluyen `la potencia de procesamiento y el conjunto de características`, lo que permite adaptarlos a diversas aplicaciones.

<div class="center">
  <img src="https://github.com/Kzamudioq/AdM_workspace/assets/138271936/adb5c11f-1ac9-4721-8ac3-b29000a83795" width="400">
</div>

*Imagen de ARM citada desde [este enlace](https://www.orientdisplay.com/es/how-to-select-arm-processors/).*


### Cortex-🅰️ 
Los procesadores Cortex-A están diseñados para dispositivos Linux y Android, desde relojes inteligentes hasta equipos de red. Aquí tienes algunas características clave:
- Los procesadores Cortex-A `(A5, A7, A8, A9, A12, A15 y A17)` se basan en la arquitectura ARMv7-A.
- Ofrecen un máximo rendimiento y eficiencia energética, ideales para una variedad de dispositivos.
- `Ejemplos de procesadores:` Cortex-A7 para tabletas y teléfonos inteligentes sensibles al costo, Cortex-A15 para dispositivos de gama alta.

### Cortex-🆁
Los procesadores Cortex-R son ideales para aplicaciones en tiempo real de alto rendimiento, como sistemas automotrices y más. Algunos ejemplos incluyen:
- `Cortex-R4:` ideal para aplicaciones automotrices, con baja latencia y sincronización de hasta 600 MHz.
- `Cortex-R5:` ofrece mayor eficiencia y gestión de errores mejorada, ideal para respuestas en tiempo real.
- `Cortex-R7:` mayor rendimiento con canalización de 11 etapas y soporte para multiprocesamiento simétrico y asimétrico.

### Cortex-🅼
Cortex-M está diseñado para microcontroladores (MCU) y se adapta a una variedad de aplicaciones. Aquí están los aspectos más destacados:
- Los procesadores Cortex-M se utilizan en MCU con memorias, relojes y periféricos integrados.
- `Cortex-M0+:` utiliza el conjunto de instrucciones Thumb-2 y es eficiente en energía.
- `Cortex-M3 y M4:` ofrecen un rendimiento sólido, con Cortex-M4 destacando en DSP y punto flotante.

De esta manera podemos decir que, Cortex-🅰️ es ideal para dispositivos de alto rendimiento, Cortex-🆁 es perfecto para aplicaciones en tiempo real y Cortex-🅼 se adapta a una amplia gama de aplicaciones, desde eficiencia energética hasta rendimiento sólido. ¡Espero que esta guía te haya ayudado a comprender mejor estas familias de procesadores ARM! 😄




<div class="center">
  <img src="https://github.com/Kzamudioq/AdM_workspace/assets/138271936/2162ff14-54d6-4734-abef-2d290409e292" alt="Lisa Simpson" width="300">
</div>

`Referencia`: [ARM Architectures](https://developer.arm.com/architectures)

## 1. Diferencias Entre las Familias Cortex-<span style="color: blue;">🅼</span>

🧠 ¡Claro! En el mundo de los microprocesadores ARM, las familias `Cortex-M0, M0+, M1, M3 y M4` tienen sus propias peculiaridades. El `Cortex-M0` es simple y eficiente en energía, ideal para aplicaciones con recursos limitados, en `Cortex-M3` se obtiene un rendimiento más sólido y se adapta bien a una variedad de aplicaciones, mientras que el `Cortex-M4` es similar al M3 pero agrega capacidades de procesamiento de señales digitales (DSP) y punto flotante, lo que lo hace excelente para aplicaciones que requieren un procesamiento intensivo.💡

<div class="center">
  <img src="https://github.com/Kzamudioq/AdM_workspace/assets/138271936/49e114fe-c38e-4e2c-a474-600bff8c82d0" width="600">
</div>

`Referencia`: [ARM Architectures](https://soloelectronicos.com/2022/07/27/hablemos-de-la-familia-stm32/)


<table style="font-size: 9px;">
  <tr>
    <th>Modelo ARM</th>
    <th>Juego de Instrucciones</th>
    <th>Thumb-2</th>
    <th>Multiplicación Hardware</th>
    <th>División Hardware</th>
    <th>Extension DSP</th>
    <th>Como Flotante</th>
    <th>Versión de Arquitectura</th>
    <th>Arquitectura CPU</th>
  </tr>
  <tr>
    <td>Cortex-M0</td>
    <td>parcial 1 o 32 ciclos</td>
    <td>no</td>
    <td>no</td>
    <td>no</td>
    <td>no</td>
    <td>no</td>
    <td>ARMv6-M</td>
    <td>Von Neuman</td>
  </tr>
  <tr>
    <td>Cortex-M0+</td>
    <td>parcial 1 o 32 ciclos</td>
    <td>no</td>
    <td>no</td>
    <td>no</td>
    <td>no</td>
    <td>no</td>
    <td>ARMv6-M</td>
    <td>Von Neuman</td>
  </tr>
  <tr>
    <td>Cortex-M1</td>
    <td>parcial 3 o 33 ciclos</td>
    <td>no</td>
    <td>no</td>
    <td>no</td>
    <td>no</td>
    <td>no</td>
    <td>ARMv6-M</td>
    <td>Von Neuman</td>
  </tr>
  <tr>
    <td>Cortex-M3</td>
    <td>completo 1 ciclo</td>
    <td>sí</td>
    <td>no</td>
    <td>no</td>
    <td>no</td>
    <td>no</td>
    <td>ARMv7-M</td>
    <td>Harvard</td>
  </tr>
  <tr>
    <td>Cortex-M4</td>
    <td>completo 1 ciclo</td>
    <td>sí</td>
    <td>sí</td>
    <td>opcional</td>
    <td>ARMv7EM</td>
    <td>sí</td>
    <td>ARMv7-M</td>
    <td>Harvard</td>
  </tr>
</table>

`Referencia:` [Comparación de las familias Cortex-M](https://developer.arm.com/ip-products/processors/cortex-m)

<p><span style="color: purple;">¡Vaya!</span> ahora que tenemos esta tabla, puedo explicarte un poco más sobre las subfamilias de los procesadores Cortex-M. Como ves, hay modelos como el Cortex-M0, que son menos potentes y requieren menos silicio, y luego están los M4, que ofrecen mucho más rendimiento a costa de ocupar más espacio.</p>
La familia ARM Cortex-M es genial por varias razones:
<ul>
  <li>Una arquitectura, muchas implementaciones. Cada fabricante agrega su toque especial, como en automoción, aeroespacial, bajo consumo, FPGA y más.</li>
  <li>Un montón de herramientas, tanto de hardware como de software. Hay emuladores, compiladores, IDEs, bibliotecas y más, ¡algunas son incluso gratuitas!</li>
  <li>¡Una comunidad superactiva! Hay blogs, foros y proyectos interesantes como mbed, lpcxpresso y mapple.</li>
  <li>Los "starter kits" son prácticamente regalados, lo que facilita empezar con estos microcontroladores.</li>
  <li>Finalmente, la depuración es una parte fundamental en el mundo de los microcontroladores, y la familia Cortex-M lo hace más accesible.</li>
</ul>
Estamos listos para explorar en detalle cada una de estas subfamilias. ¡Vamos a aprender más sobre los `Cortex-M0, M0+, M1, M3 y M4`! 🚀



## 2. Ventajas del Conjunto de Instrucciones Thumb

¡Vamos a explorar esto! El conjunto de instrucciones Thumb de ARM es como un atajo inteligente para reducir el tamaño del código. Las instrucciones Thumb son más compactas, lo que significa que ocupan menos espacio en la memoria. Esto es esencial en dispositivos con recursos limitados. Al reducir el tamaño del código, aumentamos la densidad de código, lo que permite almacenar más instrucciones en la misma cantidad de memoria. Es como un juego de tetris con código, ¡optimizando cada espacio disponible!

🧠`Por ende, el set de instrucciones Thumb es una característica inteligente de los procesadores ARM que permite una mayor densidad de código.` 💡

Imagina que tienes un programa de software, y quieres que ocupe la menor cantidad de memoria posible, especialmente en dispositivos con `recursos limitados` como los sistemas embebidos. Aquí es donde entra en juego el set de instrucciones Thumb, 👾 el set de instrucciones Thumb utiliza instrucciones de 16 bits en lugar de las instrucciones de 32 bits del conjunto completo de instrucciones ARM, esto significa que, en general, el código generado con Thumb es más compacto y ocupa menos espacio de memoria. 👍 Entonces, la respuesta a la pregunta 2. ¿Por qué se dice que el set de instrucciones Thumb permite mayor densidad de código? es que el set de instrucciones Thumb permite una mayor densidad de código porque utiliza instrucciones más pequeñas y compactas, lo que ahorra espacio de memoria y es ideal para dispositivos con recursos limitados. 😎

Referencia: [ARM Thumb Instruction Set](https://developer.arm.com/documentation/ddi0210/c/)
Aplicabilidad: [ARM Thumb Instruction Set](https://developer.arm.com/documentation/ddi0210/c/)

## 3. Arquitectura Load-Store

Por supuesto, permíteme explicar. La arquitectura load-store es una forma de organizar las operaciones de un procesador. En esta arquitectura, las operaciones de carga (load) y almacenamiento (store) solo se realizan en registros de propósito general, no directamente en la memoria principal. Las instrucciones de carga directa o almacenamiento directo en memoria, como las que operan directamente en ubicaciones de memoria, no son parte de esta arquitectura. En cambio, en la arquitectura load-store, primero se cargan los datos en registros, se realizan las operaciones y luego se almacenan los resultados en memoria.

Referencia: [Arquitectura load-store](https://www.embedded.com/the-importance-of-the-load-store-architecture/)

## 4. Mapa de Memoria de la Familia Cortex-M

Por supuesto, estaré encantada de explicarlo. La familia Cortex-M sigue un mapa de memoria típico para sistemas embebidos. La memoria flash se utiliza para almacenar el código, mientras que la RAM almacena datos. Los registros forman parte del procesador y se utilizan para operaciones de procesamiento. Los periféricos, como puertos de entrada/salida y temporizadores, se mapean en direcciones de memoria específicas para que el procesador pueda interactuar con ellos de manera eficiente. :blush:

Referencia: [Mapa de memoria de ARM Cortex-M](https://www.keil.com/pack/doc/cmsis/Core/html/group__system__init__gr.html)






> [!NOTE]
> Highlights information that users should take into account, even when skimming.

> [!IMPORTANT]
> Crucial information necessary for users to succeed.

> [!WARNING]
> Critical content demanding immediate user attention due to potential risks.


`línea de código`

```php
<?php
  echo "fragmento largo de código";
?>
```

| Tables   |      Are      |  Cool |
|----------|:-------------:|------:|
| col 1 is |  left-aligned | $1600 |
| col 2 is |    centered   |   $12 |
| col 3 is | right-aligned |    $1 |


|Tables|Are|Cool|
|-|:-:|-:|
|col 1 is|left-aligned|$1600|
|col 2 is|centered|$12|
|col 3 is|right-aligned|$1|



