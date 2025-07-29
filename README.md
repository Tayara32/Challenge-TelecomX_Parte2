# 📊 Telecom X – Prevendo Churn (Parte 2)

Este projeto foi desenvolvido como parte de um desafio de Machine Learning, com foco em **antecipar a evasão de clientes (churn)** em uma operadora de telecomunicações. A missão é clara: ajudar a empresa a identificar, com antecedência, quais clientes estão prestes a abandonar os serviços.

## 🎯 Objetivo

Criar modelos preditivos capazes de prever o churn de clientes com base em seus dados históricos e comportamentais, oferecendo insights estratégicos que ajudem na **retenção**.

## 🧪 Etapas do Projeto

- **Pré-processamento dos dados**
  - Tratamento de valores ausentes e inconsistentes
  - Codificação de variáveis categóricas (`LabelEncoder`, `OneHotEncoder`)
  - Normalização dos dados numéricos para algoritmos sensíveis à escala

- **Análise exploratória e seleção de variáveis**
  - Avaliação de correlação entre atributos
  - Identificação e remoção de colinearidades
  - Foco em variáveis mais influentes para o churn

- **Treinamento de modelos preditivos**
  - Modelos utilizados:
    - `RandomForestClassifier`
    - `LogisticRegression`
    
- **Avaliação de desempenho**
  - Métricas aplicadas: Accuracy, Precision, Recall, F1-Score e ROC AUC
  - Validação cruzada para garantir robustez

- **Interpretação dos resultados**
  - Análise da importância das variáveis
  - Identificação dos principais fatores que levam ao cancelamento

## 📌 Principais Insights

- Clientes com **contratos mensais**, **baixo tempo de permanência** e **sem serviços adicionais** têm maior tendência a cancelar.
- **Forma de pagamento**, **tipo de internet contratada** e **número de serviços ativos** também são determinantes no comportamento de churn.

## 🧠 Conclusão Estratégica

A Telecom X pode **reduzir o churn** ao:

- Criar programas de fidelização para clientes com contratos mensais.
- Oferecer vantagens progressivas conforme o tempo de permanência aumenta.
- Incentivar pacotes mais completos e o uso de serviços adicionais.

## 🛠️ Tecnologias Utilizadas

- Python 3.8+
- Pandas
- NumPy
- Scikit-learn
- Matplotlib e Seaborn
- (Adicione outras bibliotecas, como XGBoost, SHAP, etc., se tiver usado)

## 🙋‍♀️ Sobre Mim

Sou **Tayara**, Futura Analista de Dados, apaixonada por entender como as coisas funcionam. Em transição da Administração para a área Tech, focada em **Java** e **Análise de Dados**. Meu objetivo é claro: **me destacar no mercado com projetos inteligentes, práticos e que gerem impacto real**. 🚀

---

> 💡 *"Dados bem analisados não mentem. Eles gritam soluções."*
