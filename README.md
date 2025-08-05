
# 📘 TelecomX Churn Prediction – Parte 2

Este projeto tem como objetivo prever a evasão de clientes (churn) de uma empresa fictícia de telecomunicações, **Telecom X**, utilizando técnicas de Machine Learning. O trabalho contempla desde o tratamento dos dados até a modelagem e avaliação de diferentes algoritmos, com foco em fornecer insights estratégicos para o negócio.

## 📌 Objetivos do Projeto

- Limpeza e transformação de dados complexos e aninhados.
- Análise exploratória e de correlação para identificação de padrões.
- Treinamento e avaliação de modelos preditivos.
- Apoio à tomada de decisão com base nos resultados obtidos.

## 🧰 Tecnologias e Bibliotecas Utilizadas

- **Linguagem:** Python 3
- **Bibliotecas:**
  - `pandas`, `numpy` – manipulação de dados
  - `matplotlib`, `seaborn` – visualização
  - `sklearn` – pré-processamento, modelagem e métricas

## 🔄 Etapas do Projeto

1. **Carregamento dos dados**  
   Os dados foram carregados a partir de um arquivo `.json`, com estrutura aninhada.

2. **Pré-processamento**  
   - Expansão das colunas complexas (`customer`, `phone`, `internet`, `account`)
   - Conversão de colunas monetárias
   - Codificação de variáveis categóricas
   - Tratamento de valores ausentes

3. **Análise de Correlação**  
   Visualização da matriz de correlação para identificar variáveis mais relevantes.

4. **Modelagem**  
   Treinamento de dois modelos principais:
   - **Regressão Logística**
   - **Random Forest**

5. **Avaliação dos Modelos**  
   Métricas utilizadas:
   - Acurácia
   - Precisão
   - Recall
   - F1-Score
   - Matriz de Confusão
   - Classification Report

## 📊 Resultados

- O modelo de **Random Forest** apresentou melhor desempenho geral em comparação com a regressão logística, sendo mais adequado para previsões em contextos de churn.
- Algumas variáveis apresentaram alta correlação com o churn, como tipo de contrato, uso de serviços adicionais e tempo de relacionamento com a empresa.

## 🧠 Conclusão

O projeto evidenciou que é viável identificar, com boa precisão, os clientes com maior probabilidade de cancelar os serviços da Telecom X. O uso de técnicas de análise de dados e algoritmos de machine learning mostrou-se eficaz como suporte estratégico na retenção de clientes. Ao longo do desenvolvimento, foram aplicadas e consolidadas habilidades em manipulação e visualização de dados, engenharia de atributos e avaliação de modelos preditivos. Além disso, o trabalho reforçou o valor da análise de dados como ferramenta essencial para orientar decisões de negócio fundamentadas.

## 📁 Estrutura do Projeto

```
.
├── TelecomX_Churn_Prediction.ipynb
├── TelecomX_Data-2.json
├── README.md

```

## 🚀 Como executar


1. Clone este repositório:
   ```bash
   git clone https://github.com/MatheusLadeia/Desafio_TelecomX

2. Instale as dependências necessárias:
   ```bash
   pip install -r requirements.txt
   
3. Abra o notebook TelecomX_BR.ipynb em seu ambiente Jupyter:
   ```bash
   jupyter notebook

**Ou acesse no Google Colab:**  
[📎 Clique aqui para abrir no Colab](https://colab.research.google.com)



## 📬 Contato

Caso queira discutir ideias, sugerir melhorias ou colaborar, entre em contato!  
🔗 [LinkedIn – Matheus Ladeia](https://www.linkedin.com/in/matheusantos-ladeia/)

