##  Projeto web services com Spring Boot e JPA / Hibernate   

Este é um projeto desenvolvido no curso de  Java Completo do Professor Nélio Alves 

:link: Link do curso:  [Udemy-Java-NélioAlves](https://www.udemy.com/course/java-curso-completo/)

##### Modelo de domínio da aplicação

![Modelo de Dominio](https://github.com/MardonioEng/course-springboot-2-java-11/blob/main/modelodedominio.PNG?raw=true)

###### :house: Para rodar esta Rest API local você precisa rodar na sua IDE a classe main() 

` @SpringBootApplication
public class CourseApplication `

##### :arrow_right: Endpoints:

GET

```
http://localhost:8080/users
http://localhost:8080/users/{id}

http://localhost:8080/products
http://localhost:8080/products/{id}

http://localhost:8080/orders
http://localhost:8080/orders/{id}

http://localhost:8080/categories
http://localhost:8080/categories/{id}
```

POST

```
http://localhost:8080/users
```

DELETE

```
http://localhost:8080/users/{id}
```

PUT

```
http://localhost:8080/users/{id}
```



Esta RestAPI esta hospedada no Heroku, você consegue acessar em: https://course-javasb-mardonio.herokuapp.com/
