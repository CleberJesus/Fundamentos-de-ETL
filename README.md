# Fundamentos-de-ETL

## Pandas

## Extrair, transformar e carregar
### df.head() // visualização
### df.shape // linhas x colunas
### df.info() //formato que se encontram os dados em cada coluna, além da memória
### df.columns // nomes das colunas
#### df.columns = ['id', 'data','valor_un']
### df.isnull().sum() // dados faltantes
### df['setor'].unique() //valores unicos existentes naquela coluna
### df['setor'].value_counts.plot(kind='bar') // matplotlib// gerar visualização gráfica
### df.describe() //informações estastísticas


## Scikit-learn

### from sklearn.datasets import make_regression
#### gerando uma massa de dados
### x,y = make_regression(n_samples=200, n_features=1, noise=30)


### import matplotlib.pyplot as plt

#### mostrando o gráfico
### plt.scatter(x,y) // criando o gráfico
### plt.show() // mostrando o gráfico

## Criando modelo de machine learning

### from sklearn.linear_model import LinearRegression
#### criando modelo
### modelo = LinearRegression() // pronto para receber os dados

### modelo.predict(x)



