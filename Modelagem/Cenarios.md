> **Autor:** Wictor Girardi, Daniel Oda
>
> **Descrição:** Cenários
>
> **Versão:** 0.2

## Introdução

A observação do cenário é quase sempre a primeira técnica utilizada para identificar os requisitos de negócio e de software. Tratasse de um método informal porêm extremamente eficiente.

## Metodologia

Para a contrução dos cenários foi proposto o seguinte modelo de _abstração_ mostrado abaixo.

|**Cenário XX**|
|--------------|
|**Titulo**    |
|_Nome do Cenário._|
|**Objetivo**  |
|_Objetivo do Cenário._|
|**Contexto**  |
|<p>Local: _Local onde acontece o Cenário._</p> <p>Tempo: _Tempo do Cenário._</p> <p>Pré-condição: _Condição para que o Cenário aconteça._</p>|
|**Atores**    |
|_Autor(es) do Léxico._|
|**Recursos**  |
|_Recursos do Cenário._|
|**Episódios** |
|_Episódios do Cenário da aplicação._|
|**Restrição** |
|_Restrição do Cenário._|
|**Exceção**   |
|_Exceção do Cenário._|


## Cenário 01
|**Cenário 01**|
|--------------|
|**Titulo**    |
|Cadastro de um novo usuário na Rappi |
|**Objetivo**  |
|Cadastrar um novo usuário|
|**Contexto**  |
|<p>Local: Tela inicial ao entrar na aplicação pela primeira vez</p> <p>Tempo: Indeterminado</p> <p>Pré-condição: Acesso a internet e acesso a rede telefonica</p>|
|**Atores**    |
|Usuário não cadastrado|
|**Recursos**  |
|<p>Internet</p> <p>Smartphone</p> <p>Aplicativo da Rappi já instalado</p>|
|**Episódios** |
|<p>Usuário novo</p> <p>Usuário que deseja criar uma conta no app</p> <p>Usuário seleciona sua localidade</p> <p>Usuário entra com o número do telefone celular</p> <p>Escolhe entre receber o código por WhatsApp ou SMS</p> <p>Digita o código recebido</p>|
|**Restrição** |
|Internet indisponível, Rede celular indisponível, Localidade indisponível|
|**Exceção**   |
|<p>Sem acesso ao Smartphone</p> <p>Telefone inexistente</p> <p>Internet indisponível</p>|

## Cenário 02
|**Cenário 02**|
|--------------|
|**Titulo**    |
|Comprando em um restaurante|
|**Objetivo**  |
|Escolher um restaurante para realizar o pedido|
|**Contexto**  |
|<p>Local: Tela inicial, Tela de restaurantes</p> <p>Tempo: Indeterminado</p> <p>Pré-condição: Acesso a internet, localidade atendida pela Rappi</p>|
|**Atores**    |
 <p>Usuário cadastrado</p>|
|**Recursos**  |
|<p>Internet</p> <p>Smartphone</p> <p>App da Rappi previamente instalado</p> <p>Localidade atendida pelo Rappi</p> <p>Forma de pagamento válida</p>|
|**Episódios** |
|<p>Usuário clica na aba 'Restaurante'</p> <p>Usuário escolhe a categoria do restaurante desejado</p> <p>Usuário escolhe o Restaurante</p> <p>Usuário escolhe a refeição dentro do cardapio do restaurante</p> <p>Usuário escolhe os acompanhamentos do pedido</p> <p>Usuário escolhe o endereço de entrega</p> <p>Usuário escolhe forma de pagamento válida</p> <p>Usuário finaliza a compra da refeição</p> |
|**Restrição** |
|<p>Internet indisponível</p> <p>Localidade não atendida</p> <p>Forma de pagamento inválida</p>|
|**Exceção**   |
|<p>Sem acesso a Smartphone</p> <p>Internet indisponível</p>|

