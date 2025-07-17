# 2. Representación de la información y sistemas de numeración

## 2.1 ¿Cómo entienden los ordenadores la información?

Un ordenador **no entiende palabras, imágenes ni sonidos como lo hacemos las personas**: todo lo transforma en combinaciones de ceros y unos. A estas unidades mínimas de información las llamamos **bits**. Cada bit puede representar **dos estados: 0 o 1**, que se corresponden con un pulso eléctrico apagado o encendido. Todo lo que ocurre en un ordenador parte de ahí.

## 2.2 Unidades de medida de la información

En informática medimos la cantidad de información que usamos con una unidad básica: **el bit**. Agrupando 8 bits obtenemos un **byte**, suficiente para representar una letra o símbolo. A partir de ahí, usamos múltiplos como el *kilobyte*, *megabyte* o *terabyte*, que te suenan porque aparecen en móviles, discos duros o archivos.

Esta tabla te puede ayudar a ver la escala de tamaños:

| Unidad     | Abreviatura | Equivalencia aproximada | ¿Dónde lo has visto?                             |
|------------|-------------|--------------------------|--------------------------------------------------|
| Byte       | B           | 8 bits                   | Una letra o número en un archivo                 |
| Kilobyte   | KB          | 1.024 bytes              | Un documento de texto sencillo                   |
| Megabyte   | MB          | 1.024 KB                 | Una canción en formato MP3 (~3–5 MB)             |
| Gigabyte   | GB          | 1.024 MB                 | Capacidad de una memoria USB (8–64 GB)           |
| Terabyte   | TB          | 1.024 GB                 | Disco duro de un ordenador o consola (1–2 TB)    |


!!! example "EJEMPLO"
    
    Una foto tomada con tu móvil puede ocupar 3 o 4 MB. Un videojuego puede ocupar más de 100 GB. ¡Imagina la cantidad de información que eso representa!


## 2.3 El sistema binario

Los ordenadores, a diferencia de nosotros, no pueden contar del 0 al 9. Como hemos visto, sus circuitos trabajan con dos únicos estados: **encendido (1)** y **apagado (0)**. Por eso utilizan el **sistema binario**, una forma de representar cantidades utilizando solo dos cifras: 0 y 1. 

Vamos a ver cómo funciona, y para eso, primero vamos a recordar cómo lo hacemos nosotros.

### 2.3.1 ¿Cómo contamos nosotros?

En nuestra vida diaria usamos el **sistema decimal**, basado en **diez cifras (del 0 al 9)**. Cada posición en un número tiene un valor que depende de una **potencia de 10**.

!!! example "Sistema decimal"

    El número decimal 345 se calcula así: 345 = 3×100 + 4×10 + 5×1 = 300 + 40 + 5

Cuanto más a la izquierda está una cifra, más vale. A esto se le llama **valor posicional**.

### 2.3.2 ¿Cómo cuentan los ordenadores?

En informática, todo se basa en dos estados eléctricos:
- **0 → apagado**
- **1 → encendido**

Estos estados se representan mediante **bits** (dígitos binarios), que son gestionados por millones de transistores dentro del procesador. Cada bit representa una **potencia de 2**, y con combinaciones de varios bits podemos representar cualquier número o dato.

Veamos cómo funciona el valor posicional en binario. En lugar de potencias de 10, usamos potencias de 2.

!!! example "Sistema binario"

    El número binario 101 se calcula así: 1×2² + 0×2¹ + 1×2⁰ = 4 + 0 + 1 = 5

Así, el número decimal 5 se representa como 101 en binario. La lógica es la misma que en decimal, solo que usamos otra base (2 en lugar de 10).

### 2.3.3 Comparativa binario vs decimal

| Posición         | Sistema decimal               | Sistema binario            |
|------------------|-------------------------------|----------------------------|
| Base             | 10                            | 2                          |
| Cifras posibles  | 0–9                           | 0 y 1                      |
| Valor posicional | Potencias de 10 (10⁰, 10¹...) | Potencias de 2 (2⁰, 2¹...) |
| Ejemplo          | 345 = 3×10² + 4×10¹ + 5×10⁰   | 101 = 1×2² + 0×2¹ + 1×2⁰   |


## 2.4 Conversión entre sistemas

## 2.5 Otros sistemas: octal y hexadecimal

### 2.5.1 Octal (base 8)

Este sistema usa solo los dígitos del 0 al 7. Se utiliza a veces en programación y electrónica para representar grupos de 3 bits de forma más compacta.

Binario 101011 → Octal 53

### 2.5.2 Hexadecimal (base 16)

Más usado que el octal. El sistema hexadecimal emplea los números del 0 al 9 y las letras de la A a la F para representar los valores del 10 al 15.

Binario 1111 0000 = Hexadecimal F0

Ejemplo práctico: En diseño web, los colores se codifican con este sistema:
Rojo → #FF0000
Verde → #00FF00
Azul → #0000FF

## 2.6 Representación de los caracteres: ASCII y Unicode

¿Cómo sabe un ordenador que 01000001 significa la letra A? Para eso usamos códigos de representación.

El más básico y conocido es el código ASCII, que asigna un número a cada carácter del alfabeto, incluyendo letras, signos de puntuación y algunos símbolos.

Ejemplos:

- A → 65 → 01000001
- B → 66 → 01000010
- espacio → 32 → 00100000

Pero ASCII es limitado: solo incluye caracteres del alfabeto inglés. Para representar palabras en árabe, chino, o emojis como 😄, usamos un sistema más moderno llamado Unicode, que puede codificar más de 100.000 caracteres diferentes.

💡 Curiosidad: El emoji 😄 se representa como U+1F604 en Unicode.

## 2.7 Representación digital de imágenes, sonido y vídeo

### 2.7.1 Imágenes

Las imágenes digitales están formadas por píxeles, que son pequeños puntos de color. Cada píxel necesita una cierta cantidad de bits para representar su color. Por ejemplo, una imagen en color verdadero suele usar 24 bits por píxel (8 para rojo, 8 para verde y 8 para azul → sistema RGB).

Una imagen de 1920×1080 píxeles (Full HD), sin comprimir, puede ocupar más de 6 MB.

### 2.7.2 Sonidos

El sonido se convierte en datos mediante un proceso llamado muestreo, que consiste en tomar "fotografías" del sonido muchas veces por segundo. Cuantas más tomas, mejor calidad (pero más tamaño ocupa el archivo).

Una canción en formato MP3 de 3 minutos a 320 kbps puede ocupar unos 7 MB.

### 2.7.3 Vídeos

Un vídeo digital es una secuencia de imágenes más sonido. La cantidad de datos puede ser enorme.

Una película en calidad 4K puede ocupar entre 20 y 60 GB.