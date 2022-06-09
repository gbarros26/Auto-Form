# Auto Form
 
### Formulario que gera médias e relatórios sobre empresas de acordo com suas respostas. 

> Status: Em desenvolvimento



# Funcionalidade 

 Formulários de pesquisas para empresas com o intuito de identificar o grau de maturidade tecnológica de uma startup, esses formulários possuem dimensões e atributos, de forma exemplificada, as dimensões possuem atributos, cada atributo possui perguntas, e essas perguntas possuem uma nota que é computada no momento que o usuário responde o questionário, ou seja, os atributos possuem notas que ao serem respondidos por completo, geram uma média da dimensão, após a geração das notas/médias é criado um relatório com as informações mais relevantes da empresa, que foram determinadas de acordo com cada resposta dada. 

 

# Desenvolvedores 

+ Alexsandra Beatriz 
+ Breno Correia 
+ Everson Felipe 
+ João Guilherme 
+ Luan Henrique 
+ Marcelle Mascarenhas 
+ Paulo Vinicíus 
 

 

# Tecnologias utilizadas

> Front-end 

<table> 
 <tr>
  <td>Java-script 
    <td>React 
      <td>Node.js 
        <td>CSS 
  
  </table>


 

> Back-end 

 <table>
  <tr>
   <td>Python
    <td>PostgreSQL
     <td>Flask

 </table>
 
 
 
 
#### O CRUD foi implementado

⚠️ Funcionalides em desenvolvimento:
- Dashboard 
- Login(com autenticação)

 

# Como foi feito

> Front-end: 

 Criado através da Biblioteca React.JS, que é baseado no padrão SPA (Single Page Application), foram criados componentes para tornar o código mais limpo e facilitar a conexão com o banco de dados. 

> Back-end: 

 API criada em Phyton e Flask no padrão MVC, o POSTGRESQL foi o sistema gerenciador de banco de dados escolhido para armazenar os dados relacionados às perguntas, respostas, atributos, dimensões e notas da nossa aplicação. 

 # Instalação e configuração
  
  1. Instale o Node.js
  > https://nodejs.org/en/
  
  5. Clone o repositorio do git
  > git clone https://github.com/gbarros26/AutoForm
  
  2. Abra o terminal de comando 
  > Windows + R e digite cmd
  
  4. Acesse a sua pasta 
  > cd nome-da-pasta
  
   3. Instale as dependencias do react
  > npm i
  
  6. Execute a aplicação
  > npm start