## Cenário 03
|**Cenário 03**|
|--------------|
|**Titulo**    |
|Comprando em um supermercado|
|**Objetivo**  |
|Realizar a compra em um supermercado especifíco|
|**Contexto**  |
|<p>Local: Tela inicial, Tela de supermercados</p> <p>Tempo: Indeterminado</p> <p>Pré-condição: Acesso a internet, Usuário cadastrado</p>|
|**Atores**|
|Usuário da Rappi|
|**Recursos**  |
|<p>Internet</p> <p>Smartphone</p> <p>App da Rappi previamente instalado</p> <p>Localidade atendida pelo Rappi</p> <p>Forma de pagamento válida</p>|
|**Episódios** |
|<p>Usuário clica na aba 'SuperMercados'</p> <p>Usuário escolhe a categoria do supermercado desejado</p> <p>Usuário escolhe o supermercado</p> <p>Usuário escolhe a categoria do produto dentro do supermercado</p> <p>Usuário escolhe o produto</p> <p>Usuário escolhe a quantidade de produtos</p> <p>Usuário escolhe o endereço de entrega</p> <p>Usuário escolhe forma de pagamento válida</p> <p>Usuário finaliza a compra dos produtos</p>|
|**Restrição** |
<p>Internet indisponível</p> <p>Localidade não atendida</p> <p>Forma de pagamento inválida</p>|
|**Exceção**   |
|<p>Sem acesso a Smartphone</p> <p>Internet indisponível</p>|

## Cenário 04
|**Cenário 04**|
|--------------|
|**Titulo**    |
|Comprando em uma farmácia|
|**Objetivo**  |
|Realizar a compra em uma farmácia especifíca|
|**Contexto**  |
|<p>Local: Tela inicial, Tela de farmácia</p> <p>Tempo: Indeterminado</p> <p>Pré-condição: Acesso a internet, Usuário cadastrado</p>|
|**Atores**|
|Usuário da Rappi|
|**Recursos**  |
|<p>Internet</p> <p>Smartphone</p> <p>App da Rappi previamente instalado</p> <p>Localidade atendida pelo Rappi</p> <p>Forma de pagamento válida</p>|
|**Episódios** |
|<p>Usuário clica na aba 'farmácias'</p> <p>Usuário escolhe a farmácia</p> <p>Usuário escolhe a categoria do medicamento dentro da farmacia</p> <p>Usuário escolhe o produto</p> <p>Usuário escolhe a quantidade de produtos</p> <p>Usuário escolhe o endereço de entrega</p> <p>Usuário escolhe forma de pagamento válida</p> <p>Usuário finaliza a compra dos produtos</p>|
|**Restrição** |
<p>Internet indisponível</p> <p>Localidade não atendida</p> <p>Forma de pagamento inválida</p>|
|**Exceção**   |
|<p>Sem acesso a Smartphone</p> <p>Internet indisponível</p>|


## Cenário 05
|**Cenário 05**|
|--------------|
||**Titulo**    |
|Comprando bebidas|
|**Objetivo**  |
|Realizar a compra de bebidas em uma loja especifíca|
|**Contexto**  |
|<p>Local: Tela inicial, Tela de bebidas</p> <p>Tempo: Indeterminado</p> <p>Pré-condição: Acesso a internet, Usuário cadastrado</p>|
|**Atores**|
|Usuário da Rappi|
|**Recursos**  |
|<p>Internet</p> <p>Smartphone</p> <p>App da Rappi previamente instalado</p> <p>Localidade atendida pelo Rappi</p> <p>Forma de pagamento válida</p>|
|**Episódios** |
|<p>Usuário clica na aba 'bebidas'</p> <p>Usuário escolhe a loja</p> <p>Usuário escolhe a categoria da bebida dentro da loja</p> <p>Usuário escolhe o produto</p> <p>Usuário escolhe a quantidade de produtos</p> <p>Usuário escolhe o endereço de entrega</p> <p>Usuário escolhe forma de pagamento válida</p> <p>Usuário finaliza a compra dos produtos</p>|
|**Restrição** |
<p>Internet indisponível</p> <p>Localidade não atendida</p> <p>Forma de pagamento inválida</p>|
|**Exceção**   |
|<p>Sem acesso a Smartphone</p> <p>Internet indisponível</p>|

