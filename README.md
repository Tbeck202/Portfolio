# Portfolio

This is a repository of my favorite projects that I have completed up to this point. This includes the project I worked on during my internship an Prosper IT consulting.  

My work done on these project is outlined below.

Fist, and most obvious, is my portfolio site.  I designed my site from scratch with a mobile first approach and pure HTML & CSS.  You can visit my site [here](http://202code.com/).

Next I'd like to point you towards a web application that calculates the total cost of a pizza order.  This site was built with HTML, CSS & Javascript, with Javascript handling the logic performing the calculations.  You can view and demo this site [here](http://202code.com/pizzaSite/index.html).

Next, I'd point you towards a .NET MVC application that calculates a quote for car insurance based upon user input. The inputs and quotes are then stored in a SQL database which can be displayed upon request. For this site, I used HTML (with Bootstrap 4), c# for the logic, and the enitity framework to handle database queries. The site will be hosted for demo soon, but until then the code for this project can be seen [here](https://github.com/Tbeck202/C-Sharp-Coding-Projects/tree/master/InsuranceQuoteApp).

Lastly, and maybe most importantly, is my participation in a live coding project which is outlined below.

# Internship project description

After completing all of the required coursework in the Tech Academy curriculum, I had the opportunity to take an internship working on a legacy .net MVC application. I really enjoyed being able to put my skills to the test on both front and back end user stories to make updates, add features, and improve the over all user experience of the app. This project had been worked on by my peers for some time before I was able to jump in and as such, I gained valuable experience in working with version control, de-bugging, and develpoing in a team environment.  After taking time to familiarize myself to the code base, I was able to get to work and complete the following User stories.

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

As an admin of this application, you have the ability to create a user name for new users, who will then register in the app and claim this username. These unregistered users are stored in a seperate database from the registered users and there was no way to view unregistered users. It was my job to update the index and create a view for unregistered users that the admin could view.  The admin would then be able to view all application users, including those that had not yet registered their username.
#### Index page
I added the third Div in which the UnregisteredUser partial view is called.
![All user index screenshot](https://github.com/Tbeck202/C-Sharp-Coding-Projects/blob/master/LiveProject/UserListIndex.png?raw=true "Index Page")
#### Controller method
This is the controller method for the UnregisteredUser partial view
![All user index screenshot](https://github.com/Tbeck202/C-Sharp-Coding-Projects/blob/master/LiveProject/UnregisteredUserContollerMethod.png?raw=true "Controller Method")
#### Partial View
This is UnregisteredUser the partial view
![All user index screenshot](https://github.com/Tbeck202/C-Sharp-Coding-Projects/blob/master/LiveProject/UnregisteredUsersView.png?raw=true "Controller Method")

## Overall summary
After completing this sprint, I have have a better understanding of .NET MVC applications and how they work. I was challenged to find solutions to real-world problems and was required to use practical problem solving skills in order to find these solutions. There were certainly times in this project that I struggled with the things I didn't understand, but I really enjoyed the ups and downs and the thrill of overcoming those struggles. I'm excited to take this experience and build upon it as I continue to learn and expand my skill set as a programmer.
