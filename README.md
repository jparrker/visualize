# Visualize

Visualize is a full stack web app where users can register, log in, post memes, and comment on others posts.

**Link to project:**
https://visualize.onrender.com/

<img src='https://i.imgur.com/EhCfzuk.png'>
<img src='https://i.imgur.com/nxNwjFch.jpg'>
<img src='https://i.imgur.com/jT4llkW.png'>

## How It's Made:

**Tech used:** HTML, CSS, Bootstrap, JavaScript, Node.js, Express, MongoDB

This project was created with an MVC (Model-View-Controller) architecture. We used mongoose to assist in creating schemas for our models and ejs to handle our views. Passport.js is handling the authentication for user sign-up and login, cloudinary is used to store and retrieve user uploaded images.

## Lessons Learned:

While building this app, I learned a lot about MVC architecture, specifically designing routes and schemas, and keeping our functionality in our controllers seperate form our views.

## Optimizations

There are many features we can add to improve user experience. We implemented the basic functionality in about four hours of class time. To improve the user experience we should add a dedicated user profile page where favorites and followed users show up, as well as a modal for new posts.

## Packages/Dependencies used

bcrypt, connect-mongo, dotenv, ejs, express, express-flash, express-session, mongodb, mongoose, morgan, nodemon, passport, passport-local, cloudinary, method-override, multer

## Contributors

Robin Herzig : <a href="https://github.com/RobinHerzig">Github</a> - <a href="https://www.linkedin.com/in/robinherzig/">LinkedIn</a><br>
Jeff Whetzal : <a href="https://github.com/NothingRemains">Github</a> - <a href="https://www.linkedin.com/in/jwhetzal/">LinkedIn</a><br>
Larry Nguyen: <a href="https://github.com/vu5381">Github</a> - <a href="https://www.linkedin.com/in/larrydnguyen/">LinkedIn</a><br>
Jason Parker: <a href="https://github.com/jparrker/">Github</a> - <a href="https://www.linkedin.com/in/jsonparker/">LinkedIn</a><br>
Jordan Veloso: <a href="https://github.com/jrveloso">Github</a> - <a href="https://www.linkedin.com/in/jordan-veloso/">LinkedIn</a><br>
Thomas Wright: <a href="https://github.com/thomasxwright">Github</a> - <a href="https://www.linkedin.com/in/thomasxwright/">LinkedIn</a><br><br>

# Install

`npm install`

---

# Things to add

- Create a `.env` file in config folder and add the following as `key = value`
  - PORT = 2121 (can be any port example: 3000)
  - DB_STRING = `your database URI`
  - CLOUD_NAME = `your cloudinary cloud name`
  - API_KEY = `your cloudinary api key`
  - API_SECRET = `your cloudinary api secret`

---

# Run

`npm start`
