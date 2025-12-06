Relatório de Análise Financeira e Vendas (Sales Report)

Este projeto de Business Intelligence apresenta um Relatório de Vendas (Sales Report) desenvolvido no Microsoft Power BI. O objetivo principal deste painel é fornecer uma visão macroeconômica dos resultados financeiros da empresa, permitindo a análise de lucros, custos e desempenho por segmentos de mercado e geográficos.

O dashboard foi projetado para facilitar a tomada de decisão estratégica, oferecendo interatividade através de filtros temporais e botões de navegação entre visualizações.

📄 Visualização do Dashboard

Abaixo, a visão geral do painel construído, destacando os principais indicadores de desempenho (KPIs) e distribuições de vendas.

![Sales Report Dashboard](uploaded:desafio-Dio - Power BI.pdf)

Nota: A imagem acima representa a página principal do relatório, consolidando dados financeiros e operacionais.

🎯 Objetivos da Análise

Este relatório foi estruturado para responder às seguintes questões de negócio:

Saúde Financeira: Qual é o faturamento total e qual o impacto dos custos (COGS) e descontos na receita final?

Sazonalidade: Existem meses com picos de vendas que exigem maior atenção logística ou de estoque?

Desempenho por Produto e Segmento: Quais produtos são os "Carros-chefe" e qual segmento de cliente traz o maior retorno?

Presença Global: Como as vendas estão distribuídas entre os diferentes países de atuação?

📊 Detalhamento das Métricas e Visuais

1. KPIs (Indicadores Chave de Desempenho)

Os cartões no topo do dashboard foram escolhidos para fornecer uma leitura rápida da saúde do negócio:

Métrica

Valor

Propósito da Escolha

Total de Vendas

118,73 Mi

Indica a Receita Líquida. É a métrica principal para entender o fluxo de caixa real da empresa após as deduções.

Soma de Gross Sales

127,93 Mi

Representa a Venda Bruta. Comparar este valor com o "Total de Vendas" ajuda a entender o impacto das estratégias de precificação e descontos.

Total de Descontos

9,21 Mi

Monitorar este valor é crucial para garantir que as promoções não estejam corroendo excessivamente a margem de lucro.

Soma de COGS

101,83 Mi

Cost of Goods Sold (Custo das Mercadorias Vendidas). Essencial para calcular a margem bruta e a eficiência operacional.

Unidades Vendidas

1,13 Mi

Mede o volume físico de saída, importante para o planejamento de estoque e logística.

2. Análise dos Gráficos

Cada visualização foi selecionada para contar uma parte específica da história dos dados:

Soma das Vendas por Mês (Gráfico de Área):

Justificativa: O gráfico de área é excelente para mostrar tendências ao longo do tempo e o volume acumulado.

Insight: Observa-se uma tendência de crescimento significativa no segundo semestre, com um pico acentuado em Outubro (22 Mi), sugerindo uma forte sazonalidade que pode estar ligada a fechamentos de contratos governamentais ou demandas de fim de ano.

Soma por Segmento (Gráfico de Rosca):

Justificativa: Ideal para mostrar a composição de um todo.

Insight: O segmento Government (Governo) é predominante, representando a maior fatia do faturamento, seguido por Small Business. Isso indica uma dependência alta de contratos públicos.

Soma de Vendas por Produto (Gráfico de Barras):

Justificativa: Permite um ranking claro e comparação direta entre os itens.

Insight: O produto Paseo é o líder isolado de vendas (33 Mi), seguido pelo VTT. Produtos como Carretera têm desempenho inferior e podem necessitar de revisão estratégica.

Sales por Country (Treemap):

Justificativa: O Treemap foi escolhido para visualizar a hierarquia e proporção das vendas por país de forma compacta.

Insight: A distribuição é relativamente equilibrada entre os principais mercados (EUA, Canadá, França, Alemanha e México), todos girando em torno de 21 a 25 Milhões, indicando uma presença global bem consolidada sem dependência excessiva de um único território.

🛠️ Funcionalidades Técnicas

Botões de Alternância (Bookmarks): Foram implementados botões para permitir que o usuário alterne a visualização entre gráficos (Ex: Pie vs Bar e Treemap vs Map), economizando espaço na tela e oferecendo flexibilidade de análise.

Filtros de Data: Um slicer temporal permite restringir a análise a períodos específicos (01/09/2013 a 01/12/2014).

💡 Conclusão e Próximos Passos

A análise revela uma empresa com forte atuação no setor governamental e vendas consistentes internacionalmente. Para maximizar os resultados:

Investigar o motivo do pico de vendas em Outubro para replicar o sucesso nos outros meses.

Avaliar a margem de lucro do produto Paseo para garantir que o alto volume de vendas está se traduzindo em lucro real, dado o alto valor de COGS geral.

Desenvolver estratégias para aumentar a participação dos segmentos Midmarket e Channel Partners, diversificando a carteira de clientes.

👤 Autor

Projeto Desenvolvido por: Fábio R SOares

Conecte-se no LinkedIn: linkedin.com/in/fábio-soares-ti
