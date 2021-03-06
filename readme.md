# Flujo de Temperatura en un bloque de madera de pino

Esto es el ejercicio 4 de la practica final de la asignatura metodos de
 simulaci贸n y modelado de la convocatoria ordinaria del curso  2021/22.



## Comenzando 馃殌

_Estas instrucciones te permitir谩n obtener una copia del proyecto en funcionamiento en tu m谩quina local para prop贸sitos de desarrollo y pruebas._


### Pre-requisitos 馃搵

Para poder ejecutar el codigo es necesario utilizar [FlexPDE](https://www.pdesolutions.com/v6student.html).


### Instalaci贸n y Configuraci贸n 馃敡

Una vez descargado el proyecto encontramos la siguiente estructura de carpetas
```
.
鈹溾攢鈹? src
鈹斺攢鈹? readme.md
```    

* en la carpeta _src_ encontramos el codigo fuente de la aplicaci贸n

## Enunciado

Escriba un script en FlexPDE para obtener la temperatura y los vectores 
correspondientes al flujo de calor del sistema descrito a continuaci贸n.


El sistema est谩 formado por un bloque de madera de pino. El bloque de madera
de pino tiene una conducci贸n t茅rmica anis贸tropa, siendo su constante de 
conductividad diferente en la direcciones x e y. La conductividad t茅rmica en la 
direcci贸n del eje X es kx = 0.15W/(m路K) y en la direcci贸n del eje Y es ky = 0.36 
W/(m路K).


En la superficie superior del bloque de madera hay un calefactor el茅ctrico que
tiene una anchura de 0.02 m. El calefactor produce calor a una tasa constante
de 500 W/m2. La superficie inferior del bloque de madera se mantiene a una
temperatura constante de 300 K. El resto de lados del bloque de madera est谩n
bien aislados.

El sistema se trata como un problema bidimensional. En la figura se muestra una
secci贸n transversal, en la cual el bloque tiene una forma cuadrada de lado 0.2 m.
La l铆nea negra m谩s gruesa indica la superficie que est谩 calefactada.
![seccionDelBloqueDeMadera](/img/seccionDelBloqueDeMadera.png?raw=true "seccionDelBloqueDeMadera")

Este fen贸meno se describe mediante la ecuaci贸n diferencial siguiente:
![ecuacionDiferencial](/img/ecuacionDiferencial.png?raw=true "ecuacionDiferencial")

donde T es la temperatura.

Escriba el c贸digo del script de FlexPDE para obtener un gr谩fico de las l铆neas de
temperatura y un gr谩fico vectorial del flujo de calor. Las componentes x e y del
flujo de calor son, respectivamente, las siguientes:

![componentesXY](/img/componentesXY.png?raw=true "componentesXY")
## Autores 鉁掞笍


* **Victor Fag煤ndez Poyo** - *Trabajo Inicial* - [vincitori-dev](https://github.com/vincitori-dev)



