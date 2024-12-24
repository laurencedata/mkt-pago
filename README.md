# Análise de Correlação: MQLs, SQLs e Receita  

🔗 **Link**:  
Notebook: [Análise de Correlação de MQLs e Receita](https://github.com/laurencedata/mkt-pago/blob/main/mkt-pago.ipynb)  

📌 **Introdução**: 

Este projeto tem como objetivo explorar e identificar a existência de correlações entre três métricas importantes no contexto de mídia paga: MQLs (Marketing Qualified Leads), SQLs (Sales Qualified Leads) e Receita. O foco principal é fornecer insights baseados em dados para compreender a relação entre a geração de leads qualificados e os resultados financeiros da empresa. A análise abrange o 4º trimestre de 2024, com dados coletados no período de 01/10/2024 a 10/12/2024.


🎯 **Objetivos**:  

- Avaliar a força e a direção da correlação entre MQLs e SQLs.  
- Determinar como a quantidade de MQLs impacta diretamente a Receita gerada.  
- Automatizar o processo de análise utilizando Python.  

🌐 **Fontes de Dados**:  

Os dados utilizados neste projeto foram extraídos de sistemas internos de mídia paga e CRM – HubSpot. Todos os detalhes de coleta e tratamento podem ser encontrados no notebook principal.  

🔎 **Etapas da Análise**: 

1. **Extração dos Dados**: Os dados foram coletados diretamente de ferramentas de mídia paga e CRM, exportados no formato CSV.  
2. **Limpeza e Tratamento**: Tratamento de dados faltantes, remoção de duplicatas e ajustes de tipos de dados para assegurar a qualidade da análise.  
3. **Exploração e Visualização**: Análise exploratória para entender padrões nos dados.  
4. **Cálculo de Correlação**: Utilização de métricas estatísticas para calcular correlações (Pearson).  
5. **Resultados e Conclusões**: Interpretação dos valores obtidos para identificar a força e relevância das correlações.  

⚙️ **Ferramentas Utilizadas**:

- **Python**: Para o processamento e análise dos dados.  
  - **Bibliotecas**: Pandas, Matplotlib, Seaborn e SciPy.  

📊 **Visualizações**:  

- Gráficos de dispersão para MQLs vs. Receita e SQLs vs. Receita.  
- Histogramas e boxplots para análise de distribuição dos dados.  

💡 **Insights**:  

1. Existe uma forte correlação positiva entre MQLs e SQLs, sugerindo que uma maior qualificação inicial impacta diretamente o pipeline de vendas.  
2. A relação entre MQLs e Receita é moderada, indicando que outros fatores também influenciam a conversão em receita.  
3. Identificou-se que picos de MQLs nem sempre resultam em um aumento proporcional de Receita, destacando a importância da qualidade dos leads gerados.  

📝 **Storytelling**:  

A análise revelou a importância de otimizar a geração de MQLs para maximizar a conversão em SQLs e, consequentemente, impulsionar a Receita. 
