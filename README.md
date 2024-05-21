# Technical-Task

How to run the Automated Test Cases:

Requirements:
- Customer Data API up and running on Docker host
- Postman installed and loged in

Precondition:
1. Clone this repository to your local machine
2. Open its folder (called Technical-Task)

Steps:

3. Open Postman and create a Workspace
4. Click on the Import button on the right side of your Workspace name 
5. Import the Postman Collection folder's content (the 2 files must be imported, Tech-Task and Test Environment)
6. Change the environment to Test Environment (where the environment variables are)
7. Expand all 3 folders (consents, Generate JWT, and Accounts), so you can access the requests inside of them
8. Now you can run the requests in the following order:
   - Create consents
   - Update consents
   - Generate JWT Accounts
   - All Accounts*
   - Specific Accounts*
 9. *The automated test scripts for these requests are in the Tests tab below the API endpoint address.
 10. *After running the requests the Test Results tab is in the response section.

