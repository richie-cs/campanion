Live Demo
To see the app in action, go to https://dashboard.heroku.com/apps/stark-river-10366

Features
Authentication:

User login with username and password

Admin sign-up with admin code

Authorization:

One cannot manage posts and view user profile without being authenticated

One cannot edit or delete posts and comments created by other users

Admin can manage all posts and comments

Manage campground posts with basic functionalities:

Create, edit and delete posts and comments

Upload campground photos

Display campground location on Google Maps

Search existing campgrounds

Manage user account with basic functionalities:

Password reset via email confirmation (disabled)

Profile page setup with sign-up

Flash messages responding to users' interaction with the app

Responsive web design

Custom Enhancements
Update campground photos when editing campgrounds

Update personal information on profile page





Getting Started
This app contains API secrets and passwords that have been hidden deliberately, so the app cannot be run with its features on your local machine. However, feel free to clone this repository if necessary.




Built with
Front-end
ejs
Google Maps APIs
Bootstrap
Back-end
express
mongoDB
mongoose
async
crypto
helmet
passport
passport-local
express-session
method-override
nodemailer
moment
cloudinary
geocoder
connect-flash
Platforms
Heroku


#Add Mongoose
* Install and configure Mongoose
* Setup campground model
* Use campground model inside of our rouotes

#Show Page
* Review the RESTful routes 
* Add description to our campground model
* Show db.collection.drop()
* Add a show route/template


#Refactor Mongoose Code
* Create a models directory
* Use module.exports
* Require everything Correctly

#Add Seeds file
* Add a seeds.js file
* Run the seeds file everytime the server restarts

#Add the Comment Model
* Make our errors go away
* Display comments on campground show page

#Comment New/Create
* Discuss nested routes
* Add the comment new and create routes
* Add the new comment form

#Style Show Page
* Add sidebar to show page
* Display comments nicely

##Finish Styling Show page
* Add public directory
* Add custom stylesheet

##Auth Pt. 1 - Add User Model
* Install all packages needed for auth
* Define User model

##Auth Pt. 2 - Register
* Configure Passport
* Add register routes
* Add register template

##Auth Pt. 3 - Login
* Add login routes
* Add login template

##Auth Pt. 4 -Logout/Navbar
* Add logout route
* Prevent user from adding a comment if not signed in
* Add links to navbar
* Show/hide auth links correctly

##Auth Pt. 5 - Show/Hide links
* Show/hide auth links in navbar correctly

##Refactor The Routes
* Use Express router to reorganize all routes

##Users + Comments
* Associate users and comments
* Save author's name to a comment automatically


##Users + Comments
* Associate users and comments
* Save author's name to a comment automatically

##Users + Campgrounds
* Prevent an unaunthenticated user from creating a campground 
* Save username+id to newly created campground

#Editing Campgrounds
* Add Method-Override
* Add Edit Route for Campgrounds
* Add link to Edit page
* Add Update Route
* Fix $set problem

#Deleting Campgrounds
* Add Destroy Rouote
* Add Delete button


#Authorization 
* User can only edit his/her campgrounds
* User can only delete his/her campgrounds
* Hide/Show edit and delete buttons

#Deleting Comments
* Add Destroy route
* Add Delete button

#Authorization Part: Comments
* User can only edit his/her comments
* User can only delete his/her comments
* Hide/Show edit and delete buttons
* Refactor Middleware

#Authorization Part 2: Comments
* User can only edit his/her comments
* User can only delete his/her comments
* Hide/Show edit and delete buttons
* Refactor Middleware

#Adding in Flash!
* Demo working version
* Install and configure connect-flash
* Add bootstrap alerts to header











