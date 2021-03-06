# Introducción a la Consola y a los Scripts en R

## La Consola

Es una ventana que nos permite comunicarnos al motor de R. Esta ventana acepta **comandos** en el lenguaje de R y brinda una respuesta (resultado) a dichos comandos. 

Los comandos son instrucciones escritas **para una computadora** en un **lenguaje de cómputo**, en este caso **R**. A un conjunto de comandos se le llama **código**. 

Por ejemplo, le podemos pedir a R que sume 1+1 así:

```{r, eval=FALSE}
1+1
```    

La consola se distingue por tener el símbolo `>` seguido de un cursor parpadeante que espera a que le demos instrucciones (cuando recién abrimos R además muestra la versión que tenemos instalada y otra info).

Tu Consola debe verse más o menos así después del ejemplo anterior:

![Consola](Consola.PNG)


## Scripts
Un **script** es un archivo de nuestros análisis que es:

* un archivo de texto plano (**¡¡NO WORD!!**)
* permanente,
* repetible,
* antoado,
* compartible y 
* compatible con otras plataformas

En otras palabras, un script es una recopilación por escrito de las instrucciones que queremos enviar a la consola, de modo que al tener esas instrucciones cualquiera pueda repetir el análisis tal cual se hizo. 

El script consta de dos tipos de texto: 

**1.** El **código** (comandos) que queremos que R ejecute, en el órden que queremos que lo ejecute.

En análisis de R el código involucra:

* Instrucciones de cómo cargar y manipular datos.   
* Análisis de datos paso por paso.
* Instrucciones para construir figuras a partir de datos y resultados.

Es decir lo mismo que escribiríamos en la Consola para hacer un análisis, pero guardado en un archivo de texto que tiene todos los comandos juntos y que podemos abrir para **repetir** o **compartir** el análisis.

**2.** Comentarios escritos **para un ser humano** en un **lenguaje de humanos**, dígase no solo en español, sino que nos permita entender qué hace el código, qué tipo de información requiere y cualquier otra cosa que una persona cualquiera necesite para poder utilizar el código del script de forma correcta.


Para que la computadora distinga entre el código y los comentarios para humanos se utiliza el símbolo `#`. Todo el texto a la *derecha* del símbolo `#` será ignorado por la computadora, aunque sí "se imprima" en la Consola. 


Un script muy sencillo podría verse así:

![Script](Script.PNG)


"Ejemplo_script.R" es el nombre del archivo, es decir, que este texto es un **archivo de texto** (con terminación .R en vez de .txt) que vive en mi computadora.

![dondeEjemplo_script](dondeEjemplo_script.PNG)

## Importancia de los scripts

Recapituando, un script es un archivo de texto: 

* permanente,
* repetible,
* antoado,
* compartible y 
* compatible con otras plataformas

Es decir que permiten que cualquiera (empezando por quién hizo el análisis) sepa cómo se hizo análisis, lo pueda repetir y se lo pueda compartir a otra persona. Estos son los principios básicos de la **investigación reproducible** y una de las **mayores ventajas de R**.


