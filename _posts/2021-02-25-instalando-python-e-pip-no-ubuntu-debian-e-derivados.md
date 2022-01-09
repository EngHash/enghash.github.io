---
date: 2021-02-25 12:26:40
layout: post
title: Instalando Python e Pip no Ubuntu, Debian e seus Derivados
subtitle: Instalando o Python e PIP no Ecossistema Linux.
description: Hoje vamos aprender a instalar o Python e o gerenciador de pacotes pip no Sistema Operacional Ubuntu e seus derivados.
image: https://res.cloudinary.com/dlpu1d2ml/image/upload/v1641687409/enghash/ubuntu_bh3xaj.png
optimized_image: https://res.cloudinary.com/dlpu1d2ml/image/upload/c_scale,w_380/v1641687409/enghash/ubuntu_bh3xaj.png

category: code
tags:
  - python
  - pip
  - linux
  - ubuntu

author: oseiasfarias
---

Para roda seus scripts python no Debian ou Ubuntu e seus derivados é preciso ter o python instalado em sua máquina, nas versões mais atuais do ubuntu o python já vem instalado por padrão. caso ele não esteja instalado por algum motivo, siga os passos a seguir para instala-lo.

<div class="embad">
<iframe width="100%" height="422" src="https://www.youtube.com/embed/CGf-l0ElRFM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

para instalar o python é muito simples, basta abrir o terminal do Ubuntu ou Debian e digitar o comando abaixo.

```shell
sudo apt install python3
```

Após apertar Enter no teclado, você terá que digitar a sua senha de usuário de depois escolher “yes” para proseguir com a instalação.

Caso tenha ocorrido tudo corretamente se você digitar o seguinte comando no terminal, terá a indicação da versão do python instalado.

```shell
python3 --version

ou

python --version
```

Esse comando retornará a versão do python instalado em sua máquina.

## **Instalando o Pip**

O pip é o gerenciador de pacotes do python, esses pacotes são códigos que pode ser reutilizado em seus programas usando o paradigima de programação POO (Programação Orientada a Objetos), esses módulos facilitam o desenvolvimentos de programas, já que reduz o tempo de criação de código.

Para instalar o pip basta digitar o seguinte comando em seu terminal.

```shell
sudo apt install python3-pip
```

## **Executando o seu primeiro código python no terminal Ubuntu\Debian**

agora vamos rodar seu primeiro programa no seu terminal, para isso siga os passos a seguir.

1° Abra seu termial

2° digite o seguinte comando no seu terminal

```shell
python3
```

Após isso, o interpretador python irá abrir em seu terminal, agora vocẽ pode executar comandos python.

3° Ditige o comando python abaixo

```shell
print("Hello World!!!")
```

Quando você apertar ENTER no seu teclado, terá como resultado o “Hello World” printado logo abaixo, nesse momento você já executol um código python em seu Ubuntu/Debian.


Esperamos tê-lo(a) ajudado(a) a sanar suas dúvidas. Até o próximo post…








