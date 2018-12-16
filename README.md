# Warbler
About: Warbler is a mock twitter clone built completely as a backend application. Users can signup/login, follow other users, be followed by other users, create warbles which are tweets, as well as direct message other users. User authentication/authorization is done with bcrypt for verification and sessions are used to store current user information. The backend is built in Flask and Jinja is used as a templating system for the HTML. PostgreSQL is the database that is used. Tests are written for the views and models using the unittest module. Feel free to run the app locally or go to the live hosted heroku site: [warbler](https://warbler-vsha2.herokuapp.com/)

# Setup

To clone the repository run the following command:
```
git clone https://github.com/hineshamin/warbler.git
```

Run the following command to install the necessary packages in the root folder  
```
npm install
```

Run the following command to start the app  
```
npm start
```
