# Prova-do-melhor-professor-do-mundo-Donde-queres-Palmeiras-n-o-tem-mundialll
1 - #include<stdio.h>
int main(){
    int numeros;
    int numeros2;
    int multi = 0; 
    int div = 0;
    int sub = 0; 
    int soma = 0;

    printf("\n--- NUMEROS ---\n");

    for(int i = 1; i <= 1; i++){
        printf("\nInsira o 1Â° numero: ");
        scanf("%d", &numeros);
        printf("\nInsira o 2Â° numero: ");
        scanf("%d", &numeros2);

        multi = numeros * numeros2;
        div = numeros / numeros2;
        soma = numeros + numeros2;
        sub = numeros - numeros2;
    }

    printf("\nA soma dos numeros e: %d", soma);
    printf("\nA subtracao dos numeros e: %d", sub);
    printf("\nA multiplicacao dos numeros e: %d", multi);
    printf("\nA divisao dos numeros e: %d", div);

    return 0;
}

2 - #include<stdio.h>
int main(){
    int numero;

    for(int i = 1; i <= 10; i++){
        printf("\nNumero: %d\n", i);
    }

    return 0;
}

3 - #include <stdio.h>

int main(){
    int numero = 1;

    while (numero <= 5) {
        printf("%d\n", numero);
        numero++;
    }

    return 0;
}

4 - #include <stdio.h>

int main(){
    int senha = 123;
    int senha_digitada;

    do {
        printf("\n--- ARROGANTHI, DONDE QUERES????? ---\n");

        printf("Digite sua senha: ");
        scanf("%d", &senha_digitada);

        if(senha_digitada == senha){
            printf("\nSenha correta!\nAcesso liberado!");
        } else{
            printf("\nSenha incorreta!\nTente novamente!");
        }

    } while (senha_digitada != senha);
   


    return 0;
}

5 - #include <stdio.h>

int main() {
    int i;

    for (i = 1; i <= 5; i++) {
        printf("%d\n", i);
    }
    //Os nÃºmeros que aparecem na tela apÃ³s iniciar o programa sÃ£o: 1, 2, 3, 4 e 5.
    return 0;
}

6 - #include <stdio.h>

int main() {
    int x = 5;

    if (x > 3) {
        printf("Maior que 3");
    } else {
        printf("Menor ou igual a 3");
    }
    //O resultado sempre serÃ¡ maior que 3, porque o x foi atribuido direto com o valor 5.
    return 0;
}

7 -   #include <stdio.h>

int main() {
    int opcao;
    int numero;
    int numero2;
    int resultado;

    do{
        printf("\n--- NUMEROS ARROGANTHIS ---\n");
        printf("\nInsira o 1Â° numero: ");
        scanf("%d", &numero);
        printf("\nInsira o 2Â° numero: ");
        scanf("%d", &numero2);
        printf("\n--- Escolha uma operacao ---\n");
        printf("\n1 - Soma\n2 - Subtracao\n3 - Multiplicacao\n4 - Divisao\n5 - Sair\nResposta: ");
        scanf("%d", &opcao);

        switch(opcao){
            case 1:
                printf("\n--- Soma ---\n");
                resultado = numero + numero2;
                printf("\nA soma dos numeros %d e %d e: %d\n", numero, numero2, resultado);
                break;
            case 2:
                printf("\n--- Subtracao ---\n");
                resultado = numero - numero2;
                printf("\nA subtracao dos numeros %d e %d e: %d\n", numero, numero2, resultado);
                break;
            case 3:
                printf("\n--- Multiplicacao ---\n");
                resultado = numero * numero2;
                printf("\nA multiplicacao dos numeros %d e %d e: %d\n", numero, numero2, resultado);
                break;
            case 4:
                printf("\n--- Divisao ---\n");
                if (numero2 == 0) {
                    printf("\nErro: nao e possivel dividir por zero.\n");
                } else {
                    resultado = numero / numero2;
                    printf("\nA divisao dos numeros %d e %d e: %d\n", numero, numero2, resultado);
                }
                break;
            case 5:
                printf("\nSaindo...\n");
                break;
            default:
                printf("\nOpcao invalida.\n");
                break;
        }
    }
    while(opcao != 5);
    return 0;
}

8 - #include <stdio.h>

int main(){
    int numero;

    printf("Digite um numero: ");
    scanf("%d", &numero);

    for (int i = 1; i <= 10; i++) {
        printf("%d x %d = %d\n", numero, i, numero * i);
    }

    return 0;
}

9 - #include <stdio.h>

int main(){
    int numero = 1;
    int soma = 0;

    printf("\n DONDE QUERES???\n");

    while (numero <= 5) {
        soma += numero;
        numero++;
    }

    printf("Resultado da soma: %d\n", soma);

    return 0;
}

10 - #include <stdio.h>

int main(){

    printf("\nNumeros ARROGANTHI ---\n");
    for(int i = 1; i <= 20; i++){
        if(i % 2 == 0){
            printf("%d\n", i);
        }
    }
    return 0;
}
