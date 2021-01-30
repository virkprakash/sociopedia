# SOCIAL AWARENESS 
    . Is a app, where real user are able to post their campaign adds to raise awareness. 
    . under development 

## Node.js, expressJs, mongoDb, pug, (ReactJs) 
    Node.js - rest API 

## Installation
    Use the package manager [npm] (https://www.npmjs.com/get-npm) to install the app 
   
    npm install 
    
    create an environment variable on the base of the project (You need to add secret key in this .env file, ask your project manager)
    
    $ touch .env
    
    Steps for env and database connection to run in local 
    
    1. install mongodb 
    2. create database name as [socialawareness]
    3. create collection name as [users]
    3. What to add in .env 
        PORT = 3030
        DB_LINK = [your db link]
                SHOULD LOOK LIKE THIS
                mongodb+srv://DATABASE_USERNAME:<DATABASE_PASSWORD>@cluster0.ua44v.mongodb.net/socialawareness?retryWrites=true&w=majority
                
        DATABASE_USERNAME = [your username]
        DATABASE_PASSWORD = [your password]

        JWT_SECRET_KEY = this.is.a.secret.jwt.key.from
        JWT_EXPIRES_IN = 90d
        JWT_COOKIE_EXPIRES_IN = 90

    
## Usage 
    
    To run in development 
        npm run start

    To run in production 
        npm run start:prod

    
## Routes (http://127.0.0.1:3030/)
    # VIEW ROUTES
    
        GET     / 
        POST    /login
        POST    /signup
    
    # API ROUTES 
    
        POST    /api/users/signup
        POST    api/users/login
        POST    /api/users/logout

## App Screenshot 
    
    see folder snapshot 

## Contributing 
    Prakash and team

## Licence 

 
    
