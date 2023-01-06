<h1 align="center">General Front-End Questions</h1>

### 1. In HTML, what is the `<meta>` tag used for?
The `<meta>` HTML element represents metadata that cannot be represented by other HTML meta-related elements, like ``<base>``, ``<link>``, ``<script>``, ``<style>`` or ``<title>``.

Machine parsable data about your page

### 2. What is the HTML tag used to declare a JavaScript block?
``<script></script>``

### 3. What is the difference between a runtime error and a compilation error?

A **compile-time** error generally refers to the errors that correspond to the semantics or syntax. A **runtime error** refers to the error that we encounter during the code execution during runtime.

### 4. True or False: The OR operator displays a record if ANY conditions are true. The AND operator displays if ALL of the conditions listed are true.
TRUE

### 5. What is the difference between and Object and an Method?
A Method is an action that an Object is able to perform.

### 6. What is the root element of every SOAP API call, also referred to as the SOAP ____?
``<Envelope>``

### 7. In the below HTML, pleas explain what the ``<iframe>`` tag is doing?
```
<html>
    <body>
        <p>This page rocks!</p>
        <iframe src="https://www.cool.com" height="200" width="300"></iframe>
    </body>
</html>
```

Loading the webpage **cool.com** into 200x300 frame inside the current webpage.

### 8. If an API call was sent asynchronusly what would an "OK" response most likely indicate?
That the call was succussful.

Asynchronous APIs are also known as async APIs. With an asynchronous process, **the availability of a resource, service or data store may not be immediate.** 
The API may have to wait for a backend response. These APIs may provide a callback notification to the requester when the requested resource is ready.

### 9. Which SQL statement is used to return only different values?
DISTINCT

### 10. In JavaScript, what number is used to indicate the first element of an Array?
0

### 11. JavaScript uses the ______ keyword to define variables.
``var``

### 12. What is the correct HTML for referring to an external style sheet?
``<link rel="stylesheet" type="text/css" href="mystyle.css">``

### 13. What is meant when referring to the **scope** of a variable?
A variable is only available from inside the region it is created. This is called scope.

Scope refers to the accessibility of a variable (local, global, function).

### 14. In SQL, what is the difference between an index and view?
* **INDEX** are pointres that maps to the physical address of data. So by using indexes data manipulation becomes faster.
* **VIEW** is a logical table. It is a physical object which stores data logically. View just refers to data that is stored in base tables.

### 15. What does the term Boolean refer to?
``True/False``

### 16. Given the following HTML: ``<img src="welcome.gif" alt="Whoops!"> What is the alt used for?
Alternative text if the image cannot be found.

### 17. If you are declaring that your JavaScript will be Server-Side, what attribute is needed within the ``<script>`` tag?
``runat="server"``

### 18. REST usually uses what type of data format?
JSON

### 19. What is the difference between Server-Side and Client-Side JavaScript?

* **Client-Side JavaScript** is sent from a server and then typically ran in a browser.
* **Server-Side JavaScript** is ran on a server and then results are typically sent to a browser to be viewed. 


So client side scripting runs code like JavaScript on your phone or desktop while server-side scripting runs on the back-end server. That way, it can deliver dynamic content to web pages in response to the client device.

### 20. Why does @variable2 not need quotaton marks around the value?
Var ``@variable1, @variable2 Set @variable1 = 'User Name' Set @variable2 = 3``

### 21. Explain the purpose of a primary key and foreign key in a relational database?
* **Primary key** ensures unique row identification.
* **Foreign key** is a column or a set of columns in a table whose values correspond to the values of the primary key in another table.

### 22. MVC - In the context of a webpage built o mysql and php, what is MVC?

**MVC (Model-View-Controller)** is a pattern in software design commonly used to implement user interfaces, data, and controlling logic. 

### 23. In the below HTML, what does the ``<tr>`` tag represent?
```
<table>
    <tr>
        <th>Firstname</th>
        <th>Lastname</th>
        <th>Age</th>
    </tr>
</table>
```

A **row** in the table

### 24. Using Server-Side Javascript, how would you initalize an Account object named "myAccount"?
Account.Init("myAccount");

### 25. Which SQL operator is used to search for a specified pattern in a field value?
**LIKE**
```
SELECT * FROM Customers
WHERE CustomerName LIKE 'a%';
```

### 26. If you are creating a hyperlink in HTMl, which tag would you use to do so and what is the key element to define the link?
``<a href>``

### 27. Which SQL functions allows you to display a column header in a result set with a different name than the one actually stored in the table?
RENAME

### 28. What is a WSDL?
A machine readable description of how a web service can be interacted with.

**Web Services Description Language (WSDL)** is a standard specification for describing networked, XML-based services.

### 29. Which is the correct HTML tag for the larget heading?
``<h1>``

### 30. What is the below REST API call likely attempting to do?
``POST https://www.somesite.com/somecode``

**POST** data to an endpoint.














