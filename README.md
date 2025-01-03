# Mess Management System

## Project Overview
The Mess Management System is a Java-based application designed to streamline the management of mess operations in hostels. It provides an intuitive interface for administrators to manage student attendance, track mess units, generate bills, and maintain student records efficiently. The system leverages **Java Swing** for its graphical user interface and **Apache POI** for handling Excel file operations.

## Features
1. **Admin Login**
   - Secure login access restricted to administrators.

2. **Home Page**
   - Central dashboard with tile buttons for easy navigation to all features.

3. **Attendance Page**
   - Input mess units and students' mess numbers to mark attendance.
   - Automatically updates Excel sheets with the following format:
     - Column A: `Mess No.`
     - Column B: `Name`
     - Column C: `Mess Units`
     - Column D: `Total Bill`
   - Calculates the total bill using the formula:
     ```
     Total Bill = Mess Units * 0.87
     ```
   - Continuously processes data until the admin exits the page.

4. **Generate Mess Bill**
   - Saves an Excel file named "Mess Bill" on the computer for record keeping.

5. **View Student Details**
   - Displays hostel students' details in a table format for easy access and review.

6. **Edit Mess Bill**
   - Allows corrections to meal units, including adding or subtracting values.
   - Includes a "Clear Data" button to reset the month's data.

7. **Defaulter List**
   - Facilitates the creation of a defaulter list with an option to preview the Excel sheet.

## Technology Stack
- **Programming Language**: Java
- **GUI Framework**: Java Swing
- **Excel File Operations**: Apache POI (v5.2.3)

## Installation and Setup
1. **Prerequisites**:
   - Java Development Kit (JDK) 8 or higher.
   - Apache POI library version 5.2.3 (download and add to your project classpath).

2. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-repository/mess-management-system.git
   cd mess-management-system
   ```

3. **Compile and Run**:
   - Compile the project:
     ```bash
     javac -cp .;poi-5.2.3.jar;poi-ooxml-5.2.3.jar *.java
     ```
   - Run the application:
     ```bash
     java -cp .;poi-5.2.3.jar;poi-ooxml-5.2.3.jar Main  
   ```

4. **Excel Files Connected**:
   - The Excel files connected with this project should be saved in 'D' because of the location given in the program.

## Usage
1. Launch the application and log in using the admin credentials.
2. Navigate through the Home Page to access various features.
3. Use the Attendance Page to input daily mess data.
4. Generate and save bills using the "Generate Mess Bill" feature.
5. View and edit student details as needed.
6. Use the "Defaulter List" feature to manage and review defaulters.

## Design
- **Theme**: Light blue color scheme with consistent text formatting.
- **UI Elements**: Simple and user-friendly interface for seamless navigation.

## Contribution
Contributions are welcome! Follow these steps to contribute:
1. Fork the repository.
2. Create a new branch for your feature:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Added feature-name"
   ```
4. Push to your branch:
   ```bash
   git push origin feature-name
   ```
5. Create a Pull Request.


## Contact
For questions or suggestions, feel free to reach out:
- **Name**: Affan Yasir
- **Email**: affanyasir16@gmail.com
- **LinkedIn**: http://www.linkedin.com/in/affanyasir

---
Thank you for using the Mess Management System! Your feedback is invaluable.

