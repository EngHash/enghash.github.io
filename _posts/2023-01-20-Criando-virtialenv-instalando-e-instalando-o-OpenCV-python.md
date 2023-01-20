---
date: 20223-0120 11:30:00
layout: post
title: Criando Virtualenv e instalando o OpenCV Python
subtitle: Criando ambiente exclusivo para seus estudos com OpenCV Python.
description: Nesse tutorial você irá aprender como criar um ambiente virtual python para instalar o OpenCV Python.
image: https://res.cloudinary.com/dlpu1d2ml/image/upload/v1674224769/enghash/demo_kbwvvw.png
optimized_image: https://res.cloudinary.com/dlpu1d2ml/image/upload/c_scale,w_380/v1674224769/enghash/str_cmkjcl.png


category: python
tags:
  - python
  - opencv
  - cv2

author: oseiasfarias
---

Aprenda a programar com Python:

<iframe width="100%" height="440" src="https://www.youtube.com/embed/videoseries?list=PL5jigOsyxDtCGEdY1I0Ymmv4lOyUkWbm2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


O Python é uma linguagem de programação de alto nível de abstração, isso significa que você não precisa aprender técnicas complexas de programação para se aventurar nessa linguagem, no entrando o Python possui uma grande gama de bibliotecas que podem ser usadas para diferentes aplicações é fazer o gerenciamento de cada uma delas pode ser complicado caso você use apenas o python padrão da sua maquina, pensando nisso, os desenvolvedores da linguagem criaram os ambientes virtuais, que possibilitam ter um interpretador especifico para cada aplicação se que eles interfiram uns nos outros, esse ambientes são chamados de virtualenv.

## **Criando Virtualenv usando o Python**

Para criar uma virtualenv é preciso que você tenha o Python e o pip instalado em sua máquina, caso você ainda não tenha,<a href="https://pythonaltas.github.io/instalando-python-e-pip-no-ubuntu-debian-e-derivados/" target="_blank">nesse posto mostro como realizar a instalação dos dois</a>.

Tendo instalado esses dois requisitos, para criar um ambiente virtual basta digitar o seguinte comando em seu terminal;


```shell
python3 -m venv env
```

sua virtualenv para esse exemplo terá o nome de env, agora que você criou a virtualenv é preciso que você ative ela para que ela possa ser usada. digite o seguinte comando em seu terminal para ativa-lá.

```shell
# Sistema Operacional Linux
source env/bin/activate

# Sistema Operacional Windows
env/Scripts/Activate
```

Pronto, agora você tem um ambiente virtual onde pode instalar as bibliotecas especificas do seu projeto, sem que interfira em seu python padrão.

<span style="color:red">OBS: sempre que você for trabalhar em seu projeto, deve ativar sua virtualenv e deve executar o código usando o terminal em que você ativou ela, dessa forma seu código será executado a partir do interpretador da virtualenv.</span>


#### **Instalando o OPenCV no Ambiente Virtual**

Para realizar a instalação do OpenCV vamos usar o pip, você pode ver sempre a vensão mais atualizada atraves do link, <a href="https://pypi.org/project/opencv-python/" target="_blank">OpenCV PIP</a>, basta digitar o seguinte comando em seu terminal para realizar a instalação.

```shell
pip install opencv-python
```

Pronto, agora você possui o OpenCV instalado em seu ambiente virtual.

para verificar se esta corretamente instalado, basta executar o interpretador e importar o opencv, omo mostrado abaixo.

<div>
<img src="https://res.cloudinary.com/dlpu1d2ml/image/upload/v1674224769/enghash/demo_kbwvvw.png"/>
</div>

Executando o Python no terminal, digite:

```shell
python
```

Importando o OpenCV e verificando a versão, digite:

```shell
# Importando a biblioteca
import cv2

# Verificando a versão
cv2.__version__
```

Realizando esses passos, você terá o OpenCV instalado e pronto para usar em seus projetos.

---


Esperamos tê-lo(a) ajudado(a) a sanar suas dúvidas. Até o próximo post…



