# Hospital Management System

## Overview
The Hospital Management System is a comprehensive web-based application designed to streamline and optimize the administrative, operational, and patient care processes of a hospital. The system enables efficient management of patients, doctors, appointments, medical records, and billing. Built with scalability and user-friendliness in mind, this system aims to enhance the overall experience for both staff and patients.

## Features
1. **Patient Management**:
   - Register and maintain patient records.
   - View patient history and medical reports.
   - Appointment scheduling with doctors.

2. **Doctor Management**:
   - Maintain doctor profiles and specialties.
   - Manage doctor schedules and availability.

3. **Appointment System**:
   - Online booking and rescheduling of appointments.
   - Automated notifications and reminders.

4. **Billing and Payment**:
   - Generate detailed invoices.
   - Support for multiple payment methods.

5. **Administrative Dashboard**:
   - Analytics and reporting tools for hospital administrators.
   - Role-based access control for secure data management.

## Technology Stack
- **Frontend**: React.js
- **Backend**: Spring Boot
- **Database**: PostgreSQL
- **Containerization**: Docker
- **Version Control**: Git

## Team Members
This project is collaboratively developed by the following team members:

1. **Bui Xuan Thang** - Project Manager
   - Responsible for overall project coordination, task allocation, and timeline management.

2. **Duong Thanh Phat** - Backend Developer
   - Focused on building RESTful APIs, database design, and server-side logic.

3. **Nguyen Dac Thang** - Frontend Developer
   - Responsible for designing and implementing the user interface using React.js.

4. **Nguyen Ngoc Quy** - QA Engineer
   - Ensures the quality of the application through rigorous testing and debugging.

5. **Nguyen Tuan Huy** - DevOps Engineer
   - Responsible for CI/CD pipeline setup, server management, and application deployment.

6. **Pham Dinh Hao** - UX/UI Designer
   - Focused on designing user-friendly and accessible interfaces for the application.
     
## Installation and Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/itstee2k3/medical-be.git
   ```

2. Navigate to the project directory:
   ```bash
   cd medical-be
   ```

### Without Docker
1. Install dependencies:
   ```bash
   npm install
   ```

2. Create an admin account:
   ```bash
   npm creataAdmin
   ```
   *This creates a user admin for login. Account: admin@gmail.com / Password: 123456.*

3. Start the development server:
   ```bash
   npm run dev
   ```

### With Docker
1. Build and run the application using Docker Compose:
   ```bash
   docker-compose up -d
   ```

2. Access the application at `http://localhost:3000`.

## Contribution Guidelines
We welcome contributions from all team members. Please follow these steps:
1. Create a new branch for each feature or bug fix.
2. Ensure your code follows the project's coding standards.
3. Submit a pull request with a clear description of the changes made.

## Future Enhancements
- Integration with third-party services for telemedicine.
- Advanced reporting and analytics dashboards.
- Mobile application support for patients and staff.

## Contact
For any queries or support, please contact:
- Email: xthang.lib@gmail.com
- Phone: +84 522 383 757

---
We aim to deliver a robust and user-friendly hospital management solution that meets the needs of modern healthcare facilities.

