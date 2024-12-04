---
title: "Pseudocódigo Predator"
description: "Pseudocódigo de cómo funcionaría el efector con el sistema Predator. aaaaaaaaaa"
publishDate: "04 Dec 2024"
tags: ["test"]
---

En presudocódigo, el efector hace lo sgte para bloquear dos vóxeles: 

```md
#Pseudocódigo para representar bloqueo

Mover posición_inicial;

if voxelA == voxelX {
  Rotar efectorA;
  } else {
  Rotar efectorB;
}

Accionar efectorA.movPinzas;
Accionar efectorB.movPinzas; #Estas dos líneas deberían ocurrir en paralelo

Esperar accionPinzas;

Accionar efectorA.movLineal;
Accionar efectorB.movLineal; 

Esperar accionLineal;

Accionar efectorA.movPinzas;
Accionar efectorB.movPinzas;

Esperar accionPinzas;

Soltar efectorA.movLineal;
Soltar efectorB.movLineal;

Esperar accionLineal;

Mover posición_final;

```

Y lo sgte para soltar dos vóxeles: 

```md
#Pseudocódigo para representar soltura

Mover posición_inicial;

if voxelA == voxelX {
  Rotar efectorA;
  } else {
  Rotar efectorB;
}

Accionar efectorA.movLineal;
Accionar efectorB.movLineal; #Estas dos líneas deberían ocurrir en paralelo

Esperar accionLineal;

Accionar efectorA.movPinzas;
Accionar efectorB.movPinzas;

Esperar accionPinzas;

Soltar efectorA.movLineal;
Soltar efectorB.movLineal;

Esperar accionLineal;

Soltar efectorA.movPinzas;
Soltar efectorB.movPinzas;

Esperar accionPinzas;

Mover posición_final;

```
