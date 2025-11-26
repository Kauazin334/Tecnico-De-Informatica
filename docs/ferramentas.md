# HTML : Quais elementos estao sendo usados?
R= <h1> pro titulo
   <nav> para o menu
   <div> para o container
   <footer> para fazer o rodape
   <h3> explicaçao
   <h1 style> para mudar a cor das letras
   <head> para fazer o cabeçalho

   # CSS : Quais propriedades estao sendo usadas?
 #intel / #pichau

border-radius: 30px;

.container

background-color: #000000;

border-radius: 24px;

margin: 48px auto;

padding: 24px;

width: 800px;

box-sizing: border-box;

body

background-image: url

#titulo

text-align: center;

.navbar

height: 50px;

overflow: hidden;

background-color: black;

border-radius: 30px;

width: 50%;

.navbar a

float: left;

display: block;

color: rgb(255, 255, 255);

text-align: center;

padding: 14px 16px;

text-decoration: none;

.navbar a:hover

background-color: rgb(0, 0, 0);

color: rgb(95, 219, 223);

.formulario-campo

display: flex;

flex: 1;

gap: 16px;

width: 70%;

justify-content: space-around;

.formulario-campo label

font-family: "inter", sans-serif;

font-weight: 400;

.formulario-campo input, select, textarea

width: 300px;

justify-self: flex-end;

margin-bottom: 8px;

align-items: center;

# JS: há algum recurso javascript?
1.try { ... } catch { ... }

Estrutura usada para capturar erros caso algo dê errado.

try → tenta executar o código

catch → pega qualquer erro e evita que a página quebre  

document.querySelector()

Serve para selecionar elementos HTML.

Eventos (Event Listener)
Isso quer dizer que quando o botão for clicado, a função validarFormulario será executada.


event.preventDefault()

Evita que o formulário seja enviado automaticamente.
Isso é necessário para você validar antes de enviar.

Validação de dados

Você verifica se:

O nome não está vazio
A mensagem não está vazia
A mensagem tem menos de 500 caracteres

Exibição de alertas

Você usa alert() para avisar o usuário quando algo está errado.

Envio manual do formulário