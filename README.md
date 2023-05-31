# Student Enrollment Form

This form allows you to enroll students and store their information in the STUDENT-TABLE relation of the SCHOOL-DB database. The form includes various input fields such as Roll-No, Full-Name, Class, Birth-Date, Address, and Enrollment-Date. The primary key for the STUDENT-TABLE relation is the Roll No.

## Usage Instructions

1. On page load or any control button click, an empty form will be displayed with the cursor focused on the Roll-No field. All other fields and buttons will be disabled initially.

2. Enter the Roll No value in the Roll-No field. If the Roll No does not exist in the database, the [Save] and [Reset] buttons will be enabled, and you can move to the next field to enter the student's information.

3. Enter the required information in each field. Ensure that all fields are filled out correctly and no field is left empty.

4. Once you have completed filling in the form, click the [Save] button to store the data in the database.

5. If the Roll No already exists in the database, the existing data will be displayed in the form, and the [Update] and [Reset] buttons will be enabled. You can make changes to the fields other than the Roll-No field.

6. Modify the necessary information in the fields and ensure that all fields are valid and not left empty.

7. Click the [Update] button to update the data in the database with the modified information.

8. To reset the form and start fresh, click the [Reset] button. This will clear all the fields and disable the [Save] and [Update] buttons.

Note: The form will automatically validate that all fields are filled out correctly before allowing you to save or update the data. 

## Database Structure

The form stores data in the STUDENT-TABLE relation of the SCHOOL-DB database. The primary key for this relation is the Roll No.

The fields in the STUDENT-TABLE relation are as follows:

- Roll-No (Primary Key): The unique identifier for each student.
- Full-Name: The full name of the student.
- Class: The class in which the student is enrolled.
- Birth-Date: The birth date of the student.
- Address: The address of the student.
- Enrollment-Date: The date when the student was enrolled.

Please ensure that the database is properly set up and accessible for storing the data entered through this form.

Feel free to modify and adapt this form to suit your specific requirements or integrate it into your existing project.
