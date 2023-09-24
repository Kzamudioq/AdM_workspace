@Kzamudio ¿Qué te parece el repositorio? ¡Está chido! :+1:

<h1 align="center">
  <p align="center">:star: Lisa Simpson te guía: resolución del Cuestionario :star:</p>
</h1>

¡Hola a todos! Soy Lisa Simpson, estoy aquí para ayudarte a navegar por el fascinante mundo de los microprocesadores ARM y resolver este cuestionario. 


<p align="center" width="100%">
    <img width="60%" src="https://github.com/Kzamudioq/AdM_workspace/assets/138271936/67ba9f76-0e78-4c72-b221-bfcbd64c9453"> 
</p>

## 🧠 ¿Qué es un microconrolado? 🧠

<img align="right" width="65%" src="https://github.com/Kzamudioq/AdM_workspace/assets/138271936/466c6c44-d85b-43ae-bdda-a748411061ca"> 

Vaya, antes de zambullirnos en las diferencias entre las familias Cortex y todo lo relacionado con la arquitectura de los `micros`, primero, ¡necesitamos entender la importancia de estos pequeños pero poderosos dispositivos! 😄. 

Imagina, un microcontrolador es como el cerebro y el corazón de muchos sistemas electrónicos. Es un pequeño dispositivo electrónico que cabe en la palma de tu mano, pero no subestimes su capacidad. Este pequeño prodigio integra un procesador, memoria y periféricos en un solo chip, como puedes ver en la *imagen de esquema de bloques del microcontrolador citada desde [este enlace](https://www.disca.upv.es/aperles/arm_cortex_m3/llibre/libro-ARM-Cortex-M.pdf).*




`¿Y cuál es su misión principal?` Bueno, su propósito es controlar, monitorear y ejecutar tareas en sistemas embebidos, en otras palabras, estos diminutos héroes electrónicos son los encargados de hacer funcionar todo, desde tu lavadora y secadora, hasta tu teléfono inteligente y tu reloj digital. Sin ellos, la mayoría de los dispositivos que usamos a diario simplemente no funcionarían, alguno se puden viualizar en la ssiguiente imagen.

<p align="center" width="75%">
    <img width="32%" src="https://github.com/Kzamudioq/AdM_workspace/assets/138271936/01ff8360-8041-4200-9561-5a41e6e1db01"> 
    <img width="32%" src="https://github.com/Kzamudioq/AdM_workspace/assets/138271936/aec1b786-e341-422a-a7a6-89173f439d17"> 
    <img width="32%" src="https://github.com/Kzamudioq/AdM_workspace/assets/138271936/b33d0c0b-2357-40ce-8d1a-8ebe353786f6"> 
</p>
<p align="center" width="75%">
    <img width="32%" src="https://github.com/Kzamudioq/AdM_workspace/assets/138271936/01898572-8479-4f4f-b3c9-1cd825e0b186"> 
    <img width="32%" src="https://github.com/Kzamudioq/AdM_workspace/assets/138271936/64adf1c8-9484-4249-a35b-9a2c3dee4518"> 
    <img width="32%" src="https://github.com/Kzamudioq/AdM_workspace/assets/138271936/8dcf2abe-7893-4ea7-82ef-9cdc74e6d2bb"> 
</p>

¡Vamos a comenzar! 🚀 recuerda que durante esta aventura, exploraremos juntos las respuestas a las preguntas orientadoras y aprenderemos más sobre los microprocesadores ARM. ¡Así que, prepárate para sumergirte en el conocimiento y la diversión de la `arquitectura de los microcontroladores`!

## 🧠 Familias de Microprocesadores 🅰️🆁🅼 🧠


Estoy emocionada de ayudarte a comprender las familias de microprocesadores de 🅰️🆁🅼. Las familias principales son `Cortex-A`, `Cortex-R` y `Cortex-M`, cada una tiene un propósito distinto, en `Cortex-A` se destaca en el rendimiento y se encuentra en dispositivos como smartphones, para `Cortex-R` el enfoca es dado en aplicaciones en tiempo real, como sistemas de control, por último, `Cortex-M` es ideal para sistemas embebidos de baja potencia, como sensores y dispositivos IoT. De esta manera, es favorable indicar que las diferencias clave incluyen `la potencia de procesamiento y el conjunto de características`, lo que permite adaptarlos a diversas aplicaciones.


<p align="center" width="100%">
    <img width="70%" src="https://github.com/Kzamudioq/AdM_workspace/assets/138271936/adb5c11f-1ac9-4721-8ac3-b29000a83795"> 
</p>


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

`Referencia`: [ARM Architectures](https://developer.arm.com/architectures)

<p align="center" width="100%">
    <img width="30%" src="https://github.com/Kzamudioq/AdM_workspace/assets/138271936/2162ff14-54d6-4734-abef-2d290409e292"> 
</p>



## 1. Diferencias Entre las Familias Cortex-<span style="color: blue;">🅼</span>

🧠 ¡Claro! En el mundo de los microprocesadores ARM, las familias `Cortex-M0, M0+, M1, M3 y M4` tienen sus propias peculiaridades. El `Cortex-M0` es simple y eficiente en energía, ideal para aplicaciones con recursos limitados, en `Cortex-M3` se obtiene un rendimiento más sólido y se adapta bien a una variedad de aplicaciones, mientras que el `Cortex-M4` es similar al M3 pero agrega capacidades de procesamiento de señales digitales (DSP) y punto flotante, lo que lo hace excelente para aplicaciones que requieren un procesamiento intensivo.💡


<p align="center" width="100%">
    <img width="50%" src="https://github.com/Kzamudioq/AdM_workspace/assets/138271936/49e114fe-c38e-4e2c-a474-600bff8c82d0"> 
</p>

`Referencia`: [ARM Architectures](https://soloelectronicos.com/2022/07/27/hablemos-de-la-familia-stm32/)


<p><span style="color: purple;">¡Vaya!</span> ahora que tenemos una visualización gráfica, puedo explicarte un poco más sobre las subfamilias de los procesadores Cortex-M. Como ves, hay modelos como el Cortex-M0, que son menos potentes y requieren menos silicio, y luego están los M4, que ofrecen mucho más rendimiento a costa de ocupar más espacio.</p>

**La familia ARM Cortex-M es genial por varias razones:**

<ul>
  <li>Una arquitectura, muchas implementaciones. Cada fabricante agrega su toque especial, como en automoción, aeroespacial, bajo consumo, FPGA y más.</li>
  <li>Un montón de herramientas, tanto de hardware como de software. Hay emuladores, compiladores, IDEs, bibliotecas y más, ¡algunas son incluso gratuitas!</li>
  <li>¡Una comunidad superactiva! Hay blogs, foros y proyectos interesantes como mbed, lpcxpresso y mapple.</li>
  <li>Los "starter kits" son prácticamente regalados, lo que facilita empezar con estos microcontroladores.</li>
  <li>Finalmente, la depuración es una parte fundamental en el mundo de los microcontroladores, y la familia Cortex-M lo hace más accesible.</li>
</ul>
Estamos listos para explorar en detalle cada una de estas subfamilias. ¡Vamos a aprender más sobre los Cortex-M0, M0+, M1, M3 y M4! 🚀 ¡Comencemos!

### 1.1. Cortex-M0 🌟

El Cortex-M0 es como el miembro pequeño pero poderoso de la familia. Está diseñado para ser eficiente en términos de energía y es una opción económica. Su arquitectura es simple y compacta, lo que lo hace ideal para sistemas embebidos con recursos limitados, como sensores y dispositivos IoT. Si buscas un microcontrolador que haga el trabajo sin gastar demasiada energía, el Cortex-M0 es una excelente elección.

**Ejemplo**: **Sensor de Temperatura en un Termostato Inteligente**

Imagina un termostato inteligente en tu hogar que ajusta automáticamente la temperatura. El Cortex-M0 podría estar dentro de un sensor de temperatura que mide constantemente la temperatura ambiente. Es eficiente en energía para prolongar la duración de la batería y lo suficientemente potente para realizar cálculos de control de temperatura.

### 1.2. Cortex-M0+ 💡

Similar al M0 pero con mejoras en eficiencia y rendimiento. Es como el M0 pero un poco más fuerte. Es una excelente elección para aplicaciones en tiempo real y dispositivos de bajo consumo. Si necesitas un rendimiento un poco más alto sin sacrificar la eficiencia energética, el Cortex-M0+ es tu opción.

**Ejemplo**: **Dispositivo de Monitoreo de Ejercicio en una Pulsera Inteligente**

En una pulsera inteligente que rastrea tu actividad física, el Cortex-M0+ podría gestionar las mediciones de ritmo cardíaco, pasos y distancia recorrida. Su eficiencia energética permite que la pulsera funcione durante días sin necesidad de recarga, y su rendimiento es suficiente para procesar datos en tiempo real.

### 1.3. Cortex-M1 🤖

El Cortex-M1 se enfoca en el control lógico programable (PLC) y se utiliza principalmente en aplicaciones FPGA. Si estás en el mundo de la automatización industrial y necesitas un procesador que se adapte perfectamente a sistemas lógicos programables, el Cortex-M1 es la elección.

**Ejemplo**: **Controlador en una Máquina de Fabricación Industrial**

En una máquina de fabricación industrial, el Cortex-M1 podría ser parte del controlador lógico programable (PLC). Se encargaría de coordinar las diferentes partes de la máquina, asegurando que cada componente funcione en el momento adecuado y en la secuencia correcta.

### 1.4. Cortex-M3 🏁

El Cortex-M3 ofrece un equilibrio impresionante entre eficiencia y rendimiento. Tiene soporte para interrupciones y multitarea, lo que lo hace ideal para aplicaciones en tiempo real y controladores de dispositivos. Si buscas un procesador que pueda manejar tareas complejas y mantener la eficiencia, el Cortex-M3 es la respuesta.

**Ejemplo**: **Controlador de Vehículo Autónomo**

En un vehículo autónomo, el Cortex-M3 podría ser responsable de gestionar las entradas de sensores, como cámaras y lidar, y tomar decisiones en tiempo real para mantener el vehículo seguro y en la carretera. Su capacidad de multitarea lo hace ideal para esta tarea.

### 1.5. Cortex-M4 🎯

Similar al M3, pero con una ventaja adicional: capacidades de DSP (procesamiento de señales digitales) y punto flotante. Es ideal para aplicaciones de procesamiento intensivo, como robótica y sistemas de audio. Si necesitas un procesador que pueda enfrentar cálculos intensivos, el Cortex-M4 está a la altura del desafío.

**Ejemplo**: **Sistema de Procesamiento de Audio en un Altavoz Inteligente**

Imagina un altavoz inteligente que puede responder a comandos de voz y reproducir música con calidad de estudio. El Cortex-M4 podría manejar el procesamiento de señales digitales (DSP) para mejorar la calidad del sonido y permitir comandos de voz precisos.


Así que aquí lo tienes, un vistazo rápido a las subfamilias de procesadores Cortex-M. Cada uno tiene su propio encanto y se adapta a diferentes necesidades. ¡Prepárate para sumergirte en el emocionante mundo de los microcontroladores ARM! 😊



## 2. Ventajas del Conjunto de Instrucciones Thumb

¡Vamos a explorar esto! El conjunto de instrucciones Thumb de ARM es como un atajo inteligente para reducir el tamaño del código. Las instrucciones Thumb son más compactas, lo que significa que ocupan menos espacio en la memoria. Esto es esencial en dispositivos con recursos limitados. Al reducir el tamaño del código, aumentamos la densidad de código, lo que permite almacenar más instrucciones en la misma cantidad de memoria. Es como un juego de tetris con código, ¡optimizando cada espacio disponible!

🧠`Por ende, el set de instrucciones Thumb es una característica inteligente de los procesadores ARM que permite una mayor densidad de código.` 💡

Imagina que tienes un programa de software, y quieres que ocupe la menor cantidad de memoria posible, especialmente en dispositivos con `recursos limitados` como los sistemas embebidos. Aquí es donde entra en juego el set de instrucciones Thumb, 👾 el set de instrucciones Thumb utiliza instrucciones de 16 bits en lugar de las instrucciones de 32 bits del conjunto completo de instrucciones ARM, esto significa que, en general, el código generado con Thumb es más compacto y ocupa menos espacio de memoria. 👍 Entonces, la respuesta a la pregunta 2. ¿Por qué se dice que el set de instrucciones Thumb permite mayor densidad de código? es que el set de instrucciones Thumb permite una mayor densidad de código porque utiliza instrucciones más pequeñas y compactas, lo que ahorra espacio de memoria y es ideal para dispositivos con recursos limitados. 😎

Referencia: [ARM Thumb Instruction Set](https://developer.arm.com/documentation/ddi0210/c/)
Aplicabilidad: [ARM Thumb Instruction Set](https://developer.arm.com/documentation/ddi0210/c/)

## 3. Arquitectura Load-Store


Imagina que tienes una caja de herramientas y una estantería llena de libros. En la arquitectura load-store, tratamos la memoria como nuestra estantería de libros y los registros como nuestra caja de herramientas. Cuando necesitamos trabajar con datos, como sumar dos números, primero debemos traer esos números de la estantería (memoria) y colocarlos en nuestra caja de herramientas (registros), usamos instrucciones especiales de carga (load) para tomar datos de la memoria y guardarlos en nuestros registros.

Luego, realizamos las operaciones matemáticas y lógicas que necesitamos en nuestra caja de herramientas, aquí es donde ocurren las verdaderas "chispas" de la computación. Finalmente, cuando hemos terminado con nuestros datos, devolvemos los resultados a la estantería (memoria) utilizando instrucciones de almacenamiento (store), así, otros programas o partes de nuestro programa pueden acceder a esos datos en el futuro.

🧠`La arquitectura load-store nos ayuda a ser organizados y eficientes, ya que todas nuestras operaciones de datos ocurren en nuestros registros generales, lo que hace que todo sea más rápido y eficiente.` 💡


<p align="center" width="100%">
    <img width="33%" src="https://github.com/Kzamudioq/AdM_workspace/assets/138271936/49bf9fdf-23de-427c-ad74-9699a55909b2"> 
</p>

Recuerda que en esta arquitectura, no realizamos operaciones de datos directamente en la memoria principal; todo pasa por nuestros registros. ¡Es como una coreografía de baile perfectamente coordinada! 💃💻

Referencia: [Arquitectura load-store](https://www.embedded.com/the-importance-of-the-load-store-architecture/)

## 4. Mapa de memoria de la familia Cortex-M

Por supuesto, estaré encantada de explicar la familia Cortex-M sigue un mapa de memoria típico para sistemas embebidos. La memoria flash se utiliza para almacenar el código, mientras que la RAM almacena datos. Los registros forman parte del procesador y se utilizan para operaciones de procesamiento. Los periféricos, como puertos de entrada/salida y temporizadores, se mapean en direcciones de memoria específicas para que el procesador pueda interactuar con ellos de manera eficiente. :blush:

<p align="center" width="100%">
    <img width="70%" src="https://github.com/Kzamudioq/AdM_workspace/assets/138271936/05855047-0c33-44c5-aa4b-b9f7df43ae4b"> 
</p>

En la anterior imagen que evidencia el mapa de memoria de la familia se define que ARM ha definido un espacio de direcciones de memoria estandarizado que es común a todos los núcleos Cortex-M. Esto es realmente genial porque garantiza que el código sea portátil entre diferentes fabricantes de chips. Ahora, este espacio de direcciones tiene un ancho de 4 gigabytes (sí, ¡gigabytes!) debido a la línea de dirección de 32 bits, y está organizado en varias subregiones, cada una con diferentes funciones lógicas.

Primero, tenemos los primeros 512 megabytes dedicados al área de código. Todos los procesadores Cortex-M asignan el área de código comenzando en la dirección 0x00000000, esta área es esencial, ya que incluye el puntero al comienzo de la pila (generalmente ubicado en SRAM) y la tabla de vectores de interrupción del sistema.

Luego, hay un área que comienza en la dirección 0x08000000, la cual está vinculada a la memoria flash interna de la MCU (Unidad de Control de Microprocesadores). Esta es la zona donde reside el código del programa. Lo interesante es que, con una configuración de arranque específica, esta área también tiene un alias de dirección en 0x00000000. Esto significa que puedes acceder al contenido de la memoria flash tanto desde la dirección 0x08000000 como desde 0x00000000. ¡Muy versátil!

Además, existe una región llamada "Memoria del sistema", que es una región ROM llena de un cargador de arranque oficial preprogramado, este cargador de arranque se puede usar para cargar código desde varios periféricos, como USART, USB y bus CAN. Es como la puerta de entrada a la funcionalidad del sistema.

Finalmente, tenemos la región de "Option Bytes" (Bytes de Opciones), que contiene indicadores de bits que se pueden usar para configurar varios aspectos de la MCU. Estos aspectos pueden incluir cosas como protección de lectura flash, vigilancia de hardware, modo de arranque, y más. La configuración de estos bytes de opción es específica de cada microcontrolador, lo que permite ajustar la MCU según tus necesidades particulares. 😊🌟

Referencia: [Mapa de memoria de ARM Cortex-M](https://www.codeinsideout.com/blog/stm32/intro/#memory-map)

## 5.  “shadowed pointers”  vs PSP vs el MSP 😊

Los "shadowed pointers" (Punteros sombreados) del PSP (Program Stack Pointer) y el MSP (Main Stack Pointer) son registros adicionales que permiten guardar y restaurar de manera rápida el estado de las pilas de programas en el Cortex-M. Esto es útil porque, en situaciones como la manipulación de interrupciones, se pueden cambiar las pilas rápidamente sin perder datos importantes. Por ejemplo, al gestionar múltiples tareas en un sistema operativo en tiempo real, los "shadowed pointers" facilitan la conmutación entre las pilas de diferentes tareas de manera eficiente. 👍

### 6. Modos de privilegio y operación del Cortex M, sus relaciones y cómo se conmuta de uno al otro. 🔄

- El Cortex-M tiene dos modos de operación principales: 🧠`el modo Thread (Hilo)`🧠 y 🧠`el modo Handler (Manejador)`🧠. El modo Thread es donde se ejecuta el código de usuario, mientras que el modo Handler es donde se manejan las excepciones y las interrupciones.
- Para cambiar entre estos modos, generalmente se utiliza una instrucción especial llamada "SVC" (Supervisor Call) o al producirse una excepción. Por ejemplo, cuando ocurre una excepción de interrupción, el procesador cambia del modo Thread al modo Handler para manejar la interrupción y luego vuelve al modo Thread cuando termina. ¡Así de versátil es el Cortex-M! 🚀

### 7. Modelo de registros ortogonal 🤓

El modelo de registros ortogonal significa que los registros del procesador tienen un conjunto coherente de operaciones que se pueden aplicar a cualquier registro de la misma categoría. Por ejemplo, en el Cortex-M, las operaciones aritméticas como sumar, restar o multiplicar se pueden aplicar de la misma manera a cualquier registro general, lo que hace que el código sea más compacto y fácil de escribir. 📜

## 8.  Ventajas presenta el uso de instrucciones de ejecución condicional (IT) 🤯

Las instrucciones de ejecución condicional (IT, por sus siglas en inglés) permiten que ciertas operaciones se realicen solo si se cumple una condición específica. Esto ahorra ciclos de reloj y mejora la eficiencia del código. Por ejemplo, en una instrucción IT, podríamos tener un bloque de código que se ejecute solo si una bandera está en un estado particular, como el siguiente:

  ```assembly
  IT EQ             ; Ejecutar siguiente instrucción si la bandera Z (igual) está activa
  ADDS r0, r1, r2  ; Sumar r1 y r2 y almacenar el resultado en r0
  ```

 ## 9. Excepciones más prioritarias (reset, NMI, Hardfault). 😮

- **Reset:** Esta es la excepción más prioritaria y ocurre al encender o reiniciar el microcontrolador. Restablece todos los registros y configuraciones a sus valores iniciales.
- **NMI (Non-Maskable Interrupt):** Esta excepción tiene la segunda prioridad más alta y no se puede deshabilitar. Se utiliza para situaciones críticas que deben ser manejadas sin importar el estado del procesador.
- **Hardfault:** Esta excepción ocurre cuando se detecta un error grave en la ejecución del código. Es una señal de que algo está muy mal y generalmente se usa para depuración.

## 10. Funciones principales de la pila. ¿Cómo resuelve la arquitectura el llamado a funciones y su retorno? 📚

La pila es una estructura de datos fundamental en la programación. En Cortex-M, se utiliza para almacenar direcciones de retorno, registros y otros datos temporales durante las llamadas a funciones. Cuando se llama a una función, la dirección de retorno se almacena en la pila, junto con otros registros que deben preservarse. Cuando la función completa su ejecución, la dirección de retorno se recupera de la pila y el programa vuelve a donde se llamó a la función. Esto permite que las funciones se llamen de manera anidada sin perder la pista de dónde regresar. 🔄

## 11. Describa la secuencia de reset del microprocesador.

El proceso de reset en un microprocesador Cortex-M sigue una secuencia definida:
  1. Al encender o reiniciar el microprocesador, se carga la dirección de inicio desde la dirección de reset (generalmente 0x00000000).
  2. Se ejecuta el código en la dirección de reset, que suele ser un programa de inicio que configura el sistema.
  3. El programa de inicio configura la pila, el espacio de direcciones y otros registros.
  4. Luego, se llama a la función `main()` del programa de usuario, y el programa comienza su ejecución normal.

## 12. ¿Qué se entiende por “core peripherals”? ¿Qué diferencia existe entre estos y el resto de los periféricos? 🤖

- Los "core peripherals" (periféricos centrales) son periféricos integrados directamente en el núcleo del procesador Cortex-M. Estos periféricos, como el NVIC (Nested Vectored Interrupt Controller) y el SysTick, son esenciales para el funcionamiento del procesador y siempre están presentes en cualquier implementación de Cortex-M.
- La diferencia clave entre los "core peripherals" y otros periféricos es que los "core peripherals" son parte fundamental del funcionamiento del procesador, mientras que los otros periféricos pueden variar según el fabricante y la aplicación específica.
