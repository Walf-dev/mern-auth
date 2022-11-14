
# MERN Auth

An authentication system built with the MERN stack.


## Features

- Register 
- Login
- Password reset with reset token send throw email


## Installation

Create a .env file at the root of the project containing the following:

```bash
MONGO_URI='Your mongo connection string'
FRONTEND_URL=http://localhost:3000
EMAIL_FROM='sender email'
JWT_SECRET='your secret'
JWT_EXPIRATION=6d (or other period)
SENDGRID_API_KEY= your API key here
```
Install & run backend in the root folder:
```bash
npm install
npm run server 
```    
Install & run frontend in the ``client`` folder:
```bash
npm install
npm start 
``` 
## Tech Stack

**Client:** React, CSS

**Server:** Node, Express, Mongo, SendGrid

