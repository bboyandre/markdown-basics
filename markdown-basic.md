#Basicos de Markdown

Markdown permite você escrever usando um formato de texto fácil de ler e escrever, que converte em HTML valido para visualização no GitHub.

##Escrita Basica

###Paragrafos

Paragrafos em Markdown são apenas uma ou mais linhas de texto consecutivo, seguido de uma ou mais linhas em branco.
Em 2 de Julho, uma nave-mãe Alienigena entrou na orbita da terra e implantando varias dezenas de espacias em forma de pires(Destruidor) a cada 15 milhas (24 KM) de largura.
Em 3 de Julho, os cavaleiros negros, um esuqdrão do corpo de fuzileiros navais F/4 - 18 Hornets participou de um assalto em um destroyer perto de Los Angeles.

###Cabeçalhos

Você pode criar um título, adicionando um ou mais símbolos # antes de seu texto de título. O número de # você usa irá determinar o tamanho do cabeçalho.

<code>#</code> O maior título (an <h1> tag)

<code>##</code> O segundo maior título (an <h2> tag)
…

<code>######</code> O sexto maior título (an <h6> tag)

###Citações

Você pode indicar sua citação com um >.

*Este texto será italico*
*Este texto será negrito*

Ambos negrito e itálico podem usar um * ou um _ em torno do texto para o estilo. Isso permite que você combinar os dois em negrito e itálico, se necessário.

** Todos _devem_ participar da reunião hoje às 5 horas. **

##Listas

###Listas não coordenadas

Você pode fazer uma lista desordenada precedendo itens da lista ou com um * ou um -.

* Item
* Item
* Item

- Item
- Item
- Item
 
###Listas Ordenadas

Você pode fazer uma lista ordenada precedendo itens da lista com um número.

1. Item 1
2. Item 2
3. Item 3

###Listas Aninhadas

Você pode criar listas aninhadas pelo recuo de itens da lista por dois espaços.

1. Item 1
 1. Um corolário do item acima.
 2. No entanto, outro ponto a considerar.
2. O Item 2
 * Um corolário que não precisam ser solicitados.
   * Esta é recuado quatro espaços, porque é dois espaços mais longe do que o item acima.
   * Você pode querer considerar fazer uma nova lista.
3. O Item 3

##Formatação do Código

###Formatos em Linha

Use acentos graves (`) para formatar o texto em um formato especial monospace. Tudo dentro dos acentos graves aparecem como está, sem nenhuma outra formatação especial.
Aqui está uma idéia: por que não vamos tomar `SuperiorProject` e transformá-lo em`**Reasonable**Project`.

###Várias Linhas

Você pode usar acentos graves triplos (`` `) para formatar o texto como seu próprio bloco distinto.
Confira este programa limpo que eu escrevi:

`` `
x = 0
x = 2 + 2
o que é x
`` `

##Ligações

Você pode criar uma ligação em linha por envolvimento de texto ligação entre colchetes ([]), e, em seguida, envolver a ligação entre parênteses (()).

Por exemplo, para criar um hiperlink para www.github.com, com um texto de ligação que diz, Visite GitHub !, você escreveria isso em Markdown: [Visite GitHub!] (Www.github.com).
