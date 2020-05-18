# Flex-Container

## Flex-Direction

> Propriedade: 

```css
.container {
  display: flex;
  flex-direction: [?];
}
```

*main-axios*
> flex-direction: row | row-reverse 

*cross-axios*
> flex-direction: column | column-reverse

## Flex-Wrap

Ele nos fornece condições para que possamos controlar os nossos  `flex-item`
quando visualizamos que eles irão quebrar ultrapassar a medida
que foi definida para o nosso `flex-container`.

> Propriedade:

```css
.container {
  display: flex;
  flex-direction: row;
  flex-wrap: nowrap | wrap | wrap-reverse |
}
```

## Flex-flow

Se trata de um shorthand para que possamos definir através de uma propriedade,
os valores para `flex-directon` e `flex-wrap`, desta forma escrevemos menos CSS.

> Propriedade:

```css
.container {
  display: flex;
  border: 5px solid #f1c40f;
  width: 500px;
  /*---flex-direction: row;---
  ---flex-wrap:wrap;---*/
 
  /* flex-flow: <flex-direction> <flex-wrap> */
  flex-flow: row wrap;
}
```

## Justify-Content

Serve para que possamos controlar o alinhamento dos nossos `flex-item`, de forma 
de compreendermos melhor o seu uso seria uma alusão ao `text-align`. Ele executa a ordem a partir do main axios ou seja no eixo horizontal.

> Propriedades

```css
.container {
  display: flex;
  border: 5px solid #f1c40f;
  flex-direction: row;
  justify-content: flex-start | flex-end | center | space-around | space-between;
} 
```


## Align-items

Serve para que possamos controlar o alinhamento dos nossos `flex-item`,  similar ao `justify-content` porém seria a partir do cross-axios ou seja na vertical.

> Propriedades

```css
.container {
  display: flex;
  border: 5px solid #f1c40f;
  width: 500px;
  height: 500px;
  flex-direction: row;
  align-items: stretch | flex-start | flex-end | center | baseline
} 
```


## Align-Content

É uma propriedade similar ao `justify-content` entretanto ela funciona para n linhas.

> Propriedades

```css
.container {
  display: flex;
  border: 5px solid #f1c40f;
  width: 500px;
  height: 500px;
  flex-direction: row;
  align-content: stretch | flex-start | flex-end | center | baseline
} 
```