## Cenário 06
|**Cenário 06**|
|--------------|
||**Titulo**    |
|Comprando uma BMW|
|**Objetivo**  |
|Realizar a compra de um veículo BMW|
|**Contexto**  |
|<p>Local: Tela inicial, Tela da BMW</p> <p>Tempo: Indeterminado</p> <p>Pré-condição: Acesso a internet, Usuário cadastrado</p>|
|**Atores**|
|Usuário da Rappi|
|**Recursos**  |
|<p>Internet</p> <p>Smartphone</p> <p>App da Rappi previamente instalado</p> <p>Localidade atendida pelo Rappi</p> <p>Forma de pagamento válida</p>|
|**Episódios** |
|<p>Usuário clica na aba 'BMW'</p> <p>Usuário escolhe a loja</p>  <p>Usuário escolhe o veículo</p> <p>Usuário escolhe a quantidade de veículos</p> <p>Usuário escolhe o endereço de entrega</p> <p>Usuário escolhe forma de pagamento válida</p> <p>Usuário finaliza a compra dos veículos</p>|
|**Restrição** |
<p>Internet indisponível</p> <p>Localidade não atendida</p> <p>Forma de pagamento inválida</p>|
|**Exceção**   |
|<p>Sem acesso a Smartphone</p> <p>Internet indisponível</p>|


## Cenário 07
|**Cenário 07**|
|--------------|
||**Titulo**    |
|Comprando artigos para animais domésticos na loja PETZ|
|**Objetivo**  |
|Realizar a compra de artigos para animais domésticos na loja PETZ|
|**Contexto**  |
|<p>Local: Tela inicial, Tela da Petz</p> <p>Tempo: Indeterminado</p> <p>Pré-condição: Acesso a internet, Usuário cadastrado</p>|
|**Atores**|
|Usuário da Rappi|
|**Recursos**|
|<p>Internet</p> <p>Smartphone</p> <p>App da Rappi previamente instalado</p> <p>Localidade atendida pelo Rappi</p> <p>Forma de pagamento válida</p>|
|**Episódios** |
|<p>Usuário clica na aba 'PETZ'</p> <p>Usuário escolhe a categorias de produto</p> <p>Usuário escolhe o produto</p> <p>Usuário escolhe a quantidade de produtos</p> <p>Usuário escolhe o endereço de entrega</p> <p>Usuário escolhe forma de pagamento válida</p> <p>Usuário finaliza a compra dos produtos</p>|
|**Restrição** |
<p>Internet indisponível</p> <p>Localidade não atendida</p> <p>Forma de pagamento inválida</p>|
|**Exceção**   |
|<p>Sem acesso a Smartphone</p> <p>Internet indisponível</p>|

## Cenário 08
|**Cenário 08**|
|--------------|
||**Titulo**   |
|Realizando doações para a Amazônia|
|**Objetivo**  |
|Realizar doações para a Amazônia|
|**Contexto**  |
|<p>Local: Tela inicial, Tela do 'act for Amazônia'</p> <p>Tempo: Indeterminado</p> <p>Pré-condição: Acesso a internet, Usuário cadastrado</p>|
|**Atores**|
|Usuário da Rappi|
|**Recursos**|
|<p>Internet</p> <p>Smartphone</p> <p>App da Rappi previamente instalado</p> <p>Forma de pagamento válida</p>|
|**Episódios** |
|<p>Usuário clica na aba 'act for Amazônia'</p> <p>Usuário escolhe o valor da doação</p> <p>Usuário escolhe a quantidade de doações</p> <p>Usuário finaliza as doações</p> <p>Usuário escolhe forma de pagamento válida</p>|
|**Restrição** |
<p>Internet indisponível</p> <p>Forma de pagamento inválida</p>|
|**Exceção**   |
|<p>Sem acesso a Smartphone</p> <p>Internet indisponível</p>|

