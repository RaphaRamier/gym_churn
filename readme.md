# Rotatividade de Clientes de uma rede de Academias 

---

# Introdução

O presente projeto visa auxiliar com sua análise uma rede de academias que está desenvolvendo uma estratégia de interação com o cliente baseados em dados analíticos.

Um dos problemas mais comuns que academias e outros serviços enfrentam é a rotatividade de clientes. Como você sabe se um cliente não está mais com você? Você pode calcular a rotatividade baseado nas pessoas que se livram das suas contas ou não renovam seus contratos. No entanto, às vezes não é óbvio que um cliente saiu: eles podem sair de fininho.

O prosente trabalho tem por finalidade


*	Aprender a predizer a probabilidade de rotatividade (para o mês seguinte) para cada cliente
*	Elaborar retratos de usuários típicos: selecionar os grupos mais marcantes e descrever suas principais características
*	Analisar os fatores que mais impactam a rotatividade
*	Tirar conclusões básicas e desenvolver recomendações sobre como melhorar o serviço de clientes:
>> *	Identificar grupos alvo
>> *	Sugerir medidas para diminuir a rotatividade
>> *	Descrever qualquer outro padrão que for visto com respeito às interações com clientes.

---

# Descrição dos Dados

O conjunto de dados inclui os seguintes campos:

*	'Churn' — a rotatividade do mês em questão
## Campos de dados atuais:
> ###	Dados do mês anterior:
>> *	'gender'
>> *	'Near_Location' — se o cliente morar ou trabalhar na vizinhança onde a academia está localizada
>> *	'Partner' — se o usuário for um funcionário de uma companhia parceira (a academia tem empresas parceiras cujos funcionários conseguem descontos; nesses casos, a academia armazena informações sobre clientes de são funcionários)
>> *	Promo_friends — se o cliente originalmente se inscreveu através de uma oferta "traga um amigo" eles normalmente usam o código de promoção do amigo quando pagam pela primeira filiação)
>> *	'Phone' — se o usuário fornece o seu número de telefone
>> *	'age' (idade)
>> *	'Lifetime' — o tempo (em meses) desde a primeira vez que o cliente veio à academia

## Dados do log de frequência e compras e dados sobre status de filiação atual
>> *	'Contract_period' — 1 mês, 3 meses, 6 meses, ou um ano
>> *	'Month_to_end_contract' — os meses remanescentes até que o contrato expira
>> *	'Group_visits' — se o cliente participa de sessões em grupo
>> *	'Avg_class_frequency_total' — frequência média de idas por semana por toda a vida do cliente
>> *	'Avg_class_frequency_current_month' — frequência média de visitas por semana durante o mês corrente
>> *	'Avg_additional_charges_total' — a quantidade total de dinheiro gasto em outros serviços da academia: café, artigos esportivos, cosméticos, massagem, etc.

--- 

# Conclusão

Baseado nas análises feitas, foi reforçado que a quantidade de 27% de saídas de clientes em um único mês é um valor muito alto para deixar passar despercebido. Portanto, fez-se necessário recomendar que fosse elaborado uma estratégia de retenção desses clientes, focada principalmente naqueles clientes que foram classificado no grupo de risco. 

Deve-se reforçar a retenção de clientes, focando em fazê-los permanecer um periodo maior. Para que eles permaneçam, devemos lembrar que exercício físico é penoso para muitos e é desconfortável, portanto deve-se tornar o processo mais leve e prazeroso para o cliente. 

Observa-se que os clientes que participam de atividades em grupo e os que foram indicados por amigos, tem uma taxa de saída menor.

Clientes mais novos, possuem uma taxa de saída maior, enquanto os que possuem mais idade tendem a permanecer mais tempo.

Baseado nessas análises foi feita um classificação e agrupamento dos clientes em grupos. Essa classificação poderá ajudar a entender o comportamento dos clientes e traçar perfis de risco.
Com esses dados em mãos, a academia poderá criar estratégias personalizadas para cada tipo de cliente, ou grupo. Com isso, poderá aumentar sua receita e sua taxa de retenção.