# AULA 02
- Os elementos (marcações) do html são conhecidos como tags.
- As tags podem possuir somente abertura ou abertura/encerramento.

1. Principais tags
<h1></h1> até a <h6></h6> -> Títulos.
<p></p> -> Parágrafos.
<a></a> -> Tag de link.
<img> -> Tag responsável por apresentar uma imagem.
<strong></strong> -> Tag semântica, Indica uma força na palavra/frase.
<em></em> -> Tag semântica. Indica um ênfase na palavra/frase.
<b></b> -> Coloca uma frase/palavra em negrito.
<i></i> -> Coloca uma frase/palavra em itálico.
<br> -> Realiza uma quebra de linha.
<hr> -> Cria uma linha horizontal.
<div></div> -> Cria um bloco contendo outras tags.

2. Realizando a comunicação do CSS com o HTML
- `CSS Interno` -> Fica no arquivo html e é separado pela tag <style></style>
- `CSS Externo`-> É um arquivo separado ao arquivo do html. Possui a extensão .css e é a forma mais recomendada.
- `CSS Inline` -> É utilizado exatamente na tag no html. Deve ser usado com cautela.

3. Estilizações básicas no css
- `color:` -> Irá colocar uma cor no texto
- `background:` -> Irá colocar uma cor de preenchimento no fundo do elemento.
- `font-size:` -> Altera o tamanho da fonte

# AULA 03
## SELETORES NO CSS
=> É a forma como você irá chamar um determinado elemento do `html` no `css`.
1. tag => Basicamente, você chama a tag em si para realizar a estilização.
* Quando você chama diretamente a tag, cuidado pra não estilizar todos os elementos que possuem aquela tag.

2. #id -> Você cria um identificador único na tag do elemento [html] e chama esse identificador no css.

3. .class => Você cria um "apelido" na tag do elemento e ese "apelido" pode ser utilizado quantas vezes necessário,
inclusive em outras tags diferentes.