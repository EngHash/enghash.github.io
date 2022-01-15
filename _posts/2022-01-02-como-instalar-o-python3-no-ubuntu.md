---
date: 2021-02-27 12:26:40
layout: post
title: Como Instalar o Python3.10 no Ubuntu
subtitle: Instalando o Python3.10 sem interferir as outras versões.
description: Nessa postagem vamos aprender a instalar o Python3.10 no Ubuntu e seus Derivados.
image: https://res.cloudinary.com/dlpu1d2ml/image/upload/v1641740760/enghash/run_python3_vr5gf9.png
optimized_image: https://res.cloudinary.com/dlpu1d2ml/image/upload/c_scale,w_380/v1641740760/enghash/run_python3_vr5gf9.png

category: code
tags:
  - python
  - debian
  - linux
  - ubuntu

author: oseiasfarias
---

Vídeo Tutorial no nosso Canal no YouTube:

<div class="embad">
    <iframe width="100%" height="440" src="https://www.youtube.com/embed/XACgnZ5t3DY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>


## **Instalando Bibliotecas Necessárias para Compilar o Python**

Antes de iniciarmos a compilação do Python precisamos verificar se algumas bibliotecas estão instaladas na sua Máquina Linux.

Para isso digite o seguinte comando:

```shell
sudo apt install build-essential checkinstall
```

Vamos instalar outras bibliotecas que também nos ajudaram a compilar o Python

Para isso digite o seguinte comando:

```shell
sudo apt install libreadline-gplv2-dev libncursesw5-dev libssl-dev libsqlite3-dev tk-dev libgdbm-dev libc6-dev libbz2-dev libffi-dev zlib1g-dev
```

Agora vá para o diretório opt:

```shell
cd /opt
```

Dentro do diretório, baixe o arquivo que usaremos para compilar o Python:


```shell
sudo wget https://www.python.org/ftp/python/3.10.0/Python-3.10.0.tar.xz
```

Para ter a versão mais recente, visite o site.

Agora extraia os arquivos usando o seguinte comando:


```shell
sudo tar -xvf Python-3.10.0.tar.xz
```

Agora vamos para dentro da pasta que extraimos os arquivos, para isso use o seguinte comando:

```shell
cd Python-3.10.0
```

E agora vamos otimozar a compilação do Python para o seu Sistema Operacional com o seguinte comando:

```shell
sudo ./configure --enable-optimizations
```

Por fim, vamos fazer a compilação do Python3.10, é muito importante colocar o comando <b>altinstall</b> pois é usado para impedir que o programa compilado tome o lugar padrão do arquivo binário python em /usr/bin/python.:

```shell
sudo make altinstall
```

Agora você pode verificar se a instalação foi bem sucesida como o comando abaixo:

```shell
python3.10 --version
```

Com a instalação finalizada, você pode voltar a pasta /opt e apagar o arquivo baixado:

```shell
cd /opt
    
sudo rm Python-3.10.0.tar.xz
```

Esperamos tê-lo(a) ajudado(a) a sanar suas dúvidas. Até o próximo post…


