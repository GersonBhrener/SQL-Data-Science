# <div align="center">SQL para Data Science</div>

<div align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://i.imgur.com/RjY9oBo.png">
  <img width="128px" alt="" src="https://i.imgur.com/V278dTp.png">
</picture>
</div>

## Sobre

Este repositório apresenta variados projetos na aprendizagem e aplicação da linguagem SQL na área Data Science, mais especificamente, em Análise de Dados.


## Objetivos

- Aprendizado da linguagem SQL em diferentes SGBDs de execução local na criação, leitura, atualização e exclusão de dados.
- Demonstrar a aplicaçao da linguagem em diferentes situações (datasets) de análise de dados.
- Familiarizar e integrar diferentes ferramentas utlizadas no contexto Data Science.
- Melhorar as softskills necessárias para um projeto de anállise de dados.

## Processo

- Os projetos serão divididos de acordo com o SGBD em que a análise foi realizada respeitando os comandos SQL particulares de cada sistema.
- A execução das análises serão por meio do Jupyter Notebook.
- Os dataset serão com dados reais (open data) ou fictícios (dummy data)
- Para melhor visualização da análise, os notebooks poderão conter representações visuais.


### Ferramentas

- **SGBD**:
  - [MySQL 8 Community Edition &  MySQL Workbench](https://www.mysql.com/products/community/)

- **Python**
    - [Jupyter Notebook](https://jupyter.org/)
    - [SQLAlchemy](https://www.sqlalchemy.org/): Integração ambiente Python com SGBDs
    - [mysql-connector-python](https://pypi.org/project/mysql-connector-python/): Conector Python-MySQL
    - [ipython-sql](https://pypi.org/project/ipython-sql/): Comandos SQL diretamente no Jupyter Notebook

## Projetos

### MySQL

<details>
<summary>Seleção, Filtro e Ordenamento</summary>

```
SELECT [DISTINCT] * columns [AS alias]
FROM tables
[WHERE] condition
[ORDER] columns
[LIMIT] number
```

| Projetos | Dataset | Data da Análise |
| :---:     | :---:     | :---:             |
| [Inspeção de Navios de Cruzeiro - Anvisa](/MySQL/Inspecao_Navios_Cruzeiro_Anvisa/Inspecao_Navios_Cruzeiro.ipynb)| Open Data | 31/08/2022 |
</details>

<details>
<summary>CASE Statement</summary>

```
SELECT
  CASE
    WHEN condition THEN value
    WHEN condition THEN value
  [ELSE]
  END [AS alias]

```

| Projetos | Dataset | Data da Análise |
| :---:     | :---:     | :---:             |
|[Ocorrência de Câncer de Mama - UC Irvine ML Repository](/MySQL/Cancer_Mama_UC_Irvine_ML_Repository/Breast_Cancer_UCI_ML.ipynb) | Open Data | 09/09/2022 |
</details>

