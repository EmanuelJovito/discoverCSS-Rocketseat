# Responsividade

## CCS units

Unidades de medidas do CSS

layout fixo
`px` - Pixels

layout Fluido 
`%`  - Porcentagem 
`auto` - Automática
`vh` - Viewport Height
`vw` - Viewport Width

textos fixos
`1px` = 0.75px
`16px` = 12pt

textos fluidos
`em` - multiplicado pelo pai
`rem` - multiplicado pelo root

## Media Queries

```css
@media (max-width: 320px) {
  #form h3 {
    font-size: 2rem;
  }
}
```