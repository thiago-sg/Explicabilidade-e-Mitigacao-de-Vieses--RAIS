# Explicabilidade-e-Mitigacao-de-Vieses--RAIS

Arquivos do trabalho de conclusão do Curso de Especialização em Ciência de Dados - PUCRS.

- Pré-processamento nos microdados da RAIS para obtenção de conjunto com profissionais de TI no RS, fixando a remuneração como rótulo. Tal rótulo foi binarizado a partir do valor médio encontrado para a remuneração, resultando em conjunto no qual cada instância é um profissional que percebe remuneração acima ou abaixo da média.

- Utilização da biblioteca de explicabilidade SHAP para compreensão de modelo XGBoost treinado neste conjunto.

- Avaliação de métricas de fairness antes e após a aplicação de três algoritmos de mitigação de vieses da biblioteca AIF360, considerando os atributos sexo e raça.
