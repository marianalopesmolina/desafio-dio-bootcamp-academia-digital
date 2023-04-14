<p align="center">
  <img width="300px" src="https://user-images.githubusercontent.com/13790608/230697094-3c4f6836-bbcd-42fb-b770-f6698fb4cf7e.png">
</p>

>*Este repositório foi criado para armazenar as soluções dos desafios propostos no Bootcamp Java Developer, uma parceria DIO (Digital Innovation One) com o Banco PAN.*

<h1>Projeto Spring Data JPA na Prática com Java</h1>
<p> Projeto de LAB <strong>Conhecendo o Projeto Spring Data JPA na Prática</strong> oferecido pela plataforma de cursos online <a href="https://dio.me/"><strong> Digital Innovation One</strong></a>.<br>

<h2>🎯 Objetivo do Projeto</h2>
<p>Treinar habilidades de desenvolvimento de software com os principais conceitos de mapeamento objeto relacional (ORM) usando o <strong>Spring Data JPA</strong>. Para isso, uma <strong>API RESTful</strong> será desenvolvida com ênfase na modelagem de suas entidades, no domínio de uma academia de ginástica.</p>


<h2>🛠 Tecnologias Utilizadas</h2>

| - | - | - | - |
|---|---|---|---|
|<img width="30px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg"/>|Java|<img width="30px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/spring/spring-original.svg"/>|Spring Framework|
|<img width="30px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg"/>|GIT|<img width="30px" src="https://user-images.githubusercontent.com/13790608/230699259-29f91eda-dd18-4d7d-8ad3-e5fabd71663b.png"/>|GitHub|
|<img width="30px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg"/>|PostgreSQL|<img width="30px" src="https://user-images.githubusercontent.com/13790608/230749826-89ea1de0-db74-406f-9a25-0b5027627ab7.png"/>|Maven

<ul>
    <li>IDE IntelliJ</li>
    <li>Java 11</li>
    <li><strong>Spring Web</strong></li>
    <li><strong>Spring Data JPA</strong></li>
    <li><strong>Hibernate Validator</strong></li>
    <li>Lombok</li>
    <li>Postman</li>
</ul>


<h2><a href="https://strn.com.br/artigos/2018/12/11/todas-as-anota%C3%A7%C3%B5es-do-jpa-anota%C3%A7%C3%B5es-de-mapeamento/"> Anotações de Mapeamento </a></h2>

<strong>@Entity</strong>
Usada para especificar que a classe anotada atualmente representa um tipo de entidade.

<strong>@Table</strong>
Usada para especificar a tabela principal da entidade atualmente anotada.

<strong>@Id</strong>
Especifica o identificador da entidade. Uma entidade deve sempre ter um atributo identificado.

<strong>@GeneratedValue</strong>
Especifica que o valor do identificador de entidade é gerado automaticamente.

<strong>@Column</strong>
Usada para especificar o mapeamento entre um atributo de entidade básico e a coluna da tabela de banco de dados.

<strong>@JoinColumn</strong>
Usada para especificar a coluna FOREIGN KEY. Indica que a entidade é a responsável pelo relacionamento.

<strong>@OneToMany</strong>
Usada para especificar um relacionamento de banco de dados um-para-muitos.

<strong>@OneToOne</strong>
Usada para especificar um relacionamento de banco de dados um-para-um.

<strong>@ManyToOne</strong>
Usada para especificar um relacionamento de banco de dados muitos-para-um.

<strong>cascade</strong>
Realizar operações em cascata só faz sentido em relacionamentos Pai - Filho.

<strong>mappedBy</strong>
Indica qual é o lado inverso ou não dominante da relação.

<h2>🔗 Links Úteis</h2>
<ul>
    <li><a href="https://start.spring.io/#!type=maven-project&language=java&platformVersion=2.6.1&packaging=jar&jvmVersion=11&groupId=me.dio.academia&artifactId=academia-digital&name=academia-digital&description=Tutorial%20API%20RESTful%20modelando%20sistema%20de%20academia%20de%20gin%C3%A1stica&packageName=me.dio.academia.digital&dependencies=web,data-jpa,postgresql,validation,lombok">Spring Initializr</a></li>
    <li><a href="https://docs.spring.io/spring-boot/docs/2.0.x/reference/html/common-application-properties.html">Common application properties</a></li>
    <li><a href="https://docs.spring.io/spring-data/jpa/docs/current/reference/html/#jpa.repositories">Spring Data JPA - Reference Documentation</a></li>
</ul>
