# 🚀 Desafio Técnico - Triggo.ai | Engenharia de Dados & DataOps

Este repositório contém as soluções desenvolvidas para o desafio técnico do Programa Trainee Triggo.ai de Excelência em Engenharia de Dados e DataOps (2025).

---

## 📌 Objetivo

Realizar análises e modelagens com base no dataset público do e-commerce brasileiro **Olist**, extraído do [Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce), simulando desafios reais da área de dados.

---

## 🧰 Tecnologias e Bibliotecas

- Python (Pandas, NumPy)
- Visualizações: Matplotlib, Seaborn
- Machine Learning: scikit-learn (RandomForest, KMeans)
- Ambiente: Jupyter Notebook

---

## 🧪 Etapas Realizadas

### 1. 📊 Preparação e Limpeza dos Dados
- Leitura dos CSVs do Kaggle
- Tratamento de nulos, duplicados e padronização de colunas

### 2. 📈 Análises Exploratórias
- Volume de pedidos por mês
- Distribuição do tempo de entrega
- Relação entre distância e valor do frete
- Categorias com maior faturamento
- Valor médio por estado

### 3. 👥 Análise de Retenção
- Apenas **3%** dos clientes são recorrentes

### 4. 📦 Predição de Atraso
- Modelo Random Forest
- Acurácia: 92%
- Desempenho limitado na classe "atrasado" devido ao desbalanceamento

### 5. 🧠 Segmentação de Clientes
- KMeans com 3 clusters (baixo, médio e alto valor)
- Identificação de perfis estratégicos

### 6. ⭐ Fatores que Impactam a Avaliação
- Tempo de entrega = principal fator de insatisfação

---

## 🖼️ Exemplos de Gráficos

> Veja a pasta `/imgs/` para as visualizações salvas.

---

## 📂 Arquivos

- `desafio_triggo.ipynb`: notebook com todo o código, gráficos e análises
- `df_unificado.csv`: base tratada e unificada (opcional)
- `README.md`: este arquivo com resumo explicativo

---

## 📬 Contato

Desenvolvido por **Rafael Santiago**  
🔗 [linkedin.com/in/santoraf09](https://linkedin.com/in/santoraf09)  
🐙 [github.com/santoraf09](https://github.com/santoraf09)

---

## ✅ Status

✔️ Desafio finalizado com sucesso.