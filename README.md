# technical-Task
A small technical task for finding good junior back-end developers

## Task description
First of all, those who want to start their careers in software engineering, should consider that you always have to keep learning new skills. This task is for those who want to start developing in JavaScript, but want to learn a thing or two about Web-Development as well. Let's get right to the Task: we are creating a big social media platform, that people have never seen before! Your task is simple: start a web server and make an authentification system for our platform. You should implement all the latest & greatest techniques, like cookies based sessions and password encryption. It is not necessary to implement two factor authentification, but it will give you some bonus points. 

## What to use
For starting clean and minimal web server you can use [express](https://github.com/expressjs/express) and [express-session](https://github.com/expressjs/session) for sessions implementation, althought you can use any Node.js framework. It's not prerequisite to work with a particular database system, although I recommend [MySQL](https://www.mysql.com) or [MongoDB](https://www.mongodb.com). There is plenty of support for integrating these databases with Node.js.
### 1. Start a Node.js webserver
You can use any framework/library to do that, but keep in mind that you will create a failry complex system, so be careful: use well documented ones. You should also implement package.json in your project in order to make it compatible with npm package manager. I forgot to mention: always use https over http!!!
### 2. Start using a database and integrate it with your webserver
Fairly easy one. There are plenty of support for Node.js & database integration, so be creative! Also, you should store all user data encrypted in a good database.
### 3. Make a simple login/registration system
Start playing with authentification using all libraries you can find, but keep in mind, that you should make it as secure as posible, so, think about what to write after you have all the technologies you need!
### 4. Finishing up
Probably most of the people use social media everyday. Use it as a reference for your small project. It's commendable to see your knowledge of authentification systems. Design part is not important, so you can about it later.
## In the end
You should have modern and secure authentification system ready to use later in upcoming projects. Implement cookies to keep user authentificated as long as he does not press 'logout' button! If user is trying to log in with different IP, you should send him an e-mail, telling about the possible security breach. Upload project to GitHub explaining everything in README.md, and make it fetchable via npm.
 
#### P.S: Good Luck and Have Fun!
