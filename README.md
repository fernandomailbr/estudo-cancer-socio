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

Descrição do projeto em formato vídeo: https://youtu.be/DoauGouCxCo

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
A maioria dos artigos sobre o tema utilizam Revisões sistemáticas de literatura para condensar e apresentar os dados:


* (https://referenciaincor.com.br/wp-content/uploads/2020/02/priscila-berenice-da-costa.pdf; https://www.scielosp.org/pdf/rsap/2014.v16n5/786-798; https://www.unicesumar.edu.br/mostra-2016/wp-content/uploads/sites/154/2017/01/juliana_santos_tortajada.pdf;  https://www.scielo.br/scielo.php?script=sci_arttext&pid=S1413-81232011000200025) 

* “Foram analisados os óbitos por câncer ocorridos entre 2010 e 2012, obtidos no Sistema de Informação sobre Mortalidade. Foram selecionados 268 municípios brasileiros que apresentaram população acima de 80 mil habitantes e melhor qualidade de informação. Os indicadores socioeconômicos referentes ao ano 2000 foram extraídos do Atlas Brasil 2013. Para analisar a correlação entre indicadores socioeconômicos e a mortalidade por câncer foi utilizada a Correlação de Pearson e a regressão linear simples. Resultados: Verificou-se correlação negativa com o analfabetismo (r=-0,509) e com o Gini (r=-0,197); a correlação foi positiva com o indicador de renda (r=0,414) e esperança de vida (r=0,537); a regressão linear simples mostrou que há uma associação fraca entre a mortalidade por câncer e as variáveis socioeconômicas pesquisadas.” (https://periodicos.unifor.br/RBPS/article/view/4291) 

* “O objetivo desse estudo foi analisar a influência dos índices socioeconômicos municipais nas taxas de mortalidade por câncer de boca e de orofaringe em idosos nas 645 cidades do Estado de São Paulo, Brasil. Dados secundários de óbitos foram obtidos no Sistema de Informações sobre Mortalidade do Ministério da Saúde. O número de idosos e os valores da renda média per capita e do Índice de Desenvolvimento Humano por município (IDH-M) foram obtidos de dados governamentais. A análise descritiva e exploratória dos dados foi realizada, seguida de modelos binomiais negativos descritos pelo procedimento PROC GENMOD e avaliados pelo AICc (Critério de Informação de Akaike corrigido), pelo grau de liberdade e pelo teste de Wald (α=0.05). 30% das cidades notificaram óbitos em 2013” (http://repositorio.unicamp.br/bitstream/REPOSIP/322214/1/Sakamoto_AssahitoJoel_M.pdf).

* “Objetivo: Investigar associações entre nível socioeconômico e incidência e mortalidade por câncer e seus tipos, através de revisão de estudos ecológicos. Definir a real importância desempenhada pelos estudos ecológicos na investigação dessa relação. Método: As principais bases de dados regionais e internacionais foram pesquisadas na seleção de artigos em português, espanhol e inglês, publicados entre 1998 e 2008. Resultados: 32 estudos elegíveis foram incluídos. Verificou-se associação positiva e consistente do nível socioeconômico da área de residência com incidência de câncer de próstata e mortalidade pelo de cólon nos homens, e com incidência e mortalidade por câncer de mama e mortalidade pelo de cólon nas mulheres. Associação consistente e negativa foi encontrada para incidência e mortalidade por cânceres de esôfago e estômago, para incidência dos de cólon e pulmão e mortalidade pelos de laringe e cavidade oral, nos homens, e para incidência e a mortalidade pelos de esôfago, estômago e colo uterino e para incidência dos de cólon e pulmão, nas mulheres. Conclusão: Apesar da presença de efeito residual de área e de viés relacionado à medida agregada de nível socioeconômico, estudos ecológicos podem ser eficientemente utilizados na mensuração das desigualdades socioeconômicas em câncer. Uso de pequenas unidades geográficas e de dados de registros de câncer em países em desenvolvimento pode contribuir para melhor conhecimento de suas desigualdades em saúde” (https://www.revistas.usp.br/sausoc/article/download/76484/80219)

* “Chronic non-communicable diseases represent a major public health problem, requiring more effective investigation and control by government agencies. The aim of this study was to correlate the mortality rate for oral cancer in Brazilian State capitals from 1998 to 2002 with socioeconomic factors collected in the 2000 census, using an ecological study design. Data were obtained from the Mortality Information System from 1998 to 2002. Social factors were taken from the Brazilian Human Development Atlases. After data collection, statistical analysis was performed using Pearson's correlation index. The findings included positive and significant correlations among the socioeconomic indicators (Municipal Human Development Index - MHDI, MHDI-income, MHDI-education, MHDI-life expectancy, and per capita income), and negative and significant correlations with the socioeconomic indicators Gini Index and infant mortality. Despite the study’s limitations and probable underreporting in less developed State capitals, the study found significant statistic correlations between the selected socioeconomic indicators and the oral cancer mortality rate.” (https://repositorio.ufrn.br/bitstream/1/3055/1/2010ART_Mortalidade_Angelloroncalli.pdf)

* “Desenho do estudo: Estudo transversal contemporâneo do perfil socioeconômico de pacientes oncológicos adultos em tratamento quimioterápico ambulatorial. Pacientes e métodos: 136 pacientes adultos em tratamento quimioterápico parental para câncer no hospital das clinica de porto alegre responderam a um questionário com perguntas relacionadas a situação socioeconômica durante o tratamento no período de fevereiro a setembro de 2004” (https://lume.ufrgs.br/bitstream/handle/10183/11364/00061173%205.pdf?sequence=1)  

A metodologia que será utilizada no projeto é a CRISP-DM. Após uma rápida pesquisa, encontramos algumas bases de dados informando taxa de mortalidade de pacientes com câncer agrupados por local e ano. A partir de um determinado local (em diferentes granularidades como país, estado, cidade) e ano, podemos buscar outras bases contendo índices socioeconômicos como renda per capita, IDH e analfabetismo. Finalmente, mediremos a correlação entre taxas de mortalidade e o índice sócio-econômico através de: 1) coeficiente de correlação de Pearson e 2) regressão linear simples.

![Figura](https://github.com/edgartanaka/estudo-cancer-socio/blob/main/references/E1%20-%20Projeto%20-%20Primeira%20Entrega.jpg)

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
