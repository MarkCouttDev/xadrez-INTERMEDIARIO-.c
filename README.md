# ♟️ Simulação de Movimentos de Peças de Xadrez em C - Nível Aventureiro

Projeto desenvolvido como parte do **Desafio de Programação - Nível Aventureiro**, com foco na aplicação prática de **loops aninhados** e estruturas de repetição na linguagem C. O objetivo é simular os movimentos de quatro peças do jogo de xadrez: Torre, Bispo, Rainha e Cavalo.

## 👨‍🎓 Aluno Desenvolvedor

**Marcos Augusto do Couto**

## 🎯 Objetivo

Simular os movimentos das peças de xadrez utilizando diferentes estruturas de repetição, agora incluindo o movimento do **Cavalo em "L"**:

- **Torre**: movimento horizontal (direita) usando `for`
- **Bispo**: movimento diagonal (cima e direita) usando `while`
- **Rainha**: movimento horizontal (esquerda) usando `do-while`
- **Cavalo**: movimento em "L" (2 casas para baixo e 1 casa para a esquerda) usando **loops aninhados** (`for` + `while`)

## 🧩 Estrutura do Código

O código está contido em um único arquivo: `xadrez.c`.

Cada peça é simulada com uma estrutura de repetição específica:

| Peça   | Direção do Movimento             | Estrutura Usada               |
|--------|---------------------------------|-------------------------------|
| Torre  | 5 casas para a direita          | `for`                        |
| Bispo  | 5 casas na diagonal superior direita | `while`                      |
| Rainha | 8 casas para a esquerda         | `do-while`                   |
| Cavalo | 2 casas para baixo + 1 para a esquerda | `for` aninhado com `while` |

