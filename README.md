# **Projeto: Análise e Apresentação de Dados (Databricks - SQL)**

## **Stack**
Databricks, SQL

## **Sobre**
Projeto de análise e visualização de dados, importando um dataset Kaggle, manipulando os dados com SQL em notebooks da plataforma gratuita Databricks e exportando os gráficos de BI gerados no notebook para construir um Dashboard de Análise de Mercado.

## **Sobre os Dados**
Os dados foram retirados do seguinte Dataset Kaggle: https://www.kaggle.com/datasets/gregorut/videogamesales.

## Sobre o Dataset
Este conjunto de dados contém uma lista de videogames com vendas superiores a 100.000 cópias. Foi gerado por um rascunho de vgchartz.com.

### Os campos incluem:
- Rank - Ranking das vendas gerais
- Name - O nome do jogo
- Platform - Plataforma de lançamento do jogo (ou seja, PC, PS4, etc.)
- Year - Ano de lançamento do jogo
- Genre - Gênero do jogo
- Publisher - Editora do jogo
- NA_Sales - Vendas na América do Norte (em milhões)
- EU_Sales - Vendas na Europa (em milhões)
- JP_Sales - Vendas no Japão (em milhões)
- Other_Sales - Vendas no resto do mundo (em milhões)
- Global_Sales - Total de vendas mundiais.

> O script para extrair os dados está disponível em https://github.com/GregorUT/vgchartzScrape.<br>
> É baseado em BeautifulSoup usando Python.<br>
> Existem 16.598 registros. 2 registros foram descartados devido a informações incompletas.

## Perguntas de Negócio
As perguntas de negócio para o processo de análise foram respondidas utilizando linguagem SQL e foram geradas utilizando o ChatGPT como "Stakeholder": 
- 001: Qual é a distribuição das vendas globais de videogames por plataforma?<br>
- 002: Quais são os anos com o maior número de lançamentos de jogos e como as vendas globais variam nesses anos?<br>
- 003: Como as vendas de videogames se distribuem ao longo dos anos e qual é a linha de tendência geral?<br>
- 004: Como tem sido a taxa de crescimento das vendas globais de videogames ao longo dos anos e qual é a tendência de crescimento anual dessas vendas?<br>
- 005: Qual é a participação de mercado(%) dos principais editores de videogames em termos de vendas Norte Americanas e Japonesas?<br>
- 006: Quais são os cinco jogos mais vendidos em termos de vendas globais e em quais plataformas eles foram lançados?<br>

## Notebook
O Notebook pode ser acessado através do links gerado pela plataforma:<br><br>
**Notebook:** https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/4587457387213016/4128318070257346/8228578099102552/latest.html<br>

## Dashboard
Este é o resultado da estrutura final do dashboard, montado a partir das análises e gráficos feitos através do notebook.
![Dashboardgif](https://github.com/caioypaulino/Projeto-Videogame_Sales_Databricks/blob/main/Images/Dashboard.gif)

## Imagens de Exemplo:
(Acesse os links acima para conferir todas as análises detalhadas e Dashboard completo)

![Dashboard](https://github.com/caioypaulino/Projeto-Videogame_Sales_Databricks/blob/main/Images/Dashboard%20Videogame%20Sales%20Example.png)

![Notebook5](https://github.com/caioypaulino/Projeto-Videogame_Sales_Databricks/blob/main/Images/Notebook%20005%20Example.png)

![Notebook6](https://github.com/caioypaulino/Projeto-Videogame_Sales_Databricks/blob/main/Images/Notebook%20006%20Example.png)
