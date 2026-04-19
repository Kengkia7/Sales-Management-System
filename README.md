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
  <img src="https://github.com/user-attachments/assets/77b38bcc-ee17-477a-9074-4b933ecd7446" width="500">
</p>

<p align="center">
 <em>Illustrates the interface for management to monitor the sales performance against target</em>
</p>

### Sales Data Table with Filters
<p align="center">
  <img src="https://github.com/user-attachments/assets/121d8c0f-0358-4fe7-8dbd-e5927f12b25e" width="500">
</p>

<p align="center">
<em>Illustrates the interface to see the sales data keyed</em>
</p>

### Sales Data Entry Form
<p align="center">
  <img src="https://github.com/user-attachments/assets/ffad15bb-adff-484f-90bf-81f6ddbbcb5a" width="500">
</p>
<p align="center">
<em>Illustrates the interface for employees to record sales data, including validation prompts.</em>
</p>

### User Administration & Permissions
<p align="center">
  <img src="https://github.com/user-attachments/assets/29323a0e-8df5-4393-830a-fdbc42b22fce" width="500">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/2afad28c-3a7b-4c57-a5c3-90a2e2a865c7" width="500">
</p>
<p align="center">
<em>Demonstrates the process for administrators to create users and assign owner access.</em>
</p>

### OTP Flow

<p align="center">
  <!-- Step 1 -->
  <img src="https://github.com/user-attachments/assets/e5bc2429-2a59-4993-9c69-02bc07ab834d" width="200" height="250" alt="OTP Step 1: Enter Username" style="vertical-align: bottom; margin-right: 15px;">
  <!-- Step 2 -->
  <img src="https://github.com/user-attachments/assets/79be9dcc-82d4-43cb-b6ae-80f6fdf60bfb" width="200" height="250" alt="OTP Step 2: Enter Phone Number" style="vertical-align: bottom; margin-right: 15px;">
  <!-- Step 3 -->
  <img src="https://github.com/user-attachments/assets/82b28381-c862-4fb2-965b-0cd56d990923" width="200" height="400" alt="OTP Step 3: Enter OTP" style="vertical-align: bottom; margin-right: 15px;">
  <!-- Step 4 -->
  <img src="https://github.com/user-attachments/assets/471f7225-1fa9-46e6-8d65-e809fe440f2e" width="200" height="250" alt="OTP Step 4: Set New Password" style="vertical-align: bottom;">
</p>

<p align="center">
<em>Demonstrates the process to reset password, including validation prompts.</em>
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
