# Blog com Node.js

Este é um projeto de um sistema de blog simples construído com Node.js. Ele permite a criação de postagens e categorias, além de um sistema de autenticação e gerenciamento de usuários.

## Instalação e Uso

Para executar este projeto localmente, siga os seguintes passos:

1.  **Clone o repositório:**
    ```bash
    git clone https://github.com/manoelcn/blog-com-nodejs.git
    cd blog-com-nodejs
    ```
2.  **Instale as dependências:**
    ```bash
    npm install
    ```
3.  **Configure as variáveis de ambiente:**
    -   Crie um arquivo **`.env`** na raiz do projeto. O arquivo `.gitignore` já está configurado para ignorá-lo.
    -   Adicione as seguintes variáveis de ambiente ao arquivo `.env`:
        -   `MONGO_URL=sua_string_de_conexao_mongodb` (A string de conexão para o seu banco de dados MongoDB)
        -   `SECRET=uma_chave_secreta_para_a_sessao` (Uma chave secreta para a sessão Express)
4.  **Execute a aplicação:**
    ```bash
    npm run app
    ```
    O servidor será iniciado em `http://localhost:8081`.