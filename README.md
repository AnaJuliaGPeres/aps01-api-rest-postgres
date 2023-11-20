#API 01 -API REST com POSTGRES

Integrantes: 
-Ana Julia
-Ana Clara 
-Natali


##Dependencias do projeto 
```
 shell

 poetry add fastapi
 poetry add sqlmodel
 poetry add uvicorn
 poetry add psycopg2-binaty
 
```

## Iniciando o servidor http
```
shell
 uvicorn src.server:app --reload
```

##Caso queira subir sem carregar o shell executar o comando abaixo