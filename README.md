# Project Setup
 - go into the project directory and use `npm i`
 - Create a new .env file and configure a variable `PORT=XXXX` 
 - then change username and password in the `config.config.json`
 - To create the db - `npx sequelize init` 
 - then `npx sequelize db:create`
 - Seed roles: `npx sequelize db:seed:all`
 - If you wish to later remove the seed: `npx sequelize db:seed:undo:all`
 