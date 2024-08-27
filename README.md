Fundação CECIERJ - Vice Presidência de Educação Superior a Distância
Curso de Tecnologia em Sistemas de Computação
Disciplina Construção de Páginas WEB
AD1 2° semestre de 2024.
Observações importantes:
1. Esta avaliação consiste no desenvolvimento do site de uma academia de
musculação e natação. As imagens utilizadas nas páginas de exemplo estarão
disponíveis para download na plataforma como arquivos auxiliares. À
exceção dos logos, você pode substituir essas imagens, desde que respeite o
layout estabelecido em cada questão.
2. A resolução do monitor ou o tamanho da janela do navegador onde as
páginas serão exibidas não tem importância. Nas figuras ilustrativas das
questões, a janela do navegador foi dimensionada para exibir um efeito
visual que sua página deve reproduzir, quando dimensionada de forma
semelhante.
3. Os trabalhos devem ser feitos utilizando editores simples, que não incluam
código no texto. Utilize preferencialmente o Notepad (Windows) ou o Gedit
(Linux). Outros editores, com esta característica, podem ser utilizados como
Notepad++ e PsPad (Windows); Kate e Kwrite (Linux); Coda e TextMate
(Mac); ou Gedit, Geany, Atom e Visual Studio Code (Multiplataforma).
4. ATENÇÃO: A avaliação é individual. Caso existam duas ou mais
implementações excessivamente coincidentes, independente de qualquer
motivo, todas as avaliações envolvidas receberão nota ZERO!
5. Não serão aceitos trabalhos em papel. O aluno deve postar na atividade
determinada na plataforma. É imprescindível que o tutor receba todos os
arquivos que compõem o site. A entrega destes arquivos deve ser feita através
DA PLATAFORMA na forma de um arquivo de extensão zip. Os arquivos
HTML, JS ou CSS devem estar individualizados (mesmo que agrupados num
ZIP) para que o tutor possa testar seu site. Não serão aceitos trabalhos em
arquivos de texto DOC ou PDF.
6. Fazer as ADs é muito importante, não apenas pela nota, mas principalmente
pela experiência que permitirá um melhor desempenho nas avaliações
presenciais. Os assuntos abordados na AD podem cair na prova presencial
mesmo não tendo sido abordados nos vídeos ou no material escrito.
PÁGINA COM LAYOUT BASEADO EM TABELA
1. Escreva o código necessário para criar a página mostrada na figura 1. O
posicionamento dos elementos na página deve ser feito utilizando uma tabela de bordas
invisíveis. Devem ser utilizadas as fontes “Verdana” e “Ubuntu” (principal, alternativa)
para o menu e o endereço e as fontes “Lucida Bright” e “Liberation” para o texto
principal. As referências do menu apontam respectivamente para as páginas:
HalteresSeusHabitos.html, Planos.html, Equipamentos.html e Inscricao.html. Os links do
menu estão numa lista NÃO numerada, com cada item indicado por um quadrado
(square). A seleção de um link deve causar a abertura da página correspondente em uma
nova janela do navegador (ou novo tab). Use uma tag <address> para as informações de
localização (endereço, telefone e e-mail). No canto superior esquerdo aparece uma
imagem (arquivo HalteresSeusHabitosTopo.png), com uma linha contínua abaixo dela
(criada pela tag HR com tamanho 320 px). Junto com o texto de apresentação aparece a
imagem HalteresSeusHabitosLogo.png centralizada. As cores utilizadas foram: Fundo -
#DDCC55, Texto - #000000, Link - #222222 e Link Visitado - #222222. [1 ponto]
Figura 1 – Página do Site da Academia Halteres Seus Hábitos
PÁGINA COM CSS E ESTRUTURA HTML5
Leia o texto “Caminho até o HTML5” disponibilizado na seção “textos” da primeira
semana para que você possa implementar uma nova versão de sua página inicial e todas
as demais páginas do trabalho. É recomendável também que você tenha lido o material
“Folhas de Estilo”.
2. Faça uma nova implementação da página inicial da loja, desta vez utilizando as tags de
estrutura do HTML5 (figura 2). A aparência deve ser definida por estilos armazenados
em um arquivo de extensão css (não devem ser usadas na página atributos e tags
obsoletas). Para esta página foram criadas três classes de estilo: ender, imgLogo e apres.
Além disso, as tags <body>, <header>, <nav>, <section>, <ul> e <a> tiveram sua
aparência modificada. Os textos da página devem utilizar as fontes “karla”, “verdana” e
“ubuntu” (principal, alternativa, alternativa) para o endereço e o menu, e as fontes
“stoke”, “Lucida Bright” e “liberation” (principal, alternativa, alternativa) para o texto
principal. No quadro 1 são mostrados os estilos das tags de estrutura para produzir o
posicionamento mostrado na figura. A descrição dos estilos que devem ser aplicados às
outras classes e tags está no quadro 2. [2 pontos]
Figura 2 - Página do site na nova implementação
DICA: A página precisa utilizar as tags header, nav e section (não necessariamente
nesta ordem).
DICA: As fontes “Karla” e “Stoke” são disponibilizadas pelo Google. Consulte a página
https://www.w3schools.com/csS/css_font_google.asp para saber como usá-los.
DICA: A tag <hr> foi substituída pela definição da borda.
header { display: block; margin-bottom: 1px; }
nav { display: block; width: 20%; float: left; }
section { display: block; width: 70%; float: right; }
Quadro 1 – Estilo das divisões padrão da página
<body> Cor de fundo #DDCC55, cor de texto #000000, tamanho de fonte de
16px e fontes stoke, Lucida Bright, liberation.
<a> Sem sublinhado, cor de link #222222 e link visitado #222222.
<ol> e <ul> Espaçamento entre as linhas (line-height) de 200%
ender Informações de localização (endereço, telefone e e-mail). Elemento
colado na direita da janela (float com valor right), texto alinhado à
direita, espaçamento entre as linhas (line-height) de 140%, tamanho
de fonte 14px e fontes Karla, Verdana, Ubuntu.
imgLogo Logo do topo esquerdo da página. Borda inferior solida, com 3px e na
cor #222222, margem inferior de 6px e espaçamento do conteúdo
com a borda inferior da célula (padding-bottom) de 15px.
apres Texto e imagem de apresentação da página. Alinhamento de texto
centralizado (center) e tamanho do fonte de 16px.
ESTILOS DENTRO DE <nav>
<ul> Cor de texto #000000, espaçamento entre as linhas (line-height) de
230%, margem superior de 40px e marca de início de item (list-styletype) como quadrado (square).
Quadro 2 – Classes de Estilo da Página
VÁRIOS TIPOS DE LISTA
3. A imagem ao lado mostra a página que será aberta
quando o link “Planos” for selecionado na página da
segunda questão. Esta e as próximas páginas utilizam os
mesmos estilos da questão anterior, com alguns acréscimos.
A descrição destes acréscimos está no quadro 3 e eles devem
ser adicionados ao arquivo CSS usado na questão anterior.
Apenas o interior da tag section (figura 3) foi modificado em relação à página da segunda
questão (header e nav permanecem como mostrado na figura 2). [2 pontos]
Figura 3 – Interior do Section da Página do Link Planos
titulo Texto com alinhamento centralizado
listaPlano Largura de 300px, cor de texto #202020, cor de fundo #EEEEBB,
tamanho do fonte de 12px, padding (espaçamento entre o interior e a
borda) variável (10px 10px 10px 30px) e borda de 3px, sólida e na cor
#202020. Margem superior de 0px e inferior de 10px. Lista
centralizada na página (DICA: margem esquerda e direita com valor
auto). Lista não numerada com itens indicados por um quadrado.
<h4> Texto da Matrícula. Tamanho do fonte de 14px.
ESTILOS DENTRO DE listaPlano
<ol> Cor de texto #202020 e lista numerada com letras minúsculas (loweralpha).
preco Cor de texto #CC0000.
Quadro 3 - Classes de Estilo da lista de Planos
TABELA COMUM COM JUNÇÃO DE CÉLULAS
4. A figura 4 mostra o interior da section da página que
será aberta (imagem ao lado) quando o link
“Equipamentos” for selecionado na página da segunda
questão. Esta página utiliza os mesmo estilos da questão
anterior, com os acréscimos de algumas novas classes. A
apresentação dos equipamentos é feita através de uma
tabela com bordas definida com o estilo tabEquip. A tabela têm as tags <td>, <th> e
<img> modificadas conforme o contexto. Foram também definidas as classes tabTitulo
(utilizada na primeira linha), tabSubTit (utilizada como título da descrição dos
equipamentos) e imgCel (células onde aparece a imagem do equipamento). Apenas o
interior da tag section foi modificado em relação à página da segunda questão (header e
nav permanecem como mostrado nas figuras das questões 2 e 3). A descrição dos novos
estilos necessários está no quadro 4 e eles devem ser adicionados ao arquivo CSS usado
na questão anterior. [2,5 pontos]
Figura 4 – Interior do Section da página do Link Equipamentos
tabEquip Borda sólida de 1px com espaçamento interno (DICA: bordercollapse com valor separate), largura de 510px, margem inferior de
10px e tamanho do fonte de 14px.
tabTitulo Tag <th> com cor de fundo #402020 e cor de texto #FFFFFF.
tabSubTit Tag <th> com cor de fundo #802020 e cor de texto #FFFFFF.
ESTILOS DENTRO DE tabEquip
<th> Borda sólida de 1px. Padding (espaçamento do conteúdo com a borda
da célula) de 10px.
<td> Borda sólida de 1px. Padding de 10px, tamanho de fonte de 12px e
cor de fundo #EEEEBB.
imgCel Largura de 100px e cor de fundo #FFFFFF.
ESTILOS DENTRO DE imgCel
<img> Largura e altura da imagem de 100px.
Quadro 4 - Classes de Estilo da Página Equipamentos
DICA: Tabela em três colunas.
DICA: Após a descrição de cada equipamento há um link (endereços no quadro 5) para
a fonte da informação da descrição (“[fonte]”). Se o usuário selecionar esse link,
a página deverá ser aberta num novo tab do navegador.
FONTE DE CADEIRA EXTENSORA
https://treinomestre.com.br/cadeira-extensora-comopotencializar-os-resultados-4-dicas-importantes/
FONTE DE SUPINO VERTICAL
https://www.academiacentralfitness.com.br/post/supinom%C3%A1quina-como-fazer-benef%C3%ADcios-e-varia%C3%A7%C3%B5es
FONTE DE REMADA BAIXA DE TRIÂNGULO
https://www.hipertrofia.org/blog/2018/03/24/remada-baixa/
Quadro 5 – Endereço das fontes dos textos
FORMULÁRIO COM NOVOS ELEMENTOS
O site termina com uma página de formulário. Para cria-la, devemos utilizar os elementos
<fieldset> e <legend> para organizar os seus campos logicamente e para compor o seu
visual. Não devemos esquecer também os elementos <label> para ligar os textos de
identificação com os campos do formulário.
O posicionamento dos campos do formulário sempre foi uma tarefa complicada.
Antigamente, utilizavam-se tabelas sem bordas para fazer este posicionamento e definir o
layout. A tendência hoje em dia é evitar o uso de tabelas para posicionamento e utilizar
CSS para este fim.
Nos nossos formulários devemos também utilizar, sempre que possível, os novos
elementos presentes no HTML5, mesmo que nem todos os navegadores estejam
atualmente preparados para aproveitar todo o potencial destes elementos. Está
disponibilizado na seção “textos” da quinta semana (Formulários) material para que você
possa implementar seus formulários com as novidades do HTML5.
DICA IMPORTANTE: Não esqueça que o atributo nome deve estar definido em todos
os elementos do formulário.
5. A imagem ao lado mostra a página que será aberta quando
o link “Inscrição” for selecionado na página da segunda
questão. A página utiliza as mesmas cores e estilos definidos
para as páginas das questões anteriores e alguns novos estilos
descritos no quadro 6. Utilizando tags como <form>,
<label>, <select>, <option>, <fieldset>,
<legend> e <input>, faça o formulário de modo que o
posicionamento de seus elementos seja como o mostrado na figura 5.
Figura 5 – Interior da tag section da página do Link Pedidos
A figura 6 mostra o conteúdo das duas listas de seleção de atividades e de planos.
Figura 6 – Listas de seleção de atividades e de planos
Como nas questões anteriores, apenas o interior da tag section foi modificado em relação
à página da segunda questão. Utilize os estilos descritos no quadro 6 e os adicione ao
arquivo CSS usado na questão anterior. [2,5 pontos]
formul Largura de 400px, padding do topo e do fundo de 20px, margem
superior de 0px, margem inferior de 10px, elemento centralizado na
página (DICA: margem esquerda e direita com valor auto), cor de
texto #202020, cor de fundo #EEEEBB, borda sólida de 3px na cor
#202020, tamanho de fonte de 12px.
POSICIONAMENTO E TAMANHO DE FIELDSETS
fsPessoal Fieldset dos dados pessoais. Largura 340px, margem esquerda e
direita com valor auto.
fsGenero Fieldset da seleção de gênero. Preso ao lado direito do formulário
(float com valor right). Margem do topo e da direita de 10px.
fsCartao Fieldset dos dados de cartão de crédito. Largura 280px, margem
esquerda e direita com valor auto.
POSICIONAMENTO E TAMANHO DE BOXES INTERNAS DOS FILEDSETS
linhaNome Altura de 30px, largura de 340px e padding do topo de 8px.
linhaDados Altura de 130px, largura de 340px.
ColDirMat Preso ao lado direito do formulário (float com valor right).
ColEsqPes Largura de 70px. Preso ao lado esquerdo do formulário (float com
valor left). Elemento de bloco (display com valor block).
ColLabCrd Largura de 270px, altura de 30px e texto alinhado à esquerda. Preso
ao lado esquerdo do formulário (float com valor left). 
ColValTot Largura de 220px e texto alinhado à esquerda. Preso ao lado
esquerdo do formulário (float com valor left). Elemento de bloco
(display com valor block).
entDireita Botões de envio e limpeza. Margem direita de 20px. Preso ao lado
direito do formulário (float com valor right).
TAMANHO DE ELEMENTOS DE ENTRADA DE VALORES
inpNome Input de nome. Largura de 220px
numDD Input numérico de dois dígitos com largura de 35px.
numQD Input numérico de quatro dígitos com largura de 50px.
inpNCC Input de número do cartão de crédito. Largura de 130px
inpTelef Input do número de telefone. Largura de 90px
inpMat Input do número da matrícula. Largura de 70px
inpVal Input para mostrar o valor da inscrição. Largura de 50px
Quadro 6 - Classes que podem ser usadas nos formulários
OBS FINAL: Todas as imagens utilizadas na avaliação foram capturadas no Firefox no
sistema operacional Linux, com exceção da figura 7 capturada no Chrome do Windows.