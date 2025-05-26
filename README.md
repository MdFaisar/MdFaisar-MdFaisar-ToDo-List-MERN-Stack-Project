# MERN To-Do List Application

A full-stack To-Do List application built with the MERN stack (MongoDB, Express.js, React.js, Node.js) that allows users to efficiently manage their tasks with full CRUD operations.

## 🚀 Live Demo

[![Live Demo](https://img.shields.io/badge/Live%20Demo-View%20App-brightgreen?style=for-the-badge&logo=heroku)](https://your-demo-link.herokuapp.com)

*Click the button above to view the live application*

## 📝 Description

This To-Do List application provides a clean and intuitive interface for task management. Users can seamlessly add new tasks with titles and descriptions, edit existing tasks, delete completed or unwanted tasks, and view all their tasks in an organized manner. The application features a responsive design that works perfectly across desktop and mobile devices.

### Key Features

- ✅ **Add Tasks**: Create new tasks with title and description
- ✏️ **Edit Tasks**: Modify existing task details
- 🗑️ **Delete Tasks**: Remove completed or unwanted tasks
- 👀 **View Tasks**: Display all tasks in an organized list format
- 📱 **Responsive Design**: Optimized for all device sizes
- 🔄 **Real-time Updates**: Instant synchronization with the database
- 🎨 **Modern UI**: Clean and user-friendly interface

## 🛠️ Technologies Used

### Frontend
- **React.js** - UI library for building user interfaces
- **CSS3** - Styling and responsive design
- **Axios** - HTTP client for API requests
- **React Hooks** - State management

### Backend
- **Node.js** - JavaScript runtime environment
- **Express.js** - Web application framework
- **MongoDB** - NoSQL database
- **Mongoose** - MongoDB object modeling

### Development Tools
- **Nodemon** - Development server auto-restart
- **Concurrently** - Run multiple scripts simultaneously
- **CORS** - Cross-origin resource sharing
- **dotenv** - Environment variable management

## 📋 Prerequisites

Before running this application, make sure you have the following installed:

- **Node.js** (version 14.0 or higher)
- **npm** (Node Package Manager)
- **MongoDB** (local installation or MongoDB Atlas account)
- **Git** (for cloning the repository)

You can verify your installations by running:
```bash
node --version
npm --version
mongod --version
```

## 🚀 Installation & Setup

### 1. Clone the Repository
```bash
git clone https://github.com/MdFaisar/ToDo-List-MERN-Stack-Project.git
cd ToDo-List-MERN-Stack-Project
```

### 2. Install Backend Dependencies
```bash
# Navigate to backend directory
cd backend
npm install 
```

### 3. Install Frontend Dependencies
```bash
# Navigate to frontend directory
cd ../frontend
npm install --save-dev concurrently
```

### 4. Start MongoDB
Make sure MongoDB is running on your system,
If not, go to services in the settings, search mongodb and start the service mannually
```bash
# For local MongoDB installation
mongod
```

### 5. Run the Application

#### Option 1: Run Both Concurrently
```bash
# From frontend directory
cd frontend
npm run dev
```

#### Option 2: Run Frontend and Backend Separately

```bash
# Terminal 1 - Start Backend Server
cd backend
node service.js

# Terminal 2 - Start Frontend Development Server
cd frontend
npm start
```

The application will be available at:
- **Frontend**: http://localhost:3000
- **Backend API**: http://localhost:5000


## 🎯 Usage

1. **Adding a Task**: Click the "Add Task" button, fill in the title and description, then submit
2. **Editing a Task**: Click the edit icon next to any task, modify the details, and save
3. **Deleting a Task**: Click the delete icon next to any task to remove it
4. **Viewing Tasks**: All tasks are displayed in the main interface with their titles and descriptions

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Your Name**
- GitHub: [@yourusername](https://github.com/MdFaisar)
- LinkedIn: [Your LinkedIn](https://www.linkedin.com/in/mohammedfaisar/)
- Email: amohammedfaisar@gmail.com

## 🙏 Acknowledgments

- Thanks to the MERN stack community for excellent documentation
- Inspiration from various todo applications
- Icons from [React Icons](https://react-icons.github.io/react-icons/)

## 🐛 Known Issues

- None at the moment. Please report any bugs in the Issues section.

## 🔮 Future Enhancements

- [ ] User authentication and authorization
- [ ] Task categories and tags
- [ ] Due date functionality
- [ ] Task priority levels
- [ ] Search and filter capabilities
- [ ] Dark mode toggle
- [ ] Email notifications
- [ ] Data export functionality

---

⭐ If you found this project helpful, please give it a star on my GitHub page!
