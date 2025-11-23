# Item Journal Approval Workflow
1.  Navigate to Workflow Templates
2.  Select Item Journal Approval Workflow
3.  Click on New
4.  Click on New Workflow from Template
   
![image011](./images/image011.png)

5. Capture desired conditions such as who the approver should be
-   Under Approval User Setup, the “Approve Item Journals” field should be ticked for the specified approver

![image012](./images/image012.png)

6. Once satisfied that all necessary conditions have been stipulated, workflow can be enabled

##	Test Instructions
1.	Navigate to Item Journals
-   Select Item Journal Template
-   Populate accordingly
2.	Attempt to Post the journal
-   Verify the system displays the message: 
    - _"This document can only be released when the approval process is complete."_
3.	Send for Approval
-   Click on Send Approval Request to initiate the approval process.
-   Confirm that the Status changes to Pending Approval.

 ![image013](./images/image013.png)

4.	Approver Notification
-   Verify that the approver receives a notification about the approval request.
5.	Approval Process
-   Simulate or allow the approver to approve the request.
6.	Confirm Release
-   Ensure the Status of the journal changes to Released after approval is granted.

[**⬆️ Back to Top**](#item-journal-approval-workflow) &nbsp;&nbsp;&nbsp;&nbsp; [**🏠 Home**](/BC-Workflow-Pack)