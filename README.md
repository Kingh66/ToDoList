# Premium Todo List Application

![App Screenshot](https://i.imgur.com/JqYXOzL.png) *(Replace with actual screenshot)*

A modern, feature-rich Todo List application with API integration, local storage persistence, and premium styling.

## Features ✨

- **Dual Data Source** - Fetches from API first, falls back to local storage
- **CRUD Operations** - Create, Read, Update, Delete todos
- **Beautiful UI** - Modern design with smooth animations
- **Responsive Design** - Works on all device sizes
- **Smart Filtering** - View All/Completed/Pending tasks
- **Instant Feedback** - Toast notifications for all actions
- **Offline Support** - Works without internet connection
- **Icon-Based Actions** - Intuitive edit/delete buttons

## Tech Stack 🛠️

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Icons**: Font Awesome 6
- **API**: JSONPlaceholder (mock REST API)
- **Storage**: LocalStorage for persistence

## Installation & Usage 🚀

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/todo-list-app.git
Open index.html in your browser

No build step or dependencies required!

API Integration 🌐
The app uses JSONPlaceholder for mock API operations:

GET /todos - Fetch initial todos

POST /todos - Add new todo

PUT /todos/:id - Update todo

DELETE /todos/:id - Remove todo

Code Structure 📂
Copy
todo-list-app/
├── index.html          # Main application file
├── README.md           # This documentation
└── (screenshot.png)    # App screenshot
Customization 🎨
Easily customize by editing these CSS variables:

css
Copy
:root {
  --primary: #6366f1;     /* Primary brand color */
  --danger: #ef4444;      /* Delete/destructive actions */
  --warning: #f59e0b;     /* Edit/warning actions */
  --success: #22c55e;     /* Success notifications */
  --text: #0f172a;        /* Main text color */
  --light-bg: #f8fafc;    /* Background color */
  --border: #e2e8f0;      /* Border color */
}
Contributing 🤝
Contributions are welcome! Please follow these steps:

Fork the project

Create your feature branch (git checkout -b feature/AmazingFeature)

Commit your changes (git commit -m 'Add some amazing feature')

Push to the branch (git push origin feature/AmazingFeature)

Open a Pull Request

License 📄
This project is licensed under the MIT License - see the LICENSE file for details.

Made with ❤️ by [Your Name] | Live Demo | Report Bug
