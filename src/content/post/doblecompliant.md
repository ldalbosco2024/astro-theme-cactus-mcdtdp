---
title: "Avance - Mecanismo complaciente lineal + rotacional."
description: "Prueba de mecanismo complaciente lineal + rotacional. La prueba muestra que esta configuración no es adecuada."
publishDate: "02 Dec 2024"
tags: ["test", "fast prototype"]
---

Se imprimió un test para probar la factibilidad de un mecanismo complaciente que haga movimiento rotacional + movimiento lineal.

![notas-rotacional-lineal](https://github.com/user-attachments/assets/8a81d297-df14-4243-8b93-e208135747e3)
![lineal-rotacional](https://github.com/user-attachments/assets/00770fd7-80cb-4c6b-a6dc-91f02d5464c1)

Lamentablemente, no parece ser una configuración adecuada. Al retractar el mecanismo lineal el mecanismo rotacional se deforma hasta el fallo. Quizás los mecanismos complacientes solo sirven para acercar, pero el bloqueo debe ser hecho por un mecanismo tradicional.

![falla-complaciente](https://github.com/user-attachments/assets/d76486db-7fa4-43b8-80ee-10a86e552e4a)
![{analiss-fea-fusion-linealrotacional}](https://github.com/user-attachments/assets/b324b8c6-80ed-4ae2-a654-1bd515013d23)

Luego de una conversación con Olivia Formoso, se mostró el paper [MMIC-I: A Robotic Platform for Assembly Integration and Internal Locomotion through Mechanical Meta-Material Structures](https://ieeexplore.ieee.org/document/10161263). Allí se presenta una forma de accionar el sistema de bloqueo con un efector robótico. 

Quizás los mecanismos complacientes no son necesarios, pero sí podrían, aún, ser una forma de ensamble válida y/o valiosa.
