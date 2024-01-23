# World Cup Database

This project provides a PostgreSQL database dump named "worldcup," capturing information about World Cup games and participating teams.

## Database Structure

### 1. Games Table

- `game_id` (Primary Key)
- `year`
- `round`
- `winner_id` (Foreign Key referencing teams)
- `opponent_id` (Foreign Key referencing teams)
- `winner_goals`
- `opponent_goals`

### 2. Teams Table

- `team_id` (Primary Key)
- `name` (Unique)

## Usage

1. **Install PostgreSQL:**
   - Ensure you have PostgreSQL installed on your system.

2. **Create Database:**
   - Create a database named "worldcup" using the following command:

     ```sql
     CREATE DATABASE worldcup;
     ```

3. **Connect to Database:**
   - Connect to the "worldcup" database:

     ```sql
     \c worldcup;
     ```

4. **Run SQL Script:**
   - Execute the provided SQL script to create tables and insert sample data:

     ```sql
     -- Replace with the actual path to your SQL script
     \i path/to/your/script.sql;
     ```


Feel free to explore.
