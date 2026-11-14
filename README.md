# Online Food Ordering System

Java 17 + Spring Boot + MySQL REST API project.

## Status
Initial repository setup is in progress. The repository currently contains the Maven build file, Spring Boot entry point, MySQL configuration, and this README. The complete application source has not yet been uploaded.

## Stack
- Java 17
- Spring Boot 3.5.6
- Spring Data JPA
- MySQL
- Maven

## Planned features
- Customer registration with BCrypt password hashing
- Food menu management
- Dine-in and delivery order placement
- Server-side subtotal and 18% tax calculation
- Customer order history

## Run
After the remaining source files are uploaded, configure MySQL credentials using the DB_URL, DB_USERNAME, and DB_PASSWORD environment variables, then run:

```bash
mvn spring-boot:run
```

## Security
Authentication/authorization and admin roles are not yet implemented. Do not deploy publicly or use real customer data until these protections are added.

## Reference
The feature concept was reviewed using the public Fodder project: https://github.com/subClassy/Fodder-OOM_Project. This repository is a separate implementation, not a fork.