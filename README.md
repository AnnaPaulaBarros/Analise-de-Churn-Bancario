<p> O presente projeto consiste no desenvolvimento de um dashboard no Power BI para analisar a taxa de rotatividade (Churn) de uma instituição bancária na Europa (França, Alemanha e Espanha). O objetivo principal é identificar padrões comportamentais, geográficos e demográficos que influenciam a saída de clientes, permitindo a criação de estratégias de retenção mais eficazes.

- Tecnologias: 
Power BI: Construção de visuais e dashboards;
Power Query: Limpeza e tratamento de dados (ETL);
DAX (Data Analysis Expressions): Criação de medidas personalizadas como Taxa de Churn, Saldo Médio e Quantidade de Churn;
Modelagem de Dados: Relacionamentos entre tabelas para filtros dinâmicos.

- Análises e Insights Extraídos
1. Perfil Demográfico de Risco
Através do gráfico de Taxa de Churn por idade e género, identifiquei um padrão crítico:
Pico de Evasão: Há uma subida acentuada no churn entre os 45 e 55 anos.
Género: Clientes do género Feminino apresentam uma taxa de saída consistentemente superior à do género masculino nesta faixa etária.
Ação sugerida: desenvolver produtos financeiros ou campanhas de fidelização específicas para mulheres.
2. Visão Geográfica e Capital
Utilizando o Treemap e o mapa Coroplético:
Concentração: França e Alemanha detêm a maior parte do saldo total do banco.
Embora a Alemanha possua um saldo elevado, ela apresenta indicadores de perda de clientes que exigem uma investigação sobre a concorrência local ou taxas bancárias no país.
3. Crédito e saúde financeira
Ao analisar a Média de Pontuação de Crédito por País:
Observei que a pontuação de crédito é equilibrada entre os três países (média acima de 600 pontos).
Isso indica que o churn não está necessariamente ligado a clientes com "crédito ruim", mas sim a clientes com boa saúde financeira que estão a escolher a concorrência.
4. Impacto no Faturamento
O gráfico de rosca mostra que clientes que saíram do banco representam 8,22% da soma de salários estimados, o que significa uma perda significativa de receita potencial e poder de consumo dentro da carteira do banco.

- Como Visualizar me dashboard: Faça o download do arquivo .pbix presente neste repositório e utilize os filtros laterais para navegar entre os países e observar como os dados se comportam dinamicamente. </p>
