---
date: 2021-02-27 12:26:40
layout: post
title: Executando Códigos Python no Terminal do Ubuntu, Debian e Derivados
subtitle: Como executar códigos pelo terminal do Ubuntu, Debian e Derivados
description: Hoje vamos aprender a executar códigos pelo terminal do Ubuntu, Debian e seus derivados.
image: https://res.cloudinary.com/dlpu1d2ml/image/upload/v1641737039/enghash/terminal_ufdzbj.png
optimized_image: https://res.cloudinary.com/dlpu1d2ml/image/upload/c_scale,w_380/v1641737039/enghash/terminal_ufdzbj.png

category: code
tags:
  - python
  - debian
  - linux
  - ubuntu

author: oseiasfarias
---

O Python é uma linguagem de programação muito famosa e por isso muito utilizada em diversas áreas da tecnologia, desde desenvolvimento web até em Inteligencia Artificial. Hoje vamos aprender como roda scripts python no terminal do Ubuntu ou no Debian e seus derivados.

<div class="embad">
    <iframe width="100%" height="440" src="https://www.youtube.com/embed/SJUwHDc59yo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

## **Crie uma pasta teste**

Para fica mais organizado, vamos criar uma pasta para o nosso projeto teste, para isso digite o seguinte comando em seu terminal.

```shell
mkdir teste
```

Com isso você terá uma nova pasta como o nome de teste.

## **Acesse a pasta**

Agora vamos acessar essa pasta, para isso digite o seguinte comando:

```shell
cd teste
```

## **Crie um arquivo de texto python**

Assim que você precionar ENTER voçê irá para dentro da pasta, agora podemos criar o nosso script teste, existe varias formas de criar um arquivo de texto, nesse caso vou utilizar o nvim, fique avontade para criar com o editor de texto da sua preferência.

```shell
nvim main.py
  ou
vim main.py
  ou
vi main.py
```

Ao apertar ENTER, voçê vai ter acesso ao arquivo, precione “I” no seu teclado para poder editar o arquivo.

## **Escreva seu código Python**

Agora com o arquivo python aberto, vamos escrever um código para podemos execula-lo no terminal, para esse exemplo, vamos fazer algum bem simples, vamos escrever um “Hello World”.

```shell
print("Hello World!!!")
```

Após ter digitado o código, agora você pode salvar e sair do editor, para faça o seguinte:

1. Aperte no ESC do teclado
2. Aperte SHIFT :
3. Aperte ENTER

## **Execulte seu script no terminal**

Agora voçê está com um script pronto para ser execultado no terninal, para execultar o script, faça o seguinte:

```shell
python3 main.py
```

## **Execultando o script com uma virtualenv**

Caso você saiba o que é uma virtualenv, fizemos um post explicando como instalar o programa que cria virtuaienv, acesse <a href="https://enghash.github.io/python-criando-virtualenv-no-ubuntu/" target="_blank">Python - Criando virtualenv no Ubuntu/Debian e Seus Derivados</a>

Caso já tenha instalado, digite o seguinte comando no terminal para criar uma virtualenv:

```shell
virtualenv venv
```

Você pode mudar o nome “venv” para um de sua escolha, após isso, vamos ativar a sua virtualenv, faça o seguinte em seu terminal:

```shell
source venv/bin/activate
```

Aperte enter e terá sua virtualenv ativada e pronta para uso.

Agora vamos roda o script python nela, para isso digite o seguinte comando:

```shell
python main.py
```

Novamente você terá o seu script execultado.

## **Criando um executável python**

Para criar um executável python voçê tem que escrever uma código na sua primeira linha do seu script, para isso abra o seu script com o editor de sua preferência e digite o seguinte código na primeira linha do mesmo:

```shell
#!/usr/bin/env python3
```

Salve a modificação e digite o seguinte comando no terminal:

```shell
chmod +x main.py
```

Agora vamos roda o executável no terminal, para isso faça:

```shell
chmod +x main.py
```

Como das outras vezes seu script irá roda.


Esperamos tê-lo(a) ajudado(a) a sanar suas dúvidas. Até o próximo post…



