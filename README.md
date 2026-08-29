# Análise da Performance de Campanhas
## Problema de negócio:
Este estudo busca responder qual das duas campanhas foi mais dominante em determinados KPI's, desse modo a análise perpassa por duas principais fases
  1. Análise exploratória e descritiva
  2. Análise de significância estatística por meio de testes de hipóteses
## Bibliotecas utilizadas:
Pandas, Numpy, Ploty, statsmodels e Scipy.
## Conclusões e Recomendações
Com base nos resultados das seções 2, 3 e 4. Vemos que com base nas análises exploratórias cada campanha performou de forma diferente, **entretanto devido a presença de SRM a inferência causal sob a superioridade da campanha Controle ficam comprometidas**. Porém recomenda-se três frentes de ação:<br>
**Primeira Frente de Ação**: Utiliza-se as campanhas atuais dependendo do foco principal dos setores de vendas e marketing, respaldado pela análise exploratória e pelos testes de hipótese (sem confirmar causalidade), com isso utilizando cada uma das campanhas da seguinte maneira<br>

* **Controle**: Quando o foco dos setores for a Conversão<br>
    Isso se dá por tal campanha se mostrar mais efetiva para converter os anuncios em vendas, ela pode ser interessante quando queremos trazer o cliente para produtos de maior ticket médio, ou até mesmo quando queremos trazer um cliente antigo para comprar conosco. Isso poderia ser testado pela entrega de novos dados do setor de vendas e marketing a fim de aferir o valor dos itens comprados em cada campanha, caso ele se demonstre maior podemos suspeitar de tal característica.
    Contudo, ressalta-se que a presença do SRM evidencia que a plataforma de anúncio atribuiu tráfego adicional para a campanha em questão o que afeta a confiabilidade causal, para afirmar que a campanha Controle é superior em conversão devido a seu escopo criativo.

* **Teste**: Quando o foco dos setores for o Engajamento<br>
    Tal campanha foi mais efetiva para gerar engajamento, com a mesma apresentando melhores métricas relacionadas a isto, bem como destaca-se o CPC um pouco menor para a campanha o que exibe que ela teve um custo para clique menor. Recomenda-se a utilização dessa campanha quando a finalidade for atrair consumidores diferentes de uma base instalada, ou seja atrair potenciais consumidores que ainda não conhecem os nossos produtos.<br>
    Entretanto, mais uma vez, cabe ressaltar que a presença do SRM invalida a afirmação causal devido ao escopo criativo da campanha Teste.
    
**Segunda Frente de Ação**: Elaborar uma terceira campanha<br>
A elaboração de uma terceira campanha pode ser definida como uma nova possibilidade de corrigir os pontos fracos das campanhas controle e teste, uma vez que ambas não apresentaram um desempenho absoluto sobre a outra. Desse modo, recomenda-se avaliar os quesitos técnicos elaborados em ambas e fazer as alterações pelo departamento de marketing para a criação da campanha C. Após realizada e testada poderia-se averiguar o desempenho da campanha C frente as campanhas controle e teste (A e B).

**Terceira Frente de Ação**: Realizar uma nova amostragem para as campanhas A e B<br>
    Devido a presença do SRM a confiança causal entre as campanhas controle e teste ficaram com confiabilidade abalada. Com isso, recomenda-se para a equipe de marketing a criação de uma nova amostragem para as campanhas controle e teste com as opções de desabilitar a otimização automática, ou a utilização de ferramentas dedicadas a experimentação como o *Campaign Experiments do Google Ads*
