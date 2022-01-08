---
date: 2021-02-17 12:26:40
layout: post
title: Python - Criando virtualenv no Ubuntu/Debian
subtitle: Aprenda a gerenciar projetos com virtualenv
description: Hoje vamos aprender como criar, ativar e remover uma Virtualenv para gerenciamento de projetos em Python
image: https://res.cloudinary.com/dlpu1d2ml/image/upload/v1641676077/enghash/Design_sem_nome_frk8sc.png
optimized_image: https://res.cloudinary.com/dlpu1d2ml/image/upload/c_scale,w_380/v1641676077/enghash/Design_sem_nome_frk8sc.png

category: code
tags:
  - python
  - virtualenv
  - pip
  - linux
  - ubuntu

author: oseiasfarias
---

<div class="embad">
<iframe width="100%" height="422" src="https://www.youtube.com/embed/Osd7hcts8RQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

Para que possamos dá inicio ao processo de criação é necessário ter o gerenciador de <a href="#">pacotes do python</a> instalado em seu sistema operacional. para verificar, rode o seguinte comando em seu termial:


```shell
pip --version
```

Se ouver uma saída positiva mostrando endereço de algum diretório, isso significa que o pip está instalado.
caso ocorra algum erro, tente:

```shell
pip3 --version
```

Se nenhuma dessas duas opções funcionarem, você deve instalar o pip em seu Sistema Operacional.

## **Instalar o pip para o Python 2**

Rode o seguinte comando no seu Terminal:

```shell
sudo apt install python-pip
```

Verificar se foi realmente instalado.

```shell
pip2 --version
```
A saida do comando ACIMA será algo parecido com esse:

```shell
pip 20.2.4 from /home/user/.local/lib/python2.7/site-packages/pip (python 2.7)
```

## **Instalar o pip para o Python 3**

Rode o seguinte comando no seu Terminal:

```shell
sudo apt install python3-pip
```

verificar se foi realmente instalado


```shell
pip3 --version
```

a saida do comando assim será algo parecido com esse:

```shell
pip 21.0.1 from /home/usr/.local/lib/python3.8/site-packages/pip (python 3.8)
```

## **Instalando Virtualenv o Sistema Operacional usando o pip**

Tendo verificado se o pip está instalado em seu Sistema Operacional, agora podemos continuar, a primeira coisa que devemos fazer para podemos criar uma virtualenv no Ubuntu é instalar a virtualenv, esse programa irá ser responsável por criar as “virtuais envs”.

para temos acesso as funcionalidades, devemos instala-la utilizando o gerencioador de arquivos que instalamos na etapa anterior, para isso digite o seguinte código em seu terminal:


## **Instalar virtualenv para o Python 2**

Rode o seguinte código em seu terminal:

```shell
pip2 install virtualenv
```
Para verificar se a instalação ocorreu de forma correta, digite o seguinte comando no seu terminal:


```shell
virtualenv --version
```

Terá como saída no terminal a seguinte informação:


```shell
virtualenv 20.4.2 from /home/usr/.local/lib/python2.7/site-packages/virtualenv/\_\_init\_\_.pyc

```

## **Instalar virtualenv para o Python 3**

Rode o seguinte código em seu terminal:

```shell
pip3 install virtualenv
```

Para verificar se a instalação ocorreu de forma correta, digite o seguinte comando no seu terminal:

```shell
virtualenv --version
```
Terá como saída no terminal a seguinte informação:

```shell
virtualenv 20.0.28 from /home/usr/.local/lib/python3.8/site-packages/virtualenv/\_\_init\_\_.py
```

## **Criando uma Virtualenv**

Para criar uma virtualenv é muito fácil, basta ir para o diretório do projeto que você deseja criar a virtualenv e roda o seguinte comando no seu terminal:


```shell
virtualenv <Nome>
```

"nome" é o nome que você deseja dá a sua virtualenv, normalmente se coloca env.

Espere o processo de criação termionar, e você terá a sua primeira virtualenv, depois de rodado o código acima, você irá ver no diretório do seu projeto uma nova pasta com o nome que você colocou em sua virtualenv.

Até esse nomento nós apenas criamos a virtualenv, no entanto, para podemos utilizala devemos ativa-la, para isso demos correr o seguinte código no termial, abra um terminal na pasta do projeto, e rode:

```shell
 source nome-da-virtualenv/bin/activacte
```

Pronto, agora você tem sua virtualenv ativada e pronta para ser utilizada em seu projeto, agora todo pacote/lib/módulo que você instalar utilizando o pip irá ser instalado em sua virtalenv e estará disponível para esse projeto em explecifico.

Lembrando que caso você feche o terminal, e volte para dá continuidade em seu projeto você deve ativar sua virtualenv novamente seguindo o passo anterior.

## **Desativando e removendo Virtualenv**

caso você não deseje mais utilizar uma env, voçê pode desativar ou remove-la/deletar-la. Para desativa-lá basta fechar o terminal ou digitar no terminal o seguinte copmando:

```shell
deactivate
```

Caso você deseje remove-lá para sempre, digite o seguinte comando no terminal, dentro do diretório do projeto:

```shell
rm -r nome-da-virtualenv
```

Esperamos tê-lo(a) ajudado(a) a sanar suas dúvidas. Até o próximo post…









