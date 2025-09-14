# file-organizer-flask.
# File Organizer Flask App

A web application built with Flask that lets users upload files (or drag & drop), organizes them into folders by file extension, and optionally stores metadata in a SQLite database. Admin users have access to view file upload history.

## Features

- Upload multiple files via browser  
- Drag & drop file upload (optional)  
- Files are automatically moved into subfolders like `Images/`, `Documents/`, etc.  
- SQLite database logs file name, category (extension), and upload timestamp  
- Admin-only view for database records  
- Frontend displays current folder structure and uploaded files  

## Setup & Run Locally

1. Clone the repo:

   ```bash
   git clone https://github.com/kasaudhanshivani/file-organizer-flask.git
   cd file-organizer-flask
