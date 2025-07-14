# Analise e Modelagem de Vendas Automotivas

# Descrição do Projeto

Este projeto tem como objetivo principal a análise e modelagem de um dataset de vendas automotivas. O trabalho se divide em duas etapas principais:

- Regressão: Prever o valor das vendas ('SALES') com base em outras características numéricas do dataset.

- Classificação: Categorizar o tamanho do negócio ('DEALSIZE' - Small, Medium, Large) a partir de um conjunto de atributos  numéricos.

Para ambas as tarefas, foram explorados diversos algoritmos de Machine Learning, comparando seus desempenhos e interpretando os resultados obtidos.

# Instruções de execução

- Copie o link do repositório
- Abra a plataforma Google Colab
- Clique em File -> upload notebook -> GitHub -> cole o link e abra o arquivo
- Após o notebook ser carregado, você precisará fazer o upload do dataset. No painel lateral esquerdo, clique no ícone de pasta para abrir o navegador de arquivos. Em seguida, clique no ícone "Upload to session storage" (um ícone de pasta com uma seta para cima) e selecione o arquivo 08_vendas_automotivas.csv.
- Após, você pode executar as células individualmente ou todas clicando em Runtime -> run all
- Aguarde a execução de todas as células. Os resultados, gráficos e métricas serão exibidos diretamente no notebook.

# Conclusões Gerais

Com base em todos os resultados obtidos, a conclusão geral é que os modelos baseados em árvores (Random Forest e Árvore de Decisão) se destacam consistentemente como os mais eficazes para ambas as tarefas de previsão de vendas (regressão) e classificação do tamanho do negócio (DEALSIZE) neste conjunto de dados. Isso sugere fortemente que as relações subjacentes nos dados automotivas são complexas e não lineares, características que esses algoritmos conseguem modelar de forma superior em comparação com métodos mais tradicionais como Regressão Linear e SVR, ou até mesmo com os bons desempenhos da Regressão Logística e SVM para classificação.
  
