# projeto-node

### Iniciar um projeto node no gitHub
Criar um repositório (private ou public) Escolher a tecnologia (.gitignore), caso disponível Escolher a opção README.md

### Clonar o projeto para o computador local

Escolher a pasta correspondente aos seus projetos Escolher um editor eficiente (VsCode, Atom, SublimeText, NetBeans, WebStorm ...)

Tendo acesso ao prompt de comando

-> git clone "endereço do projeto no git hub" 

Exemplo:

 git clone https://github.com/vitorialinda00/projeto-node.git
 

### Iniciar o arquivo de configuração package.json
-> npm init -y

### Instalação de dependencias
npm install "NOME DA TECNOLOGIA"

Exemplo: -> npm install express

Sempre pesquisar a tecnologia no site que contém a documentação oficial exemplo (npm, yarn ) Exemplo: -> npm install express -> yarn add express

Obs: A pasta node_modules contém todas as tecnologias (dependencias) de terceiros

### Desinstalando uma dependencia
Não excluir qualquer pasta dentro de node_modules

-> npm uninstall express (por exemplo)

### Executando o servidor
node "NOME DO ARQUIVO" Exemplo: node app

### Instalação como devdependencies
( São tecnologia utilizadas apenas durante o desenvolvimento do projeto em específico )
npm install nodemon -D   (por exemplo)

### Iniciando tecnologia ou scripts utilizando atalhos 
No´package.json

"scripts": {
  "morango": "nodemon server.js"
  }
  
  No prompt vc executa:
  npm run moprango 
