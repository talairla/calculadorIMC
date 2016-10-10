# Práctica 1: Calculador Índice de Masa Corporal en Android.
##  Descripción de la Práctica.

Para esta práctica tendréis que crear una aplicación con sólo un activity que nos permita calcular el IMC de una persona. La práctica consistirá en la entrada de dos campos numéricos:

* Altura en metros. (con decimales)
* Peso en kilogramos. (con decimales)

La aplicación contendrá un botón calcular que cogerá los dos valores y calculará la fórmula del I.M.C., a saber:

* I.M.C. = Peso / Estatura^2

Una vez calculada la cifra del I.M.C. deberá hacer una comparación de acuerdo a las tablas que se pueden encontrar en Wikipedia y nos devolverá una descripción en base a nuestro peso. Delgadez extrema, delgadez moderada, delgadez leve, normal, ...

Utilizad 2 TextView para mostrar los valores devueltos.

Además, la aplicación contendrá un botón Borrar que resetee los campos de entrada: peso y altura; y los TextViews.

## Criterios de corrección.

* La aplicación funciona en el emulador sin errores de compilación ni de construcción, la interfaz está completa. (3 puntos)
* La aplicación calcula correctamente el I.M.C. (2 puntos)
* La aplicación controla los errores que pueda haber (campos vacíos, entrada incorrecta, etc) (2 puntos)
* El botón borrar funciona perfectamente (1 punto)
* La lógica del cálculo está separada en otra clase de tipo final. (1 punto)
* Los identificadores de los elementos de la interfaz tienen el formato visto en clase, se ha utilizado el fichero strings.xml para todos los textos de la aplicación, así como el colors.xml para los colores. (1 punto)
