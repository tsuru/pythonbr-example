# Deploys grátis durante a Python Brasil 2022

Isso mesmo!
Conheça como funciona o tsuru.io


# Instale o Client

```
curl -fsSL "https://tsuru.io/get" | bash
```

# Conecte ao Tsuru server

```
tsuru target add pythonbr https://pythonbrasil.tsuru.io -s
tsuru login
```

# Criando aplicação

```
tsuru app create {SEU-GITHUB} python --team pythonbr
```

# Deploy da Aplicação

```
tsuru app deploy -a {SEU-GITHUB} .
``` 


# Dashboard

https://tsuru-dashboard.pythonbrasil.tsuru.io/

# Feedback

https://bit.ly/tsuru-feedback
