# Project 3 - MERN Guest Book

## Overview

1. [Description](#description)
2. [Deployment Link](#deployment-link)
3. [Installation](#installation)
4. [Technologies Used](#technologies)
5. [Deliverables](#deliverables)
6. [Planning/Build Process](#planning)
7. [Challenges](#challenges)
8. [Wins](#wins)
9. [Key Learnings & Takeaways](#takeaways)
10. [Future Improvements](#future-improvements)

## <a name="description"></a> 1. Description

A Full-Stack Guestbook application, built from scratch within 9 days by a team of 4 developers using the MERN stack (MongoDB, Express, React & Node). This group project was the third application built as part of the curriculum for the General Assembly Software Engineering Immersive Course.

<br>

The website allows users to sign up for an account and subsequently login into and out of their account. They also have the option to edit their username and password once they are logged in, or delete their account. Authentication was achieved by using the Node ExpressJS and Passport.js packages.<br>
Users can also read, post, edit and delete comments in the Guestbook appliation, the concept of which was tailored around a specific event type: a divorce party. The idea behind this concept was to support recent divorcees by enjoying their divorce party to the fullest and later re-live all the happy memories.

<img src='./assets/Layout.png' alt="project landing page">

## <a name="deployment-link"></a> 2. Deployment link

https://hpramanathan.github.io/project3-mernstack-app/

## <a name="installation"></a> 3. Installation

- package manager used: npm (v9.6.7)
  - https://www.npmjs.com/package/npm
  - to install dependencies, run the following command in both the front end and back end directories:

```
npm install
```

## <a name="technologies"></a> 4. Technologies Used

### Front End

The front end of this application is based in ReactJS (v18.2.0), JavaScript, JSX and CSS.

- The front end was set up using the 'create-react-app' command
  - https://create-react-app.dev/

```zsh
create-react-app frontend
```

Additional packages:

- routing: react-router (v6.11.2)
  - https://www.npmjs.com/package/react-router
- authentication: bcryptjs (v2.4.3)
  - https://www.npmjs.com/package/bcryptjs
- UI
  - styling: TailwindCSS (v3.3.2)
    - https://tailwindcss.com/docs/guides/create-react-app
  - icons
    - all icons used are Scalable Vector Graphics from iconify
    - https://iconify.design/

### Back End

- the back end was set up using the following command:

```zsh
npm i express mongoose
```

Additional packages:

- express (v4.18.2)
  - https://www.npmjs.com/package/express
- CORS (v.2.8.5)
  - https://www.npmjs.com/package/cors
- dotenv (v.16.0.3)
  - https://www.npmjs.com/package/dotenv
- mongodb (v5.4.0)
  - https://www.npmjs.com/package/mongodb
- mongoose(v7.1.0)
  - https://www.npmjs.com/package/mongoose
- nodemon(v2.0.22)
  - https://www.npmjs.com/package/nodemon
- authentication:
  - bcrypt (v5.1.9)
    - https://www.npmjs.com/package/bcrypt
  - jsonwebtoken (v.9.0.0)
    - https://www.npmjs.com/package/jsonwebtoken
  - passport (v0.6.0)
    - https://www.npmjs.com/package/passport
  - passport-jwt (v.4.0.1)
    - https://www.npmjs.com/package/passport-jwt

### Deployment

- MongoDB Atlas
  - used to deploy the MongoDB database
  - https://www.mongodb.com/cloud/atlas/register
- Heroku
  - used to deploy the back end
  - https://www.heroku.com/
- Netlify
  - used to deploy the front end
  - https://www.netlify.com/

### Additional tools used:

- Git / GitHub: version control
  - https://git-scm.com/
  - https://github.com/https://github.com/
- Postman
  - used to test the API endpoints
  - https://www.postman.com/
- Visual Studio Code (VSCode)
  - code editor used for writing CSS, JSX and JavaScript
  - https://code.visualstudio.com/
- Google Chrome browser
  - used for launching the website and displaying the application Google Chrome
  - Google Chrome Developer Tools: For troubleshooting and debugging
  - https://www.google.com/intl/en_uk/chrome/
- excalidraw
  - used for building the wireframe + ERD
  - https://excalidraw.com/

## <a name="deliverables"></a> 5. Deliverables

### MVP Requirements

- thoroughly documented README.md file
- Excalidraw or Whimsical document to convey the data flow with component hierarchy included.
- proper indentation, semantic variable names, adhere to naming conventions
- Remove
  - unnecessary boilerplate React files and code
  - console.log()s
  - commented out code
- All team member should:
  - contribute equally
  - Have a solid understanding of the entire project, even the features implemented by other team members.
  - Take time to pair program with teammates to reinforce learning.
  - Be prepared to explain sections of code that were written by teammates.
- Front end:
  - Working, interactive React app, built using npx create-react-app client
  - at least 6 separate, rendered components in an organized and understandable React file structure.
  - Use only React for DOM Manipulation.
  - Consume data from an API, and render that data in your components.
  - Utilize React Router, for client-side routing.
  - Authentication
- Back end:
  - working generic router actions for CRUD using Express, Mongoose, and MongoDB.
  - Have at least 2 models
  - Have full CRUD on at least one of your models
  - Be able to Add/Delete on any remaining models
  - Authentication
- Styling:
  - styling with CSS
    - flexbox or Grid
  - responsive design on 2 screen sizes (including desktop) using a media query (mobile)
- Deployment:
  - Deploy the fully functional front-end via GitHub Pages or Vercel
  - Deploy the back-end via Heroku (or vercel)
  - Deploy the MongoDB database on MongoDB Atlas

### Stretch goals

- more than 2 models
- css framework e.g. TailwindCSS or bootstrap

## <a name="planning"></a>6. Planning/Build Process

- The team working on this project included 4 members:

  - [Hari Ramanathan](https://github.com/hpramanathan) - GitHub Code Owner/Team Lead
  - [Benjamin Khoury](https://github.com/khouryb)
  - [Franziska Kissling](https://github.com/FrankieSlinn)
  - myself - [Catherine Loesch](https://github.com/catherineloesch)

- Timeframe: 9 days
  - The deliverables were issued to the team on 04/05/2023 with the submission deadline and presentation date on 12/05/2023

<br>

### Day 1: 04/05/2023

On day 1, the team brainstormed together to develop the project concept, design, coding approach and working schedule.
The team picked a team name (Chewing the CRUD) and agreed on a concept: A virtual guest book for an event, specifically a divorce party. The team then discussed each member's strengths and weaknesses, the details of which were recorded in the [Team Expectations Setting Document](./assets/team_expectations_setting.pdf). <br>

Next, the team devised the user stories, a wireframe, schema and flow chart containing the database models that had been agreed upon earlier in the day:

### wireframe

<img src='./assets/wireframe.png' alt='project wireframe'>

<br>

### User Stories

- As a user I should be able to access the website from different devices/browsers.
- As a user I should be able to register with a username and password.
- As a user I should be able to login with my username and password.
- As a user I should be able to view all posts.
- As a user I should be able to view my posts.
- As a user I should be able to write new posts.
- As a user I should be able to delete my posts.
- As a user I should be able to edit my posts.
- As a user I should be able to log off from the website.

<br>

### schema

<img src='./assets/schema.png' alt="project schema">

<br>

### Database Models Flowchart

<img src='./assets/flow_chart.png' alt="Database Models Flowchart">

<br>

After setting up the git repository for the project, each team member created their own local development branch.

### Day 2: 05/05/2023

With the git repository and development branches set up, the team divided up the tasks and started the coding phase of the project:
I got started on the front end by setting the react application witht the 'npx create-react-app' command and installing react-router.
I then moved on to creating the 2 models for the project: a User and a Post model. These models have a one-to-many relationship where a User can have many posts but a post only belongs to one user.

```JavaScript
const mongoose = require('mongoose')
const Schema = mongoose.Schema;

const userSchema = new Schema({
    username: { type: String, required: true },
    password: { type: String, required: true },
    name: { type: String, required: true },
    posts: [{
        type: mongoose.Schema.Types.ObjectId,
        ref: "Post"
    }]

}, { timestamps: true })

const User = mongoose.model('User', userSchema)

module.exports = User;
```

```JavaScript
const mongoose = require('mongoose')
const Schema = mongoose.Schema;

const postSchema = new Schema({
    author: { type: String, required: true },
    title: String,
    content: { type: String, required: true }
}, { timestamps: true })

const Post = mongoose.model('Post', postSchema)

module.exports = Post;
```

While another team member focused on the Post model, I tackled the CRUD functions for the User model both for the front end and the back end, writing code to implement full CRUD functionality:

- INDEX
- SHOW
- CREATE
- UPDATE
- DESTROY

backend: DELETE route for the User model

```JavaScript
router.delete('/users/:id', (req, res) => {
    User.findByIdAndRemove(req.params.id)
    .then(user => {
        if (user) {
            res.json(user)
        } else {
            res.status(404).json({
                error: {
                    name: 'DocumentNotFound',
                    message: "The provided ID doesn't match any documents"
                }
            })

        }

    })
    .catch((error) => {
        console.log(error)
        res.status(500).json({error: error})
    })
})


```

After all the backend routes had been successfully tested, in the Postman API platform I started implementing the frontend database requests for User model.
Below is the example of the DELETE fetch request on the frontend:

```JavaScript
export const deleteOneUser = async (id) => {
    const fetchOptions = {
        method: "DELETE",
        headers: {
            "Content-Type": "application/json",
            "Accept": "application/json"
        }};

    const url = `http://localhost:5000/users/${id}`
    const response = await fetch(url, fetchOptions);

    if (!response.ok) {
        const errorMessage = await response.text();
        throw new Error(errorMessage);
    }

    return response.json();
}
```

The rest of the team implemented CRUD functions for the Post model and generated seed data for the database.

### Day 3: 06/05/2023

Since the team had decided on using a CSS framework to do the styling, I also installed tailwindCSS for react. I then proceeded to add a form in the front end to add new users to the database:

<img src='./assets/SignUpForm.jpg' alt="Sign Up form to add new Users" width="250">

### Day 4: 07/05/2023

On the fourth day I continued my tainwindCSS learning curve and created a responsibe navigation bar for the website.

<img src='./assets/nav_bar.jpg' alt="Nav Bar Full Screen">

<img src='./assets/nav_bar_mobile.jpg' alt="nav bar mobile view" width="300">

I also added a login page for users that are already in the databse:

<img src='./assets/login_mobile.jpg' alt="login page" width='300'>

### Day 5: 08/05/2023

On the fifth day of development the team focused on the deployment of the frontend to github pages and getting started on user authentication.

I used the bcrypt package to make sure that passwords entered by users are hashed and salted before being stored in the database, making sure there are no plain-text passwords stored in the backend.

```JavaScript

router.post('/users', async (req, res) => {

    try {
        //Check if username already exists in db
        //If it does, send error
        const usernameExists = await User.find({username: req.body.username})

        if (usernameExists.length > 0) {
            res.send({error: "username already exists"})

        } else {
            //salt + hash password entered by user
            const salt = await bcrypt.genSalt()
            const hashedPassword = await bcrypt.hash(req.body.password, salt)

            const newUser = {
                username: req.body.username,
                password: hashedPassword,
                name: req.body.name,
                posts: []
            }

            //create new User document
            User.create(newUser).then(function(user) {
                res.status(201).json(user)
            })
        }
    } catch {
        res.status(500).json({error: 'Internal Server Error'})    }
})

```

### Day 6: 09/05/2023

jwt passport

```JavaScript
//LOGIN when user tried to log into account with username + password
router.post('/users/login', async (req, res) => {

    //retrieve user document from db by username (usernames are unique)
    const user = await User.find({username: req.body.username})

    if (user.length == 0) { // no record found in database
        res.status(400).json({error: 'user does not exist in database'})

    } else { // user exists in db

        try {   //check if password user entered matches password in db
            if (await bcrypt.compare(req.body.password, user[0].password)) {

                const payload = {
                    id: user[0]._id,
                    username: user[0].username
                }

                //Build JWT
                const token = jwt.sign(payload, jwtOptions.secretOrKey, {expiresIn: 432000}) // 5 days -> 432000s

                //Send JWT back to user
                res.status(201).json({
                    success: true,
                    token: token,
                    user: user
                })

              } else { // password user entered does not match password in db
                res.status(401).json({error: 'Invalid username or password'})
              }
        } catch(error) {
            res.status(500).json({error: error})

        }
    }
})
```

The team also worked on etablishing a connection with the Mongo Database and producing seed data to populate it.

### Day 7: 10/05/2023

passport jwt

The user authentication was developed using bcrypt for password hashing and Passport JWT for user authentication. The authentication was integrated into the routes.

### Day 8: 11/05/2023

add account page for user
add logout
user specific posts +CRUD

### Day 9: 12/05/2023 -> Submission deadline + Project Presentation

## 7. <a name="challenges"></a> Challenges

- Seeding
  - The team faced challenges while implementing the seed file to populate initial data into the database. It required careful handling and synchronization to ensure the data was properly seeded.
- Authentication:
  - Developing user authentication posed challenges. T
- deployment
  - a major challenge encountered at the end of the project was the issue with the Front-End deployment prep and its relation to the (back-end) Heroku server.
  - This connectivity issue caused a disruption in the expected flow of data and functionality, hindering the full operation of the website.
  - The team worked diligently to troubleshoot and resolve this bug, but were unable to do so.
    Hence the website is only accessible via a _localhost_.

## 8. <a name="wins"></a> Wins

- The team managed to fullfill all the MVP requirements with the exception of front end deployment.
- Authentication

- TailwindCSS: every member on the team managed to learn a new css framework they hadn't used before and felt comfortable using it at the end the project.

## <a name="takeaways"></a> 9. Key Learnings & Takeaways

- Good communication is key when working in a team that contributes to the same git repository.
- Reviewing git conflicts as a team can avoid issues of code getting deleted.
- keeping the front end and back end code in separate git repositories helps avoid complications during the deployment process.
- frequently pulling changes from the main github repository and merging them to the local branch you're working on is important in avoiding conflicts when making pull requests further down the line.

## <a name="future-improvements"></a> 10. Future Improvements

- enable users to upload files so they can add profile pictures and add phtographs to their posts.
- incorporate a third-party api: displaying funny or motivational quotes specifically related to divorce would add interesting and relevant content to the website
