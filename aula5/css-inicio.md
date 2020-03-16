# Resumo
> Nessa aula iremos ter uma visão inicial á respeito de folha de estilos o famoso CSS.

**CSS (Cascading Style Sheets)** é uma linguagem declarativa que controla a apresentação visual de páginas web em um navegador. O navegador aplica as declarações de estilo CSS aos elementos selecionados para exibi-los apropriadamente. Uma declaração de estilo contem as propriedades e seus valores, que determinam a aparência de uma página web.

CSS é uma das três principais tecnologias Web, junto com HTML e JavaScript. CSS normalmente estiliza **Elementos HTML**, mas também pode ser usada com outras linguagens de marcação como **SVG ou XML**.

*Resumo:*

 - CSS: Cascading Style Sheets
 - Separa a formação visual do conteúdo.
 - W3C - Mantém/Desenvolve as especificações.

### Anatomia
Uma regra CSS é um conjunto de propriedades associados a um seletor. 

**Web Docs, Mozilla**

Referência: [W3C](https://developer.mozilla.org/pt-BR/docs/Glossario/CSS)

> Seletores

Estilos inline  
Folha de estilos interna
Folha de estilos externa

div a
div p, div h1
* 
#id 
.class

pseudo-class
a:hover
a:visited
div + p
ul li:nth-child(1) {
  color: red;
}

### Propriedades de Texto
text-ident
white-space
word-spacing
letter-spacing

## Propriedades de Lista
list-style-type
list-style-position
list-style-image
list-style: none


### Cores


> Hex
Hexadecimal =  16 números que vão de A - F

ff = R
ff = g
ff = b

#ffffff =  RGB

> RGBa

> HSB


# BOX-MODEL

css

.container {
width:800px
heigth; 500px
margin: 0 auto;
} 


.box1 {
  width:200px
  heigth; 80px
  margin: 0 auto;
  background: #ccc;
  padding: 10px;
  border: 1px solid black;
}

float
clear
overflow

position
display


backgrounds
