# AWS Setup (Account, IAM, Budget, DynamoDB)

## What I did
- Created an AWS account (secured the root user with MFA and stopped using it for daily work).
- Enabled **IAM access to Billing** so non-root users can view budgets.
- Created an **IAM user** with AdministratorAccess for daily tasks.
- Set up an **AWS Cost Budget** with alerts.
- Skimmed the **Amazon DynamoDB** docs to prep for upcoming lessons.

## Budget Screenshot
> Proof of budget configuration:

<img width="1062" height="258" alt="budgetScreenshot" src="https://github.com/user-attachments/assets/8ff08d8b-a599-4f40-aaca-e0fd5bf119ae" />


## DynamoDB — One Key Insight
DynamoDB’s *on-demand* capacity mode lets you skip capacity planning and pay per request, which is ideal while experimenting since usage is unpredictable.
