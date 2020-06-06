# News App

This web application involves building a simple news application which fetches news articles from an external api vendor and display them in web application

### Overview of the Application
* This web application allows the user to login. Error handling has been done, incorrect username or password won't allow the user to login. For login, you can use -> (username: **akr**, password: **akr**)
* Allowed user to choose (**add/remove**)  news sources of their own choice from the list available and display their top 10 articles. As per the requirement, the user won't be allowed to select more than 5 news sources
* Allowed the user to save articles for future reference. The user can also view the list of saved articles



## Steps to Setup and Run the Application

### Installation and Running
1. You need to have **node.js** and **npm** installed on your machine. Once installed, you can check the versions using the below commands

```sh
node -v
npm -v
```
Links for reference:
* [install node.js](https://nodejs.org/en/download/)


```sh
cd react-nodejs-newsapi
npm install
```

2. Start node.js server

```sh
node index.js
```

3. Run the react application

```sh
npm start
```

