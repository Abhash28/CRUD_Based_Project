# **NoteApp**

NoteApp is a web-based application designed to help users manage their notes in a simple and intuitive manner. The app allows users to add new notes, edit existing ones, and delete them when no longer needed.

## **Features**

- **Add Notes:** Easily create new notes with a title and description.
- **Delete Notes:** Remove any notes that are no longer needed with just a click.
- **User-Friendly Interface:** The app has a clean, minimal, and easy-to-navigate user interface, making it simple to manage your notes.
- **Secure Authentication (Optional):** Users can register, log in, and manage their notes securely with JWT-based authentication.

## **Technologies Used**

- **Frontend:** React.js, HTML, CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication (Optional):** JWT (JSON Web Tokens)
- **Styling:** Custom CSS for a simple and clean UI

## **How It Works**

1. **Adding Notes:** Users can create notes by filling in a title and description.
2. **Viewing Notes:** All added notes are displayed in a list format, providing quick access to each note’s details.
3. **Deleting Notes:** Users can easily delete notes they no longer wish to keep. The app will prompt for confirmation before deletion to avoid accidental data loss.
   
## **Project Structure**

- **Frontend:** The frontend of the application is built using React.js. It communicates with the backend to display the list of notes and handle the creation and deletion of notes.
- **Backend:** The backend is built using Node.js and Express.js. It provides API endpoints for adding, deleting, and retrieving notes from the database.
- **Database:** MongoDB is used as the database to store the notes. Each note contains a title, description, and a unique identifier.
