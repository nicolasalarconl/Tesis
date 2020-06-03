---
title: Primary Beam
created: '2020-06-02T23:10:35.690Z'
modified: '2020-06-03T03:43:14.490Z'
---

# Primary Beam

ARREGLAR !!

# referenciar 


El haz primario se puede considerar como la sensibilidad de su instrumento en función de la dirección. Los elementos receptores que forman la matriz no son uniformemente sensibles a la radiación entrante desde todas las direcciones. Por ejemplo, una serie de platos parabólicos tiene una sensibilidad máxima en la dirección a la que apuntan (generalmente el centro de fase), y la sensibilidad se aleja de esa dirección. Como regla general, el punto de media potencia en radianes, es decir, la distancia angular desde el centro de fase en el que una fuente intrínseca de 1J y tiene una densidad de flujo aparente de 0,5J y es aproximadamente (longitud de onda / 2D) donde D es el diámetro del plato.

Tradicionalmente, se supone que el patrón de haz primario es idéntico para cada receptor en la matriz, con sus efectos eliminados de una observación dividiendo la imagen final deconvolucionada por algún patrón de haz primario promedio supuesto. El efecto final de esto es corregir los flujos fuente atenuados, aunque este proceso también resulta efectivamente en un aumento del ruido de la imagen hacia el borde del mapa.

En realidad, el patrón de haz primario es un negocio complicado, y su presencia inevitable en todas las observaciones puede convertirse fácilmente en una mosca en su delicioso plato de sopa de radioastronomía. Por ejemplo, los muchos lóbulos laterales más allá del lóbulo principal central que hacen que el interferómetro sea sensible a las fuentes en el campo lejano. Las fuentes brillantes pueden ser particularmente problemáticas, como veremos en una simulación posterior.

La suposición de que los patrones de haz son los mismos para cada receptor tampoco es válida. Obviamente, es el caso de matrices heterogéneas como e-MERLIN o algunas redes VLBI, y menos obvio para matrices de apertura como LOFAR. Sin embargo, para observatorios como el VLA que aparentemente tienen elementos idénticos que forman la matriz, los efectos sutiles como la precisión de puntería finita de las antenas hacen que cada estación tenga un haz primario efectivo ligeramente diferente.

Aunque el problema de las fuentes brillantes que limitan el rango dinámico de una imagen son familiares desde hace mucho tiempo, los sutiles efectos del haz, como el error de puntería, hasta ahora solo han alzado la cabeza para las observaciones más profundas. Sin embargo, si sus objetivos son lo suficientemente débiles, pueden resultar limitantes. Pero para que no lo olvidemos: se espera que todos estos radiotelescopios que se están construyendo o mejorando puedan detectar rutinariamente el débil cielo de radio.



We can work out the reception pattern of an individual dish, known as the *primary beam*, using 

﻿

$$ \Delta \theta_{\rm pb} = \frac{\lambda}{D} $$

﻿
which returns the angle in radians.

﻿

