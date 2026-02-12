# 📊 Análise de Dados com PySpark

## 📌 Sobre o Projeto

Este repositório reúne estudos e práticas utilizando **PySpark** para processamento e análise de dados em ambiente distribuído.

O objetivo é aplicar conceitos fundamentais de Big Data, como leitura, transformação, agregação e escrita de dados, utilizando a API de DataFrames do Spark.

Os experimentos foram desenvolvidos no **Google Colab**, simulando cenários reais de manipulação de múltiplas fontes de dados.

## 🧪 Notebook 1 — Leitura e Escrita de Dados (`leitura_escrita.ipynb`)

Este notebook apresenta os fundamentos do uso do PySpark para:

- Criação da `SparkSession`
- Leitura de arquivos CSV
- Exploração inicial dos dados com DataFrames
- Visualização de colunas e estrutura
- Escrita de dados processados

Foram utilizados dois conjuntos de dados:

- `videos-stats.csv`
- `comments.csv`

Ambos disponíveis na pasta `data/`.

Este notebook estabelece a base para os próximos estudos e análises que serão adicionados ao repositório.

## 🧪 Notebook 2 — Tratamento e Transformação de Dados (`tratamento.ipynb`)

Neste notebook são aplicadas operações de transformação utilizando a API de DataFrames do PySpark, aprofundando o processamento dos dados carregados anteriormente.

Principais etapas desenvolvidas:

- Seleção de colunas específicas
- Filtros condicionais
- Manipulação e criação de colunas
- Conversão e tratamento de tipos de dados
- Limpeza e organização das informações

Este notebook demonstra a etapa de preparação dos dados, essencial em projetos de análise e engenharia de dados, antes da realização de agregações ou análises mais complexas.

## 🧪 Notebook 3 — Preparação dos Dados (`preparacao.ipynb`)

Este notebook aprofunda a etapa de preparação dos dados, consolidando transformações realizadas anteriormente e organizando as informações para futuras análises.

Entre as atividades desenvolvidas estão:

- Ajustes finais na estrutura dos DataFrames
- Tratamento complementar de colunas
- Organização e padronização dos dados
- Preparação para análises e agregações posteriores

Essa etapa é fundamental em projetos de dados, pois garante consistência, qualidade e confiabilidade antes da geração de insights.
