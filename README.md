# quest-o-6
#include <stdio.h>

int main() {
    float num1, num2;
    float divisao;

    printf("Digite o primeiro número: ");
    scanf("%f", &num1);
    
    printf("Digite o segundo número: ");
    scanf("%f", &num2);
    
    divisao = num1 / num2;

    printf("Divisão: %.2f\n", divisao);

    return 0;
}

