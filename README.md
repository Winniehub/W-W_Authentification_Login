# W-W_Authentification_Login and Register
# W&W Login And Register With JSON Web Token - Authentication System

![login register W&W 1](https://github.com/Kuzma02/MERN-Login-And-Register-With-JSON-Web-Token/assets/138793624/057541be-e8ab-4489-996d-117290a85c5a)

![login register W&W 2](https://github.com/Kuzma02/MERN-Login-And-Register-With-JSON-Web-Token/assets/138793624/364c6008-e211-4796-a745-5829f158e441)

![login register W&W 3](https://github.com/Kuzma02/MERN-Login-And-Register-With-JSON-Web-Token/assets/138793624/403f9988-3970-4b38-9de5-4469ff163164)

# A Deep Dive into W&W App with Authentication
Building upon the foundational principles of MongoDB, Express, React, and Node.js, my project offers a detailed implementation of W&W login register functionality. 
By integrating JWT authentication W&W stack techniques, I ensure a secure and seamless user experience.

# W&W Login Signup Flow
My application simplifies the complexity of the W&W login signup process. The auth flow is intuitive, providing clear navigation from signing up to signing into the application. This makes my project an excellent login app example for developers seeking to 
understand the intricacies of authentication flows.

# W&W Boilerplate with Authentication
I've constructed this repository as a W&W boilerplate with authentication, so you can fork it, extend it, and build upon it to create your own applications. It serves as a W&W stack login template, showcasing best practices in W&W user authentication.

# Design and User Experience
With a focus on login app design, the front-end features a React login page template that is not only functional but also aesthetically pleasing. This application is not just an authentication W&W stack demonstration but also a testament to thoughtful design in creating engaging user interfaces.

# Authentication for React App
The authentication for react app mechanism is implemented with security and efficiency in mind. I utilize JWTs (JSON Web Tokens) to manage sessions and secure user data, providing a reliable and robust auth W&W structure.

# W&W Authentication JWT
Incorporating W&W authentication JWT within this W&W stack application example ensures that the tokens used for user sessions are managed according to the latest security standards. It's a critical feature that underscores the entire authentication process in my W&W application example.

# Comprehensive Learning Resource
This repository is more than just a W&W login and register system. It is an educational tool for understanding user authentication React methods and W&W stack authentication strategies. I aim to provide a solid understanding of how authentication integrates within a W&W stack app, offering developers a practical W&W authentication tutorial.

# Features
- User Registration: Allows new users to create an account.
- User Login: Enables users to log in with their credentials.
- JWT Authentication: Secures user sessions using JSON Web Tokens.
- Responsive Design: Ensures a great user experience across various devices.

# Technologies Used
Frontend:
- React.js: For building the user interface.
- Toastify: To display notifications and alerts.
- React Router DOM: For managing navigation in the application.
Backend:
- Node.js: As the runtime environment.
- Express: Web application framework for Node.js.
- MongoDB: Database to store user credentials and session data.

# Installation
1. Clone the repository:

```
git clone https://github.com/Winniehub.github.io/W-W_Authentification_Login.git
```

2. Install dependencies:
Navigate to the project directory:
```
cd folder-name
```

3. Install backend dependencies:
```
npm install
```

4. Install frontend dependencies:

```
cd client
npm install
```

5. Configure MongoDB and JWT:
Visit MongoDB website, create account, database and take connection string.
After that generate 256 bits random key and add it to .env file.
Create the .env file in the root directory with the following contents:
```
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
```

6. Run the application:
Start the backend server:
```
node app.js
```

7. In a new terminal, start the frontend:
```
cd client
npm run dev
```

# Usage
After starting the application, visit http://localhost:5173 in your browser. Users can now register for a new account or log in using existing credentials.
