# Sales-Management-System

## Project Overview 

*Note: Due to confidentiality agreements, full source code is not publicly available.*

This project showcases the backend system I developed during my internship, designed to streamline sales performance monitoring. It provides management with insights through multi-filter analytics (owner, platform, date range). The system prioritizes data accuracy with validation access for sales entries and ensures secure operations via a role-based access control system and a WhatsApp OTP flow for password recovery and user setup.

## Key Features & Functionalities

This system provides a comprehensive suite of features:

   **Real-time Sales Dashboard:** Management gains immediate insights into key sales metrics (sum of sales, orders, AOV) across configurable timeframes (daily, monthly, quarterly, yearly).
   
   **Sales & Target Recording:** Employees can accurately record sales figures and targets, supported by robust input validation and access control to ensure data integrity and authorized data entry.
   
   **Advanced Data Viewing & Management:** Users can track sales and targets with flexible filtering (date range, multiple owners/platforms), quick search, and efficient in-line editing capabilities. Data is presented with pagination and customizable display options.
   
   **Organizational Management:** Streamlined administration for creating and managing groups and owners, defining the structure of sales territories or business units.
   
   **User Administration & Permissions:** Administrators can create new user accounts, set up profiles (username, phone number), and assign specific owner access through an intuitive group and team-based workflow.
   
   **Enhanced Security:** Implemented secure One-Time Password (OTP) process via WhatsApp API for first-time logins and password resets.

## Screenshots

  *(Screenshots below use dummy data for demonstration purposes.)*

### Sales Dashboard Overview
<p align="center">
  <img src="images/dashboard.png" width="500">
</p>

<p align="center">
 <em>Illustrates the interface for management to monitor the sales performance against target</em>
</p>

### Sales Data Table with Filters
<p align="center">
  <img src="images/sales_list.png" width="500">
</p>

<p align="center">
<em>Illustrates the interface to see the sales data keyed</em>
</p>

### Sales Data Entry Form
<p align="center">
  <img src="images/edit_sales_target.png" width="500">
</p>
<p align="center">
<em>Illustrates the interface for employees to record sales data, including validation prompts.</em>
</p>

### User Administration & Permissions
<p align="center">
  <img src="images/create_user.png" width="500">
</p>

<p align="center">
  <img src="images/team_member_access.png" width="500">
</p>
<p align="center">
<em>Demonstrates the process for administrators to create users and assign owner access.</em>
</p>

### OTP Flow

<div align="center" style="display: flex; justify-content: center; gap: 15px; flex-wrap: wrap;">
  <div style="display: flex; flex-direction: column; align-items: center; height: 400px; justify-content: flex-end;">
    <img src="images/forgot_password.png" width="200" alt="OTP Step 1: Enter Username">
    <p style="margin-top: 5px;">Step 1: Choose Forgot Password</p>
  </div>
  <div style="display: flex; flex-direction: column; align-items: center; height: 400px; justify-content: flex-end;">
    <img src="images/otp_verfification_error message.png" width="200" alt="OTP Step 2: Enter Phone Number">
    <p style="margin-top: 5px;">Step 2: Enter Username & Phone Number</p>
  </div>
  <div style="display: flex; flex-direction: column; align-items: center; height: 400px; justify-content: flex-end;">
    <img src="images/user_verification_error message.png" width="200" alt="OTP Step 3: Enter OTP">
    <p style="margin-top: 5px;">Step 3: Enter OTP</p>
  </div>
  <div style="display: flex; flex-direction: column; align-items: center; height: 400px; justify-content: flex-end;">
    <img src="images/change_password.png" width="200" alt="OTP Step 4: Set New Password">
    <p style="margin-top: 5px;">Step 4: Set New Password</p>
  </div>
</div>

<p align="center">
<em>Demonstrates the process to reset password and setup new user, including validation prompts.</em>
</p>

## Technical Stack

   **Server-Side Language:** PHP
   
   **Database:** MySQL
   
   **API Style:** REST API
   
   **Client-Side:** JavaScript, HTML, CSS

## My Contributions

*   Developed backend API endpoints for data processing and management.
*   Wrote and optimized SQL queries for efficient data retrieval and updates.
*   Implemented robust input validation and access control logic.
*   Integrated with external services (WhatsApp API for OTP).
*   Contributed to backend system design and performance improvements.
