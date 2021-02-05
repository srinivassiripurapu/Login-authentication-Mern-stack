
Developed login authenication application using Mern stack.
Used mongodb to store the user credentials when user try to register.
Used express node module for setting up the server.
Used mongoose module to connect to mongodb.
Used bcryte for encrypting the passwords before storing in the database.
Used json web tokens and cookie-parser to create cookies so that user session will not end until he logout.
when the user logout, the token of the cookie was made empty and expiring the cookie. So the user session is destroyed.
Used some validations so the user details are correct and doesnt collide with other users in the database.
Used bcryte compare function to for user when he use login.
