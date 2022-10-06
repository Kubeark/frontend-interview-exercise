# frontend-interview-exercise


# Goal

Create a React JS application using webhooks that will have the following frameworks/npm packages: NextJS, AntD, Recoil and SAAS.

# The Task

You are required to create a page that will have a table with different entries. It must:

* contain a way to add new entries
* contain a way to edit or delete entries
* adding a new entry it should be done through a form


# Mandatory Work

The form should contain the following form items:

* Username (type: input | mandatory: yes | pattern: yes, lowercase letter, uppercase letters, !@#, and numbers | rules: min char: 4, max char: 80 | validation: yes)
* First name (type: input | mandatory: yes | pattern: yes, lowercase letter, uppercase letters and ' | rules: min char: 2, max char: 80 | validation: yes)
* Last name (type: input | mandatory: yes | pattern: yes, lowercase letter, uppercase letters and ' | rules: min char: 2, max char: 80 | validation: yes)
* Gender (type: Switch | mandatory: no)
* Date of birth (type: date picker | mandatory: yes | rules: only dates that are 18 years ago or more from current date | validation: yes)
* Address (type: input | mandatory: no)
* City (type: input | mandatory: no)
* Register to newsletter (type: Checkbox | mandatory: no)
* Country (type: dropdown | mandatory: no | rules: add a max 10 EU countries)
* Phone (type: input | mandatory: no | rules: country code, phone number)
* Details (type: textarea | mandatory: no)
* Hobbies (type: textarea | mandatory: no)

All the entries will be kept on localstorage or in a state management

Give github users `mirceaKA|cr8or1|tadrian88` access to your fork.
Feel free to ask questions as you go if anything is unclear, confusing, or just plain missing.

# Extra Credit

Add by default some entries by using a JSON Mockup or another way.
The table should have the following:
 * visible columns: Index, Username, Gender, Date of Birth, City, Newsletter, Country, Phone, Hobbies
 * sorting: Username, Gender, Date of Birth, City, Country
 * filter: Username, Gender, City, Country, Phone, Hobbies

