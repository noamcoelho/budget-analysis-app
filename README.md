# Budget Analysis App 💰

Este projeto tem como objetivo realizar uma análise completa de dados financeiros pessoais, com base em orçamentos planejados, transações reais e um resumo final que pode ser usado em dashboards ou aplicativos.

---

## 📌 Objetivos

- Analisar e comparar orçamentos planejados com despesas reais
- Identificar padrões de consumo
- Preparar dados para visualizações em dashboards (Power BI, Streamlit, etc.)
- Obter insights financeiros úteis para controle pessoal

---

## 📂 Estrutura dos Dados

Os dados são organizados em 3 arquivos principais:

- `Budget.csv`: valores orçados por categoria e mês
- `personal_transactions.csv`: lista de todas as transações financeiras realizadas
- `summary_for_app.csv`: resumo consolidado por mês e categoria para uso direto em dashboards

---

## ⚙️ Etapas da Análise (`main.ipynb`)

1. **Importação e pré-processamento dos dados**
   - Leitura dos arquivos CSV
   - Conversão de datas
   - Normalização de nomes de categorias

2. **Cruzamento de dados**
   - Agrupamento de gastos por categoria
   - Comparação entre orçado x realizado

3. **Geração de resumo mensal**
   - Cálculo do total de entrada e saída
   - Saldo por mês
   - Categorias com maior gasto

4. **Preparação para visualização**
   - Exportação do `summary_for_app.csv`
   - Formatação amigável

---

## 📊 Principais Resultados

- 🔍 **Diferenças claras entre orçamento planejado e gastos reais**
- 💸 **Categorias com maior impacto no orçamento:** alimentação, transporte e moradia
- 🧾 **Resumo mensal** com saldo positivo/negativo
- 📈 **Dados prontos para dashboards interativos**

---

## ▶️ Como Usar

### 1. Clone o repositório

```bash
git clone https://github.com/seu-usuario/budget-analysis-app.git
cd budget-analysis-app
