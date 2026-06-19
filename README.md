# Criando um Star Schema para Cenários de Vendas com Power BI

## Descrição

Neste desafio foi desenvolvido um modelo dimensional em formato Star Schema utilizando a base de dados Financial Sample.

O objetivo foi transformar a tabela original em uma estrutura otimizada para análise de dados, separando as informações em tabela fato e tabelas dimensão.

## Estrutura do Modelo

### Tabela Fato
- F_Vendas

### Tabelas Dimensão
- D_Produtos
- D_Produtos_Detalhes
- D_Descontos
- D_Detalhes
- D_Calendario

### Tabela de Origem
- Financials_origem

## Transformações Realizadas

- Criação da tabela fato F_Vendas.
- Criação das tabelas dimensão a partir da tabela original.
- Agrupamento de produtos para geração da dimensão D_Produtos.
- Criação do identificador ID_Produto para relacionamentos.
- Criação da chave SK_ID na tabela fato.
- Remoção de colunas desnecessárias nas dimensões.
- Criação da dimensão calendário utilizando DAX.
- Configuração dos relacionamentos entre fato e dimensões.
- Organização do modelo em formato Star Schema.

## Tecnologias Utilizadas

- Power BI Desktop
- Power Query
- DAX

## Resultado

O modelo foi estruturado seguindo o padrão Star Schema, facilitando futuras análises de vendas, produtos, descontos e indicadores temporais.
