Explicação da Estrutura de arquivos:
Backend:
controllers/: Aqui vamos colocar os controladores, que manipulam as requisições e as respostas.
models/: Vamos definir os modelos do MongoDB (usando Mongoose para manipular os dados).
routes/: Definimos as rotas da API.
config/: Arquivos de configuração (por exemplo, conexão com o banco de dados).
.env: Arquivo de configuração para variáveis de ambiente (por exemplo, URL do MongoDB).
server.js: Arquivo principal que vai rodar o servidor.
package.json: Arquivo de dependências e scripts.
Frontend:
public/: Arquivos estáticos públicos.
src/assets/: Imagens, CSS, etc.
src/components/: Componentes Vue reutilizáveis.
src/views/: Páginas (login, cadastro, etc.).
src/router/: Configuração das rotas do Vue Router.
src/store/: Estado global (usaremos Vuex).
App.vue: Componente principal da aplicação.
main.js: Arquivo de entrada do Vue.
.env: Configurações de ambiente para o frontend (API URL, por exemplo).
vite.config.js: Configurações do Vite (ferramenta de build).
