# Projeto de Qualidade de Vida

Este projeto explora dados de qualidade de vida em diversos países, examinando aspectos como segurança, custo de vida, transporte e outros fatores socioeconômicos. O objetivo é identificar padrões, correlações e destacar diferenças entre países, com foco em comparações como Brasil versus Alemanha.  
Os dados utilizados, `Quality_of_Life.csv`, foram obtidos via interação com a API do [Kaggle](https://www.kaggle.com/datasets). 

## Dados Utilizados

- **Fonte:** Arquivo `Quality_of_Life.csv`.
- **Principais Indicadores:**
  - Qualidade de Vida (Quality of Life Value)
  - Índice de Segurança (Safety Value)
  - Índice de Custo de Vida (Cost of Living Index)
  - Tempo de Transporte (Traffic Commute Time Index)

## Etapas do Projeto

1. **Limpeza dos Dados:**
   - Correção de valores ausentes e inconsistentes.
   - Conversão de colunas para formatos adequados.

2. **Visualizações Iniciais:**
   - Distribuição da qualidade de vida.
   - Relação entre segurança e qualidade de vida.
   - Impacto do custo de vida nos indicadores gerais.

3. **Análises Avançadas:**
   - Correlações entre variáveis principais.
   - Impacto do transporte público na qualidade de vida.
   - Comparativos regionais e entre países (ex.: Brasil vs. Alemanha).

## Tecnologias Utilizadas

- **Linguagem:** Python
- **Bibliotecas:**
  - `pandas` para manipulação de dados.
  - `numpy` para operações numéricas.
  - `matplotlib` e `seaborn` para visualizações gráficas.

## Principais Conclusões

- **Alemanha:** Apresenta melhores índices de qualidade de vida, segurança e transporte comparados ao Brasil.
- **Brasil:** Apesar do custo de vida relativamente baixo, apresenta desafios em segurança e transporte.
- **Globalmente:** Custos elevados não necessariamente indicam maior qualidade de vida, enquanto segurança tem forte correlação com bem-estar.

## Como Executar o Projeto

1. Certifique-se de que o arquivo `Quality_of_Life.csv` esteja no mesmo diretório do notebook.
2. Execute o notebook `qualidade_de_vida.ipynb` em um ambiente Python.
3. Explore os gráficos e inferências gerados.

## Estrutura de Arquivos

- `Quality_of_Life.csv`: Dados brutos originais.
- `qualidade_de_vida.ipynb`: Notebook com código e análises.
- `Quality_of_Life_Cleaned.csv`: Dados limpos para análises futuras.

## Possíveis Expansões

- Análise via séries temporais para avaliar tendências ao longo dos anos.
- Inclusão de mais indicadores econômicos e sociais.
- Criação de dashboards interativos para visualização dinâmica.

---
Projeto desenvolvido como parte de estudos em análise de dados e visualizações exploratórias.
