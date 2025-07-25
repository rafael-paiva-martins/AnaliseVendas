# 📊 Análise Comercial de Vendas

Este repositório apresenta um conjunto de relatórios de Business Intelligence desenvolvidos com o Power BI, focados na análise comercial de vendas. O objetivo é transformar dados brutos em insights claros e acionáveis, promovendo a tomada de decisão estratégica.

---

## 📁 Estrutura dos Relatórios

A análise foi segmentada em **quatro relatórios distintos**, visando manter o foco da audiência e evitar sobrecarga visual. Cada relatório está estruturado de forma a destacar uma etapa específica da análise, favorecendo a navegação por meio de **botões de página** (navegação implementada via `Buttons > Page Navigator` no Power BI):

1. **Narrativa Inteligente** – Resumo automático e interpretativo dos dados.
2. **Principais Influenciadores de Vendas** – Fatores que impactam diretamente os resultados de vendas.
3. **Faixas de Vendas por Categoria e Ponto de Venda** – Distribuição de vendas por categoria em diferentes PDVs.
4. **Performance Regional de Vendedores** – Desempenho dos vendedores por localização geográfica.

---

## 🎯 Diretrizes de Visualização

Ao projetar dashboards eficazes, algumas práticas foram seguidas para garantir clareza e objetividade:

- **Um gráfico por página**: evita sobrecarga cognitiva e garante o foco da análise.
- **Uso criterioso de cores**: cores foram aplicadas com propósito informacional, não estético. Evitou-se o excesso de elementos visuais que comprometam a leitura.
- **Navegação estruturada**: os relatórios utilizam paginação interna para orientar o usuário entre as seções, promovendo uma melhor experiência de exploração dos dados.

---

## 🧠 Considerações Analíticas

### 🔍 Principais Influenciadores de Vendas
- Segmentação: Análise por **segmento** e **categoria**.
- Tipo de variável: **Contínua** (valor de venda).
- Observação: A ferramenta realiza automaticamente a identificação dos influenciadores mais relevantes, dispensando sumarização manual.

### 📈 Faixas de Vendas
- Objetivo: Monitorar a **variação de vendas por categoria** em um mesmo ponto de venda (PDV).
- Interpretação: Identifica tendências de crescimento ou queda em categorias específicas.

### 🗺️ Mapa de Performance Regional
- A geolocalização é extraída automaticamente a partir dos dados de **cidades** listadas na base (neste caso, no estado de São Paulo).
- Caso o endereço completo esteja disponível, recomenda-se incluir **coordenadas (latitude/longitude)** para maior precisão.
- O recurso de filtros (aba *Filters*) permite expandir a análise para diferentes regiões geográficas.

---

## 🧩 Boas Práticas

- O foco principal da análise não deve ser a criação indiscriminada de gráficos, mas sim a **resolução de problemas de negócio**.
- Ferramentas como Power BI e Tableau tornam a visualização acessível, mas exigem **bom senso** na organização e apresentação dos dados.
- A atenção da audiência deve ser cuidadosamente dirigida. Visualizações em excesso, ou sem propósito claro, tendem a gerar confusão.

---

## 🛠️ Ferramentas Utilizadas

- Power BI  
- Power Query  
- DAX  
- Git e GitHub  

---

## 📂 Estrutura do Projeto

```
📁 Projeto
 ┣ 📄 Projeto.pbix
 ┣ 📄 README.md
```

---

## 🚀 Como Visualizar

1. Baixe o arquivo `.pbix` deste repositório  
2. Abra-o no **Power BI Desktop**  
3. Navegue entre as páginas para visualizar os dashboards

---

## 🤝 Conecte-se

Conecte-se comigo no [LinkedIn](https://www.linkedin.com/in/rafael-paiva-martins/) para acompanhar mais projetos, trocar ideias ou colaborar em soluções de dados e inteligência de negócios.


# 📊 Sales Business Analysis

This repository presents a set of Business Intelligence reports developed using Power BI, focusing on commercial sales analysis. The goal is to transform raw data into clear, actionable insights that support strategic decision-making.

---

## 📁 Report Structure

The analysis is divided into **four distinct reports**, designed to maintain audience focus and avoid visual overload. Each report highlights a specific analysis step and includes internal page navigation via `Buttons > Page Navigator` in Power BI:

1. **Smart Narrative** – Automated interpretative data summary.
2. **Key Sales Influencers** – Factors directly impacting sales outcomes.
3. **Sales Ranges by Category and POS** – Sales distribution by category across different points of sale.
4. **Regional Sales Performance** – Sales performance by region and seller.

---

## 🎯 Visualization Guidelines

To ensure clear and objective dashboards, the following best practices were applied:

- **One chart per page**: Prevents cognitive overload and improves focus.
- **Purposeful use of color**: Colors highlight data differences, not for aesthetics.
- **Structured navigation**: Internal page links guide users smoothly through the reports.

---

## 🧠 Analytical Insights

### 🔍 Key Sales Influencers
- Segmentation: Analysis by **segment** and **category**.
- Variable type: **Continuous** (sales value).
- Note: Power BI automatically identifies and ranks the key influencers.

### 📈 Sales Ranges
- Purpose: Track **sales variation by category** at a single point of sale (POS).
- Interpretation: Highlights upward or downward sales trends.

### 🗺️ Regional Performance Map
- Geolocation is auto-detected from **city names** (São Paulo state in this dataset).
- For higher precision, include **latitude and longitude**.
- Filters (in the *Filters* pane) can expand the analysis to a broader geographic region.

---

## 🧩 Best Practices

- The goal of the analysis is to **solve business problems**, not to create endless charts.
- Power BI and Tableau simplify visualizations, but must be used with **intentional design**.
- Focus must be guided — excessive or unclear visuals can hinder insight.

---

## 🛠️ Tools Used

- Power BI  
- Power Query  
- DAX  
- Git & GitHub  

---

## 📂 Project Structure

```
📁 Project
 ┣ 📄 Projeto.pbix
 ┣ 📄 README.md
```

---

## 🚀 How to View

1. Download the `.pbix` file from this repository  
2. Open it in **Power BI Desktop**  
3. Navigate through the pages to explore the dashboards

---

## 🤝 Connect

Connect with me on [LinkedIn](https://www.linkedin.com/in/rafael-paiva-martins/) for more projects, ideas, or collaborations in data and business intelligence.
