![A black and gold logo Description automatically
generated](./images/report/media/image1.png){width="1.531463254593176in"
height="0.6875962379702537in"}

**DATB 06023 Business Database Development**

> **Title of the Assignment:**

**Transition to a Digital Era for RetroGaming Emporium**

> **Name:**
>
> **Student ID:**
>
> **Submission Date:**

+-----------------------------------------------------------------------+
| 1.  **Part 1**                                                        |
+=======================================================================+
| **Interview with Alex, Owner of Retro Gaming Emporium**               |
|                                                                       |
| Q1: What are the main challenges you that face with the current       |
| paper-based system?                                                   |
|                                                                       |
| ANS: The main challenges mainly include tracking orders and inventory |
| efficiently, managing customer and supplier information, and          |
| generating reports on time. It's becoming quite difficult to maintain |
| accuracy and speed as the business grows.                             |
|                                                                       |
| Q2: How could a computerised system enhance your day-to-day           |
| activities?                                                           |
|                                                                       |
| ANS: I anticipate the computerized system making our tasks easier by  |
| handling inventory, simplifying orders, and organizing customer and   |
| supplier details for quick access. It should also speed up report     |
| creation to aid in making decisions.                                  |
|                                                                       |
| Q3: What specific features would you want in the new system to handle |
| orders and payments?                                                  |
|                                                                       |
| ANS: I need the system to track all the order details, including      |
| customer information, arcade machine details, and payment statuses.   |
| It should support different payment methods and terms, especially for |
| our corporate customers who pay over the course of 30 days.           |
|                                                                       |
| Q4: How important is data security? Especially corporate customers    |
| sensitive information?                                                |
|                                                                       |
| ANS: Data security is extremely sensitive. We need to ensure that     |
| sensitive information, such as corporate balances and contact         |
| information, is accessible only to verified personnel. I'm also quite |
| concerned about parttime staff accessing this information as they are |
| new here.                                                             |
|                                                                       |
| Q5: What types of reports do you expect to require from the system?   |
|                                                                       |
| ANS: I need reports on sales, outstanding corporate balances,         |
| inventory levels, and customer order history. It would also be        |
| helpful to have customizable reports for specific data analysis.      |
|                                                                       |
| **System Requirements**                                               |
|                                                                       |
| **General Requirements:**                                             |
|                                                                       |
| Accessible User Friendly Interface: The system should have an easy to |
| access interface for navigation and operation.                        |
|                                                                       |
| Scalability: It must be able to accommodate business growth and       |
| additional features.                                                  |
|                                                                       |
| **Data Requirements:**                                                |
|                                                                       |
| Comprehensive Data Management: It should be able to manage supplier,  |
| customer, orders, parts, and payment data efficiently.                |
|                                                                       |
| Data Validation: Ensure data integrity / security through validation  |
| rules such as a bounced payment or negative balance                   |
|                                                                       |
| Automated Inventory Management: It should automatically update        |
| inventory levels based on the orders and supplies.                    |
|                                                                       |
| **Report Requirements:**                                              |
|                                                                       |
| Customizable Reports: It has to generate reports that can be          |
| customized for sales, inventory, and order history.                   |
|                                                                       |
| Report Access Control: Only the owner can generate and access         |
| reports.                                                              |
|                                                                       |
| **Security Requirements:**                                            |
|                                                                       |
| Role-Based Access Control : This needs to be in place to restrict     |
| access to sensitive data from unauthorised personnel.                 |
|                                                                       |
| Sensitive Data Protection: It must secure customer balances and       |
| contact information from unauthorized access.                         |
|                                                                       |
| Audit Trails: The system has to log all user activities for audit     |
| purposes.                                                             |
|                                                                       |
| **Additional Requirements:**                                          |
|                                                                       |
| Payment Management: Control transactions and review payment terms,    |
| such as offering a 30-day credit to business clients.                 |
|                                                                       |
| Promotion Control: To discounts for loyal / long time customers,      |
| maintaining a maximum of 25% off unless specifically approved by      |
| Alex.                                                                 |
+-----------------------------------------------------------------------+
| 2.  **Part 2**                                                        |
+-----------------------------------------------------------------------+
| > **Part 1 : Entities**                                               |
|                                                                       |
| -   Staff                                                             |
|                                                                       |
| -   Branch                                                            |
|                                                                       |
| -   Customer Details                                                  |
|                                                                       |
| -   Corporate Details                                                 |
|                                                                       |
| -   Orders                                                            |
|                                                                       |
| -   Discounts                                                         |
|                                                                       |
| -   Security                                                          |
|                                                                       |
| > Part 2 : Relationships                                              |
|                                                                       |
| -   Staff to Branch                                                   |
|                                                                       |
| > Staff will be many to one branch                                    |
|                                                                       |
| -   Staff to Customers                                                |
|                                                                       |
| > Staff will be one to many customers                                 |
|                                                                       |
| -   Customers to Order                                                |
|                                                                       |
| > Customers will be one or many to orders                             |
|                                                                       |
| -   Discounts to Customers                                            |
|                                                                       |
| > Discounts will be an optional 1 to 1 customer                       |
|                                                                       |
| -   Security to Customer                                              |
|                                                                       |
| > Security will be 1 to 1 customer                                    |
+-----------------------------------------------------------------------+
| 3.  **Part 3**                                                        |
+-----------------------------------------------------------------------+
| -   *Utilize **Crow's Foot Notation** to construct a more specific    |
|     data model. Include attributes, primary keys, foreign keys, and   |
|     cardinality. You can use any software such as                     |
|     [draw.io](https://app.diagrams.net/)*.                            |
+-----------------------------------------------------------------------+
| 4.  **Part 4**                                                        |
+-----------------------------------------------------------------------+
| -   *Normalize all the tables including the sample tables (**Table 1  |
|     and 2**) to **3NF notation**. Show the new 3NF tables with sample |
|     data.*                                                            |
+-----------------------------------------------------------------------+
