# Análise de Dados de Fraude

## Acesso ao dados

Este é um projeto que engloba a análise de dados de endereços da blockchain Ethereum e a criação de modelo Random Forest para definição de fraude. O texto a seguir explica com mais detalhes o que foi feito.

Os dados utilizados podem ser obtidos em: https://www.kaggle.com/datasets/vagifa/ethereum-frauddetection-dataset

## Introdução

O Ethereum é uma blockchain criada em 2015 por Vitalik Buterin e outros desenvolvedores e sua criptomoeda nativa é o Ether. Além de ter se consagrado como uma das blockchains mais utilizadas, configurando uma alternativa ao Bitcoin, o Ether é, de acordo com o portal InfoMoney, a segunda moeda digital mais valiosa, sendo cotada (09/03/2025) a 2.189,39 dólares. Por se tratar de uma plataforma em que ocorre a tranferência de valores, o Ethereum, assim como o sistema bancário tradicional, pode ser empregado na realização de fraudes e gerar prejuízos dos mais variados tipos e magnitudes. Relembrando o caso DAO, em 2016, quando hackers se aproveitaram de suscetibilidades e roubaram 150 milhões de dólares em ethers, não é difícil compreender a importância do controle das transações com o objetivo de inibir atividades maliciosas e a perda de valores.

## Objetivo 

A finalidade deste projeto foi, com o intuíto de promover o aprendizado em análise de dados e criação de modelos de machine learning, explorar, sob diferentes aspectos, dados de carteiras Ethereum rotuladas como fraudulentas e não fraudulentas. As análises feitas permitiram delinear melhor o perfil das carteiras e compreender de que forma as características e hábitos transacionais ajudam na definição de um endereço fraudulento. Os dados foram obtidos no repositório Kaggle e não há informações sobre serem fictícios, ou não.

## Solução

O projeto foi desenvolvido por meio da linguagem Python, utilizando a interface Jupyter Lab e aplicando o algoritmo de modelo Random Forest. O trabalho divide-se em três etapas: a de ETL (Extract, Transform, Load), EDA (Exploratory Data Analysis) e construção de modelo. 
No decorrer da fase de ETL foi carregado o arquivo .csv, salvando-o em um DataFrame Pandas, além de efetuar alterações no formato dos dados. 
Após, na fase de EDA, para guiar a abordagem dos dados, foram definidos seis tópicos de exploração e aplicados recursos diagnósticos como a execução do teste estatístico Kolmogorov-Smirnov (KS), a divisão das variáveis em decis e o cálculo de probabilidade.
Por fim, na terceira etapa do projeto, foi construído o modelo, bem como avaliada sua acurácia, por meio do Índice de Gini, e avaliada, utilizando o algoritmo Shap, a relevância de cada variável nas predições.

## Conclusões

Após concluir o projeto, as principais conclusões obtidas foram:

1.Uma estratégia dos fraudadores é realizar um número alto de transações com valores baixos, ao invés de enviar valores muito altos efetuando poucas transações;

2.Outra estratégia é, nas transações envolvendo tokens, realizar repasses de valores a partir de uma baixa diversidade de tokens;

3.O modelo Random Forest atende bem a demanda, revelando-se uma ferramenta robusta no aprendizado e classificação das carteiras.


