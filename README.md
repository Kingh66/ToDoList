# 🌟 Premium Todo List Application


A modern, feature-packed Todo List application built with clean UI, smart filtering, and both API and offline support.

---

## ✨ Features

- 🔄 **Dual Data Source** – Fetches todos from an API first, then falls back to `localStorage`
- 🛠 **Full CRUD** – Create, Read, Update, Delete todos
- 🎨 **Modern UI** – Premium look and feel with smooth animations
- 📱 **Responsive Design** – Works beautifully on all screen sizes
- 🧠 **Smart Filtering** – Filter by All, Completed, or Pending tasks
- 🚀 **Real-Time Feedback** – Toast notifications for every action
- 🌐 **Offline Ready** – Functional without internet
- 🖱 **Icon-Based Actions** – Quick edit and delete with intuitive icons

---

## 🛠 Tech Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Icons**: Font Awesome 6
- **API**: [JSONPlaceholder](https://jsonplaceholder.typicode.com/) (Mock REST API)
- **Storage**: `localStorage` for persistence

---

## 🚀 Getting Started

### 1. Clone the repo
```bash
git clone https://github.com/Kingh66/TodoList.git
```

### 2. Run the app  
Simply open `index.html` in your browser.  
✅ No build tools or dependencies required.

---

## 🌐 API Integration

This app uses [JSONPlaceholder](https://jsonplaceholder.typicode.com/) to simulate a real backend:

| Method | Endpoint           | Description         |
|--------|--------------------|---------------------|
| GET    | `/todos`           | Fetch todos         |
| POST   | `/todos`           | Add a new todo      |
| PUT    | `/todos/:id`       | Update a todo       |
| DELETE | `/todos/:id`       | Delete a todo       |

---

## 📁 Project Structure

```
ToDoList/
├── index.html         # Main app file
├── styles.css         # External CSS (optional)
├── script.js          # External JS logic
├── README.md          # Project documentation
└── screenshot.png     # App preview
```

---

## 🎨 Customization

You can easily change the theme by editing these CSS variables in `styles.css`:

```css
:root {
  --primary: #6366f1;
  --danger: #ef4444;
  --warning: #f59e0b;
  --success: #22c55e;
  --text: #0f172a;
  --light-bg: #f8fafc;
  --border: #e2e8f0;
}
```

---

## 🤝 Contributing

Contributions are more than welcome! Here's how:

1. Fork the repository  
2. Create your feature branch  
   ```bash
   git checkout -b feature/AmazingFeature
   ```
3. Commit your changes  
   ```bash
   git commit -m "Add AmazingFeature"
   ```
4. Push to GitHub  
   ```bash
   git push origin feature/AmazingFeature
   ```
5. Open a Pull Request 🎉

---

## 📄 License

This project is licensed under the **MIT License**. See the `LICENSE` file for details.

---

Made with ❤️ by Sizwe Mthembu 
🔗 [Live Demo](#) • 🐞 [Report Bug](https://portfolio-vo6v.onrender.com/)
