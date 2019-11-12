# GoBarber-backend
API REST do Backend do GoBarber em Node.JS, do bootcamp da RocketSeat

## Instalação

Será necessário primeiramente instalar as dependencias: npm install ou yarn.

Além das dependencias, foi utilizado o DOCKER, com banco MYSQL para os dados relacionais.

MONGODB para dados não relacionais a fim de ganhar desempenho.

REDIS para funcionar junto com o BeeQueue, para gerenciar em background jobs o envio de EMAIL com nodemailer.

```bash
npm install
ou
yarn
```

## Tecnologias/Ferramentas utilizadas

```bash
Docker Desktop
Sequelize
Mongoose
*Autenticação JWT
Bcrypt: Password HASH
Multer: Upload de imagens
NodeMailer: Envio de email com Node.JS
Handlebars: Templates de EMAIL com HTML e CSS
BeeQueue: Fila e background jobs com REDIS
Sentry.io: Tratamento de exceções
```

## :memo: Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE.md) para mais detalhes.
