# Golang Bookstore API

A simple RESTful API for managing a bookstore, built using Golang, Gorilla Mux, and GORM.

## Features

- 📚 **CRUD operations** for books (Create, Read, Update, Delete)
- 🔗 **RESTful API design**
- 🛢️ **MySQL database integration**
- 🔧 **Gorilla Mux for routing**
- 🏗️ **Docker support for containerization**
- ⚡ **Scalable and efficient architecture**

## Technologies Used

- **Golang** - Backend programming language
- **Gorilla Mux** - HTTP router for API endpoints
- **GORM** - ORM for MySQL database integration
- **MySQL** - Database for storing book records
- **Docker** - Containerization for deployment

## Installation & Setup

### 1. Clone the Repository


git clone https://github.com/Suryakausthub/Golang-With-MySQL-Book-Management-System.git
cd golang-project


2. Install Dependencies
Ensure you have Golang installed. Then, install the required packages:
go mod tidy

3. Configure Database
Edit config/config.go and update your MySQL connection details:
d, err := gorm.Open("mysql", "your-username:your-password@tcp(localhost:3306)/bookstore?charset=utf8&parseTime=True&loc=Local")

4. Run the Application
go run main.go
The server will start at http://localhost:8080.

Project Structure:
golang-bookstore/
│── pkg/
│   ├── config/       # Database configuration
│   ├── controllers/  # Request handlers
│   ├── models/       # Database models
│   ├── routes/       # API routes
│   ├── utils/        # Utility functions
│── main.go           # Entry point
│── go.mod            # Go module file
│── README.md         # Documentation

