
# Innovya Tech – Java Developer Interview (R1)

**Company:** Innovya Tech  
**Role:** Java Developer  
**Round:** R1  
**Date:** 26 November 2026  
**Time:** 3:00 PM – 3:30 PM  
**Mode:** Virtual  
**Duration:** 30 minutes  

## 1. Introduction and Project Experience

1. Tell me about yourself.
2. Explain your roles and responsibilities in your most recent project.
3. What was the architecture of your recent project?
4. What technologies and frameworks did you use in your project?

## 2. Core Java

5. What is the difference between the `==` operator and the `equals()` method in Java?

6. Do you know how `HashMap` works internally in Java?
   - How are key-value pairs stored in a `HashMap`?
   - What happens when two keys have the same hash code?
   - What is a hash collision?
   - How does `HashMap` handle collisions?

7. What is the `Optional` class in Java?
   - Why was `Optional` introduced?
   - How do you use `Optional` in Java 8?
   - What is the difference between `Optional.of()` and `Optional.ofNullable()`?

8. Why would you use `Optional` instead of returning `null` or throwing an exception?
   - Does `Optional` completely eliminate the need for exceptions?
   - When should you use `Optional`?

## 3. Spring Boot and REST APIs

9. What is the difference between `@RequestParam` and `@PathVariable` in Spring Boot?

10. Why do we use `@PathVariable`? Why can't we always use `@RequestParam`?

11. Can we use `@RequestParam` for filtering data? If yes, when should we use `@RequestParam` instead of `@PathVariable`?

12. What is the difference between using path variables for resource identification and request parameters for filtering or searching?

## 4. Java Coding Questions

### Question 1: Reverse a String

Given the following string:

```java
String str = "mozammil";
```

Write a Java program to reverse the string **without using an extra variable**.

### Question 2: Find Duplicate Elements in an Array

Given an array of integers, return all elements that appear more than once.

```java
int[] nums = {4, 3, 2, 7, 8, 2, 3, 1, 2};
```

**Expected output:**

```text
[2, 3]
```

Write a Java program to find the duplicate elements.

- Do not print duplicate values multiple times.
- Explain the time and space complexity of your solution.
