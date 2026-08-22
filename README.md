# secure-aws-web-hosting-with-private-database
This project demonstrates a secure AWS cloud infrastructure using VPC, public/private subnets, NAT Gateway, Internet Gateway, VPN connectivity, and database isolation. The architecture follows AWS networking and security best practices to protect backend resources while maintaining internet accessibility for web applications.
# Project Screenshots

## Architecture Diagram

![Architecture](AWS_architecture_diagram.png)

## VPC Configuration

![VPC](Screenshots/Vpc.png.png)

## Public Subnet

![Public Subnet](Screenshots/public_subnet.png.png)

## Private Subnet

![Private Subnet](Screenshots/private_subnet.png.png)

## NAT Gateway

![NAT Gateway](Screenshots/NAT_Gateway.png.png)

## Internet Gateway

![Internet Gateway](Screenshots/Internet_gateway.png.png)

## Route Table

![Route Table](Screenshots/Routetable.png.png)

## EC2 Instance

![EC2](Screenshots/EC2-instances.png.png)

## Database Tables

![Database](Screenshots/MySQL_Tables.png.png)

## Project Overview

This project demonstrates the design and implementation of a secure AWS cloud infrastructure for hosting a web application.

The architecture uses:

- Amazon VPC
- Public and Private Subnets
- Internet Gateway
- NAT Gateway
- VPN Connectivity
- Database Isolation
- Security Groups

The goal is to securely host a web application while protecting backend resources from direct internet exposure.

---

## Architecture Diagram

![Architecture Diagram](AWS_architecture_diagram_png.png)

---

## AWS Services Used

| Service | Purpose |
|----------|----------|
| VPC | Network Isolation |
| EC2 | Web/Application Server |
| NAT Gateway | Outbound Internet Access |
| Internet Gateway | Public Internet Access |
| VPN | Secure Remote Access |
| Security Groups | Traffic Control |
| Database | Data Storage |

---

## Network Architecture

### Public Subnet

Contains:

- EC2 Web Server
- NAT Gateway

### Private Subnet

Contains:

- Database Server
- Internal Resources

The database is not exposed directly to the internet.

---

## Security Features

- Private Database Isolation
- VPN-Based Secure Access
- Security Group Restrictions
- Public/Private Subnet Segregation
- Controlled Inbound and Outbound Traffic

---

## Challenges Faced

### Challenge 1

Private subnet resources could not access the internet.

### Solution

Configured NAT Gateway and updated route tables.

---

### Challenge 2

Application server could not connect to database.

### Solution

Updated security groups and routing configurations.

---

## Documentation

Detailed project documentation is available in:

- AWS_Project_Report.pdf

---

## Author

Devekishan Kumar Singh

B.Tech CSE Student

AWS Cloud Enthusiast
