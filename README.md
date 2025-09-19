# Análise de Séries Temporais - Dados do Banco Central

Este projeto utiliza dados públicos do **Banco Central do Brasil (SGS 21086)** para análise de séries temporais, explorando tendências, sazonalidade e estacionariedade.

## Estrutura do Projeto
- **Coleta de Dados:** Requisições via `requests` à API do BCB.  
- **Pré-processamento:** Limpeza, criação de colunas auxiliares (diferenças, tempo).  
- **Análise Exploratória:** Estatísticas descritivas e gráficos com `matplotlib`.  
- **Modelagem:**  
  - Regressão linear (OLS) para tendência.  
  - Testes de estacionariedade (ADF).  
  - Transformações (diferenciação).  
- **Visualizações:** Séries originais, séries diferenciadas, resíduos e diagramas ilustrativos.

## Principais Bibliotecas
- `pandas`  
- `matplotlib`  
- `statsmodels`  
- `requests`

## Objetivo
Explorar a série temporal de inadimplência, avaliando:
- Presença de tendência e sazonalidade.  
- Estacionariedade da série.  
- Transformações necessárias para análise robusta.
