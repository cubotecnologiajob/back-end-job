<h2>Objetivo</h2>
Criar uma aplicação web que implemente um CRUD de imóveis. Um imóvel é uma casa, apartamento, terreno ou loja com as seguintes características:

<h3>Imóvel:</h3>
O sistema deve permitir o cadastro/edição/exclusão de imóveis com as propriedades (código, tipo, pretensão, título, detalhes, quartos e valor).

<h2>
Critérios de aceitação:
  </h2>

* Todos os atributos são obrigatórios.
* Código não pode se repetir.
* Deve ser possível pesquisar os imóveis por qualquer atributo, exceto pelo id.
* Deve ser possível pesquisar os imóveis por faixa de preço.

<h2>
Interessados:
  </h2>
  
O sistema deve permitir o cadastro/edição/exclusão de interessados com as propriedades (nome, email). Um interessado pode ter um ou mais Interesses com as propriedades (interessado, imóvel).

<h2>
Critérios de aceitação:
</h2>

* Todos os atributos são obrigatórios.
* Email não pode se repetir.
* Deve ser possível pesquisar os interessados por nome, email ou imóvel.
* Não existe cadastro de usuários e/ou autenticação.

<h2>
Requisitos:
 </h2>
 
* A aplicação deve comportar-se como uma REST FULL Api.
* Backend desenvolvido em Laravel 8+
* Processo de desenvolvimento versionado via Git em algum repositório público.
* A aplicação deve possuir um script que popula o banco inicialmente com imóveis, interessados e interesses fictícios para demonstração.

<h2>Critérios de avaliação:</h2>

* Modelagem do banco de dados e das migrations.
* Organização do código: desacoplamento e legibilidade.
* Flexibilidade do sistema para adição/remoção de funcionalidades.

<h2>Como vamos avaliar:</h2>

* Vamos rodar as migrations.
* Vamos subir a aplicação e cadastrar/editar/deletar algumas entidades. Vamos listar os imóveis segundo diferentes combinações de filtros.

<h2>Gostamos de:</h2>

* Arquitetura que favorece a escalabilidade do sistema.
* Ambientes de desenvolvimento em Docker.
* Códigos escritos para humanos.
* Tudo que for desenvolvido não será utilizado comercialmente e a única intenção é de avaliar o conhecimento atual do interessado

<h2>Entrega</h2>

Enviar o link do repositorio para joaomarcusjesus@gmail.com
