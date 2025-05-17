# Projeto-Alura-e-Google-2025
Projeto Alura/Google IA 2025
BookFlix
Descrição
BookFlix é uma aplicação em Python que simula uma interface simplificada de uma plataforma de streaming de livros, como a Netflix, utilizando a API da Open Library. A aplicação permite aos utilizadores procurar livros por gênero e visualizar informações sobre os mesmos.

Funcionalidades
Busca por Gênero: Permite ao utilizador introduzir um gênero literário e obter uma lista de livros relacionados.

Exibição de Título e Autor: Apresenta o título e o autor de cada livro encontrado, com a opção de mostrar o título e autor originais.

Exibição de Sinopse: Permite ao utilizador selecionar um livro da lista e visualizar a sua sinopse.

Interface de Linha de Comando: A aplicação interage com o utilizador através de uma interface de linha de comando simples.

Tradução para Português: Os títulos e nomes dos autores são traduzidos para português usando a biblioteca googletrans.

Como Usar
Requisitos:

Python 3.x

Bibliotecas: requests, json, googletrans

Instalação:

Instale as bibliotecas necessárias usando o pip:

!pip install googletrans==4.0.0-rc1

Execução:

Execute o script Python:

python bookflix.py

A aplicação irá solicitar o gênero do livro que pretende procurar.

Após introduzir o gênero, será exibida uma lista de livros encontrados.

Pode selecionar um livro da lista para ver a sua sinopse, ou sair.

Estrutura do Código
O código está estruturado em torno de quatro agentes principais:

Busca: Responsável por buscar livros na API da Open Library.

Exibe: Responsável por formatar e exibir os resultados da busca, incluindo a tradução de títulos e autores, e exibir sinopses.

Interage: Responsável pela interação com o utilizador através da linha de comando.

BookFlix: Agente orquestrador que coordena o fluxo da aplicação.

Notas
A API Key utilizada é apenas para fins de demonstração.

A tradução é feita usando a biblioteca googletrans, que pode ter algumas limitações.

A aplicação não implementa a funcionalidade completa de uma plataforma de streaming de livros, como leitura online ou gestão de uma biblioteca pessoal.
