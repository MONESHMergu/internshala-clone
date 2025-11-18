# Internshala Clone

A full-stack web application clone of Internshala, built with modern web technologies. This platform allows users to browse and apply for internships and jobs, while admins can manage and post opportunities.

## 🚀 Features

- **User Authentication**: Firebase-based authentication system
- **Internship & Job Listings**: Browse available internships and jobs
- **Application Management**: Apply for opportunities and track applications
- **Admin Panel**: Manage internships, jobs, and applications
- **Responsive Design**: Mobile-friendly interface with Tailwind CSS
- **Real-time Updates**: Redux state management for seamless user experience

## 🛠️ Tech Stack

### Frontend
- **Framework**: Next.js 15.2.1
- **Language**: TypeScript
- **Styling**: Tailwind CSS 4
- **State Management**: Redux Toolkit
- **Authentication**: Firebase 11.4.0
- **UI Components**: Lucide React, Swiper
- **HTTP Client**: Axios
- **Notifications**: React Toastify

### Backend
- **Runtime**: Node.js
- **Framework**: Express.js 4.21.2
- **Database**: MongoDB with Mongoose 8.12.1
- **Development**: Nodemon 3.1.9
- **Middleware**: CORS, Body-parser
- **Environment**: dotenv

## 📦 Installation

### Prerequisites
- Node.js (v14 or higher)
- MongoDB (local or cloud instance)
- Git

### Clone the Repository
```bash
git clone https://github.com/MONESHMergu/internshala-clone.git
cd internshala-clone-main
```

### Backend Setup
```bash
cd backend
npm install
```

Create a `.env` file in the backend directory:
```env
MONGODB_URI=your_mongodb_connection_string
PORT=5000
```

Start the backend server:
```bash
npm start
```

### Frontend Setup
```bash
cd internarea
npm install
```

Create a `.env.local` file in the internarea directory with your Firebase configuration:
```env
NEXT_PUBLIC_FIREBASE_API_KEY=your_api_key
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=your_auth_domain
NEXT_PUBLIC_FIREBASE_PROJECT_ID=your_project_id
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=your_storage_bucket
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
NEXT_PUBLIC_FIREBASE_APP_ID=your_app_id
```

Start the development server:
```bash
npm run dev
```

The application will be available at `http://localhost:3000`

## 📁 Project Structure

```
internshala-clone-main/
├── backend/
│   ├── Model/
│   │   ├── Application.js
│   │   ├── Internship.js
│   │   └── Job.js
│   ├── Routes/
│   │   ├── admin.js
│   │   ├── application.js
│   │   ├── index.js
│   │   ├── internship.js
│   │   └── job.js
│   ├── db.js
│   ├── index.js
│   └── package.json
└── internarea/
    ├── src/
    │   ├── Components/
    │   ├── Feature/
    │   ├── firebase/
    │   ├── pages/
    │   ├── store/
    │   └── styles/
    └── package.json
```

## 🔑 Key Features

### For Users
- Browse internships and jobs
- View detailed information about opportunities
- Submit applications
- Track application status
- User profile management

### For Admins
- Post new internships and jobs
- Manage applications
- Review applicant details
- Admin authentication

## 🌐 API Endpoints

- `/api/internship` - Internship operations
- `/api/job` - Job operations
- `/api/application` - Application management
- `/api/admin` - Admin functionalities

## 👨‍💻 Author

**Monesh Mergu**
- Email: moneshmergu@gmail.com
- Phone: +91 9699545020
- Location: Solapur, Maharashtra
- GitHub: [@MONESHMergu](https://github.com/MONESHMergu)

## 📄 License

This project is licensed under the ISC License.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

## ⭐ Show your support

Give a ⭐️ if this project helped you!
