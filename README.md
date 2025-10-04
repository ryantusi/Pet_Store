# 🐾 Pet Store App

This is a **React-based Pet Store application** that demonstrates the use of **React Router** for navigation and routing. It fetches pet data from an API and organizes the UI into distinct pages, such as a home page, a hero section, and a page for displaying individual pets.

-----

## 🚀 Features

  * **Client-side routing**: Uses React Router to navigate between different sections of the app without a full page reload.
  * **API integration**: Fetches pet data from an external API (Petfinder API).
  * **Component-based UI**: The app is built with modular React components for better organization and reusability.

-----

## 🛠️ Tech Stack

  * **Frontend**: React
  * **Routing**: React Router
  * **API**: Petfinder API

-----

## 📂 Project Structure

```
pet-store-app/
│
├── public/                 # Static assets
├── src/
│   ├── api/                # API calls
│   │   └── petfinder/
│   │       └── index.js    # Petfinder API requests
│   ├── assets/             # Images, icons, etc.
│   ├── components/         # Reusable React components
│   │   ├── hero/
│   │   │   └── index.js    # Hero section component
│   │   ├── navigation/
│   │   │   └── index.js    # Navigation bar component
│   │   └── pet/
│   │       └── index.js    # Pet display component
│   ├── App.js              # Main application component with router setup
│   ├── App.test.js         # Test file for App.js
│   ├── index.js            # Entry point of the application
│   ├── logo.svg
│   ├── reportWebVitals.js
│   └── setupTests.js
├── LICENSE
├── package-lock.json
├── package.json
├── README.md
└── yarn.lock
```

-----

## ⚙️ Installation & Setup

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/your-username/pet-store-app.git
    cd pet-store-app
    ```

2.  **Install dependencies:**

    ```bash
    npm install
    ```

3.  **Run the app:**

    ```bash
    npm start
    ```

    The application will be available at `http://localhost:3000`.