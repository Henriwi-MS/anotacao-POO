# Anotações de Java

## Tipos em Java

String
int
float
double
char
boolean

byte
short
long

## constante em java
final int numero = 2;

## numeros com ponto flutuante
float myFloatNum = 5.99f;

double myDoubleNum = 5.999999d;

## booleanos
boolean verdadeiro = true;

boolean falso = false;

## Casting em Java

double myDouble = 9.78d;

int myInt = (int) myDouble;

### Widening Casting (automatically) - converting a smaller type to a larger type size
byte -> short -> char -> int -> long -> float -> double

###Narrowing Casting (manually) - converting a larger type to a smaller size type
double -> float -> long -> int -> char -> short -> byte 

## Tamanhos de vetores

- String: txt.length()
- Arrays: array.length

## bruxaria
String x = "10";
int y = 20;
String z = x + y; //2010

## Como usar a classe Math
Math.sqrt(64);
int randomNum = (int)(Math.random() * 101);

## Atribuir matriz
int[][] myNumbers = { {1, 2, 3, 4}, {5, 6, 7} };
System.out.println(myNumbers[1][2]); // Outputs 7

## Method overloading

With method overloading, multiple methods can have the same name with different parameters:

```java
int myMethod(int x)
float myMethod(float x)
double myMethod(double x, double y)
```

## Compilar e executar codigo

```sh
javac filename.java
java filename
```

## Construtor

```java
public class Main {
  int x;  // Create a class attribute

  // Create a class constructor for the Main class
  public Main() {
    x = 5;  // Set the initial value for the class attribute x
  }

  public static void main(String[] args) {
    Main myObj = new Main(); // Create an object of class Main (This will call the constructor)
    System.out.println(myObj.x); // Print the value of x
  }
}
```

## Modificadores de acesso

- public
  - metodo que pode ser acessado somente pelo objeto
- static
  - metodo que pode ser acessado pela classe
  - variavel da classe em si e não do objeto, e o objeto pode modificar essa variavel da classe.

## This

O "this" é o mesmo que o do Javascript

```java
this.name = newName;
```

## Classes abstratas

é o mesmo que as interfaces do typescript

```java
abstract class Main {
  public String fname = "John";
  public String lname = "Doe";
  public String email = "john@doe.com";
  public int age = 24;
  public abstract void study(); // abstract method 
}

// Subclass (inherit from Person)
class Student extends Main {
  public int graduationYear = 2018;
  public void study() {
    System.out.println("Studying all day long");
  }
}
```

## Como usar o Scanner para leitura do stdin

é que nem a função "input()" do python. Soq melhor.

```java
import java.util.Scanner/
Scanner myObj = new Scanner(System.in);
tring userName = myObj.nextLine();
```

### Métodos do Scannner

- nextBoolean() 	Reads a boolean value from the user
- nextByte() 	    Reads a byte value from the user
- nextDouble()   	Reads a double value from the user
- nextFloat()   	Reads a float value from the user
- nextInt() 	    Reads a int value from the user
- nextLine() 	    Reads a String value from the user
- nextLong() 	    Reads a long value from the user
- nextShort() 	  Reads a short value from the user

## Bibliotecas inportantes

```java
import java.util.Scanner
import java.util.*
```
