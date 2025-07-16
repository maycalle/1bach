# 1. Introducción a los sistemas informáticos

## 1.1 ¿Qué es un sistema informático?

Un **sistema informático** es un conjunto de elementos interconectados que trabajan de forma coordinada para **recibir, procesar, almacenar y transmitir información** de forma automática y eficiente. Su objetivo es realizar tareas que van desde operaciones básicas (como escribir un documento) hasta procesos complejos (como simular un clima o diagnosticar una enfermedad).

Está compuesto por:

- **Hardware:** los componentes físicos del sistema.
- **Software:** los programas que indican al hardware qué hacer.
- **Datos:** la información que se introduce, procesa y produce.

**Ejemplos de sistemas informáticos:**

- Un *ordenador personal* con sus periféricos y sistema operativo.
- Un *cajero automático* que procesa transacciones bancarias.
- Un *smartphone* que ejecuta apps, recibe datos y muestra resultados.
- Una *impresora multifunción con Wi-Fi y pantalla táctil**, que guarda trabajos en cola y puede recibir archivos desde la nube.

**Ejemplos de sistemas que NO se consideran sistemas informáticos:**

- Una *calculadora básica*:	aunque tiene componentes electrónicos, no ejecuta software programable ni guarda datos.
- Un *reloj digital sencillo*: solo muestra la hora mediante circuitos fijos, sin procesamiento programable.
- Una *cámara desechable con flash*: usa componentes electrónicos, pero no almacena ni procesa información digital.

👉 **RECUERDA:** Para que algo sea un sistema informático, debe procesar información de forma automatizada mediante hardware, software y datos. Si falta uno de esos elementos, no lo es.

## 1.2 Componentes de un SI

### 1.2.1 Hardware 

El **hardware** es la parte física y tangible del sistema. Se divide en:

- **Unidad central de procesamiento (CPU):** ejecuta instrucciones.
- **Memoria:** almacena datos temporalmente (RAM, caché).
- **Almacenamiento secundario:** guarda información de forma persistente (discos duros, SSD, unidades USB).
- **Periféricos:**
    - **Entrada:** teclado, ratón, escáner.
    - **Salida:** pantalla, impresora.
    - **Mixtos:** pantalla táctil, webcam, unidades de almacenamiento externas.

### 1.2.2 Software

El **software** es el conjunto de instrucciones y programas que controlan el hardware. Se clasifica en:

- **Sistema operativo:** gestiona los recursos del sistema (Windows, Linux, Android, macOS).
- **Software de aplicación:** permite realizar tareas específicas (navegadores, procesadores de texto, videojuegos).
- **Software de desarrollo:** herramientas para crear otros programas (editores de código, compiladores, entornos IDE).

Hoy en día muchas apps funcionan directamente en la web, sin necesidad de instalar nada (como Google Docs o Canva), gracias al desarrollo del **cloud computing**.

## 1.3 Relación entre hardware y software

- El **hardware sin software** no tiene instrucciones que seguir; es como un cuerpo sin cerebro.
- El **software sin hardware** no puede ejecutarse; necesita un medio físico para funcionar.

Esta **relación simbiótica** hace que el desarrollo de uno influya directamente en el otro:

- **Nuevos procesadores** → programas más complejos y potentes.
- **Nuevos programas** → necesidad de mejorar el hardware para ejecutarlos correctamente.

**EJEMPLO:** Para jugar a un viodejuego moderno en resolución 4K se requiere:

- Una GPU avanzada (hardware) y
- Un motor gráfico optimizado (software), como *Unreal Engine* o *Unity*.

## 1.4 Arquitectura de Von Neumann

La **arquitectura de Von Neumann** es el modelo sobre el que se basan la mayoría de los ordenadores actuales. Fue propuesta en **1945** por el matemático **John Von Neumann**, y su principal aportación fue organizar todos los componentes del ordenador de forma lógica y funcional.

### 1.4.1 ¿Por qué fue revolucionaria?

