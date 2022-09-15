# CSS

## What is CSS?

É a apresentação visual para o cliente, servem para estilizar o HTML, e significa Cascading Style Sheets ou Folhas de Estilo em Cascata.

## Declaration

Pedaço de código que irá ditar as propriedades e valores a serem aplicadas a um elemento HTML.

## Sintaxe

Seletor, chave (abre), propriedade, dois pontos, valor, ponto e vírgula, chave (fecha) 

```css
body {
  background: #f00;
}
```

## Cascading

Quando há 2 (ou mais) declarações a última será mais relevante

```css
body {
  background: #f00;
}
body {
  background: #00f;
}
```

## Specificity

Especifidade: Cada seletor tem um peso e a soma dos pesos, será levada em conta para que determinada declaração seja mais específica.

```css
#id {
  /* weight 100 */
}

.class {
  /* weight 10 */
}

element {
  /* weight 1 */
}
```