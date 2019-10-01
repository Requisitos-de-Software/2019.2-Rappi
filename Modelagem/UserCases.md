> **Autor:** Grupo
>
> **Descrição:** Casos de usúario
>
> **Versão:** 0.1

### **UC01 - Fazer login**

![Casos de Uso](https://i.imgur.com/FPpyALq.jpg)

| Versão                | 1.0 29/09/2019                                                                                                                                                                                                                                                                                                                 |
| --------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Autores**           | André Freitas e João de Assis                                                                                                                                                                                                                                                                                                  |
| **Descrição**         | Fazer Login na Rappi                                                                                                                                                                                                                                                                                                           |
| **Atores**            | > Usuário <br> > Rappi                                                                                                                                                                                                                                                                                                         |
| **Pré condições**     | > Usuário estar deslogado no aplicativo                                                                                                                                                                                                                                                                                        |
| **Fluxo principal**   | > Usuário acessa o aplicativo Rappi <br> > Usuário clica na Bandeira de seu país <br> > Usuário insere seu DDD e seu número de celular <br> > Usuário clica no botão "Receber código" <br> > O número de login é autenticado <br> > O usuário recebe um código de verificação <br> > O código é digitado, e o login é efetuado |
| **Fluxos de exceção** | **Número de login inválido:** <br> > É exibida uma modal que informa que o número é inválido e que o problema pode estar no código do país informado <br>                                                                                                                                                                      |
| **Pós condições**     | Usuário permanece logado e sempre é direcionado para o menu inicial da Rappi                                                                                                                                                                                                                                                   |

                                                                                 |

### **UC02 - Fazer um pedido**

![Fazer um pedido](https://i.imgur.com/6rT3I67.jpg)

| UC02 | Fazer um pedido |
| Versão |1.0 29/09/2019 |
| -------------- |:----------- |
| **Autor(es)** | André Freitas e João de Assis |
| **Descrição** | Realizar um pedido no aplicativo |
| **Ator(es)** | > Usuário do aplicativo <br> > Aplicativo Rappi |
| **Pré condições** | > Estar logado no aplicativo |
| **Fluxo principal** |> Usuário acessa o aplicativo da Rappi <br> > Usuário clica no ícone de Lupa <br> > Usuário pesquisa o nome do estabelecimento desejado <br> > Usuário clica no estabelecimento desejado <br> > Usuário vê o menu <br> > Usuário decide o produto que quer <br> > Usuário coloca descrição de como o produto deve ser achado para o motoboy <br> > Usuário confirma o pedido|
| **Fluxos alternativos** | **Fluxo Alternativo 1 - Fazer pedido:** <br> > Usuário acessa o aplicativo Rappi <br> > Usuário encontra o produto que quer na pagina inicial <br> > Usuário confirma o pedido <br> <br>**Fluxo Alternativo 2 - Fazer pedido com cupom de desconto:** <br>> Usuário acessa o aplicativo Rappi <br> > Usuário realiza todo o procedimento descrito no fluxo principal <br> > Usuário insere cupom de desconto antes de confirmar o pedido <br> <br> |
| **Fluxos de exceção** | **Fluxo de Exceção 1 - Estabelecimento estar fechado:** <br> > Aplicativo aprrsenta um aviso comunicando que não o estabelecimento não está disponível <br> <br> **Fluxo de Exceção 2 - Erro no método de pagamento :**<br> > Aplicativo aprrsenta um aviso comunicando que o cartão cadastrado não é válido ou está com problemas <br> <br> |
| **Pós condições** | Usuário pode avaliar o entregador após receber seu pedido|
