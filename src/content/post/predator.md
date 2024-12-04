---
title: "Descubrimiento Predator"
description: "El fin de semana me compré una polera de Depredador. Un poco edgy, debo admitir."
publishDate: "03 Dec 2024"
tags: ["test"]
---

El fin de semana me compré una polera de Depredador. Un poco edgy, debo admitir.

Dando vueltas a potenciales mecanismos de unión pensé en algo similar a la boca de los depredadores. 
Un mecanismo así funcionaría con un movimiento lineal, que simplemente acerque las uniones, y un mecanismo lineal que se deforme para sostener a su contraparte.

El problema de este mecanismo es que introduce orientación en el mecanismo. Para esto se propone una solución rápida: Dos bloques, los bloques X y los bloques +.
Si bien eso hace que los agentes robóticos dean mantener orientación, simplemente basta con saber la orientación de un (1) bloque, para saber la orientación de toda la estructura.

Imprimí prototipos en PLA. Definitivamente no es un material ni método de fabricación ideal. 
Quizás este es el momento de escribirle a Antonino para que suelte la SLS (para hacer el mecanismo en TPU, igual como en este [ejemplo](https://youtu.be/jHqkL6dLo2M?list=PL_7vkwuHJcWeusrb3Y4F1cCdOYK5ljvnl).)

![predator-1](https://github.com/user-attachments/assets/bcc9d85c-fbd8-4a1a-8fd8-ec9300c7d056)
![prototipo1](https://github.com/user-attachments/assets/66bc595b-b14e-48da-b1bf-cf681cec052d)

Prototipo 1. Tosco, gigante, ni siquiera está a escala con voxel MIT (7 in.) o ARMADAS (12 in.)

![predator-2(1)](https://github.com/user-attachments/assets/73b56217-241a-488f-90bd-334f7a3819dd)
![predtator-2-impresion](https://github.com/user-attachments/assets/f07797d5-9bd9-41fa-8881-e95cfdd604a8)
Prototipo 2. Funciona perfecto. Se rompió inmediatamente por lo débil de las capas y por el material. 

Los pasos a seguir son hacer un prototipo que incluya el segundo movimiento lineal. Dicho movimiento puede ser similar al realizado en el prototipo anterior. 
Además, ahora hay que leer en detalle los libros de diseño de mecanismos complacientes, y empezart a familiarizarme con los softwares de optimización topológica para mecanismos complacientes. 
También es importante buscar materiales y métodos de fabricación adecuados.

![ambos-voxeles-iso](https://github.com/user-attachments/assets/01bdf6fe-8bf1-4059-ae5d-dd7003568a34)
![ambos-voxeles-rontal](https://github.com/user-attachments/assets/5f8631f3-43f1-497b-9ace-9250e1cc6702)


En paralelo se puede diseñar el efector robótico, por ahora, tiene los siguientes requerimientos:
- Debe poder entrar al mismo tiempo por los triángulos del vóxel.
- Debe poder rotar para adaptarse a un vóxel X y un vóxel +.
- Debe tener un actuador lineal de dos fases, o dos actuadores lineales. Así el efector podrá acercar las partes y luego accionar las pinzas.


Se ve entretenida la tesis, ojalá resulte. 
