Móveis J.S

Um modelo para o desenvolvimento do Projeto Integrador do Curso de Técnico em Desenvolvimento de Sistemas para a Internet Integrado ao Ensino Médio do IFC - Campus Araquari. (Gerenciamento de vendas para uma loja de móveis.)

https://github.com/Vencce/documento_pi-main.git

Professores: Marco André Mendes e Alann Perini.

Equipe:

    Vinicius Unlauf Ramos (https://github.com/v1nizin)
    Victor Luiz da Silva (https://github.com/VictoorLDS)
    Vitor Ferreira (https://github.com/Vencce)

Links do projeto: (Coloque aqui os links para a documentação do projeto e os repositórios e plubicação do backend e frontend.)

    Documentação (https://github.com/Vencce/documento_pi-main.git)
    Backend: Repositório e Publicação
    FrontendRepositório e Publicação


## 1- Ponto de Vendas (PDV)

**Gerenciamento de vendas para uma loja de móveis**

O nosso cliente Sr. José de Souza, possui uma loja de móveis chamada "Móveis JS" e, devido a um ótimo atendimento de seus clientes, alcançou um crescimento muito rápido na sua empresa, necessitando de mais funcionários para gerir a demanda que só crescia. José agora procura desenvolver um sistema de modo que aumente a praticidade de seus funcionários de gerir a nova demanda, de forma com que haja um controle dos produtos, e relatórios de vendas.  

# Situação Problema: 

A Móveis JS, é uma empresa criada por José de Souza, no ano de 2018. Tem como foco a venda de móveis pré-moldados, tendo como principais características a qualidade dos produtos e o excelente atendimento, sendo possível por meio de tais qualidades um crescimento altissímo no último ano, se fazendo necessário a busca por um sistema.

Atualmente a loja possui 10 funcionários, sendo o dono (José de Souza), um gerente, 3 caixas, e 5 atendentes.

O cliente chega na loja, e analisa as opções de móveis que ele quer com a ajuda de um funcionário disponível.; O funcionário anota os seus produtos escolhidos. Após escolher o produto, o cliente é direcionado ao caixa.

Chegando ao caixa, o cliente diz o seu nome, telefone e endereço. Porém, como é feito de forma manual, não há como ter uma forma segura de ter controle dessas informações. 

Após essa etapa, a(o) atendente solicita pela forma pagamento, podendo ser somente: à vista, débito ou crédito. Com o pagamento realizado, o pedido é encaminhado para o estoque, onde é preparada a entrega.

O pedido é efetuado e devidemente preparado para entrega. Contudo o pedido só é encaminhado para entrega após a efetuação do pagamento, com um tempo limite de 7 dias, Se após esse período não houver a efetuação, o pedido é cancelado. Caso o cliente queira cancelar sua compra, ele deve ir até a loja relatando o motivo para não comprar o produto. 

Após o cumprimento de todos os tópicos anteriores, o pedido é entregue. Havendo algum defeito, o cliente pode entrar em contato com a loja, via número de telefone ou indo até a loja, notificando o problema, e solicitando um novo produto.
 
Após a análise da loja no dia-a-dia foi nítida a falta de um sistema, que auxilie no cadastro dos clientes, e principalmente no pós-venda, sendo utilizado de um forma de trabalho antiquada, se fazendo necessário incrementar formas de contato mais simples, sem ser necessário o cliente se deslocar até a loja ou ligar para solicitar tarefas simples como a troca de produto ou até mesmo a demanda do pedido e sua forma de pagamento. Também é extremamente necessário que o próprio sistema gere os relatórios dos pedidos, sua situação, e notifique quando este é finalizado, fazendo com que o controle por parte do gerente se torne mais fácil.
 
# Descrição da Proposta

Com os problemas apresentados anteriormente, o objetivo dessa proposta é desenvolver um software que melhore o a gestão de clientes, produtos, vendas e estoque.

O foco do sistema será a gestão dos pedidos e clientes, auxiliando de forma prática no cadastro dos clientes e no controle dos pedidos e geração de relatórios. 

O sistema deve cadastrar as informações dos clientes contendo o CPF, telefone, endereço, nome e e-mail para a empresa ter um maior controle das suas vendas e melhorar sua comunicação.

Agora o sistema pode fazer com que o cliente tenha novas formas de pagamento já que as formas de pagamento da empresa estão desatualizadas. As formas de pagamento serão: à vista, débito, crédito (parcelando em até 12x), boleto, pix.

O pedido será efetuado e devidemente preparado para entrega, agora com um prazo de entrega pré-definido de acordo com o produto e sua disponibilidade.

O sistema permitirá cancelar a sua compra pelo site da loja, sem precisar ir até lá pessoalmente. 

Após a efetuação do pedido, este será registrado em um relatório, para que o gerente tenha um controle dos pedidos realizados, e da situação do pedido.

O site terá as telas iniciais com uma breve apresentação dos produtos, a página específica de cada produto, uma página para realizar a compra do produto, uma página para registro do cliente, e para os gerentes, uma página de controle dos pedidos e relatórios.

O sistema terá partes que serão exclusivas dos gerentes, como a parte de geração dos relatórios de pedidos e vendas e todo o controle dos pedidos.

# Regras de Negócio

- **RF001- Cadastro de Clientes**: Para realizar o pedido o cliente deve estar cadastrado no sistema.
- O pedido será separado para entrega conforme disponibilidade no estoque.
- O sistema deve estabelecer um prazo de entrega pré-definido com base no produto e sua disponibilidade.

- **RN002- Formas de Pagamento:** O cliente deve escolher a forma de pagamento no momento da compra. As opções de pagamento disponíveis são: À vista, Débito, Crédito (parcelado em até 12 vezes), Boleto e Pix.

- **RN003- Cancelamento de pedido:** O sistema deve fornecer uma opção de cancelamento de pedido no site da loja. Os clientes têm o direito de cancelar seus pedidos antes da entrega.

- **RN005- Relatórios e Controle de pedidos:** O sistema deve manter um registro de todos os pedidos realizados.

- O relatório de pedidos deve ser atualizado automaticamente após a finalização ou cancelamento de um pedido.
- O relatório poderá ser visto apenas pelo administrador.

- **RF008- Atendimento pós-venda**
O sistema deve fornecer uma forma de registro de problemas ou defeitos relatados pelos clientes após a entrega, permitindo que a loja acompanhe e resolva essas questões de forma adequada.

# Requisitos Funcionais

## Entrada

- **RF001- Cadastro de clientes:** O sistema deve solicitar os dados para o cadastro do cliente. 
  - **Dados necessários:** Nome e e-mail, telefone, CPF, endereço.
  - **Usuários:** Cliente, vendedor.

- **RF002- Inclusão de pedido** O sistema deve permitir o registro dos pedidos feitos pelos clientes, incluindo a lista de produtos escolhidos e suas quantidades.
  - **Dados necessários:** Lista de produto do cliente, valor e quantidade.
  - **Usuários:** Cliente.
 
  - ******  falta o cadastro de produtos*****
   
## Processamento

*** visualizar produtos *****

*** venda ****

- **RF003- Controle de Pagamentos**
O sistema deve possibilitar o registro dos pagamentos realizados pelos clientes, permitindo as formas de pagamento disponíveis (à vista, débito e crédito) e registrando as informações relevantes, como valor pago, data e hora do pagamento.
  - **Dados necessários:** Valor pago, data e hora do pagamento.
  - **Usuários:** Vendedor e Gerente.

- **RF004- Controle de estoque**
O sistema deve manter um registro atualizado do estoque, permitindo a atualização das quantidades disponíveis após a realização de vendas e entregas.
  - **Dados necessários:** Dados das novas vendas e entregas.
  - **Usuários:** Gerente.
 
- **RF005- Controle de entrega**
O sistema deve permitir o estabelecimento de prazos de entrega para os pedidos, possibilitando que a equipe saiba quando cada pedido deve ser entregue aos clientes.
  - **Dados necessários:** Numero do pedido, data, endereco.
  - **Usuários:**  Gerente, vendedor e cliente.

- **RF006- Notificação de pedidos finalizados**
O sistema deve notificar o gerente ou a equipe responsável quando um pedido for finalizado, indicando que está pronto para entrega.
  - **Dados necessários:** pedidos finalizados
  - **Usuários:** Vendedor e gerente.

## Saída

- **RF007- Relatório de Vendas**
O sistema deve ser capaz de gerar relatórios que forneçam informações relevantes sobre os pedidos, incluindo seu status, informações sobre os clientes e outras métricas úteis para o gerenciamento da loja.
  - **Dados necessários:** pedidos, seus status e informações dos clientes.
  - **Usuários:** Gerente.
  - 

  ***Relatório de Produtos****
 --Gerente

# Requisitos Não Funcionais

RNF001 - A senha do usuário deve ter no mínimo 8 caracteres, contendo pelo menos um número,uma letra maiúscula e um caractere especial
   
RNF002 - O sistema deve ser capaz de atuar em diversas plataformas como dispositivos mobile e computadores sem alterações na funcionalidade.
   
RNF003 - O sistema será desenvolvido em front-end em React-Native e Vue.js e o back-end em Django.
   
RNF004 - O sistema deve ser de fácil uso, para utilização de qualquer usuário.

