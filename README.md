# AWS Organization Formation 

https://github.com/org-formation/org-formation-cli

This tool allows us to manage AWS Organizations, their Organizational Units and their accounts with Infrastructure as Code.

On top of that, you can easily bind CloudFormation templates with Org Formation templates in order to assign resources/services/IAM users to an specific OU.

### Get started

Install: 
```bash
npm install -g aws-organization-formation
```

Init:
```bash
org-formation init organization.yml --region us-east-1
```

Deploy CloudFormation templates:
```bash
org-formation update-stacks template.yml --stack-name my-stack
```