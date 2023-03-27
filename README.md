  <p>
    Exam portal Application using Angular & Spring boot! 
  </p>

<!-- About the Project -->
## :star2: About the Project

---------
Exam portal application developed for performing Admin and user role operations with respective user interfaces. Application is implemented in two parts:
1. RESTfull web services: API's build using spring boot are used for handling all the back end operations which includes session management using encrypted JWT Tokens 
2. Front End: User interfaces designed and developed using Angular utilising web services for handling appropriate user actions  

### :dart: Features

* Admin
  * Adding Quiz Categories
  * Updating Quizes
  * Checking User Attempts
* User
  * Registering into System
  * Login into Website
  * Attempting Quiz
  * Checking Quiz Results

* Technologies: 
  * Angular 11
  * Typescript
  * Spring Boot
  * Hibernate with JPA 
  * MySQL
  * JWT Token (Session management)


<!-- TechStack -->
### :space_invader: Tech Stack

<details>
  <summary>Client</summary>
  <ul>
    <li><a href="https://www.typescriptlang.org/">Typescript</a></li>
    <li><a href="https://angular.io/">Angular</a></li>
    <li><a href="https://getbootstrap.com/docs/4.0/getting-started/introduction/">Bootstrap 4</a></li>
  </ul>
</details>

<details>
  <summary>Server</summary>
  <ul>
    <li><a href="https://spring.io/">Spring Boot</a></li>
    <li><a href="https://www.baeldung.com/spring-boot-hibernate">Hibernate with Spring boot</a></li>
  </ul>
</details>

<details>
<summary>Database</summary>
  <ul>
    <li><a href="https://www.mysql.com/">MySQL</a></li>
  </ul>
</details>

<!-- Getting Started -->
## 	:toolbox: Getting Started

<!-- Prerequisites -->
### :bangbang: Prerequisites

- Java 8
- Angular 11.2.11 CLI
- Mysql 5


```bash
 https://github.com/ch-samiksha/ExamPortal.git 
```

### :running: Run Locally

Install necessary packages with npm

```bash
  cd "ExamPortal Front end"
  npm install
```

Start the server

```bash
  ng serve -o
```


<!-- Deployment -->
### :triangular_flag_on_post: Deployment

Run ng build to build the project. The build artifacts will be stored in the dist/ directory. Use the --prod flag for a production build.
