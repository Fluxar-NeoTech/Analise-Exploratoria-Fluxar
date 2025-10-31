# Exploratory Data Analysis – Projeto Fluxar

<div style="background:#F7F3FF; font-family: Poppins, Segoe UI; border-left:8px solid #FFA726; padding:18px; border-radius:10px; margin-top:24px; width:97%; color:#4B0055">

Este notebook realiza uma **Análise Exploratória de Dados (EDA)** sobre o conjunto de dados de estoque, com o objetivo de identificar padrões, tendências e gargalos operacionais.  
O foco é gerar **insights estratégicos** que possam orientar melhorias no app e na gestão de inventário.
</div>

---

## Etapa 1 – Importação de Bibliotecas e Dataset
<div style="background:#F7F3FF; font-family: Poppins, Segoe UI; border-left:8px solid #FFA726; padding:18px; border-radius:10px; margin-top:12px; width:97%; color:#4B0055">

**O que esperar:**  
- Importação das bibliotecas essenciais (`pandas`, `numpy`, `matplotlib`, `seaborn`, `kagglehub`);  
- Download do dataset via **KaggleHub**;  
- Visualização inicial com tabelas estilizadas (`display(... .style.set_table_styles(...))`).  

**Objetivo:**  
Compreender a estrutura do dataset — colunas, tipos, dimensões e primeiras observações.
</div>

---

## Etapa 2 – Limpeza e Pré-processamento Inicial
<div style="background:#F7F3FF; font-family: Poppins, Segoe UI; border-left:8px solid #FFA726; padding:18px; border-radius:10px; margin-top:12px; width:97%; color:#4B0055">

**O que esperar:**  
- Verificação e tratamento de valores ausentes (`NaN`);  
- Correção de tipos de dados (datas, inteiros, floats);  
- Normalização dos nomes das colunas.  

**Objetivo:**  
Garantir consistência e qualidade dos dados antes das análises principais.
</div>

---

## Etapa 3 – Análise Descritiva
<div style="background:#F7F3FF; font-family: Poppins, Segoe UI; border-left:8px solid #FFA726; padding:18px; border-radius:10px; margin-top:12px; width:97%; color:#4B0055">

**O que esperar:**  
- Estatísticas descritivas com `describe()`;  
- Contagem de SKUs, categorias e armazéns;  
- Métricas de estoque, vendas e lead time (média, mínimo, máximo, desvio padrão).  

**Objetivo:**  
Explorar o comportamento geral dos dados e identificar padrões iniciais.
</div>

---

## Etapa 4 – Visualização Exploratória
<div style="background:#F7F3FF; font-family: Poppins, Segoe UI; border-left:8px solid #FFA726; padding:18px; border-radius:10px; margin-top:12px; width:97%; color:#4B0055">

**O que esperar:**  
- Histogramas e boxplots para distribuições e outliers;  
- Gráficos comparativos (ex.: estoque por categoria ou warehouse);  
- Séries temporais (vendas e estoque ao longo do tempo).  

**Objetivo:**  
Visualizar tendências, sazonalidades e possíveis problemas operacionais.
</div>

---

## Etapa 5 – Análise de Correlações
<div style="background:#F7F3FF; font-family: Poppins, Segoe UI; border-left:8px solid #FFA726; padding:18px; border-radius:10px; margin-top:12px; width:97%; color:#4B0055">

**O que esperar:**  
- Matriz de correlação entre variáveis numéricas;  
- Heatmap do `seaborn` para identificar relações fortes.  

**Objetivo:**  
Descobrir relações que possam impactar a gestão de estoque (ex.: lead time vs stockout, vendas vs estoque).
</div>

---

## Etapa 6 – Análise de Stockouts e Criticidade
<div style="background:#F7F3FF; font-family: Poppins, Segoe UI; border-left:8px solid #FFA726; padding:18px; border-radius:10px; margin-top:12px; width:97%; color:#4B0055">

**O que esperar:**  
- Identificação de produtos com histórico de estoque baixo ou zerado;  
- Frequência de stockouts por SKU ou categoria;  
- Visualizações de produtos mais críticos.  

**Objetivo:**  
Destacar produtos com risco operacional e priorizar ações corretivas.
</div>

---

## Etapa 7 – Agrupamentos e Insights Operacionais
<div style="background:#F7F3FF; font-family: Poppins, Segoe UI; border-left:8px solid #FFA726; padding:18px; border-radius:10px; margin-top:12px; width:97%; color:#4B0055">

**O que esperar:**  
- Análise de estoque médio por armazém e categoria;  
- Ranking de produtos mais vendidos e menos disponíveis;  
- Identificação de excessos de estoque ou produtos parados.  

**Objetivo:**  
Gerar **insights operacionais** práticos que possam ser aplicados diretamente no **Fluxar**.
</div>

---

## Etapa 8 – Conclusões da EDA
<div style="background:#F7F3FF; font-family: Poppins, Segoe UI; border-left:8px solid #FFA726; padding:18px; border-radius:10px; margin-top:12px; width:97%; color:#4B0055">

**O que esperar:**  
- Resumo dos achados mais relevantes;  
- Identificação de padrões, tendências e problemas recorrentes;  
- Sugestões de possíveis automações ou alertas.  

**Objetivo:**  
Apresentar de forma clara e visual os resultados da EDA, preparando o terreno para análises preditivas futuras.
</div>

---

## Extras Opcionais
<div style="background:#F7F3FF; font-family: Poppins, Segoe UI; border-left:8px solid #FFA726; padding:18px; border-radius:10px; margin-top:12px; width:97%; color:#4B0055">

- Uso de `value_counts()` com gráficos estilizados;  
- Mini dashboards dentro do notebook com `seaborn` e `matplotlib`;  
- Tabelas estilizadas com rankings de vendas e stockouts;  
- Documentação em Markdown para cada bloco da análise.  
</div>
