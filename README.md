# Doe Vida

Este site visa a conscientização sobre o tema doação de sangue.


Link do site: https://pifatecfranca.github.io/doevida/
## 🚀 Começando

Temos 5 páginas.
A primeira página chama-se "Quem somos", nesta página de forma intrudutório o tema sobre doação de sangue é 
apresentado visando demonstrar o impacto que uma ação tão simples acarretar na vida de muitas pessoas. Nesta página também 
é possível acessar o botão "Estoque" onde se tem acesso ao estoque do Hemocentro de Franca-sp atualizado diariamente.

A segunda página "Quem pode doar" traz os requisitos preliminares para que se realize uma doação de sangue segura.

A terceira página "contatos" traz as formas de entrar em contato com o Hemocentro de Franca-sp tais como whatsapp, assistente virtual e e-mail.

A quarta página traz um vídeo que trata de 5 mitos sobre a doação de sangue a fim de desmistificar a doação de sangue.

A quinta página traz um cadastro que a princípio é apenas o front-end, mas a ideia é criar um banco de dados com pessoas que tiverem interesse em 
realizar um pré cadastro para que o Hemocentro da cidade mais próxima entre em contato para realizar um agendamento.


### 📋 Prototipação 


O usuário precisa apenas possuir um dispositivo com acesso à internet.


## 🛠️ Construído com

Ferramentas usadas na criação:

Para a construição deste site foi usada a IDE VSCODE sob influência de HTML e CSS.

## 📌 Versão

Última versão data: 25/09/2023





