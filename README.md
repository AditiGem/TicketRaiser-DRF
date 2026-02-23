Smart Campus Ticket Raiser API

Overview

The Smart Campus Ticket Raiser is a backend REST API developed using Django and Django REST Framework.
This project allows students to raise campus-related complaints such as internet issues, classroom problems, hostel maintenance concerns, and other infrastructure-related requests.
The project is developed by extending the concepts learned in Django Project-2, including CRUD operations, authentication, filtering, pagination, and PostgreSQL database integration.

Objective

The main objective of this project is to create a secure and structured backend system where:
Students can create and view complaints.
Administrators can manage and update complaint status.
All APIs are protected using JWT authentication.
Complaints can be filtered and ordered.
Data is stored securely in PostgreSQL.

Technologies Used

Python
Django
Django REST Framework
PostgreSQL
JWT Authentication (SimpleJWT)

Features

User authentication using JWT tokens
Admin panel access through Django admin
Create, view, update, and delete complaints
Pagination for listing complaints
Filtering complaints by category and status
Ordering complaints by priority or creation date
Secure API access for authenticated users only

Complaint Data Structure

Each complaint contains the following details:
Title
Description
Category (classroom, hostel, network)
Priority (low, medium, high)
Status (open, in-progress, closed)
Created date
Updated date

API Endpoints

The system provides endpoints for:
Generating authentication tokens
Listing all complaints
Creating new complaints
Viewing complaint details
Updating complaint information
Deleting complaints
All complaint-related endpoints require authentication.

Database
PostgreSQL is used as the primary database for storing complaint data and user authentication information.
Migrations are used to create database tables and manage schema changes.

How the System Works

A user logs in using their credentials.
A JWT access token is generated.
The token is used to access protected APIs.
The user can raise complaints through the API interface.
Administrators can update complaint status through the system.

Learning Outcomes

This project demonstrates:
REST API development using Django
Implementation of JWT authentication
Function-based API views
Query parameter filtering and ordering
Pagination handling
PostgreSQL database configuration
Secure backend architecture design

Conclusion

The Smart Campus Ticket Raiser is a simple yet structured backend system designed to handle campus maintenance requests efficiently.
It reflects practical implementation of backend development concepts and showcases understanding of Django REST Framework and secure API design.
