A análise feita a cima tem como principal objetivo identificar pontos que impactaram fortemente na perda de clientes da empresa Telecom, logo, seguem algumas análises feitas e tambem alguns pontos a serem observados e possíveis melhoras.

Extraimos os dados emitidos no github via .zip e criamos um diretorio local e um online onde fizemos as tratativas e subimos periodicamente conforme alterações. Realizamos a abertura de dados aninhados e separaos as tabelas para podermos entender os tipos de dados que tinhamos em mãos logo após, unificamos os mesmo e verificamos dados nulos ou duplicados e seguimos as análises. Consequentemente chegamos as seguintes conclusões:

- Por mais que esteja equilibrado, o maior número de "Churns" foram de pessoas do sexo feminino
- O contratos assinados por Mês tiveram o maior número de cancelamentos diferente dos contratos feitos por anos
- Algo que chamou a atenção foram a quantidade de cancelamentos com a forma de pagamento "Electronic Check" isso mostra uma dificuldade nesse meio de pagamento que tem influenciado fortemente na tomada de decisão do cliente em cancelar.
- Entretanto vale destacar que a maioria dos "Churns" foram de cliente que não aderiram a assinatura do serviço de Suporte Técnico com menos tempo de espera. É valido rever o processo de suporte técnico normal para tentar elevar o nível da qualidade de serviço, visto que tivemos um menor número de evasão com cliente que aderiram o serviço.
- Outra proposta interessante seria criar contratos semestrais, visto que temos uma taxa de evasão muito alta com clientes a baixo dos 6 meses.

Bibliotecas utilizadas:
Pandas
Matplotlib
Seaborn
Numpy
