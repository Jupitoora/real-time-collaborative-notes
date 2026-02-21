# Real-Time Collaborative Notes App

A web-based application that allows multiple users to create and edit notes collaboratively in real time.  
The app synchronizes changes instantly across all connected users using WebSockets.

---

## Features
- Real-time collaborative note editing
- Multiple users can edit the same note simultaneously
- Auto-save functionality
- User authentication
- Create, edit, and delete notes
- Secure data storage

---

## Tech Stack

### Frontend
- React.js
- Tailwind CSS
- Socket.IO Client

### Backend
- Node.js
- Express.js
- Socket.IO

### Database
- MongoDB

---

## Project Structure


---

## How It Works (High-Level)

- The frontend connects to the backend using Socket.IO.
- Each note acts as a shared room.
- When a user edits a note, changes are broadcast to all connected users in real time.
- Notes are periodically saved to the database.

---

##  Project Status
Under development

---

## Future Enhancements
- Cursor tracking for collaborators
- Version history and rollback
- Sharing notes via links
- Rich text formatting
- Dark mode

---

## Author
**Jupitoora Kaushik**
- GitHub: https://github.com/your-jupitoora
