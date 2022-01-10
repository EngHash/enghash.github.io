---
date: 2022-01-10 12:36:40
layout: post
title: Como Instalar o Pycharm no Ubuntu 20.04
subtitle: Instalando o Pycharm facilmente no Ubuntu 20.04
description: Nesse pequeno Tutorial iremos aprender a instalar de maneira fácil o Pycharm no Ubuntu 20.04.
image: https://res.cloudinary.com/dlpu1d2ml/image/upload/v1641828896/enghash/pycharm_u9lrc1.png
optimized_image: https://res.cloudinary.com/dlpu1d2ml/image/upload/c_scale,w_380/v1641828896/enghash/pycharm_u9lrc1.png


category: tutorial
tags:
  - python
  - pycharm
  - linux
  - ubuntu

author: oseiasfarias
---

Aprenda a programar com Python:

<iframe width="100%" height="440" src="https://www.youtube.com/embed/videoseries?list=PL5jigOsyxDtCGEdY1I0Ymmv4lOyUkWbm2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


O Pycharm é um ambiente de desenvolvimento integrado projetado para facilitar a vida dos programadores Python. PyCharm porque ele pode ser usado para analisar código, depurar programas e é integrado com Git e outros sistemas de controle de versão, bem como aplicativos de desenvolvimento web.

Para instala-lo em seu Ubuntu, siga as etapas a seguir:

### **Passo 1:**

Abra seu terminal e digite o comando:

Obs: a versão *pycharm-professional* é paga!.

```shell
sudo snap install pycharm-community --classic

OU

sudo snap install pycharm-professional --classic

OU

sudo snap install pycharm-educational --classic
```

### **Passo 2:**

Após a instalação terminar, abra o Pycharn executando o seguinte comando no terminal:

```shell
pycharm-community

OU

pycharm-professional

OU

pycharm-educational
```

## **Solução de problemas**

Caso você receba a seguinte mensagem de erro durante o carregamento do PyCharm:

```shell
ModuleNotFoundError: No module named 'distutils.core'
```

Execute o seguinte comando no terminal:

```shell
sudo apt-get install python3-distutils
```

Esperamos tê-lo(a) ajudado(a) a sanar suas dúvidas. Até o próximo post…



