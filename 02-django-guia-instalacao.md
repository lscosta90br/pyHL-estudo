# Criando projeto django


## Entrando no ambiente virtual
```bash
# entrando no diretorio do projeto e ambiente virtual
cd d:\project\pyhl
poetry shell

# criando projeto django e app
poetry run django-admin startproject djhl .
cd d:\project\pyhl\djhl
poetry run python ..\manage.py startapp core
# criando app core dentro do projeto djhl

# Rodando a aplicaação django
cd d:\project\pyhl
poetry run python manage.py runserver
```
