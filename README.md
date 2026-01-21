📊 Análise de Teste A/B: Otimização de Loja Online
Este projeto consistiu na priorização de hipóteses e análise de um teste A/B para uma grande loja online, com o objetivo de impulsionar o faturamento através da melhoria nas taxas de conversão.

🚀 Principais Conclusões
Vencedor: Grupo B 🏆
Conversão: Obteve um aumento estatisticamente significativo de 19.8% em relação ao Grupo A.
Ticket Médio: Não apresentou alteração significativa, indicando que o ganho de receita veio do volume de novos compradores e não do aumento de gasto por pedido.

🛠️ Metodologia e Tecnologias
Linguagem: Python
Bibliotecas: Pandas (Manipulação), Matplotlib / Seaborn (Visualização), Scipy (Testes Estatísticos).
Processamento de Dados: Remoção de usuários duplicados em ambos os grupos e filtragem de 22 outliers que distorciam os resultados financeiros.

📈 Análise Visual
Para cada etapa, foram gerados gráficos acumulados para garantir a estabilidade dos dados antes da tomada de decisão:
Receita Acumulada: O Grupo B assumiu a liderança definitiva após o dia 13 de agosto.
Tamanho Médio do Pedido: Identificamos um salto anômalo no dia 19/08 no Grupo B, estabilizando-se em queda logo após.
Taxa de Conversão: O Grupo B estabilizou-se consistentemente acima do Grupo A desde a primeira semana de teste.

⚖️ Decisão Estatística (Teste Mann-Whitney)
A decisão final foi baseada em critérios estatísticos rigorosos:
Taxa de Conversão: O p-valor foi inferior a 0,05, permitindo-nos rejeitar a hipótese nula. Há uma diferença real e positiva no Grupo B.
Valor Médio do Pedido: O p-valor foi superior a 0,05. Não rejeitamos a hipótese nula, concluindo que a diferença vista nos gráficos foi causada por pedidos atípicos e não por uma mudança de comportamento.
Veredito: O teste deve ser interrompido. O Grupo B é o vencedor, pois garante um aumento real na receita total através do aumento do volume de conversões.
Como rodar este projeto
Clone o repositório.
Certifique-se de ter as bibliotecas instaladas: pip install pandas matplotlib scipy.
Abra o arquivo analise_ab.ipynb no Jupyter Notebook ou VS Code.

