# Dashboard_Subscri-o_Xbox_2024

# 📊 Dashboard de Assinaturas - Loja Xbox (Simulação Educacional)

Este projeto consiste em um dashboard desenvolvido em Excel com **dados fictícios** de assinaturas da loja Xbox. Ele tem como objetivo o **aprendizado em análise de dados, criação de KPIs e visualização de informações de negócios.**

Os dados utilizados são **simulados** e não representam valores reais.

---

## 🧾 Estrutura da Base de Dados

A principal tabela utilizada contém os seguintes campos:

| Campo                         | Descrição                                                    |
|-------------------------------|--------------------------------------------------------------|
| `Subscriber ID`               | Identificador único do assinante                             |
| `Name`                        | Nome do assinante                                            |
| `Plan`                        | Categoria da assinatura (Standard, Core ou Ultimate)         |
| `Start Date`                  | Data de início da assinatura                                 |
| `Auto Renewal`                | Se a renovação automática está ativada (Sim/Não)             |
| `Subscription Price`          | Valor do plano principal                                     |
| `Subscription Type`           | Tipo de plano assinado (mensal, trimestral, anual)           |
| `EA Play Season Pass`         | Indica se o assinante possui o passe da EA                   |
| `EA Play Season Pass Price`   | Valor do passe da EA                                         |
| `Minecraft Season Pass`       | Indica se o assinante possui o passe do Minecraft            |
| `Minecraft Season Pass Price` | Valor do passe do Minecraft                                  |
| `Coupon Value`                | Valor de desconto aplicado                                   |
| `Total Value`                 | Valor total pago pelo assinante (com adicionais e descontos) |

---

## 🧩 Tabelas de Apoio

### 📁 `assets`
Contém os elementos gráficos e visuais utilizados no dashboard:
- Logos das empresas e serviços (Xbox, EA, Minecraft)
- Paleta com 5 cores para padronização visual
- Imagens de avatar representando o usuário

### 📐 `calculos`
Esta aba armazena **métricas e KPIs** importantes, com fórmulas e filtros aplicados para responder perguntas de negócio como:
- **Faturamento total** com assinaturas, filtrado por tipo (mensal, trimestral, anual)
- **Total de assinaturas do EA Play**
- **Total de assinaturas do Minecraft**
- **Total de assinaturas apenas do Xbox Game Pass**

---

## 📊 Planilha `dashboard`

Painel visual interativo que exibe:
- Indicadores principais (faturamento e número de assinaturas por tipo de season pass)
- Destaques de produtos (EA Play, Minecraft, Game Pass)
- Elementos visuais padronizados para facilitar a leitura

---

## ✅ Objetivo do Projeto

Este projeto foi criado com fins **educacionais e de prática em visualização de dados**. Ele foi usado como base para:
- Demonstrar aprendizado em estruturar dados para dashboards
- Criar KPIs em planilhas
- Simular cenários de negócio baseados em serviços por assinatura

---

## ⚠️ Aviso

Todos os dados utilizados neste projeto são **fictícios e gerados para fins de aprendizado**. Nenhuma informação real ou sensível está presente.

---

## 📁 Arquivos

- `dashboard_xbox.xlsx` — arquivo principal do projeto com dados, cálculos e dashboard
- `README.md` — este documento com explicações
- `LICENSE` - licença do projeto

---

## 📫 Contato

Se quiser trocar ideias sobre projetos de análise ou dashboards, sinta-se à vontade para entrar em contato ou abrir uma issue.

