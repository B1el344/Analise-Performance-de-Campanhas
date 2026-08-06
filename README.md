# Análise da Performance de Campanhas
## Problema de negócio:
Este estudo busca responder qual das duas campanhas foi mais dominante em determinados KPI's, desse modo a análise perpassa por duas principais fases
  1. Análise exploratória e descritiva
  2. Análise de significância estatística por meio de testes de hipóteses
## Bibliotecas utilizadas:
Pandas, Numpy, Ploty, statsmodels e Scipy.
## Conclusões e Recomendações
Com base nos resultados das análises. Recomenda-se duas frentes de ação:<br>
**Primeira Frente de Ação**: Utiliza-se as campanhas atuais dependendo do foco principal dos setores de vendas e marketing, com isso utilizando cada uma das campanhas da seguinte maneira<br>

* **Controle**: Quando o foco dos setores for a Conversão<br>
    Isso se dá por tal campanha se mostrar mais efetiva para converter os anuncios em vendas, ela pode ser interessante quando queremos trazer o cliente para produtos de maior ticket médio, ou até mesmo quando queremos trazer um cliente antigo para comprar conosco. Isso poderia ser testado pela entrega de novos dados do setor de vendas e marketing a fim de aferir o valor dos itens comprados em cada campanha, caso ele se demonstre maior podemos suspeitar de tal característica.
    Algo que reforça o poder superior também da campanha em relação a conversão, é que a propria plataforma de anúncios utilizada, sendo assim dando preferência a campanha controle por este motivo. Com isso, sendo aferido pela presença de SRM por meio do teste do Qui-Quadrado.
* **Teste**: Quando o foco dos setores for o Engajamento<br>
    Tal campanha foi mais efetiva para gerar engajamento, com a mesma apresentando melhores métricas relacionadas a isto, bem como destaca-se o CPC um pouco menor para a campanha o que exibe que ela teve um custo para clique menor. Recomenda-se a utilização dessa campanha quando a finalidade for atrair consumidores diferentes de uma base instalada, ou seja atrair potenciais consumidores que ainda não conhecem os nossos produtos.<br>
    
**Segunda Frente de Ação**: Elaborar uma terceira campanha<br>
A elaboração de uma terceira campanha pode ser definida como uma nova possibilidade de corrigir os pontos fracos das campanhas controle e teste, uma vez que ambas não apresentaram um desempenho absoluto sobre a outra. Desse modo, recomenda-se avaliar os quesitos técnicos elaborados em ambas e fazer as alterações pelo departamento de marketing para a criação da campanha C. Após realizada e testada poderia-se averiguar o desempenho da campanha C frente as campanhas controle e teste (A e B). 
