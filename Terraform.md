# Infrastructure as a code

## What is Infrastructure as a code
   
   Define your Infrastructure in a machine readable format. 

## what is Terraform
 
   Terraform is a tool for building, changing, and versioning infrastructure safely and efficiently. It takes your infrastructure you have defined 
   in code and make it cool. It uses a HCL language. 
   
## Why use Terraform

   Terraform can compare your desired infrastructure state to the current infrastructure state you actually have and automatically work out
   how to align two states.As your infrastructure is now defined as code you can check it into your version control system.
   
   Reproduciable, every time you create an environment it will be exactly the same and it is very fast to setup the whole environment. 
   
   Terraform has many plugins and providers support for multiple clouds and applications.
   
   * Uses providers model - allows you to define infrastructure on many sources in a consitent way.
   * `terraform init` - Initialization of providers
   * `terraform plan` - plan before apply changes 
   * `terraform apply` - Apply changes after reviewing plans.
   * `terraform destroy` - Destroy changes after done with the instances.
      
   Other Reasons to use to Terraform is,
   
   * Importing Existing infrastructure by slowy migrating.
   * Provider kept up to date by community.
   * Open source so you can debug issues.
   * Write your own providers.
      
## Terraform vs AWS cloudFormation

   * It is Open source and genrally moves faster.
   * Terraform allows you to plan before changing your infrastructure.
   * Terraform allows you to configure multiple clouds/resources with the same skillset allowing you to manage all of your
     infrastructure in the same way.
      
