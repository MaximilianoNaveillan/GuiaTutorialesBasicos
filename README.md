# Guia tutoriales Básicos Java

## Nivel Básico

- **Hola Mundo**: Crear un programa simple que imprima "Hola, mundo!" en la consola.
- **Variables y Tipos de Datos**: Declarar variables de diferentes tipos (enteros, decimales, texto) y realizar operaciones básicas.
- **Entrada y Salida de Datos**: Utilizar la clase `Scanner` para leer datos ingresados por el usuario y mostrar resultados en la consola.
- **Condicionales**: Utilizar `if`, `else if` y `else` para tomar decisiones basadas en ciertas condiciones.
- **Bucles**: Usar `for` y `while` para repetir un bloque de código varias veces.

---

### i. Tutorial: Hola, Mundo

---

[![Imagen del video](https://encrypted-tbn1.gstatic.com/images?q=tbn:ANd9GcRKgmqPKrBzBR_HZk8xbdPeE2J9-SU1Z0Uqzte_ffxk7MLEyjDB)](https://www.youtube.com/watch?v=c9Lr9XkOAYA)

#### 1. Descarga e Instalación de IntelliJ IDEA

- **Visita la página oficial**: Dirígete a [JetBrains IntelliJ IDEA](https://www.jetbrains.com/idea/) y descarga la versión Community de IntelliJ IDEA (es gratuita).
- **Ejecuta el instalador**: Sigue las instrucciones del instalador para completar la instalación en tu computadora.

#### 2. Creación de un Nuevo Proyecto

- **Inicia IntelliJ IDEA**: Una vez instalado, abre IntelliJ IDEA.
- **Nuevo proyecto**: Haz clic en "Create New Project".
- **Selecciona Java**: Elige el SDK de Java que tengas instalado y dale un nombre a tu proyecto (por ejemplo, "HolaMundo").
- **Finalizar**: Haz clic en "Finish" para crear el proyecto.

#### 3. Creación de la Clase

- **Panel de proyecto**: En el panel izquierdo, encontrarás la estructura de tu proyecto.
- **Paquete**: Crea un nuevo paquete (por ejemplo, `com.ejemplo`) haciendo clic derecho en la carpeta `src` y seleccionando `New` -> `Package`.
- **Clase**: Dentro del paquete, crea una nueva clase llamada `HolaMundo` haciendo clic derecho y seleccionando `New` -> `Java Class`.

#### 4. Escribir el Código

Reemplaza el contenido generado por IntelliJ IDEA con el siguiente:

public class HolaMundo {
public static void main(String[] args) {
System.out.println("¡Hola, mundo!");
}
}

#### 5. Ejecutar el programa

(Los mismos pasos que en el tutorial anterior)

#### Explicación del código:

1. **Declaración de variables**: En la primera parte del código, se declaran variables de diferentes tipos para almacenar diversos datos como nombre, edad, altura, etc.
2. **Operaciones**: Se realizan operaciones aritméticas (suma, división) y de comparación (mayor que) con las variables declaradas.
3. **Impresión de resultados**: Se utiliza `System.out.println()` para mostrar los valores de las variables y los resultados de las operaciones en la consola.

---

### ii . Tutorial: Variables y Tipos de Datos en Java

---

#### 1. Descarga e instalación de IntelliJ IDEA:

_(Los mismos pasos que en el tutorial anterior)_

#### 2. Creación de un nuevo proyecto:

_(Los mismos pasos que en el tutorial anterior)_  
**Nombre del proyecto:** `VariablesYTiposDeDatos`

#### 3. Creación de la clase:

_(Los mismos pasos que en el tutorial anterior)_  
**Nombre de la clase:** `MiPrimerPrograma`

#### 4. Escribir el código:

Reemplaza el contenido de la clase `MiPrimerPrograma` con el siguiente código:

```java
public class MiPrimerPrograma {
public static void main(String[] args) {
// Declaración de variables
int edad = 30;
double altura = 1.75;
String nombre = "Juan";
char inicial = 'J';
boolean esEstudiante = true;

        // Operaciones con variables
        int x = 10, y = 5;
        int suma = x + y;
        double division = (double) x / y; // Casting a double para obtener un resultado con decimales

        boolean esMayor = x > y;

        // Imprimir resultados
        System.out.println("Nombre: " + nombre);
        System.out.println("Edad: " + edad + " años");
        System.out.println("Altura: " + altura + " metros");
        System.out.println("Inicial: " + inicial);
        System.out.println("Es estudiante: " + esEstudiante);
        System.out.println("La suma de x e y es: " + suma);
        System.out.println("La división de x entre y es: " + division);
        System.out.println("¿x es mayor que y? " + esMayor);
    }

}
```

#### 5. Ejecutar el programa:

_(Los mismos pasos que en el tutorial anterior)_

##### Explicación del código:

- **Declaración de variables:** En la primera parte del código, se declaran variables de diferentes tipos para almacenar diversos datos como nombre, edad, altura, etc.
- **Operaciones:** Se realizan operaciones aritméticas (suma, división) y de comparación (mayor que) con las variables declaradas.
- **Impresión de resultados:** Se utiliza `System.out.println()` para mostrar los valores de las variables y los resultados de las operaciones en la consola.

---

#### Ejercicio adicional:

Modifica el código para:

##### a. Calcular el área de un círculo.

**Pistas:**

- **Fórmula:** El área de un círculo se calcula utilizando la fórmula: `Área = π * radio^2`.
- **Variables:** Necesitarás una variable para almacenar el radio del círculo y otra para almacenar el resultado del cálculo del área.
- **Constante:** La constante matemática pi (π) se puede aproximar a 3.14159.

##### b. Convertir una temperatura de grados Celsius a Fahrenheit.

**Pistas:**

- **Fórmula:** La fórmula para convertir de Celsius a Fahrenheit es `Fahrenheit = (Celsius * 9/5) + 32`.
- **Variables:**
  - `celsius`: Un número de punto flotante (`double`) para almacenar la temperatura en grados Celsius.
  - `fahrenheit`: Otro número de punto flotante para almacenar el resultado de la conversión.
- **Pasos:**
  1. Pedir al usuario que ingrese la temperatura en grados Celsius.
  2. Convertir el valor ingresado a un tipo numérico (`double`) si es necesario.
  3. Aplicar la fórmula de conversión.
  4. Mostrar el resultado en la consola.

##### c. Crear un programa que determine si un número es par o impar.

**Pistas:**

- **Operador módulo (%):** Este operador devuelve el resto de una división. Si el resto de dividir un número entre 2 es 0, el número es par.
- **Condicional:** Utilizar la estructura `if-else` para verificar si el resto es 0 y mostrar el mensaje correspondiente.
- **Variables:**
  - `numero`: Un número entero (`int`) para almacenar el número a evaluar.

---

### iii. Tutorial: Condicionales en Java (if, else if, else)

---

#### 1. Descarga e instalación de IntelliJ IDEA:

_(Los mismos pasos que en los tutoriales anteriores)_

#### 2. Creación de un nuevo proyecto:

_(Los mismos pasos que en los tutoriales anteriores)_  
**Nombre del proyecto:** `CondicionalesJava`

#### 3. Creación de la clase:

_(Los mismos pasos que en los tutoriales anteriores)_  
**Nombre de la clase:** `TomaDeDecisiones`

#### 4. Escribir el código:

```java
public class TomaDeDecisiones {
public static void main(String[] args) {
int edad = 25;

        if (edad >= 18) {
            System.out.println("Eres mayor de edad.");
        } else {
            System.out.println("Eres menor de edad.");
        }

        // Usando else if
        int nota = 75;
        if (nota >= 90) {
            System.out.println("¡Excelente!");
        } else if (nota >= 75) {
            System.out.println("¡Muy bien!");
        } else if (nota >= 60) {
            System.out.println("Aprobado.");
        } else {
            System.out.println("Reprobado.");
        }
    }

}
```

#### 5. Ejecutar el programa:

(Los mismos pasos que en los tutoriales anteriores)

##### Explicación del código:

- **if:** Se utiliza para evaluar una condición. Si la condición es verdadera, se ejecuta el código dentro del bloque `if`.
- **else:** Se utiliza para ejecutar código si la condición del `if` es falsa.
- **else if:** Se utiliza para evaluar condiciones adicionales si la condición del `if` anterior era falsa.

#### Ejercicios adicionales:

##### a. Crear un programa que determine si un número es positivo, negativo o cero.

**Pistas:**

- Utiliza una estructura `if-else if-else`.
- Compara el número con 0.

##### b. \*\*Crear un programa que determine la categoría de edad de una persona (niño, adolescente, adulto, adulto mayor).

**Pistas:**

- Define rangos de edad para cada categoría.
- Utiliza múltiples condiciones `if-else if`.

##### c. Crear un programa que simule un menú de opciones.

**Pistas:**

- Utiliza una estructura `switch-case` para manejar múltiples opciones.
- Pide al usuario que ingrese una opción.
- Basado en la opción, ejecuta el código correspondiente.

##### d.Crear un programa que verifique si un año es bisiesto.

**Pistas:**

- Utiliza las reglas de los años bisiestos (divisible por 4, excepto los divisibles por 100 pero no por 400).

##### e.Crear un programa que calcule el máximo de tres números.

**Pistas:**

- Utiliza múltiples condiciones `if` para comparar los números.

#### Ampliando el conocimiento:

- **Operadores lógicos:** AND (`&&`), OR (`||`), NOT (`!`).
- **Anidamiento de condicionales:** Puedes anidar estructuras `if-else` dentro de otras.
- **Operador ternario:** Una forma más concisa de escribir ciertas condiciones.

---

### iiii. Tutorial: Bucles en Java (for y while)

---

#### 1. Descarga e instalación de IntelliJ IDEA:

(Los mismos pasos que en los tutoriales anteriores)

#### 2. Creación de un nuevo proyecto:

(Los mismos pasos que en los tutoriales anteriores)  
**Nombre del proyecto:** BuclesJava

#### 3. Creación de la clase:

(Los mismos pasos que en los tutoriales anteriores)  
**Nombre de la clase:** Repeticion

#### 4. Escribir el código:

```java
public class Repeticion {
public static void main(String[] args) {
// Bucle for
for (int i = 0; i < 5; i++) {
System.out.println("Iteración " + i);
}

        // Bucle while
        int contador = 1;
        while (contador <= 10) {
            System.out.println("Número: " + contador);
            contador++;
        }
    }

}
```

#### Ejercicios adicionales:

##### a. Crear un programa que imprima los números del 1 al 100.

**Pistas:**

- Utiliza una estructura `if-else if-else`.
- Compara el número con 0.

##### b. Crear un programa que calcule la suma de los números del 1 al 100.

**Pistas:**

- Inicializa una variable suma en 0. Dentro del bucle for, suma el valor del contador a la variable suma. Al finalizar el bucle, imprime el valor de suma.

##### c. Crear un programa que imprima la tabla de multiplicar de un número ingresado por el usuario.

**Pistas:**

- Utiliza un bucle for anidado. El bucle externo itera sobre las filas (del 1 al 10) y el bucle interno itera sobre las columnas (multiplicando la fila por un número fijo).

##### d. Crear un programa que simule el lanzamiento de un dado varias veces.

**Pistas:**

- Utiliza la clase Random para generar números aleatorios entre 1 y 6. Repite este proceso dentro de un bucle for para simular múltiples lanzamientos.

##### e. Crear un programa que pida al usuario que ingrese números hasta que ingrese un 0 y luego muestre la suma de todos los números ingresados.

**Pistas:**

- Utiliza un bucle while que se ejecute mientras el número ingresado sea diferente de 0. Dentro del bucle, suma el número ingresado a una variable suma.
