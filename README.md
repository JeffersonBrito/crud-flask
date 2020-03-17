## Estudo de Crud
crud usando flask 
- flask_sqlalchemy
- flask_migrate
- flask_marshmallow
- marshmallow_sqlalchemy



## Como rodar projeto
```sh
export FLASK_APP=app
export FLASK_ENV=Development
export FLASK_DEBUG=True

flask run
```


## Como fazer as migrações

```sh
flask db init
flask db migrate
flask db upgrade
```

## Serializer
``` sh
    Faz o objeto que é um JSON que vem da rota, ser retornado como um objeto no banco. 
    É para simplificar os tipos intercambiáveis para haver menos problemas...
```