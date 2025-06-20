# Análise de Evasão de Clientes - Telecom X

## Descrição do Projeto

Este projeto tem como objetivo realizar uma análise exploratória dos dados de clientes da Telecom X para identificar fatores que influenciam a evasão (churn). A evasão de clientes é um problema crítico que impacta diretamente a receita e a sustentabilidade da empresa. Com essa análise, esperamos fornecer insights para ajudar na criação de estratégias eficazes de retenção.

---

## Etapas do Projeto

### 1. Coleta e Importação dos Dados

Os dados foram obtidos a partir de uma API, contendo informações sobre os clientes, seus contratos, serviços e histórico de evasão. Algumas colunas estavam aninhadas em estruturas do tipo dicionário, sendo necessário normalizá-las para facilitar a análise.

### 2. Limpeza e Tratamento dos Dados

- Expansão das colunas aninhadas em colunas simples e tabulares.
- Tratamento de valores ausentes, substituindo-os por médias ou valores mais adequados.
- Conversão de colunas para tipos numéricos ou categóricos, conforme o caso.
- Remoção de colunas irrelevantes para a análise (ex: identificadores únicos).

### 3. Análise Exploratória de Dados (EDA)

- Cálculo de estatísticas descritivas para variáveis numéricas, incluindo média, mediana, desvio padrão, mínimos e máximos.
- Análise da distribuição da evasão por variáveis categóricas relevantes, como gênero, tipo de contrato e método de pagamento.
- Visualização dos dados por meio de gráficos de barras segmentados por evasão para facilitar a identificação de padrões.

### 4. Conclusões e Insights

- Clientes com contratos mensais apresentam taxas de evasão significativamente maiores.
- O método de pagamento via cheque eletrônico está associado a maior probabilidade de cancelamento.
- O gênero do cliente não apresenta influência significativa na evasão.

### 5. Recomendações

- Incentivar os clientes a optarem por contratos de maior duração (anuais ou bienais).
- Revisar processos e políticas relacionadas ao pagamento via cheque eletrônico.
- Direcionar ações de retenção e fidelização para clientes com contratos mensais.

---

## Tecnologias Utilizadas

- Python 3.x
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Referências

- Documentação do Pandas: https://pandas.pydata.org/
- Documentação do Seaborn: https://seaborn.pydata.org/
