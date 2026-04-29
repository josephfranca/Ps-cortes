# Ps-cortes
Landing page de barbearia desenvolvida com HTML, CSS e JavaScript no front-end, integrada a um backend em PHP responsável pelo processamento de dados de formulários e comunicação com banco de dados MySQL para armazenamento das informações de clientes.


Projeto de uma landing page institucional para uma barbearia da comunidade, desenvolvido com foco em apresentação de serviços, experiência do usuário e captação de clientes, contando com integração back-end para armazenamento de dados.

A aplicação foi construída com HTML, CSS e JavaScript no front-end, e PHP no back-end, permitindo o envio e armazenamento de informações de clientes por meio de formulário de contato.

Os dados enviados são processados pelo servidor e persistidos em banco de dados MySQL, simulando um cenário real de coleta de leads para negócios locais.

Tecnologias utilizadas

Front-end:

HTML
CSS
JavaScript

Back-end:

PHP
MySQL

Funcionalidades
Landing page responsiva para apresentação de serviços
Formulário de contato integrado ao backend
Captura de dados do usuário (nome, WhatsApp, email e mensagem)
Armazenamento das informações em banco de dados MySQL
Feedback visual ao usuário após envio (alert + redirecionamento)
Estrutura simples de comunicação entre front-end e back-end

Estrutura do backend
Script em PHP responsável por:
Receber dados via método POST
Conectar ao banco de dados MySQL
Executar inserção na tabela de clientes
Banco de dados com tabela estruturada para armazenamento de leads
Registro automático de data de envio das informações

Simular um site real de um negócio local com captação de clientes
Praticar integração entre front-end e back-end
Implementar persistência de dados com banco de dados
Desenvolver uma aplicação simples com fluxo completo (formulário → backend → banco)

Como executar o projeto

1. Clonar o repositório
 git clone https://github.com/josephfranca/Ps-cortes.git

2. Mover para o servidor local
 Coloque a pasta do projeto dentro do diretório do seu servidor:

XAMPP:
C:\xampp\htdocs\
WAMP:
C:\wamp64\www\

3. Configurar o banco de dados
   
1. Abra o phpMyAdmin
   (Geralmente: http://localhost/phpmyadmin)
   
2. Crie um banco de dados
   (Exemplo: barbearia)
   
3. Importe o arquivo
   bd.sql
   
4. Configurar conexão com o banco
   No arquivo salvar.php, ajuste a variável $db para o nome do banco de dados que você criou se necessário:

  $host = "localhost";
  $user = "root";
  $password = "";
  $db = "barbearia"; //possível ajuste aqui com o nome do banco de dados se necessário.

  5. Rodar o projeto

  1. Inicie o apache (XAMPP/WAMP)
  2. Acesse no navegador:
     http://localhost/nome-da-pasta
