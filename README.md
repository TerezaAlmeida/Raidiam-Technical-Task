# Technical Task - Open Customer Data API

## Documents location:
- Test Case and Bugs reports are in the 'Documents/Test Cases and Bugs' path- there are 2 tabs one called 'Test Cases' and the other 'Bugs' in each is the corresponding documentation.
- API Documentation Evaluation is in the 'Documents/API Documentation Evaluation' path
- Security Test Plan is in the 'Documents/Security Test Plan' path

## How to run the Automated Test Cases:

### Requirements:
- Customer Data API up and running on Docker host
- Postman installed and loged in

### Precondition:
1. Clone this repository to your local machine
2. Open its folder (called Technical-Task)

### Steps:
- Attention: Remember to have the API running in your Docker host.
1. Open Postman and create a Workspace
2. Click on the Import button on the right side of your Workspace name 
3. Import the Postman Collection folder's content (the 2 files must be imported, Tech-Task and Test Environment)
4. Change the environment to Test Environment (where the environment variables are)
5. Expand all 3 folders (consents, Generate JWT, and Accounts), so you can access the requests inside of them
6. Now you can run the requests in the following order:
   - Create consents
   - Update consents
   - Generate JWT Accounts
   - All Accounts*
   - Specific Accounts*
     
  *The automated test scripts for these requests are in the Tests or Scripts tab below the API endpoint address.
  
  *After running the requests the Test Results tab is in the response section.

