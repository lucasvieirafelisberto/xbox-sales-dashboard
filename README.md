# 🎮 Xbox Game Pass — Sales Subscriptions Dashboard

> **Desafio DIO × TOTVS** — Fundamentos de Engenharia de Dados e Machine Learning

---

## 📋 Sobre o Projeto

Este projeto tem como objetivo transformar dados brutos de assinaturas Xbox Game Pass em um **dashboard de vendas profissional no Microsoft Excel**, permitindo análise visual clara do desempenho comercial e suporte à tomada de decisões baseada em dados.

O desafio foi proposto pela plataforma **DIO (Digital Innovation One)** em parceria com a **TOTVS**, como parte da trilha de **Fundamentos de Engenharia de Dados e Machine Learning**.

---

## 🗂️ Estrutura do Repositório

```
📁 xbox-sales-dashboard/
├── 📊 Xbox_Sales_Dashboard.xlsx   ← Dashboard final completo
├── 📄 Base.xlsx                   ← Base de dados original
└── 📝 README.md                   ← Este arquivo
```

---

## 📊 Dataset — Base de Dados

O arquivo `Base.xlsx` contém **295 registros de assinantes** com as seguintes colunas:

| Coluna | Descrição |
|---|---|
| `Subscriber ID` | ID único do assinante |
| `Name` | Nome do assinante |
| `Plan` | Plano contratado (Core / Standard / Ultimate) |
| `Start Date` | Data de início da assinatura |
| `Auto Renewal` | Se tem renovação automática (Yes / No) |
| `Subscription Price` | Preço base da assinatura |
| `Subscription Type` | Tipo de assinatura (Monthly / Quarterly / Annual) |
| `EA Play Season Pass` | Se possui EA Play (Yes / No) |
| `EA Play Season Pass Price` | Valor do EA Play |
| `Minecraft Season Pass` | Se possui Minecraft Pass (Yes / No) |
| `Minecraft Season Pass Price` | Valor do Minecraft Pass |
| `Coupon Value` | Desconto de cupom aplicado |
| `Total Value` | Valor total pago pelo assinante |

---

## 📈 Estrutura do Dashboard (Excel)

O arquivo `Xbox_Sales_Dashboard.xlsx` está organizado em **4 abas**:

### 🎨 Aba 1 — Assets
Paleta de cores oficial da marca Xbox utilizada em todo o dashboard:

| Cor | Hex | Uso |
|---|---|---|
| Verde Xbox | `#9BC848` | Destaques visuais |
| Verde Brilhante | `#22C55E` | Cabeçalhos e KPIs |
| Teal | `#2AE6B1` | Menus e elementos secundários |
| Menta | `#5BF6A8` | Elementos de suporte |
| Cinza Claro | `#E8E6E9` | Zonas negativas / fundos |
| Preto Escuro | `#0D1117` | Background principal |

---

### 📋 Aba 2 — Bases
Tabela formatada com todos os **295 registros brutos** de assinantes, com:
- Cabeçalhos em verde Xbox
- Linhas alternadas para leitura facilitada
- Freeze pane na linha 1 para navegação facilitada
- Formatação de datas e valores monetários

---

### 🔢 Aba 3 — Cálculos
Análises com Tabelas Dinâmicas e fórmulas Excel respondendo às **5 perguntas de negócio**:

| # | Pergunta de Negócio |
|---|---|
| Q1 | Qual o faturamento total de vendas por tipo de assinatura? |
| Q2 | Qual o faturamento de planos anuais, separado por Auto Renovação? |
| Q3 | Qual o faturamento de planos mensais, separado por Auto Renovação? |
| Q4 | Qual o faturamento e ticket médio por plano (Core/Standard/Ultimate)? |
| Q5 | Qual a receita gerada pelos add-ons (EA Play e Minecraft Season Pass)? |

---

### 📊 Aba 4 — Dashboard
Painel visual com:

**🔢 KPI Cards:**
- 💰 **Receita Total:** $7.633
- 📅 **Planos Anuais:** $1.754
- 📆 **Planos Mensais:** $3.571
- 📊 **Planos Trimestrais:** $2.308

**📋 Tabelas de Análise:**
- Faturamento Anual por Auto Renovação (Q1 & Q2)
- Faturamento Mensal por Auto Renovação (Q3)
- Faturamento por Plano com Ticket Médio (Q4)
- Receita de Add-ons EA Play & Minecraft (Q5)

**📈 Gráficos:**
- Gráfico de colunas — Receita por Plano (Core / Standard / Ultimate)
- Gráfico de pizza — Distribuição por Tipo de Assinatura

---

## 🔍 Principais Insights

| Métrica | Valor |
|---|---|
| Total de Assinantes | 295 |
| Receita Total | **$7.633** |
| Plano mais rentável | **Ultimate** ($5.388 — 70,6% da receita) |
| Tipo mais popular | **Monthly** (139 assinantes) |
| Maior receita por tipo | **Monthly** ($3.571) |
| Add-on mais adotado | **Minecraft** (194 assinantes) |
| Receita Anual com renovação | $1.537 (87,6% do total anual) |
| Ticket Médio Ultimate | **$54,98** |
| Ticket Médio Core | **$4,40** |

---

## 🛠️ Tecnologias Utilizadas

- **Microsoft Excel** — Dashboard, tabelas dinâmicas, gráficos e formatação
- **Git** — Controle de versão
- **GitHub** — Hospedagem e entrega do projeto

---

## ▶️ Como Reproduzir

1. Faça o download do arquivo `Xbox_Sales_Dashboard.xlsx`
2. Abra com **Microsoft Excel 2016** ou superior
3. Navegue pelas 4 abas: **Assets → Bases → Cálculos → Dashboard**

---

## 📁 Dados Utilizados

Os dados são fictícios, gerados para fins educacionais no contexto do desafio DIO × TOTVS. Representam assinantes do **Xbox Game Pass** no período de **Janeiro a Dezembro de 2024**, com os planos Core, Standard e Ultimate.

---

## 👤 Autor

Desenvolvido por **Lucas Vieira** como parte do desafio **DIO × TOTVS — Fundamentos de Engenharia de Dados e Machine Learning**.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Lucas%20Vieira-0A66C2?style=flat&logo=linkedin)](https://www.linkedin.com/in/lucasvieirafelisberto)
[![GitHub](https://img.shields.io/badge/GitHub-lucasvieirafelisberto-181717?style=flat&logo=github)](https://github.com/lucasvieirafelisberto)

---

## 📄 Licença

Este projeto está sob a licença MIT. Consulte o arquivo `LICENSE` para mais detalhes.