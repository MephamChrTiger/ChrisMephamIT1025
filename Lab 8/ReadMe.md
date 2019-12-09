### Executive Summary
In this lab, we go over the importance of data, information, and knowledge, as well as relational data and big data and what they mean to you. After that, I went over SQL and databases for a short period and the structure of Query Language. Lastly we studied SQL injections and the Ethics of data and intelectual property rights.

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

####  Ethical and Legal Implications 
##### Code of Ethics
A code of ethics is a document that outlines a set of acceptable behaviors for a professional or social group; generally, it is agreed to by all members of the group. The document details different actions that are considered appropriate and inappropriate. One of the major advantages of creating a code of ethics is that it clarifies the acceptable standards of behavior for a professional group. Just like with a code of ethics, acceptable use policies specify what is allowed and what is not allowed. In most cases, such as with Wi-Fi, violating the acceptable use policy will mean that you will lose your access to the resource. While losing access to Wi-Fi at an airport may not have any impact t you, a college student getting banned from the university’s Wi-Fi from downloading illegal content or movies could have a large impact.

iii) One of the services that I use on almost a daily basis is a VPN called Tunnelbear. Under their Acceptable use policy I noticed a statement that was very interesting that most companies have, but I haven't really noticed (since I dont' read AUPs). It stated, "You agree that TunnelBear, in its sole discretion, for any or no reason, and without penalty, may terminate or suspend your use of the Service at any time. TunnelBear may also in its sole discretion and at any time discontinue the Services in their entirety, or any part thereof, with or without notice." or as they generoulsy wrote next to it, "We reserve the right to euthanize your TunnelBear." This is just interesting to me because they could with no warning and no consequence just terminate my account and service for absolutely no reason whatsoever.  (LINK - https://www.tunnelbear.com/terms-of-service )

#### Intellectual Property 
i) WIPO is the global forum for intellectual property (IP) services, policy, information and cooperation. Their mission is to lead the development of a balanced and effective international IP system that enables innovation and creativity for the benefit of all. 

ii) The automatic creation of copyright protection in the United States began in 1978. Before 1978, statutory copyright was generally secured by the act of publishing a work with a notice of copyright on the work. If a work remained unpublished, others are free to use, take, copy, and steal your work, or any work that has no copyright to your name. 

iii) Trademarks are distinctive indicators or signs that individuals, businesses, or other legal entities use. They use these indicators or signs to communicate that services or products to consumers that are connected to the trademarks stem from a unique source. 

####  Information Collection
Under information collection, there are four main big federal laws and regulations that are as follows; (HIPPA) Health Insurance Portability and Accountability Act. Gives parents rights to their student’s information, and governs how school health services share their data, (CIPA) Children’s Internet Protection Act. Requires the use of web filters on school computers. Without it we lose funding from eRate, (COPPA) Children’s Online Privacy Protection Act. Federal law that prevents collection of online data from persons under 13 years of age. This is why Apple requires you to be 13 years old before you can obtain an Apple ID, and last but not least (FERPA) Family Educational Rights and Privacy Act. Prevents disclosure of information on grades or behavior to anyone other than the student or parent.


### Conclusion
In this lab I learned a lot, and when I say that I mean it, I learned a lot that I didn't know and I am really glad I did. First, going over data and knowledge, especially big data and their technology really opened my eyes to what a company can accomplish with their data. Going over SQL and databases for a while also was a good refresher from back in high school, easy to understand, but a slight pain to remember. Lastly going over AUPs and intelectual property rights was a big one that I have heard about before but didn't really think was important. Going and reading one of my software's AUP was very informative and I learned things that I would have otherwise not knows since I don't regularly read them. 
