# Processamento_Dados_CNPJs_SPARK

Processamento de Grandes Volumes de Dados CNPJ com Apache Spark

Este projeto demonstra a capacidade de ler, manipular, tratar e salvar um grande conjunto de dados utilizando o **Apache Spark**. O foco principal é o processamento eficiente de informações de cadastro de CNPJs brasileiros, provenientes diretamente da Receita Federal.

---

## Contexto do Projeto

O Brasil possui milhões de empresas ativas, e seus cadastros de CNPJ representam um volume de dados significativo. Originalmente, o conjunto de dados da Receita Federal contém aproximadamente 40 milhões de registros. Dada essa escala, o projeto utilizou uma amostra representativa de 10%, resultando em um dataset com cerca de **4 milhões de cadastros**.

---

## Ferramentas e Tecnologias

* **Apache Spark**: Utilizado como motor de processamento distribuído, permitindo a análise de grandes volumes de dados de forma rápida e escalável.
* **Python**: Linguagem de programação principal para interagir com o Spark e realizar as operações de ETL (Extract, Transform, Load).

---

## Objetivos

* **Leitura Eficiente**: Carregar o extenso dataset de CNPJs de maneira otimizada.
* **Manipulação e Transformação**: Aplicar diversas operações para enriquecer e organizar os dados.
* **Tratamento de Dados**: Realizar limpeza, validação e correção de inconsistências nos registros.
* **Salvamento Otimizado**: Persistir os dados processados em um formato adequado para futuras análises ou integrações.

---

Este repositório servirá como documentação e código-fonte para o desenvolvimento e demonstração deste pipeline de processamento de **Big Data**.
