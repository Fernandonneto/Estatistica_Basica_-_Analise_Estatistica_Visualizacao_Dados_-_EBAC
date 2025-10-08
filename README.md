## Análise Estatística e Visualização de Dados 
#### Análise de Produtos de um Supermercado no Chile

Este projeto faz parte do Módulo de Estatística Básica da EBAC e tem como objetivo aplicar conceitos estatísticos e de visualização de dados sobre uma base real de produtos de um supermercado chileno.

A proposta foi analisar variáveis como preço normal, preço com desconto, marca e categoria, a fim de identificar padrões de comportamento e fatores que impactam o valor e o desconto dos produtos.

A análise foi desenvolvida em Python, utilizando o Google Colab para exercitar o uso de diferentes ferramentas e consolidar as habilidades de exploração e visualização de dados.

### 🧰 Ferramentas e Bibliotecas Utilizadas

- **Python**
- **Google Colab** — ambiente de desenvolvimento e execução do projeto
- **Pandas** — para manipulação e agregação de dados
- **Matplotlib** — para gráficos estáticos
- **Plotly Express** — para visualizações interativas (Treemap)

### 📊 Etapas e Análises Realizadas
#### 1️⃣ Média e Mediana por Categoria
Foi calculada a média e a mediana da coluna `Preco_Normal` agrupadas por categoria.
#### Resultado:
- Categorias com **média acima da mediana**:
`belleza-y-cuidado-personal`, `congelados`, `frutas`, `instantaneos-y-sopas`, `lacteos` e `verduras`.
- Categoria com **média abaixo da mediana**:
`comidas-preparadas`.

➡️ **Interpretação**: valores de média acima da mediana indicam presença de outliers (produtos premium ou preços extremos).

#### 2️⃣ Desvio Padrão por Categoria
O desvio padrão foi calculado para identificar a dispersão dos preços.
**Categorias com maior desvio:**
- `lacteos`, `belleza-y-cuidado-personal` e `congelados`.

➡️ **Interpretação**: Essas categorias apresentam alta variação de preços, o que indica uma ampla variedade de produtos (ex.: desde itens básicos até versões premium).

#### 3️⃣ Boxplot — Categoria de Lácteos
O boxplot mostrou a distribuição dos preços da categoria de lácteos.

➡️ **Interpretação**:
A presença de outliers reforça que há produtos com valores muito superiores à média, o que eleva o desvio padrão da categoria.

#### 4️⃣ Gráfico de Barras — Média de Desconto por Categoria
Foi criado um gráfico de barras mostrando os valores de desconto médio por categoria.

➡️ **Interpretação**:
Categorias com maiores descontos médios tendem a ter estratégias promocionais mais agressivas, possivelmente para estimular vendas de produtos de maior preço.

#### 5️⃣ Gráfico de Treemap — Desconto por Categoria e Marca
Um gráfico de mapa interativo (Treemap) foi desenvolvido para visualizar as médias de desconto agrupadas por categoria e marca, utilizando uma escala de cores (Viridis).

➡️ **Interpretação**:
Permite identificar quais marcas dentro de cada categoria oferecem maiores descontos, auxiliando na análise de estratégias de marketing e precificação.

### 💡 Principais Insights
- Categorias como lácteos e cosméticos apresentam grande dispersão de preços, com produtos premium influenciando fortemente a média.
- A média acima da mediana reforça a presença de outliers em várias categorias.
- O Treemap destacou marcas específicas com maiores descontos, evidenciando diferentes políticas promocionais por categoria.

### 💻 Desenvolvimento
O projeto foi desenvolvido inteiramente no Google Colab, permitindo:
- Upload direto do arquivo CSV via interface;
- Execução interativa de células de código;
- Criação e exibição de gráficos dinâmicos e estáticos;
- Melhoria nas habilidades com ferramentas de análise e visualização de dados.

### 🚀 Conclusão
Este projeto consolidou o uso prático de estatística descritiva e visualização de dados em Python, fornecendo uma visão clara sobre o comportamento de preços, descontos e variações entre categorias de produtos em um contexto real de varejo.
