### Executive Summary

#### Data, Information and Knowledge 
##### Relational Data
Data transforms into information by assigning a meaning or context to a date. Furthermore, the accumulation of a data bundle or the linking of various data can also represent information. The moment the information is processed, linked and stored, whether by a machine or a human being, it becomes knowledge.

ii) The primary key in the orders and customers table would have to be some sort of ID number for orders or a username for the customers. the two tables would be related because each customer needs to have orders and each order belongs to a customer. the foreign key in the orders table would be each order's ID number so only the customer and order would know that number. 

iii) It is important to properly create the date field for each order because you need to keep track of each order and when it was made so you can make and deliver the order in a proper manner and in the order you recieved each one. 

#### Big Data
i) In most big data circles, these are called the four V’s: volume, variety, velocity, and veracity. The main characteristic that makes data “big” is the sheer volume. The main characteristic that makes data “big” is the sheer volume, where variety is one the most interesting developments in technology as more and more information is digitized. Veracity refers to the trustworthiness of the data, and velocity is the frequency of incoming data that needs to be processed.
 
ii) People such as banks across the world have used Big Data technology to ensure customer loyalty. Banks while issuing credit cards have the luxury to analyze loads of information to reduce the chance of credit card fraud. Other companies such as facebook, a game changer in today’s modern world has been able to predict political opinion, intelligence and emotional stability of its users based on their activity on Facebook, all due to technological advances with big data. 

#### Structured Query Language 

a) RDBMS is a database management system. And SQL is the language used for communicating with data in an RDBMS. Or in the plain term, RDBMS is a book and SQL is the language being used in the book.

b) The two tables that I chose are the orders table and the order details table. These two are related because the order details have everything that the order table needs to complete a legitimate order from a customer. 

#### SQL Injections 
SQL injection is a code injection technique that might destroy your database, is one of the most common web hacking techniques, and is the placement of malicious code in SQL statements, via web page input. SQL injection usually occurs when you ask a user for input, like their username/userid, and instead of a name/id, the user gives you an SQL statement that you will unknowingly run on your database. A hacker might get access to all the user names and passwords in a database, by simply inserting 105 OR 1=1 into the input field. One of the simplest things to do to reduce these attacks would be to assume all user-submitted data is evil so use input validation via a function such as MySQL's mysql_real_escape_string() to ensure that any dangerous characters such as ' are not passed to a SQL query in data. You should also sanitize everything by filtering user data by context.

### Conclusion
