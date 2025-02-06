# Angel Fincap Loan Management System

## Overview

The **Angel Fincap Loan Management System** is a PHP-based web application designed to streamline and automate loan management processes for **Angel Fincap Limited**, a Non-Banking Financial Company (NBFC). This platform allows for efficient borrower registration, loan application, verification, repayment tracking, and status updates, providing a seamless experience for users and improving operational efficiency.

---

## Features

1. **User Registration and Authentication**  
   - Secure registration with role-based access (Borrower, Branch Officer, Verifier Officer, Head Officer).
   - Login functionality for all users.

2. **Loan Application Process**  
   - Branch Officer can apply for loans by submitting details such as loan amount, interest rates, installment plans, and uploading necessary documents.

3. **Loan Verification Workflow**  
   - Verifier Officers validate loan applications, check documents, and approve or reject loans.

4. **Liability Management**  
   - Comprehensive tracking of borrower liabilities, including loan amounts, installments, and remaining balance.

5. **Repayment Tracking**  
   - Real-time monitoring of repayment schedules, paid amounts, and pending installments.

6. **Role-Specific Dashboards**  
   - Separate dashboards for different user roles to handle tasks efficiently.

7. **Notifications and Alerts**  
   - Automated alerts for loan status changes, repayment deadlines, and other important updates.

8. **Reports and Insights**  
   - Generate PDF reports for loan statuses, liabilities, and repayments.

---

## Class Diagram

Below is the **Class Diagram** of the Angel Fincap Loan Management System:

