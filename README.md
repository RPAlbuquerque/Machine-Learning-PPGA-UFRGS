# Consumer Mobility: Exploring Visit Patterns and Their Economic Impacts

Write the abstract (after finishing the article)

## 🚀 Getting Started

These instructions will allow you to get a copy of the project up and running on your local machine for development and testing purposes.

See **[Deployment](#-deployment)** to learn how to deploy the project.

### 📋 Prerequisites

Database:
Base 1) Private Data - Logan AI (request from the author at rafaelpalbuquerque@hotmail.com);
Base 2) 2927408_salvador_setores_2021.geojson (source: https://dados.salvador.ba.gov.br/datasets/467ac1de99654030890d0af21724e1d3/explore?location=-12.998218%2C-38.522777%2C14.00)
Base 3) IDESH_-_Setores_Censit%C3%A1rios_do_IBGE_2010.csv (source: https://dados.salvador.ba.gov.br/datasets/467ac1de99654030890d0af21724e1d3/explore?location=-12.998218%2C-38.522777%2C14.00)


### 🔧 Installation

Follow the steps in the jupyter notebook Final ML Project.ipynb
The notebook is available at: https://github.com/RPAlbuquerque/Machine-Learning-PPGA-UFRGS/blob/main/Trabalho%20final%20ML.ipynb


## ⚙️ Running the Tests

The algorithms and tests follow the logic below:
1) Upload databases (Base 1 'df', Base 2 'gdf', and Base 3 'sdf')
2) Codes:
   - Geospatial Analysis;
   - Feature Engineering;
   - Descriptive Statistics (demographic analyses);
   - Geospatial Data Integration;
   - Geospatial Data Visualization;
   - Interactive Map;
   - Correlation Tests (pearson);
3) ML Algorithms:
    * REGRESSION - SUPERVISED LEARNING
   - Linear Regression (Prediction of 'new_visits' based on the features: 'visits', 'unique', 'repeat_visitors', 'dwell_time_mins')
 4) Reference Model;
 5) Model Evaluation:
   - Mean Squared Error;
   - R²;
   - Cross Validation;
 6) Learning Curve;
 7) Plots;
 8) Residual Analysis;
 9) Shapiro-Wilk and Anderson-Darling Test;
 10) Baseline (reference model);
 11) New Correlation (all attributes used in the linear regression model);
 12) Visual Analysis;
     NEW TEST:
13) ML Algorithms:
    * REGRESSION - SUPERVISED LEARNING
   - Random Forest Regression (Prediction of 'new_visits' based on the features: 'visits', 'unique', 'repeat_visitors', 'dwell_time_mins')
14) Visualization of the importance of each variable.

## 📌 Version

[SemVer](http://semver.org/) was used for version control. For available versions, see the [tags in this repository](https://github.com/suas/tags/do/projeto). 

## ✒️ Authors

Rafael Albuquerque - PPGA/UFRGS
Vinícius Brei - PPGA/UFRGS


## 🎁 Acknowledgments

Thanks to everyone who participated in the project.

For more information, contact rafaelpalbuquerque@hotmail.com


---
⌨️ with ❤️ by [Rafael Albuquerque](https://github.com/RPAlbuquerque) 😊
