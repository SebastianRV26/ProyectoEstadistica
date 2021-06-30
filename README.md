# ProyectoEstadistica

### I Parte: 

Descripción general det dataset tilizado (Diamantes de datos) y se presenta que no tiene columnas vacías.

### II Parte: Intervalos de confianza (IC) 
* IC de un promedio usando distribución Z e IC de una diferencia de promedios utilizando las funciones z.test de los paquetes stests (solo para el caso de una población), BSDA y PASWR2. Y para la distribución t utilizando la función t.test

* IC de una diferencia de proporciones utilizando la función prop.test

*  usando distribución Z utilizando la función z.test de los paquetes BSDA y PASWR2

* IC de una varianza usando varTest

* IC de un cociente de varianzas usando var.test

### III Parte pruebas de hipótesis de una y dos poblaciones

Para todos los casos anteriores se crea la hipótesis nula, la hipótesis alternativa y se intenta encontrar evidencia en contra para la hipótesis nula.

### IV Parte: Otras pruebas de hipótesis en R

Se presentan 4 casos relacionados con pruebas de hipótesis de bondad de ajuste, ANOVA´s e independencia.

### V Parte: Modelos de regresión lineal

En esta sección se analizan 3 casos relacionados con los modelos de Regresión Lineal Simple (RLS) y múltiple (RLM), así como los modelos de Regresión no Lineal Simple (RNLS).

### Notas

* Para realizar el proyecto fue necesario instalar el lenguaje R, el editor RStudio y Rtools.

* Para instalar algún paquete se utiliza la siguiente línea de código: 
```
install.packages("nombre del paquete", dependencies = T)
```

* En caso de tener problemas con la instalación del paquete stests ejecutar el siguiente chunk:
```
if (!require('devtools')) install.packages('devtools')
devtools::install_github('fhernanb/stests', force=TRUE)
```

## Integrantes:
* [Francisco Soto Quesada](https://github.com/franrsq)
* [Jairo Pacheco Campos](https://github.com/JairoPacheco)
* [Jason Barrantes Rodríguez](https://github.com/JasonBarrantes)
* [Sebastián Rojas Vargas](https://github.com/SebastianRV26)

Curso: Estadística.
I Semestre 2021.
Profesor: Esteban Ballestero.