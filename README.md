# Project SPP (Sumbangan Pembinaan Pendidikan)

#### Video Demo:  https://youtu.be/FuCMMOqatlk

#### Description:
Project SPP or School Fee Payment App is a desktop application designed for managing monthly fee payments for students in a school. It is built using Windows Form App and utilizes an MS SQL database for data storage.

Our application is a school payment system designed for monthly payments. It features a robust SQL database that manages various aspects, including student data, classes, staff information, and annual fee categories.

How the Application Works?
The payment system operates on a yearly basis. For instance, in 2023, Category A has a monthly fee of Rp. 25000, Category B is Rp. 50000. In 2024, Category A increases to Rp. 30000, and Category B to Rp. 60000. Payments can be made gradually or in installments.

The heart of the application is its SQL database. It consists of tables managing student details, classes, staff information, and annual fee categories.

In conclusion, our application not only simplifies the payment process but also provides a transparent and detailed payment history. This feature ensures that administrators can efficiently manage and monitor the payment status for each student throughout the academic year.

### Functionality Overview

* This application provides functionalities for user authentication, student record management, fee category management, payment processing, and transaction history tracking.

### Key Features

* User authentication and role-based access control.
* CRUD operations for student records, classes, and fee categories.
* Secure payment processing by authorized cashiers.
* Comprehensive transaction history for auditing and reference.

## Getting Started

To run the application, ensure you have the required dependencies installed (listed in Dependencies section). For installation instructions and execution details, refer to the respective sections below.

### Dependencies

* Windows OS 7/8/10/11
* .NET Framework Installed
* MS SQL Server / MS SQL Server EXPRESS Installed
* Microsoft SQL Server Management Installed

### Installing

* Open SQL Management.
* Import `.BACPAC` into database or you can run the `.SQL` file
* The default name database will be "DB_SPP" (do not change it).

### Executing program

* Navigate to ".../Desktop/bin/Debug/Desktop.exe".
* Open the application.
```
Email: admin@admin
Password: admin
```
Alternatively, you can customize your own credentials in the project file and database.


## Help

If you encounter an error or get stuck during your initial login, follow these steps:

1. Open the `helper.cs` file in your project.

2. Locate the connection string for your SQL Server.

**For MS SQL Server EXPRESS:**

   ```csharp
   string strCon = @"Data Source=.\SQLEXPRESS;initial catalog=...;"
   ```
**For MS SQL Server non-EXPRESS:**

   ```csharp
   string strCon = @"Data Source=.;initial catalog=...;"
   ```

## Authors

Contributors names and contact info

Shabri Afrizal Sutrisno
[@shabri.afrizal](https://instagram.com/shabri.afrizal/)

## Acknowledgments

Inspiration, code snippets, etc.
* [Microsoft](https://www.microsoft.com) for the development tools used in this project.