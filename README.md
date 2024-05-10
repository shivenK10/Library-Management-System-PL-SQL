# Library-Management-System-PL-SQL
Problem Statement
Libraries serve as critical repositories of knowledge and information. However, manual handling of library operations, from book lending to tracking overdue returns, is both labor-intensive and error-prone. The goal of this project is to develop an automated Library Management System (LMS) that facilitates efficient library operations, enhances the user experience, and provides librarians with powerful tools to manage the inventory and user database.

In traditional library systems, many tasks are performed manually, including book cataloguing, circulation, and member management. This manual system leads to several issues:
•	Increased Error Rates: Manual data entry and tracking increase the likelihood of errors.
•	Inefficient Resource Utilization: Librarians spend a significant amount of time on administrative tasks which could be automated.
•	Limited Access to Information: Members lack real-time access to book availability and their borrowing history.
•	Difficulty in Managing Overdue Returns: Tracking and managing overdue books is challenging and often results in revenue loss due to uncollected fines.

Introduction
A library management system is a tool that manages and stores book information digitally, catering to the needs of its patrons. This system enables both library staff and patrons to keep a constant track of all books available in the library. It facilitates the search for desired books, making it essential for libraries to maintain a continuous check on the books issued and returned, as well as calculate fines. This digital approach reduces the chances of errors associated with manual operations by maintaining up-to-date records of issue dates, due dates, and returns, eliminating the need for manual tracking.

This system significantly reduces manual workload, enhancing the efficiency of library operations by minimizing errors in transaction details.


Advantages
•	Paperless Management: The system digitizes all book information, thus eliminating the need for paper records.
•	Continuous Updates: Library staff can continuously update the system with new book arrivals and their availability, ensuring patrons do not need to physically visit the library for issuing purposes.
•	Systematic Organization: Books are systematically categorized and organized within the system, allowing users to easily search and locate books.
•	Efficiency and Resource Conservation: Automating library management saves significant human effort and resources, making library services more efficient for both staff and patrons.

Normalization

The analysis of the database schema represented in the ER diagram shows that it adheres to the first three normal forms, ensuring efficient and redundancy-free data management:

1. First Normal Form (1NF): Each table contains only atomic values with consistent data types. For example, the ‘books’ table with fields like ‘book_id’, ‘name’, and ‘author’ confirms adherence to 1NF.

2. Second Normal Form (2NF): All non-key attributes in each table are fully dependent on the primary key. In the ‘books’ table, attributes like ‘name’ and ‘author’ depend solely on ‘book_id’, indicating compliance with 2NF.

3. Third Normal Form (3NF): There are no transitive dependencies within the tables. For instance, ‘publisher_id’ in the ‘books’ table links directly to the ‘publisher’ table and depends only on ‘book_id’, not on any non-key attribute.

In conclusion, the schema effectively reaches up to the Third Normal Form (3NF), promoting data integrity and operational efficiency by ensuring that non-key attributes depend strictly on the primary keys.

