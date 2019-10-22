# Product e Sprint Backlog
> **Autor:** Lucas Ganda
>
> **Descrição:** Criação do documento
>
> **Versão:** 0.1
> 
#### Feature 01 - Cadastro de contas

- **US01**: Enquanto Usuário, eu devo me cadastrar no aplicativo, assim, posso efetuar meus pedidos.
- **US02**: Enquanto Gerente de Estabelecimento, eu devo me cadastrar no aplicativo, assim, posso gerenciar meu estabelecimento, meus produtos e pedidos

**ID**|**Descrição**|**Prioridade**| 
:---:|:---|:---:
TASK01 | <p align="justify">CRUD de Usuário por meio de número de celular.</p> | 1,02| 
TASK02 | <p align="justify">CRUD de Estabelecimento por meio de email e aprovação da equipe Rappi. </p>| 1,14|
TASK03 | <p align="justify">Definir os critérios mínimos para aceitação de um Estabelecimento. </p>| 1,14|

#### Feature 02 - Cadastro de endereços
- **US05**: Enquanto Usuário, eu devo cadastrar meu endereço de entrega.
- **US06**: Enquanto Gerente de Estabelecimento, eu devo cadastrar o endereço do meu estabelecimento.
- **US15**: Enquanto Usuário, eu posso cadastrar mais de um endereço de entrega, para aumentar a flexibilidade e agilidade na hora do pedido.

**ID**|**Descrição**|**Prioridade**| 
:---:|:---|:---:
TASK04 | <p align="justify">CRUD de endereço de entrega por CEP.</p> | 0,37|
TASK05 | <p align="justify">Utilizar geolocalização como meio de obtenção de endereço de entrega.</p> | 0,37|
TASK06 | <p align="justify">CRUD de endereço de Estabelecimento por CEP.</p>| 0,37|
TASK07 | <p align="justify">Possibilitar que um Usuário tenha mais de um endereço associado a ele.</p>|0,49|

#### Feature 03 - Cadastro de meio de pagamento
- **US03**: Enquanto Usuário, eu devo cadastrar meus meios de pagamento, assim, posso finalizar meus pedidos.
- **US04**: Enquanto Gerente de Estabelecimento, eu devo cadastrar os meios de pagamento aceitos no meu estabelecimento, assim, os Usuários podem verificar se podem comprar aqui.

**ID**|**Descrição**|**Prioridade**| 
:---:|:---|:---:
TASK09 | <p align="justify">CRUD de meios de pagamento do Usuário.</p> | 0,46| 
TASK10 | <p align="justify">CRUD de meios de pagamento associados ao Estabelecimento.</p>| 0,46|

#### Feature 04 - Cadastro de Estoque
- **US27**: Enquanto Gerente de Estabelecimento, eu posso definir o estoque de cada produto, para evitar pedidos com produtos fora de estoque.
- **US28**: Enquanto Gerente de Estabelecimento, eu posso definir desconto para produtos específicos da minha carta de produtos, para decisões estratégicas da empresa e/ou engajar os usuários a fazer mais pedidos.

**ID**|**Descrição**|**Prioridade**| 
:---:|:---|:---:
TASK11 | <p align="justify">CRUD de produto.</p> | 0,33|
TASK12 | <p align="justify">Propriedade de número de produtos em estoque poder ser facilmente alterada durante a execução de um pedido.</p> | 0,33| 
TASK13 | <p align="justify">Propriedade de desconto em produtos específicos poder ser facilmente alterada durante o uso do Gerente do Estabelecimento.</p>| 0,39|

#### Feature 05 - Busca de estabelecimento e decisão do pedido
- **US07**: Enquanto Usuário, eu posso navegar e procurar Estabelecimentos por categoria, facilitando o uso do aplicativo.
- **US08**: Enquanto Gerente de Estabelecimento, eu posso categorizar meu estabelecimento, para facilitar o uso do aplicativo para o Usuário.
- **US09**: Enquanto Usuário, eu posso verificar o tempo médio de entrega de todos os estabelecimentos, para auxiliar na minha tomada de decisão.
- **US10**: Enquanto Gerente de Estabelecimento, eu devo fornecer o tempo médio de entrega do meu estabelecimento, para gerar mais confiança entre o mesmo e os usuários.
- **US16**: Enquanto Usuário, eu posso verificar o horário de funcionamento do estabelecimento, para evitar perda de tempo pensando em um pedido de um restaurante que não está disponível.
- **US17**: Enquanto Gerente de Estabelecimento, eu devo definir os horários de funcionamento do meu estabelecimento.
- **US18**: Enquanto Usuário, eu devo ter a flexibilidade de escolher produtos de diferentes estabelecimentos e colocar na minha Cesta de Compras, para otimizar meu tempo e pagar apenas um entregador.
- **US19**: Enquanto Entregador, eu devo ter a listagem dos produtos de um usuário incluindo de onde vem cada produto, para evitar erros e desentendimentos entre ambas as partes.
- **US21**: Enquanto Usuário, eu posso ordenar o resultado de uma pesquisa por tempo de entrega ou taxa de entrega.

