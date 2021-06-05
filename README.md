<h1 align="center"> Empresa Insurance All </h1> 

## 1.0 - Sobre a Empresa

A Insurance All é uma empresa que fornece seguro de saúde para seus clientes, que tem o modelo de negócio do tipo serviço. Tendo como seu principal produto Seguro Saúde. 

A apólice de seguro é um acordo pelo qual uma empresa se compromete a fornecer uma garantia de compensação por perdas, danos, doenças ou morte especificados em troca do pagamento de um prêmio especificado.


## 2.0 - Desafio de Negócio

O time de produtos da Insurance All está analisando a possibilidade de oferecer aos assegurados, um novo produto: Um seguro de automóveis.


Como resultado da sua consultoria, você precisará entregar um relatório contendo algumas análises e respostas às seguintes perguntas:

- Principais Insights sobre os atributos mais relevantes de clientes interessados em adquirir um seguro de automóvel.
- Qual a porcentagem de clientes interessados em adquirir um seguro de automóvel, o time de vendas conseguirá contatar fazendo 20.000 ligações?
- E se a capacidade do time de vendas aumentar para 40.000 ligações, qual a porcentagem de clientes interessados em adquirir um seguro de automóvel o time de vendas conseguirá contatar?
- Quantas ligações o time de vendas precisa fazer para contatar 80% dos clientes interessados em adquirir um seguro de automóvel?


## 3.0 Como Funciona o Seguro Saúde?

O seguro saúde  diferente do plano de saúde ele não te "prende" a médicos, hospitais, laboratórios pré definidos. Dando uma melhor liberdade para o segurado na escolha.
Há também um pagamento mensal do seguro saúde que é chamado de “prêmio”. Assim como em outras modalidades de seguro, o valor do prêmio pode variar de acordo com o risco de futuros custos com tratamentos.

## 4.0 Estratégia de Solução
Minha estratégia para resolver esse desafio foi:

- **Etapa 01.** Conexão com o banco de dados: Nesta etapa vai ser realizado a conexão com o banco de dados Postgresql.
- **Etapa 02.** Coleta dos dados: Nesta etapa o objetivo era coletar os dados em um banco de dados  Postgresql.
- **Etapa 03.** Descrição dos dados: Nesta estapa o objetivo é usar métricas estatísticas para identificar dados fora do escopo do negócio
- **Etapa 04.** Feature Engineering: Derivar novos atributos com base nas variáveis originais para descrever melhor o fenômeno que será modelado
- **Etapa 05.** Filtragem de Dados: Filtrar as linhas e selecione as colunas que não contenham informações para modelagem que não correspondam ao escopo
- **Etapa 06.** Análise Exploratória de Dados: Para esta etapa o objetivo é explorar os dados para entender melhor o impacto das variáveis no aprendizado do modelo e encontrar insights.
- **Etapa 07.** Preparação dos Dados: Prepare os dados para que os modelos de aprendizado de máquina possam aprender o comportamento específico.
- **Etapa 08.** Seleção de Recursos: Seleção dos atributos mais significativos para treinar o modelo.
- **Etapa 09.** Machine Learning: Treinamento de Machine Learning.
- **Etapa 10.** Hyperparamenter Fine Tunning: Escolha os melhores valores para cada um dos parâmetros do modelo selecionado na etapa anterior.
- **Etapa 11.** Interpretação do desempenho do modelo em valores de negócios: converta o desempenho do modelo de aprendizado de máquina em um resultado de negócios.
- **Etapa 10.** Deploy do modelo: Publicar o modelo em um ambiente de nuvem para que outras pessoas ou serviços possam usar os resultados para melhorar a decisão de negócios.

## 5.0 - O conjunto de dados 

- <b>Id:</b> identificador único do cliente.
- <b>Gender:</b> gênero do cliente.
- <b>Age:</b> idade do cliente.
- <b>Driving License:</b> 0, o cliente não tem permissão para dirigir e 1, o cliente tem para dirigir ( CNH – Carteira Nacional de Habilitação )
- <b>Region Code:</b> código da região do cliente.
- <b>Previously Insured:</b> 0, o cliente não tem seguro de automóvel e 1, o cliente já tem seguro de automóvel.
- <b>Vehicle Age:</b> idade do veículo.
- <b>Vehicle Damage:</b> 0, cliente nunca teve seu veículo danificado no passado e 1, cliente já teve seu veículo danificado no passado.
- <b>Anual Premium:</b> quantidade que o cliente pagou à empresa pelo seguro de saúde anual.
- <b>Policy sales channel:</b> código anônimo para o canal de contato com o cliente.
- <b>Vintage:</b> número de dias que o cliente se associou à empresa através da compra do seguro de saúde.
- <b>Response:</b> 0, o cliente não tem interesse e 1, o cliente tem interesse.

## 5.0 Top 3 Insights

## 6.0 Modelo de Machine Learning Aplicado

## 7.0 Resultado de Negócio

## 8.0 Conclusão 

## 9.0 Aprendizados

## 10.0 - Próximos Passos do Projeto 

- [ ] Atualizar o README.md
- [ ] EDA
- [ ] Relatório de Insights

## 11.0 Referências

[Link para acessar o desafio](https://sejaumdatascientist.com/como-usar-data-science-para-fazer-a-empresa-vender-mais/)
[Sobre Seguro de carro](https://www.minutoseguros.com.br/blog/como-funciona-seguro-de-carro/)
[Sobre Seguro saúde](https://www.minutoseguros.com.br/blog/seguro-saude-plano-saude-diferencas/)
[GridSearch e KNeighbors Classifier](https://medium.com/@erikgreenj/k-neighbors-classifier-with-gridsearchcv-basics-3c445ddeb657)


