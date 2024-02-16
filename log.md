

## Day 64: January 01, 2024

**Today's Progress**: Web Infrastructure design - DNS, HTTPS/HTTP, SPOF, Firewalls

1. **Single Point of Failure (SPOF) in Systems:**
   - Defined SPOF as a non-redundant component that, if dysfunctional, can cause system failure.
   - learned the implications of SPOFs in various systems and the importance of redundancy for high availability.

2. **Eliminating Single Points of Failure:**
   - Outlined steps to identify and eliminate SPOFs, including risk assessments and achieving redundancy.
   - discovered redundancy at the internal component, system, and site levels for robust protection.

3. **HTTP vs. HTTPS:**
   - learned the secure version of HTTP, HTTPS, highlighting its role in encrypting data between browsers and websites.
   - Pointed out the visual indicators in browsers for HTTPS connections.

4. **How HTTPS Works and HTTPS Certificate:**
   - Detailed the use of SSL/TLS protocols in encrypting communications for HTTPS.
   - Explained the role of HTTPS certificates in establishing secure sessions.

5. **Benefits of HTTPS:**
   - Highlighted the encryption of customer information and the trust-building aspects of HTTPS.

6. **History, Types, and Benefits of Firewalls:**
   - Traced the history of firewalls from physical barriers to network security tools.
   - Differentiated between hardware and software firewalls, outlining their purposes and applications.
   - learned the benefits and limitations of firewalls as essential network security measures.

7. **Types of Firewalls:**
    - Covered various firewall types, including packet filtering, proxy, NAT, cloud, stateful inspection, UTM, network segmentation, and next-generation firewalls.

8. **Evolution Beyond Firewalls: Zero Trust and XDR:**
    - Acknowledged the limitations of traditional firewalls.
    - zero trust architectures, microsegmentation, and extended detection and response (XDR) as evolving security paradigms.

9. **Top Next-Generation Firewall Vendors:**
    - key next-gen firewall vendors, including Palo Alto, Check Point, Cisco, Fortinet, Juniper Networks, and Sophos.

10. **Other Firewall Vendors:**
    - Learned additional firewall vendors, offering a diverse range of security solutions.

11. **National Firewalls and the Great Firewall of China:**
    - learned the use of firewalls for content control in nations, focusing on China's Great Firewall.
    - Described techniques such as IP address blocking, DNS cache poisoning, and VPN restrictions employed in the Great Firewall.

12. **Overall Progress:**
    - Covered a wide array of topics, from foundational concepts like DNS and HTTPS to advanced topics like firewalls and network security paradigms.


