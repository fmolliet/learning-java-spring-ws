# Learning JAVA Spring API ☕

Nesse repositório, montei um uma API Rest baseado no tutorial do spring boot que pode ser encontrado [AQUI](https://spring.io/guides/tutorials/rest/). Para ele juntei com conhecimento que eu ja tinha de docker para deixar disponivel um docker-compose.yml para subir o ambiente de conexão para o banco.

## Como subir o projeto 🌀

Rode o seguintes comandos no terminal

### Docker:

```sh
docker-compose up -d
```

### Iniciando a API

```sh
mvn clean spring-boot:run
```

Ao subir a API estará disponível em `localhost:8080/employees` .

## Requests 

Eu deixei um arquivo de Insomnia.json com as requisições de teste.
