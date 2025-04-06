# Note-Taking App

A simple and user-friendly note-taking application built with Angular for the frontend and Node.js for the backend. This app allows users to create, edit, delete, and manage their notes.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [API Documentation](#api-documentation)
- [Contributing](#contributing)
- [License](#license)

## Overview

This Note-Taking App helps users keep track of their thoughts, tasks, and important information. It features a clean and intuitive UI and uses Node.js as the backend server for handling requests and storing notes in a database. Angular is used to build a dynamic frontend that interacts with the backend API.

## Features
- **Create Notes**: Easily create new notes with a title and content.
- **Edit Notes**: Modify your existing notes.
- **Delete Notes**: Remove notes that are no longer needed.
- **View Notes**: View all saved notes in a list format.
- **Search Notes**: Find notes using the search functionality.
- **User Authentication**: Secure login and registration to keep your notes private.

## Tech Stack

### Frontend:
- **Angular**: A TypeScript-based framework for building dynamic web applications.
- **Bootstrap**: For styling and responsive design.

### Backend:
- **Node.js**: JavaScript runtime built on Chrome's V8 engine.
- **Express.js**: Web framework for Node.js to handle HTTP requests.
- **MongoDB**: NoSQL database for storing user data and notes.
- **Mongoose**: ODM (Object Data Modeling) library to interact with MongoDB.

## Installation

### Prerequisites

Before you start, ensure you have the following installed on your machine:

- **Node.js** (version >= 14)
- **npm** (Node Package Manager)
- **MongoDB** (either locally or using a cloud provider like MongoDB Atlas)

### Backend Setup (Node.js + Express)
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/note-taking-app.git
   cd note-taking-app
