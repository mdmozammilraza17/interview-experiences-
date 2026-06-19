# Servosys Solutions - Interview Experience

## Company Details

* **Company Name:** Servosys Solutions
* **Mode of Interview:** Virtual
* **Date:** 18/06/2026
* **Time:** 4:00 PM - 4:30 PM

---

# Interview Questions

## Introduction

### 1. Tell me about yourself.

## Java Fundamentals

### 2. What is the difference between `==` and `equals()` in Java?

### 3. How can you implement the `equals()` method safely?

### 4. What is the difference between an interface and an abstract class?

### 5. Can a class implement multiple interfaces? How?

### 6. What are the different Garbage Collection (GC) strategies in Java?

### 7. What is the difference between an Array and a LinkedList?

### 8. What is Binary Search?

### 9. What happens if an array contains duplicate values while performing Binary Search?

## Spring Boot

### 10. What is Dependency Injection?

### 11. How does Dependency Injection improve the testability of a component?

### 12. Explain the SOLID principles.

### 13. Why is the `@SpringBootApplication` annotation usually placed in the root package?

### 14. How can you disable a specific auto-configuration in Spring Boot?

### 15. Why would you want to disable an auto-configuration?

### 16. How do you manage transactions in Spring Boot?

### 17. What is the default rollback behavior of a transaction in Spring?

### 18. How can you roll back a transaction for a checked exception?

## Database

### 19. What is an index in a database?

### 20. In which scenarios can indexes negatively impact performance?

## JWT & Security

### 21. How is a JWT token generated?

### 22. How do you handle JWT token revocation?

### 23. Why are stateless JWTs considered less vulnerable than session-based authentication?

### 24. What is SQL Injection?

### 25. How can you prevent SQL Injection?

---

# SQL Problem

## Question

Count the number of active users who have logged in at least once during the last 30 days.

### Schema

#### Users

```sql
user_id INT,
status VARCHAR(20) -- 'ACTIVE' or 'INACTIVE'
```

#### Logins

```sql
user_id INT,
login_time TIMESTAMP
```

### Solution

```sql
SELECT COUNT(DISTINCT u.user_id) AS active_users
FROM Users u
JOIN Logins l
    ON u.user_id = l.user_id
WHERE u.status = 'ACTIVE'
  AND l.login_time >= CURRENT_DATE - INTERVAL '30' DAY;
```

---

# Interview Summary

### Topics Covered

* Core Java
* OOP Concepts
* Collections
* Garbage Collection
* Spring Boot
* Dependency Injection
* SOLID Principles
* Transaction Management
* Database Indexing
* JWT Authentication
* SQL Injection Prevention
* SQL Query Writing

### Difficulty Level

**Overall:** Intermediate

### Duration

**30 Minutes**
