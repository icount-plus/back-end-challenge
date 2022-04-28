# Desafio Back-end iCount Plus

Faça o desafio Back-end e teste os seus conhecimentos.

## Requisitos

- Proatividade e compromisso
- Conhecimento sobre o paradigma orientado à objetos
- Experiência com APIs em Django
- Saber como usar ferramentas como Postman ou Insomnia para interagir com uma API
- Usar o git para controlar versões do seu código

## Desafio

Desenvolver uma API usando a framework Django REST que gerencie a abertura de chamados de suporte.

Um chamado deve conter o nome de quem abriu, uma variável "status" que guarde se o chamado está aberto ou encerrado, uma descrição e um número ilimitado de mensagens.

Uma mensagem deve conter o nome do emissor, o conteúdo da mensagem além da data e hora que foi enviada.

Os endpoints deverão realizar as seguintes ações:

- `GET /support/` deve listar todos os chamados
- `POST /support/` deve criar um novo chamado
- `GET /support/:id/` deve retornar as informações de um chamado específico
- `PUT /support/:id/` deve alterar as informações de um chamado específico
- `DELETE /support/:id/` deve apagar um chamado específico
- `GET /support/:id/messages/` deve listar todas as mensagens de um chamado específico
- `POST /support/:id/messages/` deve enviar uma nova mensagem em um chamado específico

Observação: Ao listar todos os chamados ou retornar um chamado específico, a resposta não deve conter as mensagens desse chamado. As mensagens deverão ser visíveis somente ao listá-las em `GET /support/:id/messages/`.
