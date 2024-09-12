# Project2024

## Project Setup Instructions

### To start the server:

- Go into the `server` folder.
- Run `npm install` to install the dependencies.
- Then run `npm start` to start the server with nodemon.

### To start the frontend:

- Go into the `client` folder.
- Run `npm install` to install the dependencies.
- Then run `npm start` to start the frontend.

### Create a `.env` file in the `server` folder with this info:

- `PORT=` [server port number]
- `FE_PORT=` [frontend port number]
- `DB_URL=` [database connection URL in the format `postgres://user:password@host:port/dbname`]
- `JWT_SECRET=` [cookie secret]

### Create a `.env` file in the `client` folder with this:

- `REACT_APP_BACKEND_URL=` [e.g., http://localhost:3000]

### Database Setup:

- Run the DDL queries to set up the database tables.
- Manually insert a new employee record into the `employees` table, and set the `role_id` column to the role_id that corresponds to the HR role in the `roles` table, so they will have HR access.
- Sign in using that employee’s credentials.
