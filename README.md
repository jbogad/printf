# ft_printf

Este es un proyecto de la escuela 42 (42 Madrid) en el que se implementa una versión propia de la función `printf` de la librería estándar de C.

## Descripción

El objetivo del proyecto es recrear el comportamiento de `printf` manejando múltiples especificadores de formato y asegurando la correcta impresión de los datos.

## Funcionalidades

La función `ft_printf` soporta los siguientes especificadores:

- `%c` → Caracter
- `%s` → Cadena de caracteres
- `%p` → Puntero en formato hexadecimal
- `%d` → Entero decimal con signo
- `%i` → Entero decimal con signo
- `%u` → Entero decimal sin signo
- `%x` → Número en hexadecimal (minúsculas)
- `%X` → Número en hexadecimal (mayúsculas)
- `%%` → Imprime el símbolo `%`

## Uso

```c
#include "ft_printf.h"

int main(void) {
    ft_printf("Hola, %s! Tienes %d mensajes.\n", "usuario", 5);
    return 0;
}
```
