# MindStack Backend https://github.com/Sazzazaa/MindStack-Backend
# MindStack Frontend (Student Project)

This is a frontend repository for **MindStack**, a quiz-based learning platform. This project was developed as part of a final-year university assignment. It is currently an **incomplete work-in-progress** and is intended strictly for **educational and non-commercial purposes**.

## 📌 Project Overview

MindStack is a simple web application designed to help users practice quizzes and track their basic learning progress. As a student project, it focuses on implementing core frontend functionalities using modern technologies.

### Main Features (WIP)
* **Quiz Participation**: Users can browse and take available quizzes with a simple interface.
* **User Dashboard**: A basic profile page to view quiz history and simple progress statistics.
* **Quiz Management**: Tools for creating and managing quiz content, designed for basic educator workflows.
* **Notifications**: A simple system to keep track of platform updates.
* **Responsive Layout**: Designed to work across different screen sizes using Tailwind CSS.

## 🛠 Tech Stack

Since this is a learning project, various libraries were explored to understand frontend development:
* **Core Framework**: React 19 & TypeScript (built with Vite).
* **UI Components**: Built using Radix UI primitives and Tailwind CSS for styling.
* **Data Handling**: Axios for API communication and Firebase for basic authentication.
* **Visuals**: Recharts for simple data visualization and GSAP for minor interface transitions.
* **Real-time**: Integration of Socket.io-client for basic real-time updates.

## 📂 Basic Structure

* `src/components/quizzes`: Core logic for taking quizzes and viewing results.
* `src/components/teachers`: Experimental features for quiz creation and management.
* `src/components/layout`: Common UI elements like the navigation bar and footer.
* `src/services`: Simple API and WebSocket connection handlers.

## 🚀 How to Run (Local Development)

*Note: This project requires a corresponding backend to function fully.*

1.  **Clone the project**:
    ```bash
    git clone [https://github.com/your-username/mindstack-frontend.git](https://github.com/your-username/mindstack-frontend.git)
    ```
2.  **Install dependencies**:
    ```bash
    npm install
    ```
3.  **Run in development mode**:
    ```bash
    npm run dev
    ```

## ⚠️ Disclaimer

This project is a **student assignment**. Many features may be incomplete, unoptimized, or contain bugs. It is not intended for production use or any commercial activity. All resources used are for learning purposes.
