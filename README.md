# StudyHub 2.0
### A Personal Study Management Platform

StudyHub 2.0 is a web-based study management application designed to help students organize their academic responsibilities, manage study sessions, and monitor their productivity through a centralized dashboard.

The project was developed using Python and Flask, with SQLite for persistent data storage and JavaScript for interactive functionality.

## Key Features

- **Dashboard:** Centralized overview of study activities and progress.
- **Pomodoro Timer:** Structured study sessions with a 50-minute focus and 10-minute break cycle.
- **Assignment Management:** Create, organize, and track assignments and their completion status.
- **Flashcards:** Create and review flashcards to support active recall.
- **Study Statistics:** Monitor study activity and track productivity over time.
- **Persistent Storage:** SQLite database integration to preserve assignments, flashcards, and study history.

## Technologies Used

| Technology | Purpose |
|---|---|
| Python | Backend development |
| Flask | Web application framework |
| SQLite | Database management |
| HTML | Application structure |
| CSS | Interface design and styling |
| JavaScript | Interactive functionality |

## Project Structure

```text
StudyHub2_Final/
│
├── app.py
├── studyhub.db
│
├── templates/
│   └── index.html
│
└── static/
    ├── css/
    │   └── style.css
    │
    └── js/
        └── app.js
```

*Note: `studyhub.db` is created automatically on the first run.*

## Installation and Setup

### 1. Install Flask

Install Flask using Python's package manager:

```bash
py -m pip install flask
```

### 2. Run the Application

Open a terminal inside the project directory and execute:

```bash
py app.py
```

### 3. Access StudyHub

Open your browser and navigate to:

```text
http://127.0.0.1:5000
```

The application will run locally on your computer.

## Database and Data Preservation

StudyHub 2.0 uses SQLite to maintain persistent application data.

Important considerations when updating from an earlier version:

- Stop any previously running Flask server using `Ctrl + C`.
- Back up your existing `StudyHub2/studyhub.db` before replacing project files.
- To preserve existing assignments, flashcards, and study history, copy the existing database into the new project directory before launching it for the first time.
- The application initializes missing database tables while retaining existing stored data.

**Important:** Do not delete the previous project until the updated version has been tested successfully.

## Project Objective

The main objective of StudyHub 2.0 was to develop a practical solution to common student organization challenges by combining several study-management tools into one accessible platform.

The development process involved backend implementation, database integration, frontend development, debugging, and iterative improvements to application functionality.

## Future Development

Potential areas for further development include:

- AI-assisted study recommendations.
- Intelligent flashcard generation.
- Personalized study planning.
- Advanced productivity analytics.

---

**Project:** StudyHub 2.0  
**Category:** Educational Technology / Web Development  
**Status:** Completed core application  
**Repository:** GitHub
