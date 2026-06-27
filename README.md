# AI-Resume-Builder

An AI-powered Resume Builder built using the MERN Stack that enables users to create, edit, manage, and download professional resumes with intelligent AI assistance.

## Features

* User Authentication (JWT Based)
* Secure Login & Registration
* Create and Manage Multiple Resumes
* AI-Powered Resume Content Generation and Enhancement
* Professional Resume Templates
* Resume Preview in Real Time
* Profile Image Upload Support
* Resume Data Storage using MongoDB
* Responsive User Interface
* Modern Dashboard Experience

## Tech Stack

### Frontend

* React.js
* Redux Toolkit
* React Router DOM
* Tailwind CSS
* Axios

### Backend

* Node.js
* Express.js
* MongoDB Atlas
* Mongoose
* JWT Authentication
* bcrypt.js
* Multer
* ImageKit

### AI Integration

* Google Gemini API (via OpenAI SDK Compatibility Layer)

## Project Architecture

```bash
client/
├── src/
│   ├── components/
│   ├── pages/
│   ├── assets/
│   ├── app/
│   └── configs/

server/
├── controllers/
├── models/
├── routes/
├── middlewares/
├── configs/
└── server.js
```

## Installation

### Clone Repository

```bash
git clone https://github.com/Laxminarayan-Choudhary/AI-Resume-Builder.git
```

### Backend Setup

```bash
cd server
npm install
```

Create `.env`

```env
JWT_SECRET=your_secret_key

MONGODB_URI=your_mongodb_uri

IMAGEKIT_PRIVATE_KEY=your_imagekit_private_key

OPENAI_API_KEY=your_gemini_api_key
OPENAI_BASE_URL=https://generativelanguage.googleapis.com/v1beta/openai/
OPENAI_MODEL=gemini-2.5-flash
```

Run Backend

```bash
npm run server
```

### Frontend Setup

```bash
cd client
npm install
npm run dev
```

## Future Improvements

* ATS Resume Score Checker
* Dark Mode
* Additional Resume Templates
* Resume Sharing via Public Link
* Resume Analytics Dashboard
* Drag and Drop Section Management

## Author

Laxminarayan Choudhary

B.Tech, Chemical Engineering
Indian Institute of Technology (BHU), Varanasi

GitHub:
https://github.com/Laxminarayan-Choudhary

## License

This project is intended for educational and portfolio purposes.
