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

https://youtu.be/DoauGouCxCo

# Perguntas de Pesquisa
A condição socioeconômica do paciente impacta no desfecho do tratamento de câncer de mama?

# Bases de Dados
Listamos aqui bases de dados são apenas candidatas à nossa pesquisa e ainda passarão por uma análise mais rigorosa da equipe. 

## Brasil

https://datasus.saude.gov.br/

http://dados.gov.br/dataset/ (Portal brasileiro de dados abertos)

https://mortalidade.inca.gov.br/MortalidadeWeb/pages/Modelo01/consultar.xhtml 

http://dados.gov.br/dataset/anvisa-preco-de-medicamento-consumidor (Preço remédio dataset)

http://dados.gov.br/dataset/ubs_existentes (Distribuição Unidades Básicas de Saúde Existentes-UBS)

https://www.inca.gov.br/estimativa/introducao 

http://saudepublica.bvs.br/

http://www.perfil.seade.gov.br/ (São Paulo data set)

http://aplicacao.saude.gov.br/portaltransparencia/visao/dadosTransparencia.jsf?uf=%27GO%27 (Saúde e econômia Dataset)

https://cidades.ibge.gov.br/brasil/pesquisa/30/84366 (Pesquisa nacional de saneamento básico)

http://sigtap.datasus.gov.br/tabela-unificada/app/sec/inicio.jsp (sistema de gerenciamento da tabela de procedimentos, medicamentos e OPM do SUS)

http://www.ans.gov.br/anstabnet/ (ANS TABNET)

http://www.atlasbrasil.org.br/

https://www.inca.gov.br/sites/ufu.sti.inca.local/files//media/document//cancer-in-brazil-vol4-2013.pdf (pdf mas com tabelas por estado)

https://bigdata.icict.fiocruz.br/ (Plataforma de Ciência de Dados aplicada à saúde)

https://bvsalud.org/ (Biblioteca virtual de saúde)

https://mtci.bvsalud.org/pt/

## Internacional

https://data.world/dartmouthatlas/cancer-patients-death (mortalidade por estado nos EUA) 

https://data.mendeley.com/datasets (Mendeley Data Repository)

https://virtualpatients.eu/ (Eletronic virtual pacients)

https://virtualpatients.eu/referatory/ (Referatory)

https://www.nlm.nih.gov/mesh/meshhome.html (Medical Subject Headings (MeSH))

https://www.cancerimagingarchive.net/collections/ (Cancer Imaging Archive)

https://datascience.cancer.gov/resources/nci-data-catalog#drugdiscovery (National cancer Institute Data Catalog)

https://www.scielo.br/scielo.php?script=sci_arttext&pid=S0482-50042017000600574 (Scielo)

http://www.diseasesdatabase.com/begin.asp (Diseases Database)

https://seer.cancer.gov/canques/ (National Cancer Institute - Cancer Query Systems)

https://seer.cancer.gov/ (All Cancer Sites Combined Database)

http://portals.broadinstitute.org/cgi-bin/cancer/datasets.cgi (Cancer Program Datasets)

https://toxnet.nlm.nih.gov/cgi-bin/sis/htmlgen?CCRIS (CCRIS)

https://www.cdc.gov/cancer/dcpc/data/ (Cancer Data and Statistics)

https://portal.gdc.cancer.gov/ (GDC Data Portal - National Cancer Institute)

https://data.gov.uk (Find Open Data)

https://apps.who.int/nha/database/Select/Indicators/en (Global Health Expenditure DB(WHO))

https://datacatalog.worldbank.org/dataset/universal-health-coverage-global-monitoring-data-
2017 (Universal Health Coverage Global Monitoring Data - 2017)

https://datacatalog.worldbank.org/dataset/world-development-indicators (World Developmnet indicatos)

https://www.outbreak-database.com/Home.aspx (Outbreak database)

https://ilostat.ilo.org/ (ILOSTAT)

http://datatopics.worldbank.org/ (Datatopics - World Bank)

https://www.br.undp.org/content/brazil/pt/home/idh0/rankings/idh-global.html

https://www.who.int/data/data-collection-tools/who-mortality-database 


# Metodologia
> Proposta de metodologia incluindo especificação de quais técnicas pretende-se explorar, tais como: aprendizagem de máquina, análise de redes, análise estatística, ou integração de uma ou mais técnicas. Para a primeira entrega, descreva de maneira mais genérica que tipo de abordagem seu grupo pretende realizar.

# Ferramentas
1. Orange
2. pandas
3. scikit-learn
4. matplotlib

# Cronograma
| Etapa                                          | Semana inicial | Semana final |
|------------------------------------------------|----------------|--------------|
| Entendimento da Pesquisa                       | 1              | 2            |
| Determinar os objetivos                        |                |              |
| Avaliar a situação                             |                |              |
| Determinar os objetivos da mineração dos dados |                |              |
| Produzir o plano do projeto                    |                |              |
| Entendimento dos Dados                         | 3              | 5            |
| Coletar os dados iniciais                      |                |              |
| Descrever os dados                             |                |              |
| Explorar os dados                              |                |              |
| Verificar a qualidade dos dados                |                |              |
| Preparação dos Dados                           | 6              | 6            |
| Selecionar os dados                            |                |              |
| Limpar os dados                                |                |              |
| Integrar os dados                              |                |              |
| Formatar os dados                              |                |              |
| Modelagem                                      | 7              | 8            |
| Selecionar as técnicas de modelagem            |                |              |
| Gerar os dados de teste                        |                |              |
| Construir o modelo                             |                |              |
| Avaliar o modelo                               |                |              |
| Avaliação                                      | 9              | 9            |
| Avaliar os resultados                          |                |              |
| Revisar o processo?                            |                |              |
| Determinar os próximos passos                  |                |              |
| Consolidação                                   | 10             | 10           |
| Produzir o relatório final                     |                |              |

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
