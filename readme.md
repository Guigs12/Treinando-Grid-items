# CSS GRID


## GRID

- Bimensional
- Divisão de toda a página em linhas e coluna
- Colocar elementos onde quisr nessa divisão

---

## GRID OU FLEXBOX
- Grid: Duas dimensões (colunas e linhas)
- Flexbox: Uma dimensão (ou coluna ou linha)
- Um complementa o trabalho do outro
- Verificar quais navegadores ainda não estão aceitando o Grid



---

## PROPRIEDADES


Vamos separar em 2 grupos:
`container` e `itenm(s)`

---
### CONTAINER

- display: grid; -> Inicia o container avisando que é um grid!
- grid-template-columns; -> Fatia suas colunas, avisando quantas colunas possui!
- grid-template-rows; -> Informa quantas linhas possui!
- grid-gap -> Informa espaçamento
  - grid-row-gap 
  - grid-column-gap
- grid-template-areas; -> Delimita as áreas!

... e mais 4 propriedades e **alinhamento**


---
## ITEM(s)

- grid-column
  - grid-column-start
  - grid-column-end
- grid-row
  - grid-row-start
  - grid-row-end
-grid-area

... e mais 2 propriedades de **alinhamento**


## GRID: Alinhamento
---

Existem 6 propriedades para alinhamento:
1. `Justify-content`
2. `Align-content`
3. `Justify-items`
4. `Align-items`
5. `Justify-self`
6. `Align-self`

Vamos separar em 2 grupos
1. `Justify` e `Align`
2. `Content`, `Items` e `Self`

## Justify e Align

Sabendo que o grid é bidimensional, nós temos o eixo x e o y.

O **eixo x** é o posicionamento horizontal, da esquerda para a direita.

O **eixo y** é o posicionamento vertical, de cima para baixo.


---

## Content, Items e Self

Juntando o `justify`, ou `align`, com esses elementos: `content`, `items` e `self`; nós observamos nossas propriedades

### Content