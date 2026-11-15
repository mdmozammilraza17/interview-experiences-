
# 56N Software – Java Developer Interview Questions

## Interview Details

| Detail | Information |
|---|---|
| **Company** | 56N Software |
| **Role** | Java Developer |
| **Interview Type** | Technical Round |
| **Interview Date** | Saturday, 14 November 2026 at 12:00 PM - 1:00 PM |

---

## Section 1: Java & Core Java

**Q1. What is method overriding in Java?**

**Q2. What is a functional interface in Java 8?**

**Q3. What are the important features introduced in Java 8?**

**Q4. Which methods have you used in the Java Stream API?**

**Q5. What is the difference between method overloading and method overriding?**

**Q6. What are filters in the context of Java web frameworks?**

---

## Section 2: Java Object-Oriented Programming – Output-Based Question

**Q7. Consider the following Java classes:**

```java
class A {
    void test() {
        System.out.println("Class A");
    }
}

class B extends A {
    @Override
    void test() {
        System.out.println("Class B");
    }
}
```

Now, consider the following object declarations:

```java
A obj1 = new A();

B obj2 = new B();

A obj3 = new B();

B obj4 = new A();
```

Answer the following questions:

1. Which statements are valid and which are invalid?
2. What will happen if we call `test()` on each object?
3. Which class's `test()` method will be executed?
4. Why is `B obj4 = new A();` an invalid statement?

---

## Section 3: Spring Framework & Transaction Management

**Q8. What is the `@Transactional` annotation in Spring?**

**Q9. How does transaction management work internally in Spring?**

**Q10. What are the ACID properties of a database transaction?**

**Q11. Consider the following service method:**

```java
@Transactional
public void serviceMethod() {

    try {
        // Business logic
        // Something goes wrong here

    } catch (Exception e) {
        logger.error("Error occurred", e);
    }
}
```

If an exception occurs inside the `try` block, will the transaction be committed or rolled back?

**Q12. How does Spring perform transaction rollback?**

**Q13. How can you configure rollback for checked and unchecked exceptions in Spring?**

---

## Section 4: Database & SQL

**Q14. What is a LEFT JOIN in SQL?**

**Q15. Consider the following database tables:**

- `tbl_A` contains 10 records.
- `tbl_B` contains 5 records.
- `tbl_B` has a foreign key referencing `tbl_A`.

Consider the following SQL query:

```sql
SELECT *
FROM tbl_A
LEFT JOIN tbl_B
ON tbl_B.FK_ID = tbl_A.id;
```

How many records can this query return?

Explain the possible scenarios.

---

## Section 5: JPA & Hibernate

**Q16. What is JPA, and what are its advantages?**

**Q17. What is ORM (Object-Relational Mapping)?**

**Q18. What is the difference between Eager Loading and Lazy Loading in JPA/Hibernate?**

**Q19. When creating relationships between entities, which loading strategy would you prefer: Eager or Lazy Loading, and why?**

---

## Section 6: JWT & Authentication

**Q20. What is JWT (JSON Web Token), and how does it work?**

**Q21. How do you manage expiration time in JWT?**

**Q22. What happens when a JWT token expires? How do you handle token expiration in a Spring Boot application?**

---

## Section 7: Database Connection Management

**Q23. What is connection pooling?**

**Q24. What are the advantages of connection pooling?**

---

## Section 8: Data Structures & Coding

**Q25. Find the length of the longest substring without repeating characters.**

**Input:**

```text
abcabcbb
```

**Output:**

```text
3
```

**Explanation:** The longest substring without repeating characters is `abc`, and its length is `3`.

---

**Total Questions: 25**
