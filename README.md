# Online Waste Management System Documentation

# Generation Introduction

The **Online Waste Management System** is a comprehensive software solution designed to streamline and enhance the management of waste collection, disposal, and monitoring processes. In an era where environmental sustainability is of paramount importance, efficient waste management systems play a crucial role in maintaining clean and healthy communities while minimizing environmental impact.

This project aims to address the challenges associated with traditional waste management systems by introducing modern technology and automation into the process. It offers a user-friendly platform that connects stakeholders involved in waste management, including administrators, users, collectors, and even waste collection trucks.

## Key Objectives

The core objectives of the Online Waste Management System project include:

1. **Efficient Bin Management**: Enable users to add, monitor, and manage waste bins with ease. This includes tracking bin sizes, statuses, and their physical locations.

2. **User Management**: Provide a robust user management system with multiple user roles, including administrators, regular users, and collectors. Implement secure user registration, login, and authentication mechanisms.

3. **Truck Management**: Allow for the addition and assignment of waste collection trucks to collectors, ensuring optimized collection routes and schedules.

4. **Collectors' Workflow**: Facilitate collectors in tracking their assigned routes, marking bins for collection, and updating the system with real-time data.

5. **User Engagement**: Promote user engagement by offering tools for reporting issues, such as overflowing bins or damaged containers. Implement notification systems for updates and alerts.

6. **Integration with IoT (Internet of Things)**: Seamlessly integrate Arduino-based IoT devices to monitor bin statuses and optimize collection routes based on real-time data.

7. **Security and Data Protection**: Prioritize data security by implementing robust authentication, authorization, and data encryption mechanisms to protect user information and sensitive data.

8. **User-Friendly Interface**: Develop an intuitive and visually appealing user interface that enhances user experience and encourages participation in waste management efforts.

9. **Scalability**: Design the system to be scalable, allowing for the addition of new features and capabilities in response to evolving waste management needs.

10. **Documentation and Support**: Provide comprehensive documentation for developers and end-users, ensuring easy setup and ongoing support.

## Benefits

The Online Waste Management System offers several benefits, including:

- **Improved Waste Management**: Enhance the efficiency of waste collection and disposal processes, reducing environmental pollution and health risks.

- **User Empowerment**: Empower citizens to actively participate in waste management by reporting issues and staying informed about collection schedules.

- **Data-Driven Decisions**: Utilize real-time data to make informed decisions about bin collection routes, optimizing fuel usage and reducing operational costs.

- **Environmental Impact**: Contribute to a more sustainable environment by reducing waste overflow and improving recycling efforts.

- **Streamlined Operations**: Simplify the management of waste collection, route planning, and collector assignments for municipal authorities.

The Online Waste Management System represents a significant step towards modernizing waste management practices, fostering community involvement, and contributing to a cleaner and greener future.


## Table of Contents
1. [Introduction](#introduction)
2. [System Architecture](#system-architecture)
3. [Database Design](#database-design)
4. [User Management](#user-management)
5. [Bin Management](#bin-management)
6. [Truck Management](#truck-management)
7. [Collectors](#collectors)
8. [UserBin Relationship](#userbin-relationship)
9. [Arduino Integration](#arduino-integration)
10. [Security](#security)
11. [User Interface](#user-interface)
12. [Deployment](#deployment)
13. [Installation](#installation)



## Predefined Users

| User ID | Name       | Email                      | User Type  | Status | Telephone     | OTP     | Approval Status |
| ------- | ---------- | -------------------------- | ---------- | ------ | ------------- | ------- | --------------- |
| 1002    | admin      | a@g.com                    | admin      | 1      | 12232         | 12      | 1               |
| 1025    | Kamal      | kamal@gmail.com            | user       | 0      | 754865213     | 922283  | 1               |
| 1046    | Lakshan    | duruthuautomation9@gmail.com| user       | 0      | 123455        | 527234  | 1               |
| 1047    | Chanaka    | chanaka@gmail.com          | user       | 0      | 758963254     | 589991  | 1               |
| 1048    | Dharshana  | dharshan@gail.com          | collector  | 0      | 776325698     | 484451  | 0               |

## Introduction
Provide an overview of the online waste management system and its purpose.

## System Architecture
Explain the high-level architecture and technologies used in the system.

## Database Design
Describe the database schema, table structures, and relationships.

## User Management
Detail user types, registration, authentication, and OTP verification using PHPMailer.

## Bin Management
Explain how to add, list, and remove bins. Discuss bin status (active, inactive).

## Truck Management
Describe how to add trucks and assign them to collectors.

## Collectors
Explain collector management and their status.

## UserBin Relationship
Discuss the association of users with bins.

## Arduino Integration
Detail the integration of Arduino in waste management processes.

## Security
Explain data validation, password hashing, and protection against SQL injection.

## User Interface
Provide screenshots and descriptions of key user interface screens.

## Deployment
Instructions for deploying the application and server requirements.

## Installation
1. Clone the repository:
   ```
   git clone https://github.com//menoc61/OWMS.git
   ```
2. Navigate to the Project Directory `cd OWMS`
3. Install PHPMailer Using Composer:
   If PHPMailer is not already included in your project, you can install it using Composer. First, ensure you have Composer installed on your system. If not, you can download it from <a href="https://getcomposer.org/download/">Composer's    website</a>.
   
   After installing Composer `cd PHPMailer`, run the following command in your project directory to install PHPMailer:
   ```
   composer install
   ```
4. create a database named `sbin` in your DBMS tool and ensure the sbin.sql script has been imported successfully.
5. Open your web browser and access the application at `http://localhost:8000` (or the address specified when starting the server). You should see your waste management system's  landing page.


 