**link to notes:** [Web Infrastructure](https://github.com/hunterxcobby/WEB-DEV_learning/tree/main/web_infrastructure)



## Day 65: January 02, 2024

**Today's Progress**: Errors and exceptions . Python

1. **Understanding the Problem:**
   - The problem involves handling exceptions in Python, specifically `ZeroDivisionError` and `ValueError`.
   - The goal is to perform integer division of two input values and print the result.
   - If there's a division by zero or if the input values are not valid integers, the script should print the corresponding error code.

2. **Developing a Solution:**
   - Created a function `perform_integer_division` to encapsulate the logic for integer division and exception handling.
   - Utilized a `try-except` block to catch potential exceptions and print the appropriate error code.

3. **Testing the Solution:**
   - Ran the script with various test cases:
     - Valid input values for normal integer division.
     - Division by zero scenario.
     - Invalid input values causing a `ValueError`.
   - Ensured that the script behaves as expected and handles exceptions gracefully.

4. **Refining the Solution:**
   - Reviewed the code to ensure readability and adherence to best practices.
   - Encapsulated the script logic inside functions for modularity.

5. **Documentation:**
   - Added comments to the code to explain the purpose of each section.
   - Included a brief description of the problem at the beginning of the script.

6. **Completion:**
   - The script successfully addresses the problem by performing integer division and handling exceptions appropriately.
   - The code is organized, readable, and includes error codes for better understanding in case of exceptions.


**link to solution:** [Exceptions](https://github.com/hunterxcobby/Python-Challenges/tree/main/01-HackerRank/14-Exceptions)



## Day 66: January 03, 2024

**Today's Progress**: Web Infrastructure design - The Project

1. **Understanding Requirements:**
   - Identified the specific needs and goals of the web infrastructure.
   - Considered factors such as scalability, reliability, security, and performance.
   - learned with stakeholders to gather insights into the expected traffic, user base, and future growth.

2. **Defining Architecture:**
   - Outlined the overall architecture, choosing between monolithic or microservices-based design.
   - Defined components like web servers, application servers, databases, load balancers.
   - Determined the technology stack, considering factors like programming languages, frameworks, and databases.

3. **Scalability:**
   - Designed for horizontal scalability, utilizing load balancing to distribute traffic.
   - Implemented a strategy for handling increased load, such as auto-scaling mechanisms.

4. **High Availability and Reliability:**
   - Ensured high availability by implementing redundancy for critical components.
   - Employed failover mechanisms to handle server or component failures.
   - Considered a multi-region setup for disaster recovery.

5. **Security:**
   - Implemented security best practices, including encryption for data in transit and at rest.
   - Utilized firewalls, intrusion detection systems, and regular security audits.
   - Ensured secure communication between components.

6. **Performance Optimization:**
   - Employed content delivery networks (CDNs) for static content to improve load times.
   - Utilized caching strategies to reduce database load.
   - Optimized database queries and employed indexing for efficient data retrieval.

7. **Monitoring and Logging:**
   - Integrated monitoring tools for real-time performance metrics.
   - Set up logging mechanisms to track and analyze system behavior.
   - Established alerting systems for immediate response to critical issues.

8. **Deployment and Continuous Integration/Continuous Deployment (CI/CD):**
   - Designed a robust CI/CD pipeline for automated testing and deployment.
   - Implemented rolling deployments to minimize downtime during updates.

9. **Documentation:**
   - Documented the architecture, including diagrams, component interactions, and deployment strategies.
   - Created runbooks for operations and maintenance tasks.

10. **Collaboration:**
    - Collaborated with development, operations, and security teams to ensure a holistic approach.
    - Conducted regular reviews and iterations based on feedback and changing requirements.

11. **Future Considerations:**
    - Accounted for future scalability requirements and technological advancements.
    - Planned for periodic architecture reviews and updates.

**link to solution:** [Web Infrastructure Design](https://github.com/hunterxcobby/alx-system_engineering-devops/tree/master/0x09-web_infrastructure_design)



## Day 67: January 04, 2024

**Today's Progress**: Binary Tree, Create, INser @ left && right, Delete - C lang


1. Reviewed and Improved Code:
   - Reviewed and improved C code for inserting a node as the left child in a binary tree.
   - Implemented comments using analogies to explain the logic of the code.
   - Adjusted the formatting style.

2. Code Refinement:
   - Modified the commenting style .
   - Improved comments using analogies for inserting a node as the right child in a binary tree.

3. Code Development:
   - Created a function to display a binary tree in a formatted way.
   - Developed a function to free the memory allocated for a binary tree.

4. Gitignore File:
   - created a Gitignore file pattern to ignore executable and object files in C programs.

5. User Guidance:
   - Explained the logic behind inserting a node as the left and right child in a binary tree to my imaginary students.
   - Clarified the confusion regarding the analogy and code alignment.

6. Bug Fixing:
   - Detected and corrected potential issues in the binary_tree_insert_right function.

7. New Function:
   - Implemented a function (`binary_tree_delete`) to delete an entire binary tree.
   - Developed a function (`binary_tree_is_leaf`) to check if a node is a leaf.
   - Created a function (`binary_tree_is_root`) to check if a given node is a root.


**link to notes:** [Binary Tree](https://github.com/hunterxcobby/DSA/tree/main/0x1D-Binary_trees)


## Day 68: January 05, 2024

**Today's Progress**: Binary Tree, Preorder, Inorder, Postorder Traversal, Full, Complete, Perct Tree - C lang

1. **Code Review and Refinement:**
   - Reviewed and refined the code for checking if a binary tree is full (`binary_tree_is_full`).
   - Made adjustments to adhere to coding standards, focusing on comment clarity and variable naming.

2. **New Function Implementation:**
   - Implemented a function to check if a binary tree is perfect (`binary_tree_is_perfect`).
   - Ensured that the function returns 1 if the tree is perfect and 0 otherwise, following the specified prototype.

3. **Binary Tree Concepts:**
   - learned and learned concepts related to binary trees, including fullness and perfection.
   - Implemented functions to evaluate these properties, deepening understanding of binary tree structures.

4. **Coding Style Compliance:**
   - Ensured that the code aligns with the specified coding style, emphasizing proper indentation, commenting, and function prototypes.

5. **Code Optimization:**
   - Received suggestions for optimizing code, particularly in terms of using more descriptive variable names for enhanced clarity.

6. **Continuous Learning:**
   - Engaged in continuous learning by exploring and implementing new functions, contributing to personal and academic growth in software engineering.
  
**link to implementation:** [Binary Tree](https://github.com/hunterxcobby/DSA/tree/main/0x1D-Binary_trees)


## Day 69: January 06, 2024

**Today's Progress**: AirBnB revision - CRUD, Cmd Module , Python 

1. **Overview:**
   - learned and clarified the user's request for assistance with a CRUD application using the `cmd` module in Python.
   - Developed a simple command-line application for managing users with Create, Read, Update, and Delete (CRUD) functionalities.

2. **Code Implementation:**
   - Created a class named `UserManagement` inheriting from `cmd.Cmd`.
   - Implemented CRUD methods (`do_create`, `do_read`, `do_update`, `do_destroy`) to interact with a dictionary storing user data.
   - Used the `cmd` module to facilitate command-line interactions.

3. **Command Breakdown:**
   - `do_create`: Creates a new user and adds them to the user dictionary.
   - `do_read`: Displays a list of all users in the dictionary.
   - `do_update`: Updates the name of an existing user based on their ID.
   - `do_destroy`: Deletes a user based on their ID.

4. **Initialization and User Feedback:**
   - Implemented an `__init__` method to initialize the user dictionary and superclass.
   - Provided user feedback for each CRUD operation to enhance user interaction.

5. **Code Explanation:**
   - Clarified various lines of code, including class initialization, method signatures, and input parsing.
   - Broke down the functionality of each CRUD method, explaining input validation, dictionary manipulation, and user feedback.

6. **Review and Testing:**
   - Encouraged the user to run the script and test each command for a practical understanding.
   - discovered the importance of the `cmdloop` method for maintaining the command-line interface.

7. **Documentation:**
   - Documented the code with inline comments to enhance readability and understanding.
   - Answered additional questions and provided detailed explanations as per the user's request.

8. **Future Steps:**
   - User can further customize or extend the application based on specific needs.
   - Suggested exploring additional features, error handling, or user interface enhancements.
   - Remained open to any further questions or requests from the user.

Overall, the session focused on creating a functional and educational CRUD application using Python's `cmd` module, tailored to the user's specifications.

**link to implementation:** [AirBnBV2](https://github.com/hunterxcobby/Airbnb_CloneV2)



## Day 70: January 07, 2024

**Today's Progress**: AirBnB revision - uuid module, datetime module, json as file storage type , Python 

1. **Objective:**
   - Integrated JSON serialization and deserialization into the `UserManagement` class.
   - Learned the `uuid` module for generating unique IDs and utilized the `datetime` module for timestamps.

2. **Code Enhancements:**
   - Updated the `do_create` method to use `uuid` for generating unique IDs.
   - Incorporated `datetime` for tracking created at and updated at timestamps in the user data dictionary.

3. **File Handling:**
   - Implemented `save_to_file` and `load_from_file` methods for persisting user data to and loading from a JSON file.
   - Ensured that the user data is saved to the file after creating, updating, or deleting a user.

4. **User Interaction:**
   - Modified the `do_read`, `do_update`, and `do_destroy` methods to accommodate the enhanced user data structure.
   - Displayed user details, including unique IDs and timestamps, during listing, updating, and deleting operations.

5. **Documentation:**
   - Updated inline comments to reflect changes in the code and to provide clarity on new features.
   - Maintained adherence to modular design principles for better code organization.

6. **Testing:**
   - Encouraged running the script and testing CRUD operations to ensure proper functionality.
   - Verified that user data is correctly serialized to and deserialized from the JSON file.

7. **Future Improvements:**
   - learned potential areas for further improvement, such as error handling and additional user features.
   - Remained open to future enhancements and suggestions for refining the user management system.

8. **Conclusion:**
   - Successfully enhanced the `UserManagement` class to include unique IDs and timestamps, improving data integrity and tracking capabilities.
   - The class now offers a more robust and modular solution for managing user data through a command-line interface.

**link to implementation:** [AirBnBV2](https://github.com/hunterxcobby/Airbnb_CloneV2)



## Day 71: January 08, 2024

**Today's Progress**: AirBnB revised with cohort 18- packages && modules, BaseModel, JSON  Serialization and Deserialization, CRUD

1. **Understanding and Implementing cmd Module:**
   - learned and implemented a simple command-line interface using the `cmd` module.
   - Created a basic structure for a user management system with commands like create, read, update, destroy.

2. **Integration of UUID and Time:**
   - Integrated UUID for generating unique identifiers for users.
   - Incorporated timestamps (created_at and updated_at) to track when users are created and updated.

3. **Explained File Organization, Modules, and Packages:**
   - learned the differences between modules and packages.
   - learned file organization strategies for a project.

4. **Explained Absolute and Relative Import Paths:**
   - Clarified the difference between absolute and relative import paths in Python.

5. **Implemented BaseModel and User Class:**
   - Created a `BaseModel` class with common functionalities like `save`, `to_dict`, and `__str__`.
   - Implemented a `User` class inheriting from `BaseModel` with attributes like email, password, etc.

6. **Integration of JSON Serialization and Deserialization:**
   - Integrated JSON serialization and deserialization to save and load instances.
   - Implemented the `save` and `reload` methods to persist and restore instances from a JSON file.

7. **Implemented CRUD Commands in cmd Interface:**
   - Extended the cmd interface to handle CRUD (Create, Read, Update, Delete) operations.
   - Implemented methods to create, read, update, and delete users using a simple console interface.

8. **Testing and Verification:**
   - learned and implemented how to test the functionality of the `create` method and others in the cmd interface.
   - learned interactions and outputs to ensure proper functioning.

9. **Understanding and Discussing Various Code Snippets:**
   - Analyzed and explained code snippets related to datetime, JSON handling, and command-line interfaces.

10. **Explained `to_dict` and `__str__` Methods:**
    - learned the purpose and functionality of the `to_dict` and `__str__` methods in the `BaseModel` class.

11. **Implemented Class for Handling Custom Commands:**
    - Implemented a class (`HBNBCommand`) to handle custom commands like `show`, `all`, `destroy`, and `update` in the cmd interface.

12. **Explanation of Specific Code Sections:**
    - Explained specific code sections, such as the `reload` method and the dynamic creation of instances based on class names.

13. **Introduction to Testing and Verification Strategies:**
    - learned how to test and verify the correctness of implemented functionality, especially focusing on the `create` method.

14. **Incorporated Global Dictionary for Storing Instances:**
    - Used a global dictionary (`__objects`) to store instances, allowing easy access and manipulation in different methods.

15. **Explanation of `__init__` and `do_create` Methods:**
    - Explained the purpose of the `__init__` method in the `User` class and the `do_create` method in the cmd interface.

Throughout the session, we focused on practical implementations, explanations tailored to a beginner's understanding, and testing strategies to ensure the correctness of the implemented features.

**link to implementation:** [AirBnBV2](https://github.com/hunterxcobby/Airbnb_CloneV2)



## Day 72: January 09, 2024

**Today's Progress**: conditionals, data structure, functions, operators, variables, operators precedence

1. **Short-Circuiting in JavaScript:**
   - learned the concept of short-circuiting in JavaScript, understanding how certain operators like logical AND (`&&`), logical OR (`||`), nullish coalescing (`??`), and optional chaining (`?.`) evaluate expressions.

2. **Table of Operators and Precedence:**
   - Examined a table listing JavaScript operators from highest to lowest precedence, including notes on their associativity, individual operators, and usage examples.

3. **Control Flow and Error Handling:**
   - Covered basic control flow statements in JavaScript, particularly the block statement and its scoping effects. learned the use of `var`, `let`, and `const` for scoping.

4. **Conditional Statements:**
   - learned conditional statements in JavaScript, focusing on the `if...else` statement and its best practices. learned the importance of using block statements for better code structure.

5. **Switch Statement:**
   - learned the `switch` statement in JavaScript, explaining how it allows evaluating an expression and matching its value to various case labels. learned the use of `break` statements and provided an example.

6. **User Input Handling:**
   -  modifying code to handle user input by utilizing the `readline` module for a more interactive experience. Resolved issues related to using the `prompt` function and clarified the need for user input.

7. **Exception Handling Statements:**
   - Covered exception handling in JavaScript using the `throw` statement and `try...catch` statements. learned the use of the `finally` block and learned nesting `try...catch` statements.

8. **Utilizing Error Objects:**
   - Studied the utilization of `Error` objects for throwing and catching exceptions. Provided an example of creating and handling custom errors for more informative debugging.

9. **Code Review:**
   - Reviewed and refined code snippets for user input handling and exception handling, ensuring correct syntax and addressing issues related to the `prompt` function.


**link to notes:** [Js learning](https://github.com/hunterxcobby/JS-Lessons/tree/main/basics)



## Day 73: January 10, 2024

**Today's Progress**: Functions, Objects, constructers 

1. Clarified the concept of functions in programming, covering basic syntax, invocation, scope, and parameters.

2. learned functions versus methods, emphasizing their roles and distinctions.

3. learned the concept of objects in programming, explaining how they are a collection of related data and functionality.

4. learned object literals, showcasing their structure and common patterns for creating and accessing properties and methods.

5. Dived into more advanced object concepts, such as objects as object properties and bracket notation for property access.

6. Covered setting object members, including updating values, creating new members, and dynamically setting member names.

7. learned the significance of the "this" keyword in methods and how it refers to the current object.

8. learned constructors as a way to create reusable object blueprints, making it more efficient to create multiple objects with shared properties and methods.

9. discovered the ubiquity of objects in JavaScript, pointing out their use in built-in APIs and objects like String, Array, and Document.

10. Applied the acquired knowledge to complete practical tasks involving objects and their properties, including creating band and cat objects with specific requirements.


**link to notes:** [Js learning](https://github.com/hunterxcobby/JS-Lessons/tree/main/basics)


## Day 74: January 11, 2024

**Today's Progress**: Object, functions and scopes, operators, cmdlines, modules

1. **JavaScript Basics:**
   - learned the importance of JavaScript programming.
   - Covered how to run a JavaScript script.
   - learned the creation of variables and constants.
   - learned the differences between `var`, `const`, and `let`.
   - Covered various data types available in JavaScript.

2. **Control Flow in JavaScript:**
   - learned the use of `if` and `if...else` statements.
   - Covered the use of comments and assigning values to variables.
   - learned the use of `while` and `for` loops, as well as `break` and `continue` statements.

3. **Functions and Scope:**
   - learned what a function is and how to use functions in JavaScript.
   - learned functions that do not use a return statement.
   - learned the scope of variables in JavaScript.

4. **Operators and Data Manipulation:**
   - learned arithmetic operators and how to use them.
   - learned how to manipulate dictionaries in JavaScript.

5. **Modules and Importing Files:**
   - learned how to import a file in JavaScript using ES modules.

6. **Error Resolution:**
   - Addressed and resolved issues related to package installation and script execution.

7. **Command-Line Arguments:**
   - learned scripts that handle command-line arguments using `process.argv`.
   - Explained a script checking for the number and type of command-line arguments.

8. **Additional Queries:**
   - understanding and troubleshooting issues related to Node.js installation and script execution.

9. **Next Steps:**
   - Upcoming topics include more advanced JavaScript concepts, further exploration of ES modules, and addressing specific questions or topics of interest.

**link to notes:** [Js learning](https://github.com/hunterxcobby/JS-Lessons/tree/main/basics)



## Day 75: January 12, 2024

**Today's Progress**: SQLAlchemy, declarative mapping, creating schema, instance of mapped classes, sessions.

1. **SQL Joins:**
   - learned different types of joins in SQL, including inner joins, outer joins (left and right), and cross joins.
   - learned the concept of evaluation order in SQL joins, emphasizing the importance of understanding the sequence of joins in a query.
   
2. **Set Operations on Tables:**
   - Covered set operations in SQL, highlighting that joins are not equivalent to unions and learned union and minus operations on tables.
   - discovered the importance of having identical attributes in sets participating in set operations.

3. **Introduction to SQLAlchemy:**
   - Initiated the exploration of SQLAlchemy, focusing on the Object Relational Mapper (ORM).
   - learned the ORM's method of associating Python classes with database tables and instances of those classes with rows in the tables.
   - learned the SQLAlchemy version check and connecting to an SQLite in-memory database.

4. **Declarative Mapping in SQLAlchemy:**
   - learned how to declare a mapping between Python classes and database tables using the Declarative system in SQLAlchemy.
   - Defined a base class using `declarative_base()` and created a class (`User`) mapped to a table (`users`).
   - learned the importance of having a primary key in the mapped class.

5. **Creating a Schema in SQLAlchemy:**
   - Examined the process of creating a schema in SQLAlchemy, including the creation of table metadata and issuing CREATE TABLE statements using `MetaData.create_all()`.

6. **Creating an Instance of the Mapped Class:**
   - learned the instantiation of objects from a mapped class in SQLAlchemy, understanding the role of the `__init__` method.
   - learned the default values for attributes and how SQLAlchemy instrumentation works.

7. **Creating a Session in SQLAlchemy:**
   - learned the concept of a Session in SQLAlchemy, which serves as a workspace for interacting with the database.
   - learned the creation of a Session class and its association with an Engine.
   - learned the lifecycle patterns of a Session and when to create a new Session.

8. **Adding and Updating Objects in SQLAlchemy:**
   - implemented how to add and update objects in SQLAlchemy, including using `Session.add()` and `Session.add_all()`.
   - learned the concept of a flush and how SQLAlchemy manages the identity map.
   - Showed how to commit changes to the database using `Session.commit()`.

9. **Session Object States in SQLAlchemy:**
   - learned the different object states in SQLAlchemy: transient, pending, and persistent.
   - Highlighted the importance of understanding these states for effective interaction with the database.

10. **Improving Object Representation:**
    - Addressed the need to improve the representation of objects by enhancing the `__repr__` method in the `User` class.

11. **Future Steps:**
    - Considered the need for further exploration, including querying data, handling relationships between tables, and advanced topics in SQLAlchemy.


**link to notes:** [SQL Alchemy](https://github.com/hunterxcobby/DBMS_learning/tree/main/sql_alchemy)



## Day 76: January 13, 2024

**Today's Progress**: Introduction to django


1. Web Frameworks
2. MVT - (Model, Views, Template)
3. Virtual environments
4. Projects Vs Apps
5. HTTP response cycle

   
**link to notes:** [Django](https://github.com/hunterxcobby/WEB-DEV_learning/tree/main/django)



## Day 77: January 14, 2024

**Today's Progress**: Object Relational Mappers

1. Discussed various Python ORM implementations, including SQLAlchemy, Peewee, Django's ORM, Pony ORM, and SQLObject.

2. Highlighted key characteristics of SQLAlchemy, such as its balanced abstraction level and effectiveness in handling complex queries.

3. Introduced Peewee ORM, emphasizing its design philosophy of being "simpler, smaller, and more hackable" compared to SQLAlchemy.

4. Covered Django's ORM, a built-in module in the Django web framework, suitable for simple to medium-complexity database operations. Noted criticisms about its complexity for certain queries.

5. Introduced Pony ORM, an open-source Python ORM released under the Apache 2.0 license, providing an alternative for developers.

6. Mentioned SQLObject as a long-standing ORM with over 14 years of active open-source development, showcasing its stability and reliability.

7. Included Tortoise ORM as an open-source ORM implementation for Python, broadening the options available to developers.


**link to notes:** [ORM](https://github.com/hunterxcobby/Python-Projects/tree/main/lessons/exercises/21-object_relational_mappers)



## Day 78: January 15, 2024

**Today's Progress**: Python MySQL

1. **SQLAlchemy Overview:**
   - Discussed the importance and benefits of using Object-Relational Mappers (ORMs).
   - learned various Python ORM implementations, including SQLAlchemy, Peewee, Django ORM, PonyORM, and SQLObject.

2. **Introduction to MySQL in Python:**
   - Introduced MySQL Python, the MySQL driver for Python, including the _mysql wrapper library and the DB-API 2.0 module MySQLdb.
   - Covered the installation process of MySQLdb.

3. **Connecting to a MySQL Database:**
   - Demonstrated how to establish a connection to a MySQL database using the MySQLdb module.

4. **Getting a Cursor in MySQL Python:**
   - Explained the concept of a cursor and demonstrated how to create a cursor object.

5. **Executing MySQL Queries in Python:**
   - Illustrated the execution of various MySQL queries using the cursor's execute function.

6. **Obtaining Query Results:**
   - Explained methods for fetching query results, including fetching all-at-once and fetching one-at-a-time.

7. **Exceptions & Errors:**
   - Discussed error handling using try-except blocks and demonstrated handling MySQL errors.

8. **Clean Up:**
   - Covered the importance of closing cursors and database connections for proper cleanup.

9. **Parameterized Queries:**
   - Introduced the concept of parameterized queries to prevent SQL injection.
   - Showcased examples of creating and executing parameterized queries.

10. **Using Python Virtual Environment:**
    - Addressed the need for a Python virtual environment and discussed when and why to use one.

11. **Installing SQLAlchemy:**
    - Briefly explained the process of installing the SQLAlchemy library.

12. **Miscellaneous Questions:**
    - Tackled additional questions, including the purpose of the `freeze` command, filtering options in MySQLdb, printing from a table, and using format to create SQL queries.

**link to notes:** [Python MySQL](https://github.com/hunterxcobby/Python-Projects/tree/main/lessons/exercises/22-Python_MYSQL)



## Day 79: January 16, 2024

**Today's Progress**: SQLAlchemy Python && SQL

1. **Mapping and Declaring Classes:**
   - learned the process of declaring classes in SQLAlchemy using the Declarative system.
   - Created a base class and mapped a simple User class to a database table.

2. **Creating a Schema:**
   - Discussed the creation of a schema, including the use of the Declarative system, Table objects, and MetaData.
   - Demonstrated the process of creating tables and specifying column details.

3. **Creating an Instance of the Mapped Class:**
   - learned the process of creating instances of mapped classes.
   - Demonstrated the use of the constructor (`__init__()` method) and how SQLAlchemy's instrumentation works.

4. **Creating a Session:**
   - learned the role of the Session as the ORM's handle to the database.
   - Created a Session class and discussed its lifecycle patterns.
   - learned how to instantiate and configure a Session.

5. **Adding and Updating Objects:**
   - Discussed persisting objects to the database using the Session.
   - learned the process of adding and updating objects, including the use of `add()`, `add_all()`, and `commit()`.

6. **Rolling Back:**
   - learned the ability to roll back changes made within a transaction using `rollback()`.

7. **Querying:**
   - Introduced Query objects and demonstrated basic querying using `query()` and various filtering techniques.
   - Covered the generative nature of Query objects and their use in LIMIT, OFFSET, and ordering.

8. **Common Filter Operators:**
   - learned common filter operators such as `==`, `!=`, `like`, `ilike`, `in_`, `notin_`, `is_`, `isnot`, `and_`, `or_`, and `match`.


**link to notes:** [Python && SQL](https://github.com/hunterxcobby/DBMS_learning)


## Day 80: January 17, 2024

**Today's Progress**: SQLAlchemy Python && SQL

1. **Mock Peer Review for SQL Alchemy Code:**
   - SQL Alchemy code related to common filter operators, provided explanations, and discussed potential improvements.

2. **Code Review for Console Script:**
   - Fixed code for the (`console.py`) related to parsing command-line arguments, addressing syntax warnings, and ensuring proper functionality.

3. **Database Setup Scripts:**
   - Created SQL scripts (`setup_mysql_dev.sql` and `setup_mysql_test.sql`) to set up MySQL databases, users, and privileges for a project.

4. **File Storage Update:**
   - updated the `FileStorage` class in Python related to adding a `delete` method and modifying the `all` method.

5. **User Class Update:**
   - Updated the `User` class in Python, inheriting from `BaseModel` and `Base`, and added or replaced class attributes as per the provided requirements.

These tasks involved code review, SQL script creation, and Python class updates to enhance functionality and align with project specifications.

**link to project:** [AirBnB_v2](https://github.com/hunterxcobby/AirBnB_clone_v2)



## Day 81: January 18, 2024

**Today's Progress**: SQLAlchemy Python && SQL

1. **Syntax Warning Fixes:**
   - Identified and addressed syntax warnings in the `console.py` file, replacing `is` with `==` where appropriate.

2. **Error Handling in tearDown Method:**
   - Updated the `tearDown` method in the test files (`test_base_model.py`) to include specific exception handling instead of using a bare `except` statement.

3. **BaseModel Class Modification:**
   - Modified the `BaseModel` class to properly handle the conversion of `created_at` and `updated_at` attributes from string to datetime objects.

4. **Code Review and Suggestions:**
   - Reviewed your `console.py` code, provided comments, and suggested improvements.
   
5. **Bug Fix in `do_create` Method:**
   - Addressed a bug in the `do_create` method of `console.py` by ensuring proper handling of parameters and their evaluation.

6. **Additional Code Comments:**
   - Added comments to the modified code sections to provide clarity on the changes made.

7. **Review and Suggestions on Overall Progress:**
   - Discussed errors encountered, potential improvements, and provided guidance on debugging and refining the code.

8. **Ongoing Support and Clarifications:**
   - Addressed various specific issues and errors reported by you, offering guidance and assistance.
  
  **link to project:** [AirBnB_v2](https://github.com/hunterxcobby/AirBnB_clone_v2)


  
## Day 82: January 19, 2024

**Today's Progress**: Configuration Management , Puppet


1. **Configuration Management and Automation:**
   - learned the concept of configuration management in the context of server infrastructure.
   - Discussed the role of automation in server configuration management.
   - Introduced popular configuration management tools: Puppet, Ansible, Chef, and Salt.

2. **Benefits of Configuration Management for Servers:**
   - Discussed the benefits, including quick provisioning, recovery, avoiding snowflake servers, version control, and replicated environments.

3. **Overview of Configuration Management Tools:**
   - Discussed common features shared by configuration management tools.
   - Introduced features like Automation Framework, Idempotent Behavior, System Facts, Templating System, and Extensibility.

4. **Choosing a Configuration Management Tool:**
   - Considered factors like infrastructure complexity, learning curve, cost, advanced tooling, and community support when choosing a tool.
   - Provided an overview of Ansible, Puppet, and Chef.

5. **Overview of Popular Tools:**
   - Presented a quick comparison of Ansible, Puppet, and Chef, including their script language, infrastructure model, and terminology.

6. **Puppet Documentation Exploration:**
   - Started exploring Puppet documentation.

7. **Step-by-Step Puppet Tutorial:**
   - Guided through the initial steps of creating a Puppet project.
   - Demonstrated writing a simple manifest to install a package.

8. **Puppet Project: Creating a File:**
   - Created a step-by-step project to use Puppet to create a file with specific permissions, owner, group, and content.

9. **Puppet Project: Installing Flask:**
    - Created a Puppet manifest to install Flask from pip3 with a specific version.

10. **Progress Tracking:**
    - Regularly checked for understanding and provided explanations for each step.
    - Responded to user queries and adjusted the pace based on the user's feedback.

 **link to notes:** [Configuration Management](https://github.com/hunterxcobby/system-devops_learning/tree/main/shell_scripting/0x0A-configuration_management)


## Day 83: January 20, 2024

**Today's Progress**: String Capitalization , Python
 
### Challenge: Capitalize Names

1. **Understand the Problem:**
   - The task is to capitalize the first letter of each word in a given full name.
   - The input is a string containing the full name.

2. **Input Format:**
   - A single line of input containing the full name.

3. **Output Format:**
   - Print the capitalized string.

4. **Approach:**
   - Split the full name into individual words.
   - Capitalize the first letter of each word.
   - Join the capitalized words back into a string.

5. **Pseudocode:**
   ```python
   def capitalize_name(name):
       # Split the name into words
       words = name.split()

       # Capitalize the first letter of each word
       capitalized_words = [word.capitalize() for word in words]

       # Join the capitalized words back into a string
       capitalized_name = ' '.join(capitalized_words)

       return capitalized_name

   # Sample Input
   full_name = "chris alan"

   # Output the capitalized name
   result = capitalize_name(full_name)
   print(result)
   ```

6. **Sample Input and Output:**
   - Sample Input: "chris alan"
   - Expected Output: "Chris Alan"

7. **Test the Function:**
   - Test the function with various inputs, including edge cases.

8. **Optimization:**
   - The provided solution is concise and covers the requirements.
   - No additional optimization is needed for this simple task.

9. **Documentation:**
   - Add comments or docstrings to explain the code.

10. **Finalization:**
    - Ensure the code is readable, well-documented, and provides the correct output.

**link to implementation:** [String Capitalization](https://github.com/hunterxcobby/Python-Challenges/tree/main/01-HackerRank/15-cAPITALIZE)


## Day 84: January 21, 2024

**Today's Progress**: SSH (Secure Shell)

- learned; 

1. the concept of SSH (Secure Shell) as a secure protocol for connecting to Linux servers remotely.

2. how SSH works, emphasizing the client-server model and the use of SSH keys for authentication.

3. the process of generating SSH key pairs on a local machine, including considerations for key length.

4. the use of an SSH agent to avoid typing the passphrase repeatedly and forwarding SSH credentials for server-to-server authentication.

5. changing the default port that the SSH daemon runs on to enhance security.

6. methods of limiting users who can connect through SSH using directives like AllowUsers and AllowGroups.

7. disabling root login through SSH and encouraged the use of a dedicated user account with sudo privileges.

8. scenario where root access is allowed for specific commands, achieved by modifying the root user's authorized_keys file.

9. removing the passphrase from an RSA key.

10. connecting to a server using a private key, emphasizing the use of the `ssh` command with the `-i` option.

**link to notes:** [Secure Shell](https://github.com/hunterxcobby/system-devops_learning/tree/main/shell_scripting/0x0B-ssh/SSH-Essentials)


## Day 85: January 22, 2024

**Today's Progress**: Web Servers, HTTP Requests, Nginx

1. **Setting Up Nginx Server Blocks:**
   - Created directory structure for multiple sites in `/var/www`.
   - Set ownership and permissions for web directories.
   - Created sample pages for each site.

2. **Configuring Nginx Server Blocks:**
   - Created server block files for each domain in `/etc/nginx/sites-available`.
   - Edited server block files to define root directories, server names, and basic configurations.
   - Enabled server blocks by creating symbolic links in `/etc/nginx/sites-enabled`.

3. **Server Configuration and Restart:**
   - Adjusted `server_names_hash_bucket_size` in `/etc/nginx/nginx.conf` to avoid hash bucket memory issues.
   - Tested Nginx configuration with `sudo nginx -t`.
   - Restarted Nginx to apply changes with `sudo systemctl restart nginx`.

4. **Local Hosts File Modification (Optional):**
   - Modified the local computer's hosts file for testing purposes by mapping domain names to the server's IP address.

5. **Introduction to Web Servers and Domain Names:**
   - Discussed the importance of having a domain name for a professional appearance and trust.
   - learned the concepts of internet domain, domain name, root domain, and subdomain.
   - discovered the need to buy a domain name from registrars and configure DNS records.

6. **HTTP Methods Overview:**
   - learned common HTTP methods: GET, HEAD, POST, PUT, DELETE, CONNECT, OPTIONS, TRACE.
   - Provided explanations and real-world analogies for each HTTP method.

7. **Detailed Exploration of HTTP Methods:**
   - learned the details of GET, HEAD, POST, PUT, DELETE, CONNECT, OPTIONS, TRACE methods.
   - Provided examples of HTTP requests and server responses for each method.

8. **Current Discussion: TRACE Method:**
   - learned the TRACE method, highlighting its purpose of echoing back HTTP requests for debugging.
   - read examples of TRACE requests and server responses.


**link to notes:** [Web Server](https://github.com/hunterxcobby/system-devops_learning/tree/main/shell_scripting/0x0C-web_server)



## Day 86: January 23, 2024

**Today's Progress**: HTTP Requests

1. **Understanding Redirects:**
   - Explored the concept of redirects and their importance in web development.
   - Discussed different types of redirects, including 301 (Moved Permanently), 302 (Found or Moved Temporarily), 307 (Moved Temporarily), and Meta Refresh.
   - Insights into when to use each type of redirect based on specific scenarios.

2. **SEO Best Practices in Redirects:**
   - Emphasized the SEO best practices when implementing redirects, with a focus on using 301 redirects for permanent changes.
   - Addressed the impact of redirects on SEO, link equity, and search engine recognition.
   - Explained the complexity of site-wide domain changes and the considerations involved in SEO-friendly domain migration.

3. **Log File Locations:**
   - Responded to a query about the location of Nginx configuration files.
   - Learned common paths for the main Nginx configuration file (`nginx.conf`) on Linux (Ubuntu/Debian and CentOS/RHEL) and Windows systems.


**link to notes:** [Web Server](https://github.com/hunterxcobby/system-devops_learning/tree/main/shell_scripting/0x0C-web_server)



## Day 87: January 24, 2024

**Today's Progress**: Webstack Debugging

1. **HTTP Methods:**
   - Explored various HTTP methods, including GET, POST, PUT, DELETE, CONNECT, OPTIONS, and TRACE.
   - Discussed the purpose and usage of each method in web development.

2. **Redirects:**
   - Explored the concept of redirects in web development.
   - Discussed common HTTP status codes for redirects, including 301 (Moved Permanently) and 302 (Found or Moved Temporarily).
   - Examined other redirect methods like 307 (Moved Temporarily) and Meta Refresh.

3. **SEO Best Practices:**
   - Discussed SEO best practices related to redirects, emphasizing the importance of using 301 redirects for permanent moves.
   - Highlighted the impact of redirects on search engine rankings and trust.

4. **Nginx Configuration:**
   - Explored Nginx configuration files and made adjustments to achieve specific redirection requirements.
   - Addressed issues related to duplicate location directives and the resulting "301 Moved Permanently" responses.

5. **Debugging Apache in Docker Container:**
   - Explored debugging tasks involving Apache running in a Docker container.
   - Investigated and resolved issues preventing the successful display of a "Hello Holberton" page.

6. **Miscellaneous Issues:**
   - Addressed errors related to Apache service start-up, including "apache.service not found" and Apache not starting due to port conflicts.
   - Investigated and resolved issues related to Nginx configuration causing "duplicate location" errors.

7. **File Transfer with SCP:**
   - Provided guidance on using `scp` to securely copy files between machines.

**link to notes:** [Web Server](https://github.com/hunterxcobby/system-devops_learning/tree/main/shell_scripting/0x0C-web_server)



## Day 88: January 25, 2024

**Today's Progress**: Python Network


1. **URL and URI**: Discussed the concepts of Uniform Resource Locator (URL) and Uniform Resource Identifier (URI), including their syntax and components.

2. **"POST" Request Method**: Explored the POST request method in HTTP, its syntax, usage for submitting form data, and differences from the GET method.

3. **File Upload using multipart/form-data POST Request**: Covered file uploads in HTTP using the multipart/form-data POST request, including examples and relevant MIME types.

4. **"CONNECT" Request Method**: Introduced the CONNECT request method in HTTP for establishing proxy connections.

5. **Content Negotiation**: Explained content negotiation in HTTP, including Content-Type negotiation, language negotiation, and encoding negotiation.

6. **Persistent (or Keep-alive) Connections**: Discussed persistent connections in HTTP, their benefits, and relevant Apache server configuration directives.

7. **Range Download**: Briefly touched on the Accept-Ranges and Transfer-Encoding headers for range downloads in HTTP.

8. **Cache Control**: Covered cache control in HTTP, including the Cache-Control and Pragma headers for controlling caching behavior.

9. **HTTP Cookies**: Introduced HTTP cookies, including their purpose, Set-Cookie and Cookie headers, and examples in various server-side applications like PHP, Node.js, Python, and Ruby on Rails.

10. **Lifetime of a Cookie**: Discussed the lifetime of cookies, including permanent cookies and session cookies, along with examples.

11. **Restrict Access to Cookies**: Explored methods to restrict access to cookies using the Secure and HttpOnly attributes, with examples.

12. **Where Cookies are Sent**: Defined the scope of cookies using the Domain and Path attributes, with examples.


**link to notes:** [Python Network](https://github.com/hunterxcobby/Python-Projects/tree/main/lessons/exercises/23-python-network_0/0-HTTP)



## Day 89: January 26, 2024

**Today's Progress**: Python Network 

1. **Introduction to urllib.request**: Explored the `urllib.request` module, which provides a simple interface for fetching URLs.

2. **Fetching URLs**: Discussed the `urlopen` function for fetching URLs and storing responses in temporary locations using `shutil.copyfileobj` and `tempfile.NamedTemporaryFile`.

3. **Understanding HTTP requests and responses**: Explored HTTP requests and responses, mirroring them with `Request` and `Response` objects.

4. **Data Handling**: Covered sending data to URLs using POST requests and encoding data using `urlencode` from `urllib.parse`.

5. **Headers**: Explored adding headers to HTTP requests to mimic browser behavior using the `headers` argument in `urllib.request.Request`.

6. **Handling Exceptions**: Discussed error handling with `URLError` and `HTTPError` exceptions, and how to handle them using `try-except` blocks.

7. **Error Codes**: Reviewed HTTP error codes and their meanings, along with how to handle them in Python.

8. **Wrapping it Up**: Summarized approaches to handle `URLError` and `HTTPError` exceptions.

9. **info and geturl**: Learned about the `info` and `geturl` methods of response objects, providing information about the fetched page and the actual URL.

10. **Openers and Handlers**: Explored customizing URL openers and handlers for handling specific situations like proxies, authentication, and redirects.

11. **Basic Authentication**: Covered handling basic authentication using `HTTPBasicAuthHandler` and password managers.

12. **Proxies**: Discussed working with proxies and disabling proxy detection using `ProxyHandler`.

13. **Sockets and Layers**: Explored the layered architecture of Python's web resource fetching process, including setting socket timeouts.

**link to notes:** [Python Network](https://github.com/hunterxcobby/Python-Projects/tree/main/lessons/exercises/24-python-network_1/0-URLlib)


## Day 90: January 27, 2024

**Today's Progress**: List Challenge on HackerRank, Python

1. **Read Input:**
   - Read the number of commands `n` from input.
   
2. **Initialize List:**
   - Initialize an empty list `lst`.

3. **Parse Commands:**
   - Loop `n` times to read and parse each command.
   - Split each command into words using the `split()` method.
   - The first word of each command indicates the operation to perform.

4. **Perform Operations:**
   - For each command, determine the operation to perform based on the first word.
   - Use conditional statements (`if`, `elif`, `else`) to handle different types of operations:
     - If the operation is 'insert', use `insert()` method to insert the specified element at the specified index.
     - If the operation is 'print', use `print()` method to print the current state of the list.
     - If the operation is 'remove', use `remove()` method to remove the specified element from the list.
     - If the operation is 'append', use `append()` method to append the specified element to the end of the list.
     - If the operation is 'sort', use `sort()` method to sort the list.
     - If the operation is 'pop', use `pop()` method to remove and return the last element of the list.
     - If the operation is 'reverse', use `reverse()` method to reverse the elements of the list.

5. **Handle Errors:**
   - Use `try-except` blocks to handle errors that may occur during list operations.
   - For example, handle `ValueError` when converting input arguments to integers.
   - Print error messages or handle errors gracefully as needed.

6. **Output:**
   - After processing all commands, the final state of the list should be printed as the output.

7. **Test and Debug:**
   - Test the program with sample inputs and edge cases to ensure correctness.
   - Debug any issues or errors encountered during testing.

8. **Optimization (Optional):**
   - Review the code for potential optimizations or improvements in terms of readability, efficiency, or functionality.

**link to solution:** [Lists](https://github.com/hunterxcobby/Python-Challenges/tree/main/01-HackerRank/16-Lists)


## Day 91: January 28, 2024

**Today's Progress**:Django, Python

- Created a django project
- create blog and pages apps
- routed their url to a simple html site

**link to solution:** [Lists](https://github.com/hunterxcobby/WEB-DEV_learning/tree/main/django)


## Day 92: January 29, 2024

**Today's Progress**: Load Balancer, HAProxy

1. **Introduction to HAProxy**:
   - an overview of HAProxy as a TCP/HTTP Load Balancer and proxying solution used to distribute workload across multiple servers.

2. **HAProxy Terminology**:
   - important terms like Access Control List (ACL), backend, and frontend in relation to load balancing.

3. **Types of Load Balancing**:
   - Explored different types of load balancing, including no load balancing, layer 4 load balancing, and layer 7 load balancing, along with their respective configurations.

4. **Load Balancing Algorithms**:
   - commonly used load balancing algorithms in HAProxy, such as roundrobin, leastconn, and source, along with sticky sessions.

5. **Health Check**:
   - Covered HAProxy's health check mechanism to determine the availability of backend servers and how it ensures high availability.

6. **High Availability Setup**:
   - Explored the concept of high availability (HA) setups, which prevent single points of failure, especially in load balancer configurations.

7. **HTTP Headers**:
   - Defined HTTP headers, including request headers, response headers, general headers, and entity headers, and their roles in HTTP communication.

8. **Troubleshooting Nginx and Apache**:
   - diagnosing and resolving issues related to Nginx and Apache web servers, including port conflicts and configuration errors.

9. **Configuring HAProxy**:
   - configuring HAProxy on a server to distribute traffic to multiple backend servers using roundrobin algorithm.

10. **SSH Connection Troubleshooting**:
    - troubleshooting SSH connection issues, including checking for routing problems and specifying custom SSH port numbers.


**link to notes:** [Load Balancers](https://github.com/hunterxcobby/system-devops_learning/tree/main/shell_scripting/0x0F-load_balancer)



## Day 93: January 30, 2024

**Today's Progress**: Python Network

1. **Shell Scripting Tasks:**
    - Successfully implemented Bash scripts to handle tasks involving cURL requests, including sending requests to specific URLs, managing responses, and addressing syntax errors.
    - Identified and resolved issues related to script syntax, parameter passing, and error handling, ensuring the scripts executed as intended.

2. **Python Scripting Tasks:**
    - Completed Python scripting tasks, focusing on sending requests to URLs, processing responses, and utilizing libraries like `urllib` and `requests` for HTTP interactions.
    - Developed Python scripts to interact with the GitHub API, retrieve commit information from repositories, and format the output according to task requirements.

3. **Error Handling and Debugging:**
    - Encountered errors such as HTTP status code errors and invalid JSON responses during scripting tasks, and implemented error handling mechanisms to manage these issues effectively.
    - Debugged scripts to resolve errors and ensure they functioned correctly under different scenarios, improving overall robustness and reliability.

4. **Code Optimization and Efficiency:**
    - Optimized script code to enhance readability, efficiency, and adherence to task specifications, focusing on improving performance and reducing complexity.
    - Implemented strategies to streamline code execution, enhance script performance, and maintain code quality throughout the development process.

5. **Task Completion and Testing:**
    - Successfully completed assigned tasks by writing scripts that met specified requirements and produced expected outputs, ensuring adherence to task instructions.
    - Conducted thorough testing of scripts in designated sandboxes to validate functionality and correctness, making necessary adjustments to achieve desired results.

6. **Documentation and Reporting:**
    - Maintained detailed documentation of progress, solutions, and explanations for each task, ensuring clear understanding of concepts, code implementations, and troubleshooting steps.
    - Documented insights gained from solving various scripting challenges, facilitating learning and knowledge retention for future reference.

**link to :** [Python Network](https://github.com/hunterxcobby/alx-higher_level_programming)


## Day 94: January 31, 2024

**Today's Progress**: Number Guessing Game

1. **Task Definition:**
   - Defined the task to create a number guessing game using `while` loops, `break`, and `continue` statements.
   - Set the goal of allowing users to guess a randomly generated number between 1 and 100.
   
2. **Environment Setup:**
   - Included necessary header files: `<stdio.h>`, `<stdlib.h>`, and `<time.h>`.
   - Created the `number_guessing.c` file in the "Tasks" directory to contain the program.

3. **Random Number Generation:**
   - Used `srand(time(NULL))` to seed the random number generator with the current time for randomness.
   - Generated a random number between 1 and 100 using `rand() % 100 + 1` and stored it as the target number.

4. **Variables Initialization:**
   - Declared variables `userGuess` to store user input and `attempts` to count the number of attempts.

5. **Game Implementation:**
   - Utilized a `while` loop with `while (1)` for an indefinite loop until the correct guess is made.
   - Prompted users to input their guess using `printf`.
   - Checked the validity of user input using `scanf` and handled invalid input by clearing the input buffer and prompting users to enter a numeric value again.
   - Incremented the `attempts` counter for each guess.

6. **Guess Evaluation:**
   - Implemented a check to compare the user's guess with the target number using `if` statements.
   - Provided feedback to users indicating whether their guess was too high or too low using `printf`.
   - Terminated the loop and displayed a congratulatory message when the correct guess was made using `break`.

7. **Code Refinement:**
   - Simplified the feedback message to improve clarity and readability by replacing the ternary operator with an `if-else` statement.

8. **Documentation:**
   - Documented each step and provided clear explanations for beginners to understand.
   - Ensured readability and maintainability by adding comments throughout the code.

9. **Testing:**
   - Conducted testing to ensure the program functions as expected, allowing users to successfully play the number guessing game.
   
10. **Revision and Review:**
    - Reviewed the code to ensure accuracy, readability, and adherence to task requirements.
    - Made necessary revisions to improve clarity and correctness based on feedback and review.

11. **Completion:**
    - Completed the task successfully, meeting all requirements and ensuring the code is beginner-friendly and easy to understand.
   

**link to task:** [Number Guessing Game](https://github.com/hunterxcobby/CWC-Learning/tree/main/c_programming/number_guessing-game)


## Day 95: February 01, 2024

**Today's Progress**: AirBnB_clone-Deploy_static

1. **Fabric Introduction:**
   - Discussed what Fabric is and its role in deployment processes.

2. **Deploying Code to a Server Easily:**
   - Explored the process of deploying code to a server efficiently using Fabric.
   - Discussed the steps involved, including executing Fabric commands locally and remotely, and transferring files with Fabric.

3. **Understanding TGZ Archives:**
   - Defined a TGZ archive and its purpose in software distribution.
   - Explored how TGZ archives are used to package and compress files for easier distribution and deployment.

4. **Executing Fabric Commands Locally:**
   - Discussed how to execute Fabric commands locally using the Fabric library in Python.
   - Explored the steps involved in running Fabric commands on the local machine.

5. **Executing Fabric Commands Remotely:**
   - Explored the process of executing Fabric commands remotely on a target server.
   - Discussed how Fabric simplifies remote command execution and management.

6. **Transferring Files with Fabric:**
   - Explored how to transfer files between the local machine and remote servers using Fabric.
   - Discussed the methods available in Fabric for transferring files efficiently.

7. **Managing Nginx Configuration:**
   - Explored the basics of managing Nginx configuration files.
   - Discussed how to modify Nginx configuration settings for various purposes.

8. **Difference Between `root` and `alias` in Nginx Configuration:**
   - Discussed the differences between the `root` and `alias` directives in Nginx configuration files.
   - Explored how each directive handles file locations based on URI requests.
  
  
**link to notes:** [AirBnB_clone-Deploy_static](https://github.com/hunterxcobby/system-devops_learning/tree/main/shell_scripting/0x03.AirBnB_clone-Deploy_static)



## Day 96: February 02, 2024

**Today's Progress**: HTTPS, SSL

1. **Understanding HTTPS and SSL:**
   - Explained the concepts of HTTPS and SSL in simple terms using real-life analogies.
   - Discussed the purpose and benefits of SSL certificates, including encryption, authentication, trust, and PCI compliance.
   - Explored the disadvantages of SSL, such as cost and performance considerations.

2. **Deployment Tasks:**
   - configuring domain zones and subdomains for load balancing using Bash scripting.
   - Created SSL certificates using Certbot and configured HAproxy to accept encrypted traffic.
   - Troubleshooted errors related to Apache configuration and port usage conflicts.

3. **Programming Concepts:**
   - Discussed the Feynman learning technique and applied it to explain programming concepts in step-by-step and analogy-based approaches.
   - Clarified concepts related to round-robin DNS, HTTP, and HTTPS.

4. **Hands-on Practice:**
   - Engaged in practical exercises to apply theoretical knowledge, such as configuring domain zones, generating SSL certificates, and troubleshooting deployment issues.
   - Provided guidance on using commands, editing configuration files, and resolving errors in a Linux environment.


**link to notes:** [HTTPS & SSL](https://github.com/hunterxcobby/system-devops_learning/tree/main/shell_scripting/0x10-HTTPS_SSL)



## Day 97: February 03, 2024

**Today's Progress**: HTTPS, SSL / SSL termination

1. **Initial Setup and Certificate Generation:**
   - Explored the process of setting up Certbot for certificate generation.
   - Generated SSL/TLS certificates for the domain "www.hunterxcobby.tech" using Certbot.

2. **HAProxy Configuration for SSL/TLS Termination:**
   - Reviewed the HAProxy configuration for SSL/TLS termination.
   - Updated the HAProxy configuration file (`haproxy.cfg`) to include SSL/TLS termination.
   - Explored options for binding SSL certificate files (`fullchain.pem` and `privkey.pem`) to the HAProxy configuration.
   - Modified the HAProxy configuration to bind the SSL certificate and private key files.

3. **Troubleshooting and Error Handling:**
   - Addressed errors encountered during HAProxy configuration, such as incorrect file paths and SSL certificate loading issues.
   - Provided guidance on locating SSL certificate files and understanding their contents.

4. **Final Configuration:**
   - Updated the HAProxy configuration to correctly bind the SSL certificate (`fullchain.pem`) and private key (`privkey.pem`).
   - Ensured that the HAProxy configuration is correctly set up for SSL/TLS termination on port 443.

5. **Summary and Next Steps:**
   - Reviewed the steps taken to configure HAProxy for SSL/TLS termination.
   - Provided guidance on next steps for managing SSL/TLS certificates and renewals using Certbot.

**link to project:** [HTTPS & SSL task](https://github.com/hunterxcobby/alx-system_engineering-devops/tree/master/0x10-https_ssl)


## Day 98: February 04, 2024

**Today's Progress**:  AirBnB clone - Deploy static

1. **SSL Certificate Configuration**:
   - We reviewed how to configure SSL certificates in HAProxy.
   - Discussed different configurations for binding SSL certificates, including paths and file formats.

2. **Troubleshooting SSL Errors**:
   - Addressed various errors encountered during SSL certificate configuration in HAProxy.
   - Analyzed error messages and suggested potential solutions.

3. **Fabric Script for Deployment**:
   - Discussed requirements for a Fabric script to deploy archives to web servers.
   - Outlined steps for creating the `do_deploy` function according to the provided specifications.

4. **Fabric Script Development**:
   - Developed a pseudocode representation of the `do_deploy` function.
   - Included steps to check archive existence, upload, uncompress, and manage symbolic links.

5. **Testing and Verification**:
   - Provided a command to test the Fabric script for deployment.
   - Emphasized the importance of verifying the deployment's success after running the script.

(**link to notes:** [AirBnB_clone-Deploy_static](https://github.com/hunterxcobby/AirBnB_clone_v2/)



## Day 99: February 05, 2024

**Today's Progress**:  Search Alogrithms

1. **Space Complexity**:
   - Discussed the concept of space complexity, distinguishing between auxiliary space and space complexity.
   - Explained space complexity using real-life analogies and examples, such as moving into an apartment and sorting algorithms' space requirements.
   - Reviewed example codes in C and Python to illustrate space complexity in recursive and non-recursive functions.

2. **Search Algorithms**:
   - Defined search algorithms as methods used to locate specific items within a collection of data.
   - Explained linear search as a simple search algorithm that sequentially checks each element in a dataset until a match is found.
   - Illustrated linear search with real-life analogies and provided example code in C.
   - Introduced binary search as an efficient search algorithm for sorted datasets, dividing the search interval in half with each iteration.
   - Discussed when to use linear search versus binary search based on the characteristics of the dataset and the efficiency requirements.
   - Provided example code in C for binary search and explained its implementation.

3. **Best Search Algorithms for Different Scenarios**:
   - Analyzed various search algorithms (linear search, binary search, hash table, interpolation search, exponential search, jump search) based on their suitability for different scenarios.
   - Discussed factors influencing the choice of the best search algorithm, including dataset size, sorting status, frequency of searches, and available resources.
   - Highlighted the importance of understanding trade-offs between time complexity, space complexity, and implementation complexity when selecting the appropriate search algorithm.


**link to notes:** [Search Algorithms](https://github.com/hunterxcobby/C-Projects/tree/master/lessons/solutions/0x1E-search_algorithms)



## Day 100: February 06, 2024

**Today's Progress**:  Django assignment && Importation Website

1. **Set Up Django Project**:
   - Discussed the task of setting up a Django project named "BlogAPI" and configuring necessary project settings.

2. **Create Models**:
   - Designed Django models for blog posts and comments, outlining their fields and purpose.

3. **Create Serializer Classes**:
   - Discussed the creation of serializer classes using Django REST Framework to serialize/deserialize data between Django models and JSON format for API endpoints.

4. **Create Views**:
   - Implemented views for endpoints such as retrieving a list of blog posts, retrieving a specific blog post by ID, adding a new blog post, editing an existing blog post, and deleting a blog post.

5. **Define URL Patterns**:
   - Outlined the process of mapping each view to a URL pattern in the Django project's URL configuration.

6. **Test Endpoints**:
   - Discussed testing endpoints using tools like Postman or curl to ensure they function as expected.

7. **Resolve Import Error with rest_framework**:
   - Provided steps to resolve import errors with `rest_framework`, including installing Django REST Framework, checking installed packages, ensuring correct Django settings, and rebuilding environment if using Docker.

**link to TASK:** [Django assignment](https://github.com/hunterxcobby/WEB-DEV_learning/tree/main/django-2)


## Day 38: February 07, 2024

**Today's Progress**:  Introduction to HTML

1. ** HTML Code Crectionor**:
   - correcting HTML code by identifying errors.

2. **Learned HTML Concepts**:
   - the `<figure>` element and its usage in HTML.
   - the purpose and usage of the `alt` attribute in HTML images.
   - HTML elements and attributes, highlighting their differences.

3. **HTML Form Implementation**:
   - addition of an `action` attribute to a `<form>` element in HTML.
   - the significance of the `action` attribute in specifying the destination of form data.

4. **Input Elements**:
   - the purpose and usage of the `<input>` element in HTML forms.
   - nesting an `<input>` element within a `<form>` element.

5. **Name Attribute in HTML**:
   - the purpose and usage of the `name` attribute in HTML input elements.
   - the role of the `name` attribute in uniquely identifying input fields within a form.


**link to TASK:**[Introduction to HTML](https://github.com/hunterxcobby/100-days-FreeCodeCamp/blob/main/projects/catphoto.html)


## Day 39: February 08, 2024

**Today's Progress**: Arbnb clone review && Cat App Challenge on FreeCodeCamp

1. **Refactoring**: identified areas for improvement in the AirBnB Clone. These changes included adding error handling in the `__init__` method, modularizing the `to_dict` method, adding unit tests, updating comments, and refactoring code organization.

2. **Implemented Changes**: Implemented changes in the code to improve its readability, maintainability, and reliability while maintaining its functionality and purpose. This included adding error handling using a `try-except` block, modularizing the `to_dict` method by introducing a helper function `_format_datetime`, updating comments, and organizing imports according to PEP 8 guidelines.

3. **Review and Finalization**: Reviewed the updated code to ensure that all changes were successfully implemented and met the requirements outlined in the task.

4. **HTML Concepts**:
   - Learned the purpose and usage of HTML elements such as `<input>`, `<fieldset>`, `<legend>`, and `<label>`.
   - Clarified the semantic meaning and practical application of these elements in creating accessible and user-friendly web forms.

5. **Form Elements and Attributes**:
   - creation of various form elements such as radio buttons and checkboxes.
   - learned the importance of attributes such as `name`, `value`, `id`, `for`, and `charset` in defining form behavior, associating labels with form elements, and specifying character encoding.

6. **Browser Behavior**:
   - learned how self-closing `<meta>` elements in the `<head>` section of an HTML document can control browser behavior and specify character encoding, with an example of setting the `charset` attribute to UTF-8.

**link to progress:**[Catapp challenge](https://github.com/hunterxcobby/100-days-FreeCodeCamp/tree/main/projects/Day_2)


## Day 40: February 09, 2024

**Today's Progress**: Coffee Shop , Introduction to CSS

1. **Introduction to CSS**:
   - **CSS (Cascading Style Sheets)**: Introduced the purpose of CSS as a styling language used to control the presentation and layout of HTML documents.
   - **Separation of Concerns**: Discussed the concept of separating content (HTML) from presentation (CSS) to enhance maintainability and flexibility in web development.

2. **CSS Selectors and Properties**:
   - **Selectors**: Explained how CSS selectors target HTML elements for styling, with examples such as element selectors, class selectors (e.g., `.class`), and ID selectors (e.g., `#id`).
   - **Properties**: Introduced key CSS properties like `color`, `font-size`, `margin`, `padding`, and `background-color` to control various aspects of element styling.

3. **Box Model**:
   - **Box Model Concept**: Introduced the CSS Box Model, which represents how elements are rendered as boxes with content, padding, borders, and margins.
   - **Box Model Properties**: Discussed how to control the box model using properties like `width`, `height`, `padding`, `border`, and `margin`.

4. **Layout and Positioning**:
   - **Layout Concepts**: Briefly touched on layout concepts such as block-level and inline elements, and how elements can be displayed as `block`, `inline`, `inline-block`, or `flex`.
   - **Positioning**: Introduced the `position` property for positioning elements, including values like `relative`, `absolute`, and `fixed`.

5. **Responsive Design**:
   - **Viewport Meta Tag**: Discussed using the `viewport` meta tag to control the layout and scaling of web pages on different devices.

6. **Styling Specific Elements**:
   - **ID Selector**: Demonstrated using the `id` selector to target specific elements and apply styles, such as setting the width of an element with `#menu`.


**link to progress:**[Coffee Shop ](https://github.com/hunterxcobby/100-days-FreeCodeCamp/tree/main/projects/Day_3)


## Day 41: February 10, 2024

**Today's Progress**: Coffee Shop , Introduction to CSS

1. **Introduction to CSS**:
   - **CSS (Cascading Style Sheets)**: Introduced the purpose of CSS as a styling language used to control the presentation and layout of HTML documents.
   - **Separation of Concerns**: Discussed the concept of separating content (HTML) from presentation (CSS) to enhance maintainability and flexibility in web development.

2. **CSS Selectors and Properties**:
   - **Selectors**: Explained how CSS selectors target HTML elements for styling, with examples such as element selectors, class selectors (e.g., `.class`), and ID selectors (e.g., `#id`).
   - **Properties**: Introduced key CSS properties like `color`, `font-size`, `margin`, `padding`, and `background-color` to control various aspects of element styling.

3. **Box Model**:
   - **Box Model Concept**: Introduced the CSS Box Model, which represents how elements are rendered as boxes with content, padding, borders, and margins.
   - **Box Model Properties**: Discussed how to control the box model using properties like `width`, `height`, `padding`, `border`, and `margin`.

4. **Layout and Positioning**:
   - **Layout Concepts**: Briefly touched on layout concepts such as block-level and inline elements, and how elements can be displayed as `block`, `inline`, `inline-block`, or `flex`.
   - **Positioning**: Introduced the `position` property for positioning elements, including values like `relative`, `absolute`, and `fixed`.

5. **Responsive Design**:
   - **Viewport Meta Tag**: Discussed using the `viewport` meta tag to control the layout and scaling of web pages on different devices.

6. **Styling Specific Elements**:
   - **ID Selector**: Demonstrated using the `id` selector to target specific elements and apply styles, such as setting the width of an element with `#menu`.


**link to progress:**[Coffee Shop ](https://github.com/hunterxcobby/100-days-FreeCodeCamp/tree/main/projects/Day_4)


## Day 42: February 11, 2024

**Today's Progress**: Color Markers, CSS

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Colored Markers</title>
    <link rel="stylesheet" href="styles.css">
  </head>
  <body>
    <h1>CSS Color Markers</h1>
    <div class="container">
      <div class="marker">
        </div>
    </div>
  </body>
</html>
```

**link to progress:**[Color Markers ](https://github.com/hunterxcobby/100-days-FreeCodeCamp/tree/main/projects/Day_5)


## Day 43: February 12, 2024

**Today's Progress**: CSS Color Markers 

1. **CSS Styling**:
   - Explored various CSS styling techniques such as setting colors, fonts, margins, padding, borders, and backgrounds.
   - Covered box model concepts including content, padding, borders, and margins.
   - Demonstrated how to style text, links, images, forms, lists, and layout elements using CSS.

2. **Responsive Design**:
   - Introduced the concept of responsive design and discussed the importance of creating web pages that adapt to different screen sizes and devices.
   - Covered the use of meta tags like `<meta name="viewport" content="width=device-width, initial-scale=1.0">` to optimize web page layout on various devices.

3. **Color Theory**:
   - Explained color theory concepts including primary colors, secondary colors, and the RGB color model used in digital media.
   - Discussed how colors are created by mixing different intensities of red, green, and blue light in the RGB color model.

**link to progress:**[Color Markers](https://github.com/hunterxcobby/100-days-FreeCodeCamp/tree/main/projects/Day_6)


## Day 44: February 13, 2024

**Today's Progress**: MySQL, Replication && Redundacy

1. Researched and learned about setting up MySQL replication for redundancy and load distribution.
2. Studied the Feynman learning technique to understand complex concepts as a beginner.
3. Investigated the main role of a database, understanding it as a structured collection of data.
4. Explored the concept of a database replica, learning about its advantages in redundancy and load distribution.
5. Discussed the purpose of a database replica, highlighting redundancy and load distribution as its main objectives.
6. Analyzed the importance of storing database backups in different physical locations for disaster recovery and data protection.
7. Examined the necessity of regularly testing database backup strategies to ensure their effectiveness.
8. Encountered an access denied error while trying to access MySQL as root, prompting troubleshooting steps to resolve the issue.
9. Explored the process of installing MySQL on multiple servers and configuring its settings.
10. Set up MySQL replication between web-01 and web-02 servers, ensuring redundancy and load distribution.
11. Checked MySQL configuration files and executed commands to apply changes.
12. Troubleshooted issues with MySQL replication, including verifying connectivity and replication status.
13. Documented progress and tasks completed for reference and future review.

**link to progress:**[mysql](https://github.com/hunterxcobby/alx-system_engineering-devops/tree/master/0x14-mysql)


## Day 45: February 14, 2024

**Today's Progress**: Color Markers

1. **CSS Styling**:
   - Applied CSS styling to customize the appearance of markers, including setting background colors, borders, padding, and margins.
   - Utilized CSS properties like `display`, `color`, `font-size`, `border-radius`, `box-shadow`, and `text-align` to enhance the visual presentation.

2. **Box Model**:
   - Demonstrated understanding of the box model by setting dimensions (width and height) for markers, as well as adjusting padding and margins for spacing.

3. **Color Theory**:
   - Incorporated color theory principles to choose appropriate colors for markers, ensuring visual appeal and readability.

4. **Responsive Design**:
   - Implemented responsive design techniques to ensure markers display properly across different screen sizes and devices.
   - Utilized media queries and viewport meta tags to optimize layout and styling for mobile and desktop devices.

5. **CSS Selectors**:
   - Leveraged CSS selectors, including class selectors (`.class`) and element selectors, to target specific elements for styling.

6. **CSS Units**:
   - Utilized CSS units such as pixels (px) and percentages (%) to specify dimensions, spacing, and positioning of markers.

9. **Project Completion**:
   - Successfully completed the "Color Markers" challenge, showcasing understanding and application of HTML and CSS concepts.
   - Produced a visually appealing project
  
**link to progress:**[Color Markers](https://github.com/hunterxcobby/100-days-FreeCodeCamp/tree/main/projects/Day_7)


## Day 46: February 15, 2024

**Today's Progress**: WebStack Debuggging && Registration Forms

- ### WEB STACK DEBUGGING
1. **Researched and Gathered Information:** I consulted resources and understood the security implications of using the `root` user.
2. **Updated Script:** I made changes to the script to:
    - Uncomment the `user nginx;` line in the Nginx configuration file.
    - Modify the default site configuration to listen on port 8080.
    - Adjust file permissions.
    - Attempt to kill Apache2 (if relevant).
    - Restart Nginx as the `nginx` user using `sudo -u`.
3. **Encountered Challenges:** The updated script did not achieve the desired outcome. Nginx remained running as the `www-data` user.
4. **Sought Further Assistance:** I provided more details and requested help with troubleshooting and improvements from Gemini Ai 

**link to progress:**[Webstack Debugging](https://github.com/hunterxcobby/alx-system_engineering-devops/tree/master/0x12-web_stack_debugging_2)


- ### ONLINE REGISTRATION FORMS
- 
1. **HTML Form Creation**:
   - Created an HTML form structure using elements such as `<form>`, `<input>`, `<label>`, and `<button>` to collect user input.

2. **Form Accessibility**:
   - Linked `<label>` elements to their corresponding `<input>` elements using the `for` attribute and specific `id` values to improve accessibility for users, especially those relying on screen readers.

3. **Form Styling**:
   - Applied CSS styling to the form elements to enhance visual presentation and user experience.
   - Used CSS units such as `rem` and `vh` to create responsive and adaptable layouts for different screen sizes.

4. **Semantic HTML**:
   - Utilized semantic HTML elements such as `<fieldset>` and `<legend>` to group and organize related form elements, improving the structure and readability of the form.

5. **CSS Styling**:
   - Styled form elements using CSS properties like `display`, `margin`, `padding`, and `border` to achieve desired layout and spacing.
   - Applied visual enhancements such as `box-shadow` and `border-radius` to improve the appearance of form elements.

6. **Accessibility Best Practices**:
   - Implemented accessibility best practices by associating `<label>` elements with `<input>` elements using the `for` attribute, ensuring that form controls are properly labeled for users with disabilities.

7. **Responsive Design**:
   - Implemented responsive design techniques to ensure that the form layout adapts to various screen sizes and devices, providing a consistent user experience across different platforms.

8. **CSS Units**:
   - Used CSS units like `rem` (root em) and `vh` (viewport height) to create scalable and flexible layouts, accommodating different text sizes and viewport dimensions.

9. **Form Submission**:
   - Configured form submission behavior using the `action` attribute to specify the URL where form data should be sent, and the `method` attribute to specify the HTTP method (e.g., `POST`) for sending form data.


**link to progress:**[Registration forms](https://github.com/hunterxcobby/100-days-FreeCodeCamp/tree/main/projects/Day_8)
