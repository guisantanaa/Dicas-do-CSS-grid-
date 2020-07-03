# CSS GRID

## GRID

- Bimensional
- Divisão de toda a página de linhas e colunas
- Colocar elementos onde quiser nessa Divisão

## GRID OU FLEXBO

- Grid: Duas dimensões (colunas e linhas)
- Flexbox: Uma dimensão (ou coluna ou linha)
- Um complenta o trabalho do outro 

## PROPRIEDADES

Vamos separar em 2 grupos:
`Container` e `item(s)`

## CONTAINER 
- display: Grid;
- grid-template-columns;
- grid-template-rows;
- grid gap
- grid-row-gap
- grid-template-areas

... e mais 4 propriedades e **alinhamento**

## ITEN(s)

- grid-columns
- grid-column-start
- grid-column-end
- grid-row
- grid-row-start
- grid-row-start
- grid-row-end
- grid-area

... e mais 2 propriedades de **alinhamento*

# Grid: alinhamento

Existe 6 propriedades para alinhamento:
1. `justify` e `align`
2. `content` e `items` e `self`

## Justify e align

Sabendo que o grid é bidemensional, nós temos o eixo X e o Y.

O **eixo x** é o posicionamento horizontal, da esquerda para a direita.

O **eixo y** é o posicionamento vertical, de cima para baixo 

## Content, Items e Self

Jutando o `justify` ou `align`, com esses elementos `content`, `items` e `self`; nós observamos nossas propriedades

### Content

`justify-content` e `align-content` nos permite alinhar o próprio grid, relativo ao espaço fora do grid.

O uso dessas propriedades são raras, pois só é aplicado o gird seja menor que a area definida. (por exemplo, quando usamos em px o tmanaho do grid, poderemos terminar com um grid pequeno, para o tamanho da area do grid)

Podemos usar **7 Valores**:
1. start
2. end 
3. center 
4. stretch
5. space-between
6.space-around
7.space-evenly

### Items

`justify-items` e `align-content` vai permitir alinhar os items do nosso grid, em qualquer espaço disponivel, na célula que ele habitar.

Podemos usar **4 valores**;
1. start
2. end
3. center
4. stretch

### Self

`justify-self` e `align-self` vai nos permitir alinhar o item em si.
