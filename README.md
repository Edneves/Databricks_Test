# Databricks_Test

Projeto idealizado com o intuito de extrair as tabelas do Database Type Ecommerce e carregá-las no Databricks.
Dentro do repositório consta o diagrama do database, arquivo Readme.md e o notebook em formato IPython.

 - Executado o desenho do diagrama do database.
 - Foi construído um Notebook no Databricks.
 - Implementado o processo de ETL utilizando o spark, precisamente pyspark.
 - Construído os respectivos arquivos parquet para cada tabela.
 - Utilização do parquet para construção das tabelas.
 - Executado uma análise para levamento de algumas informações necessárias, como:
 * O país que possui a maior quantidade de itens cancelados;
 * O faturatamento da linha d eproduto mais vendido com status "Shipped" para o ano de 2005;
 * Levantamento do Nome, Sobrenome e email dos vendedores do Japão, sendo mascarado o local-part na projeção.
 - Os Resultados das análises foram persistidos em formato delta.

 Obs:
 Os métodos "update_table()" e "delete_table()" estão comentados, será necessário executar alguns passos.
 - Definir a regra de atualização, caso seja o método update_table().
 - Definir a regra de deleção, caso seja o método delete_table().
