# CHALLENGE_2

## Book Management API | Tech Challenge - FIAP
Este projeto é uma API CRUD para gerenciamento de livros, desenvolvida como parte do Tech Challenge da FIAP. A API permite criar, ler, atualizar e deletar registros de livros. A aplicação é construída utilizando Node.js, Express e MongoDB.

### Tecnologias Utilizadas
Node.js
Express
MongoDB
Mongoose

### Pré-requisitos
Antes de começar, certifique-se de ter o Node.js e o npm instalados em sua máquina. Além disso, você precisará de uma instância do MongoDB em execução. Você pode usar o MongoDB localmente ou via Docker.

#### Instalação
##### Clone este repositório:
git clone <URL_DO_SEU_REPOSITORIO>
cd <NOME_DO_REPOSITORIO>

##### Instale as dependências:
npm install

#### Configure o MongoDB:

Certifique-se de que o MongoDB está em execução. Se estiver usando Docker, execute:
docker run -d -p 27017:27017 --name mongodb mongo

### Estrutura do Projeto
![image](https://github.com/user-attachments/assets/2c1d4d14-8adc-453e-be54-a3a127eb8682)

### Configuração do Banco de Dados
A configuração da conexão com o MongoDB está localizada em config/database.js. Certifique-se de que o MongoDB está em execução e acessível na porta padrão 27017.

### Executando a Aplicação
Para iniciar o servidor, execute:
## ![image](https://github.com/user-attachments/assets/f907b64d-1819-4c37-b4f8-31a25efec59f)

O servidor estará em execução na porta 3000.

## Endpoints da API
### Criar um Livro

##### URL: /livros
##### Método: POST
##### Body: (JSON

![image](https://github.com/user-attachments/assets/9c85a5f5-5b98-40cf-8ff9-c8e53d7a4a13)
