# ConsumerMobility: Exploring Visit Patterns and Their Economic Impacts

Escrever resumo (depois de finalizar o artigo)

## 🚀 Começando

Essas instruções permitirão que você obtenha uma cópia do projeto em operação na sua máquina local para fins de desenvolvimento e teste.

Consulte **[Implantação](#-implanta%C3%A7%C3%A3o)** para saber como implantar o projeto.

### 📋 Pré-requisitos

Bases de dados:
Base 1) Dados privados - Logan AI (solicitar para o autor no e-mail rafaelpalbuquerque@hotmail.com);
Base 2) 2927408_salvador_setores_2021.geojson (fonte: https://dados.salvador.ba.gov.br/datasets/467ac1de99654030890d0af21724e1d3/explore?location=-12.998218%2C-38.522777%2C14.00)
Base 3) IDESH_-_Setores_Censit%C3%A1rios_do_IBGE_2010.csv (fonte: https://dados.salvador.ba.gov.br/datasets/467ac1de99654030890d0af21724e1d3/explore?location=-12.998218%2C-38.522777%2C14.00)


### 🔧 Instalação

Seguir passos do jupyter notebook Trabalho final ML.ipynb
O notebook está disponível no link: https://github.com/RPAlbuquerque/Machine-Learning-PPGA-UFRGS/blob/main/Trabalho%20final%20ML.ipynb


## ⚙️ Executando os testes

Os algoritmos e testes seguem a lógica a seguir:
1) Upload de bases (Base 1 'df', Base 2 'gdf' e Base 3 'sdf')
2) Códigos:
   - Análise Geoespacial;
   - Feature Engineering;
   - Estatística descritiva (análises demográficas);
   - Integração de dados Geoespaciais;
   - Visualização de dados Geoespaciais;
   - Mapa Interativo;
   - Testes de Correlação (pearson);
3) Algoritmos de ML:
    * REGRESSÃO - APRENDIZADO SUPERVISIONADO
   - Regressão Linear (Previsão de 'new_visits' com base nas features: 'visits', 'unique', 'repeat_visitors', 'dwell_time_mins')
 4) Modelo de referência;
 5) Model Evaluation:
   - Mean Squared Error;
   - R²;
   - Cross Validation;
 6) Learning Curve;
 7) Plots;
 8) Análise de Resíduos;
 9) Teste de Shapiro-Wilk e Anderson-Darling;
 10) Baseline (reference model);
 11) Nova Correlação (todos atributos utilizados no modelo de regressão linear);
 12) Análise Visual;
     NOVO TESTE:
13) Algoritmos de ML:
    * REGRESSÃO - APRENDIZADO SUPERVISIONADO
   - Random Forest Regression (Previsão de 'new_visits' com base nas features: 'visits', 'unique', 'repeat_visitors', 'dwell_time_mins')
14) Visualização da importância de cada variável.

## 📌 Versão

Foi utilizado [SemVer](http://semver.org/) para controle de versão. Para as versões disponíveis, observe as [tags neste repositório](https://github.com/suas/tags/do/projeto). 

## ✒️ Autores

Rafael Albuquerque - PPGA/UFRGS
Vinícius Brei - PPGA/UFRGS


## 🎁 Expressões de gratidão

Obrigado à todos que participaram do projeto.

Para maiores informações, entrar em contato pelo e-mail rafaelpalbuquerque@hotmail.com


---
⌨️ com ❤️ por [Rafael Albuquerque](https://github.com/RPAlbuquerque) 😊
