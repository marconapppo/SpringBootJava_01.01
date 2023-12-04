# SpringBootJava_01.01
Api de Monitoramento do projeto de Spring Boot Java 01

# Starter
1- Abra o projeto que você quer usar como cliente

2- Em outro projeto qualquer adiciona dependency entre <>

<dependency>
	
	<dependency>
		<groupId>de.codecentric</groupId>
		<artifactId>spring-boot-admin-starter-client</artifactId>
		<version>3.1.8</version>
 	</dependency>
  
</dependency>

3- Adicione como module e mande rodar em outro porta para testa o a app

File > new > Module from...

4- adicionar no projeto cliente em application.properties (porta do monitor):

spring.boot.admin.client.url=http://localhost:8081
