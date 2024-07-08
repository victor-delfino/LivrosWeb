# Controle Pessoal de Livros

Este é um projeto React para gerenciar um controle pessoal de livros, com funcionalidades de inclusão, manutenção e resumo de livros. 

## Instalação

1. Clone o repositório para o seu computador:
    ```sh
    git clone https://github.com/seu-usuario/seu-repositorio.git
    ```

2. Navegue até a pasta do projeto:
    ```sh
    cd seu-repositorio
    ```

3. Instale as dependências do projeto:
    ```sh
    npm install
    ```

4. Inicie o servidor de back-end:
    ```sh
    cd projetowb
    node app
    ```

5. Inicie o projeto React:
    ```sh
    cd projeto
    npm start
    ```

## Estrutura do Projeto

- `projeto/`: Contém o código-fonte do projeto React.
    - `src/components/`: Contém os componentes React.
        - `MenuSuperior.js`: Componente do menu superior.
        - `InclusaoLivros.js`: Componente para inclusão de livros.
        - `ManutencaoLivros.js`: Componente para manutenção de livros.
        - `ResumoLivros.js`: Componente para resumo dos livros.
        - `ItemLista.js`: Componente para exibir cada item da lista de livros.
    - `src/config_axios.js`: Configuração do Axios para comunicação com a API.
    - `src/App.js`: Componente principal que configura as rotas da aplicação.
    - `src/index.js`: Ponto de entrada do React.

- `projetowb/`: Contém o código-fonte do servidor de back-end 


### Inclusão de Livros

O componente `InclusaoLivros` permite adicionar novos livros à lista. Ele utiliza o hook `useForm` do `react-hook-form` para gerenciar o formulário e `Axios` para enviar os dados para a API.

### Manutenção de Livros

O componente `ManutencaoLivros` exibe uma lista de livros cadastrados, permitindo a exclusão e a alteração dos registros. Ele utiliza `useState` para gerenciar a lista de livros e `useEffect` para obter a lista ao carregar a página.

### Resumo dos Livros

O componente `ResumoLivros` exibe um resumo dos livros cadastrados.

## Exemplo de Uso

- Para adicionar um novo livro, preencha os campos do formulário na aba "Inclusão" e clique em "Enviar".
- Para visualizar e gerenciar os livros cadastrados, vá para a aba "Manutenção".
- Para visualizar um resumo dos livros cadastrados, vá para a aba "Resumo".

## Dependências

- `react`: Biblioteca JavaScript para construir interfaces de usuário.
- `react-dom`: Pacote que fornece métodos específicos do DOM para usar com React.
- `react-hook-form`: Biblioteca para gerenciamento de formulários em React.
- `axios`: Cliente HTTP baseado em Promises para o navegador e Node.js.
- `react-router-dom`: Biblioteca para gerenciar rotas em aplicações React.



