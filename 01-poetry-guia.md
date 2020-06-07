
# Estudo de poetry


## Instalação sem interação de preenchimento
```bash
cd d:\project
poetry new pyhl # cria o diretorio pyhl-lc e os arquivos do poetry

# Neste jeito ele criará automaticamente o arquivo pyhl e os arquivos necessário sem interação
```


## Instalação com interação de preenchimento (metodo utilizado)
```bash
PS D:\Projects\PyHL> poetry init

This command will guide you through creating your pyproject.toml config.

Package name [pyhl]:
Version [0.1.0]:  
Description []:  Python Home Library Manager
Author [Leandro Costa <lscosta@gmail.com>, n to skip]:  Vicente Marçal <vicente.marcal@gmail.com>
License []:  BSD-3-Clause
Compatible Python versions [^3.8]:  

Would you like to define your main dependencies interactively? (yes/no) [yes]
You can specify a package in the following forms:
  - A single name (requests)
  - A name and a constraint (requests ^2.23.0)
  - A git url (git+https://github.com/python-poetry/poetry.git)
  - A git url with a revision (git+https://github.com/python-poetry/poetry.git#develop)
  - A file path (../my-package/my-package.whl)
  - A directory (../my-package/)
  - An url (https://example.com/packages/my-package-0.1.0.tar.gz)

Search for package to add (or leave blank to continue):

Would you like to define your development dependencies interactively? (yes/no) [yes]
Search for package to add (or leave blank to continue): 

Generated file

[tool.poetry]
name = "pyhl-lc"
version = "0.1.0"
description = "Python Home Library Manager"
authors = ["Vicente Marçal <vicente.marcal@gmail.com>"]
license = "BSD-3-Clause"
[tool.poetry.dependencies]

[tool.poetry.dev-dependencies]

requires = ["poetry>=0.12"]
build-backend = "poetry.masonry.api"


Do you confirm generation? (yes/no) [yes] yes
```


## Adicionado biblioteacas no poetry para criação de ambiente virtual
```bash
cd d:\project\pyhl
# adicionado arquivos para ambiente de produção
poetry add django dynaconf PyYaml psycopg2-binary djangorestframework markdown django-filter 

# adicionado arquivos para ambiente de produção
poetry add --dev pytest pytest-django pytest-cov flake8 black

# adicionado arquivos para ambiente de desenvolvimento
pytest pytest-django pytest-cov flake8 black
```

## Entrando no ambiente virtual
```bash
# entrando no diretorio do projeto e ambiente virtual
cd d:\project\pyhl
poetry shell
```


```bash
```
```bash
```
```bash
```
```bash
```
```bash
```
```bash
```
```bash
```
```bash
```









