# Instruções Básicas de Instalação e Execução

* O arquivo [ETLSIM.DORES_2010-v4](https://github.com/fernandomailbr/estudo-cancer-socio/blob/7e05268d3f0e1efb64fbb1e09aa53fd8d688b899/src/ETLSIM.DORES_2010-v4.ows) referente ao *Workflow* desenvolvido na ferramenta [Orange](https://orangedatamining.com/) deve ser baixado em uma pasta local;
* Todos os arquivos do tipo CSV presentes na pasta data/interim também devem ser baixados na mesma pasta do ETLSIM.DORES_2010-v4.ows:
  
  * RelatorioTabuaCBO2002_CBO94_CIUO88.csv
     
     Separador: ponto e vírgula
     Tipos das colunas:
     
     | Coluna         | Tipo       |
     |----------------|------------|
     | CBO2002        | Categórica |
     | Título CBO2002 | Categórica |
     | CBO94          | Categórica |
     | CIUO88         | Numérica   |
  
  * corrtab88-08.csv
  
     Separador: ponto e vírgula
     Tipos das colunas:
     
     | Coluna            | Tipo       |
     |-------------------|------------|
     | Level             | Ignorar    |    
     | CIUO-88 Título SP | Categórica |
     | Código CIUO-88    | Numérica   |
     | Código CIUO-08    | Numérica   |
     | CIUO-08 parte     | Ignorar    |
     | CIUO-08 Título SP | Categórica |

  * Tabela 3592.csv

     Separador: ponto e vírgula
     Tipos das colunas:
      
     | Coluna                                                                                             | Tipo       |
     |----------------------------------------------------------------------------------------------------|------------|
     | Grandes grupos, subgrupos principais, subgrupos e grupos de base da ocupação no trabalho principal | Categórica | 
     | Total                                                                                              | Categórica |
     | Homens                                                                                             | Categórica |
     | Mulheres                                                                                           | Categórica | 
     
  * ETLSIM.DORES_2010-sub.csv

     Separador: tabulação
     Tipos das colunas:
      
     | Coluna             | Tipo       |
     |--------------------|------------|
     | causabas_categoria	| Categórica | 
     | def_sexo	          | Categórica | 
     | OCUP	              | Numérica   |
     | idade_obito_anos	  | Numérica   |
     | ESC2010	          | Categórica |
     | ESCFALAGR1	        | Categórica | 
     | def_escol          | Categórica |
  
  * tab1_1_11.csv

     Separador: tabulação
     Tipos das colunas:
      
     | Coluna                       | Tipo       |
     |------------------------------|------------|
     | nível de instrução           | Categórica |
     | grupo de idade	              | Categórica | 
     | Número de Pessoas (Mulheres) | Numérica   |

* A escolha de uma das opções a seguir, não deve alterar na obtenção dos resultados finais:
  * Se a intenção for rodar o processo com o subconjunto dos dados de mortalidade, contendo somente as mortes por câncer de mama em mulheres, o arquivo ETLSIM.DORES_2010-sub.csv deve ser previamente renomeado para ETLSIM.DORES_2010.csv
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

* As variáveis consideradas na regressão linear podem ser escolhidas/alternadas diretamente no componente *Define Target*.
