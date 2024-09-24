# Password And Notes Manager Backend<br/>

# Overview<br/>
This is the backend API for a password and notes manager application. It provides a RESTful API for managing passwords and notes, and is designed to be used with a frontend client.<br/>

# Features<br/>
User authentication and authorization<br/>
Password management (create, read, update, delete)<br/>
Notes management (create, read, update, delete)<br/>
CORS enabled for cross-origin requests<br/>

# Authentication
/api/v1/auth - User authentication and registration endpoints<br/>
## Passwords<br/>
/api/v1/pass - Password management endpoints (create, read, update, delete)<br/>
## Notes<br/>
/api/v1/notes - Notes management endpoints (create, read, update, delete)<br/>

# Setup<br/>
Environment Variables<br/>
This project uses environment variables to configure the application. You can set the following variables in a .env file:<br/>

MONGOOSE_URI=""<br/>
CORS_ORIGIN=*<br/>
PORT=8015<br/>

# Running the Application
node index.js<br/>
