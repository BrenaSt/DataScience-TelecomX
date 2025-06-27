# 📊 Projeto: Análise de Evasão de Clientes (Churn) — Telecom X

Este projeto foi desenvolvido como parte de um desafio de Data Science com foco em entender os fatores que influenciam a evasão de clientes em uma empresa de telecomunicações fictícia chamada **Telecom X**.

---

## 🚀 Objetivo

Analisar o comportamento dos clientes e identificar padrões que estejam relacionados ao **cancelamento de contratos (churn)**. A partir dessa análise, gerar **insights estratégicos** que auxiliem a empresa na **redução da evasão** e na **retenção de clientes**.

---

## 🧰 Tecnologias e Bibliotecas Utilizadas

- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 🧼 Etapas Realizadas

### 1. Extração de Dados
- Importação de dados via API ou CSV.

### 2. Transformação e Limpeza
- Padronização de nomes de colunas.
- Conversão de dados categóricos e numéricos.
- Criação de colunas auxiliares: `qtd_servicos`, `contas_diarias`, `churn_num`.
- Tratamento de valores ausentes e inconsistentes.

### 3. Análise Exploratória de Dados (EDA)
- Comparações entre clientes que saíram e os que permaneceram.
- Visualização de métricas de gasto, contrato, serviços contratados e formas de pagamento.
- Geração de gráficos de barras, dispersão e matriz de correlação.

### 4. Geração de Insights
- Fatores que mais contribuem para a evasão.
- Possíveis estratégias para retenção de clientes.

---

## 📈 Principais Insights

- Clientes com contratos **mensais** e **gasto elevado** apresentam maior risco de churn.
- Quanto **mais serviços contratados**, menor a chance de cancelamento.
- O **gasto médio diário** se mostrou um bom indicador de risco.
- Contratos mais longos podem contribuir para maior retenção.

---

## ✅ Como Executar

1. Acesse o Colab
Você pode abrir o notebook diretamente no Google Colab clicando no botão abaixo:

<https://colab.research.google.com/drive/1ifApKSa1ZOZnM6RuZ3YtW7yEo_yGLw-_?usp=sharing>

2. Verifique se o ambiente está pronto

Certifique-se de que o Colab está usando o ambiente Python 3.

3. Instale as dependências (se necessário)
A maioria das bibliotecas utilizadas (como pandas, seaborn, matplotlib, numpy) já estão disponíveis no Colab.
