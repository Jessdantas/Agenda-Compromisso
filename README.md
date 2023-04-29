Agendamento de Tarfas!

Este é um projeto de um sistema de gerenciamento de tarefas desenvolvido em Node.js com o framework Express e o ORM Sequelize para o banco de dados.

Funcionamento

O sistema permite o cadastro, edição e exclusão de tarefas, bem como a listagem de todas as tarefas cadastradas.

Como executar

Clone o repositório para a sua máquina local.

Certifique-se de ter o Node.js e o banco de dados MySQL instalados.

Abra o terminal na pasta raiz do projeto e execute o comando npm install para instalar as dependências necessárias.

Crie um banco de dados MySQL e configure as informações de conexão no arquivo db/conn.js.

Execute o comando npm start para iniciar o servidor.

Acesse o sistema no seu navegador pelo endereço http://localhost:3000/tasks.

Estrutura do Projeto

db/: Contém o arquivo de configuração do banco de dados e a definição dos modelos do Sequelize.
public/: Contém os arquivos estáticos do sistema, como CSS e imagens.
routes/: Contém os arquivos com as rotas do sistema.
views/: Contém os arquivos HTML com as views do sistema.
app.js: Arquivo principal do sistema, onde são configurados o Express e as rotas.
package.json: Arquivo com as informações do projeto e as dependências utilizadas.

Dependências

Express
Express Handlebars
Sequelize
MySQL2
Créditos
Desenvolvido por [seu nome ou empresa].
