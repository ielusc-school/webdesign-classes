
## Flex-Items

Basicamente temos como propriedade a order da qual podemos definir qual a ordem o item 
deve ser apresentado.


> Propriedade: 

```css
.container {
  display: flex;
}

.container .item:nth-child(2) {
  order: 0 | 1 | -1 ;
  background: #fff;
  color:#000;
  font-weight: bold;
}

```

## Align-Self

Similar ao `align-items` para que possamos trabalhar com ele na cross-axios(eixo y) porém focando no nosso item.


> Propriedade: 

```css
.container {
  display: flex;
}

.container .item:nth-child(2) {
  align-self: flex-start | flex-end center, stretch, baseline ;
  background: #fff;
  color:#000;
  font-weight: bold;
}
```



## Flex-grow

Similar ao `align-items` para que possamos trabalhar com ele na cross-axios(eixo y) porém focando no nosso item.


> Propriedade: 

```css
.container {
  display: flex;
}

.container .item:nth-child(2) {
  align-self: flex-start | flex-end center, stretch, baseline ;
  background: #fff;
  color:#000;
  font-weight: bold;
}
```