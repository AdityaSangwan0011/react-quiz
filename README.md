# 🧠 The React Quiz

A high-performance, interactive quiz application designed to test React and JavaScript knowledge with a focus on seamless user experience and real-time feedback.

---

## 🚀 Features

* **Dynamic Progress Tracking:** A custom-built progress bar that updates in real-time as the user navigates through the 15 questions.
* **Real-time Countdown Timer:** Built-in 450(seconds) 7 minutes 30 seconds timer to simulate a real exam environment, automatically handling quiz submission upon expiration.
* **Complex State Management:** Orchestrates multiple app states (loading, active, error, finished) using React hooks for a bug-free flow.
* **Instant Evaluation:** Provides immediate visual feedback on answers and calculates the final score upon completion.
* **Responsive Design:** Fully optimized for all screen sizes, from mobile devices to desktop monitors.

## 🛠️ Tech Stack

* **Frontend:** React.js (Hooks, Functional Components)
* **Styling:** CSS3 (Custom modules for a clean, modern UI)
* **Data:** Local JSON / REST API integration for question sets

## 📥 Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/adityaSangwan/react-quiz.git](https://github.com/adityaSangwan/react-quiz.git)

2. **Install dependencies:**
   ```Bash
    npm install

3. **Start the development server:**
   ```Bash
    npm start

4. **To Start the Mock Backend (JSON Server)**
   This server hosts your questions from the questions.json file on port 9000.
   ```Bash
   npm run server

💡 **What I Learned**
While building this project, I deepened my understanding of:

Managing complex state logic across multiple components.
Using useEffect to handle side effects like timers and data fetching.
Designing accessible and high-contrast UI patterns for educational tools.
