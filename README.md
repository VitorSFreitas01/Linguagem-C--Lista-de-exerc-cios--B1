# Linguagem-C--Lista-de-exerc-cios--B1

exe.1
#include <stdio.h>

int main() {
    float num1, num2, num3;

    printf("Digite três números: ");
    scanf("%f %f %f", &num1, &num2, &num3);

    if (num1 <= num2 && num1 <= num3) {
        printf("O menor número é: %.2f\n", num1);
    } else if (num2 <= num1 && num2 <= num3) {
        printf("O menor número é: %.2f\n", num2);
    } else {
        printf("O menor número é: %.2f\n", num3);
    }

    return 0;
}
 --------------------------------------------------

exe.2
#include <stdio.h>

int main() {
    float num1, num2, num3;

    printf("Digite três números: ");
    scanf("%f %f %f", &num1, &num2, &num3);

    if (num1 >= num2 && num1 >= num3) {
        printf("O maior número é: %.2f\n", num1);
    } else if (num2 >= num1 && num2 >= num3) {
        printf("O maior número é: %.2f\n", num2);
    } else {
        printf("O maior número é: %.2f\n", num3);
    }

    return 0;
}
---------------------------------------------------

exe.3
#include <stdio.h>

int main() {
    float celsius, fahrenheit;

    printf("Digite a temperatura em graus Celsius: ");
    scanf("%f", &celsius);

    // Convertendo Celsius para Fahrenheit
    fahrenheit = celsius * (9.0 / 5.0) + 32;

    printf("%.2f graus Celsius equivalem a %.2f graus Fahrenheit.\n", celsius, fahrenheit);

    return 0;
}
-----------------------------------------------------

exe.4
#include <stdio.h>

int main() {
    float lado1, lado2, lado3;

    printf("Digite o comprimento dos três lados do triângulo: ");
    scanf("%f %f %f", &lado1, &lado2, &lado3);

    if (lado1 == lado2 && lado2 == lado3) {
        printf("O triângulo é equilátero.\n");
    } else if (lado1 == lado2 || lado1 == lado3 || lado2 == lado3) {
        printf("O triângulo é isósceles.\n");
    } else {
        printf("O triângulo é escaleno.\n");
    }

    return 0;
}



