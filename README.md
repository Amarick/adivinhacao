# Jogo de Adivinhação

Este é um programa simples em Java que simula um jogo de adivinhação. O objetivo do jogo é tentar adivinhar um número aleatório gerado pelo computador, entre 0 e 100, em até 5 tentativas.

## Funcionalidades

- O programa gera um número aleatório entre 0 e 100.
- O usuário tem até 5 tentativas para adivinhar o número.
- A cada tentativa, o programa informa se o número digitado é maior ou menor do que o número gerado.
- Caso o usuário acerte o número, o programa finaliza o jogo.
- Após esgotar todas as tentativas, o programa revela o número correto.

## Estrutura do Código
- O número aleatório é gerado utilizando:
   ```bash
  new Random().nextInt(100);

- O **Scanner** é utilizado para capturar a entrada do usuário.
- Um **loop** for é usado para controlar o número de tentativas.
- A instrução **break** é utilizada para encerrar o loop caso o usuário acerte o número.

## Desenvolvido em Java como um projeto educativo.
