#include <stdio.h> //importa biblioteca data padrão com entrada e saída, h= cabeçalho

int main () // função main tipo int, sabemos que é função por causa ()
{
    int idade; // variavel usada
    
    printf("informe sua idade "); //pede a idade
    scanf("%d", &idade); // exibe campo de digitação para o usuário, lê a informação digitada e guarda na variavel idade
    
    if( idade >= 18){ // se idade for maior ou igual a 18
        printf("você é maior de idade"); // exibe resultado se maior ou igual a 18 anos
    }
    else {
        printf("você é menor de idade"); // exibe resultado se menor que 18 anos
    }
    return 0; // fim
}
