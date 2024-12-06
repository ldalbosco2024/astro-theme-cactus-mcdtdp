---
title: "Encargo 1"
description: "Diseño del set up, diagrama de flujo, sistema de testing. "
publishDate: "29 Nov 2024"
tags: ["test"]
---

Para el primer encargo se solicitó:

- DISEÑO DEL SET UP (MODELO 3D)
- DIAGRAMA DE FLUJO (COMPONENTES)
- SISTEMA DE TESTING

## Sistema de TESTING

Se averiguó acerca de las máquinas que existen en el DesignLab.
Actualmente, contamos con un medidor de tracción y compresión Autograph AGS-X Shimadzu. 

Mucha info relevante tienen en el [sitio web de la máquina](https://www.shimadzu.com/an/products/materials-testing/uni-ttm/autograph-ags-x-series/index.html).

La mordaza de compresión, de acuerdo con Martín, es un disco de diametro mayor a los vóxeles que planeo hacer, por lo que esa parte está lista.
La mordaza de tracción, no obstante, tiene un tamaño pequeño. Es posible diseñar adaptadores para dicha mordaza.

Dado esto, se plantea lo siguiente:

```md
- Prueba de compresión: Vóxel individual
- Prueba de compresión: Matriz de 3x1 vóxeles

- Diseño de mordaza para tracción: Mordaza a unión complaciente
- Diseño de mordaza para tracción: Mordaza a holder de vóxel

- Prueba de tracción: Unión complaciente con unión complaciente
- Prueba de tracción: Vóxel con vóxel (2x1)
- Prueba de tracción. Matrix de 3x1 vóxeles
```

A continuación, se adjuntan fotografías rápidas de la máquina: