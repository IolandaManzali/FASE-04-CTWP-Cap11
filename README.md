# FIAP - Faculdade de Informática e Administração Paulista

<p align="center">
<a href= "https://www.fiap.com.br/"><img src="assets/logo-fiap.png" alt="FIAP - Faculdade de Informática e Admnistração Paulista" border="0" width=40% height=40%></a>
</p>

<br>

# Nome do projeto - Implementando Algoritmos de Machine Learning com Scikit-Learn

![Designer.jpeg](https://github.com/IolandaManzali/FASE-04-CTWP-Cap11/blob/main/assets/cap3_fase4.png)



## Nome do grupo - Grupo 15

## 👨‍🎓 Integrantes: 
- <a href="https://www.linkedin.com/in/guilherme-dos-santos-barbosa-58397b176">Guilherme dos Santos Barbosa</a>
- <a href="https://www.linkedin.com/in/iolanda-helena-fabbrini-manzali-de-oliveira-14ab8ab0">Iolanda Helena Fabbrini Manzali de Oliveira</a>
- <a href="https://www.linkedin.com/company/inova-fusca">Murilo Carone Nasser</a> 
- <a href="https://www.linkedin.com/in/pedro-eduardo-soares-de-sousa-439552309">Pedro Eduardo Soares de Sousa</a> 
- <a href="https://www.linkedin.com/company/inova-fusca">Yago Brendon Iama</a>

## 👩‍🏫 Professores:
### Tutor(a) 
- <a href="https://www.linkedin.com/in/lucas-gomes-moreira-15a8452a">Lucas Gomes Moreira</a>
### Coordenador(a)
- <a href="https://www.linkedin.com/company/inova-fusca">Andre Godoi Chaviato</a>

## 📜 Descrição
Modelo Wokwi versão 1.2

<p align="justify">
 
Este projeto de Machine Learning desenvolvido para a quarta fase do Curso de Inteligência Artificial da FIAP propõe uma solução de aprendizado de máquina para automatizar a classificação de variedades dos três tipos de grãos de trigo do dataset selecionado, substituindo o processo manual atual. 

O escopo do projeto será realizado em  três etapas:
 * Análise e pré-processamento de dados, onde o dataset será tratado e padronizado objetivando redução de inconscistências e aumento de acurácia e precisão.
 * Implementação dos Algoritmos de Classificação para averiguação do modelo mais bem adaptado ao dataset
 * Otimização do resultados e ajuste de hiperparâmetros
 * Análise dos resultados
 
</p>

## 📁 Estrutura de pastas

Dentre os arquivos e pastas presentes na raiz do projeto, definem-se:

-  <b>assets</b>: imagens utilizadas no projeto

- <b>config</b>: arquivos de parâmetros e ajustes do projeto.

- <b>document</b>: documentos complementares do projeto

- <b>scripts</b>: scripts auxiliares

- <b>src</b>: código fonte principal

- <b>README.md</b>: FIAP FASE4. 

## 🔧 Como executar o código

### ACESSANDO O AMBIENTE

  * Acesse o Jupyter Notebook pelo site <https://jupyter.org/> ou pelo VSCode
  
  * Crie um pasta para armazenar os arquivos pertinentes ao projeto

  * Faça o upload do dataset "Seeds" atraves do link <https://archive.ics.uci.edu/dataset/236/seeds>

Se for utilizar o Jupyter Notebbok pelo site:

Abra um novo arquivo (File), crie e nomeie seu notebook

![nj](https://github.com/IolandaManzali/FASE-04-CTWP-Cap11/blob/main/assets/notebookj.png)

Se for utilizar o Jupyter Notebbok pelo VSCode:

 * Crie uma pasta na sua area de trabalho (ou no local de sua preferência)

 * Abra o VSCode

 * Cliqei em "New Folder" e abra essa pasta.

 * Crie um novo arquico dentro dessa pasta.

 * Faça o upload do dataset "Seeds" atraves do link <https://archive.ics.uci.edu/dataset/236/seeds>

![vsc](https://github.com/IolandaManzali/FASE-04-CTWP-Cap11/blob/main/assets/vscode.png)
    
### Algoritmos de Classificaçao

#### Importando as bibliotecas Python (Pandas, Seaborn, Numpy, Matplotlib e Plot)
obs: Casos essas bibliotecas não estejam instaladas na sua IDE, pode-se utilzar o comando pip install nome_biblioteca  n oseu terminal para que seja instalada

#### Importando os parâmetros da Biblioteca Sbikit-Learn (LabelEncoder, OneHotEncoder, MinMaxScaler, train_test_split)

#### Importando os Algoritmos de Classificação da Biblioteca SCIKIT-LEARN ( KNeighborsClassifier, LogisticRegression, SVC, DecisionTreeClassifier, RandomForestClassifier, accuracy_score, classification_report, confusion_matrix  make_classification, mean_squared_error, mean_absolute_error, r2_score)

#### Carregando o dataset e exibindo uma amostra do seu dataset

### Começando a análise exploratória

#### Exibindo resumos estatisticos e informativo do conjunto do dataset

#### Realizando o tratamento inicial dos dados (verificar se há dados ausentes ou duplicados e analisando presença outliers)

#### Explorando as relaçoes entre as variáveis (graficos pairplot)

#### Explorando a distribuição do labels

#### Explorando a correlaçaõ entre as features numéricas

#### Pré-processamento dos dados, com substituição dos valores dos outliers pela mediana

### Imprementação e Comparação do Algoritmos de Classificação

#### Separando Labels e Features

#### Atribuindo o Label Encoder para a variável alvo

#### Dividindo os dados em cxonjuntos de treino e teste 

#### Normalizando as features numericas para MinMaxScaler

#### Treinando os modelos

#### Comparando o desempenho dos modelos em relação aos algoritmos de classficação 

#### Otimizando os hiperparametros

#### Retreinando os modelos

### Analisando os resultados


## 🗃 Histórico de lançamentos

* 0.5.0 - XX/XX/2024
    * 
* 0.4.0 - XX/XX/2024
    * 
* 0.3.0 - XX/XX/2024
    * 
* 0.2.0 - 06/12/2024
    * 
* 0.1.0 - 13/11/2024
    *
  
## 📋 Licença

<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/agodoi/template">MODELO GIT FIAP</a> por <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://fiap.com.br">Fiap</a> está licenciado sobre <a href="http://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">Attribution 4.0 International</a>.</p>
