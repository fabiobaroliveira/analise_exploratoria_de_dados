# Análise de Dados de Crédito: Estratégias para Impulsionar a Receita de Cartões

Recentemente, mergulhei em uma análise aprofundada dos dados de clientes de cartão de crédito de um banco, com o objetivo de entender a queda de 23% na receita YoY do produto. O dataset utilizado é uma amostra do arquivo original "credito.csv" (https://github.com/andre-marcos-perez/ebac-course-utils/tree/main/dataset) e foi criada uma tabela no AWS Athena, utilizando o S3 Bucket. Utilizando SQL para exploração e análise, pude desvendar insights sobre o comportamento dos clientes e identificar oportunidades estratégicas.

## Principais Descobertas:


- Perfil Dominante: A maior parte da nossa base de clientes (27,3%) e do volume de transações (aproximadamente 38%) concentra-se na faixa salarial de "menos que $40K".


- Disparidade de Cartões: Clientes com cartão Blue representam 86,9% da base, enquanto cartões Silver, apesar de terem um limite de crédito 3x maior, apresentam uma média de valor de transações surpreendentemente próxima à dos cartões Blue.


- Potencial Oculto: Mesmo com limites menores, clientes da faixa "menos que $40K" com cartão Blue demonstram um valor médio de gastos significativo, muitas vezes superando outras faixas salariais.

## Solução Proposta:

Identificamos uma oportunidade clara para reverter a queda de receita: promover um upgrade de cartão para clientes Blue qualificados para o cartão Silver. Esta estratégia visa capitalizar o potencial de clientes que já demonstram alto engajamento e valor de transações, mesmo com limites mais baixos. Encontramos 380 clientes com cartão Blue que já possuem limite de crédito e número de transações acima da média, tornando-os ideais para essa iniciativa.

Essa abordagem direcionada pode não apenas aumentar o valor médio das transações por cliente, mas também fortalecer o relacionamento e a lealdade com a base de clientes existente.

