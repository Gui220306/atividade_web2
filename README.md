# atividade_web2
*Tela Inicial de um E-commerce com ReactJS*

Este projeto é uma aplicação ReactJS que implementa a tela inicial de um e-commerce, consumindo dados de uma API RESTful para exibir produtos de forma organizada e responsiva.

*Requisitos do Projeto*

-API utilizada:

Fake Store API

-Funcionalidades implementadas:

Exibição de produtos com:

Nome

Imagem

Preço

Categoria

Suporte a diferentes tamanhos de tela (responsividade).

Carregamento condicional com mensagem "Carregando...".

Tratamento de erros com exibição de mensagens apropriadas.

-Componentização:

Componentes reutilizáveis para listagem de produtos e itens individuais.

-Tecnologias Utilizadas

ReactJS com hooks (useState e useEffect).

Estilização: CSS, Styled Components ou Material-UI.

Bibliotecas adicionais: Fetch para consumo da API.

-Instruções para Rodar o Projeto

Pré-requisitos

Certifique-se de ter instalado:

Node.js (versão LTS recomendada).

npm ou yarn.

Passos para executar

Clone o repositório:

git clone <URL_DO_REPOSITORIO>
cd <PASTA_DO_PROJETO>

Instale as dependências:

npm install

Configure a API:

Altere a URL da API no arquivo de configuração (caso aplicável).

Certifique-se de que a API escolhida está acessível.

Inicie a aplicação:

npm start
# ou
yarn start

Acesse a aplicação:

Acesse http://localhost:3000 no seu navegador.

Testando a aplicação

Carregamento inicial:

A aplicação exibirá "Carregando..." enquanto os dados estão sendo buscados.

Exibição dos produtos:

Certifique-se de que os produtos estão sendo exibidos corretamente.

Responsividade:

Teste a aplicação em diferentes tamanhos de tela para garantir que os elementos se ajustam adequadamente.

Tratamento de erros:

Simule um erro na API (ex.: altere a URL para uma inválida) e verifique a mensagem de erro exibida.

Estrutura de Arquivos

src/
├── components/
│   ├── ProductCard.js  # Componente individual para exibir produto
│   ├── ProductList.js  # Componente para listar os produtos
├── index.js            # Ponto de entrada da aplicação

Possíveis Melhorias

Adicionar funcionalidades de busca e filtro por categoria.

Implementar paginação ou carregamento infinito.

Melhorar o design visual utilizando bibliotecas como TailwindCSS ou Material-UI.

Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests no repositório.

Licença

Este projeto é licenciado sob a MIT License.

