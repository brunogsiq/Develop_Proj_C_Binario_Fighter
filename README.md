# Develop_Proj_C_Binario_Fighter

# Documentação: Binário Fighter 🎮

## Introdução

Bem-vindo ao Binário Fighter, um jogo simples em linguagem C que simula um combate entre um herói e um vilão! Este documento fornece uma visão geral do código e explica como jogar esse emocionante jogo de combate binário.

## Função `numeroAletorio`

```c
int numeroAletorio(int atq1, int atq2, int hp1, int hp2)
```

Esta função realiza um combate entre um herói e um vilão, simulando ataques aleatórios e reduzindo os pontos de vida (HP) de cada personagem. O combate continua até que o HP de um dos personagens atinja zero.

### Parâmetros

- `atq1`: Ataque do vilão.
- `atq2`: Ataque do herói.
- `hp1`: Pontos de vida do vilão.
- `hp2`: Pontos de vida do herói.

## Função `main`

```c
int main()
```

A função principal inicia o jogo Binário Fighter. O jogador decide se deseja entrar na batalha ou fugir. Se optar por entrar, terá que escolher entre lutar como herói ou vilão. A força e o HP são definidos aleatoriamente, e a função `numeroAletorio` é chamada para simular o combate.

### Variáveis

- `inscricao`: Decisão do jogador para entrar (1) ou fugir (2).
- `lutador`: Escolha do jogador para lutar como herói (1) ou vilão (2).
- `ataquePL1`: Ataque do vilão.
- `ataquePL2`: Ataque do herói.
- `hpVidaMocinho`: Pontos de vida do herói.
- `hpVidaVilao`: Pontos de vida do vilão.

## Paleta de Cores e Estilo

O jogo utiliza a biblioteca `conio.h` para ajustar a paleta de cores. A função `system("Color 47")` define um esquema de cores atraente durante a execução do jogo.

## Como Jogar

1. Execute o programa e escolha entre entrar (1) ou fugir (2).
2. Se escolher entrar, selecione seu lutador, herói (1) ou vilão (2).
3. A batalha começará, e os ataques serão simulados.
4. Ao final, o resultado da batalha será exibido - vilão vence, herói vence ou empate.
5. Você terá a opção de tentar novamente ou encerrar o jogo.

Divirta-se jogando Binário Fighter! 🎮✨
[IMAGE 1](https://github.com/brunogsiq/Inventions_Projects_Tests/tree/main/C/Binario_Fighter/public/images/1.PNG)

[IMAGE 2](https://github.com/brunogsiq/Inventions_Projects_Tests/blob/master/C/Binario_Fighter/public/images/2.PNG)

[IMAGE 3](https://github.com/brunogsiq/Inventions_Projects_Tests/blob/master/C/Binario_Fighter/public/images/3.PNG)

[IMAGE 4](https://github.com/brunogsiq/Inventions_Projects_Tests/blob/master/C/Binario_Fighter/public/images/4.PNG)