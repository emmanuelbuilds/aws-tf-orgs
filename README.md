# aws-tf-orgs
Build out an organization in aws using terraform. no resources yet. just environment.

Inside the aws-tf-orgs directory there is an environments directory that contains the shared terraform variables for each environment (DEV,TEST,PROD).
Terraform modules are contained in the src/tfe directory.

The modules in this terraform project simply define policies and permissions and roles for users in each environment.
App2App permissions will need to be defined after.