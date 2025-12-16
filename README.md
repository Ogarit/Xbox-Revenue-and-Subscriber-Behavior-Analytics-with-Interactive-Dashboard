# 📊 Análise de Receita e Comportamento de Assinantes Xbox

Este projeto apresenta um **dashboard analítico interativo** desenvolvido a partir de dados simulados de assinaturas do ecossistema **Xbox**, com foco em **receita**, **planos de assinatura**, **upsell de serviços** e **comportamento de renovação**.

O objetivo é demonstrar habilidades em **análise de dados**, **modelagem analítica** e **visualização gerencial**, aplicadas a um cenário realista de negócio.

## 🎯 Objetivos do Projeto

- Analisar a **receita total** proveniente de assinaturas Xbox
- Avaliar o impacto de **upsell** (EA Play e Minecraft Season Pass)
- Investigar o comportamento de **renovação automática**
- Identificar oportunidades de **aumento de ticket médio** e **previsibilidade de receita**

## 🧠 Perguntas de Negócio Respondidas

- Qual faturamento Total de Vendas de Planos Anuais (contendo todas as assinaturas agregadas)?
- Qual Faturamento Total de Vendas de Planos Anuais, separado por Auto Renovação Não é por Auto Renovação?
- Total de Vendas de Assinatura do EA Play
- Total de Vendas de Assinatura do Minecraft Season Pass

## 📁 Estrutura dos Dados

Cada registro representa um **assinante único**, contendo:

- Tipo de plano (Core, Standard, Ultimate)
- Modelo de cobrança (Monthly, Quarterly, Annual)
- Valor da assinatura
- Valor de passes adicionais:
  - EA Play Season Pass
  - Minecraft Season Pass
- Valor de desconto (cupons)
- Valor total consolidado
- Status de renovação automática
- Data de início da assinatura

## 📊 Principais Indicadores (KPIs)

- Receita Total Consolidada
- Ticket Médio por Plano
- Distribuição de Assinantes por Tipo de Plano
- Receita com vs. sem Upsell
- Percentual de Renovação Automática
- Impacto dos Cupons na Receita Final

## 🛠️ Ferramentas Utilizadas

- **Excel** (tratamento inicial dos dados)
- **Power BI** (modelagem, DAX e visualizações)
- **Git & GitHub** (versionamento e portfólio)

## 📈 Metodologia Analítica

1. Entendimento do contexto de negócio
2. Exploração e validação dos dados
3. Criação de métricas derivadas
4. Análise descritiva e comparativa
5. Construção de dashboard interativo
6. Geração de insights orientados a decisão

## 🚀 Insights Principais

- O plano **Ultimate** concentra o maior ticket médio
- Upsells (EA Play e Minecraft) têm impacto maior que o plano base em diversos casos
- Assinantes com **renovação automática** apresentam maior previsibilidade de receita
- Cupons reduzem valor final, mas ampliam adesão em planos intermediários

## 📌 Possíveis Evoluções do Projeto

- Normalização dos valores para **MRR (Monthly Recurring Revenue)**
- Análise temporal e criação de **coortes**
- Segmentação de usuários premium
- Simulação de cenários de precificação
- Integração com Python para ETL e automação

## 📂 Como Executar

1. Clone o repositório:
```bash
   git clone https://github.com/seu-usuario/nome-do-repositorio.git
````

2. Abra o arquivo do dashboard no **Power BI Desktop**
3. Explore os filtros e visualizações interativas

## 📎 Observação

Os dados utilizados são **simulados**, não representando informações reais da Microsoft ou do Xbox.
