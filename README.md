## Projeto de ETL e apresentação de Performance de Vendas Descritiva e Preditiva

Projeto realizado visando o desenvolvimento de habilidades de extração, tratamento e carregamento de dados para apresentação em dashboard com ***KPIS*** relevantes a análise da performance de vendas de um banco de dados simulado.

Ponta pé inicial do trabalho com a preparação do ambiente de levantamento de informações e definição do ciclo de dados, ferramentas utilizadas e modelagem dimensional.

Nesse projeto utilizamos o ***Microsoft SQL Server*** Server para extrair os dados necessários, definindo os servidores OLTP e OLAP em um ***Data Warehouse*** para posterior transformação dos dados em tabelas acessíveis e coerentes.

![SQL Server](https://user-images.githubusercontent.com/116115002/210646476-d982d16a-596e-42aa-8efc-9199cb2da01a.JPG)

Transformação de dados realizada pelo ***Talend*** criando as conexões com o servidor através das informações extraídas no banco de dados via ***SQL Server***.

Passos importantes nessa etapa, foram, a criação de ***Jobs de carga Staging*** das tabelas de dimensão e fato, introdução de ***SCD (Surrogate Key)*** e automatização das tarefas.

![Talend](https://user-images.githubusercontent.com/116115002/210646912-15c48ed2-9778-4952-adfd-ab8630f6282e.JPG)

Com as tabelas extraídas/criadas e transformadas, as mesmas foram carregadas no ***Microsoft Power BI***, onde sofreu ajustes/refinamentos no ***Powerquery***.

Na sequência foram realizados os relacionamentos das tabelas e criação da tabela calendário.

![Relacionamentos](https://user-images.githubusercontent.com/116115002/210647192-46b0d0f6-751d-4239-993e-6617f168357d.JPG)

Para o desenvolvimento do layout de apresentação do dashboard criei no ***Figma*** um design exclusivo de acordo com as necessidades previamente avaliadas

![Figma](https://user-images.githubusercontent.com/116115002/210648904-259363f6-c232-4255-89ea-ab741b97aaa7.JPG)

Com uma prévia avaliação dos ***OKRs*** a serem atingidos pelo estudo, foi desenvolvido ***KPIs*** para sinalizar as métricas indispensáveis.

***OKRs:*** 	
* Superávit de 10% sobre as metas de vendas geral           	
* Lucratividade superior a 50%

***KPIs:*** 	
* Indicadores de resultados (Mês atual e anual);
  * Faturamento X Meta (% Realizado)
	* Lucratividade
	* Desmembramento de métricas por unidade;
    * Faturamento
    * YOY
    * MOM
    *	Fat X Meta
    *	Lucratividade
* Distribuição de Faturamento por Unidade/Gerente/Vendedor 
* Top 5 Clientes
* Top 5 Produtos
* Tendência de MOM E YOY (Gerente/Vendedor)
* Tendência de Faturamento X Meta (Gerente/Vendedor)

![Capa](https://user-images.githubusercontent.com/116115002/210649024-2a904f00-353f-465c-a2fb-838b1364a9ad.JPG)
![Mensal](https://user-images.githubusercontent.com/116115002/210649062-13400b1f-33b1-4ea5-9bee-39f819e77e66.JPG)
![Anual](https://user-images.githubusercontent.com/116115002/210649098-0d13e2a6-d11a-4b85-9638-a764507b50e3.JPG)
![Tendência](https://user-images.githubusercontent.com/116115002/210649129-66288e19-34e0-419a-b5c4-50fc1f6b1859.JPG)



