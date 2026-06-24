# erp-analytics-dashboard

Este projeto consiste em um dashboard gerencial desenvolvido para consolidar e visualizar os dados dos módulos de um sistema ERP, permitindo uma visão integrada e estratégica do negócio.

Os dados são provenientes de um **Data Warehouse (DW)** conectado ao Power BI por meio de um driver **ODBC**, centralizando informações de diferentes módulos do sistema em relatórios interativos.

## Módulos Cobertos

| Módulo | Descrição |
|--------|-----------|
| 💰 **Orçamento** | Acompanhamento de orçamentos gerados, aprovados e pendentes |
| 🏭 **PCP** | Planejamento e Controle da Produção — ordens, prazos e capacidade |
| 🧾 **Faturamento** | Receitas, notas fiscais emitidas e volume de vendas |
| 📦 **GCE** | Gestão de Compras |
| 🏦 **Financeiro** | Fluxo de caixa, contas a pagar/receber e inadimplência |


## 🛠️ Tecnologias e Ferramentas

- **Power BI Desktop** — modelagem, DAX e visualizações
- **ODBC** — conexão entre o DW e o Power BI
- **DAX** — medidas e KPIs calculados


## 💡 Aprendizados

- Modelagem dimensional de dados em ambiente de DW real
- Integração de múltiplas fontes via ODBC
- Criação de medidas DAX para KPIs de negócio
- Design de dashboards orientados à tomada de decisão gerencial
