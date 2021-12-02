# Project 0 - Banking Application
🕥 *Assigned: **Thursday December 2<sup>nd</sup>, 2021*** (Week 1) <br>
🕙 *Due: **Friday December 17<sup>th</sup>, 2021*** (Week 3)

<br>

## Description
Using Java 8, create an application that simulates simple banking transactions.

### Requirements
*	Build the application using Java 8 (or higher)

*	All interaction with the user should be done through the console using the `Scanner` class

*	Customers of the bank should be able to register with a username and password, and apply to open an account.
    * Stretch Goal: Customers should be able to apply for joint accounts

*	Once the account is open, customers should be able to withdraw, deposit, and transfer funds between accounts
    * All basic validation should be done, such as trying to input negative amounts, overdrawing from accounts etc. ❗

*	Employees of the bank should be able to view all of their customers information. This includes:
    * Account information
    * Account balances
    * Personal information

*	**Employees** should be able to approve/deny open applications for accounts

*	Bank **admins** should be able to view and edit all accounts. This includes:
    * Approving/denying accounts
    * withdrawing, depositing, transferring from all accounts
    * canceling accounts

*	Reasonable test coverage for the service layer is expected using JUnit.
    * TDD is encouraged.
    * Aim for 80% coverage of the service layer.
    * Share test coverage using JaCoCo in your presentation.

*	Logging should be accomplished using Log4J
    * All transactions should be logged

* **When presenting you will be connected to a production-ready AWS RDS**

* Create an SQL script that will create a user in an SQL database and a table schema for storing your bank users and account information.
   * Stretch Goal: Your database includes at least 1 stored procedure.
   
* Have your bank application connect to your SQL database using JDBC and store all information that way.

* You should use the **DAO design pattern** for data connectivity.

<br>

### Presentation
* 15 pts: Clear, concise and professional communication during the project presentation.
* 10 pts: Ability to communicate clear answers to fully address questions asked about the project. 
* 5 pts: Logical flow to the project presentation. 

<br>

## Frequently Asked Questions

1. When is the project due? 

    >A: The project will be due no earlier than Week 3 Sept. 9th. 

2. Is there a code freeze? 
    >A: It is recommended that you institute your own code freeze at least a day before the project presentations. However, this is a recommendation only; it will not be enforced. NOTE: The code that will be evaluated by your trainer will be the code you last pushed to your repository BEFORE the time set for project presentations. Code submitted while presentations are on-going will not be evaluated. 

3. What happens if I break my project that was mostly working right before the due date? 
    >A: **As you should have been regularly pushing code to your repository** you should be able to roll back to previously working version. If you have not regularly pushed your code and do not have a working commit to return to you will need to present the state of your application in its current form. 

4. Who will be evaluating the project? 
    >A: Your trainer will be the one providing the full evaluation of your projects. However, the QC team will also be present at presentations to ask questions about your project and consult with your trainer. 

5. Are we allowed to collaborate with others on our projects? 
    >A: Collaboration is encouraged. By helping others, and in turn posing good questions, you will become a stronger developer. Hopefully you will work together to solve the problems presented in this project.  However, you should still be ultimately designing the project yourself. Straight copy/pasting of another person's code is considered plagiarism and NOT allowed. NOTE: Code provided in demos by your trainer is not subject to plagiarism concerns. *Feel free to copy/paste and edit your trainer's code as necessary to suit your projects.*

