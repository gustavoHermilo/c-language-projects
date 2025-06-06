# ejercicios_en_c
ejercicios de programación utilizando lenguaje c 
Este repositorio contiene mis primeros programas en lenguaje C, como parte de mi aprendizaje para programar microcontroladores y robots.
##  Programa: promedio de notas

Calcula el promedio entre dos calificaciones ingresadas por el usuario.

### Código fuente

```c
#include <stdio.h>
int main() {
    float examen1, examen2;
    printf("Ingrese la nota del primer examen: ");
    scanf("%f", &examen1);
    printf("Ingrese la nota del segundo examen: ");
    scanf("%f", &examen2);

    float notafinal = (examen1 + examen2) / 2;

    printf("Primer examen: %.2f\n", examen1);
    printf("Segundo examen: %.2f\n", examen2);
    printf("La nota final es: %.2f\n", notafinal);

    return 0;
}
