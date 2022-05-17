## Projeto base para o evento AWS com Docker.

### evento

[>> Página de Inscrição do evento](https://dennismichel.com.br)


#### Para rodar as migrations no container ####
```
docker-compose exec server bash -c 'npx sequelize db:migrate'
```