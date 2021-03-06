## _Bank Management System_

![Description](https://github.com/Akshatamitvyas/Mini_project/blob/main/Requirements/Image.png)

 The “Bank Account Management System” project is a model Internet Banking Site. This site enables the customers to perform the basic banking transactions by sitting at their office or at homes through PC or laptop. The system provides the access to the customer to create an account, deposit/withdraw the cash from his account, also to view reports of all accounts present. The customers can access the banks website for viewing their Account details and perform the transactions on account as per their requirements. With Internet Banking, the brick and mortar structure of the traditional banking gets converted into a click and portal model, thereby giving a concept of virtual banking a real shape. Thus today's banking is no longer confined to branches. E-banking facilitates banking transactions by customers round the clock globally.

## Features

- View balances: Firstly login your account with your account number and password. Then checking your balance doesn't require much work. You simply select Account balances and take a look at your balance and past transactions. If you have more than one account, you can also do transfers between accounts..
- Transfer funds: When you select Transfer Funds, you'll be asked where to transfer the money to and from, when, and the amount. 
- Set up recurring bill payments or transfers: If you make a regular payment every month, it might be convenient to set up an automatic withdrawal from your account.
- Monitor CIBC investments: If you have any CIBC investments, you can keep an eye on those stocks or mutual funds here.
- Pay bills: To pay your bills online, you just need to add to your account the names of the companies you wish to pay bills to.
- View our VISA* accounts: Always a good place to monitor your spending. You can make your credit card payments online, right from your account.
- Order Cheques: We don't need them much anymore due to online banking and debit purchases, but if you still use cheques, you can order them directly from the BAMS website.


## Tech

The project is made using C Programming Language. By using various concept.

- [Conditionals] - For the choice of the users!
- [Visual Studio] - Used for the text editors.
- [Mutliple file programming] - Used for the effectiveness of code.
- [Doxyzen] - Used to verify all the file.
- [Unity] - Used to run various test cases.


## Cost and Time
| Time | Cost | Feature |
| ------ | ------ | ------ |
| early 90's | Cost is for the pens and registers. | Everything was offline |
| Mid of 90's | Cost is for the maintanance for the Typerwriter | Everything was Offline |
| End 90's till now | This is the era of the Computer and Internet | Everything was online |



The main and the formost thing in the SDLC is  the design phase in this phase a coder give solution to the customer's problem. Which is being tested on various test cases. In this phase the customer start thinking about the SWOT analyzis, 4W and 1H question to the person who develop or give the solution.

In the phase My project Bank Management System also has different phase like:
1. Admin login to the Application.
2. Ask the customer for to perform their transactions(like update in details, remove account, create new account, etc). 
3. If the person is depositing the money in the bank how much rate of interest do he/she got payed by the bank.
4. For the admin to view the details of the customer which is submitted to the govt. regarding inspection.


## Defining The System
### Certain Assumption:
* Few systems already exists with which our system will interact
    * Bank management Application
    * Analytics

![Description](https://github.com/Akshatamitvyas/Mini_project/blob/main/Requirements/Diagram.png)
### Explanation:
* Bank Management System have few inbuilt features like:
    * Create a new account
    * Delete a existing account
    * Read for the transations of customer
    * Update a customer's record
    * Save record to file
    * Read record from file 
* Since I have assumed that few system are already exists. It is just for the understand of one how a person in a bank perform various task. 


#  SWOT analysis
It is very necessary to identify what are the **Strength, Weakness, Opportunity** and **Threats** in the an Application or games. 

## Strength
1. It will solve the problem handling different papers.
2. It will be easy for the customer as well as the bank employee to check the details of the cutomer.
3. If a customer want to remove his/her account it can also be done easily.

##  Weakness
1. As it is a model to it is not interoperable.
2. It is not secured as compared to the bank has.
3. There is no integrity.

##  Opportunity
1. It will help us to understand how bank employees work.
2. It will be easy for the person who want to know how does bank employees work. 

##  Threats
1. As it is not secured so details might get leaked.
2. It is device dependent.

## 4W and 1h 
### Who:
* It can help the people by learn about the bank's software.

### What:
* Nowadays for the student who are eager to learn each and everything it can help them.

### When:
* It is mock system to understand the working of Bank.

### Where:
* For performing the samll transation.

### How:
* It can act like a toy for the Engeering sstudent.

# Detail requirements
## High Level Requirements: 
| ID | Description | Category | Status | 
| ----- | ----- | ------- | ---------|
| HR01 | User shall be able to add new Customer's record | Techincal | TBD-S1 | 
| HR02 | User shall be able to read a Customer's record | Techincal | TBD-S1 |
| HR03 | User shall be able to update a Customer's record | Techincal | TBD-S1 |
| HR04 | User shall be able to delete a Customer's record | Techincal | TBD-S1 |
| HR05 | User shall be able to save records in a file | Techincal | TBD-S1 |
| HR06 | User shall be able to read data from a file | Techincal | TBD-S1 |
| HR07 | Data should not be lost in case of faliure | Scenario | FUTURE |
| HR08 | Data should always be stored when closing the system | Scenario | TBD-S1 |

##  Low level Requirements:
 
| ID | Description | HLR ID | Status (Implemented/Future) |
| ------ | --------- | ------ | ----- |
| LR01 | New record shall be added by providing all the asked information and the id should be unique or else Customer's record should not be accepted. | HR01 | TBD-S1 |
| LR02 | Reading Customer's data should be possible in 2 ways, first being by searching by id of a Customer's and second by printing all the records available | HR02 | TBD-S1 |
| LR03 | While reading all the records, it   records per page should be visible and should add as many Customer he/she wants.  | HR02 | FUTURE |
| LR04 | If user searches for an invalid ID "No Record Found" message should be displayed | HR02 | TBD-S1 |
| LR05 | User need to search by id for the pateint record to be updated, if no such record is available then "No Record Found" Message should be displayed | HR03 | TBD-S1 |
| LR06 | User need to search by id for the Customer's record to be deleted, if no such record is available then "No Record Found" Message should be displayed | HR04 | TBD-S1 |
| LR05 | User shall be able to save the files, if file already exists then it should append to file and should not overwrite it and if file does not exists then it should create a new file | HR05 | TBD-S1 |
| LR06 | If opening the file fails, then the system shloud prompt the message "Unable to access file" and should not end the program execution | HR05, HR06, HR07, HR08 | TBD-S1 |
| LR07 | When user Log off the system, message shall be prompted asking the user to save new records to file before exiting or not | HR08 | TBD-S1 |
