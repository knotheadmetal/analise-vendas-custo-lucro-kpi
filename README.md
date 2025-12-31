# Dashboard de Vendas, Custo, Margem de Lucro e KPI - Power BI 

Este repositório contém um dashboard interativo desenvolvido no Power BI, focado na análise de métricas de vendas globais, custos de envio, margens de lucro e indicadores-chave de desempenho (KPIs). O objetivo é fornecer insights estratégicos para otimizar recursos, melhorar a lucratividade e monitorar o desempenho das vendas.

- **Visualização Interativa do Dashboard:** [Clique aqui para acessar](https://app.powerbi.com/view?r=eyJrIjoiMDNkNGI3MjEtNGJhZi00YjI5LTgwYTYtZWQxNGRjMGJmNjY2IiwidCI6ImYxNDZiYjhhLTBiOTQtNGY1MC1hZmExLTNmYzc4Mjk0MjE1NSJ9)

---

## Objetivo do Projeto

O dashboard foi desenvolvido para responder às seguintes perguntas de negócio:

1. Qual foi o total de valor de venda considerando cada modo de envio dos pedidos?
2. Quais mercados tiveram o maior custo médio de envio dos produtos vendidos?
3. A empresa ficou abaixo ou acima da meta no mês de Abril/2014, considerando uma média de 350 para o valor de venda?
4. Qual categoria de produto apresentou o maior lucro médio?
5. Qual foi o comportamento da margem de lucro ao longo do tempo?

As análises fornecem insights estratégicos para otimizar custos, melhorar a lucratividade e monitorar o desempenho das vendas.

---

## Estrutura do Projeto

Os seguintes arquivos foram utilizados para criar o relatório:

- **clientes.csv:** Contém informações sobre os clientes, como ID, segmento e região.
- **pedidos.csv:** Inclui detalhes sobre os pedidos, como ID do pedido, data e prioridade.
- **produtos.csv:** Detalha as categorias e subcategorias dos produtos.
- **vendas.csv:** Fornece dados sobre as vendas, incluindo quantidade, desconto, lucro e custo de envio.
- **vendas-custo-lucro-kpi.pbix:** Arquivo principal do Power BI com as visualizações e análises.

---

## Como Utilizar

1. **Clone este repositório:**
   ```bash
   git clone https://github.com/seu-usuario/dashboard-vendas-custos
   ```

2. **Pré-requisitos:**
   - Instale o [Power BI Desktop](https://powerbi.microsoft.com/).
   - Certifique-se de ter acesso aos arquivos CSV (`clientes.csv`, `pedidos.csv`, `produtos.csv`, `vendas.csv`).

3. **Abrindo o Arquivo:**
   - Baixe o arquivo **vendas-custo-lucro-kpi.pbix** e abra-o no Power BI Desktop.
   - Conecte os arquivos CSV ao Power BI caso necessário.

4. **Exploração do Dashboard:**
   - Utilize os filtros e segmentadores para personalizar as análises.
   - Explore as visualizações para obter insights sobre vendas, custos, margens de lucro e KPIs.

---

## Visões do Dashboard

### 1. Valor Total de Venda por Modo de Envio
**Objetivo:** Mostrar o total de valor de venda considerando cada modo de envio dos pedidos.  
**Gráfico Utilizado:** Gráfico de Cascata.  
**Métricas Principais:**  
- Valor Total Vendido por Modo de Envio.  
- Contribuição de cada modo de envio no total de vendas.  

---

### 2. Custo Médio de Envio por Mercado
**Objetivo:** Identificar os mercados com maior custo médio de envio dos produtos vendidos.  
**Gráfico Utilizado:** Treemap.  
**Métricas Principais:**  
- Custo Médio de Envio por Mercado.  
- Distribuição dos custos entre diferentes mercados.  

---

### 3. Indicador de Desempenho (KPI) - Valor Médio de Venda
**Objetivo:** Verificar se a empresa atingiu a meta de manter uma média de 350 para o valor de venda no mês de Abril/2014.  
**Gráfico Utilizado:** Indicador (KPI).  
**Métricas Principais:**  
- Valor Médio de Venda no mês de Abril/2014.  
- Comparação com a meta estabelecida (350).  

---

### 4. Lucro Médio por Categoria de Produto
**Objetivo:** Determinar qual categoria de produto apresentou o maior lucro médio.  
**Gráfico Utilizado:** Gráfico de Barras.  
**Métricas Principais:**  
- Lucro Médio por Categoria de Produto.  
- Comparação entre categorias para identificar líderes em lucratividade.  

---

### 5. Comportamento da Margem de Lucro ao Longo do Tempo
**Objetivo:** Analisar a evolução da margem de lucro ao longo do tempo.  
**Gráfico Utilizado:** Gráfico de Linhas.  
**Métricas Principais:**  
- Margem de Lucro Mensal (Lucro / Valor de Venda).  
- Tendências temporais na margem de lucro.  

---

## Contribuição

Contribuições são bem-vindas! Siga os passos abaixo:

1. Faça um fork deste repositório.  
2. Crie uma branch com suas alterações:
   ```bash
   git checkout -b feature/nova-funcionalidade
   ```
3. Envie suas alterações:
   ```bash
   git push origin feature/nova-funcionalidade
   ```
4. Abra um pull request explicando suas modificações.

---

## Contato

- **LinkedIn:** [Rafael Santos](https://www.linkedin.com/in/rafaelsantosti/)  
- **Portfólio:** [GitHub](https://github.com/knotheadmetal)  
- **E-mail:** [rafaelsantosti@outlook.com](mailto:rafaelsantosti@outlook.com)  
