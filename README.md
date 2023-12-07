# Trabalho-Distribuidos

## Link

### [Trello](https://trello.com/b/2oYoHH4F/sistema-distribuidos)
### [Youtube](https://youtu.be/89v0IzNvX8k)

## Como Rodar o Codigo

## 1. Crie e Ative o Conda env no seu computador:

    $ conda create -n omni-env -c conda-forge python=3.10 omniorb omniorbpy

    $ conda activate omni-env

## 2. Gere um código Python de IDL em ambos os computadores:

    $ omniidl -bpython RemoteMiddleware.idl

## 3. Rode um o Servidor no computador A:

    $ python Servidor.py

## 5. Rode o Cliente no Computador B:

    $ python Cliente.py

## 6. Coloque o IOR do Servidor no Cliente :

    $ Enter IOR of Greetings object:

    IOR:010000001a...
