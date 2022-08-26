# <div align="center">SQL para Data Science</div>

<div align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://i.imgur.com/RjY9oBo.png">
  <img width="128px" alt="" src="https://i.imgur.com/V278dTp.png">
</picture>
</div>

## Sobre

Este repositório apresenta variados projetos na aprendizagem e aplicação da linguagem SQL na área Data Science, mais especificamente, em Análise de Dados.

## Overview

### Objetivos

- Aprendizado da linguagem SQL em diferentes SGBDs de execução local na criação, leitura, atualização e exclusão de dados.
- Demonstrar a aplicaçao da linguagem em diferentes situações (datasets) de análise de dados.
- Familiarizar e integrar diferentes ferramentas utlizadas no contexto Data Science.
- Melhorar as softskills necessárias para um projeto de anállise de dados.

## Processo

### Ferramentas

- **SQL**
<br>

- **SGBD**:
  - [MySQL Community Edition](https://www.mysql.com/products/community/)
<br>

- **Python 3 e Bibliotecas**
  - [Ambiente Python](https://www.python.org/)
  - [Jupyter Notebook](https://jupyter.org/): apresentação do projeto
  - [SQLAlchemy](https://www.sqlalchemy.org/): integração ambiente Python com SGBDs
  - [mysql-connector-python](https://pypi.org/project/mysql-connector-python/): conector Python-MySQl
  - [ipython-sql](https://pypi.org/project/ipython-sql/): conexão e comandos SQL diretamente no Jupyter Notebook

### Descrição

- Os projetos serão divididos de acordo com o SGBS em que a análise foi realizada respeitando os comandos SQL particulares de cada sistema.
- As queries, análises e conclusões se darão por meio do Jupyter Notebook conectado ao SGBD.
- Os dataset serão com dados reais (open data) ou fictícios (demo-data).
- O assunto, tipo de dataset e comandos serão exibidos nas tabelas de cada projeto.
-  Mais detalhes se encontram na pasta do devido projeto

## Projetos

### MySQL

- Seleção, Filtro e Ordenamento

```
SELECT [DISTINCT] * | columns 
FROM tables
WHERE condition
ORDER columns
LIMIT number
```

| Projetos | Dataset | Data da Análise |
| ---     | ---     | ---             |
| [Inspeção de Navios de Cruzeiro - Anvisa]()| Open Data | |


