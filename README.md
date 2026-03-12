```markdown
# MindStack Frontend

A high-performance, gamified quiz and learning management frontend built with **React 19**, **TypeScript**, and **Vite**. This platform is designed to provide an interactive and responsive experience for both students and educators, supporting web and mobile environments.

## 🌟 Key Features

### 🎓 Student Experience
* **Gamified Learning**: Features interactive components like achievement badges, progress widgets, and gamified cards to enhance engagement.
* **Real-time Quizzes**: Take quizzes with real-time feedback and dynamic UI interactions powered by GSAP.
* **Personal Dashboard**: Visualize learning progress and quiz history through interactive charts using Recharts.
* **Leaderboards & Notifications**: Compete with others and stay updated with real-time notifications via WebSockets.
* **Premium Subscription**: Integrated payment flows for upgrading to premium membership.

### 👨‍🏫 Teacher & Admin Tools
* **Quiz Management**: Comprehensive interface for creating, editing, and managing quizzes.
* **Bulk Import**: Support for importing quiz data from external files (e.g., Word documents via Mammoth).
* **Admin Control Center**: Dedicated dashboard for user management and platform-wide analytics.

## 🛠 Tech Stack

* **Framework**: React 19 (Functional Components & Hooks).
* **Build Tool**: Vite for fast development and optimized production builds.
* **Language**: TypeScript for type-safe development.
* **Styling**: Tailwind CSS with Radix UI primitives and Lucide icons.
* **Animations**: GSAP (GreenSock Animation Platform) for smooth transitions.
* **State & Data**: Axios for REST APIs and Socket.io-client for real-time updates.
* **Backend Integration**: Firebase for authentication and cloud services.
* **Mobile**: Capacitor for cross-platform mobile deployment.

## 📂 Project Structure

* `src/components/gamified`: UI components for gamification (badges, progress bars).
* `src/components/quizzes`: Core quiz logic, taking quizzes, and results.
* `src/components/teachers`: Management pages for educators and admins.
* `src/components/ui`: Reusable, accessible UI primitives powered by Radix UI.
* `src/services`: API clients and WebSocket configuration.
* `src/firebase`: Firebase configuration and initialization.

## 🚀 Getting Started

### Prerequisites
* Node.js (Latest LTS recommended)
* npm or yarn

### Installation
1. Clone the repository:
   ```bash
   git clone [https://github.com/your-username/mindstack-frontend.git](https://github.com/your-username/mindstack-frontend.git)

```

2. Install dependencies:
```bash
npm install

```


3. Set up environment variables:
Copy `.env.example` to `.env` and fill in your Firebase and API credentials.

### Development

Run the development server:

```bash
npm run dev

```

### Production

Build the project for production:

```bash
npm run build

```

## 📜 Available Scripts

* `dev`: Start Vite development server.
* `build`: Compile TypeScript and build for production.
* `lint`: Run ESLint to find and fix code issues.
* `preview`: Preview the production build locally.
