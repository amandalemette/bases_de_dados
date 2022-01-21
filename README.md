## bases_de_dados

Esse repositório contém as bases de dados que uso durante as aulas de Programação de Python. 

## 1. International football results from 1872 to 2021

[Acesso a base de dados no Kaggle](https://www.kaggle.com/martj42/international-football-results-from-1872-to-2017)

A base de dados *results.csv* inclui dados de 40838 resultados de partidas de futebol começando em 1872 até 2021. Os dados não incluem jogos olímpicos. 

Colunas de dados incluem:

- data – dia da partida
- time da casa
- time convidado
- pontuação do time da casa
- pontuação do time convidado
- classificação do torneio
- cidade onde ocorreu a partida
- país onde ocorreu a partida
- neutro - TRUE/FALSE Coluna indicando se a partida foi feita em um local neutro



<p align="center">
<img src="https://github.com/amandalemette/Visualizacao-de-Dados-em-Python/blob/298a631c27f66a487eafd5a274552b2adf7a9c17/Images/section_divider3.png?raw=true"/>
</p>

# 2. Chronic Kidney Disease dataset
Data has 25 feattures which may predict a patient with chronic kidney disease

[Acesso a base de dados no Kaggle](https://www.kaggle.com/mansoordaku/ckdisease)

<h2 id="Acesso ao arquivo .csv já tratado"><a href="https://github.com/amandalemette/bases_de_dados/blob/0c3c8c8926fa2031f3770b787e036e0aab8ba3a7/02_Chronic%20Kidney%20Disease/ckdisease.csv">Acesso ao arquivo .csv já tratado</a></h2>

Para fazer o download somente desse arquivo aqui no GitHub, acesse o link: https://bit.ly/3Guen8J

Essa base de dados contém muitos dados faltantes. 

A base de dados foi construída em um período de 2 meses na India e contém 25 atributos:

- 'age', 
- 'blood_pressure', 
- 'specific_gravity', 
- 'albumin', 
- 'sugar', 
- 'red_blood_cells', 
- 'pus_cell',
- 'pus_cell_clumps', 
- 'bacteria', 
- 'blood_glucose_random', 
- 'blood_urea', 
- 'serum_creatinine', 
- 'sodium',
- 'potassium', 
- 'haemoglobin', 
- 'packed_cell_volume', 
- 'white_blood_cell_count', 
- 'red_blood_cell_count',
- 'hypertension', 
- 'diabetes_mellitus', 
- 'coronary_artery_disease', 
- 'appetite', 
- 'peda_edema',
- 'aanemia', 
- 'class'

O objetivo é classificar cada registro como 'ckd' ou 'notckd' onde ckd significa doença de rim crônica (chronic kidney disease).

Temos 400 registros no total. 

Excelente pré-tratamento feito a essa base de dados: https://www.kaggle.com/equinxx/chronic-kidney-disease-prediction-eda

<p align="center">
<img src="https://github.com/amandalemette/Visualizacao-de-Dados-em-Python/blob/298a631c27f66a487eafd5a274552b2adf7a9c17/Images/section_divider3.png?raw=true"/>
</p>

# 3. Fuel Efficiency Dataset

<h2 id="Acesso ao arquivo .csv"><a href="https://github.com/amandalemette/bases_de_dados/blob/a8d8816dc4fad138dd1b4ee672f836912e0ebf52/03_FuelEfficiency/FuelEfficiency.csv">Acesso ao arquivo .csv</a></h2>
Download direto da base de dados: https://downgit.github.io/#/home?url=https://github.com/amandalemette/bases_de_dados/blob/a8d8816dc4fad138dd1b4ee672f836912e0ebf52/03_FuelEfficiency/FuelEfficiency.csv

Dados armazenados no arquivo:

- Mfr Name = empresa que fez o carro
- Carline = marca do carro
- Eng Displ = Cilindrada do motor
- Cylinders = quantos cilindros o carro possui
- Transmission = tipo de transmissão
- MPG = Miles per gallon
- CityMPG = milhas da cidade por galão
- HwyMPG = milhas rodoviárias por galão
- CombMPG = City+Hwy
- gears = número de marchas que o carro tem


<p align="center">
<img src="https://github.com/amandalemette/Visualizacao-de-Dados-em-Python/blob/298a631c27f66a487eafd5a274552b2adf7a9c17/Images/section_divider3.png?raw=true"/>
</p>


# 4. World Happiness Report

O Relatório de Felicidade Mundial é uma pesquisa histórica do estado de felicidade global. O primeiro relatório foi publicado em 2015. O World Happiness 2017, que classifica 155 países por seus níveis de felicidade, foi lançado nas Nações Unidas em um evento que celebra o Dia Internacional da Felicidade em 20 de março. O relatório continua a ganhar reconhecimento global à medida que governos, organizações e sociedade civil usam cada vez mais indicadores de felicidade para informar suas decisões de formulação de políticas. Os principais especialistas em todos os campos - economia, psicologia, análise de pesquisas, estatísticas nacionais, saúde, políticas públicas e muito mais - descrevem como as medições de bem-estar podem ser usadas de forma eficaz para avaliar o progresso das nações. Os relatórios analisam o estado da felicidade no mundo hoje e mostram como a nova ciência da felicidade explica as variações pessoais e nacionais da felicidade.

Acesso a base de dados no Kaggle: https://www.kaggle.com/mathurinache/world-happiness-report-20152021

Cada arquivo csv contém 12 colunas:

- 'Country'
- 'Region'
- 'Happiness Rank' 
- 'Happiness Score'
- 'Standard Error'
- 'Economy (GDP per Capita)'
- 'Family'
- 'Health (Life Expectancy)'
- 'Freedom'
- 'Trust (Government Corruption)'
- 'Generosity'
- 'Dystopia Residual'

Quais são os resíduos?

Os resíduos, ou componentes não explicados, diferem para cada país, refletindo até que ponto as seis variáveis (Economy (GDP per Capita), Family, health, freedom, trust, generosity) super ou subexplicam as avaliações de vida médias.

A métrica de distopia residual é, na verdade, a pontuação de felicidade da distopia + o valor residual para cada país.

<p align="center">
<img src="https://github.com/amandalemette/Visualizacao-de-Dados-em-Python/blob/298a631c27f66a487eafd5a274552b2adf7a9c17/Images/section_divider3.png?raw=true"/>
</p>

# 5. Pima Indians Diabetes Database

Acesso a base de dados no Kaggle:  https://www.kaggle.com/uciml/pima-indians-diabetes-database

<h2 id="Acesso ao arquivo .csv"><a href="https://github.com/amandalemette/bases_de_dados/blob/52fb600ba9ae57dd7a2967b89ba8a10106699011/05_Pima_Indians_Diabetes/diabetes.csv">Acesso ao arquivo .csv</a></h2>
Download direto da base de dados: https://downgit.github.io/#/home?url=https://github.com/amandalemette/bases_de_dados/blob/52fb600ba9ae57dd7a2967b89ba8a10106699011/05_Pima_Indians_Diabetes/diabetes.csv


It is a binary classification problem (onset of diabetes as 1 or not as 0). The input variables that describe each patient are numerical and have varying
scales. Below lists the eight attributes for the dataset:

1. Number of times pregnant.
2. Plasma glucose concentration a 2 hours in an oral glucose tolerance test.
3. Diastolic blood pressure (mm Hg).
4. Triceps skin fold thickness (mm).
5. 2-Hour serum insulin (mu U/ml).
6. Body mass index.
7. Diabetes pedigree function.
8. Age (years).
9. Class, onset of diabetes within five years.


<p align="center">
<img src="https://github.com/amandalemette/Visualizacao-de-Dados-em-Python/blob/298a631c27f66a487eafd5a274552b2adf7a9c17/Images/section_divider3.png?raw=true"/>
</p>

# 6. Iris Dataset

Acesso à base: http://archive.ics.uci.edu/ml/machine-learning-datasets/iris/iris.data

This dataset is well studied and is a good problem for practicing on neural networks because
all of the 4 input variables are numeric and have the same scale in centimeters. Each instance
describes the properties of an observed flower measurements and the output variable is specific
iris species. The attributes for this dataset can be summarized as follows:

1. Sepal length in centimeters.
2. Sepal width in centimeters.
3. Petal length in centimeters.
4. Petal width in centimeters.
5. Class.

<p align="center">
<img src="https://github.com/amandalemette/Visualizacao-de-Dados-em-Python/blob/298a631c27f66a487eafd5a274552b2adf7a9c17/Images/section_divider3.png?raw=true"/>
</p>

# 7. Sonar dataset

Acesso à base: https://archive.ics.uci.edu/ml/machine-learning-databases/undocumented/connectionist-bench/sonar/sonar.all-data

This is a dataset that describes
sonar chirp returns bouncing o↵ di↵erent surfaces. The 60 input variables are the strength of
the returns at di↵erent angles. It is a binary classification problem that requires a model to
di↵erentiate rocks from metal cylinders.



<p align="center">
<img src="https://github.com/amandalemette/Visualizacao-de-Dados-em-Python/blob/298a631c27f66a487eafd5a274552b2adf7a9c17/Images/section_divider3.png?raw=true"/>
</p>

# 8. Boston House Prices

Acesso à base: https://archive.ics.uci.edu/ml/machine-learning-databases/housing/housing.data
 
The dataset describes properties of houses in Boston suburbs and is concerned with modeling the price of
houses in those suburbs in thousands of dollars. As such, this is a regression predictive modeling
problem. There are 13 input variables that describe the properties of a given Boston suburb.
The full list of attributes in this dataset are as follows:
1. CRIM: per capita crime rate by town.
2. ZN: proportion of residential land zoned for lots over 25,000 sq.ft.
3. INDUS: proportion of non-retail business acres per town.
4. CHAS: Charles River dummy variable (= 1 if tract bounds river; 0 otherwise).
5. NOX: nitric oxides concentration (parts per 10 million).
6. RM: average number of rooms per dwelling.
7. AGE: proportion of owner-occupied units built prior to 1940.
8. DIS: weighted distances to five Boston employment centers.
9. RAD: index of accessibility to radial highways.
10. TAX: full-value property-tax rate per 10,000.
11. PTRATIO: pupil-teacher ratio by town.
12. B: 1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town.
13. LSTAT: % lower status of the population.
14. MEDV: Median value of owner-occupied homes in 1000s.


<p align="center">
<img src="https://github.com/amandalemette/Visualizacao-de-Dados-em-Python/blob/298a631c27f66a487eafd5a274552b2adf7a9c17/Images/section_divider3.png?raw=true"/>
</p>
