# IsraelEstoque
Repositório de suporte e aprendizado para outro projeto

## Como rodar o projeto?

* Clone esse repositório.
* Crie um virtualenv.
* Ative o virtualenv.
* Instale as dependencias.
* Rode as migrações.

```
git clone https://github.com/israelwerther/IsraelEstoque.git.
cd IsraelEstoque.
virtualenv --python=python3 venv.
source venv/bin/activate.
pip isntall -r requirements.txt.
python contrib/env_gen.py    (cria arquivo .env aleatoriamento toda vez que roda o comando). 
python manage.py migrate.
```

## Links

[python-decouple](https://github.com/henriquebastos/python-decouple)

[package-of-the-week-python-decouple](https://simpleisbetterthancomplex.com/2015/11/26/package-of-the-week-python-decouple.html)