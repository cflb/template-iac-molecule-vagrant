# Construindo uma base Generica do Molecule para provisionar com Vagrant

----------

## Construindo Ambiente de isolamento virtual do python
> python3 -m venv nome-da-env

### Ativando ambiente virtual
> source nome-da-env/bin/activate


``` 
Se tudo ocorreu bem, seu terminal/prompt apresentará o seguinte pré-fixo (nome-da-env).
Assim, sera semelhante a:
```
> (nome-da-env)$

----------

### Desativando o ambiente 
Para finalizar seu ambiente executo o comando a baixo:

> (nome-da-env)$ desactivate


----------

## Instalando dependências
> (nome-da-env)$ python3 -m pip install ansible molecule python-vagrant

