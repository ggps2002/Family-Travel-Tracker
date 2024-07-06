# Family Travel Tracker

Family Travel Tracker is a web application designed to help users keep track of the countries they have visited. By adding a country as visited, users can choose a color to mark it on a world map interface. This application is built using EJS (Embedded JavaScript), PostgreSQL, and Node.js.

## Features

- **Track Visited Countries**: Add countries to your visited list.
- **Visual Representation**: Choose a color to mark visited countries on a world map.

## Technology Stack

- **Frontend**: EJS (Embedded JavaScript)
- **Backend**: Node.js, Express.js
- **Database**: PostgreSQL
- **Styling**: CSS

## Installation

### Prerequisites

- Node.js and npm installed
- PostgreSQL installed and running

### Steps

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/family-travel-tracker.git
    cd family-travel-tracker
    ```

2. **Install dependencies**:
    ```bash
    npm install
    ```

3. **Set up the database**:
    - Create a PostgreSQL database.
    - Run the SQL script provided in `db/schema.sql` to set up the database schema.
    - Create a `.env` file in the root directory and add your database connection details:
      ```env
      PG_HOST=localhost
      PG_USER=yourusername
      PG_PASSWORD=yourpassword
      PG_PORT = your_db_port
      PG_DATABASE = your_pg_database
      ```

4. **Start the application**:
    ```bash
    npm start
    ```

5. **Open your browser** and go to `http://localhost:3000`.

## Usage

3. **Add Visited Countries**:
    - Navigate to the world map interface.
    - Select a country and choose a color.
    - Save to mark the country as visited.
4. **View Visited Countries**: See all the countries you have visited highlighted on the map.
