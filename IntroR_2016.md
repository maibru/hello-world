Breve Introducción a R
================
M. A. Ibañez
16 de septiembre de 2016

¿Qué es R?
==========

R es un sistema diseñado para realizar análisis estadísticos y gráficos.

Consiste de un lenguaje de programación (R) más un entorno iterativo con gráficos, comunicación con otros lenguajes como C, C++ y Fortran, *debugger* acceso a ciertas funciones del sistema y la posibilidad de ejecutar programas almacenados en ficheros (*scripts*).

El lenguaje de programación R lo comenzaron a escribirse **Ross Ihaka** and **Robert Gentleman** en el Departamento de Estadística de la universidad de Auckland, Nueva Zelanda.

Es un dialecto de S que fue diseñado en la década de los 80 del siglo pasado en los laboratorios de AT&T Bell por **Rick Becker**, **John Chambers** y **Allan Wilks**.

R tiene una pagina oficial en <http://www.R-project.org>.

Actualmente existe un grupo de personas dedicadas al desarrollo de R ([http://www.r-project.org/contributors.html](R%20Deveploment%20Core%20Team)).

Es software libre distribuido bajo licencia [http://www.r-project.org/COPYING](GNU%20General%20Public%20License).

R se puede ampliar facilmente utilizando paquetes. Con la distribución de R se instalan 8 paquetes. Se pueden obtener muchos más a través de la pagina oficial del proyecto R y cubren un amplio rango de moderna técnicas estadísticas.

¿Cómo Instalar R?
=================

R está disponible para los sistemas Windows, Linux y MacOS X.

Para obtener el archivo de instalación hay que seleccionar en [http://cran.r-project.org/mirrors.html](CRAN%20(The%20Comprehensive%20R%20Archive%20Network)) una dirección desde donde bajar el ejecutable.

Seleccionando para que sistema deseamos instalar R accedemos al directorio con el programa de instalación que debemos bajar a nuestro ordenador.

Una vez guardado, se jecuta y se siguen las instrucciones durante la instalación.

Para cualquier duda durante la instalacción es posible consultar [http://cran.es.r-project.org/doc/FAQ/R-FAQ.html](R-FAQ)

En concreto para Windows [http://cran.es.r-project.org/bin/windows/base/rw-FAQ.html](R%20for%20Windows%20FAQ).

¿Que documentación existe para R?
=================================

Si se desea, la distribución se instala con los siguientes manuales:

-   An Introduction to R (R-intro). Incluye información sobre los tipos de datos, elementos de programación, modelos estadísticos y gráficos

-   Writing R Extensions (R-exts). Describe el proceso de crear paquetes, escribir la documentación,...

-   R Data Import/Export (R-data). Una guía para importar y exportar datos en R

-   The R Language Definition (R-lang).

-   R Installation and Administration (R-admin).

-   R Internals (R-ints). (A partir de la versión R 2.4.0.)

Existe una documentación en línea para la mayoría de las funciones en R a la que podemos acceder tecleando .

Por ejemplo, para obtener información sobre la función solve, tecleamos:

``` r
help(solve)
```

alternativamente

``` r
?solve
```

Si deseamos información sobre la utilización de caracteres especiales entonces debemos poner el argumento entre comillas. Esto también debe realizarse con algunas palabras claves como :

``` r
help('[[')
help('if')
```

Esta documentación también está disponible en los formatos HTML y pdf, dependiendo de que opciones se hayan elegido para instalar R.

Libros que utilizan R:
----------------------

En la pagina oficial de R [http://www.r-project.org/doc/bib/R-books.html](en%20Documentacion) existe un lista de libros relacionados con R.

Los siguientes son algunos libros de especial interés.

-   P. Dalgaard (2002), 'Introductory Statistics with R', Springer: New York.
-   J. Fox (2002), 'An R and S-Plus Companion to Applied Regression', Sage Publications.
-   J. Maindonald and J. Braun (2003), 'Data Analysis and Graphics Using R: An Example-Based Approach', Cambridge University Press.
-   P. Murrell (2005), 'R Graphics', Chapman & Hall/CRC.
-   Robert Gentleman (2008). Bioinformatics with R. Chapman & Hall/CRC.
-   Robert Gentleman. R Programming for Bioinformatics. Computer Science & Data Analysis. Chapman & Hall/CRC.

El libro:

*W. N. Venables and B. D. Ripley (2002), 'Modern Applied Statistics with S'. Fourth Edition, Springer*: tiene una página Web en <http://www.stats.ox.ac.uk/pub/MASS4/> en la que se proporciona material adicional.

Ver también <http://www.stats.ox.ac.uk/pub/MASS3/Sprog/> para más información.

El libro:

*J. C. Pinheiro and D. M. Bates (2000), 'Mixed-Effects Models in S and S-Plus' , Springer*: es una excelente guía del paquete `nlme` para el uso de modelos de efectos mixtos, lineales y no lineales.

También existen documentos en lengua [http://cran.r-project.org/other-docs.html\#nenglish](no%20inglesa).

Existe una traducción al castellano por J.A. Ahumada del manual *R para principinates de E. Paradis* y del documento *An Introduction to R* por Andrés González y Silvia González.

La pagina Web [http://www.statmethods.net/index.html](Quick-R) de Robert I. Kabacoff es un excelente sitio sobre como utilizar R.

En general tecleando en Google `R` `statistic` se obtiene bastante información sobre R y su utilización.

    !! Cuidado con la información que se obtiene a través de internet. No siempre es fiable!!

¿Qué listas de correos existen para R?
======================================

Existen 4 listas de correos dedicadas a R:

-   R-announce. Lista con anuncios sobre el desarrollo de R y la disponibilidad de código nuevo
-   R-packages. Lista con anuncios sobre la mejora en paquetes o la disponibilidad de nuevos paquetes.
-   R-help. Es la lista más improtante sobre R, donde se discuten problemas y se aportan soluciones en la utilización de R.
-   R-help-es. La misma lista pero en español.
-   R-devel. Esta lista es para cuestiones y discusión sobre el dearrollo de R.

Información sobre estas y otras listas de correo y como subscribirse se puede obtener en la siguiente dirección <http://stat.ethz.ch/mailman/listinfo/>.

R Journal
=========

[R Journal](http://journal.r-project.org/index.html) es la revista de referencia del proyecto R. Consta de pequeños y medianos artículos que cubren temas que puden ser de interés para usurios y desarroladores de R tales como:

-   Add-on packages: Breves introducciones o comentarios de los paquetes de extensión de R.

-   Programmer's Niche: Sugerencias para la programación en R.

-   Help Desk: Consejos para los recién llegados que explica los aspectos de R que pueden no ser tan evidente en la lectura de los manuales y en las preguntas frecuentes.

-   Applications: Demostrar cómo una técnica nueva o existente puede ser aplicado en un área de interés utilizando R, proporcionando una nueva visión de estos análisis en R más allá de la aplicación específica.

También podemos encontrar las siguientes secciones:

-   Changes in R: las nuevas características de la última versión de R
-   Changes on CRAN: Nuevos paquetes, manuales,...
-   Add-on packages: Pequeñas introducciones o revisones de paquetes
-   Upcoming conferences: Anuncios de conferencias relacionadas con R

La consola de R
===============

Una vez instalado R aparecerá en el escritorio un acceso directo, si se ha seleccionado dicha opción al hacer la instalación. En el caso de que no aparezca, podemos ir a `Inicio/Todos los Programas/R` donde encontraremos el ejecutable para comenzar una sesión en R.

De esta forma se ejecutará la aplicación `Rgui.exe` que inicia una consola de windows (las siglas gui corresponden a Graphics User Interface) que será el entorno donde trabajaremos con R. En la figura se muestra la consola.

<!-- \begin{figure}[!htp] -->
<!-- \centering -->
<!-- \includegraphics[width=0.8\textwidth]{consola.png} -->
<!-- \caption{Consola en windows de R} \label{fig:fig1} -->
<!-- \end{figure} -->
![consola](consola.png)

La consola está diseñada para trabajar de forma interactiva, es decir mediante instrucciones o comandos que son tecleadas en la línea donde aparece el simbolo `>` y son ejecutadas al pulsar la tecla `Intro` o `Enter`. Al ejecutarse la instrucción se muestra en pantalla el resultado, en el caso de que exista, y vuelve a aparecer la línea con el `>` indicando que es posible introducir una nueva instrucción.

Por ejemplo, tecleamos la siguiente instrucción.

``` r
3+5
```

    [1] 8

La consola dispone de una serie de menús desplegables que facilitan determinadas tareas como cambiar de área de trabajo, cargar paquetes, instalar paquetes, acceder a la ayuda, etc.

Área de trabajo, Carpeta de trabajo
-----------------------------------

Todos los objetos que creamos en una sesión de R están almacenados temporalmente en el área de trabajo. Si deseamos terminar la sesión tecleando `q()`, o en el menú `Archivo/Salir`, nos preguntará si deseamos guardar una imagen del área de trabajo (crear un archivo).

Si seleccionamos `no` perderemos todo lo almacenado en el área de trabajo. En el caso de seleccionar la opción `si` lo guardará en un directorio o carpeta de trabajo con el nombre \*\* .RData\*\*.

Por defecto R, y salvo que se le diga lo contrario, asume que el directorio o carpeta de trabajo es la carpeta en la que está instalado.

Podemos cambiar la carpeta de trabajo utilizando el menú `Archivo/Cambiar dir..` e indicar que carpeta queremos utilizar.

Para seleccionar una carpeta de trabajo diferente y un nombre diferente para el área de trabajo podemos seleccionar en el menú `Archivo/Guardar Area de Trabajo`. En dicho caso es posible seleccionar la carpeta y el nombre que deseamos poner a la imagen del área de trabajo.

Es conveniente guardar la imagen con la extensión \*\* .RData\*\*. Para recuperar dicha imagen de trabajo seleccionamos en `Archivo/Cargar Area de Trabajo` y buscamos la carpeta y el nombre de la imagen deseados.

Al instalar R, se asocia de forma automática los archivos con extensión \*\* .RData\*\* a la aplicación **Rgui.exe**, de forma que si con el explorador de windows se pincha con el botón derecho del ratón inmediatamente se ejecuta la consola de R cargando dicha imagen. Esta es la forma más cómoda de trabajar con distintas áreas de trabajo en distintas carpetas.

R dispone de las funciones `getwd` y `setwd` para obtener y cambiar la carpeta de trabajo, respectivamente.

``` r
getwd()
setwd("G:/")
getwd()
```

R dispone de las funciones `save.image` y `load` que guardan y cargan imágenes de la misma manera que se ha indicado utilizando los menús.

``` r
save.image("C:\\clase\\ejercicio1.RData")
load("C:\\clase\\ejercicio1.RData")
```

El nombre del fichero y la ruta ha de ir entre comillas y las carpetas se separan utilizando la barra inclinadas a las derecha o dos barra inclindas a la izquierda.

Los archivos `script` son archivos de formato plano con instrucciones de R que podemos ejecutar.

En el menú `Archivo` podemos crear un nuevo script, abrir un script ya creado o ejecutar un script.

Comandos de R, funciones, etc.
==============================

El lenguaje R es un lenguaje de expresiones con una sintaxis simple.

Diferencia mayúsculas de minúsculas de forma que `A` y `a` son diferentes símbolos que pueden referirse a diferentes variables.

Normalmente se permiten cualquier tipo de símbolo con algunas excepciones para las palabras claves.

Los comandos elementales o son expresiones o asignaciones.

Si en un comando se proporciona una expresión esta es evaluada, mostrada en la consola y el valor se pierde.

``` r
3+5
```

    [1] 8

Una asignación también evalúa la expresión y el valor es asignado a la variable pero el resultado no se muestra en la consola.

La asignación se realiza con el símbolo `<-`

``` r
a<-3+5 # Para asignar se utiliza <-
a
```

    [1] 8

La asignación también puede realizarse utilizando el simbolo `=`

``` r
b=3+5
b
```

    [1] 8

`b` para indicarle que utilice el símbolo b en la asignación.

En estas notas utilizaremos el simbolo `<-`.

Los comandos pueden separase por `;` o por una nueva línea.

``` r
a<-3+5;b<-sqrt(a);a;b
a<-3+5
b<-sqrt(a) # sqrt es la función raiz cuadrada
a
b
```

Los comandos pueden agruparse en un único comando utilizando llaves `{ }`

``` r
{a<-3+5
b<-sqrt(a)
a
b}
```

    [1] 2.828427

Es posible insertar comentarios utilizando el símbolo `#`. Cualquier expresión hasta el final de la línea es un comentario. Los comentarios no son ejecutados en R.

``` r
a<-3+5 # a es la suma de 3+5
b<-sqrt(a) # b es la raiz cuadrada de a
# estos comentarios no se ejcutana
b
```

Si un comando no es completado al final de la línea, R utiliza por defecto el símbolo `+` y la siguiente línea es leída como input hasta que el comando está sintáticamente completado.

``` r
a<-3*
   5
a
```

R dispone de mecanismos para recuperar y ejecutar comandos previos. Las flechas verticales del teclado pueden utilizarse para avanzar hacia adelantes y hacia atrás en el historial de comandos.

Una vez el comando deseado es localizado se pueden utilizar las flechas horizontales del teclado para corregir, cambiar, borrar con la tecla `Supr` del teclado.

Las entidades que R crea y manipula son objetos. Durante una sesión los objetos se crean y almacenan en el área de trabajo.

Existen dos comandos, `objects` y `ls`, que nos permiten visualizar los objetos almacenados en el área de trabajo.

``` r
objects()
```

    [1] "a" "b"

``` r
ls()
```

    [1] "a" "b"

Para eliminar objetos podemos utilizar el comando `rm`

``` r
rm(a)
```

Para eliminar todos los objetos del área de trabajo podemos utilizar la siguiente combinación de los comandos `ls` y `rm`.

``` r
rm(list=ls(all=TRUE))
```

Este es un ejemplo como en R se combinan funciones para crear nuevas instrucciones.

En el menú `Misc` de la consola podemos encontrar `Listar objetos` y `Remover todos los objetos` que realizan las mismas tareas que las funciones descritas.

El área de trabajo puede guardarse permanentemente en el disco duro para futuras sesiones.

Al final de la sesión tenemos la opción de guardar el área de trabajo en el directorio de trabajo actual con un fichero denominado **.RData** junto con el historial de los comandos utilizado en la sesión bajo el nombre de **.Rhistory**.

Es recomendable utilizar distintos directorios de trabajo para distintos análisis. De esta forma se evitará confusión con los objetos creados.

Funciones y paquetes
--------------------

Muchos de los comandos utilizados en R son funciones diseñadas para realizar determinadas tareas. En general, las funciones tienen uno o varios argumentos algunos de los cuales es obligatorio asignarles un valor y otros tienen asignado un valor por defecto que podemos cambiar si deseamos.

Para dar valores a los argumentos utilizaremos el nombre del argumento = al valor deseado. Si no se indica el nombre del argumento se utilizará el orden de los mismos en la función. Una misma función puede tener distintas formas de operar según los argumentos utilizados.

Los paquetes son colecciones de funciones diseñados para realizar tareas especificas. R se instala por defecto con un conjunto de paquetes. Para ver que paquetes tenemos instalados podemos ir al menú `Paquetes/Cargar Paquetes` que nos mostrará los paquetes instalados con R.

Cuando ejecutamos `Rguiexe` se cargan en memoría una serie de paquetes, es decir podemos utilizar las funciones de dichos paquetes. Si un paquete no está cargado en memoria no podremo utilizar sus funciones.

La función `search` nos permite verificar los paquetes cargados en memoria y la posición en la que están (*entorno*).

``` r
search() # lista el camino de búsqueda de objetos
```

    [1] ".GlobalEnv"        "package:stats"     "package:graphics" 
    [4] "package:grDevices" "package:utils"     "package:datasets" 
    [7] "package:methods"   "Autoloads"         "package:base"     

Así, en la posición 1 se encuentra el área de trabajo que recoje los objetos creados por el usuario (`.GlobalEnv`). En la siguientes posiciones están los paquetes cargados, como por ejemplo el paquete `stats` diseñado para realizar análisis estadísticos.

El orden de posición es el orden en que R busca una función determinada comenzando a buscar en la posción 1 hasta que la encuentra en una determinada posición.

Si deseamos cargar en memoria alguno de los paquetes instalados lo podemos seleccionar de la lista obtenida en el menú `Paquetes/Cargar Paquetes` alternativamente utilizar la función `library` con el nombre del paquete como argumento. En este caso el paquete cargado pasa a la posción 2 desplazando a los demás paquetes una posición.

``` r
library(nlme)   # Carga el paquete nlme
search()
```

     [1] ".GlobalEnv"        "package:nlme"      "package:stats"    
     [4] "package:graphics"  "package:grDevices" "package:utils"    
     [7] "package:datasets"  "package:methods"   "Autoloads"        
    [10] "package:base"     

Antes de poder cargar un paquete en memoría tiene que estar instalado en el ordenador.

Para instalar nuevo paquetes utilizaremos el menú `Paquetes/Instalar paquetes` que nos abriara una ventana en la que nos pedirá que seleccionemos el servidor (mirror) más cercano. Una vez seleccionado dicho servidor despliega una ventana con todos los paquetes disponibles.

En la pagina oficial del proyecto R es posible acceder a la lista de los paquetes disponibles con la descripción de lo que hacen, quien lo ha desarrollado y algún documento de ayuda.

Los paquetes instalados se almacenan por defecto en la carpeta `library` dentro de la carpeta en la que está instalado R.

Cuando se actualiza a una nueva versión la forma más sencilla de no perder los paquetes instalados es copiar aparte las carpetas con los paquetes instalados que están en `library` y una vez instalada la nueva versión volver a copiar las carpetas de los paquetes en `library`. Con el Menú `Paquetes/Actualizar paquetes...` se pueden actualizar los paquetes instalados.

En [R for Windows FAQ, the best way to upgrade](http://cran.es.r-project.org/bin/windows/base/rw-FAQ.html#What_0027s-the-best-way-to-upgrade_003f), se detalla como actualizar a una nueva versión.

Vectores
========

La estructura de datos más sencilla con la que trabaja R es el vector. Un vector es un objeto en el que se han almacenado una colección de números y que tiene una sola dimensión.

Para crear un vector se utiliza la función `c()` que concatena valores o vectores.

``` r
# Para crear el vector se ha utilizado la función c() 
# que concatena valores o vectores
x<-c(10,3.4,5.6,7.0,2.3) 
x
```

    [1] 10.0  3.4  5.6  7.0  2.3

``` r
# utiliza la función c() para concatenar el vector x con 0 y con x
y<-c(x,0,x) 
y
```

     [1] 10.0  3.4  5.6  7.0  2.3  0.0 10.0  3.4  5.6  7.0  2.3

Los decimales en R son puntos y las comas sirven para separar los valores que deseamos alamcenar en el vector `x`.

La función `length` proporciona la longitud del vector.

``` r
length(x)
```

    [1] 5

``` r
length(y)
```

    [1] 11

Si los vectores se utilizan en expresiones aritméticas las operaciones se realizan elemento por elemento. Si los vectores implicados en la expresión no tienen la misma longitud, los de menor longitud se reciclan para que tengan la misma longitud que el vector de mayor longitud.

``` r
v<-2*x+y+1
```

    Warning in 2 * x + y: longitud de objeto mayor no es múltiplo de la
    longitud de uno menor

``` r
v
```

     [1] 31.0 11.2 17.8 22.0  7.9 21.0 17.8 15.6 20.6 12.6 23.3

Las operaciones aritméticas elementales son `+,-,*,/` y `^` o `**` para la potencia.

Además están también disponibles las funciones `log, exp, sin, cos, tan, sqrt,..`

La siguiente es una lista de funciones matemáticas que podemos utilizar:

``` r
  max(x) # máximo de x
  min(x) # mínimo de x
  range(x)  # máximo y mínimo de x
  length(x) # número de elementos de x
  sum(x)  # suma total de los elementos de x
  prod(x) # producto el producto de los elementos de x
  mean(x) # media de x
  sum(x)/length(x) # expresión equivalente
  abs(x) # valor absoluto de x
  var(x)  # varianza de x
  sum((x-mean(x))^2)/(length(x)-1) # expresión equivalente
  sd(x) # desviación tipica
  y<-numeric(0) # vector de longitud cero
  y<-c() # forma equivalente
  sort(x,decreasing=F) # ordena x en orden creciente
  sort(x,decreasing=T) # ordena x en orden decreciente
  order(x,decreasing=F) # proporciona la posición de los
                        # elementos de x cuando
                        # se ordenan en orden creciente
  order(x,decreasing=T) # proporciona la posición de los
                        # elementos de x cuando
                        # se ordenan en orden decreciente
```

No es necesario preocuparse si los números son enteros o reales o incluso complejo. Las operaciones internas se realizan en doble precisión.

Secuencias de números
---------------------

Disponemos de distintas funciones para generar secuencias de números.

``` r
1:10  # genera la secuencia de los 10 primeros enteros
```

     [1]  1  2  3  4  5  6  7  8  9 10

genera la secuencia de los 10 primeros enteros.

La función `seq` permite generalizar la generación de secuencias.

``` r
# otra forma alternativa con los nombre de los
# argumentos de la llamada
seq(from=20,to=30,by=2) 
```

    [1] 20 22 24 26 28 30

``` r

# otra forma alternativa con los nombres argumentos
# de la llamada en distinta posición
seq(to=30,by=2,from=20) 
```

    [1] 20 22 24 26 28 30

En este caso se han utilizado los nombres de los argumentos para asignar el inicio, el final y el paso de la secuencia. La misma función sin en el nombre de los argumentos pero manteniendo la posición será:

``` r
# la misma función sin el nombre de los argumentos pero
# manteniendo la posición   
seq(20,30,2) 
```

    [1] 20 22 24 26 28 30

``` r
seq(along=x) # genera la secuencia 1,2,3,...,length(x)
```

    [1] 1 2 3 4 5

genera la secuencia 1, 2, 3..., length(x).

La función `rep` permite repetir un número o vector las veces que deseamos.

``` r
rep(x,times=5) # repite el vector x 5 veces
```

     [1] 10.0  3.4  5.6  7.0  2.3 10.0  3.4  5.6  7.0  2.3 10.0  3.4  5.6
    [14]  7.0  2.3 10.0  3.4  5.6  7.0  2.3 10.0  3.4  5.6  7.0  2.3

repite el vector `x` 5 veces.

``` r
# repite cada elementos de x 5 veces antes de pasar al
# siguiente elemento                                  
rep(x,each=5) 
```

     [1] 10.0 10.0 10.0 10.0 10.0  3.4  3.4  3.4  3.4  3.4  5.6  5.6  5.6
    [14]  5.6  5.6  7.0  7.0  7.0  7.0  7.0  2.3  2.3  2.3  2.3  2.3

repite cada elemento del vector `x` 5 veces.

Valores lógicos, operadores lógicos y expresiones lógicas
---------------------------------------------------------

Además de trabajar con valores numéricos es posible trabajar con valores lógicos (TRUE (T), FALSE (F) y NA (no disponible).

``` r
# genera un vector de longitud la de x con valores  FALSE en
# aquellos elementos de x que no cumplen la expresión 
# y TRUE si la cumplen                      
x>3 
```

    [1]  TRUE  TRUE  TRUE  TRUE FALSE

`x>3` es una expresión lógica que genera un vector de longitud la de x con valores FALSE en aquellos elementos de x que no cumplen la expresión y TRUE si la cumplen.

Disponemos de los siguientes operadores lógicos:

    < menor que
    <= menor o igual que
    > mayor que,
    >= mayor o igual que
    == igual que
    != distinto que.

Además, es posible componer expresiones lógicas con `&` para la intersección y con `|` para la unión.

``` r
x>3 & x<5 # dos expresiones lógicas con y (intersección)
```

    [1] FALSE  TRUE FALSE FALSE FALSE

``` r
x>3 | x<5 # dos expresiones lógicas con o (unión)
```

    [1] TRUE TRUE TRUE TRUE TRUE

R indica si el resultado de una operación no es un número mediante el simbolo `NaN` (No a number) y utiliza el simbolo `NA` para indicar que dicho valor no existe (No avaiable). Las funciones `is.na` y `is.nan` nos premiten determinar si los valores de un objeto son `NA` o `NaN`.

``` r
xx<-sqrt(-3) # valor que no es un numero NaN
```

    Warning in sqrt(-3): Se han producido NaNs

``` r
is.na(xx)    # función para determinar si los valores de X son NA y NaN
```

    [1] TRUE

``` r
is.nan(xx)   # función para determina si los valores de x son NaN
```

    [1] TRUE

Vectores con caracteres
-----------------------

También es posible almacenar caracteres.

``` r
c("Pedro","Juan","Inés") # vector de caracteres
```

    [1] "Pedro" "Juan"  "Inés" 

La función `paste` concatena uno a uno los elementos. Con el argumento (`sep=`) podemos indicar que carácter pone entre los dos elementos que pega. Por ejemplo, para no dejar espacio entre ellos:

``` r
#  concatena uno a uno los elementos y  
#  no deja espacio entre ellos          
paste(c("x","y"),1:10,sep="") 
```

     [1] "x1"  "y2"  "x3"  "y4"  "x5"  "y6"  "x7"  "y8"  "x9"  "y10"

o bien para colocar el carácter `-` :

``` r
#  concatena uno a uno los elementos y 
#  pone - entre ellos                  
paste(c("x","y"),1:10,sep="-") 
```

     [1] "x-1"  "y-2"  "x-3"  "y-4"  "x-5"  "y-6"  "x-7"  "y-8"  "x-9" 
    [10] "y-10"

El vector más pequeño es reciclado hasta al canzar la longitud del vector más grande, en este caso 10.

Índices de un vector
====================

Es posible acceder a los elementos de un vector indicando su posición en el vector.

Existen diferentes posibilidades:

``` r
x[3] # selecciona el elemento de x que está en la posición 3
```

    [1] 5.6

selecciona el elemento de x que está en la posición 3.

``` r
x[1:3] # selecciona los tres primeros elementos de x
```

    [1] 10.0  3.4  5.6

selecciona los tres primeros elementos de `x`.

``` r
x[-(1:3)] # excluye los tres primeros
```

    [1] 7.0 2.3

excluye los tres primeros

``` r
# selecciona el primero, tercero y segundo en el orden
# indicado
x[c(1,3,2)]  
```

    [1] 10.0  5.6  3.4

selecciona el primero, tercero y segundo en el orden indicado.

También pueden utilizarse expresiones logicas.

``` r
x[x>5] # selecciona los valores de x que son mayores de 5
```

    [1] 10.0  5.6  7.0

selecciona los valores de `x` que son mayores de 5.

``` r
x[!is.na(x)] # selecciona los elementos de x que no son NA o NaN
```

    [1] 10.0  3.4  5.6  7.0  2.3

selecciona los elementos de `x` que no son `NA` o `NaN`.

La función `order` proporciona la posición de los elementos del vector ordenado de menor a mayor. Utilizada como indice de un vector es equivalente a la función `sort`.

``` r
x[order(x)] # equivalente a sort(x)
```

    [1]  2.3  3.4  5.6  7.0 10.0

``` r
sort(x)
```

    [1]  2.3  3.4  5.6  7.0 10.0

Existen funciones especiales para generar letras del Abecedario.

``` r
# genera un vector con las 5 primeras letras del abecedario
# en minúsculas
letters[1:5] 
```

    [1] "a" "b" "c" "d" "e"

genera un vector con las 5 primeras letras del Abecedario en minúsculas.

``` r
# genera un vector con las 5 primeras letras del
# abecedario en mayúsculas
LETTERS[1:5] 
```

    [1] "A" "B" "C" "D" "E"

genera un vector con las 5 primeras letras del Abecedario en mayúsculas.

Podemos asignar nombres a las posiciones de un vector utilizando la función `names` y aceder al valor en una posición utilizando dichos nombres.

``` r
# función que asigna nombres
# a los componentes de x
names(x)<-c("uno","dos","tres","cuatro","cinco") 
x
```

       uno    dos   tres cuatro  cinco 
      10.0    3.4    5.6    7.0    2.3 

``` r
x["uno"]
```

    uno 
     10 

``` r
x[c("uno","tres","cinco")]
```

      uno  tres cinco 
     10.0   5.6   2.3 

Es posible asignar valores a determinadas posiciones del vector `x`.

``` r
# a los elementos de x mayores de 5 le asigna el valor de 100
x[x>5]<-100 
x
```

       uno    dos   tres cuatro  cinco 
     100.0    3.4  100.0  100.0    2.3 

Factores
========

Son vector de caracteres que asigna o agrupa observaciones en categorías. Tienen especial interés en el análisis estadístico de datos que están agrupados por una o más variables.

Por ejemplo, podemos crear el vector `ed` como un vector numérico que recoge la energía digestible (Mcal/Kg MS) de 4 dietas utilizadas en un experimento para cebar **24** conejos, **6** conejos por cada dieta.

``` r
# vector numérico energía digestible Mcal/kg MS
# expande  el vector repitiendo cada valor 6 veces
ed<-c(2.99,2.67,2.48,2.33) 
ed<-rep(ed,each=6)  
ed
```

     [1] 2.99 2.99 2.99 2.99 2.99 2.99 2.67 2.67 2.67 2.67 2.67 2.67 2.48
    [14] 2.48 2.48 2.48 2.48 2.48 2.33 2.33 2.33 2.33 2.33 2.33

A partir del vector `ed` se va a generar el factor `trat` utilizando la función `factor`.

``` r
trat<-factor(ed) # genera el vector trat como factor
trat
```

     [1] 2.99 2.99 2.99 2.99 2.99 2.99 2.67 2.67 2.67 2.67 2.67 2.67 2.48
    [14] 2.48 2.48 2.48 2.48 2.48 2.33 2.33 2.33 2.33 2.33 2.33
    Levels: 2.33 2.48 2.67 2.99

``` r
levels(trat) # niveles del factor trat
```

    [1] "2.33" "2.48" "2.67" "2.99"

Con la función `levels` se renombran los niveles del factor `trat` asignando un vector con los nombres deseados.

``` r
levels(trat)<-c("D1","D2","D3","D4") # cambia el nombre de los niveles
trat
```

     [1] D4 D4 D4 D4 D4 D4 D3 D3 D3 D3 D3 D3 D2 D2 D2 D2 D2 D2 D1 D1 D1 D1
    [23] D1 D1
    Levels: D1 D2 D3 D4

El vector `ganp` es un vector que recoge la ganancia media de peso de los 24 conejos del experimento. En este ejemplo se van a generar 24 valores al azar de una normal de media 30 y desviación típica 5 utilizando la función `rnorm`.

``` r
# vector de ganancia media  de peso  generado al azar de una normal 
ganp<-rnorm(24,mean=30,sd=5)   
```

Disponemos pues, de dos vectores, el vector `ganp` que recoge la ganancia de peso de los 24 conejos y el vector `trat` que recoge que dieta ha recibido cada uno de los conejos.

Con la función `tapply` podemos calcular la media del vector `ganp` para cada nivel del factor `trat`

``` r
# calcula la media para cada nivel del factor ed
medias<-tapply(ganp,trat,mean)  
medias # vector de medias para cada nivel de ed
```

          D1       D2       D3       D4 
    28.80917 26.21695 30.73131 25.94859 

Podemos utilizar otro tipo de funciones distinta de `mean`, por ejemplo `length`.

``` r
# tabla de frecuencias de cada
# tratamiento en la muestra
frecuencias<-tapply(ganp,trat,length)  
frecuencias
```

    D1 D2 D3 D4 
     6  6  6  6 

La función `length` calcula el número de observaciones en cada nivel del factor `trat`, aunque para hacer esto es más conveniente utilizar la función `table`.

``` r
table(trat) # Más conveniente
```

    trat
    D1 D2 D3 D4 
     6  6  6  6 

Si utilizamos la función `sd` calculamos la desviación típica en cada nivel del factor `trat`.

``` r
tapply(ganp,trat,sd) # vector de desviaciones típicas
```

          D1       D2       D3       D4 
    3.578711 4.538255 3.859314 4.520972 

Si es necesario indicar algún argumento de la función se pone a continuación.

``` r
tapply(ganp,trat,mean,na.rm=TRUE)
```

          D1       D2       D3       D4 
    28.80917 26.21695 30.73131 25.94859 

calcula la media para cada nivel del factor `trat` y elimina del cálculo los elementos `NA`.

R dispone de otro tipo de factores, factores cuyos niveles tienen un orden determinado y que se crean con la función `ordered`.

``` r
# factor cuyos niveles tienen un orden determinado
Eding<-ordered(ed) 
Eding
```

     [1] 2.99 2.99 2.99 2.99 2.99 2.99 2.67 2.67 2.67 2.67 2.67 2.67 2.48
    [14] 2.48 2.48 2.48 2.48 2.48 2.33 2.33 2.33 2.33 2.33 2.33
    Levels: 2.33 < 2.48 < 2.67 < 2.99

Matrices o arreglos de 2 o más dimensiones
==========================================

Además de trabajar con vectores podemos trabajar con matrices o arreglos de más de dos dimensiones.

La función `array` permite crear arreglos con las dimensiones deseadas.

``` r
z<-array(1:24,c(3,4,2));z # array de dimensión 3
```

    , , 1

         [,1] [,2] [,3] [,4]
    [1,]    1    4    7   10
    [2,]    2    5    8   11
    [3,]    3    6    9   12

    , , 2

         [,1] [,2] [,3] [,4]
    [1,]   13   16   19   22
    [2,]   14   17   20   23
    [3,]   15   18   21   24

Para acceder a los elementos de un array podemos operar de la misma forma que con los vectores separando cada dimensión por una coma ( ,).

``` r
z[,,1]  # elementos de z en la posición 1 de la tercer dimensión
```

         [,1] [,2] [,3] [,4]
    [1,]    1    4    7   10
    [2,]    2    5    8   11
    [3,]    3    6    9   12

``` r
z[2,,]  # elementos de z en la fila 2
```

         [,1] [,2]
    [1,]    2   14
    [2,]    5   17
    [3,]    8   20
    [4,]   11   23

``` r
z[,3,]  # elementos de z en la columna 3
```

         [,1] [,2]
    [1,]    7   19
    [2,]    8   20
    [3,]    9   21

La función `matrix` es similar a la función `array` pero es especifica para crear matrices (arreglos de dos dimensiones).

``` r
x<-array(1:20,dim=c(4,5));x # Matriz de 4x5
```

         [,1] [,2] [,3] [,4] [,5]
    [1,]    1    5    9   13   17
    [2,]    2    6   10   14   18
    [3,]    3    7   11   15   19
    [4,]    4    8   12   16   20

x es una matriz de . Los elementos se almacenan por columna.

``` r
x<-matrix(1:20,nrow=4,ncol=5);x # forma alternativa
```

         [,1] [,2] [,3] [,4] [,5]
    [1,]    1    5    9   13   17
    [2,]    2    6   10   14   18
    [3,]    3    7   11   15   19
    [4,]    4    8   12   16   20

es otra forma alternativa indicando el número de columnas y filas.

Con el argumento se le indica que los elementos se almacenen por filas.

``` r
# Matriz de 4x5 almacena por fila
y<-matrix(1:20,nrow=4,ncol=5,byrow=T);y 
```

         [,1] [,2] [,3] [,4] [,5]
    [1,]    1    2    3    4    5
    [2,]    6    7    8    9   10
    [3,]   11   12   13   14   15
    [4,]   16   17   18   19   20

Podemos determinar el número de filas y columnas de una matriz utilizando las funciones `nrow` y `ncol`.

La función `dim` muestra ambos valores en un vector.

``` r
nrow(x) # número de filas de x
```

    [1] 4

``` r
ncol(x) # número de columnas de x
```

    [1] 5

``` r
# dimensión de x . Vector con dos elementos el número de filas y columnas
dim(x) 
```

    [1] 4 5

Podemos acceder a los valores de la matriz indicando la fila y columna.

``` r
x[2,3] # muestra el elemento (2,3) de x
```

    [1] 10

``` r
x[,2]  # muestra los elementos de la columna 2 de x
```

    [1] 5 6 7 8

``` r
x[3,]  # muestra los elementos de la fila 3 de x
```

    [1]  3  7 11 15 19

o también podemos crear submatrices.

``` r
y<-x[c(1,2),c(3,4)];y # submatriz de x
```

         [,1] [,2]
    [1,]    9   13
    [2,]   10   14

``` r
dim(y) # dimensión de y
```

    [1] 2 2

Del mismo modo que con los vectores podemos asignar nombres a las filas y columnas de las matrices utilizando la función `row.names` y `colnames`.

``` r
row.names(x)<-letters[1:nrow(x)]
colnames(x)<-LETTERS[1:ncol(x)]
x
```

      A B  C  D  E
    a 1 5  9 13 17
    b 2 6 10 14 18
    c 3 7 11 15 19
    d 4 8 12 16 20

``` r
x["b",] # muestra los valores de la fila b de x
```

     A  B  C  D  E 
     2  6 10 14 18 

``` r
x["c","D"] # muestra el valor de la fila c columna D
```

    [1] 15

``` r
dimnames(x) # muestra los nombres de las dos dimensiones
```

    [[1]]
    [1] "a" "b" "c" "d"

    [[2]]
    [1] "A" "B" "C" "D" "E"

la función `dimnames` muestra los nombres de las dos dimensiones.

A continuación se muestran otras funciones utiles para trabajar con matrices:

``` r
t(x) # traspuesta de la matriz x
lower.tri(x) # triangular inferior de x
y<-x[lower.tri(x)]<-NA;y # asigna NA a los elementos de la triangular
                           # inferior
upper.tri(x) # elementos de la triangular superior
x[upper.tri(x)] # muestra los valores de la triangular superior
d<-diag(x);d # muestra los elementos de la diagonal de x
diag(d) # crea una matriz cuadrada con su diagonal principal
          # formada por los elementos de d
diag(3) # forma una matriz identidad de dimensión 3x3
row.names(x)<-letters[1:nrow(x)] # asigna nombres a las filas de x
x["b",] # muestra los valores de la fila b de x
colnames(x)<-LETTERS[1:ncol(x)];x # asigna nombres a las columnas ed x
dimnames(x) # muestra los nombres de las dos dimensiones
x["c","D"] # muestra el valor de la fila c columna D
A<-matrix(1,nrow=4,ncol=4);A # matriz de unos de dimensión 3x2
B<-matrix(1:16,nrow=4,ncol=4);B # matriz de dimensión 2x3
A*B # multiplicación  elemento por elemento
A%*%B # multiplicación de matrices
C<-diag(d);C  # matriz diagonal con elementos de d
d%*%A%*%d # forma cuadrática d'Ad
d%*%d # forma cuadrática x'x
crossprod(d) # producto cruzado d'd. Más eficientes
t(A)%*%d # producto cruzado A'd
crossprod (A,d) # producto cruzado A'd. Más eficiente
d%*%t(d) # producto dd'
d%o%d  # producto outer
solve(C,d) # Resuelve el sistema Cx=d
solve(C) # inversa de C
# Resuelve el sistema Cx=d. Menos eficiente y numéricamente # más inestable
solve(C)%*%d 
           
d%*%solve(C,d) # forma cuadrática d'C-1d
d%*%solve(C)%*%d # Menos eficientes
cbind(A,B) # concatena por columnas las matrices A y B
rbind (A,B) # concatena por filas las matrices A y B
as.vector(B) # convierte la matriz B en un vector de longitud 16
```

Listas
======

La lista es un objeto formado por una colección de objetos a los que se les denomina componentes. Los componentes no tienen porque ser del mismo tipo. Es decir en una lista tenemos almacenados distintos tipos de objetos.

La función `list` permite crear las listas asignando nombres a cada uno de los componentes que la forman.

``` r
# lista formada por el nombre, apellidos
# telefoneo y email
agenda<-list(nombre="Pedro",primer.apellido="Martin",segundo.apellido=
   "Lopez",telf=915324569,email="ldf```dgf.com");agenda 
```

    $nombre
    [1] "Pedro"

    $primer.apellido
    [1] "Martin"

    $segundo.apellido
    [1] "Lopez"

    $telf
    [1] 915324569

    $email
    [1] "ldf```dgf.com"

Para acceder a los componentes de una lista podemos utilizar distintos procedimientos:

``` r
agenda[[1]] # muestra el primer componente
```

    [1] "Pedro"

``` r
agenda$nombre   # otra forma alternativa
```

    [1] "Pedro"

``` r
agenda[["nombre"]] # ora forma alternativa
```

    [1] "Pedro"

``` r
agenda[1] # algo diferente de agenda[[1]]
```

    $nombre
    [1] "Pedro"

Para obtener los nombres de los componentes de una lista utilizamos la función `names`

``` r
# proporciona los nombres de los componentes de la lista
names(agenda) 
```

    [1] "nombre"           "primer.apellido"  "segundo.apellido"
    [4] "telf"             "email"           

Muchos de los resultados que obtenemos en R cuando utilizamos las funciones de los paquetes son listas.

Marco de datos
==============

Los marcos o cuadros de datos son listas con características especiales. Puede entenderse como una matriz con columnas que corresponden a objetos de diferente tipo. Es la forma habitual que tiene R para manejar datos.

La función `data.frame` permite crear los marcos de datos.

Así podemos crear el marco de datos `dietas` que recoja las dietas utilizadas y la ganancia media de peso de los 24 conejos del expermiento:

``` r
# data frame para el ejemplo de la ganancia media de
#  peso en función de ED
dietas<-data.frame(tratamiento=trat,ganpeso=ganp);dietas 
```

       tratamiento  ganpeso
    1           D4 28.09722
    2           D4 22.90853
    3           D4 26.38971
    4           D4 25.91061
    5           D4 19.55866
    6           D4 32.82682
    7           D3 32.32169
    8           D3 36.55633
    9           D3 31.14694
    10          D3 29.04858
    11          D3 30.49499
    12          D3 24.81935
    13          D2 27.91635
    14          D2 27.16374
    15          D2 18.04902
    16          D2 24.41190
    17          D2 30.97129
    18          D2 28.78937
    19          D1 28.04505
    20          D1 35.39647
    21          D1 29.93812
    22          D1 26.92383
    23          D1 25.18164
    24          D1 27.36992

como los objetos `trat` y `ganp` están incorporados en `dietas`, los podemos eliminar del área de trabajo.

``` r
# elimina del área de trabajo los objetos trat y ganp
rm(trat,ganp) 
```

La función `names` no permite visualizar los nombres de los componentes del marco de datos.

``` r
names(dietas) # nombres asignado a las columnas de dietas
```

    [1] "tratamiento" "ganpeso"    

La función `str` nos muestra una breve descripción de la estructura del marco de datos.

``` r
str(dietas)
```

    'data.frame':   24 obs. of  2 variables:
     $ tratamiento: Factor w/ 4 levels "D1","D2","D3",..: 4 4 4 4 4 4 3 3 3 3 ...
     $ ganpeso    : num  28.1 22.9 26.4 25.9 19.6 ...

y la funcción `summary` proporciona un resumen de la variable que depende del tipo de variable.

``` r
summary(dietas)
```

     tratamiento    ganpeso     
     D1:6        Min.   :18.05  
     D2:6        1st Qu.:25.73  
     D3:6        Median :27.98  
     D4:6        Mean   :27.93  
                 3rd Qu.:30.61  
                 Max.   :36.56  

Podemos acceder a los elementos de `dietas` de las siguientes forma:

``` r
dietas[1,] # muestra la primera fila
```

      tratamiento  ganpeso
    1          D4 28.09722

``` r
dietas[1:10,] # muestra las 10 primeras filas
```

       tratamiento  ganpeso
    1           D4 28.09722
    2           D4 22.90853
    3           D4 26.38971
    4           D4 25.91061
    5           D4 19.55866
    6           D4 32.82682
    7           D3 32.32169
    8           D3 36.55633
    9           D3 31.14694
    10          D3 29.04858

``` r
head(dietas) # muestra las primeras filas
```

      tratamiento  ganpeso
    1          D4 28.09722
    2          D4 22.90853
    3          D4 26.38971
    4          D4 25.91061
    5          D4 19.55866
    6          D4 32.82682

``` r
tail(dietas) # muestra las últimas filas
```

       tratamiento  ganpeso
    19          D1 28.04505
    20          D1 35.39647
    21          D1 29.93812
    22          D1 26.92383
    23          D1 25.18164
    24          D1 27.36992

``` r
dietas$tratamiento # muestra la columna tratamiento
```

     [1] D4 D4 D4 D4 D4 D4 D3 D3 D3 D3 D3 D3 D2 D2 D2 D2 D2 D2 D1 D1 D1 D1
    [23] D1 D1
    Levels: D1 D2 D3 D4

``` r
dietas[,1] # forma equivalente
```

     [1] D4 D4 D4 D4 D4 D4 D3 D3 D3 D3 D3 D3 D2 D2 D2 D2 D2 D2 D1 D1 D1 D1
    [23] D1 D1
    Levels: D1 D2 D3 D4

Una forma más comoda de manejar los elementos de un marcos de datos es utilizando la función `with` que permite un acceso de sólo-lectura de sus componentes.

``` r
with(dietas,ganpeso/10) # divide por 10 la variable ganpeso
```

     [1] 2.809722 2.290853 2.638971 2.591061 1.955866 3.282682 3.232169
     [8] 3.655633 3.114694 2.904858 3.049499 2.481935 2.791635 2.716374
    [15] 1.804902 2.441190 3.097129 2.878937 2.804505 3.539647 2.993812
    [22] 2.692383 2.518164 2.736992

La función `within` permite un acceso a los datos de lectura-escritura. No cambia el marco de datos original pero permite crear una copia modificada. Para cambiar los datos debemos asignar el resultado de la función al mismo objeto.

``` r
dietas<-within(dietas,ganpeso10<-ganpeso/10)
str(dietas)
```

    'data.frame':   24 obs. of  3 variables:
     $ tratamiento: Factor w/ 4 levels "D1","D2","D3",..: 4 4 4 4 4 4 3 3 3 3 ...
     $ ganpeso    : num  28.1 22.9 26.4 25.9 19.6 ...
     $ ganpeso10  : num  2.81 2.29 2.64 2.59 1.96 ...

Un marco de datos puede guardarse en el direcorio de trabajo con la función `save`. El nombre del fichero a guardar debe ir entre comillas y es convieniente guardralo con la extension `.rda`.

``` r
save(dietas,file="dietas.rda")
```

Para recuperar el marco de datos se utiliza la función `load`.

``` r
rm(list=ls(all=TRUE))
ls()
```

    character(0)

``` r
load("dietas.rda")
ls()
```

    [1] "dietas"

``` r
str(dietas)
```

    'data.frame':   24 obs. of  3 variables:
     $ tratamiento: Factor w/ 4 levels "D1","D2","D3",..: 4 4 4 4 4 4 3 3 3 3 ...
     $ ganpeso    : num  28.1 22.9 26.4 25.9 19.6 ...
     $ ganpeso10  : num  2.81 2.29 2.64 2.59 1.96 ...

Importar datos
--------------

Para crear un marco de datos a partir de un fichero de datos externo es conviniente que los datos estén en formato ASCII (texto simple creado por ejemplo por el bloc de notas ) y separada cada columna por tabulaciones o por comas. Por ejemplo, acontinuación se muestran las primeras lineas del archivo `dietas.txt` formado por dos columnas separadas por tabulaciones y con el nombre de cada columna en la primera fila.

    Tratamiento ganpeso
    D4  28.03
    D4  29.78
    D4  25.93
    D4  36.73
    D4  23.98
    D4  27.23
    D3  35.49
    D3  31.56
    .............
    .............

La función `read.table` nos permite acceder al fichero con los datos y crear un marco de datos.

``` r
rm(dietas)
dietas<-read.table("dietas.txt",sep="\t",header=TRUE)
```

El argumento `sep` le indica que la separación de las columnas son tabulaciones y `header=TRUE` que en la primera fila están los nombres de las columnas.

La función `subset` extrae un subconjunto de filas, de columnas o de ambas de un marco de datos.

``` r
alta<-subset(dietas,subset=tratamiento=="D1" | tratamiento=="D2")
str(alta)
```

    'data.frame':   12 obs. of  2 variables:
     $ tratamiento: Factor w/ 4 levels "D1","D2","D3",..: 2 2 2 2 2 2 1 1 1 1 ...
     $ ganpeso    : Factor w/ 24 levels "20,58","21,38",..: 9 23 4 21 18 10 16 8 24 6 ...

El primer argumento es el nombre del marco de datos. El segundo es una expresión indicando que filas se seleccionan. El argumento `select` permite indicar que variables deseamos seleccionar.

Los factores resultantes de la función `subset` mantienen el número de niveles del factor en el marco de datos orginal. Con la función `factor` podemos eliminar niveles no existentes en el nuevo factor.

``` r
alta$tratamiento<-factor(alta$tratamiento)
str(alta)
```

    'data.frame':   12 obs. of  2 variables:
     $ tratamiento: Factor w/ 2 levels "D1","D2": 2 2 2 2 2 2 1 1 1 1 ...
     $ ganpeso    : Factor w/ 24 levels "20,58","21,38",..: 9 23 4 21 18 10 16 8 24 6 ...

Un operador útil para seleccionar un conjunto de valores de una variable es el operador `\%in\%`.

``` r
alta<-subset(dietas,subset=tratamiento %in% c("D1","D2"))
alta$tratamiento<-factor(alta$tratamiento)
str(alta)
```

    'data.frame':   12 obs. of  2 variables:
     $ tratamiento: Factor w/ 2 levels "D1","D2": 2 2 2 2 2 2 1 1 1 1 ...
     $ ganpeso    : Factor w/ 24 levels "20,58","21,38",..: 9 23 4 21 18 10 16 8 24 6 ...

que selecciona solo aquellas filas donde el tratamiento es D1 o D2.
