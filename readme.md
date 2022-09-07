# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

### Follow these steps to setup on your local machine:
1. Clone this repository in your machine. <br />
``` git clone https://github.com/ObelusFamily/Anythink-Market-hpxcd```<br /><br />
2. Install docker from the official site and check if it is successfully installed by running: <br />
```docker -v```<br />
```docker-compose -v```<br /><br />
3. Now go to project's root directory and run:<br /> ```docker-compose up```<br /><br />
4. Now paste the link in the browser:<br /> ```http://localhost:3000/api/ping```<br /><br />
5. Create a new user here:<br /> ```http://localhost:3001/register```

### Congratulations, You have successfully setup on your local machine