**ID**|**Descrição**|**Prioridade**| 
:---:|:---|:---:
TASK14 | <p align="justify">Criação de tela de resultado de busca e lógica de mecanismo de busca.</p> | 0,40| 
TASK15 | <p align="justify">Criação de mecanismo de categorias e refletir no mecanismo de busca.</p> | 0,40| 
TASK16 | <p align="justify">Propriedade de categoria do Estabelecimento ser definido pelo Gerente do Estabelecimento</p>| 0,40|
TASK17 | <p align="justify">Criação de mecanismo de tempo médio e refletir no mecanismo de busca.</p>| 0,46|
TASK18 | <p align="justify">Propriedade de horário de funcionamento no CRUD do Estabelecimento</p>| 0,95|
TASK19 | <p align="justify">Criação de elementos visuais para refletir na UI os Estabelecimentos abertos e fechados e refletir no mecanismo de busca.</p>| 0,46|
TASK20 | <p align="justify">Implementação visual e lógica de Cesta de Compras.</p>| 0,51|
TASK21 | <p align="justify">Implementação lógica para que o Usuário possa comprar produtos de diferentes Estabelecimentos em seu pedido.</p>| 0,51|
TASK22 | <p align="justify">Implementação visual e lógica para que o Entregador tenha acesso de forma clara a todos os produtos listados no pedido.</p>| 0,51|
TASK23 | <p align="justify">Criação de mecanismo de filtro e ordenação nos resultados de busca.</p>| 0,51|

#### Feature 06 - Cupons e desconto
- **US22**: Enquanto Gerente de Estabelecimento, eu posso definir a validade de cupons no meu estabelecimento.
- **US24**: Enquanto Usuário, eu posso receber notificações com promoções e novas funcionalidades do aplicativo, para estar mais engajado na plataforma.

**ID**|**Descrição**|**Prioridade**| 
:---:|:---|:---:
TASK24 | <p align="justify">Criação de lógica dos cupons de desconto.</p> | 0,68|
TASK25 | <p align="justify">Criação de UI para o Gerente de Estabelecimento definir quais cupons são válidos em seu Estabelecimento.</p> | 0,68|
TASK26 | <p align="justify">Criação de lógica de push notifications para veicular promoções do aplicativo para o Usuário.</p>| 0,30|

#### Feature 07 - Acompanhamento do pedido
- **US11**: Enquanto Entregador, eu posso decidir quais estabelecimentos são válidos para eu realizar uma entrega, baseado na distância que estou dele.
- **US12**: Enquanto Usuário, eu posso verificar o status do meu pedido, para ter uma sensação maior de controle e familiaridade.
- **US13**: Enquanto Gerente de Estabelecimento, eu posso modificar o status do pedido de um usuário, para ser mais transparente com este.
- **US14**: Enquanto Entregador, eu devo modificar o status do pedido quando estiver no processo de entrega, para ser mais transparente com o usuário.
- **US23**: Enquanto Usuário, Entregador ou Gerente de Estabelecimento, eu posso utilizar o chat de dúvidas, para sanar dúvidas e resolver problemas.

**ID**|**Descrição**|**Prioridade**| 
:---:|:---|:---:
TASK27 | <p align="justify">Criação de UI para o Entregador definir seu raio de atuação.</p> | 0,46| 
TASK28 | <p align="justify">Implementação de lógica de status do pedido, sendo facilmente atualizada.</p>| 0,32|
TASK29| <p align="justify">Implementação da tela do chat de dúvidas e lógica de funcionamento do mesmo.</p>| 0,45|

#### Feature 08 - Avaliação
- **US20**: Enquanto Usuário, eu posso avaliar o entregador, para contribuir positiva ou negativamente com o trabalho do entregador.
- **US25**: Enquanto Usuário, eu posso acessar um histórico com todos meus pedidos.
- **US26**: Enquanto Usuário, eu posso enviar gorjeta para entregadores segundo a minha vontade e disponibilidade, para parabenizá-lo pelo bom trabalho.

**ID**|**Descrição**|**Prioridade**| 
:---:|:---|:---:
TASK30 | <p align="justify">Criação de UI e lógica para feedback do entregador.</p> | 0,34| 
TASK31 | <p align="justify">Criação de UI e lógica para histórico de pedidos do usuário</p> | 0,49|
US26 | <p align="justify"><Criação de UI e lógica de envio de gorjetas feitas pelo Usuário para o Entregador. </p>| 0,11|
