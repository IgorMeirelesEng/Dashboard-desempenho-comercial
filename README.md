# Dashboard Desempenho comercial
Este projeto apresenta um dashboard de desempenho comercial desenvolvido no **Power BI**, utilizando quatro arquivos CSV: clientes, produtos, pedidos e vendas.

Durante a importação dos dados, não foram criadas relações automáticas no modelo devido à presença de duplicatas. Esse problema afetou a modelagem automática do Power BI, exigindo uma etapa manual de **limpeza e estruturação dos dados**. A remoção de duplicatas e a padronização de campos foram necessárias para garantir relacionamentos corretos entre as tabelas (1:N).

Além disso, foram aplicadas transformações no Power Query e criadas métricas com DAX para cálculo de KPIs como receita lucro médio e margem de lucro. O resultado é um dashboard interativo e dinâmico, que permite analisar o desempenho comercial por cliente, produto, região e período, fornecendo insights estratégicos para a tomada de decisão.
