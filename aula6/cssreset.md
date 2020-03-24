# Sumário

- CSS Reset
- Box-Border
- Seletores



# Introdução ao Reset CSS

Um dos maiores problemas enfrentados pelos web designers e programadores web em geral é a forma como um mesmo código se comporta em browsers diferentes. Nem sempre é possível obter o mesmo resultado para a interface trabalhando com diferentes navegadores.

Isso muitas vezes faz com que seja necessário escrever vários arquivos CSS e utilizar “diretivas de compilação” para que o documento identifique qual browser está sendo utilizado e aplique uma formatação específica.

Há momentos também em que um elemento sem formatação alguma é exibido de formas distintas em browsers diferentes, o que ocorre devido à existência de uma formatação básica nativa para essas tags. Essa formatação é necessária para que, caso o usuário visualize a página sem nenhuma folha de estilos, seja possível obter o mínimo de organização a fim de que o documento seja ao menos “legível”.

Essa diferença “natural” entre a formatação aplicada pelos navegadores pode se tornar uma dor de cabeça para os designers, que geralmente precisam obter um padrão mesmo para os pontos da página que não necessitam de estilos “especiais”.

Para contornar esse problema, foi desenvolvida uma técnica chamada “Reset CSS”, que consiste em sobrepor a esse padrão uma folha de estilos básica para remover toda formatação “original” aplicada pelo browser.



