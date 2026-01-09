# 📊 Análise de Vendas — Loja Online de Eletrônicos

Projeto demonstrativo de **Análise de Dados**, com foco em limpeza de dados, análise exploratória, geração de insights e comunicação dos resultados por meio de relatório executivo.

---

## 📌 Contexto

Este projeto utiliza um conjunto de dados **fictício** de vendas de uma loja online de eletrônicos.  
O objetivo é simular desafios reais enfrentados por analistas de dados, incluindo **problemas de qualidade nos dados**, validação de regras de negócio e interpretação dos resultados para apoio à tomada de decisão.

---

## 🎯 Objetivos da Análise

- Avaliar o desempenho comercial da loja  
- Identificar produtos e categorias mais relevantes em termos de receita  
- Analisar o perfil e o comportamento dos clientes  
- Avaliar a eficiência operacional dos pedidos  
- Investigar a qualidade e consistência dos dados  
- Gerar insights e recomendações acionáveis  

---

## 🧹 Tratamento e Qualidade dos Dados

Durante a análise, foram identificados e tratados problemas comuns de dados, como:

- Valores ausentes e inválidos  
- Inconsistências textuais (ex.: nomes de cidades)  
- Violações de regras de negócio  
- Campos numéricos em formato incorreto  

As decisões de tratamento foram documentadas ao longo do notebook técnico.

---

## 📈 Principais Análises Realizadas

- Receita total e receita por categoria  
- Produtos mais vendidos  
- Distribuição etária dos clientes  
- Ticket médio por cliente e por faixa etária  
- Análise de status dos pedidos (entregue, cancelado, devolvido)  
- Avaliação das formas de pagamento e sua relação com cancelamentos  

---

## 🧠 Principais Insights

- A receita está concentrada em poucas categorias de alto valor agregado  
- Clientes em faixas etárias intermediárias apresentam maior ticket médio  
- Cancelamentos e devoluções estão associados a categorias e formas de pagamento específicas  

---

## 🎯 Recomendações

- Priorizar categorias com maior impacto na receita  
- Investigar causas de cancelamento em categorias críticas  
- Revisar fluxos de pagamento associados a maior taxa de cancelamento  
- Explorar segmentação de clientes para campanhas direcionadas  

---

## 📄 Relatório Executivo

Um **relatório executivo em PDF**, sem código, foi gerado para apresentar os principais resultados de forma clara e objetiva.

📂 Local: `/relatorio/relatorio_da_analise.pdf`

---

## 🗂 Estrutura do Projeto

📁 analise-vendas-loja-online
├── assets/
│ └── imagens dos gráficos utilizados no relatório
├── data/
│ └── vendas_loja_online.csv
├── notebook/
│ └── analise_tecnica.ipynb
├── relatorio/
│ └── relatorio_analise_vendas.pdf
└── README.md
