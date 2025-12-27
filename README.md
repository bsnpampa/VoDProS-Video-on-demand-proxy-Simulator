# VoDProS-Video-on-demand-proxy-Simulator

O VoDProS simula o fluxo do funcionamento de um servidor proxy VoD para extrair informações como a taxa de acertos do proxy, para diferentes cenários de carga e algorítmos de cacheamento.

###### Passos de instalação, configuração e execução:

Passo 1) Criar Ambienste virtual:
`python3 -m  venv ./env`

Passo 2) Ativar ambiente virtual:
`source ./env/bin/activate`

Passo 3) Instalar os seguintes pacotes:

OS-sys
`pip install os-sys `

Python-time
`pip install python-time`

Python-math
`pip install python-math`

Multiprocess
`pip install multiprocess`

###### Passos para executar o código:

Passo 1: #### PYTHON 3

    cd ./src/

    python3 main.py

ou, alternativamente, especificando:

    cd ./src/

    python3 main.py 1 1 1

1º argumento define o numero/nome do diretorio de leitura.
2º argumento define a variação dos parametros.
3º argumento define o número do algortimo que deseja utilizar na simulação.

### OBS
  Altere a variável `numeroThreadMax` que define o grau de paralelismo (quantidade de threads) que o simulador usará na simulação.

##### *OBS:* utilize o pypy3 como compilador para gerar um código mais eficiente (que executa em menor tempo).

## Video Tutorial

VoDProS- dicas para a primeira execução: https://youtu.be/QUK5pwUS6-o

###### Matheus Koch-
