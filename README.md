# TP 8 : Spring @RestController

Application Spring Boot `ms-banque` exposant une API REST construite avec `@RestController` sur une base H2 en mémoire, avec documentation Swagger (springdoc-openapi) et sérialisation des réponses en JSON **et** en XML. Le projet contient l'entité `Compte`, l'énumération `TypeCompte`, le `CompteRepository` JPA, un `CommandLineRunner` qui initialise trois comptes et le `CompteController` (`@RequestMapping("/banque")`) offrant les cinq opérations CRUD.

## 1. Structure du projet, configuration H2 et dépendances

![Structure du projet, properties et pom](screenshots/01-structure-config.png)

## 2. Entité JPA Compte, énumération TypeCompte et dépôt JPA

![Entité, énumération et repository](screenshots/02-entite-repository.png)

## 3. Initialisation des données et contrôleur REST

![Application et CompteController](screenshots/03-application-controller.png)

## 4. Documentation Swagger UI

![Swagger UI](screenshots/04-swagger-ui.png)

## 5. Exécution : endpoints JSON/XML et tests

![Exécution](screenshots/05-execution.png)
