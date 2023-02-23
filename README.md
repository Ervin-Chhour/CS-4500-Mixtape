# Mixtape
Mixtape is a mobile application that lets you sign into multiple music streaming services and create combined playlists of songs. Planned features include a cross-platform song search, playlist importing, and a song tagging system. This project was created for our Senior Capstone Class.

# Description
Mixtape aims to make it easier for people to listen to a large variety of music from various streaming platforms all in one application which will be easy for anyone to use. Instead of having to switch between multiple streaming applications to listen to songs that are exclusive to a certain streaming service, our users will be able to have all the music they want to listen to in one place without having to worry about a song being exclusive to a particular service. In order to accomplish this, Mixtape will be a mobile application that will connect to each of these services’ APIs and let the user sign into multiple music streaming services such as Apple Music, SoundCloud, and YouTube Music.

# Libraries
**Express:**
Express is a framework for Node.js which we chose to use for its ease of use and the fact that it can be used for both mobile applications and web applications. The simple routing functionality and ease of using middleware for our authentication made it seem like a great fit for use in this project.

**Sequelize:**
Sequelize is an ORM for Node.js which we chose to use to connect to our MySQL database. It allows for creating tables for the database in JavaScript which directly correspond to models usable within the backend.

**Bcrypt and JWT:**
Bcrypt is a library of password hashing functions, which we used for our authentication system to make storing passwords more secure. We used JWTs (JSON Web Token) in tandem with our authentication system to securely let users access only the resources they were allowed to.

**Swagger/Postman:**
For testing and making API calls both internally and externally we will be using Postman.

**Testing Plans and Tools:**
We’re going to make automated unit tests as we see fit when making new changes. Also, potentially we’ll get something set up where before a pull request can be merged it automatically runs our tests to make sure the PR wouldn’t break anything.

**Versioning:**
For our versioning we are using Git, due to everyone’s familiarity with it. We will be making use of branches for being able to work on different features simultaneously and using pull requests to merge things 

**Issue and Bug Tracking:**
For tracking our issues and posting bug reports we will be using the GitLab issues board. We also have used Trello in the past, so that is a possible option if we do not wish to use GitLab’s issue management system anymore.

**Docker:**
Having to run the AWS RDS instance everytime we want to develop and test our app is tiresome and expensive. This is why we’ve set up docker containers on our local setups that host the database locally. This means we can run and test our app 100% locally without needing to run AWS constantly.

# License
GNU General Public License v3.0 (GPLv3)
