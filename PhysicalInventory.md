# Braintree Advanced Workflow Pack

## Physical Inventory Order Approval Workflow
1. Navigate to Workflow Templates
2. Select Physical Inventory Order Approval Workflow
3. Click on New
4. Click on New Workflow from Template

 ![image014](./images/image014.png)

5. Capture desired conditions such as who the approver should be
-   Under Approval User Setup, the “Approve Physical Inventory Orders” field should be ticked for the specified approver

 ![image015](./images/image015.png)

 
6. Once satisfied that all necessary conditions have been stipulated, workflow can be enabled

###	Test Instructions
1.	Navigate to Physical Inventory Orders
-   Create new order
-   Populate accordingly
2.	Attempt to Post the Order
-   Verify the system displays the message: 
    - _"This document can only be released when the approval process is complete."_
3.	Send for Approval
-   Click on Send Approval Request to initiate the approval process.
-   Confirm that the Status changes to Pending Approval.

 ![image016](./images/image016.png)

 
4.	Approver Notification
-   Verify that the approver receives a notification about the approval request.
5.	Approval Process
-   Simulate or allow the approver to approve the request.
6.	Confirm Release
-   Ensure the Status of the order changes to Released after approval is granted.