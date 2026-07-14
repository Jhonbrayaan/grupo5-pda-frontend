# 🚗 SystemCar

Full Stack application for vehicle and parking management, developed as an academic group project.

The project consists of a **Node.js/Express REST API** and a **server-side rendered web application using Express and EJS**, allowing users to register, manage vehicles, schedule services and access platform features.

---

# 📖 About

SystemCar was developed to simulate a complete vehicle management platform, integrating frontend and backend into a single application.

The system provides features for user registration, authentication, vehicle management, payment information registration and scheduling, following a layered architecture using Express and Sequelize.

---

# ✨ Features

- User registration and authentication
- Vehicle registration
- Payment card registration
- Vehicle management
- Scheduling page
- User profile
- REST API
- Server-side rendering with EJS

---

# 🛠 Technologies

## Backend

- Node.js
- Express
- Sequelize
- PostgreSQL
- dotenv
- CORS

## Frontend

- Express
- EJS
- Bootstrap 5
- JavaScript
- Fetch API
- HTML5
- CSS3

---

# 📂 Project Structure

```text
grupo5-pda-frontend/

backend/
├── src/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   └── serve.js

frontend/
├── public/
├── views/
└── index.js
```

---

# 🚀 Getting Started

## Clone the repository

```bash
git clone https://github.com/Jhonbrayaan/grupo5-pda-frontend.git
```

## Backend

```bash
cd backend
npm install
node src/serve.js
```

## Frontend

```bash
cd frontend
npm install
node index.js
```

Frontend:

```
http://localhost:3000
```

Backend:

```
http://localhost:3200
```

---

# 🗄 Database

The application uses **PostgreSQL** through Sequelize ORM.

Create your own `.env` file before running the application.

Example:

```env
DATABASE_HOST=
DATABASE_PORT=
DATABASE_NAME=
DATABASE_USERNAME=
DATABASE_PASSWORD=
```

---

# 🏗 Architecture

The project follows a layered architecture separating responsibilities into:

- Controllers
- Models
- Routes
- Views
- Services

This organization improves maintainability and scalability.

---

# 📌 Main Endpoints

| Method | Endpoint | Description |
|---------|----------|-------------|
| POST | /usuario | Create user |
| POST | /usuarioLogin | User login |
| GET | /usuario | List users |
| POST | /veiculo | Register vehicle |
| GET | /veiculo | List vehicles |
| POST | /cartao | Register payment card |
| POST | /estado | Register vehicle entry/exit |

---

# 🚧 Future Improvements

Some features that could be added in future versions include:

- JWT Authentication
- Password hashing
- Input validation
- Better error handling
- Automated tests
- Docker support
- CI/CD pipeline
- Environment configuration improvements

---

# 👥 Contributors

- Jhonatan Brayan
- Andressa Laurentino de Lima
- Caline Lira
- Vinicius Castro
- Vitor Ferreira Fernandes
