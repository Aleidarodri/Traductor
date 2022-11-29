# Traductor

Como sabemos un compilador es un pequeño programa informático,  que se encarga de traducir un el código fuente ,este es un 
software que se encarga de traducir el programa hecho en lenguaje de programación, a un lenguaje de máquina que pueda ser 
comprendido por el equipo y pueda ser procesado o ejecutado por este.
Acontinuacion se presentara el proceso de la creación de un traductor de lenguaje C a la creacion de un lenguaje propio,en este caso se tradujo frances y al finalizar con un lenguaje de Maquina(jasmine)


# Creacion de cascaron

Creación de un cascarón para una interfaz con la que se empezara el proyecto para comenzar a usar nuestro propio lenguaje.

![interfaz](https://user-images.githubusercontent.com/93956966/204643194-8fdeca79-6076-47e4-8e78-bb60130d4d0e.png)
    Figura 1: Cascarón de interfaz para creación para uso de nuestro lenguaje

Declaración de tokens para iniciar un lenguaje basico void main(),para uso de operaciones basicas de matematicas multiplicación, división, suma y resta

![tokens](https://user-images.githubusercontent.com/93956966/204643470-524fc3f6-ab3c-4191-a548-5c07bdb77e69.png)

Figura 2:Declaración de tokens para inicar un lenguaje básico 
  
 Creación de una expresión básica de matematicas con un metodo  basico void  main() con declaración de expresión.
 
 ![metodo](https://user-images.githubusercontent.com/93956966/204644094-81dfda11-d6c1-42c3-8749-0c4d99696cb9.png)
Figura 3: metodo de declaración de operaciones

Visita a BaseVisitor a los metodos para realizar cada operación en MyVisitor,con declaración estableciendo limite en dos operaciones del mismo nivel,como Multiplicación y división o Suma y resta 

![limite](https://user-images.githubusercontent.com/93956966/204644283-0cfa9e6e-391d-44f6-a272-af628ece7270.png)

Figura 4:Visita a los metodos de limitación para cada una de las operaciones 

Prueba de metodo Void main (){} en intefaz con resultado de declaración de variable con asignación e impresión de la misma 

![prueba1](https://user-images.githubusercontent.com/93956966/204644778-c5776ae3-ba59-4816-9f01-42d25c4090ad.png)

Figura 5: Declaracion de variables e impresión de la mismas.



