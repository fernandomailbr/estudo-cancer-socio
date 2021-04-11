# Projeto Condições socioeconômicas e câncer de mama: estudo de correlação. 
# Project Socioeconomic conditions and breast cancer: correlation study

# Apresentação

O presente projeto foi originado no contexto das atividades da disciplina de pós-graduação [*Ciência e Visualização de Dados em Saúde*](https://github.com/datasci4health/home), oferecida no primeiro semestre de 2021, na Unicamp.

| Nome           | RA        | Especialização |
|----------------|-----------|----------------|
| Aline Borges   | 210598    | Saúde          |
| Edgar Tanaka   | 023577    | Computação     |
| Fernando Akune | 970709    | Computação     |
| Lana Soares    | 209580    | Saúde          |
| Tiago Andrade  | (ouvinte) | Saúde          |


# Descrição Resumida do Projeto
O câncer de mama é o tipo de câncer mais frequente nas mulheres, sem considerar o câncer de pele não melanoma. Apesar de todas as campanhas de conscientização, como o Outubro Rosa, o número de casos continua grande, estimativa de 66.280 em 2020 (segundo o INCA), e principalmente com uma alta taxa de letalidade, cerca de 30%. O diagnóstico da doença muitas vezes pode ser recebido como uma sentença de morte, além de todo sofrimento que pode ser causado pelo tratamento desse e de outros tipos de tumores malignos. Esse projeto visa estabelecer uma relação entre o nível socioeconômico e a probabilidade de sucesso do tratamento para o câncer de mama. 

<span style="background-color: red">Link para vídeo de apresentação da proposta do projeto (máximo 3 minutos).</span>

# Perguntas de Pesquisa
> Perguntas de pesquisa que o projeto pretende responder ou hipóteses a serem avaliadas, enunciadas de maneira objetiva e verificável.

# Bases de Dados
> Elencar bases de dados candidatas a serem utilizadas no projeto.

# Metodologia
> Proposta de metodologia incluindo especificação de quais técnicas pretende-se explorar, tais como: aprendizagem de máquina, análise de redes, análise estatística, ou integração de uma ou mais técnicas. Para a primeira entrega, descreva de maneira mais genérica que tipo de abordagem seu grupo pretende realizar.

# Ferramentas
> Ferramentas a serem utilizadas (com base na visão atual do grupo sobre o projeto).

# Cronograma
> Proposta de cronograma. Procure estimar quantas semanas serão gastas para cada etapa do projeto.

Project Organization
------------

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization  <- Scripts to create exploratory and results oriented visualizations
    │       └── visualize.py
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.readthedocs.io


--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
