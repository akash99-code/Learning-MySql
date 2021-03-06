# Learning-MySql
### For a Library Database Management Systems, created ER diagram, Relational Model, performed Normalization and executed various Queries.


**Problem Statement:**
	The library management database keeps track of library staffs, members, books, and other various units of library. 
One of the library staff is assigned to manage other staffs. Staff’s shift or work timings are recorded in the log DB. 
Library Staffs have various jobs. Providing new membership to numerous people is one of the important job. 
Every membership is completed by choosing a member plan. This plan can later be updated by the members under the consent of any library staff.
Members have facility to search through diverse collection of texts, which consists of all categories of books, articles, magazines, newspaper, etc. 
Members can perform various transactions like borrowing and returning of issuable texts. 
A member can have atmost 5 books in possession, which are issued from the library. 
Fine is calculated on every return of book and its amount is dependent on member’s plan. 
Only library staffs have permission to update the records of the texts. 
These texts are usually ordered from selected vendors. 
Staffs also maintains overall monetary transactions-track all expenses and incomes (fundings and other credits).


**ER Diagram**

<img src='3.%20ER-Diagram.jpg' width=1500/>

**DB Tables**

<img src='database_snapshot.PNG'/>

[Check out the descriptions of each table and their relationships.](https://github.com/akash99-code/Learning-MySql/blob/master/2.%20Entity%20Descriptions.pdf)



**DB State**

[Check out the populated data in each table and various queries executed on them, by clicking here.](https://github.com/akash99-code/Learning-MySql/blob/master/7.%20MySql%20Queries.pdf)