Antes, las computadoras se diseñaban para tareas fijas y era necesario modificar físicamente el hardware para cambiar de programa. 

Gracias a la arquitectura de Von Neumann se puede:

- Cambiar de programa sin cambiar el hardware.
- Usar un ordenador para múltiples tareas.
- Tener sistemas más flexibles, programables y potentes.

### 1.4.2 Componentes principales 

#### 1. Unidad Central de Procesamiento (CPU)

La CPU es el **cerebro del sistema**. Su función es **ejecutar instrucciones** paso a paso. Está compuesta por:

- **Unidad de Control (CU):** dirige el tráfico dentro del ordenador. Interpreta las instrucciones y organiza qué componente debe hacer qué, y cuándo.
- **Unidad Aritmético-Lógica (ALU):** realiza operaciones matemáticas (sumas, restas, comparaciones) y lógicas (como comprobar si algo es verdadero o falso).
- **Registros:** pequeñas memorias dentro de la CPU donde se almacenan temporalmente los datos que están siendo utilizados en ese momento. Son extremadamente rápidos, pero de muy poca capacidad.

#### 2. Memoria principal (RAM)

La memoria principal es donde se cargan **los programas y datos que la CPU necesita ejecutar en ese momento**. 

Se guarda:

- El código que el procesador va a ejecutar.
- Los datos que necesita para trabajar.

Esta es una de las claves de la arquitectura de Von Neumann: **datos e instrucciones en la misma memoria**. Antes de esta idea, se usaban memorias separadas, lo que era mucho más limitado.

💡 Ejemplo: cuando abres un videojuego, su código y la información del jugador (nivel, puntuación, etc.) se cargan en la RAM.

#### 3. Buses

Los buses son **caminos por los que circula la información** dentro del ordenador. Son como autopistas internas. Hay tres tipos principales:

- **Bus de datos:** transporta los datos que se están procesando.
- **Bus de direcciones:** indica dónde se encuentran los datos o instrucciones dentro de la memoria.
- **Bus de control:** coordina las señales que activan y desactivan cada componente.

**Analogía:** si un ordenador fuese una ciudad, los buses serían las carreteras que conectan todos los edificios (CPU, memoria, periféricos).

#### 4. Dispositivos de Entrada/Salida (E/S)

Son los componentes que permiten al sistema comunicarse con el exterior:

- **Entrada:** ratón, teclado, cámara, micrófono…
- **Salida:** pantalla, impresora, altavoces…

Estos dispositivos **no forman parte del núcleo de la arquitectura**, pero son necesarios para que el sistema informático sea útil para el usuario.

### 1.4.3 Características clave del modelo Von Neumann

| Característica             | Explicación                                                                 |
|----------------------------|------------------------------------------------------------------------------|
| Memoria unificada          | Datos e instrucciones se almacenan en el mismo espacio de memoria.          |
| Ejecución secuencial       | Las instrucciones se ejecutan una tras otra, en orden.                      |
| Flexibilidad               | Se puede cambiar el programa sin modificar el hardware.                     |
| Reutilización del hardware | El mismo hardware sirve para ejecutar diferentes programas. 

## 1.5 Resumen 

En esta unidad hemos aprendido qué es un sistema informático y cuáles son sus componentes fundamentales: hardware, software y datos. Un dispositivo solo se considera sistema informático si integra esos tres elementos y procesa información de forma automatizada.

Hemos distinguido ejemplos reales de sistemas informáticos frente a otros que no lo son, como relojes digitales básicos o cámaras desechables. También hemos comprendido la dependencia mutua entre hardware y software, ya que uno no puede funcionar correctamente sin el otro.

Por último, hemos estudiado la arquitectura de Von Neumann, base de la mayoría de los ordenadores actuales. Este modelo organiza el sistema en torno a una CPU, una memoria unificada, buses de comunicación y dispositivos de entrada/salida, permitiendo flexibilidad y reutilización del hardware con solo cambiar el software.


