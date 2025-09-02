# varrendo-host-em-C
meu primeiro programa em c varrendo host.

O código abaixo mostra como criar um programa em C, trabalhar com variáveis e imprimir informações no terminal.

⚠️ Uso exclusivo para fins educacionais • Desenvolvido por M!ss s3c

📝 Guia passo a passo: Criando e executando seu programa

1. Criar o arquivo do programa

No terminal, digite:

nano program.c


Adicione o seguinte código:

// Meu Primeiro programa em C
#include <stdio.h>

int main(void) {

    int porta = 80;
    char ip[] = "192.168.0.1";
    float ver = 1.1;

    printf("Desec Security\n");
    printf("Scan Versao: %.1f \n", ver);  // imprime apenas 1 casa decimal
    printf("Varrendo Host: %s na porta %i \n", ip, porta);

    return 0;
}

2. Compilar o programa

No terminal, digite:

gcc program.c -o program


gcc → compilador do C.

-o program → nome do arquivo executável gerado.

3. Executar o programa
./program

4. Exemplo de saída
M!ss s3c
Scan Versao: 1.1
Varrendo Host: 192.168.0.1 na porta 80

👉 O que você aprendeu aqui

int → tipo de variável inteira.

char[] → tipo de variável para texto (string).

float → tipo de variável para números decimais.

printf() → imprime informações na tela.

%.1f → formata float para uma casa decimal.

Compilar programas em C é obrigatório antes de executar.
