# Attt9
#include <stdio.h>
#define PI 3.14159

int main() {
    float raio, volume;

    printf("Digite o raio da esfera: ");
    scanf("%f", &raio);

    volume = (4.0/3.0) * PI * raio * raio * raio;

    printf("O volume da esfera é: %.2f\n", volume);

    return 0;
}
