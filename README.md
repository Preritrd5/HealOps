# HealOps AI 🚀
### Autonomous CI/CD Healing Platform

**HealOps AI** is an advanced, autonomous agentic system designed to self-heal broken CI/CD pipelines. By leveraging multi-agent AI architectures, it detects, diagnoses, and fixes code issues in real-time—ranging from simple linting errors to complex logic failures.

---

## 🌟 Key Features

- **🤖 Multi-Agent Architecture**  
  Orchestrates specialized AI agents for detection, diagnosis, and patching.
  
- **🔍 Intelligent Repository Analysis**  
  Scans GitHub repositories to identify bugs, syntax errors, and performance bottlenecks.

- **⚡ Autonomous Self-Healing**  
  Automatically creates a fix branch, generates code patches, and validates them via simulation.

- **📊 Interactive Dashboard**  
  Visualizes the healing process with real-time logs, failure charts, and health scores.

- **📈 Detailed Reporting**  
  Generates comprehensive reports (PDF & JSON) and commits analysis summaries directly to GitHub.

- **🔒 Secure & Scalable**  
  Built with Supabase for secure backend operations and GitHub authentication.

---

## 🛠️ Tech Stack

- **Frontend:** React, TypeScript, Vite
- **Styling:** Tailwind CSS, shadcn/ui, Framer Motion
- **AI Engine:** Google Generative AI (Gemini)
- **Backend:** Supabase Edge Functions
- **Integration:** GitHub API (Octokit)

---

## 🚀 Getting Started

Follow these steps to set up the project locally.

### Prerequisites
- Node.js (v18 or higher)
- npm or yarn

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/healops-ai.git
   cd healops-ai
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```

4. **Open the app**  
   Visit `http://localhost:8080` in your browser.

---

## 📖 How to Use

1. **Enter Repository URL**  
   Paste the link to the GitHub repository you want to analyze.
2. **Provide Team Details**  
   Enter your Team Name and Leader Name for report generation.
3. **Start Analysis**  
   Click "Analyze Repository" to trigger the AI agents.
4. **Review & Heal**  
   Watch the live simulation as agents fix issues. Review the generated fixes in the dashboard.
5. **Export Results**  
   Download a PDF report or view the committed changes on GitHub.

---

