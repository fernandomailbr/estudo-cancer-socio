# Instruções Básicas de Instalação e Execução

* O arquivo [ETLSIM.DORES_2010-v4](src/ETLSIM.DORES_2010-v4.ows) referente ao *Workflow* desenvolvido na ferramenta Orange deve ser baixado em uma pasta local;
* Todos os arquivos do tipo CSV, presentes na pasta data/interim também devem ser baixados na mesma pasta do ETLSIM.DORES_2010-v4.ows;
* A escolha de uma das opções a seguir, não deve alterar na obtenção dos resultados finais:
  * Se a intenção for rodar o processo com o subconjunto dos dados de mortalidade, o arquivo ETLSIM.DORES_2010-sub.csv deve ser previamente renomeado para ETLSIM.DORES_2010.csv
  * Caso contrário, para usar o arquivo completo dos registros de mortalidade, o ETLSIM.DORES_2010.csv deve ser baixado diretamente do site da Fiocruz: https://bigdata-metadados.icict.fiocruz.br/dataset/sistema-de-informacoes-de-mortalidade-sim
* Os arquivos usados no *script* Python do componente merge OCUP desse *workflow* devem ser importados/lidos na ordem a seguir, para manter os índices do *array* in_datas:

~~~python
# converte as tabelas do Orange para dataframes

# RelatorioTabuaCBO2002_CBO94_CIUO88
df_CBO2002_CIUO88 = table_to_frame(in_datas[0])

# corrtab88-08
df_CIUO88_CIUO08 = table_to_frame(in_datas[1])

# Tabela 3592
df_CIUO08_POPULACAO = table_to_frame(in_datas[2])

# OCUP, OBITOS C50
df_CBO2002_OBITOS = table_to_frame(in_datas[3])
~~~

* As variáveis consideradas na regressão linear devem ser escolhidas/alternadas diretamente no componente *Define Target*.
