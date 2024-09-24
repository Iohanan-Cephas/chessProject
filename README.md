# Chess Game

Este é um jogo de xadrez implementado em Java. O jogo pode ser jogado em um terminal, permitindo que os usuários joguem entre si, realizando movimentos válidos para as peças de xadrez.

## Pré-requisitos

Antes de rodar o programa, certifique-se de ter o seguinte instalado em sua máquina:

- **Java JDK 11 ou superior**: Você pode baixar o JDK do [site oficial do Oracle](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html) ou usar uma versão open-source como o [OpenJDK](https://openjdk.java.net/).
- **Um IDE ou editor de texto**: Para compilar e executar o código. Algumas opções populares incluem:
  - IntelliJ IDEA
  - Eclipse
  - VS Code

## Como Jogar

- O jogo começa com a configuração padrão de xadrez.
- Os jogadores se revezam para mover suas peças.
- Para mover uma peça, digite a posição de origem e a posição de destino no formato **`<coluna><linha>`**. Por exemplo:
  - Para mover uma peça de **e2** para **e4**, você deve digitar:
    ```bash
    e2
    ```
  - E depois digitar:
    ```bash
    e4
    ```
### Regras Básicas do Jogo

- **Movimentação das Peças**:
  - As peças se movem de acordo com as regras tradicionais do xadrez.
  - Se um movimento não for válido, o jogo irá retornar uma mensagem de erro.

- **Captura**: 
  - Se você capturar uma peça adversária, ela será removida do tabuleiro.

- **Xeque e Xeque-Mate**:
  - O jogo verifica automaticamente se um jogador está em xeque.
  - Se um jogador não puder fazer um movimento válido e estiver em xeque, o jogo termina em xeque-mate.

## Contribuindo

Se você quiser contribuir para o projeto, sinta-se à vontade para abrir uma issue ou enviar um pull request. Suas sugestões e melhorias são bem-vindas!