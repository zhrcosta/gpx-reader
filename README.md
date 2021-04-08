[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/cauachagas/gpx-reader/HEAD?filepath=reader.iypnb)


# Geolocalização + Python

Nesse notebook um traçado colorido da rota gravada associado a velocidade. Também é analisado os pontos de parada e o tempo em cada um, criando círculos vermelhos nesses pontos.

## Reproduzindo o projeto

A forma mais fácil é usando o excelente serviço chamado `Binder`. Ele pode transformar nosso repositório numa imagem `Docker` e roda um container que fica disponível por um determinado tempo. Muito útil para Jupyter Notebooks das mais diversas linguagens.


### Instalando localmente

Sempre que possível, crie um ambiente de desenvolvimento. É uma forma simples para garantir que os pacotes instalados fiquem somente no ambiente, não alterando os pacotes oficiais do sistema.


Com o pacote `virtualenv` podemos criar um ambiente `geopython` dessa seguinte maneira

```bash
python3 -m venv geopython
```
Depois podemos ativá-lo 

```bash
. geopython/bin/activate
```

Em seguida, instale os pacotes necessários no ambiente ativado

```bash
pip3 install -r requirements.txt
```

Há outras possibilidades para criar ambientes, que servem também para outras linguagens, como `conda` ou `micromamba`, mas não serão abordados aqui.


### Abrindo o Jupyter Notebook

Com os pacotes instalados

```bash
jupyter-notebook reader.ipynb
```

[Preview](https://nbviewer.jupyter.org/github/zhrcosta/gpx-reader/blob/master/reader.ipynb)