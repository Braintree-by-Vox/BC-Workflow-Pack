# G/L Budget Approval Workflow
- Navigate to Workflow Templates
- Select G/L Budget Approval Workflow
- Click on New
- Click on New Workflow from Template

![image002](./images/image002.png)

- Capture desired conditions such as who the approver should be
  Under Approval User Setup, the “Approve G/L Budgets” field should be ticked for the specified approver

 ![image003](./images/image003.png)
 ![image004](./images/image004.png)
 
1. Once satisfied that all necessary conditions have been stipulated, workflow can be enabled
   
## Test Instructions
- Navigate to G/L Budgets
  Open the G/L Budgets page in Business Central.
- Create a New Budget
  Click on New to create a budget.
- Provide the necessary details for the budget.

![image005](./images/image005.png)

- Edit Budget
  - Click on Edit Budget to open the budget for editing.
  - Enter the required values in the budget lines.
- Attempt to Release the Budget
  - Click Release without sending for approval.
  - Verify the system displays the message: 
  - _"This document can only be released when the approval process is complete."_

![image006](./images/image006.png)
 
- Send for Approval
  - Click on Send Approval Request to initiate the approval process.
  - Confirm that the Status changes to Pending Approval.

![image007](./images/image007.png)

- **Approver Notification**: Verify that the approver receives a notification about the approval request.
- **Approval Process**: Simulate or allow the approver to approve the request.
- **Confirm Release**: Ensure the Status of the budget changes to Released after approval is granted.

[**⬆️ Back to Top**](#gl-budget-approval-workflow) &nbsp;&nbsp;&nbsp;&nbsp; [**🏠 Home**](/BC-Workflow-Pack)