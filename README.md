# Tech Challenge - Previsão de Tendência do Ibovespa

Este repositório apresenta uma solução completa desenvolvida para a **Fase 2 do Tech Challenge da Pós-Tech FIAP**. O desafio propõe a criação de um modelo de machine learning capaz de prever se o índice **Ibovespa** fechará em **alta (↑)** ou **baixa (↓)** no dia seguinte, com base em dados históricos reais.

---

## Objetivos do Projeto

* Prever a tendência de fechamento do Ibovespa com acurácia mínima de **75%**.
* Utilizar dados históricos com abordagem sequencial realista.
* Integrar modelo a um pipeline de análise quantitativa.
* Desenvolver storytelling e apresentação para time de decisão.

---

## Tecnologias Utilizadas

* **Linguagem:** Python 3
* **Bibliotecas:** pandas, matplotlib, seaborn, scikit-learn
* **Modelo:** Random Forest Classifier (sklearn)
* **Visualização:** Seaborn e Matplotlib

---

## Estrutura dos Arquivos

| Arquivo                                     | Descrição                                                                    |
| ------------------------------------------- | -----------------------------------------------------------------------------|
| `Dados Históricos - Ibovespa - 20 anos.csv` | Base de dados em CSV que contempla 20 anos de dados (27/06/2005 a 25/07/2025)|
| `postechfiap_predição_bovespa.ipynb`        | Script com o modelo Random Forest para prever a tendência do dia seguinte    |
 
---

## Resultados Alcançados

* Modelo alcançou acurácia de **acima de 80%** no conjunto de teste (30 dias mais recentes).
* Respeito total à natureza temporal dos dados (sem shuffle).
* Foco em aplicação realista no contexto de fundos quantitativos.

---

## Próximos Passos
* Incluir features técnicas: médias móveis, RSI, bandas de Bollinger
* Automatizar ingestão de dados com coleta via API/scraping
* Criar dashboard interativo para visualização dos resultados

---

## Referências

* Dados: [Investing.com - Histórico do Ibovespa](https://br.investing.com/indices/bovespa-historical-data)
* Documentação Scikit-learn: [https://scikit-learn.org](https://scikit-learn.org)
* Documentação pandas: [https://pandas.pydata.org](https://pandas.pydata.org)

---

## 🙏 Agradecimentos

Agradecimentos à coordenação da Pós-Tech FIAP, docentes e colegas de turma pelo suporte e feedback durante o desenvolvimento do desafio.

> Desenvolvido por: Ana, Bruno, Carlos, Daniela e Eduardo
