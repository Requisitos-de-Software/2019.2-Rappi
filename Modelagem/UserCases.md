> **Autor:** Grupo
>
> **Descrição:** Casos de usúario
>
> **Versão:** 0.1
> 
> **Autor:** João de Assis
>
> **Descrição:** Refatorando casos de Usuário
>
> **Versão:** 0.2

## Casos de uso

Utilizado para representar os requisitos funcionais de um software, o diagrama de casos de uso é um importante elemento para a documentação do projeto, comunicação interna do time de desenvolvimento e, mesmo, comunicação com o cliente. Por isso, é um ponto fundamental a todo engenheiro, arquiteto, programador, entre outras ocupações que atuam em um projeto, compreender e saber criar diagramas de casos de uso.

### **UC01 - Fazer login**

![Casos de Uso](https://i.imgur.com/FPpyALq.jpg)


| Versão |1.0 29/09/2019 |
| -------------- |:----------- |
| **Autores** | André Freitas e João de Assis |
| **Descrição** | Fazer Login na Rappi |
| **Atores** | > Usuário <br> > Rappi |
| **Pré condições** | > Usuário estar deslogado no aplicativo |
| **Fluxo principal** | > Usuário acessa o aplicativo Rappi <br> > Usuário clica na Bandeira de seu país <br> > Usuário insere seu DDD e seu número de celular <br> > Usuário clica no botão "Receber código" <br> > O número de login é autenticado <br> > O usuário recebe um código de verificação <br> > O código é digitado, e o login é efetuado
| **Fluxos de exceção** | **Número de login inválido:** <br> > É exibida uma modal que informa que o número é inválido e que o problema pode estar no código do país informado <br> |
| **Pós condições** | Usuário permanece logado e sempre é direcionado para o menu inicial da Rappi |

                                                                                 |

### **UC02 - Fazer um pedido**

![](https://i.imgur.com/uxBFYHN.png)




| Versão |1.1 21/10/2019 |
| -------------- |:----------- |
| **Autor(es)** | André Freitas e João de Assis |
| **Descrição** | Realizar um pedido no aplicativo |
| **Ator(es)** | > Usuário do aplicativo <br> > Aplicativo Rappi |
| **Pré condições** | > Estar logado no aplicativo |
| **Fluxo principal** |> Usuário acessa o aplicativo da Rappi <br> > Usuário clica no ícone de Lupa <br> > Usuário pesquisa o nome do estabelecimento desejado <br> > Usuário clica no estabelecimento desejado <br> > Usuário vê o menu <br> > Usuário decide o produto que quer <br> > Usuário coloca descrição de como o produto deve ser achado para o motoboy <br> > Usuário confirma o pedido|
| **Fluxos alternativos** | **Fluxo Alternativo 1 - Fazer pedido:** <br> > Usuário acessa o aplicativo Rappi <br> > Usuário encontra o produto que quer na pagina inicial <br> > Usuário confirma o pedido <br> <br>**Fluxo Alternativo 2 - Fazer pedido com cupom de desconto:** <br>> Usuário acessa o aplicativo Rappi <br> > Usuário realiza todo o procedimento descrito no fluxo principal <br> > Usuário insere cupom de desconto antes de confirmar o pedido <br> <br> |
| **Fluxos de exceção** | **Fluxo de Exceção 1 - Estabelecimento estar fechado:** <br> > Aplicativo apresenta um aviso comunicando que não o estabelecimento não está disponível <br> <br> **Fluxo de Exceção 2 - Erro no método de pagamento :**<br> > Aplicativo apresenta um aviso comunicando que o cartão cadastrado não é válido ou está com problemas <br> <br> |
| **Pós condições** | Usuário pode avaliar o entregador após receber seu pedido|



### **UC03 - Gerenciar entregas**

![Cadastrar entregador](https://i.imgur.com/iGRoa64.png)



| Versão |1.0 29/09/2019 |
| --------------           |:----------- |
| **Autor(es)**            | Lucas Ganda |
| **Descrição**            | Cadastrar um entregador no aplicativo |
| **Ator(es)**             | > Futuro entregador do aplicativo <br> > Aplicativo Rappi |
| **Pré condições**        |  |
| **Fluxo principal**      |> Futuro entregador baixa o aplicativo <br> > Futuro entregador assiste a palestra motivacional <br> > Futuro entregador responde questionário <br> > Futuro entregador já está apto a realizar entregas <br>
| **Fluxos de exceção**    | **Fluxo de Exceção 1 - Entregador ser menor de idade :** <br> > Aplicativo não permite o cadastro de futuros entregadores, caso o indivíduo seja menor de idade <br> <br> **Fluxo de Exceção 2 - Erro na falta de CNH :**<br> > Aplicativo não permite o cadastro de entregadores que entregarão de carro ou moto, se o indivíduo não possuir CNH <br> <br> |
| **Pós condições**        | Entregador já está apto para realizar entregas|

### **UC04 - Gerenciamento de estabelecimento**

![](https://i.imgur.com/I1KXj0z.png)



| Versão |1.1 21/10/2019 |
| -------------- |:----------- |
| **Autor(es)** | André Freitas, João de Assis e Lucas Ganda |
| **Descrição** | Dono de estabelecimento gerencia informações sobre seu estabelecimento na Rappi |
| **Ator(es)** | > Dono do Estabalecimento  <br> > Aplicativo RappiAliados|
| **Pré condições** | > Estar logado no aplicativo  <br> > Possuir um estabelecimento|
| **Fluxo principal** |> Responsável pelo estabelecimento entra no aplicativo <br> > Responsável gerencia estabelecimento e produtos <br> > Responsável altera características de produtos <br> > Produtos tem características como nome, disponibilidade e preço alterados <br>|
| **Fluxos alternativos** | **Fluxo Alternativo 1 - Cadastrar produtos:** <br> > Responsável abre o aplicativo Rappi <br> > Responsável cadastra ou exclui produtos<br> **Fluxo Alternativo 2 - Gerar Promocões** <br> >  Responsável abre a aplicação <br> > Responsável gera promoções e define duração das mesmas|
| **Fluxos de exceção** | **Fluxo de Exceção 1 - Produto não estar cadastrado :** <br> > Aplicativo apresenta um erro comunicando que não é possível colocar um produto inexistente em promoção <br>|
| **Pós condições** | > O produto estará cadastrado no aplicativo|

