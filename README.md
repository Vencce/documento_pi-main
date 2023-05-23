## 1- Ponto de Vendas (PDV)

**Gerenciamento de vendas para uma loja de móveis**

O nosso cliente Sr. José de Souza , possuí uma loja de móveis chamada "Móveis JS" e, devido a um ótimo atendimento de seus clientes, alcançou um crescimento muito rápido na sua empresa, necessitando de mais funcionários para gerir a demanda que só crescia. José agora procura desenvolver um sistema de modo que aumente a praticidade de seus funcionários de gerir a nova demanda, de forma com que haja um controle dos produtos,e relatórios de vendas.  

# Situação Problema: 

   A Móveis JS, é uma empresa criada por José de Souza, no ano de 2018, tem como foco a venda de móveis pré-moldados, tendo como principais            características a qualidade dos produtos e o excelente atendimento, sendo possível por meio de tais qualidades um crescimento altissímo no último ano, se fazendo necessário a busca por um sistema.

   Atualmente a loja possui 10 funcionários, sendo o dono (José de Souza), um gerente, 3 caixas, e 5 atendentes.

   O cliente chega na loja, e analisa as opções de móveis que ele quer com a ajuda de um funcionário disponível, o funcionário anota os seus produtos escolhidos, após escolher o produto o cliente é direcionado ao caixa.

   Chegando ao caixa, o cliente diz o seu nome,telefone e endereço, porém como é feito de forma manual não há como ter uma forma eficiente de ter controle dessas informações. 

   Após essa etapa , a (o) atendente solicita pela forma pagamento podendo ser somente: Á vista, Débito e Crédito. Com o pagamento sendo realizado, o pedido é encaminhado para o estoque, onde será preparado a entrega.

   O pedido será efetuado e devidemente preparado para entrega, sem um prazo de entrega pré-definido 

   Contudo o pedido só é encaminhado para entrega após a efetuação do pagamento, com um tempo limite de 7 dias, se após esse período não houver a efetuação, o pedido é retirado da planilha, ou seja cancelado.

   Se caso o cliente querer cancelar sua compra deverá vir até a loja relatando o motivo para não comprar o produto. 

   Após o cumprimento de todos os tópicos anteriores, o pedido é entregue, e se houver algum defeito o cliente poderá entrar em contato com a loja, via número de telefone ou indo até a loja, notificando o problema, e solicitando um novo produto.
    
   Após a análise da loja no dia-a-dia foi nítida a falta de um sistema, que auxilie no cadastro dos clientes, e principalmente no pós-venda, sendo utilizado de um forma de trabalho antiquada, se fazendo necessário incrementar formas de contato mais simples, sem ser necessário o cliente se deslocar até a loja ou ligar para solicitar tarefas simples como a troca de produto ou até mesmo a demanda do pedido e sua forma de pagamento, também é extremamente necessário que o próprio sistema gere os relatórios dos pedidos, sua situação,e notifique quando este é finalizado, fazendo com que o controle por parte do gerente se torne mais fácil.

   
# Descrição da Proposta
 
   Com os problemas apresentados anteriormente, o obejetivo dessa proposta é desenvolver um software em que melhore o controle de informações e pagamento.  
   
   O foco do sistema será na gestão dos pedidos e clientes, auxiliando de forma prática no cadastro dos clientes e no controle dos pedidos e geração de relatórios. 
   
   Os clientes terão que cadastrar suas informações como CPF , Telefone , Endereço , Nome e E-mail para a empresa ter um maior controle das suas vendas e melhorar sua comunicação 
   
   Agora os clientes poderão ter novas formas de pagamento já que as formas de pagamento da empresa estão desatualizadas podendo ser Á vista, Débito, Crédito(Parcelando em até 12x), Boleto, Pix. 

   O pedido será efetuado e devidemente preparado para entrega, agora com um prazo de entrega pré-definido de acordo com o produto e sua disponibilidade.

   O cliente poderá cancelar sua compra pelo site da loja, sem precisar ir até lá pessoalmente. 

   Após a efetuação do pedido, este será registrado em um relatório, para que o gerente tenha um controle dos pedidos realizados, e da situação do pedido; O relatório é atualizado após um novo pedido ou a finalização de outro pedido. 
  
   O site terá as telas iniciais com uma breve apresentação dos produtos, a página específica de cada produto, uma página para realizar a compra do produto, uma página para registro do cliente, e para os gerentes, uma página de controle dos pedidos e relatórios.

   O sistema terá partes que serão exclusiva dos gerentes como a parte de geração dos relatórios e todo o controle dos pedidos.

