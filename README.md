# 📊 Análise de Regressão Linear Múltipla para Avaliação do Impacto de Investimentos em Publicidade nas Vendas

## 📌 Visão Geral

Este projeto aplica técnicas de estatística e regressão linear múltipla para analisar o impacto dos investimentos em diferentes canais de publicidade (TV, Rádio e Jornal) sobre o resultado de vendas.

O objetivo principal é compreender a relação entre investimento em marketing e retorno em vendas, além de avaliar a qualidade estatística do modelo através da análise de pressupostos fundamentais da regressão linear.

Este projeto demonstra a aplicação prática de conceitos estatísticos essenciais para modelagem preditiva e inferência em ciência de dados.

---

## 🎯 Objetivo

Desenvolver e avaliar um modelo de regressão linear múltipla capaz de explicar e prever o resultado das vendas com base nos investimentos em publicidade, incluindo:

* Análise exploratória dos dados
* Avaliação das relações entre variáveis
* Construção do modelo de regressão
* Validação estatística do modelo
* Análise de pressupostos e qualidade do ajuste

---

## 🧠 Conceitos e Técnicas Aplicadas

Este projeto envolve a aplicação de técnicas fundamentais de estatística e machine learning, incluindo:

### Análise Exploratória de Dados (EDA)

* Estatísticas descritivas
* Análise univariada e bivariada
* Histogramas e boxplots
* Análise de correlação
* Matriz de covariância
* Visualização de dispersão

### Modelagem Estatística

* Regressão Linear Múltipla (OLS - Ordinary Least Squares)
* Estimação de coeficientes
* Interpretação estatística dos parâmetros

### Validação de Pressupostos do Modelo

* Análise de resíduos
* Teste de homocedasticidade (Breusch-Pagan)
* Teste de normalidade dos resíduos (Shapiro-Wilk)
* Análise gráfica com QQ-Plot
* Teste de autocorrelação (Durbin-Watson)
* Detecção de outliers

### Diagnóstico de Multicolinearidade

* Cálculo do Variance Inflation Factor (VIF)
* Avaliação da independência entre variáveis explicativas

### Avaliação Estatística do Modelo

* Coeficiente de determinação (R² e R² ajustado)
* Teste F global do modelo
* Teste t de significância dos coeficientes
* Análise da especificação do modelo

---

## 🛠️ Tecnologias e Ferramentas Utilizadas

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Statsmodels
* Jupyter Notebook

---

## 📊 Etapas do Projeto

O projeto foi desenvolvido seguindo um pipeline estruturado de análise de dados:

1. Carregamento e inspeção inicial dos dados
2. Validação da qualidade dos dados (tipos, valores faltantes, consistência)
3. Análise exploratória univariada e bivariada
4. Análise de correlação e covariância entre variáveis
5. Construção do modelo de regressão linear múltipla
6. Análise detalhada dos resíduos do modelo
7. Testes estatísticos para validação dos pressupostos da regressão
8. Análise de multicolinearidade entre variáveis independentes
9. Avaliação da qualidade e adequação do modelo

---

## 📈 Resultados e Principais Insights

Os principais achados da análise incluem:

* O modelo apresentou alto poder explicativo, com coeficiente de determinação R² de aproximadamente 0.897, indicando que cerca de 89,7% da variabilidade das vendas pode ser explicada pelas variáveis analisadas.

* As variáveis de investimento em publicidade apresentaram relação positiva com o resultado das vendas, confirmando a expectativa teórica.

* Foram identificadas limitações importantes no modelo, incluindo:

  * Indícios de heterocedasticidade
  * Resíduos que não seguem distribuição normal
  * Presença de outliers
  * Possível especificação incompleta do modelo

* Não foram identificados problemas significativos de multicolinearidade entre as variáveis explicativas.

Esses resultados reforçam a importância da validação estatística completa do modelo, não apenas sua capacidade preditiva.

---

## 🎓 Contexto Acadêmico

Este projeto foi desenvolvido como parte de exercícios práticos da pós-graduação em Inteligência Artificial e Aprendizado de Máquina, com foco na aplicação de técnicas de estatística aplicada e modelagem preditiva utilizando Python.

O objetivo foi consolidar conceitos fundamentais de regressão linear múltipla, diagnóstico de modelos e inferência estatística.

---

## 🚀 Competências Demonstradas

Este projeto demonstra as seguintes competências relevantes para atuação como Cientista de Dados:

* Análise exploratória de dados (EDA)
* Modelagem estatística com regressão linear múltipla
* Validação e diagnóstico de modelos estatísticos
* Interpretação de resultados estatísticos
* Análise de resíduos e validação de pressupostos
* Aplicação de testes estatísticos
* Detecção de multicolinearidade
* Visualização de dados
* Utilização de Python para análise de dados
* Uso da biblioteca Statsmodels para inferência estatística

---

## 📁 Estrutura do Projeto

```
lista_01_exer_01_deivison_morais.ipynb   # Notebook contendo toda a análise
propaganda.csv                          # Dataset utilizado
README.md                               # Documentação do projeto
```

---

## ✅ Conclusão

Este projeto demonstra a aplicação prática de técnicas de regressão linear múltipla em um problema realista de análise de impacto de investimentos em publicidade, incluindo não apenas a construção do modelo, mas também uma análise rigorosa dos pressupostos estatísticos e da qualidade do ajuste.

A análise evidencia a importância do diagnóstico estatístico completo para garantir a confiabilidade de modelos preditivos, competência essencial para cientistas de dados em ambientes profissionais.
