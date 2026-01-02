# Análise de Séries Temporais (CE017) - UFPR

Este repositório contém o primeiro trabalho prático da disciplina de Séries Temporais do curso de Estatística. O objetivo principal é demonstrar a aplicação de conceitos fundamentais de processos estocásticos e modelagem utilizando a linguagem R.

## 🛠️ Conteúdo do Projeto

O trabalho aborda três problemas principais da área:
1. **Simulação de Ruído Branco:** Comparação de ACF teórica vs. amostral e o impacto do tamanho da amostra ($n$) na precisão estatística.
2. **Modelagem Estrutural (Johnson & Johnson):** Ajuste de modelo com tendência linear e sazonalidade trimestral via variáveis indicadoras, incluindo análise de resíduos e cálculo de crescimento anual.
3. **Análise de Commodities (Petróleo e Gás):**
   - Teste de Estacionariedade.
   - Transformação de Log-Retornos $Y_t = \nabla \log(X_t)$.
   - Análise de Correlação Cruzada (CCF) e Regressão Retardada.
   - Investigação de Assimetria de Preços (efeito dos preços do petróleo na gasolina).

## 🚀 Tecnologias e Pacotes Utilizados

* **Linguagem:** R
* **Pacotes Principais:** `astsa` (Applied Statistical Time Series Analysis)
* **Relatório:** R Markdown (Gerado em PDF)

## 📈 Principais Insights Técnicos

* **Sazonalidade:** Foi identificado um crescimento anual de aproximadamente 18,2% no lucro das ações da J&J durante o período analisado.
* **Correlação Cruzada:** A análise demonstrou que as variações no preço do petróleo tendem a conduzir o preço da gasolina com uma defasagem de até 3 semanas.
* **Assimetria:** O modelo de regressão sugeriu que a resposta dos preços da gasolina é mais acentuada em períodos de alta do petróleo do que em períodos de queda.

## 📂 Arquivos

* [SeriesTemporais1.Rmd](./SeriesTemporais1.Rmd): Código fonte com as simulações e modelos.
* [SeriesTemporais1.pdf](./SeriesTemporais1.pdf): Relatório final formatado com gráficos e interpretações.

---
**Autor:** Luiz Henrique Barretta Francisco  
*Graduado em Estatística / Mestrando em Métodos Numéricos em Engenharia - UFPR*
