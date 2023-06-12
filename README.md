# Project 3 - MERN Guest Book

## Overview

1. Description
2. Deployment Link
3. Installation
4. Technologies Used
5. Deliverables
6. Planning
7. Build Process
8. Challenges
9. Wins
10. Key Learnings & Takeaways
11. Future Improvements

## 1. Description

A MERN Full-Stack Website that allows users to sign-up for an account, read, post, edit and delete comments in a Divorce Party Guest Book. This was implemented as a group project consisting of four General Assembly Software Engineering Immersive students with the amusing team name "Chewing the CRUD".

WHY A DIVORCE PARTY GUESTBOOK?
Lots of people will attest to their experience of divorce as one of the best things that ever happened to them. Of course they will want to celebrate with lots of friends and family. What better way to commemorate the celebration than with a Divorce Party Guestbook? The app was developed to help recent divorcees enjoy their divorce party to the fullest and will hopefully let users re-live all the happy memories. A divorce isn't the end; merely the beginning to either a new chapter or a whole new sequel.

## 2. Deployment link

https://hpramanathan.github.io/project3-mernstack-app/

## 3. Installation

- Front end dependencies:
  - package manager used: npm - v9.6.7
  - https://www.npmjs.com/package/npm
  - to install dependencies, run the following command in both the front end and back end directories:

```
npm install
```

## 4. Technologies Used

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
- styling: TailwindCSS (v3.3.2)
  - https://tailwindcss.com/docs/guides/create-react-app

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
- Icons
  - All icons used are Scalable Vector Graphics from iconify
  - https://iconify.design/

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

## 5. Deliverables

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

## 6. Planning

- The team working on this project included 4 members:

  - [Hari Ramanathan](https://github.com/hpramanathan) (GitHub Code Owner/Team Lead)
  - [Benjamin Khoury](https://github.com/khouryb)
  - [Franziska Kissling](https://github.com/FrankieSlinn)
  - myself, [Catherine Loesch](https://github.com/catherineloesch)

- Timeframe: We were given 8 days to complete work on this project
  - from: 04/05/2023
  - to: 12/05/2023

### Day 1: 04/05/2023

On day 1, the team brainstormed together to develop the project concept, design, coding approach and working schedule.
The team name was picked (Chewing the CRUD) and agreed on a concept: A virtual guest book for an event, specifically a divorce party. The team then discussed each member's strengths and weaknesses, the details of which were recorded in the [Team Expectations Setting Document](https://docs.google.com/document/d/1QG9nAynGNKvsSN4Jzfesn4T-DbXv5GxTEtXh-bZMAAM/edit). <br>

Next, the team devised the user stories, a wireframe, schema and flow chart containing the database models that had been agreed upon earlier in the day:

### wireframe

<img src='./assets/wireframe.png' alt='project wireframe'>

### schema

<img src='./assets/schema.png' alt="project schema">

### Database Models Flowchart

<img src='./assets/flow_chart.png' alt="Database Models Flowchart">

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

After setting up the git repository for the project, each team member created their own local development branch.

### Day 2: 05/05/2023

### Day 3: 06/05/2023

### Day 4: 07/05/2023

### Day 5: 08/05/2023

### Day 6: 09/05/2023

### Day 7: 10/05/2023

### Day 8: 11/05/2023

### Day 9: 12/05/2023 -> Submission deadline + Project Presentation

- ### FLOW CHART, USER STORIES AND WIREFRAME

- ### LAYOUT

  Franziska took the lead with researching a number of colour schemes online and as a team we agreed upon the first colour scheme below:
  ![Colour Schemes](./documentation/ColourSchemes.png "Colour Schemes")

  Franziska did the same with potential images to be used for the website. Again, as a team we went with the first one. (**WARNING**: One of the images contains a swear word.)
  ![Divorce Party Images](./documentation/DivorcePartyImages.png "Divorce Party Images")

  We used the **Tailwind CSS** framework for our layout and styling. We added the chosen colour scheme above to our Tailwind _config_ file.

  This is what our final homepage layout looked like:
  ![Layout](./documentation/Layout.png "Layout")

## BUILD/CODE PROCESS

We utilised the MERN Stack. As a first step a connection with the Mongo Database was established. A seed file was then produced to populate initial data into the database.

Models were then established for the Users and Posts.

![User Model](./documentation/UserModel.png "User Model")

Once the models were completed backend routes were coded. The routes were tested in Postman API Platform.

![Example Backend Route](./documentation/ExampleBackendRoute.png "Example Backend Route")

After the backend routes were successfully tested the frontend routes were implemented.

The user authentication was developed using bcrypt for password hashing and Passport JWT for user authentication. The authentication was integrated into the routes.

Github provided version control. To minimise merge conflicts commits and pulls were done frequently.

## CHALLENGES

- Seeding: The team faced challenges while implementing the seed file to populate initial data into the database. It required careful handling and synchronization to ensure the data was properly seeded.
- Authentication: Developing user authentication posed challenges. The team utilized bcrypt for password hashing and Passport JWT for user authentication. Integrating authentication into the routes required careful implementation and testing.

## WINS

- Authentication: Successfully implementing user authentication using bcrypt for password hashing and Passport JWT for user authentication was a significant win for the team. It ensured secure access and protected user data.
- Tailwind CSS: Utilizing the Tailwind CSS framework for layout and styling proved to be a success. The chosen color scheme and styling enhanced the overall design of the website.
- Git conflicts: The team effectively managed Git conflicts by frequently committing and pulling changes from the repository. This approach minimized conflicts and facilitated smooth collaboration.

## KEY LEARNING/TAKEAWAYS

- In the immortal words of Big Chris, _It's been emotional_.

## BUGS

- One notable challenge encountered at the end of the project was the issue with the Front-End deployment prep and its relation to the (back-end) Heroku server. This connectivity issue caused a disruption in the expected flow of data and functionality, hindering the full operation of the website. The team worked diligently to troubleshoot and resolve this bug, but were unable to do so. Hence the website is only accessible via a _localhost_.

## FUTURE IMPROVEMENTS

- Create a file upload facility for user profile pictures and party pictures within a post: Enhancing the website by adding a file upload feature would allow users to upload profile pictures and images related to their divorce party posts, further enriching the user experience.
- Get quotes about divorce via an external API: Integrating an external API that provides quotes specifically related to divorce would add interesting and relevant content to the website. It could enhance the overall user engagement and provide additional value to the users.
