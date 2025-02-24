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

## SISTEMA DE CORES
1. `nome da cor` => Especifica o valor da cor através do nome dela e inglês.
2. `hexadecimal` => Especifica o valor da cor através de uma sequência alfa-numpérica.
3. `rgb` => Especifica a cor através da intensidade do red [vermelho], green[verde] e blue[azul].
4. `rgba` => São os mesmos valores do rgb, porém com o valor do alpha[opacidade].

# AULA 04
1. <img> => Tag responsável por inserir uma imagem interna ou externa.
- src -> É onde é inserido o caminho da imagem;
- alt -> é o texto alternativo que será exibido caso a imagem "quebre" e por questões de acessibilidade.
Ex:<img src="caminho_da_imagem" alt="Descrição da imagem">

2. Listas 
`<ul></ul>` -> Informa que existirá itens e a posição desses itens não importa. `--Lista não ordenada.--`
`<ol></ol>` -> Informa que existirá itens e a posição desses itens importa. `--Lista ordenada--`
`<li></li> `-> É cada item da lista.

3. Tag de Link
<a></a> -> É utilizada para gerar um texto clicável. --Link--
- href -> É uma propriedade onde você irá informar qual o caminho que o link irá enviar o usuário.
Ex: <a href="caminho_do_link">Sobre</a>

## CSS
1. font-family: Arial, Helvetica, sans-serif; -> Propriedade que altera o tipo de fonte utilizado no elemento.
2. `padding` -> É o espaçamento interno de um conteúdo até a borda.
3. `margin` -> É o espaçamento externo do elemento em relação a outro elemento
4. `border` -> 

# AULA 05

1. POSICIONAMENTO (GRID)
`GRID` -> É uma das tecnologias mais utilizadas no sistemas web e sites. A lógica utilizada é separar a tela em
colunas e linhas que podem ser diferentes tamanhos.

2. UTILIZANDO O GRID
Utilizamos a propriedade display com o valor de grid.
Ex: display: grid;

3. PRINCIPAIS PROPRIEDADES DO GRID
`grid-template-columns:` -> Propriedade utilizada para informar ao css quantas colunas e quais os tamanhos você irá usar.
`grid-template-rows:` -> Propriedade utilizada para informar quantas linhas serão geradas e o tamanho delas.
* Métricas utilizadas
- %, e px -> Evitar
- fr -> Fração referente a página toda.
- auto -> Tamanho de forma automática.

- `grid-row:` -> Define em qual linha o elemento irá se posicionar.
- `grid-column:` -> Define em qual coluna o elemento irá se posicionar.
