# Frontend interview exercise


# Goal

Create a React JS application using react hooks that will have the following frameworks/npm packages: NextJS, AntD, Recoil and SASS (SCSS).

# The Task

As an assignment, your task is to design a webpage with a table consisting of various entries. 
The page must provide options to add new entries, edit or delete existing entries. 
Moreover, for adding a new entry, the page should include a form to fill in the required details.


# Mandatory Work

The items required in the form are as follows:

- Username (Input type, required field, pattern must include lowercase letters, uppercase letters, !@#, and numbers, with a character limit of 4 to 80, and validation must be enabled)
- First name (Input type, required field, pattern must include lowercase letters, uppercase letters, and ' , with a character limit of 2 to 80, and validation must be enabled)
- Last name (Input type, required field, pattern must include lowercase letters, uppercase letters, and ' with a character limit of 2 to 80, and validation must be enabled)
- Gender (Switch type, not mandatory)
- Date of birth (Date picker type, required field, only accepts dates that are 18 years ago or more from the current date, and validation must be enabled)
- Address (Input type, not mandatory)
- City (Input type, not mandatory)
- Register to newsletter (Checkbox type, not mandatory)
- Country (Dropdown type, not mandatory)
- Phone (Input type, not mandatory, must include country code and phone number)
- Details (Textarea type, not mandatory)
- Hobbies (Textarea type, not mandatory)

 All entries will be stored either on local storage or in a state management system.

Give github users `cr8or1 | Kurounin | SeekerS11` access to your fork.
Feel free to ask questions as you go if anything is unclear, confusing, or just plain missing.

# Extra Credit

To begin with, some entries should be added by default using a JSON Mockup or any other relevant method. 

The table should consist of the following: 
- Visible columns: The table must display the columns in the following order: Index, Username, Gender, Date of Birth, City, Newsletter, Country, Phone, and Hobbies. 
- Sorting: It should be possible to sort the data in the table based on Username, Gender, Date of Birth, City, and Country columns. 
- Filter: The table should offer the ability to filter data based on Username, Gender, City, Country, Phone, and Hobbies.

