
# Kinsfolk Technologies – Technical Consultant Interview (R1)

**Company:** Kinsfolk Technologies, Mumbai  
**Role:** Technical Consultant  
**Round:** R1  
**Date:** 23 November 2026  
**Time:** 3:00 PM – 3:30 PM  
**Mode:** Virtual  
**Duration:** 30 minutes  

## 1. REST APIs and Web Services

1. What types of APIs are you currently working with in your project?
2. Which HTTP methods do you commonly use in REST APIs? Explain their purposes.
3. What is the difference between the HTTP `POST` and `PUT` methods?
4. What authentication methods are commonly used to secure APIs?
5. What is a JWT? Explain its structure and how it is used for API authentication.
6. An API works successfully in Postman and returns `200 OK`, but the same API call from your application in Eclipse throws an `UnknownHostException`. What could be the reason, and how would you troubleshoot it?

## 2. Core Java and OOP

7. Explain the four main principles of Object-Oriented Programming (OOP) with Java examples:
   - Encapsulation
   - Abstraction
   - Inheritance
   - Polymorphism

8. Can a private method be overridden in Java? Explain why or why not.

9. What is the difference between `HashMap` and `Hashtable` in Java?

10. Why is `String` considered an immutable class in Java? What are the benefits of String immutability?

11. Consider the following Java code. What will be the output, and why?

    ```java
    String str = "ABC";
    String str1 = new String("ABC");

    System.out.println(str1 == str);
    ```

    Explain the difference between reference comparison (`==`) and content comparison (`equals()`).

## 3. Java Web – JSP and Servlet

12. Explain how an HTTP request is processed between a JSP page and a Servlet in a Java web application.

13. What is the role of a Servlet in handling an HTTP request and generating a response?

14. How does a JSP page interact with a Servlet? Explain the request-response flow.

## 4. Project and Technical Setup

15. What technology stack and development setup are you currently using in your project?

16. Describe your project's architecture and explain the technologies used on the backend.

## 5. SQL and Database

17. Consider an `Employee` table with the following columns:

    | Column |
    |---|
    | employee_id |
    | employee_name |
    | department_name |

    Write an SQL query to retrieve all employees who belong to the **Computer** department.

18. Consider the following tables:

    **Employee**

    | Column |
    |---|
    | employee_id |
    | employee_name |
    | salary |

    **Department**

    | Column |
    |---|
    | employee_id |
    | department_id |
    | department_name |

    Write an SQL query to retrieve employee details for employees whose salary is greater than `50000` and who belong to the **Computer** department. Join the two tables using `employee_id`.

19. What is the difference between an `INNER JOIN` and a `LEFT JOIN`? Explain with an example.

## 6. Multithreading

20. What is a deadlock in Java? What are the necessary conditions for a deadlock?

21. How can you prevent or avoid deadlocks in a multithreaded application?

---

## Interview Preparation Notes

- The original question mentioned `str2`, but the example defined `str1`. This version uses `str1 == str` so the code is complete and compilable.
- For the JSP/Servlet question, prepare to explain the browser request, Servlet processing, forwarding to JSP, and response back to the browser.
- Review both the concept and a short practical example for Java and SQL questions.