##                      Explicação da Estrutura em HTML
● !DOCTYPE html - Usada para dizer ao navegador em qual versão html a página
é escrita..<br>
● html -Representa o tipo do meu documento.<br>
● tittle - Aqui é o título da página, nome que aparece na aba do navegador..<br>
● head - Aqui ficam as informações gerais do documento.<br>
● link - Aqui essa tag é para fazer o link entre a página html e a página do CSS,
acompanhada do atributo href e seu valor de atributo que no caso é o endereço da
página CSS.<br>
● meta - Foram inseridas informações de compatibilidade em relação ao tamanho
da imagem.<br>
● body- Aqui são as informações do corpo do site.<br>
● div -criei uma div aqui para construir os ícones da esquerda e da direita da
parte superior do site, vinculando cada um respectivamente em suas classes, para
depois aplicar o CSS definindo seus parâmetros de forma que as alterações sejam
feitas em todos que estiverem dentro das classes.<br>
● a - Dentro dessa Div estão os ícones clicáveis que foram inseridos com tag a
de ancoragem, acompanhada do atributo href representando o endereço das
informações que serão buscadas ao clicar em algum icone.<br>
● img Ainda dentro de body, criei uma tag img para inserir as imagens.
section Criei 2 para agrupar algumas div`s dentro de section e as sim
separar por blocos as imagens e seus textos.<br>

  



##                 Explicação da Estrutura em CSS
body{ Aqui o body está sendo utilizado de modo que todo o
corpo do site será alterado.<br>
margin:0; Esse seletor de margem com valor zero é para fazer a
imagem cobrir toda a tela, sem que alguma predefinição de margem
atrapalhe.<br>padding: 0; Esse seletor serve para definir a distância de um
elemento e sua borda.Deixei zerado também para a imagem preencher toda
a tela<br>
background-color:black; Este elemento define a cor do fundo, no
caso do corpo do site.<br>
}<br>
BotãoEsquerdo{-Classe que define todas as alterações realizadas nos
ícones clicáveis da esquerda<br>
color: red; - Define Cor do ìcone.<br>
background-color: rgb(5, 5, 5); - Define Cor do Fundo do Ícone.<br>
border-radius: 5px; - Altera a borda deixando mais reta ou
arredondada.<br>
padding:5px 15px; -Define a altura e largura do ícone<br>
font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande',
'Lucida Sans Unicode', Geneva, Verdana, sans-serif; - Define o tipo da
fonte do ícone.<br>
font-size: 30px; Define Tamanho do ìcone.<br>
text-decoration: none; - Faz a retirada da linha que sublinha o
ícone, com o valor do seletor NONE.<br>
}<br>
.BotãoDireito{Classe que define todas as alterações realizadas nos
ícones clicáveis da Direita<br>
color:rgb(143, 0, 172); - Define Cor do ìcone.<br>
padding-left: 200px; - Posiciona os ìcones mais à direita<br>
font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande',
'Lucida Sans Unicode', Geneva, Verdana, sans-serif; - Define o tipo da
fonte do ícone.<br>
font-size: 30px; Define Tamanho do ìcone.<br>
text-decoration: none; - Faz a retirada da linha que sublinha o
ícone, com o valor do seletor NONE.}<br>
.corpo{ classe corpo para definir o tamanho da minha <section> , onde
vou acomodar minhas<b div<br>
width: 960px; - Define a largura, no caso o valor é 960 pixels.<br>
margin: auto; - Define a margem, no caso o valor é auto.<br>
}<br>
.texto2{Classe para definir as alterações dos parágrafos da imagem Rede
de Apoio.<br>
color: aliceblue; - Define a Cor do Texto2.<br>
display: table; - Define qua div não tem uma posição livre, ela
está em modo tabela, respeitando altura e largura.<br>
float: left; - Deixa a imagem em modo flutuante à esquerda do Site
width: 300px; - Define a largura da imagem.<br>
margin-left: 50px; - Define a distância da margem do texto2. No
caso a margem esquerda.<br>
text-align:justify; - Define a orientação do meu texto2.<br>
font-size: 20px; - Define Tamanho das letras do texto2.<br>
font-family:Impact, Haettenschweiler, 'Arial Narrow Bold',
sans-serif ; Define o tipo da fonte do texto2.<br>
}<br>
.conteudo2{<br>
display: table; - Define qua div não tem uma posição livre, ela
está em modo tabela, respeitando altura e largura
}<br>
.imagem2{<br>
display: table-cell; - Define a posição<br>
float: left; - Define a imagem flutuante à esquerda do site.<br>
width: 600px; - Define a largura da imagem em pixels, no caso<br>
600px.height: 500px; - Define a Altura da imagem em pixels, no caso
500px.<br>
}<br>
SEGUNDA PÁGINA DO SITE<br>
.whats{ Classe para definir todas as mudanças do botão de denúncia pelo
whats app.<br>
width: 420px; - Define a largura do botão.<br>
height:150px; - define a altura do botão.<br>
display:block; - Deixa o botão bloqueado em uma posição independens
de quantas camadas o site tenha.<br>
margin-right: auto; - Define a distância da margem direita.<br>
margin-left: auto; - Define a distância da margem esquerda.<br>
color: rgb(207, 5, 5); - Define a cor da fonte.<br>
background-color: bisque; - Define a cor do fundo do botão.<br>
font-family:fantasy; - Define o Tipo de fonte do Botão.<br>
font-size: 30px; Tamanho da fonte do Botão.<br>
text-decoration:double;<br>
}<br>
.Sigilo{ Classe criada para as alterações da frase “O sigilo é
absoluto”, da segunda página<br>
color:white; - Define cor da fonte.<br>
display: flex; - Posição livre.<br>
justify-content: center; - Define a orientação da frase.<br>
font-size: 60px; - Define o tamanho da fonte da frase.<br>
margin: 50px; - Define a margem à direita.<br>
width: -20px; - Define a largura da frase.<br>
height: 10p<br>






## 📄 Licença



Este projeto está sob a licença (sua licença) - veja o arquivo [LICENSE.md](https://github.com/Wilton-Monteiro/site/blob/main/LICENSE) para detalhes.

## 🎁 Expressões de gratidão

Agradeço a FATEC, Faculdade de Tecnologia de Franca , e ao seu quadro de  colaboradores, 
por proporcionar ensino de qualidade, buscando o desenvolvimento da educação. 


---
⌨️ Wilton Monteiro 😊
