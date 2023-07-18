# Desafio

Você foi alocado(a) em um time da Indicium que está trabalhando atualmente junto a um cliente que o core business é compra e venda de veículos usados. Essa empresa está com dificuldades na área de revenda dos automóveis usados em seu catálogo.

Para resolver esse problema, a empresa comprou uma base de dados de um marketplace de compra e venda para entender melhor o mercado nacional, de forma a conseguir precificar o seu catálogo de forma mais competitiva e assim recuperar o mau desempenho neste setor.

Seu objetivo é analisar os dados para responder às perguntas de negócios feitas pelo cliente e criar um modelo preditivo que precifique os carros do cliente de forma que eles fiquem o mais próximos dos valores de mercado. 

Para isso são fornecidos dois datasets: 

1. Um dataset para treinamento chamado cars_training composto por 29584 linhas, 28 colunas de informação (features) e a variável a ser prevista (“preco”). 
2. Um segundo dataset para teste chamado de cars_test composto por  9862 linhas e 28 colunas, sendo que este dataset não possui a coluna “preco”. 

**Seu objetivo é prever a coluna "preco" coluna a partir dos dados enviados e nos enviar para avaliação dos resultados.**

Você poderá encontrar em anexo um dicionário dos dados.

## Entregas

1. Utilizando as variáveis (features), faça um relatório com uma análise das principais estatísticas da base de dados. Descreva graficamente essas variáveis (features), apresentando as suas principais estatísticas descritivas. Comente o porquê da escolha destas estatísticas e o que elas nos informam..
2. Faça uma EDA. Nesta EDA, crie e responda 3 hipóteses de negócio. Além disso,  responda também às seguintes perguntas de negócio:
   1. Qual o melhor estado cadastrado na base de dados para se vender um carro de marca popular e por quê?
   2. Qual o melhor estado para se comprar uma picape com transmissão automática e por quê?
   3. Qual o melhor estado para se comprar carros que ainda estejam dentro da garantia de fábrica e por quê?
3. Explique como você faria a previsão do preço a partir dos dados. Quais variáveis e/ou suas transformações você utilizou e por quê? Qual tipo de problema estamos resolvendo (regressão, classificação)? Qual modelo melhor se aproxima dos dados e quais seus prós e contras? Qual medida de performance do modelo foi escolhida e por quê?
4. Envie o resultado final do modelo em uma planilha com apenas duas colunas (id, preco). 
5. A entrega deve ser feita através de um repositório de código público que contenha:
   1. README explicando como instalar e executar o projeto
   2. Arquivo de requisitos com todos os pacotes utilizados e suas versões
   3. Relatórios das análises estatísticas e EDA em PDF, Jupyter Notebook ou semelhante conforme passo 1 e 2.
   4. Códigos de modelagem utilizados no passo 3.
   5. Arquivo final com o nome predicted.csv conforme passo 4 acima.

Todos os códigos produzidos devem seguir as boas práticas de codificação.

