# Resumo
> Nessa aula iremos ter uma visão geral á respeito de elementos em bloco, inline e folhas de estilos.

 *Uma página web* é diferente do tipo de página que você abre no seu processador de texto(word) 
 e começa a digitar. Páginas Web são projetadas apra algum tipo de tela de computador
 de mesa, um notebook ou mesmo um dispositivo móvel.

Você não está lidando com uma folha de papel de 21 po 29.7cm - está lidando com uma 
plataforma de visualização muito mais dinâmica. Por isso, primeiro pense na aparência 
que sua página terá em uma tela digital. 

**via Bill Sanders - Smashing HTML5**

### Layout

Vamos pensar na estrutura de uma página na web, que tal o [Youtube](www.youtube.com), como seria 
o wireframe para pensarmos na concepção do nosso HTML? 

![Wireframe Youtube](https://cdn.visual-paradigm.com/handbooks/agile-handbook/wireframe/01-youtube-wireframe-example.png)

Será que com o que vimos até, agora conseguimos estruturar uma página com base nesse wireframe?

Vamos, entender antes a respeito de elementos de estrutura para depois conceber nosso layout.

### DIV

A tag `<div>` é um elemento estrutural que não possui significado semântico. Ela serve para que possamos
estruturar o conteúdo da nossa página web. Ela se trata de um elemento de **bloco**.

```

<h1>Meus Pedidos</h1>
<div>
  <img src="..." alt="..." title="...">
</div>

<div>
 <h3>Hot Dog</h3>
  <p>...</p>
</div>

```


### SPAN

A tag `<span>` é um elemento estrutural que não possui significado semântico. Ela serve para que possamos
estilizar o conteúdo da nossa página web. Ele se trata de um elemento **inline**.

```

<h1>Meus Pedidos</h1>
<div>
  <img src="..." alt="..." title="...">
</div>

<div>
 <h3>Hot Dog</h3>
  <p> Cachorro com <span>picles</span> </p>
</div>

```

## Semântica:

Existem alguns elementos de texto que não pretendem afetar a estrutura de suas páginas da Web, mas adicionam informações extras às páginas - eles são conhecidos como marcação semântica.


### Article e Section

A tag `<article> e <section>`, se trata de elementos estruturais que possui significado semântico. Ela serve para que possamos
estruturar a nossa página. Ele se trata de um elemento **block**.

```
<article>
  <h1>Meus Pedidos</h1>
  <img src="..." alt="..." title="...">
</article>


<article>
 <h3>Hot Dog</h3>
 <p> Cachorro com <span>picles</span> </p>
</article>

```

### Header e Footer

A tag `<article> e <section>`, se trata de elementos estruturais que possui significado semântico. Ela serve para que possamos
estruturar a nossa página. Ele se trata de um elemento **block**.

```
<article>
  <h1>Meus Pedidos</h1>
  <img src="..." alt="..." title="...">
</article>


<article>
 <h3>Hot Dog</h3>
 <p> Cachorro com <span>picles</span> </p>
</article>

```

### Nav

A tag `<nav>`, se trata de elementos estruturais que possui significado semântico. Ela serve para que possamos
estruturar a nossa página. Ele se trata de um elemento **block**.

```
<article>
  <h1>Meus Pedidos</h1>
  <img src="..." alt="..." title="...">
</article>


<article>
 <h3>Hot Dog</h3>
 <p> Cachorro com <span>picles</span> </p>
</article>

```