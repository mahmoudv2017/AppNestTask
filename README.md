# Tax Website - Backend and Frontend Submodules

This repository contains the source code for the Tax Website project, which consists of two submodules: Backend and Frontend. The project is designed to provide taxpayers with the convenience of filing taxes online, viewing their tax history, and tracking the status of their tax returns. The application is built using ASP.NET Core for the backend, utilizing SQLite as the database, and Angular for the frontend.

## Getting Started

To clone this repository and its submodules, follow these steps:

1. Clone the main repository:

git clone --recurse-submodules https://github.com/mahmoudv2017/AppNestTask.git

## Important Note for Backend Development: API Startup Project**

When working on the backend of the Tax Website project, make sure to set the correct project as the API startup project in your development environment. This step is crucial to ensure that the API server is properly started when running and debugging the backend code.

To set the API startup project in Visual Studio:

1. Right-click on the desired API project in the Solution Explorer.
2. Select "Set as Startup Project" from the context menu.


## Backend (ASP.NET Core and SQLite)

The backend of the Tax Website is built using ASP.NET Core, a cross-platform web framework. It provides robust and scalable APIs to handle tax-related data and operations. The data is stored using SQLite, a lightweight, serverless, and file-based relational database, making it suitable for small to medium-sized applications.

### Backend Features:
- API endpoints for taxpayers to file taxes, view tax history, and track tax returns.
- API endpoints for government agencies to manage tax data and track returns.
- Authentication and authorization using Identity Framework for taxpayers and admins.
- Entity Framework Core for seamless database interactions.
- Data validation and error handling for enhanced reliability.

## Frontend (Angular)

The frontend of the Tax Website is built using Angular, a powerful and popular web framework for building dynamic single-page applications. The frontend provides a user-friendly interface for taxpayers to interact with tax-related features.

### Frontend Features:
- User-friendly forms for taxpayers to input income, filing details, and tax-related data.
- Real-time validation and error messages to guide users in data entry.
- Interactive dashboards to view tax history and track tax return status.
- Responsive design for optimal user experience on various devices.
- Secure communication with the backend APIs using HTTPS.

## Tax Website Description

The Tax Website is an all-in-one platform that simplifies the tax filing process for taxpayers while providing efficient management tools for government agencies. Taxpayers can log in, enter their income and tax-related details, and easily file their taxes online. The system ensures data accuracy with strict validation rules and securely stores taxpayer information in a reliable database.

Government agencies can access the system to manage and monitor tax data efficiently. They can track tax return status, view taxpayer history, and gain valuable insights into the tax ecosystem. The application adheres to strict security protocols, ensuring the confidentiality and integrity of taxpayer data.

