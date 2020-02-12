# Banking-System                                            
#### INTRODUCTION
A banking system provides financial services for public. These systems are used by banks and are responsible for operating a payment system, providing loans, taking deposits, and helping with investments and transactions for customers. It reduces the manual work and helps bank to provide services like loan and fixed deposit in efficient and error free manner.
      
#### OBJECTIVE
The aim of this project is to apply our database knowledge in a practical and efficient way. 

#### TOOLS USED
*	HTML
*	CSS
*	PHP
*	JavaScript
*	MySQL
*	XAMPP Server (phpMyAdmin)

#### ER DIAGRAM
#### APPLICATIONS
*	Employee and Manager login for different branches. 
*	User-id and password for each employee and manager. 
*	Managers can add employees along with other operations done by employees.
*	Adding new customers, new accounts.
*	Old customers can have multiple accounts.
*	3 types of accounts-CURRENT ACCOUNT, SAVINGS ACCOUNT, LOAN ACOUNT
*	Withdraw and Deposit operations for various types of accounts.
*	Loan facility. 
*	Different types of loans with different interest rates are BUSINESS LOAN, EDUCATION LOAN, GOLD LOAN, HOME LOAN, PERSONAL LOAN, VEHICLE LOAN
*	Fixed deposit facility. 
*	Check on Maturity date of FD is done automatically. 
*	Option to break FD before Maturity Date. 
*	Options to view : 
1.	Customer details
2.	Account details
3.	Account Transactions
4.	Fixed Deposit transactions
5.	FD details. 
6.	Loan transactions
*	Event Scheduler for
1.	FDs 
2.	Loan Accounts 
3.	Interest on savings account. 
 
 #### FRONT-END
*	On insertion in EMPLOYEE table to automatically insert in LOGIN_DETAILS.
*	On insertion in CUSTOMERS to modify ACCOUNTS_INFO TRANSACTIONS, CARD TABLES according to type of account.
*	Insertion in ACCOUNT_INFO when existing customer creates new account.
*	Updating ACCOUNT table for premature FD.
        
#### PROCEDURES
*	To delete FD after maturity date.
*	To increase FD amount every month.
*	To update loan amount to be paid based on interest rate for every month.
*	To increase SAVINGS account balance based on interest rate for every month.
                 
#### BACKEND TRIGGERS
*	Trigger on insertion and deletion in FIXED_DEPOSIT_DATA
*	Trigger on deletion of employee data from employee data.
                
#### EVENTS
*	Automatic deletion of fixed-deposit on maturity-date and transfer of balance to his account.
*	Automatic updating of ACCOUNT at the end of every month and addition of interest to the balance of the savings account, loan amount to be paid and FD account is done for every month. 

#### LIMITATIONS
*	Interest rate of different types of loans are fixed. 
*	No time limit to pay back the loan.
*	No limit on number of loans for a customer.

#### MODIFICATIONS
*	Better FD break policy
*	Incorporation of service charges for CURRENT account
*	Incorporation of limit on number of withdrawals for savings account
*	Proper loan policies
                
 #### CONCLUSION
*	The banking system database project has been successfully implemented.
*	Though there are certain limitations this project works reasonably well.
