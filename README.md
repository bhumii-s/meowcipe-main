# Meowcipe

Meowcipe is a full-stack web application developed to create an online platform where users 
can share, browse, and save culinary recipes. The project highlights core concepts of full
stack development, integrating modern backend and frontend technologies to build an 
interactive and user-friendly system. 
The backend is built using Node.js and Express.js, with MongoDB as the database and 
Mongoose for structured data modelling. It offers RESTful APIs for user authentication, 
recipe management, and email subscription. User authentication is handled securely using 
sessions and bcrypt, while image uploads for recipes are managed with Multer. The system 
also allows users to save their favourite recipes and subscribe to newsletters through Mailgun. 
The frontend consists of static HTML pages served by the backend, with dynamic features 
powered by jQuery and AngularJS. The interface is styled using Bootstrap and custom CSS 
to ensure responsiveness and usability across devices. 
This project aims to demonstrate the integration of backend APIs with a responsive frontend, 
showcasing essential aspects of web application development including security, interactivity, 
and database integration.

## Project Goal.

**1.** Develop a Functional Recipe Sharing Platform: Create a working web application 
where users can successfully register, log in, submit, browse, view, and save recipes. 

**2.** Implement Secure User Authentication: Ensure secure user registration and login 
processes, including password hashing and session management to protect user 
accounts. 

**3.** Build a Robust Backend API: Design and implement a RESTful API using Node.js 
and Express to handle all data operations related to users, recipes, and saved items. 
**.** Utilize MongoDB for Data Persistence: Effectively use MongoDB and Mongoose to 
model, store, and retrieve application data, including user credentials, recipe details, 
and saved recipe associations. 

**4.** Create an Interactive Frontend: Develop a user-friendly interface using HTML, CSS, 
Bootstrap, and client-side JavaScript (jQuery/AngularJS) that allows users to easily 
interact with the platform's features. 

**5.** Enable Recipe Management: Allow authenticated users to upload new recipes with 
images, view their own submitted recipes, and delete them. Provide functionality for 
all users to browse and view recipe details.

**6.** Implement Recipe Saving Feature: Allow logged-in users to save recipes they like and 
view their collection of saved recipes.

**7.** Integrate Email Functionality: Implement a feature for users to subscribe to a 
newsletter, sending confirmation/welcome emails using Mailgun. 

**8.** Demonstrate Full-Stack Development Skills: Showcase proficiency in integrating 
backend (Node.js, Express, MongoDB) and frontend (HTML, CSS, JS) technologies 
to build a complete web application. 

**9.** Ensure Code Modularity and Maintainability: Structure the backend code logically 
using Express routers and service layers for better organization and ease of future 
development. 

## Technology Stack 

### Backend:

o Runtime: Node.js 

o Framework: Express.js 4.x 

o Language: JavaScript (ES Modules) 

o Database ORM/ODM: Mongoose 8.x 

o Authentication: express-session (Session Management), bcrypt (Password 
Hashing) 

o File Uploads: multer 

o Environment Variables: dotenv 

o Email Service Integration: mailgun.js, form-data 

### Frontend: 

o Markup: HTML5 

o Styling: CSS3, Bootstrap 5.x 

o Client-Side Scripting: JavaScript (ES6+), jQuery 3.6+, AngularJS 1.8.x (used 
in specific pages like savedRecipes2.html) 

o Rich Text Editing: Quill.js (for recipe instructions) 

### Database: 

o MongoDB (locally hosted on mongodb://localhost:27017/dishDB) 

### Development/Runtime: 

o Package Manager: npm 

o Server: Node.js integrated HTTP server

