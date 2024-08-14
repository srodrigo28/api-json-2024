### Api Json-Server para nossos projetos
    * npm init -y
    * npm i json-server
    * npm i nodemon

#### rodando no terminal
    * npx json-server data.json
    * npx nodemon data.json

#### config package.json
"scripts": {
    "test": "echo \"Error: no test specified\" && exit 1",
    "api": "npx json-server data.json",
    "api1": "npx nodemon data.json"
},

#### rodar o projeto
    * npm run api
    * npm run api1

#### Nossas rotas Endpoints implementar
* Get
* Delete
* Post
* Put