# Hybrid-Cloud-Engineer-Nanodegree-Projects

### Udacity's hybrid cloud engineer nanodegree projects

# What it Does?

## Project One: Private Cloud Web Application Infrastructure

- In this project, Nutanix’s integrated lab environment was used to design a private cloud solution for the company’s 
  key revenue generator, an e-commerce web application.
- Three Virtual Machines composing the infrastructure for a web application: a web server VM, application VM and 
  database server VM were protected and deployed on the private cloud.


## Project Two: Private Cloud SaaS: Three Tier Web Application Infrastructure

- A blueprint was designed to deploy and configure a three-tier web application with a load balancer, web server, and database VM hosted on the private cloud.
- Each VM is configured with the proper resources and tasks.
- Tested to ensure that the deployment works with a read and write to the database.
- Tested the web tier scaling to ensure that: scale-in and scale-out actions changing the population by a count of 1.
- It allows an end user to make a database backup.


## Project Three: Hybrid Cloud SaaS: Three Tier Web Application

- In this project, a blueprint was designed to deploy and configure a three tier web application with a load balancer hosted on the private cloud, 
  two web server tiers (each hosted on a private and a public cloud), and database VM hosted on the public cloud.
- Each VM is configured with the proper resources and tasks
- Tested the deployment to ensure that it works with a read and write to the database.
- Tested the web tier scaling: to ensure that scale-in and scale-out actions changing the population by a count of 1 on private cloud separately 
  from scaling on the public cloud.
- It allows self-service, ad-hoc backup of the database.
- It creates two application profiles for deployment for a small (1 vCPU, 1 core, 1GB RAM or t2.micro) and medium (2vCPU, 2 cores, 
  1GB RAM or t2.micro) CPU and memory configuration variants.
  

## Dependencies/Libraries:

- Calm Prism Central
- AWS Provider
- Amazon EC2, VPU, Key Pair, IAM, Security Groups
- t2.micro
- Bash
  
  
## Credits:
- Special thanks and appreciation to Nutanix and Udacity for this scholarship opportunity!

