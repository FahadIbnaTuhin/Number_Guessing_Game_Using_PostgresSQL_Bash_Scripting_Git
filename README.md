# Number Guessing Game

This is a simple Bash and PostgreSQL project from the freeCodeCamp Relational Database course.  
The program generates a random number between 1 and 1000 and lets the user guess it. User statistics are stored in a PostgreSQL database.

---

## What I Learned

While building this project, I learned:

- How to write Bash scripts
- How to connect Bash with PostgreSQL
- How to use SQL queries inside Bash
- How to read user input in shell scripts
- How to use loops and conditions
- How to validate integer input
- How to store and retrieve user game statistics
- How to work with Git and commits

---

## Skills Used

- Bash scripting
- PostgreSQL
- SQL
- Git and GitHub
- Linux terminal commands

---

## Features

- Random number generation
- Username system
- Stores number of games played
- Stores best game score
- Input validation for integers
- Higher/lower guessing hints

---

## How to Run

### 1. Clone the repository

```bash
git clone <your-repo-link>
cd number_guessing_game
```

### 2. Import the database

```bash
psql -U postgres < number_guess.sql
```

### 3. Give executable permission

```bash
chmod +x number_guess.sh
```

### 4. Run the game

```bash
./number_guess.sh
```
 
