# PrernaSinghTest
This is a repository

###### Question 1
Internet websites consist of two main divisions: front-end and back-end.Front-end: The visible part of the website that users interact with directly. It includes HTML (structure), CSS (styling), JavaScript (interactivity), and frameworks/libraries.Back-end: The behind-the-scenes operations handling data processing, database management, and server-side tasks. It involves server-side programming languages, databases, servers, and APIs.Front-end focuses on user experience and design, while back-end manages the infrastructure and functionality.

###### question 2
html tags are used to define the structure and elements of a web page. some html tags are
heading tags <h1> <h2> <h3> <h4> <h5> <h6> all are used for headings and there size decreases as we go towards right in the series
<p> defines paragraphs of text.
<a> </a> used to create links
<img> image tag use src to link the image inside the image tag
<li></li> used for list tags
division tags are also there

###### question 3
The Virtual DOM (Document Object Model) is a concept and technique used in some JavaScript frameworks, such as React, to optimize the process of updating the actual DOM efficiently. Here's a simplified explanation of how the Virtual DOM works:-
Initial Render:When a component is first rendered, both the Virtual DOM and the actual DOM are created.The Virtual DOM is a lightweight copy of the actual DOM, represented as a tree-like structure in memory.
Update Phase:When changes occur in the component's state or props, a re-render is triggered.Instead of directly updating the actual DOM, React makes changes to the Virtual DOM.
Reconciliation:React performs a process called reconciliation, where it compares the previous Virtual DOM with the updated Virtual DOM.
It identifies the differences (or "diffs") between the two Virtual DOM representations efficiently.
Virtual DOM Diffing:React's diffing algorithm analyzes the changes in the Virtual DOM and determines the minimum number of operations required to update the actual DOM.It identifies which elements need to be added, modified, or removed from the actual DOM.
Actual DOM Update:After determining the differences, React updates the actual DOM with the necessary changes in an optimized manner.
Only the specific parts of the actual DOM that require modification are updated, minimizing the performance impact.
By utilizing the Virtual DOM, React can optimize the rendering process by reducing the number of direct manipulations on the actual DOM. Instead, it batches and performs updates efficiently, resulting in better performance and a smoother user experience.It's worth noting that this explanation provides a simplified overview of the Virtual DOM's working procedure. The actual implementation and optimizations can vary across different frameworks and libraries.

###### question 4


Here are some key differences between MySQL  and NoSQL
Data Model:
MySQL: It follows a structured, table-based data model where data is organized into rows and columns within predefined schemas.
NoSQL: It supports various data models, including key-value, document, columnar, and graph. It provides flexibility in storing unstructured or semi-structured data.
Schema:
MySQL: It requires a predefined schema with a fixed structure that defines the tables, columns, and their data types.
NoSQL: It is schema-less, allowing for dynamic and flexible data structures. Each document or object can have its own structure without adhering to a fixed schema.
Scalability:
MySQL: It typically relies on vertical scaling, where hardware resources are increased to handle larger workloads.
NoSQL: It excels in horizontal scalability, allowing data to be distributed across multiple servers, enabling high scalability and performance.
Transactions:
MySQL: It supports ACID (Atomicity, Consistency, Isolation, Durability) transactions, ensuring data integrity and enforcing complex relationships between tables.
NoSQL: It may not provide full ACID guarantees in all implementations. Some NoSQL databases prioritize scalability and performance over strict transactional guarantees.
Query Language:
MySQL: It uses Structured Query Language (SQL) as the standard query language for defining and manipulating relational data.
NoSQL: Depending on the NoSQL database, query languages can vary. Some NoSQL databases use SQL-like syntax, while others provide their own query languages or APIs.
Use Cases:
MySQL: It is well-suited for applications with structured data and complex relationships, such as e-commerce platforms, content management systems, and financial systems.
NoSQL: It is often used in scenarios requiring high scalability, rapid development, and handling large volumes of unstructured or semi-structured data, like social media platforms, real-time analytics, and IoT applications.
It's important to note that both MySQL and NoSQL databases have their strengths and weaknesses, and the choice between them depends on the specific requirements of your project, such as data structure, scalability needs, and desired level of consistency

###### question 5

MongoDB, a popular NoSQL database, is a document-oriented DBMS that stores and manages data in a flexible and schema-less manner. Instead of using traditional tables with fixed columns like in relational databases, MongoDB uses collections to store documents in a JSON-like format called BSON (Binary JSON).One of the standout features of MongoDB is its ability to handle unstructured and semi-structured data efficiently. It allows developers to store data with varying structures within the same collection, making it suitable for dynamic and evolving data models. This flexibility enables agile development and easy scalability.MongoDB's document-oriented nature also simplifies data access and manipulation. With a rich query language and powerful indexing capabilities, developers can perform complex queries, filtering, and sorting operations on documents without relying on explicit joins or complex relationships. This enhances performance and speeds up development time.Another key aspect of MongoDB is its horizontal scalability. By using sharding, MongoDB can distribute data across multiple servers or clusters, allowing it to handle massive amounts of data and high read/write workloads. This scalability makes MongoDB a great choice for applications that require high availability and performance.Furthermore, MongoDB provides built-in replication, enabling data redundancy and fault tolerance. By replicating data across multiple nodes, it ensures that even if one node fails, the system can continue operating seamlessly.In summary, MongoDB, as a document-oriented DBMS, offers the advantages of flexibility, scalability, and ease of development. Its ability to handle diverse data structures, powerful query capabilities, and horizontal scalability make it a popular choice for modern applications that deal with complex, rapidly changing data.




