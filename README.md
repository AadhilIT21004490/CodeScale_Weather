# CodeScale_Weather - Aadhil Shihabdeen

This server-side development outline describes the creation of a Node.js API with key functionalities such as storing user details and locations in a MongoDB database, providing routes for data retrieval, and automatically sending weather reports to users' emails every 3 hours using Nodemailer and Gmail. This server-side application, built using Express.js and Mongoose, lays the foundation for a robust system capable of managing user data and delivering timely weather updates while adhering to best practices in error handling, validation, and scalability. The outlined steps encompass the essential components required for building a fully functional backend system for a weather notification service.

In this Application there are totally 4 API endpoints are avaialable, those 4 API endpoints are grouped into 2 groups those are,
Authentication - This will contain basic user authentication related API endpoints for user login and new user Registration
Location - This will contain Location related API endpoints such as Update the Location of user and retrive a Location and weather detail based on the date

The Authentication Group has 2 API endpoints Those are,
Login - First of all a user must login to the system to experience the features of the application, so this endpoint will work as the main page of this application. for that a user must provide his username and password which he used to register him self in this application
Register - if User is new to the application, he should create an account in the application by providing a valid username and a password. to acheive this task this API endpoint will be useable

The Location Group also has 2 API endpoints Those are,
Update - This API endpoint will be usable when the user try to enter his location data( his city name) for the first time in this application. also he can use this Endpoint to Update his location whenever needed. So he needs to provide his location data as a input through the body
Fetch - this will be usable to retrive the user's specific user data along with weather on a specifc day. to acheive this he need to enter the data in body as a JSON formate to fetch the relevent data.

