
## Summary (Summarize the bug encountered concisely)

Test Case 1: Login With Valid Credential
Summary: The login page does not accept valid credentials.

Test Case 2: Create Blank Project
Summary: The create project page does not allow users to create a blank project.

Test Case 3: Update Name of Template Project
Summary: The update project page does not allow users to update the name of a template project.

## Steps to reproduce     
Test Case 1
Open a web browser and navigate to https://gitlab.com: https://gitlab.com.
Click on the "Sign in" button.
Enter a valid username and password.
Click on the "Log in" button.

test case 2
Open a web browser and navigate to https://gitlab.com: https://gitlab.com.
Click on the "New project" button.
Select the "Blank project" option.
Enter a valid project name and description.
Click on the "Create project" button.

Test Case 3:
Open a web browser and navigate to https://gitlab.com: https://gitlab.com.
Create a new template project.
Go to the project's settings page.
Click on the "Edit project name" button.
Enter a new project name.
Click on the "Save changes" button.


## What is the current bug behavior?
Test Case 1
The user should be logged in and redirected to the dashboard
Test Case 2
The blank project is not created. The user is met with the error message "Project with this name already exists".

Test Case 3
The project name is not updated. The user is met with the error message "The project name is invalid".

## What is the expected correct behavior?
Test Case 1
The user should be logged in and redirected to the dashboard.

Test Case 2
The blank project should be created and the user should be redirected to the project's dashboard.

Test Case 3
The project name should be updated and the user should see the new name reflected in the project's UI.
     
## Relevant logs and/or screenshots

 Test Case 1     
Invalid login or password

Test Case 2
Project with this name already exists

Test Case 3
The project name is invalid

## Possible fixes
Test Case 1
Check the validation logic for the login form.
Ensure that the correct username and password are being entered.

Test Case 2
Check the code that validates project names for uniqueness.
Ensure that the project name is unique before creating the project.

Test Case 3
Check the validation logic for project names.
Ensure that the new project name meets the requirements.

## Whom do you report/ Assign To/ Tags
Test Case 1,2 and 3
project manager


## Priority
Test Case 1,2 and 3
Medium

      
