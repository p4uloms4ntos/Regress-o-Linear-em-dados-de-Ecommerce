# Objetivo
O objetivo deste projeto foi desenvolver um modelo de regressão linear para analisar e quantificar o impacto das principais variáveis sobre o comportamento de compra dos clientes de uma empresa de comércio eletrônico. A empresa buscava identificar qual plataforma — aplicativo ou site — exerce maior influência sobre as vendas anuais e utilizar essas informações para direcionar estratégias de alocação de recursos e otimização de investimentos.

Os dados utilizados foram extraídos do conjunto "ecommerce-customers.csv", disponível no Kaggle, e incluíam medições relacionadas ao comportamento dos clientes em ambas as plataformas.
<br>
<br>

# Técnicas Aplicadas
* Análise Exploratória de Dados (EDA): 
  * Identificação de padrões e correlações iniciais.
* Regressão Linear: 
  * Criação de um modelo preditivo para estimar o valor anual gasto pelos clientes.
* Testes Estatísticos: 
  * Validação das premissas do modelo:
    * Normalidade dos resíduos
    * Homocedasticidade
* Exclusão de variáveis irrelevantes com base em p-valores
* Interpretação do Modelo: 
  * Análise dos coeficientes e sua relação com as variáveis dependentes.

# Introdução
Este projeto foi concebido para atender à necessidade estratégica de uma empresa de comércio eletrônico sediada em Nova York, que opera tanto via aplicativo quanto website. Por meio de análises baseadas em dados, o objetivo era entender como essas plataformas contribuem para o comportamento de compra dos clientes e, assim, orientar decisões empresariais de maneira fundamentada.

###  Com um modelo de regressão linear ajustado, conseguimos identificar que:

O tempo de associação ao programa de membros é o fator de maior impacto no valor anual gasto pelos clientes.
O tempo gasto no aplicativo móvel é a segunda variável mais influente, destacando a importância dessa plataforma.
O tempo gasto no website mostrou correlação mínima com os gastos anuais, indicando menor relevância estratégica.
O modelo apresentou um R² de 98,4%, indicando que a variabilidade do gasto anual dos clientes foi explicada de forma robusta pelas variáveis analisadas.

# Conclusão
O modelo revelou informações relevantes para a tomada de decisão estratégica da empresa:

* Tempo de Associação (Length of Membership): Cada mês adicional de associação contribui com um aumento médio de $61,27 no gasto anual por cliente.
* Tempo no Aplicativo (Time on App): Cada minuto adicional gasto no app está associado a um incremento médio de $38,59.
* Tempo Médio de Sessões na Loja (Avg. Session Length): Apesar de menor impacto, também contribui para os gastos em $25,98 para cada minuto adicional.
* Por outro lado, o tempo gasto no website foi excluído do modelo devido à sua baixa relevância estatística e ausência de correlação com os gastos, indicando uma necessidade de melhora na experiÊncia do cliente via plataforma web site.

###  Recomendações Estratégicas

1. #### Fortalecimento do Programa de Associação
* Benefícios adicionais para membros antigos: introduzir benefícios exclusivos, como descontos progressivos com o tempo de associação.<br>
* Engajamento contínuo: promover interações frequentes, como newsletters personalizadas e convites para eventos exclusivos.<br>
* Fidelização e recompensas: implementar um programa de pontos que incentive compras recorrentes e longas associações.

2. #### Foco no Aplicativo Móvel:

* Investir em melhorias de interface e funcionalidades.
Oferecer promoções e descontos exclusivos para usuários do app.
Criar ferramentas de recomendação personalizadas com base no comportamento do usuário.
Fortalecimento do Programa de Associação:

* Recompensar clientes fiéis com benefícios progressivos, como descontos e acesso prioritário a novos produtos.
Ampliar as iniciativas de engajamento, como eventos e comunicações personalizadas.
Repensar a Experiência do Website:

* Simplificar o fluxo de compra para conversões mais rápidas.
Focar em integração com o aplicativo para uma experiência omnichannel.

#

Para entender como essas conclusões foram alcançadas, acompanhe o desenvolvimento do problema de negócio proposto, algoritmo criados e técnicas utilizadas clicando [aqui](https://github.com/p4uloms4ntos/Regress-o-Linear-em-dados-de-Ecommerce/blob/main/regressao-linear-projeto.ipynb). 