!![Untitled Diagram drawio (17)](https://github.com/user-attachments/assets/a5fdf42d-8c73-42eb-99cc-ed278fc8fc63)


This diagram represents the system's structure and the relationships between its components.

---

## Technologies Used

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** PHP
- **Database:** MySQL
- **Hosting:** Apache / Nginx (via cPanel or other hosting platforms)
- **PDF Reports:** FPDF / Dompdf libraries for generating reports

---

## Installation and Setup

### Prerequisites
- PHP 7.x or higher
- MySQL server
- Apache/Nginx web server

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/AngelFincap-LoanSystem.git
   cd AngelFincap-LoanSystem
   ```
2. Download and set up the XAMPP Server
   
3. Set up the database:
   - Create a MySQL database (e.g., `brac_loan`).
   - Import the `brac_sql.sql` file into the database:
     ```bash
     mysql -u your-username -p brac_loan < brac_loan.sql
     ```

4. Configure database credentials in `config.php`:
   ```php
   $db_host = 'localhost';
   $db_user = 'root';
   $db_pass = 'your_password';
   $db_name = 'brac_loan';
   ```

5. Launch the application in your browser:
   ```
   http://localhost/AngelFincap-LoanSystem
   ```

---

## How to Use

### User Roles and Actions
1. **Borrowers**:
   - Register and apply for loans.
   - Upload documents, track loan applications, and monitor repayment schedules.

2. **Branch Officers**:
   - Manage borrower profiles and loan applications.
   - Forward applications for verification.

3. **Verifier Officers**:
   - Verify loan applications and uploaded documents.
   - Approve or reject loan requests.

4. **Head Officers**:
   - Oversee the loan process, monitor repayments, and generate reports.

### Key Features:
- Borrowers can view their liabilities and repayment status.
- Officers can monitor pending applications and borrower activities.
- Automated notifications ensure timely updates.

---

## CONTRIBUTORS

- [Dev Khurana](https://github.com/devkhurana02)
- [Manaswi Singh](https://github.com/sonderxd)



Here's a revised version of your content with added spacing between the images and descriptions to make it visually more organized:

---

## Result

Below is the **Screenshot** of the Angel Fincap Loan Management System:

---

![Screenshot 2025-01-26 182049](https://github.com/user-attachments/assets/c661bc9a-4956-45e9-a695-a606c064c50e)  

**Fig 1:** This diagram represents the Register Of the Angel Fincap Loan Management System.

---

![WhatsApp Image 2025-01-26 at 17 47 42_a1e0863e](https://github.com/user-attachments/assets/48bd7853-3251-43ae-be57-0a139042f36f)  

**Fig 2:** This diagram represents the Login Of the Angel Fincap Loan Management System.

---

![Screenshot 2025-01-26 180014](https://github.com/user-attachments/assets/d784d8f6-f57c-44b7-b9db-a2a02a4d0ff9)  

**Fig 3:** This diagram represents the Dashboard of the Branch Officer Of the Angel Fincap Loan Management System.

---

![Screenshot 2025-01-26 180150](https://github.com/user-attachments/assets/872ce17d-bb13-4280-b55d-80fb540c793e)  

**Fig 4:** This diagram represents the Add Borrow of the Branch Officer Of the Angel Fincap Loan Management System.

---

![Screenshot 2025-01-26 180318](https://github.com/user-attachments/assets/466de260-f28c-4e96-9ed7-5af823281694)  

**Fig 5:** This diagram represents the View Borrow of the Branch Officer Of the Angel Fincap Loan Management System.

---

![Screenshot 2025-01-26 180408](https://github.com/user-attachments/assets/b383e757-9d35-416b-bb0b-d9a80a7f026b)  

**Fig 6:** This diagram represents the Apply Loan to the Branch Officer Of the Angel Fincap Loan Management System.

---

![Screenshot 2025-01-26 180612](https://github.com/user-attachments/assets/58461872-df69-4c12-a51a-47dfb5f76690)  

**Fig 7:** This diagram represents the Loan Track to the Branch Officer Of the Angel Fincap Loan Management System.

---

![Screenshot 2025-01-26 180722](https://github.com/user-attachments/assets/9455cb1f-0e3c-4d75-a6aa-31ca0edc1537)  

**Fig 8:** This diagram represents the Loan Payment to the Branch Officer Of the Angel Fincap Loan Management System.

---

![Screenshot 2025-01-26 180819](https://github.com/user-attachments/assets/87486a7f-1b7f-41e1-9f84-9bc308385373)  

**Fig 9:** This diagram represents the Loan Status to the Branch Officer Of the Angel Fincap Loan Management System.

---

![Screenshot 2025-01-26 180930](https://github.com/user-attachments/assets/42afd254-7935-40b4-8d58-bdeb35962bd9)  

**Fig 9.1:** This diagram represents the Loan Status to the Branch Officer Of the Angel Fincap Loan Management System.

---

![Screenshot 2025-01-26 181007](https://github.com/user-attachments/assets/a5bba01e-fc53-4a22-917c-a0d5f7ee4a05)  

**Fig 10:** This diagram represents the Loan Report to the Branch Officer Of the Angel Fincap Loan Management System.

---

![Screenshot 2025-01-26 181049](https://github.com/user-attachments/assets/14d7c0c0-012a-44d8-bb0c-305cbbe64c3c)  

**Fig 11:** This diagram represents the Add the Property Liability to the Branch Officer Of the Angel Fincap Loan Management System.

---

![Screenshot 2025-01-26 181153](https://github.com/user-attachments/assets/a3bc59c8-ad31-4820-a9f9-a4c341edff4a)  

**Fig 12:** This diagram represents the View the Property Liability to the Branch Officer Of the Angel Fincap Loan Management System.

---

![Screenshot 2025-01-26 181153](https://github.com/user-attachments/assets/95639730-a500-45eb-8149-4a9f9bc13884)  

**Fig 13:** This diagram represents the Loan Verify Documents to the Branch Officer Of the Angel Fincap Loan Management System.

---

![Screenshot 2025-01-26 181402](https://github.com/user-attachments/assets/87f8677e-eda6-4749-bb6e-58fed58eaae7)  

**Fig 14:** This diagram represents Verifier Of the Angel Fincap Loan Management System.

---

![Screenshot 2025-01-26 181708](https://github.com/user-attachments/assets/693dc79c-dd17-4d37-bf0a-ed4a56bfbb6a)  

**Fig 15:** This diagram represents Verify By Verifier Of the Angel Fincap Loan Management System.

---

![Screenshot 2025-01-26 181812](https://github.com/user-attachments/assets/ab4fc28d-46be-46cd-b47a-17cf63b19d99)  

**Fig 16:** This diagram represents Head Officer Of the Angel Fincap Loan Management System.

---

![Screenshot 2025-01-26 181905](https://github.com/user-attachments/assets/528f6380-75f5-4fb2-953a-e152ddf0ae09)  

**Fig 17:** This diagram represents Verify By Head Officer Of the Angel Fincap Loan Management System.

---

## Contributor
- *Prince Kumar*  
  [![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue)](https://www.linkedin.com/in/prince-kumar-519a05287?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)


## License

This project is licensed under the **MIT License**.
