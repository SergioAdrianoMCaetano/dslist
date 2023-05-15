# dslist
<h1>Aula 01: </h1>

<ul>
	<li>Baixar projeto referência pronto: https://github.com/devsuperior/dslist-backend; </li>

	<li>Criar projeto/lib Maven; </li>

	<li>Arquivos Properties, entidade Game, ORM; </li>

	<li>Seed dos games; </li>

	<li>GameMinDRO, GameRepository, GameService, GameController; </li>
</ul>
<br>

<h2>O que você aprendeu:</h2>

<ul>
<h3>* Conceitos:</h3>
<ul>
	<li>Sistemas web e recursos;</li>
	<li>Cliente/servidor, HTTP, JSON; </li>
	<li>Padrão Rest para API web </li>
</ul>
<h3>* Estruturação de projeto Spring Rest; </h3>

<h3>* Entidades e ORM;</h3>

<h3>* Database seeding; </h3>

<h3>* Padrão camadas;</h3>

<h3>* Controller, service, repository;</h3>

<h3>* Padrão DTO;</h3>
</ul>
<br>

<h1>Aula 02: </h1>

<h2>Relacionamentos:</h2>

<ul>
	<li>Baixar projeto referência pronto: https://github.com/devsuperior/dslist-backend; </li>
	<li>Implementar modelo de domínio;</li>
	<li>Atualizar seed da base de dados;</li>
	<li>GameDTO, busca game por id;</li>
	<li>Busca todas as listas em '/lists';</li>
	<li>Consulta SQL, projection, busca de games por lista;</li>
</ul>

<h2>O que aprendeu:</h2>

<ul>
<h3>* Relacionamento N-N;</h3>

	<li><p>O relacionamento N-N é quando uma entidade de uma tabela pode estar 	associada a várias entidades em outra tabela e vice-versa, representado 	por meio de uma tabela intermediária com as chaves estrangeiras das duas 	tabelas. Esse relacionamento é comum em muitas aplicações, como sistemas 	de gerenciamento de bibliotecas.</li></p>

<h3>* Classe de associação, embedde id:</h3>
	<li><p>Classe de associação e Embeddable são técnicas de modelagem de 			classes em sistemas orientados a objetos. A primeira é usada para 			representar um relacionamento entre duas ou mais entidades do sistema, 			tendo a capacidade de possuir atributos próprios. Já a segunda é uma 			técnica de composição em que uma classe é incorporada como um atributo de 		outra classe, permitindo que o atributo seja tratado como um objeto 			completo, com seus próprios atributos e métodos, mas ao mesmo tempo seja 		parte da classe contenedora e seja armazenado na mesma tabela do banco de 		dados. Ambas as técnicas são importantes na modelagem de sistemas 			complexos e na implementação de lógicas de negócio específicas.</li></p>

<h3>* Consultas SQL no Spring Data JPA;</h3>
	<li><p>Consultas SQL no Spring Data JPA são consultas personalizadas 			escritas em SQL que podem ser executadas usando a interface JpaRepository. 	O Spring Data JPA permite que os desenvolvedores escrevam consultas 			personalizadas em SQL usando a interface JpaRepository. Essas consultas 		podem ser escritas em SQL ou JPQL e permitem mais flexibilidade na 			manipulação de dados em bancos de dados relacionais.</li></p>

<h3>* Projections:</h3>
	<li><p>Projection: é um conceito utilizado em banco de dados para se 			referir à seleção de um subconjunto de colunas de uma tabela em uma 			consulta. A projeção permite que o resultado da consulta seja mais 			eficiente e contenha apenas as informações necessárias.</li></p>
</ul>
