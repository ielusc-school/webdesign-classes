# Caminho Relativo / Caminho Absoluto

`..` > sai de um diretório


### Imagens

*HTML*
Formato aceito: JPG, GIF, PNG e SVG.

Propriedades, tag `<img>`

```
<img src="path"
  alt="aqui é sua imagem"
  title="imagem bacana"
  width="300"
  heigth="200"
  align="left || right">
```
Propriedades, tag `<picture>`
```
<picture>
    <source srcset="path" media="(min-width: 600px;)">
    <source srcset="path" media="(min-width: 400px;)">
    <source srcset="path" media="(min-width: 200px;)">
</picture>
```


*CSS*

background-image
background-color:
background-repeat:
background-position:
background0-size:


### Video

Referencia: https://www.w3schools.com/html/html5_video.asp

*HTML*
Formato aceito: .

Propriedades, tag `<video>`
`https://coverr.co/videos/mountain-lake-SzbwQXG2Vc`

````
<video width="800" heigth="450" controls autoplay controlsList="nodownload">
  <source src="path" type="video/mp4">
  Seu browser nào suporta a tag e vbideo.

</video>

# Seletores

* - todos elementos
.class
#id
[atrib]
:pseudo-class
::pseudo-elementos


Combinar Seletores

div + p  => adjacent sibling
div ~ p => general sibling 
div > p  => child
div p => descendente
div, p, h1



## Overflow