## Cenário 09
|**Cenário 09**|
|--------------|
||**Titulo**   |
|Realizando o pedido de dinheiro|
|**Objetivo**  |
|Realizar o pedido de dinheiro|
|**Contexto**  |
|<p>Local: Tela inicial, Tela do 'cash'</p> <p>Tempo: Indeterminado</p> <p>Pré-condição: Acesso a internet, Usuário cadastrado</p>|
|**Atores**|
|Usuário da Rappi|
|**Recursos**|
|<p>Internet</p> <p>Smartphone</p> <p>App da Rappi previamente instalado</p> <p>Localidade atendida pelo Rappi</p> <p>Forma de pagamento válida</p>|
|**Episódios** |
|<p>Usuário clica na aba 'cash'</p> <p>Usuário escolhe o valor do saque</p> <p>Usuário escolhe o endereço de entrega</p> <p>Usuário escolhe forma de pagamento válida</p> <p>Usuário finaliza as doações</p>|
|**Restrição** |
<p>Internet indisponível</p> <p>Localidade não atendida</p> <p>Forma de pagamento inválida</p>|
|**Exceção**   |
|<p>Sem acesso a Smartphone</p> <p>Internet indisponível</p>|

## Cenário 10
|**Cenário 10**|
|--------------|
||**Titulo**   |
|Realizando a plantação de árvores|
|**Objetivo**  |
|Realizar a plantação de árvores|
|**Contexto**  |
|<p>Local: Tela inicial, Tela do 'sua árvore'</p> <p>Tempo: Indeterminado</p> <p>Pré-condição: Acesso a internet, Usuário cadastrado</p>|
|**Atores**|
|Usuário da Rappi|
|**Recursos**|
|<p>Internet</p> <p>Smartphone</p> <p>App da Rappi previamente instalado</p> <p>Localidade atendida pelo Rappi</p> <p>Forma de pagamento válida</p>|
|**Episódios** |
|<p>Usuário clica na aba 'sua árvore'</p> <p>Usuário escolhe a quantidade de árvores a serem plantadas</p> <p>Usuário escolhe forma de pagamento válida</p> <p>Usuário finaliza o plantio</p>|
|**Restrição** |
<p>Internet indisponível</p> <p>Localidade não atendida</p> <p>Forma de pagamento inválida</p>|
|**Exceção**   |
|<p>Sem acesso a Smartphone</p> <p>Internet indisponível</p>|

## Cenário 11
|**Cenário 11**|
|--------------|
||**Titulo**   |
|Realizando doações para a AACD|
|**Objetivo**  |
|Realizar doações para a AACD|
|**Contexto**  |
|<p>Local: Tela inicial, Tela do 'AACD'</p> <p>Tempo: Indeterminado</p> <p>Pré-condição: Acesso a internet, Usuário cadastrado</p>|
|**Atores**|
|Usuário da Rappi|
|**Recursos**|
|<p>Internet</p> <p>Smartphone</p> <p>App da Rappi previamente instalado</p> <p>Forma de pagamento válida</p>|
|**Episódios** |
|<p>Usuário clica na aba 'AACD'</p> <p>Usuário escolhe o valor da doação</p> <p>Usuário escolhe a quantidade de doações</p> <p>Usuário escolhe forma de pagamento válida</p> <p>Usuário finaliza as doações</p>|
|**Restrição** |
<p>Internet indisponível</p> <p>Forma de pagamento inválida</p>|
|**Exceção**   |
|<p>Sem acesso a Smartphone</p> <p>Internet indisponível</p>|


## Cenário 12
|**Cenário 12**|
|--------------|
||**Titulo**   |
|Adicionar e verificar Cupons|
|**Objetivo**  |
|Adicionar e verificar Cupons|
|**Contexto**  |
|<p>Local: Tela inicial, icone de cupons</p> <p>Tempo: Indeterminado</p> <p>Pré-condição: Acesso a internet, Usuário cadastrado</p>|
|**Atores**|
|Usuário da Rappi|
|**Recursos**|
|<p>Internet</p> <p>Smartphone</p> <p>App da Rappi previamente instalado</p> <p>Localidade atendida pelo Rappi</p>|
|**Episódios** |
|<p>Usuário clica no icone de cupons</p> <p>Usuário digíta ou verifica se há um cupom</p> <p>Usuário aplica o cupom</p>|
|**Restrição** |
<p>Internet indisponível</p> <p>Localidade não atendida</p>|
|**Exceção**   |
|<p>Sem acesso a Smartphone</p> <p>Internet indisponível</p>|


