# LH_CD_RUANN_CAMPOS_DE_CASTRO_FARRAPO
## Desafio Indicium - Ciência de Dados

Nesse repositório foi realizada uma análise exploratória da base de dados dos filmes, além do desenvolvimento de um modelo de predição que prever a nota de avaliação IMDb dos filmes, como foi requerido. 

## Como rodar o projeto? 
A forma mais simples de rodar o projeto é utilizando o serviço Google Colab. 

É necessário ter uma conta google e entrar no site: https://colab.research.google.com/

Depois desse passo, deve-se ir na aba Upload, e escolher o arquivo que você deseja executar ( Notebook_EDA.ipynb, Notebook_Modelagem.ipynb)

Ao abrir o arquivo no ambiente do Colab, vá na aba Arquivos na lateral esquerda e faça o upload das bases de dados desafio_indicium_imdb.csv

As bibliotecas utilizadas já estão instaladas por padrão no ambiente do Colab.

Outra forma de rodar o projeto é utilizar o programa Jupyter, que vai ler os notebooks do projeto. Para executar nesse ambiente, você deve instalar as bibliotecas no ambiente que será executado os notebooks. Para instalar use: pip install -r requirements.txt.

## Requirements   
As bibliotecas utilizadas foram: 
- pandas: para manipulação das bases de dados
- matplotlib e seaborn: para plotar os gráficos e histogramas
- scikit-learn: para utilizar os modelos de aprendizagem de máquina, além dos pré-processamentos e métricas de performance
- numpy: para manipulação dos dados
- ipywidgets: para criar controles interativos, como botões, caixas de seleção, auxiliando a manipulação de dados dinamicamente
- wordcloud: para criar visualizações de nuvem de palavras a partir de um conjunto de textos 
- ipython: para exibir imagens dentro do notebook
- joblib: para salvar o modelo desenvolvido no formato .pkl

## Arquivos
- **Notebook_EDA.ipynb:** Arquivo notebook com a primeira parte da entrega, que corresponde à construção da análise exploratória dos dados(EDA) e as respostas dos questionamentos.
- **Notebook_Modelagem.ipynb:** Arquivo notebook a segunda e última parte da entrega, que corresponde à construção das modelagens e previsões requeridas.
- **avaliacao_imdb_model.pkl:** Modelo desenvolvido salvo em formato .pkl, como requerido.
- **requirements.txt:** Bibliotecas necessárias para rodar o projeto.
- **Gráfico_Overview.png:** Imagem de apresentação do gráfico interativo da coluna 'Overview'.
- **desafio_indicium_imdb.csv:** Base de dados utilizada no projeto.