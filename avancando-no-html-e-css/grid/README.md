# CSS Grid

## Propriedades Fundamentais
Todo grid é composto de 2 principais grupos:
`container: o pai` e `itens: o(s) filhos`

---

### Container (pai)
- display: grid;
- grid-template;
  - grid-template-columns;
  - grid-template-rows;
  - grid-template-areas;

---

### Itens (filhos)
- grid-column;
  - grid-column-start;
  - grid-column-end;
- grid-row;
  - grid-row-start;
  - grid-row-end;

---

## Propriedades de Alinhamento
Existem 9 propriedades fundamentais

**6 aplicadas em container:**
`align-content`,
`justify-content`,
`place-content`,
`align-items`,
`justify-items`,
`place-items`

**3 aplicadas em items:**
`align-self`,
`justify-self`,
`place-self`

Então podemos separar em 3 grupos:
`align`, `justify`, `place`

E cada um deles irá observar ou o
- conteúdo do elemento `content`
- itens do elemento `items`
- o próprio elemento `self`

---

### Propriedades Auto
- grid-auto-flow
- grid-auto-rows
- grid-auto-columns