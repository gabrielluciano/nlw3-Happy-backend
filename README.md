# Next Level Week 3 - Happy - Backend

Projeto do backend da aplicação Happy, realizado no evento Next Level Week 3, trilha Omnistack.

## Tecnologias

* [NodeJs](https://nodejs.org/)
* [Typescript](http://typescriptlang.org/)
* [Express](https://expressjs.com/pt-br/)
* [MySQL](https://www.mysql.com/)
* [TypeORM](https://typeorm.io/#/)

## Instalando dependências

Após clonar o projeto, você pode instalar as dependências usando o gerenciador de pacotes [yarn](https://yarnpkg.com/) com o comando:

```bash
yarn install
```

## Banco de Dados

Diferente do que foi feito na semana, optei por utilizar o MySQL para o backend da aplicação. Para fazer a conexão com o MySQL, você deve modificar o arquivo `ormconfig.json` inserindo os dados do seu banco de dados e da tabela

```json
{
    "username": "",
    "password": "",
    "database": "",
}
```

## Rodando seu projeto com `yarn dev`

Para rodar o projeto basta utilizar o comando yarn dev.