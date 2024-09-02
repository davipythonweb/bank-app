# Criando ambiente do pacote python com Poetry, linters, tests e documentação

- iniciando projeto com poetry , pip install poetry
`poetry new my-app`

- comandos gh-version==2.4 , github cli -linux
`git init .`
`gh repo create`
`gh auth login`

* criando .gitignore com: pip install ignr
`ignr -p python > .gitignore`
`git add .`
`git commit -m "mandando-uma-mensagem"`
`git push --set-upstream origin main`

* adicionando o pytest ao projeto, usando o poetry
`poetry add --group dev pytest`

* coverage para garantir a cobertura de tests
`poetry add --group dev pytest-cov`

* para seguir o estilo da PEP8
`poetry add --group dev blue`

* biblioteca para ordenação de imports
`poetry add --group dev isort`

* para fazer a automaçao na hora de rodar os comandos de test, lint, documentação,deploy e mais
`poetry add --group dev taskipy`

* biblioteca mkdocs para documentar
`poetry add --group doc mkdocs-material`

* para gerar a docstring
`poetry add --group doc mkdocstrings`
`poetry add --group doc mkdocstrings-python`

* criando ambiente virtual com venv
`python3 -m venv venv`
`source venv/bin/activate`