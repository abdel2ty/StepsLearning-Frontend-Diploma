# Introduction To Web

### Difference between Website and Web application?
- **Website:** define the first level of data. this website privew data like if you are making portfolio, landing page, etc. so, it's to make data that user only can see it and cannot react with it.
- **Web-App:** it's a normal website but interactive, means the user can enter data and receive data. not just a static page user cannot react with. like ecommerce, social media, etc.

---

### Web Technologies

| Front-end Development | Back-end Development |
|-----------------------|----------------------|
| Html5                 | Html5                |
| Css3                  | Css3                 |
| JavaScript            | JavaScript           |
| Bootstrap             | Node.js              |
| Tailwind css          | Express.js           |
| EcmaScript6           | Nest.js              |
| TypeScript            | Php                  |
| React.js              | Laravel              |
| Angular.js            | C#                   |
| Vue.js                | Asp.Net              |

---

### Life Cycle of Web Development

1. **Browser:** the section that uses front-end.

   - **Definition:** The browser (like Chrome, Firefox, or Edge) is the software users interact with to access websites.
   - **Role:** 
     - Sends HTTP requests to servers.
     - Receives HTTP responses.
     - Renders pages using HTML, CSS, and JavaScript.
   - **Example technologies:** HTML, CSS, JavaScript, React, Angular, etc.


2. **Server**

   - **Definition:** The server is the machine or application that receives requests from users and returns responses.
   - **Role:** 
     - Handles client requests.
     - Communicates with the database.
     - Sends files or API responses to the browser.
   - **Example technologies:** Node.js, .NET, Django, Flask, Express, etc.


3. **Database**

   - **Definition:** A system to store, organize, and manage data.
   - **Role:**
     - Stores website data like users, posts, products, etc.
     - Supports create, read, update, and delete operations (CRUD).
     - Interacts with the server through queries.
   - **Example technologies:** MySQL, PostgreSQL, MongoDB, SQLite, Redis, etc.



4. **Domain → DNS → IP**

   - **Domain Name:**
     - Human-readable address of a website (e.g., `example.com`).
   - **DNS (Domain Name System):**
     - Translates domain names into IP addresses.
     - Works like a phonebook of the internet.
   - **IP Address:**
     - The real address of the server (e.g., `192.168.1.1` or `142.250.184.206`).

---

### Steps of Website Access (From user to website):

   1. The user types a domain like `www.example.com` in the browser.
   2. The browser sends a request to a *DNS server* to get the IP address.
   3. DNS returns the IP address of the server.
   4. The browser sends an *HTTP/HTTPS request* to that IP address (usually on port 80 or 443).
   5. The *server* receives the request and processes it.
   6. If needed, the server queries the *database*.
   7. The database returns data to the server.
   8. The server generates a response (like HTML or JSON).
   9. The browser receives the response and renders the website.

---

### SQL vs NoSQL Databases

**1. SQL Databases (Relational Databases)**

- **Definition:**  
  SQL (Structured Query Language) databases are **relational databases** that store data in **tables** with rows and columns.

- **Structure:**  
  - Uses **schemas** (predefined structure).
  - Data is organized in **tables** with relationships between them (foreign keys, joins).

- **Examples:**  
  - MySQL  
  - PostgreSQL  
  - SQLite  
  - Microsoft SQL Server  
  - Oracle

- **When to Use:**  
  - When data is highly structured and relational.  
  - When consistency and complex queries are important.

- **Pros:**  
  - Strong data integrity (ACID compliance).  
  - Powerful querying using SQL.  
  - Well-supported and widely used.

- **Cons:**  
  - Less flexible with unstructured or changing data.  
  - Scaling horizontally (across many servers) is harder.


 **2. NoSQL Databases (Non-Relational Databases)**

- **Definition:**  
  NoSQL databases are **non-relational** and store data in flexible formats like documents, key-value pairs, graphs, or wide-columns.

- **Structure:**  
  - No fixed schema.  
  - Data can be nested (e.g., JSON documents).  
  - Types: Document, Key-Value, Graph, Column-based.

- **Examples:**  
  - MongoDB (Document)  
  - Redis (Key-Value)  
  - Cassandra (Column-based)  
  - Neo4j (Graph)

- **When to Use:**  
  - When dealing with **big data**, real-time apps, or unstructured data.  
  - When flexibility and scalability are priorities.

- **Pros:**  
  - High performance with large-scale data.  
  - Easy to scale horizontally.  
  - Flexible data models (schema-less).

- **Cons:**  
  - Weaker data integrity (may sacrifice ACID for speed).  
  - Limited support for complex queries (depending on the type).

---

|            | SQL                        | NoSQL                          |
|------------------|----------------------------|--------------------------------|
| Data Structure    | Tables (Relational)        | Documents, Key-Value, etc.     |
| Schema            | Fixed                      | Dynamic/Flexible               |
| Query Language    | SQL                        | Varies (e.g., JSON queries)    |
| Scaling           | Vertical (harder)          | Horizontal (easier)            |
| Best For          | Structured data & complex queries | Big data, real-time apps  |
| Examples          | MySQL, PostgreSQL          | MongoDB, Redis, Cassandra      |

---

###### last update: 22-7-2025