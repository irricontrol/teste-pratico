# <strong>Teste Prático - Irricontrol</strong>

Neste repositório você encontra o enunciado para o teste técnico da [Irricontrol](https://irricontrol.com.br/).

## Problema

A empresa IrrigaABC possui sua própria Wiki onde os membros da equipe se dispõe a inserir materiais que irão contribuir com a documentação das regras de negócio da empresa ou itens que acreditam favorecer a equipe ao serem compartilhados.

A organização dos itens a serem cadastrados na Wiki é feita através de um quadro que se localiza na sede da IrrigaABC. Porém, com a chegada de membros que irão trabalhar na modalidade remota este quadro não estará disponível. Além disto, foi observado que alguns post-its se perdiam no quadro, desta forma então ocorriam informações desatualizadas e perdidas.

<img src="https://user-images.githubusercontent.com/94069574/141885560-0e0e5852-ea0d-435e-8b9c-62515622cf1a.png" alt="post-it" width="400"/>

## Solução

Para que o quadro de controle de itens da Wiki seja compartilhado entre todos os membros da equipe IrrigaABC e garantir a integridade dos dados foi sugerido construir uma <strong>plataforma WEB</strong> onde todos os membros da empresa possuíssem acesso e continuem compartilhando os itens da Wiki.

## Esqueleto

A plataforma precisará cadastrar cada item da Wiki com os seguintes campos, onde <strong>Status</strong> e <strong>Setor</strong> contém valores <strong>predefinidos</strong>:

* <strong>Nome</strong>
* <strong>Status</strong>:
    - To Do
    - Doing
    - Done
* <strong>Setor</strong>:
    - adm
    - compras
    - mkt
    - vendas
    - produto
    - software
    - hardware
    - produção
    - pós-vendas

A plataforma deverá ser construída utilizando a linguagem de programação <strong>Python</strong> e framework <strong>Django</strong>.

Apresente os itens cadastrados em uma página utilizando algum framework de Frontend, onde a cada item cadastrado por último no banco de dados seja apresentado no topo desta página.

## Passos

* Crie uma conta Github (caso não tenha alguma) e realize um novo repositório
* Inicie o teste prático e realize <code>commits</code> conforme desenvolve a sua aplicação.
* O teste prático deve ser entregue até o dia 20/11/2021 às 16:00, qualquer entrega após este dia será desconsiderada
* Ao finalizar o teste prático comunique a entrega por [e-mail](mailto:dev@irricontrol.com.br) e informe o link do repositório criado no Github
