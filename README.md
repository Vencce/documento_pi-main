# Projeto Integrador - Modelo

Um modelo para o desenvolvimento do Projeto Integrador do Curso de Técnico em Desenvolvimento de Sistemas para a Internet Integrado ao Ensino Médio do IFC - Campus Araquari.

Professores: [Marco André Mendes](github.com/marcoandre) e [Alann Perini](https://github.com/AlannKPerini).

Links do projeto:

-   [Documentação (esse documento)](github.com/marcoandre/pi-modelo)
-   [Backend](github.com/marcoandre/pi-backend)
-   [Frontend](github.com/marcoandre/pi-frontend)

# Como usar esse modelo para o Projeto Integrador

1. Faça um fork desse repositório para a sua conta do GitHub.
2. Clone o repositório para o seu computador.
3. Abra o arquivo README.md no seu editor de texto favorito (recomendamos o [Visual Studio Code](https://code.visualstudio.com/)).
4. Tenha instalada a extensão [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one) no seu editor de texto.
5. Edite o arquivo README.md com as informações do seu projeto.

# Desenvolvimento

-   As equipes serão avaliadas por cada etapa da documentação e entregas realizadas.
-   Cada equipe deverá escolher um sistema para o desenvolvimento das atividades, a partir dos modelos apresentados.

# Modelos de Sistemas

**Nessa parte a equipe deve escolher um dos modelos de sistemas para desenvolver o projeto. Ao escolher, escreva uma breve descrição do sistema e o motivo da escolha e pode apagar os outros modelos.**

## 1- Ponto de Vendas (PDV)

**Gerenciamento de vendas para uma loja de móveis**

O nosso cliente Sr. José de Souza , possuí uma loja de móveis chamada "Móveis JS" e, devido a um ótimo atendimento de seus clientes, alcançou um crescimento muito rápido na sua empresa, necessitando de mais funcionários para gerir a demanda que só crescia. José agora procura desenvolver um sistema de modo que aumente a praticidade de seus funcionários de gerir a nova demanda, de forma com que haja um controle dos produtos,e relatórios de vendas.  

# Situação Problema

**Nessa parte a equipe deve descrever a situação problema que será resolvida pelo sistema. O texto abaixo descreve o que essa etapa deve conter e pode ser apagado depois.**

![Ciclo da Venda](docs/ciclo_da_venda.webp "Ciclo da Venda")

Descrevem o que acontece atualmente na empresa em um contexto global,
abordando o funcionamento da empresa como um todo, não apenas os “problemas” que lá ocorrem.

Sabendo disso, seu papel é **detalhar o funcionamento da empresa escolhida na
atualidade, ou seja, antes de seu novo software**, usando como base a situação que passamos, mas aprofundando os detalhes de como as coisas acontecem.

-   Pesquise sobre empresas do ramo escolhido
    para entender como funcionam;
-   Aproveite seus conhecimentos previamente adquiridos na área da empresa que escolheu, se houver;
-   Simule uma situação real. Lembre-se que são
    propostas com empresas fictícias, sendo assim,
    você terá que tomar certas decisões sobre como
    a empresa funciona em relação às coisas que
    não estão definidas no documento base (por
    exemplo, no caso da padaria, dizemos que seu
    Genival contratou mais funcionários, mas saber
    quantos e o que fazem pode ser relevante para o software), então tente “visualizar” a
    empresa funcionando, como se você estivesse lá acompanhando o dia-a-dia;

Seguindo essas dicas, você deve ser capaz de descrever o dia-a-dia da empresa selecionada. E para ajudar na organização do texto, indicamos uma abordagem em 3 etapas:

-   **Introdução**: A Móveis JS, é uma empresa criada por José de Souza, no ano de 2018, tem como foco a venda de móveis pré-moldados, tendo como principais características a qualidade dos produtos e o excelente atendimento, sendo possível por meio de tais qualidades um crescimento altissímo no último ano, se fazendo necessário a busca por um sistema.
    Atualmente a loja possui 10 funcionários, sendo o dono (José de Souza), um gerente, 3
    caixas, e 5 atendentes.


    O cliente chega na loja, e analisa as opções de móveis que ele quer com a ajuda de um funcionário disponível, o funcionário anota os seus produtos escolhidos, após     escolher o produto o cliente é direcionado ao caixa.

    Chegando ao caixa, a(o) atendente realiza um cadastro manualmente, contendo: Nome, CPF, E-mail, Telefone, Endereço.

    Após o cadastro, a (o) atendente solicita pela forma pagamento podendo ser: Á vista, Débito, Crédito(Parcelando em até 12x), Boleto, Pix. Com o pagamento sendo realizado, o pedido é encaminhado para o estoque, onde será preparado a entrega.

    O pedido será efetuado e devidemente preparado para entrega, com um prazo de entrega pré-definido de acordo com o produto e sua disponibilidade.

    Após a efetuação do pedido, este será registrado em um relatório, para que o gerente tenha um controle dos pedidos realizados, e da situação do pedido; O relatório é atualizado após um novo pedido ou a finalização de outro pedido. 

    Contudo o pedido só é encaminhado para entrega após a efetuação do pagamento, com um tempo limite de 7 dias, se após esse período não houver a efetuação, o pedido é retirado da planilha, ou seja cancelado.

    Após o cumprimento de todos os tópicos anteriores, o pedido é entregue, e se houver algum defeito o cliente poderá entrar em contato com a loja, via número de telefone ou indo até a loja, notificando o problema, e solicitando um novo produto.
    
    Após a análise da loja no dia-a-dia foi nítida a falta de um sistema, que auxilie no cadastro dos clientes, e principalmente no pós-venda, sendo utilizado de um forma de trabalho antiquada, se fazendo necessário incrementar formas de contato mais simples, sem ser necessário o cliente se deslocar até a loja ou ligar para solicitar tarefas simples como a troca de produto ou até mesmo a demanda do pedido e sua forma de pagamento, também é extremamente necessário que o próprio sistema gere os relatórios dos pedidos, sua situação,e notifique quando este é finalizado, fazendo com que o controle por parte do gerente se torne mais fácil.

   

# Descrição da proposta

Após entender o problema, proponha uma solução que será útil nos aspectos de dificuldade encontrados. Assim, aqui você deverá **explicar de maneira resumida, e preferencialmente mais textual, como o software funcionará**. Pense nesse texto como uma **introdução ao seu cliente** do que você pretende fazer por ele, para que ele confirme se realmente está dentro do
desejado e permita sua continuidade.

**Alguns pontos importantes a se destacar são:**

-   **Qual o foco de ação do software** relacionado com os problemas levantados na análise da situação-problema. O que realmente o software vai fazer. Por exemplo, o foco de ação do Gmail é permitir o envio e recebimento de e-mails.
-   **Os níveis de usuário do sistema**. Somente o gestor tem acesso? E os funcionários? Talvez seja para ambos, ou para funcionários de cargos
    diferentes, etc.
-   **O que poderá ser feito no software**.Apenas o principal, sem pensar em
    telas ou detalhes específicos, pois isso será feito em outro momento.
    -   **Se houver mais de um nível de usuário**, ressaltar as diferenças entre
        eles na descrição da proposta.

Tenha em mente que essa é uma etapa relativamente breve. Não é necessário um texto gigantesco, apenas dar uma noção do funcionamento do sistema. Mais adiante
precisaremos ser bem detalhistas, todavia agora a intenção é apenas fazer algo que permita ao cliente nos dizer se estamos no caminho certo.
