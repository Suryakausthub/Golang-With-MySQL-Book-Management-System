📖 Golang-With-MySQL-Book-Management-System

A simple RESTful API for managing books using Golang, Gorilla Mux, and GORM with MySQL as the database.

🚀 Features
✅ CRUD Operations: Create, Read, Update, and Delete books
✅ RESTful API Design for easy integration
✅ MySQL Database for persistent storage
✅ Gorilla Mux for flexible routing
✅ Docker Support for easy deployment
✅ Scalable & Efficient architecture

🛠️ Technologies Used
🐹 Golang – Backend programming language
🔄 Gorilla Mux – HTTP router for API endpoints
🛢️ GORM – ORM for MySQL integration
🗄️ MySQL – Database for storing books
🐳 Docker – Containerization for deployment
📥 Installation & Setup


1️⃣ Clone the Repository
git clone https://github.com/Suryakausthub/Golang-With-MySQL-Book-Management-System.git
cd Golang-With-MySQL-Book-Management-System

2️⃣ Install Dependencies
Ensure Golang is installed, then run:
go mod tidy

3️⃣ Configure Database
Edit config/config.go and update your MySQL credentials:
d, err := gorm.Open("mysql", "your-username:your-password@tcp(localhost:3306)/bookstore?charset=utf8&parseTime=True&loc=Local")

4️⃣ Run the Application
go run main.go
The server will start at http://localhost:8080.

📂 Project Structure:
Golang-With-MySQL-Book-Management-System/
│── cmd/              # Application entry point
│── pkg/
│   ├── config/       # Database configuration
│   ├── controllers/  # Request handlers
│   ├── models/       # Database models
│   ├── routes/       # API routes
│   ├── utils/        # Utility functions
│── go.mod            # Go module file
│── go.sum            # Dependency tracking
│── main.go           # Main application entry point
│── README.md         # Documentation
