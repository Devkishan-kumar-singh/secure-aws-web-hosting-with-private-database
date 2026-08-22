# Secure AWS Web Hosting with Private Database

## Overview

This project demonstrates a secure AWS cloud infrastructure architecture using Amazon VPC, public and private subnets, NAT Gateway, Internet Gateway, VPN connectivity, and database isolation.

The goal is to host a web application securely while protecting backend resources from direct internet exposure.

## AWS Services Used

- Amazon VPC
- EC2
- NAT Gateway
- Internet Gateway
- VPN
- Security Groups
- Route Tables
- MySQL Database

## Architecture Highlights

- Public subnet for web/application resources
- Private subnet for database resources
- Secure database isolation
- Controlled traffic using Security Groups
- NAT Gateway for outbound internet access
- VPN-based secure administrative access

## Project Documentation

- AWS_Project_Report.pdf
- Documentation_Part.pdf

## Architecture Diagram

![Architecture Diagram](AWS_architecture_diagram.png)

# Project Screenshots

## VPC Configuration

![VPC](Screenshots/Vpc.png)

## Public Subnet

![Public Subnet](Screenshots/public_subnet.png)

## Private Subnet

![Private Subnet](Screenshots/private_subnet.png)

## NAT Gateway

![NAT Gateway](Screenshots/NAT_Gateway.png)

## Internet Gateway

![Internet Gateway](Screenshots/Internet_gateway.png)

## Route Table

![Route Table](Screenshots/Routetable.png)

## EC2 Instance

![EC2 Instance](Screenshots/EC2-instances.png)

## Database Tables

![Database Tables](Screenshots/MySQL_Tables.png)

## Security Group (Inbound Rules)

![Inbound Rules](Screenshots/Security_group_db_server(Inbound).png)

## Security Group (Outbound Rules)

![Outbound Rules](Screenshots/Security_group_dbserver(Outbound).png)

## Author

Devekishan Kumar Singh

B.Tech CSE Student

AWS & Cloud Computing Enthusiast
