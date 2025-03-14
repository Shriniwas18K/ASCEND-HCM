# Ascend HCM
<img width="286" alt="ascend-hcm-medium-sized" src="https://github.com/user-attachments/assets/93111b76-c369-4191-860c-5377ee006b79" />

### Overview
This project is a Human Capital Management (HCM) system built using Java EE 8, inspired by Oracle HCM. It aims to provide a comprehensive solution for managing HR processes, including employee data management, payroll, and talent management.

## Features
- Employee Data Management
- Payroll Processing
- Talent Management
- Role-Based Access Control
- RESTful APIs for Integration
- User-Friendly Interface

## Prerequisites
- Java Development Kit (JDK) 8 or higher
- Java EE 8 compatible application server (e.g., WildFly, GlassFish)
- Oracle Database or any other compatible database
- Maven or Gradle for build automation

## Installation

1) Clone the repository:
```bash
git clone https://github.com/Shriniwas18K/ascend-hcm.git
cd ascend-hcm
````

2) Configure the database connection:
- Update the src/main/resources/META-INF/persistence.xml file with your database connection details.

3) Build the project:
```bash
mvn clean install
```

4) Deploy the application to your application server:
- Copy the generated WAR file from the target directory to the deployment directory of your application server.
- Start the application server and access the application at http://localhost:8080/ascend-hcm.

## Usage
- Employee Data Management:
-- Add, update, and delete employee records.
-- View employee details and history.
- Payroll Processing:
-- Generate payroll reports.
-- Process employee salaries and deductions.
- Talent Management:
-- Track employee performance.
-- Manage employee training and development.
- Role-Based Access Control:
-- Assign roles and permissions to users.
-- Ensure secure access to sensitive data.

## API Documentation
The application provides RESTful APIs for integration with other systems. The API documentation can be accessed at http://localhost:8080/ascend-hcm/api-docs.

## Contributing
Contributions are welcome! Please fork the repository and submit pull requests.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

## Acknowledgements
- Inspired by Oracle HCM
- Built using Java EE 8
