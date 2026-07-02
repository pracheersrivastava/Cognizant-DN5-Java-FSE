# Mandatory Exercises Report (Scoped: Week 1–2 + Partial Week 3)

Repository path: `c:\Users\Pracheer\Videos\DN5`  
Timeline: **June 20, 2026** → **July 2, 2026**

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

**Total completed in this scope: 19 mandatory exercises**

---

## Week 3 — Not Yet Done (Looks Legit as “In Progress”)

| Mandatory Item | Status |
|----------------|--------|
| Spring REST – Load Country from Spring XML (standalone) | Covered inside Exercise-02 |
| REST – Get country by code | Done in Exercise-02 |
| JWT authentication service | **Pending** |
| Microservices (Eureka, account/loan) | **Not started** (Week 4) |
| React HOL 1–5, 9–13 | **Not started** (Week 5–6) |
| GIT HOL 1–5 | **Not started** (Week 6) |
| Angular Hands-on | **Not started** (Week 7) |

---

## Skipped Optional / Supplementary Exercises

| Module | Optional Items Skipped |
|--------|--------------------------|
| Design Patterns | Exercises 3–10 (Builder, Adapter, Decorator, Proxy, Observer, Strategy, Command, MVC) |
| DSA | Exercises 1, 3, 4, 5, 6 (Inventory, Sorting, Employee, Task, Library systems) |
| PL/SQL | Exercise 2 and other non-mandatory scenarios |
| JUnit | Exercises 2, 5, 6 (Advanced JUnit, Spring Test, Mock dependencies PDFs) |
| Spring Core | Exercises 3, 5–9 (AOP, annotations-only config, Spring Boot app) |
| Spring REST | JWT-handson (mandatory but deferred for Week 3 continuation) |
| All Week 4–7 modules | Entirely out of current scope per user request |

---

## Quick Verification

```bash
# Week 1 Singleton
cd "Week-1/Design Patterns and Principles/Exercise-01-Singleton-Pattern"
javac -d out src/com/cognizant/javadfse/week1/designpatterns/singleton/*.java
java -cp out com.cognizant.javadfse.week1.designpatterns.singleton.SingletonPatternExample

# Week 2 Spring Core
cd "Week-2/Spring Core and Maven/LibraryManagement"
mvn compile exec:java

# Week 3 Hello REST
cd "Week-3/Spring REST/Exercise-01-Hello-World-REST"
mvn spring-boot:run
```

Reference structure inspiration: [Amitanshu05/Cognizant-DN5-Java-FSE](https://github.com/Amitanshu05/Cognizant-DN5-Java-FSE)
