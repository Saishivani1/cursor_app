# AI First Lab

A full-stack application for managing AI lab resources and user authentication.

## Features

- User authentication (login/signup)
- Password reset functionality
- User profile management
- Admin dashboard
- Resource management
- Progress tracking

## Tech Stack

### Frontend
- React.js
- React Router
- Axios
- CSS

### Backend
- Node.js
- Express.js
- SQLite3
- JWT Authentication
- Nodemailer

## Setup Instructions

1. Clone the repository:
```bash
git clone https://github.com/Saishivani1/ai-first-lab.git
cd ai-first-lab
```

2. Install backend dependencies:
```bash
cd backend
npm install
```

3. Install frontend dependencies:
```bash
cd frontend/frontend
npm install
```

4. Create a `.env` file in the backend directory with the following variables:
```
EMAIL_SERVICE=gmail
EMAIL_USER=your-email@gmail.com
EMAIL_PASSWORD=your-app-specific-password
EMAIL_FROM=your-email@gmail.com
```

5. Start the backend server:
```bash
cd backend
npm start
```

6. Start the frontend development server:
```bash
cd frontend/frontend
npm start
```

## Environment Variables

### Backend (.env)
- `EMAIL_SERVICE`: Email service provider (e.g., gmail)
- `EMAIL_USER`: Email address for sending reset links
- `EMAIL_PASSWORD`: App-specific password for the email account
- `EMAIL_FROM`: Sender email address

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License. 