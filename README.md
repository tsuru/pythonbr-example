# Deploys grátis durante a Python Brasil 2022

Isso mesmo!
Conheça como funciona o tsuru.io


# Instale o Client

TODO:

# Conecte ao Tsuru server

tsuru target add pythonbr https://pythonbrasil.tsuru.io -s
tsuru login


# Criando aplicação

tsuru app create {SEU-GITHUB} python --team pythonbr


# Deploy da Aplicação

tsuru app deploy -a {SEU-GITHUB} .


# Feedback
