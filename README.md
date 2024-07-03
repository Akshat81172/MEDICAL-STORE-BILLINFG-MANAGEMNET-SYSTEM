# MEDICAL-STORE-BILLINFG-MANAGEMNET-SYSTEM

1. INTRODUCTION: 
The Medical Store Management System is a Python-based desktop application developed using 
the Tkinter library for the graphical user interface. It serves as a comprehensive solution for 
managing patient information, including personal details, medical history, and prescription 
records. The system allows users to submit patient information, add medicine details, and 
generate reports in both PDF and Excel formats.

3. TOOLS AND TECHNOLOGIES: 
- Programming Language: Python 
- GUI Library: Tkinter 
- External Libraries: openpyxl, tkcalendar, filedialog, reportlab
- 
3. APPLICATION STRUCTURE: 
The application is structured into several frames and sections, each serving a specific purpose: 
- Main Frame: 
 - Accepts patient information such as name, age, gender, hospital, country, and phone number. 
 - Provides options to submit, clear, and access the medicine entry frame. 
- Medicine Entry Frame: 
 - Allows the user to add medicine details, including name, quantity, per-price, and total price. 
 - Displays a running total of the grand price. 
 - Options to calculate and display the total price and grand total. 
 - Buttons to add, clear, submit, print, go back, and exit.
 - 
4. FUNCTIONALITY:
- User Authentication: 
 - Validates user inputs for patient details (name, age, gender, etc.). 
 - Ensures proper formatting and completeness of data. 
- Data Storage: 
 - Stores patient information, including medicine details, in an Excel file 
(`registration_data.xlsx`). 
 - Uses openpyxl for Excel file manipulation. 
- Report Generation: 
 - Generates a detailed PDF report with patient and medicine details. 
 - Utilizes the reportlab library for PDF creation.

 - 
5. OUTPUT: 
- The system outputs a PDF report containing patient information, medicine details, and the 
grand total. 
- Excel file (`registration_data.xlsx`) is updated with each new patient entry. 
