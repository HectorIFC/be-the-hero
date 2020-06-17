Após fazer o clone, entre no diretório do projeto:

cd be-the-hero

Entre no diretório backend:

cd ./backend

Faça a instalação dos pacotes, execute:

npm install

Execute as migrações do banco de dados:

knex migrate:latest

Agora é só "subir" o serviço:

npm start
