# Live project summary

After completing all of the required coursework in the Tech Academy curriculum, I had the opportunity to participate in a two-week code sprint working on a .net MVC application. I really enjoyed being able to put my skills to the test on both front and back end user stories to make updates, add features, and improve the over all user experience of the app. This project had been worked on by my peers for some time before I was able to jump in and as such, I gained valuable experience in working with version control, de-bugging, and develpoing in a team environment.  After taking time to familiarize myself to the code base, I was able to get to work and complete the following User stories.

## Adding a "Back/cancel" Button

The Account/NewUser & Account/Login pages had no way to navigate back to the previous page. It was my task to implement this button to add the required functionality.
![Back button screenshot](https://github.com/Tbeck202/C-Sharp-Coding-Projects/blob/master/LiveProject/BackButtonMVC.png?raw=true "Suspended Checkboxes")


## Adding a checkbox to partial user view

Inside the User List Partial view, I was tasked with adding a checkbox that would bind to the "Suspended" property for a User in order to allow an admin to set that User to suspended if needed. 
![Suspended Checkbox screenshot](https://github.com/Tbeck202/C-Sharp-Coding-Projects/blob/master/LiveProject/SuspendUserCheckBox.png?raw=true "Suspended Checkboxes")

## Refactor "Company News controller" JS call

The application has a "Company news" page where an admin can create a news article.  The developer that created this page, included server-side date validation that would return an error if the admin tried to set the date of the news article to a date in the past.  They did this by checking the date input in the controller and then returning a JavaScript alert.  It was my job to do this validation on the client side before any data is passed to the database. I used Javascript and Jquery to compare the date values and return an alert.
![Company news controller screenshot](https://github.com/Tbeck202/C-Sharp-Coding-Projects/blob/master/LiveProject/DateValidationJs.png?raw=true "Suspended Checkboxes")

## Phone-call from the dashboard

Employee's phone numbers are displayed on the user list partial view layout page. I was tasked with adding the functionality to allow an Admin to click and call an employee directly from the dashboard. 
![Phone call from dashboard screenshot](https://github.com/Tbeck202/C-Sharp-Coding-Projects/blob/master/LiveProject/MakePhoneNumberClickableFromView.png?raw=true "Suspended Checkboxes")

## All user index page

As an admin of this application, you have the ability to create a user name for new users, who will then register in the app and claim this username. These unregistered users are stored in a seperate database from the registered users and there was no way to view unregistered users. It was my job to create an index view for the admin of all application users, including those you had not yet registered their username.
#### Index page
![All user index screenshot](https://github.com/Tbeck202/C-Sharp-Coding-Projects/blob/master/LiveProject/UserListIndex.png?raw=true "Index Page")
#### Controller method
![All user index screenshot](https://github.com/Tbeck202/C-Sharp-Coding-Projects/blob/master/LiveProject/UnregisteredUserContollerMethod.png?raw=true "Controller Method")
#### Partial View
![All user index screenshot](https://github.com/Tbeck202/C-Sharp-Coding-Projects/blob/master/LiveProject/UnregisteredUsersView.png?raw=true "Controller Method")
