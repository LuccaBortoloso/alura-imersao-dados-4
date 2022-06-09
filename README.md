# Imersão de Dados 4 - Alura

A 4° edição da Imersão de Dados da Alura foi realizada nos dias 23 à 27 de maio e foi um oferecimento da Alura em conjunto com a Creditas.
O projeto que foi desenvolvido buscou prever o valor de um imóvel na cidade de São Paulo, através de um algoritmo de Regressão Linear.

Tabela de conteúdos
=================
<!--ts-->
   * [Sobre](#Sobre)
   * [Requisitos](#Requisitos)
   * [Instalação](#Instalação)
   * [Conteúdo das aulas](#Conteúdo-das-aulas)
      * [Aula 01](#Aula-01)
      * [Aula 02](#Aula-02)
      * [Aula 03](#Aula-03)
      * [Aula 04](#Aula-04)
      * [Aula 05](#Aula-05)
   * [Ferramentas e tecnologias utilizadas](#Ferramentas-e-tecnologias-utilizadas)
<!--te-->

# Sobre

O projeto foi desenvolvido tanto em notebook tanto localmente, utilizando o [Jupyter Notebook](https://jupyter.org/), quanto remotamente com o [Google Colab](https://colab.research.google.com/).
O objetivo do projeto foi prever o valor de um imóvel na cidade de São Paulo, com base em alguns parâmetros desses imóveis. Embora o projeto tenha sido desenvolvido pela [Alura](https://www.alura.com.br/) em conjunto com a [Creditas](https://www.creditas.com/),
o _dataset_ base foi retirado de um desafio do [Kaggle](https://www.kaggle.com/datasets/kaggleshashankk/house-price-data-of-sao-paulo).

# Requisitos

Todos os requisitos estão disponíveis no arquivo ```requirements.txt```.

# Instalação

Para instalação dos requisitos, ao iniciar o prompt de comando no diretório do projeto basta executar o seguinte comando:

```pip install -r requirements.txt```

# Conteúdo das aulas

## Aula 01

Aula introdutória sobre Google Colab e primeiro contato com Python e Pandas. Observando e entendendo as características gerais dos dados.

## Aula 02

Nesta aula, as análises foram avançando conforme os dados iam sendo tratados. Além disso, foram utilizadas as bibliotecas Matplotlib e Seaborn para visualização e plotagem de gráficos que pudessem ampliar as análises.
A aula abordou assuntos de estatística, visualização de dados e tratamento de dados.

## Aula 03

Esta foi uma aula para explorar mais os dados e suas estatísticas. Fez-se necessário o uso de técnicas de _feature engineer_ para criar novas variáveis que pudessem agregar ao _dataset_ proposto, como forma de enriquecer a qualidade das análises.
Para isso, um _dataset_ disponível com dados do IBGE foi agregado ao _dataset_ original. Além do tratamento de _outliers_ que poderiam prejudicar as análises.

## Aula 04

A aula 04 foi a aula mais complexa, visto a dificuldade do assunto, pois nesta aula foram cruzadas diversas base de dados a fim de gerar um único _dataset_ que trouxesse características do imóvel, quanto da
região socioeconômica que esse imóvel se encontra. Desta forma, conseguimos analisar o valor do imóvel baseado nas características sociais e econômicas da região.

## Aula 05

A aula de encerramento da imersão teve o foco no aprendizado de máquina. Foram abordadas as diferenças entre os problemas de classificação e regressão, como treinar um modelo de _machine learning_ utilizando o Scikit Learn
e por fim, quais as métricas possíveis para validar o modelo de regressão utilizado.

# Ferramentas e tecnologias utilizadas
<img src="https://cdn3.iconfinder.com/data/icons/logos-and-brands-adobe/512/267_Python-512.png" width="80" height="80"/>          <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/38/Jupyter_logo.svg/883px-Jupyter_logo.svg.png" width="80" height="80"/>         <img src="https://colab.research.google.com/img/colab_favicon_256px.png" width="80" height="80"/>         <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/05/Scikit_learn_logo_small.svg/2560px-Scikit_learn_logo_small.svg.png" width="140" height="80"/>         <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/ed/Pandas_logo.svg/512px-Pandas_logo.svg.png?20200209204934" width="140" height="80"/>         <img src="https://seaborn.pydata.org/_images/logo-tall-lightbg.svg" width="80" height="80"/>          <img src="https://geopandas.org/en/stable/_images/geopandas_logo.png" width="160" height="80"/>         <img src="https://matplotlib.org/3.1.1/_static/logo2_compressed.svg" width="120" height="80"/>          <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" width="80" height="80"/>
