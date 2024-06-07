## Description
Simple web-based note-taking application where users can write a note, save it, view a list of their saved notes, and delete a note. The user's notes are saved so they are available on any web-capable device.

## Features
- **Write Note:** Users can type a note in a text area.
- **Save Note:** A save button allows users to save the note.
- **View Notes:** Users can view a list of all saved notes.
- **Delete Note:** Users can delete a specific note from the list.

## Architecture Overview
The architecture is composed of the following main components:

### User Interface (UI)
- **NoteUI:** Composed of `TextArea`, `Button`, and `NoteList`.

### Controller
- **NoteController:** Handles HTTP requests and calls the appropriate services.

### Service
- **NoteService:** Contains business logic.
- **AuthService:** Validates the user session.

### Repository
- **NoteRepository:** Interacts with the database for CRUD operations.

### Model
- **Note:** Represents a note.
- **User:** Represents a user.

## UML Diagram
![UML Diagram](http://ai.getresolv.com:80/plantuml/29d8bc1e-3376-4429-a1f1-a4781018feee.png)

## Pseudo Code
Pseudo code for the main endpoints is available in the `pseudocode.txt` file.
