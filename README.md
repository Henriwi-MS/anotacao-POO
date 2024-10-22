## tipos

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

int myMethod(int x)
float myMethod(float x)
double myMethod(double x, double y)


## Atributos de metodos e atributos
public -> metodo que pode ser acessado somente pelo objeto
static -> metodo que pode ser acessado somente pela classe

## Como usar o Scanner para leitura do stdin

## Bibliotecas inportantes
import java.util.Scanner/
*/
