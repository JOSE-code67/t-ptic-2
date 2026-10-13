* fazer as atividades no Teams
* mostrar o fluxograma
* como foi feito o código(explicação da lógica)
* linquagem de programação- anything
* apresentação de slides



# SISTEMA DE CONTROLE DE ESTOQUE E ALERTA DE REPOSIÇÃO(MERCADINHO)



Foco: pequeno Comércio Local



##### SITUAÇÃO PROBLEMA:



&#x09;um pequeno mercado de bairro perde produtos por falta de controle de estoque mínimo e não sabe quando fazer novos pedidos aos fornecedores, gerando perda de vendas.



##### CASO DE USO (UCO2 - CADASTRAR E VERIFICAR ESTOQUE):



ATORES: Atendente de Estoque



FLUXOS: O usuário cadastra produtos em um laço. Para cada item, insere nome, quantidade atual e quantidade mínima. O sistema utiliza operadores lógicos para emitir alertas e reposição urgente.



##### BACKLOG DO PRODUTO:



* leitura contínua de produtos até solicitação de parada.
* Verificação condicional ('quantidade < mínimo' AND 'mínimo > 0 ')
* Classificação de status 'Crítico', 'Atenção', ou 'OK'
* resumo final listando apenas os itens que precisam de compra urgente.





##### USER STORY:



"como comerciante, quero registrar a quantidade dos meus produtos e receber um alerta automático para os itens cujo estoque esteja abaixo do limite para não ficar sem mercadoria"

