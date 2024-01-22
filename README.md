# artgal
Art Gallery Database Project <3 

This project involves the design and implementation of a relational database for managing an art gallery. The database includes tables for galleries, artists, artwork, exhibits, customers, sales, and the relationships between them. The schema has been designed to support common queries related to gallery management, sales tracking, and exhibit information.

Database Structure

The database consists of the following tables:

gallery: Stores information about art galleries, including name, address, city, and description.
artists: Contains details about artists such as name, address, phone number, and the gallery they are associated with.
artwork: Captures information about individual art pieces, including title, price, year, style, medium, and the artist associated with it.
exhibit: Records details about art exhibits, including name, address, start and end dates, RSVP count, and the gallery hosting the exhibit.
customers: Stores customer information, including first name, last name, address, and email.
sales: Tracks sales transactions, including date, payment method, customer ID, and artwork ID. This table also utilizes foreign keys for relationships with customers and artwork.
exhibit_artwork: Represents the many-to-many relationship between exhibits and artwork, linking them through foreign keys.
Data Population

The project includes a data section where sample data is inserted into the tables. This data includes information about customers, galleries, exhibits, artwork, artists, sales, and the relationships between exhibits and artwork.

Queries and Use Cases

The README includes a section showcasing various SQL queries and their use cases. These queries demonstrate how the database can answer different questions related to gallery management, sales tracking, and exhibit information. The queries cover single table SELECT, INNER JOIN, LEFT JOIN, aggregate functions (MIN, MAX, SUM, AVG, COUNT), GROUP BY, HAVING, ORDER BY, LIMIT, and subqueries.

How to Use

To use this database, follow these steps:

Database Creation: Execute the SQL statements in the provided script to create the necessary tables.
Data Population: Insert sample data into the tables using the provided data section.
Query Examples: Explore the README to understand the different queries that can be executed on the database.
Adjustments: Modify the data or schema as needed for your specific use case.
Contributions

Contributions to improve the database schema, queries, or any other aspect of the project are welcome. Feel free to fork the repository, make changes, and submit a pull request.
