# Wiki de Repositório



Este projeto é uma wiki de repositório desenvolvida em React JavaScript. Ele permite que você visualize e pesquise informações sobre um repositório específico do GitHub, fornecendo o nome do usuário e do repositório na URL.

## Descrição do funcionamento do código

Esse código é para uma página web que mostra uma lista de repositórios do GitHub. A página tem uma barra de pesquisa que permite ao usuário digitar o nome de um repositório, um botão para buscar o repositório na API do GitHub e uma lista de repositórios encontrados.

O código começa importando alguns componentes e bibliotecas que serão usados para construir a página. Em seguida, ele define dois estados usando o hook useState, que são currentRepo e repos. currentRepo armazena o valor atual da barra de pesquisa e repos é uma lista de repositórios que serão exibidos na página.

Depois disso, o código define duas funções: handleSearchRepo e handleRemoveRepo. handleSearchRepo é chamada quando o botão de busca de repositórios é clicado. Ele faz uma chamada à API do GitHub com o nome do repositório atual e adiciona o novo repositório à lista de repositórios se ele não existir ainda. handleRemoveRepo é chamada quando um botão de remoção de repositório é clicado. Ele remove o repositório da lista de repositórios.

Em seguida, o código renderiza os componentes na página. A imagem do logo do GitHub é exibida, seguida pela barra de pesquisa e o botão de busca de repositórios. Por último, a lista de repositórios é exibida usando o componente ItemRepo para cada item.

## Como usar

### Para usar esta aplicação, siga os seguintes passos:

Clone este repositório em sua máquina local.

Instale as dependências do projeto executando o comando `npm install`.

Inicie o servidor local executando o comando `npm start`.

Acesse a página da aplicação em `http://localhost:3000/`, substituindo "usuario" e "repositorio" pelos respectivos nomes do usuário e do repositório do GitHub que você deseja visualizar.

## Funcionalidades

Pesquisa de informações sobre o repositório do GitHub a partir do nome do usuário e do repositório na URL.

Visualização de informações gerais sobre o repositório, como descrição, linguagem, número de estrelas e forks.

Listagem de todos os commits do repositório, com informações sobre autor, data e mensagem de commit.

Busca por commits específicos por meio de palavras-chave na mensagem do commit.

## Tecnologias utilizadas

React JavaScript
Axios(para api)
React Router DOM(é uma biblioteca que ajuda a lidar com a navegação em aplicativos React de página única (SPA))

## Contribuição

Contribuições são bem-vindas e incentivadas! Sinta-se à vontade para enviar pull requests e reportar issues. Certifique-se de seguir o código de conduta do projeto.

## Licença

Este projeto é licenciado sob a licença MIT.
