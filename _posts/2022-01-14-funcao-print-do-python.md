---
date: 2022-01-10 12:36:40
layout: post
title: Função print() do Python
subtitle: Como usar a função print do python
description: Nesse pequeno Tutorial iremos aprender a usar a função print() do python para mostrar no console dados.
image: https://res.cloudinary.com/dlpu1d2ml/image/upload/v1642218280/enghash/print_ng7mjz.png
optimized_image: https://res.cloudinary.com/dlpu1d2ml/image/upload/c_scale,w_380/v1642218280/enghash/print_ng7mjz.png


category: python
tags:
  - python
  - pycharm

author: oseiasfarias
---

Aprenda a programar com Python:

<iframe width="100%" height="440" src="https://www.youtube.com/embed/videoseries?list=PL5jigOsyxDtCGEdY1I0Ymmv4lOyUkWbm2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


O Python é uma linguagem que está em alta por ser muito simples de se aprender, além disso, possue uma comunidade de desenvolvedores muito ativa que torna Python uma execelente linguagem para programadores iniciantes.

Hoje vamos aprender a usar a função `print()` para mostrar dados no console e tornar um script python muito mais interesante de se usar ao interagir com o usuário.

### **Saída de dados com a Função <span style="color:MediumSeaGreen">print()</span>**

print() é a função do python usada para imprimir dados no console.


#### **sintax**

```python
print(objeto(s), sep=separador, end=fim, file=arquivo)
```

#### **Explicação dos Parâmetros**

<div>
<table>
  <thead>
    <tr>
      <th>Parâmetro</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Objeto</td>
      <td>Qualquer objeto, e quantos você quiser. Será convertido em string antes de ser impresso.
      </td>
    </tr>
    <tr>
      <td>sep=separador</td>
      <td>Opcional. Especifique como separar os objetos, se houver mais de um. O padrão é ' '.
      </td>
    </tr>
    <tr>
      <td>end='end'</td>
      <td>Opcional. Especifique o que imprimir no final. O padrão é '\n' (quebra de linha).
      </td>
    </tr>
    <tr>
      <td>Arquivo</td>
      <td>Opcional. Um objeto com um método de gravação. O padrão é sys.stdout.
      </td>
    </tr>
  </tbody>
</table>
</div>

### **Exemplos**

```python
# Printando String
print("Olá mundo!")

# Printando um Cálculo Matemático
print("A soma 2+3 = ", 2+3)

# Printando várias String Separadas por ---
print("como", "vai", "você?", sep="---")

# Printando uma Lista Python
lista = ["pipoca", "laranja", "banana", "manga"]
print(lista)

# Utilizando print para gravar dados em arquivos
with open('arquivo.txt', 'w') as arquivo:
    print("Esse texto irá ser escrito em um Arquivo txt,", file=arquivo)
    print("Esse outro texto, também será escrito no arquivo txt", file=arquivo)
```

#### **Saída:**

<div>
<img style="padding-right: 30px; padding left: 30px;" src="../assets/img/posts_img/runpy.png"/>
</div>

<br>

Esperamos tê-lo(a) ajudado(a) a sanar suas dúvidas. Até o próximo post…



