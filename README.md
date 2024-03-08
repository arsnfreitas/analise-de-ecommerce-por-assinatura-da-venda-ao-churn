

#### **Projeto de Data Science**
*by [Artur Freitas](https://www.linkedin.com/in/artur-sn-freitas/)*

---

# Análise dos dados de um ecommerce do tipo clube de assinatura

Analisaremos os dados de um ecommerce do tipo assinatura com o objetivo de entender o comportamento dos usuários afim de predizer vendas e cancelamentos. Temos as bases disponíveis do próprio ecommerce e do google analytics.

Um clube de assinatura é uma empresa que entrega produtos periodicamente (ou quinzena, mensal, etc.) para seus associados mediante um pagamento recorrente.

Esse tipo de negócio está em alta na economia da recorrência graças à comodidade e experiência de compra diferenciada. O modelo comercial mais comum é o envio de kits e boxes de produtos selecionados para a casa dos clientes, conforme o plano assinado.

É importante fazermos algumas nomenclaturas clássicas para as áreas de marketing e vendas:

- Um lead é um usuário que tem algum tipo de interesse nos serviços ou produtos de um negócio. Ou seja, nada mais é do que um consumidor em potencial que é identificado por uma empresa e precisa finalizar a jornada de compra até que a conversão aconteça. 
- Um assinante é um lead que realizou a compra da sua assinatura.

- LTV: liftime value, é quanto o assinante gasta durante seu período de assinatura.

- Churn: cancelamento da assinatura ou taxa de cancelamento.

De posse dos dados de navegação e vendas, faremos: 

> Etapa 1: Importar, tratar e analisar os dados (EDA).

> Etapa 2: Faremos uma classificação dos usuários referente a disposição para realizar a de compra utilizando da segmentação Kmeans

> Etapa 3: Vendas cruzadas para quem comprou: ao analisar as compras conjuntas anteriores, podemos identificar quais produtos podem ser oferecidos para determinadas compras.

> Etapa 4: Previsão do LTV e retenção: faremos uma segmenteção Kmeans, utilizando a técnica RFV adapatada para o modelo de assinatura e então faremos um modelo para a previsão da do valor da vida útil (LTV) e a quantidade de meses como assinante dos usuários.

> Etapa 5: Previsão de churn: desenvolveremos um modelo para prever a propensão ao cancelamento dos assinantes.

Dessa maneira, teremos um algoritmo que pode ser aplicado para novos leads e novos assinantes mensalmente a fim de buscar um aumento de vendas, de LTV e diminuição de churn.
