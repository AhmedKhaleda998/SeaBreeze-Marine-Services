# Sea Breeze: Marine Services

## Overview

Marine Services Management System is a comprehensive application designed to manage various aspects of marine services. This application caters to admins, secretaries, and accountants, each having specific roles and privileges. The frontend is built using React, providing a seamless and user-friendly interface.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [User Roles](#user-roles)
- [License](#license)

## Features

- **Employee Management**: 
  - Add, update, and remove employee records.
  - View detailed employee information including financials.

- **Shifts Management**: 
  - Schedule and manage shifts for employees.
  - View shifts associated with financial details.

- **Loans and Debts Management**: 
  - Record and manage loans given to employees.
  - Track repayments and outstanding debts.

- **Compensations, Bonuses, and Deductions**: 
  - Manage various employee financial transactions.
  - Apply bonuses, deductions, and compensations.

- **Auto Salary Calculation**: 
  - Automatically calculate employee salaries based on predefined rules.

- **Financials Management**: 
  - View and manage the financial aspects of the company.
  - Handle payments to employees.
  - Generate reports for paid and unpaid employees.
  - Track money owed by the company.

- **Payroll**: 
  - Process payroll for employees.
  - Generate and manage payroll records.

- **Reports Generation**: 
  - Generate detailed financial reports.
  - Reports for paid/unpaid employees and company debts.

## Technologies Used

- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Tokens)
- **Frontend**: React.js

## Installation

1. **Clone the repository**
    ```bash
    git clone https://github.com/AhmedKhaleda998/SeaBreeze.git
    cd SeaBreeze
    ```

2. **Install backend dependencies**
    ```bash
    cd server
    npm install
    ```

3. **Install frontend dependencies**
    ```bash
    cd client
    npm install
    cd ..
    ```

4. **Set up environment variables**
    Create a `.env` file in the root directory and add the following variables:
    ```env
    PORT=3000
    MONGODB_URI=mongodb://localhost:27017/seabreeze
    JWT_SECRET=your_jwt_secret
    JWT_EXPIRE=48h
    SALT_ROUNDS=10
    SUPER_ADMIN_PASSWORD=SeaBreeze
    SUPER_ADMIN_USERNAME=SeaBreeze
    SUPER_ADMIN_EMAIL=admin@seabreeze.com
    SUPER_ADMIN_ROLE=admin
    SUPER_ADMIN_PHONE=01000000000
    SUPER_ADMIN_SSN=20000000000000
    
    ```

5. **Run the application**
    ```bash
    npm run dev
    ```

## Usage

1. **Access the application**
    Open your web browser and navigate to `http://localhost:3000`.

## User Roles

### Admin
- Full access to all functionalities.
- Can update, delete, and manage other users.
- Oversee all financial and employee management features.

### Secretary
- Manage employee data.
- Schedule and manage shifts.

### Accountant
- View financial data.
- Handle payments and generate financial reports.

---

If you have any questions or need assistance, don't hesitate to ask for anything.

**Happy managing!**