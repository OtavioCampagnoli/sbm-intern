### Flex Box - Conceito

- Basicamente para utilizar as propriedades você precisa ter um container com display
flex;

#### justify-content

- Basicamente alinha itens horizontalmente e aceita os seguintes valores:
    - flex-start -> itens se alinham à esquerda do container;
    - flex-end -> itens se alinham à direita do container;
    - center -> itens se alinham no centro do container;
    - space-between -> itens se alinham com distância igual entre eles;
    - space-around -> itens se alinham com distância igual em torno deles.

#### align-items

- Basicamente alinha os itens verticalmente e aceita os seguintes valores:
    - flex-start: Itens se alinham na parte de cima do container;
    - flex-end: Itens se alinha na parte de baixo do container;
    - center: Itens se alinha no centro vertical do container;
    - baseline: Itens se alinham na linha base do container;
    - stretch> Itens se esticam para preencher o container.

#### flex-direction

- Basicamente define a direção em que os itens são posionados no container, aceitando
os seguintes valores:
    - row: itens são posicionados na mesma direção do texto;
    - row-reverse: itens são posicionados na direção oposta à do texto;
    - column: itens são posicionados de cima para baixo;
    - column-reverse: itens são posicionados de baixo para cima.
- Quando se usa column: o justify-content que alinha os itens na horizontal passa a alinhar os 
itens na vertical, e também o align-items que originalmente alinha na vertical os itens,
passa a alinhar na horizontal;