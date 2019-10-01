> *Autor:* Grupo
>
> *Descrição:* Criação do documento
>
> *Versão:* 0.1
 
> *Autor:* Wictor Giradi e Gustavo Veloso
>
> *Descrição:* Inserção das técnicas de elicitação usadas para cada requisito
>
> *Versão:* 0.2

# Priorização de Requisitos - MoSCoW

Esta técnica foi originalmente incluída nas técnicas do Método de Desenvolvimento Dinâmico de Sistemas – Dynamic Systems Development Method (DSDM).

A técnica é muito simples: para cada requisito ou item do seu backlog, você deverá atribuir um das quatro letras M,S,C ou W e cada uma delas tem um significado diferente:

### Must

Itens (requisitos, projetos, backlogs), classificados como MUST são críticos para a geração de valor para a empresa, atendimento de norma legal (ex: normativas da bolsa de valores, banco central, agências do governo, Receita Federal, etc), relacionados a Riscos/Compliance ou que afetam a imagem e credibilidade da empresa. Se um dos itens não é concluído e entregue, o projeto não pode ser considerado como sendo concluído com sucesso.

### Should

Itens classificados como SHOULD são importantes, mas não são necessários (do ponto de vista estratégico) para entrega neste momento. Itens SHOULD são tão importantes como os MUST, mas geralmente não são críticos ou pode-se ter outro meio de se atender a necessidade ou pode-se esperar um pouco para ser trabalhado (ex: a conclusão de outro projeto em andamento reduzirá ou eliminará a necessidade do projeto demandado).

### Could

Itens classificados como COULD são desejáveis, mas não são necessários (do ponto de vista estratégico) e podem melhorar a experiência e satisfação do cliente com algum esforço de desenvolvimento. Estes itens geralmente pode ser atendidos quando houverem tempo e recursos disponíveis.

### Won’t

Itens classificados como WON´T tem a concordância dos interessados que são itens menos críticos, com menor retorno sobre investimento ou não adequados para serem realizados durante algum período de tempo. Obs: As vezes o termo Would Like (Gostaria) pode ser utilizado para dar melhor entendimento na classificação dos itens.

| Categoria | Descrição do Requisito | Técnica utilizada | Funcional? |
| -------- | -------- | -------- |-------- |
| **Must**     | O aplicativo é obrigado a permitir o cadastro de usuário | Brainstorm | Sim |
| **Must**     | O aplicativo é obrigado a permitir o cadastro de estabelecimentos | Brainstorm | Sim |
| **Must**     | O aplicativo é obrigado a possuir uma ou mais formas de pagamento | Brainstorm | Sim |
| **Must**     | O aplicativo é obrigado a possuir um cadastro preciso de endereços, tanto de usuário quanto dos estabeleciementos | Introspecção | Sim |
| **Should**   | O aplicativo deve possuir categorias específicas diferentes para uma melhor visualização dos estabelecimentos | Introspecção | Não |
| **Should**   | O aplicativo deve exibir um tempo médio de entrega para cada estabelecimento | Instrospecção | Sim |
| **Should**   | O aplicativo deve exibir ao usuário, em tempo real, a situação do seu pedido | Brainstorm | Sim |
| **Should**   | O aplicativo deve possuir uma pesquisa eficaz de estabelecimentos e produtos | Instrospecção | Sim |
| **Should**   | O aplicativo deve permitir ao usuário o cadastro de mais de um endereço de entrega | Observação | Não |
| **Could**    | O aplicativo poderia permitir ao usuário avaliar o entregador e o pedido | Storytelling | Sim |
| **Could**    | O aplicativo poderia permitir ao usuário ordenar os estabelecimentos por tempo de entrega ou por taxa de entrega | Instrospecção | Sim |
| **Could**    | O aplicativo poderia ter um sistema de cupons de desconto para os pedidos | Storytelling | Sim |
| **Could**    | O aplicativo poderia possuir um chat de suporte de eventuais dúvidas e problemas do usuário | Brainstorm | Sim |
| **Could**    | O aplicativo poderia possuir um sistema de notificação ao usuário de promoções e novas funcionalidades | Questionário | Sim |
| **Want**     | O aplicativo poderia permitir ao usuário criar uma lista de estabelecimentos "favoritos" | Questionário | Não |
| **Want**     | O aplicativo poderia estabelecer "missões" ao usuário com uma recompensa de pontos que podem ser trocados por vantagens(Descontos, isenção da taxa de entrega e adição de saldo na conta) para próximos pedidos | Questionário | Sim |