# calculadora-multifuncional
calculadora multifuncional passada em grupo.

Objetivo:

Desenvolver uma calculadora multifuncional utilizando o Flowgorithm, permitindo ao usuário escolher diferentes operações matemáticas por meio de um menu. O programa foi estruturado para executar uma operação, apresentar o resultado de forma clara e organizada e retornar automaticamente ao menu inicial até que o usuário escolha a opção de encerramento.

Integrantes do Grupo:

- Integrante 1: Matheus De lima Braz
- Integrante 2: João Pedro Guimarães de Lima Cruvinel
- Integrante 3: Lucas Eduardo Sousa Silva
- Integrante 4: Paulo Victor Oliveira Dos Santos

Descrição das 10 Funções

O programa possui 10 funções/operações matemáticas principais:

1. **Soma**  
   Recebe dois números e calcula a soma entre eles.

2. **Subtração**  
   Recebe dois números e calcula a diferença entre o primeiro e o segundo.

3. **Multiplicação**  
   Recebe dois números e calcula o produto entre eles.

4. **Divisão**  
   Recebe dois números e realiza a divisão do primeiro pelo segundo. O programa verifica se o segundo número é diferente de zero antes de realizar a operação.

5. **Potência**  
   Recebe uma base e um expoente e calcula a potência correspondente.

6. **Raiz quadrada**  
   Recebe um número e calcula sua raiz quadrada. O programa verifica se o número é maior ou igual a zero para evitar uma raiz quadrada de número negativo no conjunto dos números reais.

7. **Média**  
   Recebe três números e calcula a média aritmética entre eles.

8. **Porcentagem**  
   Recebe uma porcentagem e um valor e calcula quanto essa porcentagem representa do valor informado.

9. **Área do círculo**  
   Recebe o raio do círculo e calcula sua área utilizando a fórmula:

   `Área = π × raio²`

10. **Conversão de Celsius para Fahrenheit**  
    Recebe uma temperatura em Celsius e realiza a conversão para Fahrenheit utilizando a fórmula:

    `F = (C × 9 / 5) + 32`

** a opção 11 do menu  é uma função para encerrar o programa.

## Lógica de Funcionamento do Programa

Ao iniciar, o programa cria e inicializa as variáveis necessárias e define a opção inicial como `0`.

Em seguida, é executado um **While**, cuja condição é manter o programa funcionando enquanto a opção escolhida for diferente de `11`.

A cada repetição:

1. O menu da calculadora é exibido.
2. O usuário escolhe uma opção de `1` a `11`.
3. O programa verifica a opção escolhida por meio de estruturas de decisão.
4. Quando uma operação é selecionada, o programa solicita os valores necessários.
5. A operação matemática é realizada.
6. O resultado é armazenado na variável `resultado`.
7. O resultado é exibido de maneira clara e organizada.
8. O programa retorna ao menu inicial.
9. Esse processo continua até o usuário selecionar a opção `11`.
10. Ao selecionar `11`, o programa informa que foi encerrado e o `While` termina.

Caso o usuário digite uma opção que não exista no menu, o programa apresenta a mensagem **"opcao invalida!"** e retorna ao menu.

## Estruturas Utilizadas

### While

A estrutura **While** é utilizada para manter a calculadora em funcionamento e fazer com que o menu seja exibido novamente após cada operação.

A condição utilizada é equivalente a:

`opcao != 11`

Assim, o programa continua repetindo enquanto a opção escolhida não for 11.

### Decisões

O programa utiliza estruturas **If/Else** para identificar a opção escolhida pelo usuário.

Cada opção do menu é verificada individualmente, permitindo executar a operação correspondente.

Também existem decisões para tratar situações específicas:

- divisão por zero;
- raiz quadrada de número negativo;
- opção inválida;
- encerramento do programa.

### Variáveis

As principais variáveis utilizadas são:

- **opcao** — armazena a opção escolhida no menu.
- **num1** — armazena o primeiro valor ou o valor principal utilizado em várias operações.
- **num2** — armazena o segundo valor quando necessário.
- **num3** — armazena o terceiro valor utilizado no cálculo da média.
- **resultado** — armazena o resultado das operações matemáticas.

As variáveis numéricas utilizadas para os cálculos são do tipo **Real**, enquanto `opcao` é do tipo **Integer**.

### Entrada de dados

A estrutura **Input** é utilizada para receber os valores digitados pelo usuário.

### Saída de dados

A estrutura **Output** é utilizada para apresentar o menu, solicitar informações e mostrar mensagens e resultados.

Os resultados são apresentados em um bloco organizado, facilitando a leitura pelo usuário.

### Atribuição

A estrutura **Assign** é utilizada para realizar cálculos e armazenar os valores nas variáveis.

## Ferramenta Utilizada

O projeto foi desenvolvido utilizando o **Flowgorithm**, uma ferramenta de criação e execução de fluxogramas que permite representar visualmente a lógica de um programa.

O arquivo principal do projeto possui extensão:

` .fprg `

## Instruções para Execução

1. Instale e abra o **Flowgorithm** no computador.
2. Abra o arquivo da calculadora com extensão `.fprg`.
3. Execute o fluxograma utilizando a opção de execução do Flowgorithm.
4. O menu da calculadora será apresentado.
5. Digite o número correspondente à operação desejada.
6. Informe os valores solicitados.
7. O resultado será apresentado de forma clara e organizada.
8. Após o resultado, a calculadora retornará automaticamente ao menu inicial.
9. Para encerrar o programa, escolha a opção **11 - Encerrar**.

## Menu do Programa

```text
Calculadora Multifuncional

1. Soma
2. Subtração
3. Multiplicação
4. Divisão
5. Potência
6. Raiz quadrada
7. Média
8. Porcentagem
9. Área do círculo
10. Celsius para Fahrenheit
11. Encerrar
```

## Tratamento de Erros

A calculadora possui algumas verificações para evitar resultados inválidos:

- Na divisão, o programa verifica se o divisor é diferente de zero.
- Na raiz quadrada, o programa verifica se o número é maior ou igual a zero.
- Se o usuário escolher uma opção que não esteja entre as opções disponíveis, o programa informa que a opção é inválida e retorna ao menu.
