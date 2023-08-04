
# Parking App
### Visão Geral
Este projeto é uma aplicação de estacionamento para dispositivos móveis que permite aos usuários estacionar seus carros em alguma área da cidade e iniciar/parar o estacionamento.

## Funcionalidades Principais
A seguir estão as principais funcionalidades que os usuários poderão realizar, as quais serão implementadas como endpoints da API. Em uma aplicação de estacionamento simples, as funcionalidades incluem:

* Registro de Usuário
* Login de Usuário
* Visualização/Atualização de Perfil e Senha do Usuário
* Gerenciamento dos veículos do usuário
* Obtenção de preços para as zonas/áreas de estacionamento
* Iniciar/Parar o estacionamento em uma zona escolhida
* Visualizar o preço atual/total do estacionamento


Observação: Nesta aplicação, não implementaremos o processamento real dos pagamentos de estacionamento, pois isso pode variar muito de acordo com o país. Trataremos apenas da lógica do estacionamento em si.

## Entidades do Sistema
Antes de começarmos a desenvolver a aplicação, vamos definir as entidades principais que compõem o sistema, as quais correspondem às tabelas do banco de dados e aos modelos Eloquent:

* Usuários: Responsável por armazenar as informações dos usuários, como nome, email e senha.
* Veículos: Armazena os veículos associados aos usuários, com informações como marca, modelo e placa.
* Zonas de Estacionamento: Contém as informações sobre as zonas/áreas de estacionamento e seus preços.
* Eventos de Estacionamento: Registra os eventos de início e término de estacionamento, incluindo detalhes como data e hora.

## Referências da API

A API desse projeto se encontra neste link: https://github.com/yurineves92/car-parking-api

## Tecnologias e Conceitos

* Javascript
* React
* API Rest
* JSON