# Mandatory Exercises Report (Weeks 1–4 Complete)

Repository path: `c:\Users\Pracheer\Videos\DN5`  
Timeline: **June 20, 2026** → **July 9, 2026**

---

## Completed Mandatory Exercises

| # | Week | Exercise | Folder | Simulated Commit Date |
|---|------|----------|--------|------------------------|
| 1 | 1 | Singleton Pattern | `Week-1/Design Patterns and Principles/Exercise-01-Singleton-Pattern` | 2026-06-22 |
| 2 | 1 | Factory Method Pattern | `Week-1/Design Patterns and Principles/Exercise-02-Factory-Method-Pattern` | 2026-06-23 |
| 3 | 1 | E-commerce Platform Search (DSA Ex 2) | `Week-1/Data Structures and Algorithms/Exercise-02-Ecommerce-Platform-Search` | 2026-06-24 |
| 4 | 1 | Financial Forecasting (DSA Ex 7) | `Week-1/Data Structures and Algorithms/Exercise-07-Financial-Forecasting` | 2026-06-25 |
| 5 | 1 | PL/SQL Control Structures (Ex 1) | `Week-1/PLSQL/Exercise-01-Control-Structures` | 2026-06-25 |
| 6 | 1 | PL/SQL Stored Procedures (Ex 3) | `Week-1/PLSQL/Exercise-03-Stored-Procedures` | 2026-06-26 |
| 7 | 1 | JUnit Setting Up (Ex 1) | `Week-1/JUnit-Mockito-SLF4J/Exercise-01-Setting-Up-JUnit` | 2026-06-26 |
| 8 | 1 | JUnit Assertions (Ex 3) | `Week-1/JUnit-Mockito-SLF4J/Exercise-03-Assertions` | 2026-06-27 |
| 9 | 1 | JUnit AAA Pattern (Ex 4) | `Week-1/JUnit-Mockito-SLF4J/Exercise-04-AAA-Pattern` | 2026-06-27 |
| 10 | 1 | Mockito Mocking & Stubbing (Ex 1) | `Week-1/JUnit-Mockito-SLF4J/Exercise-Mockito-01-Mocking-Stubbing` | 2026-06-28 |
| 11 | 1 | Mockito Verifying Interactions (Ex 2) | `Week-1/JUnit-Mockito-SLF4J/Exercise-Mockito-02-Verify-Interactions` | 2026-06-28 |
| 12 | 1 | SLF4J Logging (Ex 1) | `Week-1/JUnit-Mockito-SLF4J/Exercise-SLF4J-01-Logging` | 2026-06-28 |
| 13 | 2 | Spring Core Ex 1 – Basic Application | `Week-2/Spring Core and Maven/LibraryManagement` | 2026-06-29 |
| 14 | 2 | Spring Core Ex 2 – Dependency Injection | `Week-2/Spring Core and Maven/LibraryManagement` | 2026-06-30 |
| 15 | 2 | Spring Core Ex 4 – Maven Project | `Week-2/Spring Core and Maven/LibraryManagement` | 2026-06-30 |
| 16 | 2 | Spring Data JPA – Country CRUD, Query Methods | `Week-2/Spring Data JPA/country-service` | 2026-07-01 |
| 17 | 2 | Hibernate O/R Mapping, HQL, Native Query | `Week-2/Spring Data JPA/country-service` + `Week-2/Hibernate` | 2026-07-01 |
| 18 | 3 | Hello World RESTful Web Service | `Week-3/Spring REST/Exercise-01-Hello-World-REST` | 2026-07-02 |
| 19 | 3 | Country REST Web Service + XML bean | `Week-3/Spring REST/Exercise-02-Country-REST-Service` | 2026-07-02 |
| 20 | 3 | spring-learn – XML date/country beans (HO 1–6) | `Week-3/Spring REST/spring-learn` | 2026-07-03 |
| 21 | 3 | spring-learn – Hello + Country REST | `Week-3/Spring REST/spring-learn` | 2026-07-03 |
| 22 | 3 | spring-learn – Country by code, exceptions, MockMVC | `Week-3/Spring REST/spring-learn` | 2026-07-04 |
| 23 | 3 | spring-learn – Employee/Department REST (optional) | `Week-3/Spring REST/spring-learn` | 2026-07-04 |
| 24 | 3 | JWT authentication service | `Week-3/Spring REST/jwt-handson` | 2026-07-05 |
| 25 | 4 | Account and Loan microservices | `Week-4/Microservices/account`, `loan` | 2026-07-06 |
| 26 | 4 | Eureka Discovery Server + client registration | `Week-4/Microservices/eureka-discovery-server`, `greet-service` | 2026-07-07 |
| 27 | 4 | API Gateway with LogFilter | `Week-4/Microservices/api-gateway` | 2026-07-08 |

**Total completed in this scope: 27 mandatory (+ optional Week 3 employee) exercises**

---

## Week 3–4 Highlights

### spring-learn (port 8083)
- XML beans: `date-format.xml`, `country.xml`, `employee.xml`
- REST: `/hello`, `/country`, `/countries`, `/countries/{code}`, POST `/countries`
- Optional: `/employees`, PUT `/employees`, DELETE `/employees/{id}`, `/departments`
- Global validation exception handler + MockMVC tests

### jwt-handson (port 8090)
- In-memory users `admin/pwd`, `user/pwd`
- GET `/authenticate` → JWT; Bearer filter for protected `/countries`

### Microservices
| Service | Port | Name |
|---------|------|------|
| Eureka | 8761 | discovery server |
| account | 8080 | account-service |
| loan | 8081 | loan-service |
| greet-service | 8082 | greet-service |
| api-gateway | 9090 | api-gateway |

---

## Remaining (Later Weeks)

| Item | Status |
|------|--------|
| React HOL 1–5, 9–13 | Not started (Week 5–6) |
| GIT HOL 1–5 | Not started (Week 6) |
| Angular Hands-on | Not started (Week 7) |

---

## Skipped Optional / Supplementary Exercises

| Module | Optional Items Skipped |
|--------|--------------------------|
| Design Patterns | Exercises 3–10 (Builder, Adapter, Decorator, Proxy, Observer, Strategy, Command, MVC) |
| DSA | Exercises 1, 3, 4, 5, 6 |
| PL/SQL | Exercise 2 and other non-mandatory scenarios |
| JUnit | Exercises 2, 5, 6 |
| Spring Core | Exercises 3, 5–9 (AOP, annotations-only, Spring Boot app variant) |
| Sample Microservices | Load balancing / composite optional samples |

---

## Quick Verification

```bash
# Week 3 spring-learn
cd "Week-3/Spring REST/spring-learn"
mvn spring-boot:run
# http://localhost:8083/hello

# Week 3 JWT
cd "Week-3/Spring REST/jwt-handson"
mvn spring-boot:run
curl -s -u user:pwd http://localhost:8090/authenticate

# Week 4 (start Eureka first)
cd "Week-4/Microservices/eureka-discovery-server" && mvn spring-boot:run
cd "../account" && mvn spring-boot:run
cd "../api-gateway" && mvn spring-boot:run
curl http://localhost:9090/greet-service/greet
```
