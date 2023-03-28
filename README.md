# Guia  1

# NO SE COPIEN VAGOS 

### **Alumno:** Juan Baader

### **Año:** 2023

### **Curso:** 3B TIC

### **Profesora** Luu Parrondo

[Link a Github](https://github.com/juanpanpanyz/Guia1)

<br>

## **Primer Ejercicio**

```c#

using System;

class Program {
  public static void Main (string[] args) {
    var numa = 6;
    var numb = 9;
    var numc = 12;
    var numd = numa + numb + numc; // 27
    Console.WriteLine (numd);
  }
}
```

## **Segundo Ejercicio**

```c#
using System;

class Program {
  public static void Main (string[] args) {
    int num1 = 0; int num2 = 0;

    Console.WriteLine("Console Calculator in C#\r");
    Console.WriteLine("------------------------\n");

    Console.WriteLine("Type a number, and then press Enter");
    num1 = Convert.ToInt32(Console.ReadLine());

    Console.WriteLine("Type another number, and then press Enter");
    num2 = Convert.ToInt32(Console.ReadLine());

    Console.WriteLine("Choose an option from the following list:");
    Console.WriteLine("\ta - Add");
    Console.WriteLine("\ts - Subtract");
    Console.WriteLine("\tm - Multiply");
    Console.WriteLine("\td - Divide");
    Console.Write("Your option? ");

    switch (Console.ReadLine())
    {
        case "a":
            Console.WriteLine($"Your result: {num1} + {num2} = " + (num1 + num2));
            break;
        case "s":
            Console.WriteLine($"Your result: {num1} - {num2} = " + (num1 - num2));
            break;
        case "m":
            Console.WriteLine($"Your result: {num1} * {num2} = " + (num1 * num2));
            break;
        case "d":
            Console.WriteLine($"Your result: {num1} / {num2} = " + (num1 / num2));
            break;
    }
    Console.Write("Press any key to close the Calculator console app...");
    Console.ReadKey();
  }
}
```

## **Tercer Ejercicio**

```c#
using System;

class Program {
  public static void Main (string[] args) {
    Console.WriteLine ("Ingrese su nombre");
    string nombre = Convert.ToString(Console.ReadLine ());
    Console.WriteLine ("Ingrese su edad");
    int edad = Convert.ToInt32(Console.ReadLine ());
    Console.WriteLine ("Hola " + nombre + ", usted tiene " + edad + " años");
  }
}
```

## **Cuarto Ejercicio**

```c#
using System;

class Program {
  public static void Main (string[] args) {
     Console.WriteLine ("Ingresar la nota de el primer trimestre");
    int tri1 = Convert.ToInt32(Console.ReadLine());
    Console.WriteLine ("Ingresar la nota de el segundo trimestre");
    int tri2 = Convert.ToInt32(Console.ReadLine());
    Console.WriteLine ("Ingresar la nota de el tercer trimestre");
    int tri3 = Convert.ToInt32(Console.ReadLine());
    int promedio = (tri1 + tri2 + tri3) / 3;
    Console.WriteLine (promedio);
  }
}
```

## **Quinto Ejercicio**

```c#
using System;

class Program {
  public static void Main (string[] args) {
    Console.WriteLine ("Ingresar altura");
    int altura = Convert.ToInt32(Console.ReadLine());
    Console.WriteLine ("Ingresar base");
    int basesita = Convert.ToInt32(Console.ReadLine());
    int superficie = basesita * altura / 2;
    Console.WriteLine (superficie);
  }
}
```

## **Sexto Ejercicio**

```c#
using System;

class Program {
  public static void Main (string[] args) {
    Console.WriteLine ("Ingresar precio del producto para recibir cuanto pagaria con el valor del IVA incluido");
    int precio = Convert.ToInt32(Console.ReadLine());
    int ivachoto = precio + precio / 100 * 21;
    Console.WriteLine (ivachoto);
  }
}   
```

## **Septimo Ejercicio**

```c#
using System;

class Program {
  public static void Main (string[] args) {
    Console.WriteLine ("Ingresar precio de la nafta");
    int nafta = Convert.ToInt32(Console.ReadLine());
    Console.WriteLine ("Ingresar la distancia recorrida");
    int distancia = Convert.ToInt32(Console.ReadLine());
    int gastos = nafta * distancia / 10;
    Console.WriteLine (gastos);
  }
}
```
