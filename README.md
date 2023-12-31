# Welcome to flight service

## Project Setup
- clone the project on your local
- Execute `npm install` on the same path as of your root dirctory of the download project
- Create a `.env` file in the root directory aff the following environment variable
    - `PORT=3000`
- inside the `src/config` folder create a new file `config.json` and then add the followinf piece of json

```
{
  "development": {
    "username": "YOUR_DB_LOGIN_NAME",
    "password": <YOUR_DB_PASSWORD>,
    "database": "Flights_Search_DB_DEV",
    "host": "127.0.0.1",
    "dialect": "mysql"
  }
}

```