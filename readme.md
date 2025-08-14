# AI Code Reviewer

This project is a web application that uses AI to review code snippets. Users can paste their code into an editor, submit it for review, and receive feedback directly in the application, rendered from Markdown.

## Features

-   **Code Editor**: A simple code editor with JavaScript syntax highlighting using Prism.js.
-   **AI-Powered Feedback**: Integrates with a backend service to provide AI-driven code reviews.
-   **Markdown Display**: Renders the AI's feedback in a clean, readable format using Markdown.

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine.

### Prerequisites

-   Node.js and npm installed on your machine.

### Installation & Setup

The project is divided into a `Frontend` and a `Backend`.

#### Backend

1.  Navigate to the backend project directory.
2.  Install the necessary dependencies:
    ```bash
    npm install cors
    # You will also need to install your web framework, e.g., express
    # npm install express
    ```
3.  Start the backend server:
    ```bash
    # e.g., node index.js or npm start
    ```

#### Frontend

1.  Navigate to the `Frontend` directory:
    ```bash
    cd Frontend
    ```
2.  Install the npm packages:
    ```bash
    npm install prismjs react-simple-code-editor axios react-markdown rehype-highlight highlight.js
    ```
3.  Start the frontend development server:
    ```bash
    npm run dev
    # or npm start
    ```
4.  Open your browser and go to `http://localhost:5173` (or the port specified by your Vite/React setup).

## Technologies Used

### Frontend

-   React
-   Axios
-   Prism.js
-   React Simple Code Editor
-   React Markdown
-   Highlight.js

### Backend

-   Node.js
-   CORS
-   (Presumably a web server like Express)
git clone https://github.com/joshi-jyoti/AI-Code-Reviewer
cd code-review
```

### 2️⃣ Setup the Backend

```bash
cd backend
npm install
# Add your Google Gemini API key to .env as:
# GOOGLE_GEMINI_KEY=your_google_gemini_api_key
npx nodemon
```
### 3️⃣ Setup the Frontend

```bash
cd ../Frontend
npm install
npm run dev
```
---

## ⚙️ Usage

Get started with the AI Code Reviewer in a few simple steps:

1.  **✏️ Write or paste code** in the left editor panel.
2.  **🚀 Click "Review"** to send your code to the AI reviewer.
3.  **📋 The right panel** will then display a detailed, markdown-formatted review, including:
    * Strengths of your code
    * Identified issues
    * Suggested fixes
    * General suggestions for improvement

---

## 🌟 Features

Our AI Code Reviewer comes packed with powerful features to enhance your coding workflow:

* **🤖 Real-time code review** using Google Gemini AI, providing immediate insights.
* **🌈 Syntax-highlighted code editing and review**, making your code easy to read and understand.
* **💻 Professional, readable UI** designed for an intuitive and pleasant user experience.
* **✅ Actionable, structured feedback** that helps you understand and implement improvements efficiently.

---






