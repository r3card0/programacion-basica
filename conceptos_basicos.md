# Algortimos

Los algoritmos son la base de la programación, ya que son las estructuras sobre la cual se construyen los programags

**Un algoritmo es un conjunto de pasos ordenados, definidos y finitos para un fin**

Esto quiere decir que los algoritmos son creados para_
* Resolver un problema
* Crear un resultado
* Etc

Los algoritmos cuentan con los siguientes conceptos:
1. **Pasos Ordenados**: Un algoritmo consta de una secuencia de pasos que se ejecutan en un orden específico. Es importante que estos pasos estén claramente definidos y que no haya ambigüedad en cuanto a lo que se debe hacer en cada uno de ellos.
2. **Definición de Pasos**: Cada paso del algoritmo debe ser claro y preciso. Utilizamos un lenguaje sencillo y específico para describir las acciones que queremos que la computadora realice. Por ejemplo, en un algoritmo para hacer una taza de té, los pasos podrían ser "poner agua en la tetera", "calentar el agua", "poner una bolsita de té en la taza", etc.
3. **Secuencia Lógica**: Los pasos del algoritmo deben seguir una secuencia lógica, lo que significa que el orden en que se ejecutan tiene sentido y conduce a la solución del problema. Por ejemplo, en el algoritmo de hacer una taza de té, no tendría sentido poner la bolsita de té en la taza antes de calentar el agua.
4. **Condicionales y Bucles (Opcional)**: Los algoritmos pueden incluir estructuras de control como condicionales (if/else) y bucles (for, while) para manejar situaciones en las que se requiere tomar decisiones o repetir ciertos pasos. Estas estructuras son fundamentales para que los algoritmos puedan adaptarse a diferentes situaciones y datos de entrada.
5. **Datos de entrada y datos de salida**: Los datos de entrada y salida son esenciales para la interacción entre el usuario y el programa. Los datos de entrada permiten que el programa reciba información del usuario o del entorno, mientras que los datos de salida proporcionan los resultados del procesamiento realizado por el programa
6. **Abstracción y Modularidad**: A medida que los algoritmos se vuelven más complejos, es útil dividirlos en partes más pequeñas y manejar cada parte por separado. Esto se conoce como abstracción y modularidad, y nos permite escribir algoritmos más legibles, mantenibles y reutilizables.

Ejemplo sencillo de un algoritmo para sumar dos numeros:

Inicio

1. Solicitar al usuario que ingrese el primer número (num1).
2. Solicitar al usuario que ingrese el segundo número (num2).
3. Sumar num1 y num2 y guardar el resultado en una variable llamada suma.
4. Mostrar el resultado de la suma al usuario.
5. Fin

## algoritmo para un juego de adivinanza

Inicio
1. Generar aleatoriamente el numero secreto en el rango del 1 al 100
2. Pedir al jugador adivine el numero secreto, ingresando un numero
3. Tomar el numero del paso 2 y usarlo en la estructura de control
4. Evaluar si el numero ingresado es igual al numero secreto, si es verdadero, terminar el juego y pasar al paso 8, si no es igual entonces, evaluar si el numero ingresado es menor al numero secreto, si es verdadero, ir al paso 6 y regresar al paso 2, si es falso, entonces ir al paso 7 y regresar al paso 2
6. Mostrar el mensaje : Tu numero es menor al numero secreto
7. Mostrar el mensaje: Tu numero es mayor al numero secreto
8. Imprimir el mensaje: Felicidades, has adivinado el numero secreto
9. Fin del juego

Algoritmo optimizado:
```yaml
Inicio

1. Generar aleatoriamente el número secreto en el rango del 1 al 100.
2. Establecer el contador de intentos en 0.
3. Repetir mientras el número ingresado por el jugador no sea igual al número secreto:
   4.1. Incrementar el contador de intentos en 1.
   4.2. Pedir al jugador que adivine el número secreto, ingresando un número.
   4.3. Si el número ingresado es mayor que el número secreto:
        4.3.1. Mostrar el mensaje: "El número es menor al número ingresado. Intenta de nuevo."
   4.4. Si el número ingresado es menor que el número secreto:
        4.4.1. Mostrar el mensaje: "El número es mayor al número ingresado. Intenta de nuevo."
5. Mostrar el mensaje: "¡Felicidades! ¡Adivinaste el número secreto en {contador} intentos!"
6. Fin del juego
```
