# dmoney-api-testing
Automated and integration testing project for the DMoney API. A demo financial transaction system that enables virtual fund transfers. This project focuses on validating API endpoints for user creation, transactions, balance inquiries, and other key functionalities using modern testing tools and automation workflows.

# Tools & Technologies
postman, newman, & nodejs
### Test Case Scenarios

Below are the core test flows implemented and validated through automated API testing:

1. **Admin Operations**  
   - Create a new **Agent**, **two random Customers**, and a **Merchant** using the Admin API.

2. **System Transaction**  
   - Deposit a random amount (between **10 TK and 10,000 TK**) from the **SYSTEM account** to the Agent.

3. **Agent to Customer Transaction**  
   - The **Agent deposits** money into one of the **Customer** accounts.

4. **Agent Balance Verification**  
   - Verify that the **Agent’s balance** updates correctly after the deposit.

5. **Customer to Customer Transfer**  
   - The **first Customer sends money** to the **second Customer**.

6. **Customer Withdrawal**  
   - One **Customer withdraws** a random amount (between **10 TK and 10,000 TK**) to the **Agent**.

7. **Customer Balance & Transaction Check**  
   - Verify the **Customer’s balance** and **transaction statement** using the **transaction ID (trnxId)**.

8. **Customer to Merchant Payment**  
   - The **second Customer makes a payment** to the **Merchant** account.

9. **Post-Payment Verification**  
   - The **second Customer checks** both **balance** and **transaction statement**.  
   - The **Merchant checks** their **updated balance** to confirm receipt.
     
### Documantation for the API Collection -
https://documenter.getpostman.com/view/37977154/2sAYHzFNUX
### Test Case-
https://docs.google.com/spreadsheets/d/1ve83iC7wlCrCKW4XhV-k287BPgCDgXEg1EDmgw8BUF0/edit?gid=1767710928#gid=1767710928
### Bug Report
https://docs.google.com/spreadsheets/d/1sayj2whX-tY66Yv74q-qdIutq_193esN-URheL2ySjo/edit?gid=269962739#gid=269962739
###  How to Run?

Clone this project and run the following commands:

```bash
npm i
npm test


