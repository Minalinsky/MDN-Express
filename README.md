# Sobre
Desenvolvido para a disciplina de Desenvolvimento Web por Alyson Matheus Maruyama Nascimento (8532269) e Lucas Augusto (10550198)
Essa é uma implementação de uma biblioteca utilizando Express e integrada ao MongoDB a partir do tutorial do MDN que pode ser encontrado em: https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/Introduction

## Heroku
Além da implementação local utilizando o tutorial como guia, o sistema de Biblioteca foi integrado ao Heroku, e a aplicação pode ser encontrada rodando na seguinte URL: https://polar-fortress-58446.herokuapp.com/catalog

**OBS: ** Para submeter alterações ao Heroku, realizamos um push no remote chamado *heroku* no git (git push heroku master). Para abrir o aplicatovo rodando no heroku no navegador, usamos heroku open
#### Comandos Heroku
	Comandos usados para configurar e otimizar o heroku (Não são necessários para rodar a aplicação)
	**heroku config:set NODE_ENV='production'** -> melhoria na performance e geração de menos erros verbose
	**heroku config:set MONGODB_URI='mongodb+srv://alyson:<minhaSenhaDoClusterMongo>@alysoncluster-u4usx.mongodb.net/test?retryWrites=true&w=majority'** -> Separa também a DB para "production"
	**heroku config** -> Se quisermos inspecionar como estão as configurações do heroku

## Rodando Servidor 
- Instalar dependências com *npm install*
- Utilizar comando SET DEBUG=express-locallibrary-tutorial:* & npm start
- Ao rodar localmente, acessar o sistema através do endereço http://127.0.0.1:3000/

