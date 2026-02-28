Uma hamburgueria localizada em Belo Horizonte solicitou um estudo para investigar a queda na conversão de pedidos dentro do iFood.Apesar do volume de acessos continuar alto, o faturamento não acompanhava esse movimento.
O objetivo da análise foi identificar em qual etapa do funil os clientes estavam desistindo.
Observei o caminho que o cliente faz dentro do app:

Entra na loja (visita)

Olha o cardápio
Adiciona itens à sacola

Revisa o pedido

Finaliza a compra

A ideia foi medir quantas pessoas avançam em cada etapa.


A análise foi feita com:

Python

Pandas

Google Colab

Calculei as taxas de conversão entre cada etapa do funil.
![Funil de Conversão](grafico_conversao_2.png)
O Que os Dados Mostraram

Etapa

Conversão

Visita → Visualização

35,9%

Visualização → Sacola

51,6%

Sacola → Revisão

95,8%

Revisão → Compra

28,2%

Ao analisar os dados, apareceu algo bem claro:
o produto mais vendido é justamente o único que tem foto no aplicativo do cliente.

Isso indica que a imagem faz muita diferença na escolha.
## 📊 Análise dos Produtos

![Análise de Produtos](grafico_produtos_ifood.png)
