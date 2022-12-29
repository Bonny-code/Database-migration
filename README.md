# Database-migration
Advanced Demo - Migrating a database with the Database MIgration Service

In this advanced demo, we will be migrating a simple web application (wordpress) from an on-premises environment into AWS.
The on-premises environment is a virtual web server (simulated using EC2) and a self-managed mariaDB database server (also simulated via EC2)
We will be migrating this into AWS and running the architecture on an EC2 webserver and RDS managed SQL database.

Architecture Link : INSERT THE LINK HERE

This advanced demo consists of 5 stages :-

    STAGE 1 : Provision the environment and review tasks
    STAGE 2 : Establish Private Connectivity Between the environments (VPC Peer)
    STAGE 3 : Create & Configure the AWS Side infrastructure (App and DB)
    STAGE 4 : Migrate Database & Cutover
    STAGE 5 : Cleanup the account
