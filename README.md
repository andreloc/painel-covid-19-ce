# Análise Exploratória do COVID-19 no Estado do Ceará

O objetivo desse projeto é realizar um workshop para todos que desejem aprender python e utilizá-lo para explorar dados. 
A idéia é utiliza as informações do COVID-19 do estado do Ceará disponibilizados na base do [IntegraSUS](https://integrasus.saude.ce.gov.br/).

O Workshop será apresentado no [Open Data Day Fortaleza](https://www.facebook.com/opendatadayfortaleza/) que ocorrerá no dia 11/04/2020. 

Fontes de Informação: 
- [Corona Virus Ceará](https://indicadores.integrasus.saude.ce.gov.br/indicadores/indicadores-coronavirus/coronavirus-ceara)

- [Conjunto de APIs](https://github.com/EscolaDeSaudePublica/coronavirusAPI/issues/17)

## Organização do Tutorial 

 1) Instalaçãpo do Ambiente  
 2) Configuração do Ambiente
 3) Extração de dados e formação dos DataSets
 4) Limpeza dos dados 
 5) Visualização de dados 

## Instalação do Ambiente

Iremos utilizar o [Anaconda](https://www.anaconda.com/why-anaconda/), um ambiente completo para desenvolvimento de trabalhos de Ciência de Dados que torna fácil o controle de dependências e compartilhamento de trabalhos entre distintintos sistemas Operacionais. 

Esse ambiente facilita muito a instalação de dependências e de ferramentas para desenvolver estudos de todos os tipos em Data Science. Tanto pode ser utilizado para desenvolvimento em [R](https://www.r-project.org/) ou [Python](https://www.python.org/). 

Como linguagem, iremos utilizar [Python](https://www.python.org/). 

Para estudos e exploração, iremos utilizar [Jupyter](https://jupyter.org/). 

Para plotar resultados, iremos utilizar a lib [Plotly](https://plotly.com/).

### Passos: 
 1. __Executar procedimentos de instalação descritos no link abaixo:__ 

> [Instalação Anaconda](https://docs.anaconda.com/anaconda/install/)
Observer que pode selecionar as intruções de acordo com seu sistema operacional. 

![Instalacao](resources/install_anaconda.png)

> Escolher a opção Python 3.7 e 64-Bit. 

 2. __Após finalizar a instalação, iniciem o navegador do Anaconda (Anaconda Navigator).__

 3. __Crie um novo ambiente de desenvolvimento do seu projeto. Utilizei covid-19-ce.__

![Create Environment](resources/create_environment_anaconda.gif)

 >Esse ambiente é uma forma de isolar todo seu desenvolvimento e conjunto de bibliotecas. 
 
3. __Instalar o Jupyter Notebook__

![Installar Jupyter](resources/install_jupyter.gif)

4. __Espere finalizar a instalação e inicie o Jupyter__

O Jupyter é uma aplicação web na qual você pode criar em um documento que inclui scripts juntos com explicações dos passos que estão sendo executados. 
Ver sintaxe de [Markdown](https://pt.wikipedia.org/wiki/Markdown)

## Configuração de dependências 

TODO