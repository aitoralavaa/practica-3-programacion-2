**PROGRAMA DE APROXIMACIÓN DE PI MEDIANTE EL MÉTODO DE MONTECARLO CON EXPRESIONES LAMBDA**

**Indice**:

- [introducción](introducción)
  
- [Instalación](Instalación)
  
- [Uso](Uso)

## introducción

El programa utiliza el método de Montecarlo para aproximar el valor de pi. Genera puntos aleatorios dentro de un cuadrado y cuenta cuántos caen dentro de un círculo inscrito en ese cuadrado. La relación entre el área del círculo y el área del cuadrado nos da una aproximación de pi.

## instalación

para instalar este programa, primero hay que asegurarse de instalar Java Development kit (JDK).

luego debe clonar el siguiente repositorio en su terminal o la computadora en la que lo vaya a realizar:

```https://github.com/aitoralavaa/practica-3-programacion-2```

Para acceder al directorio:

```cd practica3programacion2```

Para compilar 

```make compilar```

Para crear un archivo JAR ejecutable:

```make jar```

Para generar documentación en formato HTML:

```make javadoc```

## Uso

Si quieres ejecutar el programa y obtener el número Pi, de forma aproximada, se debe utilizar el siguiente comando:

```java -jar pi.jar <numero de decimales>```
Ejemplo: java -jar pi.jar 100
