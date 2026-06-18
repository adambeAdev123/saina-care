# SAINA Care Portal 🌿

SAINA Care Portal is a modern, comprehensive web application designed to bridge the gap between students and mental health professionals. It provides a seamless interface for students to request counseling, chat securely with counselors, and access mental health resources, while equipping counselors with a powerful dashboard to manage appointments and student cases.

## ✨ Features

### For Students
* **Dashboard Hub:** A personalized hub to view upcoming appointments and recent activity.
* **Appointment Scheduling:** Easily request counseling sessions with available counselors.
* **Secure Chat:** Communicate directly and securely with assigned counselors.
* **Resource Vault:** Access a curated library of mental health resources and reading materials.

### For Counselors
* **Counselor Dashboard:** A comprehensive overview of daily schedules and active student cases.
* **Availability Management:** Intuitive interface to set and update working hours and availability matrix.
* **Case Management:** Detailed sidebars and tools to track student progress and history.

## 🚀 Tech Stack

* **Frontend Framework:** React 18 with TypeScript and Vite
* **Styling:** Tailwind CSS (with beautiful UI components and Framer Motion animations)
* **Backend / Database:** Supabase
* **AI Integration:** Google Gemini API
* **Icons:** Lucide React

## 🛠️ Getting Started

### Prerequisites
Make sure you have [Node.js](https://nodejs.org/) installed on your machine.

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/adambeAdev123/saina-care.git
   cd saina-care
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Environment Setup:**
   Create a `.env.local` file in the root directory and add your API keys:
   ```env
   VITE_GEMINI_API_KEY=your_gemini_api_key_here
   # Add Supabase keys if applicable
   ```

4. **Run the development server:**
   ```bash
   npm run dev
   ```

5. Open your browser and navigate to the localhost URL provided in the terminal (usually `http://localhost:5173`) to see the app in action!
