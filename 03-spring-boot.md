##  **Spring Core (Fundamentals)**

###  Basics

1. What is the Spring Framework?
2. What are the advantages of using Spring?
3. Explain Inversion of Control (IoC) and Dependency Injection (DI).
4. What are the different types of dependency injection?
5. What is a Spring Bean?
6. What are bean scopes in Spring?
7. Explain the life cycle of a Spring Bean.
8. What is the role of the `ApplicationContext`?
9. Difference between `BeanFactory` and `ApplicationContext`.
10. How can you make a class a Spring Bean?

---

###  Annotations & Configuration

11. Difference between `@Component`, `@Service`, `@Repository`, and `@Controller`.
12. What does `@Autowired` do?
13. How does Spring handle circular dependencies?
14. What is `@Qualifier` used for?
15. What is the difference between `@Configuration` and `@Component`?
16. How do you create a custom annotation in Spring?
17. Difference between XML, Annotation, and Java-based configuration.

---

##  **Spring Boot**

###  Fundamentals

18. What is Spring Boot and why is it used?
19. How is Spring Boot different from the traditional Spring framework?
20. What is `application.properties` / `application.yml` used for?
21. What is `@SpringBootApplication`?
22. What are starters in Spring Boot?
23. How does auto-configuration work in Spring Boot?
24. How to disable a specific auto-configuration?
25. What is `CommandLineRunner` and `ApplicationRunner`?
26. How can you change the default server port in Spring Boot?
27. How to profile configurations using `@Profile`?

---

###  Advanced Boot Topics

28. What is Actuator in Spring Boot?
29. How can you secure Actuator endpoints?
30. How do you handle externalized configurations (Config Server, Environment variables)?
31. How can you monitor a Spring Boot application?
32. How to package and deploy a Spring Boot application as a JAR/WAR?
33. What is a `Banner.txt` in Spring Boot?

---

##  **Spring Data JPA**

###  ORM Basics

34. What is Spring Data JPA?
35. How does it simplify database access?
36. What is the difference between `JpaRepository`, `CrudRepository`, and `PagingAndSortingRepository`?
37. What are derived query methods in Spring Data JPA?
38. How does Spring Data generate queries from method names?
39. What is the difference between `findBy`, `getBy`, and `readBy`?
40. How do you use JPQL and native queries?
41. What is `@Query` annotation used for?
42. How do you implement pagination and sorting?
43. How does lazy vs eager fetching work?

---

###  Transactions & Caching

44. What is the purpose of `@Transactional`?
45. What are isolation levels in transactions?
46. What happens if you call a `@Transactional` method from another method in the same class?
47. What is the N+1 problem and how to resolve it?
48. How can you implement caching in Spring Data?

---

##  **Spring Cloud (Microservices & Distributed Systems)**

###  Core Components

49. What is Spring Cloud?
50. What are microservices and how does Spring Cloud help build them?
51. What is service discovery?
52. Explain the role of **Eureka Server** and **Eureka Client**.
53. What is an API Gateway? How does **Spring Cloud Gateway** work?
54. Difference between Netflix Zuul and Spring Cloud Gateway.
55. What is Ribbon?
56. What is Feign Client and how does it simplify REST calls?
57. How can you handle configuration across multiple microservices? (Spring Cloud Config Server)
58. What is Circuit Breaker pattern? How is it implemented using **Resilience4j / Hystrix**?
59. What is Sleuth and Zipkin used for?
60. How does distributed tracing work in Spring Cloud?
61. What are Config Server and Bus used for?
62. How to achieve centralized logging in microservices?

---

##  **Spring Security**

###  Authentication & Authorization

63. What is Spring Security and its main goals?
64. What is the difference between authentication and authorization?
65. How do you secure a REST API using Spring Security?
66. What are filters in Spring Security?
67. What is the difference between `UserDetailsService` and `AuthenticationManager`?
68. How does the security filter chain work?
69. How do you configure role-based access?
70. How to secure endpoints using `@PreAuthorize` and `@Secured`?

---

###  JWT & OAuth2

71. What is JWT (JSON Web Token)? How is it used in Spring Security?
72. How do you validate and refresh JWT tokens?
73. What is OAuth2?
74. Explain the OAuth2 Authorization Code flow.
75. What are access token and refresh token?
76. How can you integrate Spring Boot with Keycloak / Okta / Azure AD?
77. How can you configure custom authentication providers?
78. What is CSRF and how does Spring Security prevent it?

---

##  **Spring REST API**

###  Basics

79. How do you create a REST API using Spring Boot?
80. What are the annotations used for REST controllers? (`@RestController`, `@GetMapping`, etc.)
81. Difference between `@Controller` and `@RestController`.
82. What is the role of `ResponseEntity`?
83. How do you handle exceptions in REST APIs? (`@ControllerAdvice`, `@ExceptionHandler`)
84. How to return custom HTTP status codes?
85. How to handle validation using `@Valid` and `@RequestBody`?
86. What are DTOs and why are they used?
87. What is `@PathVariable` vs `@RequestParam`?
88. How do you consume external REST APIs using `RestTemplate` or `WebClient`?

---

###  Advanced REST Concepts

89. What is HATEOAS in REST?
90. How to implement pagination and filtering in REST APIs?
91. What are idempotent HTTP methods?
92. What is content negotiation?
93. How can you document APIs using **Swagger / OpenAPI**?
94. What are the best practices for versioning REST APIs?
95. How to handle CORS in Spring Boot?
96. How to secure REST APIs using JWT tokens?
97. How can you apply rate limiting in Spring APIs?
98. How to test REST APIs using `MockMvc` and Postman?
99. How to upload and download files via REST endpoints?
100. How to handle global error responses and standardize JSON output?


