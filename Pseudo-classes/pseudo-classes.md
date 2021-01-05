# Pseudo-classes

É um tipo de seletor que irá selecionar um elemento que estiver em um estado específico.

Exemplo: É o primeiro elemento dentro de uma caixa, ou, o elemento está com o ponteiro do mouse em cima dele.

Pseudo-classes começam com 2 pontos seguidos do nome da pseudo class
`:pseudo-class-name`

## Selecionar elementos com pseudo-classes

* :first-child    - Seleciona o primeiro filho
* :nth-of-type()  - Seleciona qualquer elemento: (2, (3), (4)
* :nth-child()    - Seleciona qualquer filho do elemento: (1), (2), (3); Usando (even): seleciona os filhos de numeros pares; Usando (odd): seleciona os filhos de numero impar.

## Ações do usuário

* :hover          - Cria ações para quando o mouse passar sobre o elemento 
* :focus          - Usado mais para campos de input, muda os atributos do campo quando ele está sendo utilizado

## Atributos

* :disabled       - Muda os atributos do campo quando ele estiver desabilitado(disabled)
* :required       - Muda ps atributos quando o campo for obrigatorio(required)

## Referência

* https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-classes