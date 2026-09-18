# ToDo App Lorenz

## Project Description
This Application is a ToDo App! You can list all the things you have to do. After you did a thing you can cross it or even delete it of the list. Its realy helpful to keep an eye on your tasks.

## Requirements
- Git
- Node.js and npm
- Docker Desktop

## Download the Project
1. **Open Git Bash**
2. **Type:** 
`git clone https://github.com/gmurlorenz/To.Do.App_Lorenz.git`
3. **After that type:** `cd To.Do.App_Lorenz`

## Install 
Install the nessesary packages.
**Type in Bash:**
`npm install`

## Start Locally
**To use the application localy type the command:**
`npm run dev`
**If it doesnt work, try:** `npm.cmd` **instead of** `npm`.

**Open the app in your browser with:** http://localhost:3000.

## Build a Docker Image
Open *Docker Desktop*, then type in bash:

`docker build -t todo-app .`

## Start the App with Docker
**Type in bash:**
`docker run -d --name todo-container -p 3000:3000 todo-app`


This starts the app in a container.

## Start with Docker Compose
1. Open Docker Desktop.
2. Make sure your Compose file is saved and contains the correct settings.
3. Type in Bash:

`docker compose up -d --build`

Open http://localhost:3000

## How to Stop the App
- **Local:** Press Ctrl + C in the terminal.
- **Docker:** Run `docker stop todo-container`.
- **Compose:** Run `docker compose down`.


**Only one of the tree can work at once because they all use port3000!!!**
