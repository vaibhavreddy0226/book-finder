# 📚 Book Finder Web App

A simple web application that allows users to search for an **author** and retrieve a list of their published books using the **Open Library API**.

The app displays up to **10 books** of the searched author along with their **titles and cover images**.

---

## 🚀 Live Demo
🔗 https://vaibhavreddy0226.github.io/book-finder/

---

## 🧠 Features

- 🔍 Search books by **author name**
- 📚 Displays **up to 10 books** for each search
- 🖼️ Shows **book title and cover image**
- 🌐 Uses real-time data from Open Library API
- ⚡ Lightweight and fast (no frameworks used)

---

## 🛠️ Tech Stack

- **HTML5** – Page structure  
- **CSS3** – Styling and layout  
- **JavaScript (Vanilla JS)** – API handling and DOM updates  
- **Open Library API** – Data source  

---

## 📂 Project Structure

```
book-finder/
│── index.html # Main webpage
│── style.css # Styling
│── script.js # API logic and rendering
└── README.md # Documentation
```


---

## ⚙️ How It Works

1. User enters an **author name** in the search bar  
2. A request is sent to the Open Library API  
3. The API returns a list of books by that author  
4. The app filters and displays **10 books**  
5. Each result shows:
   - 📖 Book Title  
   - 🖼️ Cover Image  

---

## 🔗 API Used

- Open Library Search API
```
https://openlibrary.org/search.json?author=AUTHOR_NAME
```
