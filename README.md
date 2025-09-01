# Freedemy: Your Gateway to Free Online Courses 🚀

Freedemy is a web application that aggregates and presents free online courses, primarily from Discudemy, making learning accessible to everyone. It scrapes course data, caches it for performance, and provides a user-friendly interface to browse and discover new learning opportunities.

## 🚀 Key Features

*   **Course Aggregation:** Automatically scrapes course information (title, description, image, link, coupon) from Discudemy.
*   **Data Caching:** Implements in-memory caching using `node-cache` to minimize scraping frequency and improve response times.
*   **User-Friendly Interface:** Presents courses in a clean and intuitive layout using EJS templating and Tailwind CSS.
*   **Coupon Link Extraction:** Extracts the final coupon link for each course, ensuring users can directly access the free content.
*   **HTML Sanitization:** Employs `DOMPurify` to sanitize course descriptions and prevent XSS vulnerabilities.
*   **Search Functionality:** Allows users to search for specific courses (implementation pending in `search.ejs`).
*   **SEO Optimized:** Includes meta tags for improved search engine visibility and social media sharing.

## 🛠️ Tech Stack

*   **Frontend:**
    *   HTML
    *   CSS (Tailwind CSS)
    *   JavaScript
    *   EJS (Templating Engine)
    *   Font Awesome (Icons)
*   **Backend:**
    *   Node.js
    *   Express.js (Web Framework)
*   **Scraping:**
    *   Axios (HTTP Client)
    *   Cheerio (HTML Parsing)
*   **Caching:**
    *   Node-Cache (In-Memory Caching)
*   **Security:**
    *   DOMPurify (HTML Sanitization)
*   **Utilities:**
    *   Path (File Path Manipulation)
    *   jsdom (DOM Implementation)

## 📦 Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

*   Node.js (v14 or higher)
*   npm (Node Package Manager) or yarn

### Installation

1.  **Clone the repository:**

    ```bash
    git clone <repository_url>
    cd <repository_directory>
    ```

2.  **Install dependencies:**

    ```bash
    npm install  # or yarn install
    ```

### Running Locally

1.  **Start the server:**

    ```bash
    npm start  # or node app.js
    ```

2.  **Open your browser and navigate to `http://localhost:3000` (or the port specified in your `app.js` file).**

## 📂 Project Structure

```
freedemy/
├── app.js             # Main application file (Express server)
├── scrape.js          # Web scraping functions
├── oldscrape.js       # Older version of the web scraper (likely deprecated)
├── utils.js           # Utility functions
├── views/             # EJS templates
│   ├── index.ejs      # Homepage template
│   ├── course.ejs     # Course details template
│   ├── search.ejs     # Search results template (under development)
│   └── header.ejs     # Header template (navigation bar)
├── node_modules/      # Node.js dependencies
├── package.json       # Project metadata and dependencies
├── package-lock.json  # Dependency versions (npm)
└── ...                # Other files (e.g., CSS, images)
```

## 📸 Screenshots

(Add screenshots of the application here to showcase the user interface and functionality)

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1.  Fork the repository.
2.  Create a new branch for your feature or bug fix.
3.  Make your changes and commit them with descriptive messages.
4.  Push your changes to your fork.
5.  Submit a pull request.

## 📝 License

This project is licensed under the [MIT License](LICENSE) - see the `LICENSE` file for details.

## 📬 Contact

If you have any questions or suggestions, feel free to contact me at [your-email@example.com](mailto:your-email@example.com).

## 💖 Thanks

Thank you for checking out Freedemy! I hope you find it useful for discovering free online learning resources.

This is written by [readme.ai](https://readme-generator-phi.vercel.app/).
