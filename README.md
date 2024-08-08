# ExpenseReportCreationApp
This app is used to create Expense Reports and to notify approvers associated with the "ExpenseReportApprovalApp". 

# Known issues to work on:
*  'EditExpense_Screen' -> 'Btn_Submit_Edit_expense' -> 'OnSelect', the Level 1 and Level 2 approval emails have fixed url's to the approval applications, but need to be modified to dynamicly change the environment values to accomodiate for changing from one environment to another (i.e. The Prod button doesnt send an email to the approver with the Application url for the Dev environment.)
