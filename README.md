# Family Travel Tracker
  The Family Travel Tracker is a web-based application that allows users to track the countries they have visited. Users can create family profiles, add visited countries, and see the total number of countries visited. The app also supports multiple users, allowing family members to share and track their travel experiences together.


## Technologies Used

* Frontend: HTML, CSS, JavaScript, EJS
* Backend: Node.js, Express.js
* Database: PostgreSQL
* Other: dotenv for environment variables

## Features

* Multi-user support: Add multiple family members, each with a unique name and color.
* Track countries: Users can add countries they have visited by typing the country name.
* Unique User Interface: Each user is represented by a color, which is applied to the countries they have visited.
* Data persistence: All user information and visited countries are stored in a PostgreSQL database.
* Error handling: Alerts when a country has already been added or does not exist.

 ##  Getting Started

 ### Prerequisites
 Before you begin, ensure you have the following installed:

Node.js (v16 or later)
PostgreSQL (v13 or later)
npm (or yarn)

 ## Installation
 1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/family-travel-tracker.git
    cd family-travel-tracker

2. Install dependencies:
   ```bash
   npm install

3. Set up environment variables:

  Create a .env file in the root of the project and add the following:

  ```bash
  DB_USER=your-db-user
  DB_HOST=localhost
  DB_NAME=your-db-name
  DB_PASSWORD=your-db-password
  DB_PORT=5432
  PORT=3000
```

## 4.Set up PostgreSQL database:

* Create a PostgreSQL database and tables based on the structure required by the app.
* You can refer to the schema used in the project to create the necessary tables for users and visited countries.

## 5.Run the application:

Start the server with:

```bash
npm start
```

The application will be accessible at http://localhost:3000.




