# Calculadora de Tabuada em C

## Descrição

A Calculadora de Tabuada em C é um programa desenvolvido na linguagem C que calcula e exibe a tabuada de um número inteiro informado pelo usuário. O programa apresenta os resultados da multiplicação desse número pelos valores de 1 a 10.

Ele é útil para estudantes que desejam praticar matemática básica e para iniciantes em programação.

## Demonstração

A imagem abaixo mostra a execução do programa no terminal.

![Demonstração da Calculadora de Tabuada](assets/demo.png)

### Exemplo de resultado

Ao informar o número `2`, o programa apresenta:

```text
2 * 1 = 2
2 * 2 = 4
2 * 3 = 6
2 * 4 = 8
2 * 5 = 10
2 * 6 = 12
2 * 7 = 14
2 * 8 = 16
2 * 9 = 18
2 * 10 = 20
Instalação e pré-requisitos
É necessário ter um compilador C, como o GCC, instalado no computador.

O programa utiliza apenas a biblioteca padrão stdio.h e não necessita de bibliotecas externas.

Verificar o compilador
Abra o terminal e execute:

bash
gcc --version
Compilar o programa
Na pasta que contém o arquivo main.c, execute:

bash
gcc main.c -o tabuada
Uso e exemplos
Executar no Windows
powershell
.\tabuada.exe
Executar no Linux
bash
./tabuada
Exemplo de uso
Quando o programa solicitar a entrada, digite 2 e pressione Enter.

Saída esperada:

text
2 * 1 = 2
2 * 2 = 4
2 * 3 = 6
2 * 4 = 8
2 * 5 = 10
2 * 6 = 12
2 * 7 = 14
2 * 8 = 16
2 * 9 = 18
2 * 10 = 20
Você pode informar outros números inteiros para consultar outras tabuadas.

Estrutura do projeto
text
meu-projeto/
├── README.md
├── LICENSE
├── main.c
└── assets/
    └── demo.png
Arquivos e pastas
README.md: documentação do projeto.

LICENSE: texto completo da licença adotada.

main.c: código-fonte do programa.

assets/demo.png: captura real da execução do programa.

Licença
Este projeto utiliza a licença MIT. Consulte o arquivo LICENSE para ler o texto completo da licença.