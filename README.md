# salesanalysis
# 📊 Dashboard de Performance Comercial e Faturamento

## Sobre o Projeto

Este projeto consiste em um dashboard analítico desenvolvido em Power BI para monitoramento da performance comercial, faturamento, receita bruta, descontos e margens de vendas.

A solução foi construída com foco em Business Intelligence, permitindo a análise dos resultados em diferentes níveis hierárquicos, desde indicadores executivos até o detalhamento individual das transações.

O painel fornece uma experiência completa de exploração de dados por meio de visualizações interativas, filtros dinâmicos e recursos avançados de análise.

---

## 🎯 Objetivos

- Monitorar indicadores financeiros e comerciais.
- Avaliar a evolução da receita ao longo do tempo.
- Comparar resultados entre períodos.
- Identificar oportunidades de crescimento.
- Analisar o comportamento de produtos e marcas.
- Investigar o desempenho por estado e cidade.
- Apoiar a tomada de decisão baseada em dados.

---

## 🏗 Arquitetura da Solução

```text
Fonte de Dados
      │
      ▼
Power Query
(ETL e Tratamento)
      │
      ▼
Modelo Dimensional
      │
      ▼
Medidas DAX
      │
      ▼
Dashboard Power BI
      │
 ┌────┼────┐
 ▼    ▼    ▼
Resumo Decomposição Tabela
```

---

## 📈 Páginas do Dashboard

### 1. Resumo Executivo

Painel estratégico voltado para acompanhamento dos principais indicadores de negócio.

#### Indicadores Apresentados

- Receita Bruta
- Valor Total de Descontos
- Margem Comercial
- Crescimento YoY
- Comparação com Ano Anterior
- Participação por Canal de Venda
- Participação por Marca

#### Recursos

✅ Cards de KPI

✅ Comparativos de desempenho

✅ Gráficos de evolução temporal

✅ Participação por canal

✅ Ranking de marcas

✅ Análise de categorias

---

### 2. Árvore de Decomposição

Análise hierárquica dos indicadores utilizando o visual nativo de Decomposition Tree do Power BI.

Permite navegar entre diferentes dimensões de negócio.

#### Hierarquia Analítica

```text
Receita/Faturamento

├── Marca
├── Categoria
├── Subcategoria
├── Produto
├── Estado (UF)
└── Cidade
```

#### Casos de Uso

- Identificar marcas com maior resultado.
- Avaliar categorias mais lucrativas.
- Localizar regiões com melhor desempenho.
- Analisar participação de produtos em cada mercado.

---

### 3. Visão Tabular

Consulta detalhada das vendas registradas.

#### Campos Disponíveis

- Data da Venda
- SKU
- Produto
- Canal
- Estado (UF)
- Cidade
- Quantidade
- Desconto
- Receita Bruta

#### Funcionalidades

- Pesquisa textual
- Consulta individual de registros
- Navegação detalhada
- Auditoria de transações

---

## 📊 Indicadores Implementados

### Financeiros

- Receita Bruta
- Faturamento Bruto
- Valor de Desconto
- Margem (%)

### Comerciais

- Quantidade Vendida
- Receita por Marca
- Receita por Categoria
- Receita por Produto

### Comparativos

- Ano Atual vs Ano Anterior
- Crescimento YoY
- Share por Categoria
- Participação por Canal

---

## 🎨 Design e Experiência do Usuário

### Características

- Layout Dark Theme
- Navegação lateral intuitiva
- Interface moderna
- Baixa curva de aprendizado
- Foco na experiência do usuário

### Navegação

```text
Dashboard
│
├── Resumo
│
├── Decomposição
│
└── Tabela
```

---

## 🔧 Tecnologias Utilizadas

### Plataforma

- Microsoft Power BI Desktop

### Linguagens

- DAX
- Power Query (M)

### Conceitos Aplicados

- ETL
- Modelagem Dimensional
- Star Schema
- KPI Management
- Data Visualization
- Business Intelligence

---

## 📂 Estrutura Analítica

```text
Vendas
│
├── Marca
│   ├── Samsung
│   ├── Apple
│   ├── LG
│   └── ASUS
│
├── Categoria
│   ├── Informática
│   ├── Celulares
│   ├── Eletrodomésticos
│   └── Games
│
├── Produto
│
├── Região
│   ├── Estado
│   └── Cidade
│
└── Tempo
    ├── Ano
    ├── Mês
    └── Data
```

---

## 🚀 Benefícios Obtidos

- Visão única dos indicadores comerciais.
- Redução do tempo de análise.
- Maior autonomia dos usuários.
- Monitoramento contínuo dos resultados.
- Identificação rápida de oportunidades e desvios.
- Apoio à tomada de decisão baseada em dados.

---

## 📷 Funcionalidades em Destaque

### Dashboard Executivo

Monitoramento dos principais indicadores financeiros e comerciais.

### Decomposition Tree

Drill-down dinâmico para identificação de causas e oportunidades.

### Consulta Analítica

Visualização detalhada e auditável das transações.

---

## 👨‍💻 Autor

Projeto desenvolvido para fins de análise comercial e Business Intelligence utilizando Power BI, DAX e Power Query.

---

## 📄 Licença

Este projeto está disponível para estudos, demonstração de portfólio e fins educacionais.
