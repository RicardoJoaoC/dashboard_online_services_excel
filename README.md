# 📊 Projeto de Análise de Assinaturas

## 📌 Visão Geral

Esta planilha (**base.xlsx**) foi criada para organizar e analisar dados
de assinaturas, permitindo acompanhar clientes, planos contratados,
adicionais, descontos e receita total.

O modelo segue uma estrutura típica de BI: **Dados Brutos → Tratamento →
Visualização (Dashboard)**

------------------------------------------------------------------------

## 📁 Arquivo do Projeto

    base.xlsx

------------------------------------------------------------------------

## 🗂️ Estrutura das Abas

### 🔹 Bases (Base Principal)

Contém os dados transacionais dos assinantes (≈295 registros).

Campos utilizados: - **Subscriber ID** --- Identificador do cliente -
**Name** --- Nome - **Plan** --- Plano contratado - **Start Date** ---
Data de início - **Auto Renewal** --- Renovação automática (Sim/Não) -
**Subscription Price** --- Valor da assinatura - **Subscription Type**
--- Tipo do plano - **EA Play Season Pass** --- Possui adicional EA
Play - **EA Play Season Pass Price** --- Valor do adicional -
**Minecraft Season Pass** --- Possui adicional Minecraft - **Minecraft
Season Pass Price** --- Valor do adicional - **Coupon Value** ---
Desconto aplicado - **Total Value** --- Valor final pago

👉 Esta é a **fonte única de dados** da análise.

------------------------------------------------------------------------

### 🔹 Cálculos

Camada intermediária com fórmulas que tratam os dados da aba **Bases**.
Utilizada para: - Consolidações - Indicadores - Preparação para o
dashboard

⚠️ Não editar manualmente --- depende da base.

------------------------------------------------------------------------

### 🔹 Dashboard

Camada de visualização executiva. Apresenta: - Receita total -
Comparação entre planos - Impacto dos adicionais - Valores com desconto

Atualiza automaticamente ao alterar a aba **Bases**.

------------------------------------------------------------------------

### 🔹 Assets

Aba auxiliar com elementos de apoio visual e estrutural do dashboard.

------------------------------------------------------------------------

## 🔄 Fluxo de Funcionamento

    Entrada de Dados (Bases)
            ↓
    Tratamento (Cálculos)
            ↓
    Visualização (Dashboard)

------------------------------------------------------------------------

## ▶️ Como Reproduzir

### Requisitos

-   Excel 2019+ ou Microsoft 365

### Passo a Passo

1️⃣ Abra o arquivo:

    base.xlsx

2️⃣ Vá até **Bases** e insira ou altere registros.

3️⃣ Não altere a aba **Cálculos**.

4️⃣ Acesse **Dashboard** para visualizar os resultados.

------------------------------------------------------------------------