# Trabalhando com fontes

Tipografia transmite mensagem

  - negrito
  - tamanho
  - estilo

--------------------------------------------------------------------------------

## Basic Font Properties

* font-family
* font-weight
* font-style
* font-size

--------------------------------------------------------------------------------

## Fonte Family

* Tipo de fonte de um elemento
* Lista de fontes e ordem de prioridades
* Inclui *fallback* font

```css
p {
  font-family: "Times New Roman", Times, serif;
}
```

  - serif
  - sans

--------------------------------------------------------------------------------

## Font Weight

* Peso da fonte

```css
span {
  font-weight: bold;
}
```

* Dependendo da familia de font, não poderemos acessar todos os pesos

--------------------------------------------------------------------------------

## Font Style

* O Estilo da fonte

```css
span { 
  font-style: italic;
}
```

--------------------------------------------------------------------------------

## Font Size

* O tamanho da fonte

```css
p {
  font-size: 18px;
}
```

--------------------------------------------------------------------------------

## Web Fonts

- Fontes do sistema x fontes da web
- como usar fontes para web?

  * @font-face
  * @import
  * link


### Referências

* https://www.w3.org/TR/css-fonts-3/
* https://css-tricks.com/snippets/css/using-font-face/

--------------------------------------------------------------------------------

# Atribuindo mais estilo às fontes

* https://developer.mozilla.org/en-US/docs/Learn/CSS/Styling_text/Fundamentals

## font-variant

* Variações na apresentação fonte

```css
p {
  font-variant: small-caps;
}
```

* https://developer.mozilla.org/en-US/docs/Web/CSS/font-variant

## font-stretch

* Alargamento ou encolhimento da fonte
* Aceita palavra-chaves como: expanded, condensed, normal
* Aceita porcentagens de 50% a 200%

```css
p {
  font-stretch: expanded;
}
```

* https://developer.mozilla.org/en-US/docs/Web/CSS/font-stretch

## letter-spacing

* Espaços entre caracteres

```css
p {
  letter-spacing: 4px;
}
```
* https://developer.mozilla.org/en-US/docs/Web/CSS/letter-spacing

## word-spacing

* Espaços entre caracteres

```css
p {
  word-spacing: 4px;
}
```

* https://developer.mozilla.org/en-US/docs/Web/CSS/word-spacing

## line-height

* Espaços entre linhas
* Pode ser com unidades ou sem unidades de medida
* Comuns: 1.5 ou 2

```css
p {
  line-height: 1.6;
}
``` 

* https://developer.mozilla.org/en-US/docs/Web/CSS/line-height

## text-transform

* Transforma o texto

```css
p {
  text-transform: uppercase; /* capitalize | lowercase | none */
}
``` 

* https://developer.mozilla.org/en-US/docs/Web/CSS/text-transform

## text-decoration

* Aparencia decorativa de um texto
* Line: underline | overline | line-through
  * podemos aplicar mais de 1 valor
* style: wavy | dotted | double | dashed | solid
* color: `<color>` values

```css
p {
  text-decoration: underline; /* shorthand */
}
```

* https://developer.mozilla.org/en-US/docs/Web/CSS/text-decoration

## text-align

* Alinhamento de um texto

```css
p {
  text-align: center; /* left | right | center | justify */
}
```

* https://developer.mozilla.org/en-US/docs/Web/CSS/text-align

## text-shadow

* Sombra aplicada a um texto
* Permite múltiplos valores 

```css
p {
  text-shadow: 1px 1px 1px red,
              2px 2px 1px green; /* offset-x | offset-y | blur-radius | color */
}
```

* https://developer.mozilla.org/en-US/docs/Web/CSS/text-shadow 

## Shorthand

* font-style, font-variant, font-weight, font-stretch, font-size, line-height, e font-family.

```css
p {
  /* -style, -variant, weight, -stretch, -size, line-height, e -family. */
  font: italic normal bold normal 3em/1.5 Helvetica, Arial, sans-serif;
}
```