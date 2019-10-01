Especificação Suplementar - Rappi
===

|Membros participantes|
|---------------------|
|Wictor Girardi|
|André Freitas|
|Daniel Ashton|
|Gustavo Veloso|
|Lucas Ganda|
|João de Assis|

## Índice

[TOC]

## Introdução

Este documento captura os requisitos de sistema que não foram identificados previamente na elicitação. Entre estes requisitos estão incluídos:
* Atributos  de  qualidade  do  sistema  a  ser  criado;
* Sistemas   operacionais e requisitos   de compatibiliade;

## Finalidade

Este documento tem como finalidade definir requisitos não funcionais da aplicação **Rappi**, classificando-os em requisitos  de  usabilidade, confiabilidade, desempenho ou suportabilidade. A especificação suplementar junto com o modelo de casos de uso engloba todos os requisitos do sistema.

## Escopo

A **Rappi** é um app de entregas, seguindo o Workflow estabelecido pelo iFood, você, enquanto usuário cria uma conta, escolhe um produto, cadastra um meio de pagamento e faz um pedido baseado nos produtos escolhidos. Entretanto, apesar de suas semelhanças com outros apps do mesmo nicho, a **Rappi** se tornou disruptiva, principalmente, devido a o que pode ser pedido em sua plataforma, seus concorrentes se limitam a comida vinda de restaurantes e lanchonetes enquanto a **Rappi** também cobre outros tipos variados de comércio.

## Visão Geral

A  seguir, são expostos os requisitos suplementares distribuídos em usabilidade, confiabilidade, desempenho e suportabilidade.

## Requisitos Suplementares:

### Usabilidade

* O sistema realiza o cadastro de forma rápida através de uma conta previamente existente no facebook ou whatsapp. O cadastro também pode ser realizado somente com o número do celular.
* Usuário consegue realizar uma compra em 4 interações(cadastro de endereço, escolha do estabelecimento, escolha dos produtos, forma de pagamento).
* Sistema cria  um direcionamento intuitivo para o usuário realizar a compra. Estabelecimentos são separados por categorias específicas e o processo de compra que se realiza é o mesmo para todos.

| Requisito | Descrição |
| -------- | -------- |
| Requisito de Usabilidade 1 | O sistema exige que o usuário saiba instalar o app por meio da loja de seu respectivo sistema operacional. |
| Requisito de Usabilidade 2 | O sistema exige que o usuário possua um número de celular ou conta nas aplicações facebook e whatsapp para fins de cadastro. |
| Requisito de Usabilidade 3 | O sistema exige que o usuário possua forma de pagamento e endereço de entrega válidos. |

### Confiabilidade

* As informações apresentadas pelo sistema ao usuário devem condizer inequivocadamente com a realidade do que foi registrado no banco de dados, pois a entrega e o pagamento dependem totalmente de dados corretos para o funcionamento da aplicação.
* Sistema possibilita um suporte em tempo real para a resolução de eventuais problemas.

| Requisito | Descrição |
| --------  | ----------|
| Requisito de Confiabilidade 1 | O sistema está disponível 24 horas por dia, 7 dias por semana. |
| Requisito de Confiabilidade 2 | O sistema disponibiliza suporte para a resolução de problemas em pedidos.|
| Requisito de Confiabilidade 3 | O sistema disponibiliza atualizações constantes para a correção de erros e adição de novas funcionalidades.|

### Desempenho

* O tempo de resposta para cada interação deve ser o mínimo possível.
* O tempo para a confirmação do pedido deve ser o mínimo possível.
* O tempo para o envioo do número de confirmação para cadastro via whatsapp ou SMS deve ser o mínimo possível.

| Requisito | Descrição |
| --------  | ----------|
| Requisito de Desempenho 1 | O sistema deve suportar acessos simultâneos de diferentes usuários. |
| Requisito de Desempenho 2 | O sistema deve ser capaz de confirmar o pagamento o mais rápido possível. |
| Requisito de Desempenho 3 | O sistema deve exibir em tempo real a situação do pedido. |

### Suportabilidade

* O usuário deve ser capaz de utilizar o sistema através de seu smartphone com sistema operacional Android ou iOS.
* O usuário deve ser capaz de utilizar o sistema através de um navegador web.
* O usuário deve possuir em seu aparelho espaço disponível para a aplicação.

#### Especificação de Software:

| Sistema Operacional: | Android | Apple | Windows/Linux/Mac |
| -------- | -------- | -------- | -------- |
| Requer versão: | Android 4.1 ou superior. | Requer o iOS 10.0 ou posterior. Compatível com iPhone, iPad e iPod touch. | Qualquer navegador web. |
| Espaço disponível necessário: | 16 MB | 332,1 MB | ------------------------------------- |

| Descrição | Complemento |
| --------  | --------    |
| Conexão:  | Internet    |

## Restrições de Design

* O design do sistema do software deverá estar em  conformidade com os padrões do framework React(Javascript, Html, Css).
