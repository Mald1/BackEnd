# Backend
Trabalho sobre aplicações Backend

#Inicializando um Servidor Back-End com Node.js/Express.js

# 1- Preparando o ambiente
Primeiramente você deve ter o node.js/npm instalado em sua máquina. Com eles, você conseguirá executar o js direto na maquina e poderá baixar a biblioteca de gerenciamento de servidores locais "express".

# 2- Inicializando o projeto
Em uma pasta, crie o setup padrão do node com o comando "npm init -y", depois disso baixe o express para o seu projeto com o comando "npm i express", e crie sua pasta index.js/server.js

# 3- Inicializando o Express
Dentro da sua pasta index.js você deve importar o express com o comando "import express from "express". Depois, deverá inicializar o express e salvá-lo em uma variavel através do comando:
const (variavel constante cujo o valor não pode ser alterado) express (nome da variável) = (sinal de atribuição) require("express") (indica a dependencia da variavel pela biblioteca express)

# 4- Estruturando um projeto Express
Depois de inicializar o express em seu projeto, devemos atribuí-lo à uma variável controladora, da seguinte forma. const app = express() - "dessa forma atribuimos herdamos todos os metódos de express para a variavel *app*"

# 5 - Criando suas rotas com Express
Para criar suas rotas, você deve usar a seguinte estrutura (verbo http, app, (), url da rota, () =>{} função que vai ser executada quando a rota for chamada. 
<br>

# *API* - O que é?

Uma API, ou Interface de Programação de Aplicações, é um conjunto de definições e protocolos que permite que diferentes sistemas se comuniquem entre si. Ela define como os desenvolvedores podem interagir com um serviço ou software, especificando as operações disponíveis, os formatos de dados e as regras de autenticação.

Em termos simples, uma API funciona como um intermediário que permite que diferentes aplicações troquem informações de forma padronizada, facilitando a integração e a funcionalidade entre sistemas diversos. Por exemplo, uma API de um serviço de clima permite que um aplicativo busque e exiba informações meteorológicas.



