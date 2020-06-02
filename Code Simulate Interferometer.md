---
title: Code Simulate Interferometer
created: '2020-06-02T22:42:30.879Z'
modified: '2020-06-02T23:23:31.330Z'
---

# Code Simulate Interferometer

Librerias a utilizar
```python
import numpy as np
import pandas as pd
import pylab as pl
import cv2
```
Definiendo la constante de tiempo
```python
 const_c = 3e8
```
Vamos a simular algunos datos para el telescopio [VLA](./Very Large Array Telescope.md), en su configuración más compacta. El diámetro de un plato VLA es de 25 metros, vamos a simular una observación monocromática a una frecuencia de 5 GHz
```python
D = 25  # Diametro del plato [Metros]
frequency = 5e9  # frecuencia de observación[Hz]
wavelength = const_c/frequency #longitud de onda
```
[Longitud de onda](./Wavelength.md)

Podemos calcular el patrón de recepción de un plato individual, conocido como [Primary Beam](./Primary Beam.md) utilizando

$\Delta$ $\theta_{\rm pb}$ $=$ $\frac{\lambda}{D}$

$\alpha$ $A$


```python
```

```python
```
