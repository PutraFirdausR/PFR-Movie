# 🎬 PFR-Movie App

Welcome to the **PFR-Movie** project!  
This is a simple web application for searching movie data. It was built to practice **Asynchronous JavaScript** concepts (such as `fetch` or `AJAX`) by retrieving movie data in *real-time* from a public *Application Programming Interface* (API).

🔗 **Live Demo:** [Try Searching for Movies Here!](https://putra-movie.vercel.app)

## ✨ Features
- **Movie Title Search:** Users can type in a movie title and the application will display the results.
- **Dynamic Data:** The displayed data (such as posters, release year, etc.) is fetched directly from a third-party database (OMDB API).
- **Lightweight & Fast:** Built with *Vanilla JavaScript* without any heavy frameworks.

## 🛠️ Technologies Used
- **HTML5** (`index.html` for the user interface skeleton)
- **Vanilla JavaScript** (`script.js` to handle event listeners and fetching data from the API)
- **OMDB API** (The Open Movie Database - as the movie data source)

## 📂 File Structure
Based on this repository, the file structure is very minimalist and focused on functionality:
```text
PFR-Movie/
├── index.html          # Main web interface and search form
├── script.js           # Data fetching logic (Fetch API) and DOM manipulation
└── README.md           # Project documentation (this file)
```

## 💻 How to Run Locally
If you want to run or modify this code on your local machine:

1. **Clone this repository:**

```Bash
git clone [https://github.com/PutraFirdausR/PFR-Movie.git](https://github.com/PutraFirdausR/PFR-Movie.git)
```

2. **Open the project folder:**

```Bash
cd PFR-Movie
```

3. **Run the Application:**
   Simply double-click the index.html file to open it in your browser.

⚠️ API Key Note: > This project uses the OMDB API. If you want to develop it further, you might need to register at omdbapi.com to get your own API Key and insert it into the script.js file.
