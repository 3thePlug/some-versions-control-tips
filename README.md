--VERSIÓN ESPAÑOL--

## ALGUNOS APUNTES PARA EL CONTROL DE VERSIONES

## 1. MÉTODOS DE NUMERACIÓN

## 1.1. Versiones X.Y.Z

Un método bastante habitual de numerar las versiones es utilizando dos o tres cifras decimales para
indicar la importancia de los cambios realizados. El cambio de la primera cifra indica cambios más
importantes que el de la segunda. El criterio más habitual es seguir las siguientes normas:

- `X`: La primera cifra (X) indica la versión mayor del documento. Si empieza con un cero significa que el
documento aún no está listo o no cumple con los requerimientos mínimos. Cada cambio en esta cifra
denota una reescritura o la incompatibilidad con versiones mayores anteriores.

- `Y`: La segunda cifra (Y) indica la versión menor del documento. Denota cambios en el contenido o en la
funcionalidad del documento pero no lo suficientemente importantes como para decir que ya no es el
mismo. Cuando se estrena una versión mayor se deja la versión menor a cero pero aún así se incluye
de modo que la segunda versión mayor sería la 2.0.

- `Z`: La tercera cifra (Z) indica la segunda versión menor. Indica que el documento se ha corregido pero que
no se ha añadido ni eliminado nada relevante. Cuando se estrena una versión menor, es decir, cuando
la segunda versión menor es igual a cero; suele omitirse.

- Pueden añadirse recursivamente versiones menores, algunos proyectos hacen uso de ellas cuando los
criterios de selección de versiones no corresponden con los definidos en los puntos anteriores. El
núcleo del sistema operativo Linux utiliza una numeración de cuatro cifras.

- `ALPHA, BETA, RELEASE`: Otra práctica común es definir versiones especiales como las versiones alpha, beta o las release
candidate. Estas versiones suelen utilizarse antes de llegar a un hito como una nueva versión menor.
Por ejeplo, antes de llegar a la segunda versión mayor, la versión 2.0, puede publicarse una primera
versión previa alpha numerada como 2.0a o 1.99. La segunda versión previa se llamaría beta y se
numeraría como 2.0b o (por ejemplo) 1.999. Si aún así son necesarias más versiones previas, en vez
de optar por más letras griegas se numeran versiones candidatas; la primera sería la release candidate
1 numerada como 2.0-rc1

## 1.2 Versiones numeradas

Un método de numeración compatible con el anterior es numerar las versiones mediante un número
decimal. La primera versión es la 1, la segundo es la 2 y así sucesivamente. Esta numeración suele
utilizarse en el desarrollo cuando el control de versiones se lleva de forma automática mediante algún
programa de control de versiones.

En algunos casos ambas numeraciones se combinan. Por ejemplo se está desarrollando la versión 2.1 a
partir de la 2.0.5 y para el software de control de versiones (se toma como ejemplo Subversion) la
última versión es la 671. Entonces la versión de desarrlollo podría ser la 2.0.5-svn671.

## SOME TIPS FOR VERSION CONTROL

--ENGLISH VERSION (SOON)--

Soon I will update this.