# Regras de Negócio

   RN001-**Cadastro de clientes:** O cliente deve fornecer as seguintes informações no cadastro: CPF, telefone, endereço, nome e e-mail.

   RN002-**Pedidos:**   
   Para realizar o pedido o cliente deve estar cadastrado no sistema.

   O pedido será será separado para entrega conforme disponibilidade no estoque.

   O sistema deve estabelecer um prazo de entrega pré-definido com base no produto e sua disponibilidade.

   RN003-**Formas de Pagamento:**
   O cliente deve escolher a forma de pagamento no momento da compra.

   As opções de pagamento disponíveis são: À vista, Débito, Crédito (parcelado em até 12 vezes), Boleto e Pix.

   RN004-**Cancelamento de pedido:**
   O sistema deve fornecer uma opção de cancelamento de pedido no site da loja.

   Os clientes têm o direito de cancelar seus pedidos antes da entrega.

   RN005- **Relatórios e Controle de pedidos:**
   O sistema deve manter um registro de todos os pedidos realizados.

   O relatório de pedidos deve ser atualizado automaticamente após a finalização ou cancelamento de um pedido.

   O relatório poderá ser visto apenas pelo administrador.

# Requisitos Funcionais

   RF001- **Cadastro de Clientes**
   
   O Sistema deve realizar o cadastro dos clientes em que o usuario deve informar seus dados.

   RF002- **Gestão dos pedidos**

   O sistema deve permitir o registro dos pedidos feitos pelos clientes, incluindo a lista de produtos escolhidos e suas quantidades.

   RF003- **Controle de Pagamentos**

   O sistema deve possibilitar o registro dos pagamentos realizados pelos clientes, permitindo as formas de pagamento disponíveis (à vista, débito e crédito) e registrando as informações relevantes, como valor pago, data e hora do pagamento.

   RF004-**Controle de estoque**

   O sistema deve manter um registro atualizado do estoque de móveis pré-moldados, permitindo a atualização das quantidades disponíveis após a realização de vendas e entregas.

   RF005-**Gerenciamento de prazos de entrega**

   O sistema deve permitir o estabelecimento de prazos de entrega para os pedidos, possibilitando que a equipe saiba quando cada pedido deve ser entregue aos clientes.

   RF006-**Cancelamento de pedidos**

   O sistema deve permitir o cancelamento de pedidos, tanto por parte dos clientes como por parte da loja, registrando os motivos para o cancelamento.

   RF007-**Notificação de pedidos finalizados**

   O sistema deve notificar o gerente ou a equipe responsável quando um pedido for finalizado, indicando que está pronto para entrega.

   RF008-**Atendimento pós-venda**

   O sistema deve fornecer uma forma de registro de problemas ou defeitos relatados pelos clientes após a entrega, permitindo que a loja acompanhe e resolva essas questões de forma adequada.

   RF009-**Geração de relatórios**

   O sistema deve ser capaz de gerar relatórios que forneçam informações relevantes sobre os pedidos, incluindo seu status, informações sobre os clientes e outras métricas úteis para o gerenciamento da loja.


# Requisitos Não Funcionais

   RNF001 - A senha do usuário deve ter no mínimo 8 caracteres.
   
   RNF002 - O sistema deve ser capaz de atuar em diversos dispositivos sem alterações na funcionalidade
   
   RNF003 - O sistema será desenvolvido em React-Native e Django
   
   RNF004 - O sistema deve ser de fácil uso, para utilização de qualquer usuário.

