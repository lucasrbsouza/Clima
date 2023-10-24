# Clima
# README

## Descrição

Este é um script JavaScript que utiliza a API do OpenWeatherMap para buscar informações sobre o clima de uma localização específica. O usuário insere o nome da localização em um campo de busca e o script retorna informações como nome da localização, país, temperatura atual, ícone de temperatura, velocidade do vento e ângulo do vento.

## Como usar

1. Insira o nome da localização desejada no campo de busca.
2. Pressione Enter ou clique no botão de busca.
3. As informações sobre o clima na localização especificada serão exibidas na tela.

## Funções

- `showInfo(obj)`: Esta função exibe as informações do clima na tela. Ela recebe um objeto que contém as informações do clima.
- `clearInfo()`: Esta função limpa as informações do clima atualmente exibidas na tela.
- `showWarning(msg)`: Esta função exibe uma mensagem de aviso na tela. Ela recebe uma string que é a mensagem a ser exibida.

## API

Este script utiliza a API do OpenWeatherMap para buscar as informações sobre o clima. A chave da API está incluída no script.

## Notas

Este script utiliza a função `fetch` para fazer a requisição à API, portanto, ele só funcionará em navegadores que suportam a API Fetch.

Por favor, note que este script foi criado para fins educacionais e pode não ser adequado para uso em produção sem modificações.
