# 📊 Dashboard de Big Data com Pandas e Plotly

Este projeto foi desenvolvido para análise de dados da empresa **Dancor**, utilizando **Python, Pandas e Plotly**.  
O programa lê dados de um arquivo Excel (`Planejamento (1).xlsx`), gera gráficos interativos e exporta um **dashboard único em HTML**.

---

## 🚀 Funcionalidades

- Leitura de múltiplas abas do Excel:
  - **Resumo**
  - **Assertividade**
  - **Ciclo**
  - **Reserva Parcial**
  - **Reserva Integral**
  - **Reservado-Crédito**
- Padronização de colunas para evitar erros de cabeçalho.
- Geração de 4 gráficos:
  1. **Barras**: Pedidos vs Faturamento por Divisão.
  2. **Linha**: Evolução da Assertividade.
  3. **Pizza**: Distribuição dos Pedidos por Status.
  4. **Barras empilhadas**: Status dos Pedidos por Produto.
- Exportação dos gráficos em:
  - Arquivos **PNG** individuais (`C:/bigdata/graficos/`).
  - Um **HTML único** (`C:/bigdata/dashboard.html`) com todos os gráficos juntos.

---

## 📦 Dependências

Instale os pacotes necessários:

```bash
pip install pandas plotly kaleido openpyxl