## Cenário 13
|**Cenário 13**|
|--------------|
|**Titulo**    |
|Avaliar quantidade de pontos obtidos|
|**Objetivo**  |
|O usuário pode checar com qual pontuação ele esta no aplicativo |
|**Contexto**  |
|<p>Local: Tela inicial do site, ícone inferior mais à direita com um diamante</p> <p>Tempo: Indeterminado</p> <p>Pré-condição: Acesso a internet, ser usuário</p>|
|**Atores**    |
|Usuário da Rappi|
|**Recursos**  |
|<p>Internet</p> <p>Computador</p>|
|**Episódios** |
|<p>Usuário já cadastrado clica no ícone inferior mais à direita com um diamante</p> <p>Usuário vê sua quantidade de pontos no aplicativo</p> <p>Usuário pode verificar em qual nivel ele se encontra e quanto falta para ele subir de nivel</p> <p>Usuário pode verificar as missões ativas</p> |
|**Restrição** |
<p>Internet indisponível</p> <p>Localidade não atendida</p>|
|**Exceção**   |
|<p>Sem acesso a Smartphone</p> <p>Internet indisponível</p>|

## Cenário 14
|**Cenário 14**|
|--------------|
|**Titulo**    |
|Solicitar suporte da Rappi|
|**Objetivo**  |
|O usuário pode solicitar o suporte ou verificar a entrega de um pedido passado |
|**Contexto**  |
|<p>Local: Tela inicial do site, ícone inferior segundo a direita com um fone de ouvido</p> <p>Tempo: Indeterminado</p> <p>Pré-condição: Acesso a internet, ser usuário</p>|
|**Atores**    |
|Usuário da Rappi|
|**Recursos**  |
|<p>Internet</p> <p>Computador</p>|
|**Episódios** |
|<p>Usuário já cadastrado clica no ícone inferior segundo a direita com um fone de ouvido</p> <p>Usuário pode solicitar o suporte direto</p> <p>Usuário pode solicitar ajuda em cima de qualquer pedido realizado</p> <p>Usuário pode verificar o recibo dos pedidos realizados</p> |
|**Restrição** |
<p>Internet indisponível</p> <p>Localidade não atendida</p>|
|**Exceção**   |
|<p>Sem acesso a Smartphone</p> <p>Internet indisponível</p>|


## Cenário 15
|**Cenário 15**|
|--------------|
|**Titulo**    |
|Verificar e adicionar restaurantes ou pedidos favoritos|
|**Objetivo**  |
|O usuário pode adicionar restaurantes ou pedidos favoritos|
|**Contexto**  |
|<p>Local: Tela inicial do site, ícone inferior central com coração</p> <p>Tempo: Indeterminado</p> <p>Pré-condição: Acesso a internet, ser usuário</p>|
|**Atores**    |
|Usuário da Rappi|
|**Recursos**  |
|<p>Internet</p> <p>Computador</p>|
|**Episódios** |
|<p>Usuário já cadastrado clica no íconeinferior central com coração</p> <p>Usuário pode visualizar os pedidos e lojas favoritas</p> <p>Usuário pode adicionar pedidos como favoritos</p> |
|**Restrição** |
<p>Internet indisponível</p> <p>Localidade não atendida</p>|
|**Exceção**   |
|<p>Sem acesso a Smartphone</p> <p>Internet indisponível</p>|

## Referências

SEQ18RRANO, Maurício; SERRANO, Milene. Requisitos - Aula 10. 1º/2019. 35 slides. Material apresentado para a disciplina de Requisitos de Software no curso de Engenharia de Software da UnB, FGA.
