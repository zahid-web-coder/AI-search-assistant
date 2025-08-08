# AI-Powered Policy Search Assistant 🧠📜

An intelligent frontend web app built with React + TypeScript + Vite that allows users to query legal or policy documents using LLM-powered search (Gemini API). Clean UI. Lightning-fast results.

---

## 🚀 Live Demo

🔗 [Click to Open App](https://policy-ai-xi.vercel.app)

---

## 🧰 Tech Stack

- ⚛️ React + TypeScript
- ⚡ Vite for ultra-fast builds
- 🧠 Gemini API (Google AI)
- 🎨 Tailwind CSS (if used)
- 🔗 Vercel for deployment

---

## ✨ Features

- 🔍 Ask questions and get semantically matched answers
- 📄 Clean UI with Result Cards and Loaders
- 🔄 Gemini API integration for intelligent reasoning
- ⚙️ Easily extensible with your own data or APIs

---

## 🛠️ Project Structure

ai-search-assistant/
├── App.tsx # Main App component
├── index.tsx # App entry point
├── components/
│ ├── Spinner.tsx # Loading animation
│ ├── ResultCard.tsx # UI for displaying results
├── services/
│ └── geminiService.ts # LLM API handler (Gemini)
├── .env.local # Store your Gemini API key here
├── package.json # Project metadata & dependencies
├── vite.config.ts # Vite build setup

yaml
Copy
Edit

---

## 🔐 Setup & Run Locally

```bash
# 1. Clone the repo
git clone https://github.com/your-username/ai-search-assistant.git
cd ai-search-assistant

# 2. Install dependencies
npm install

# 3. Set up environment variables
echo "VITE_GEMINI_API_KEY=your_api_key_here" > .env.local

# 4. Run the development server
npm run dev
🧠 LLM Integration
This project uses Gemini Pro via Google’s Generative AI SDK. It can be extended to support other models like GPT-4, Claude, or Ollama.

📦 Deploy
This app is deployed via Vercel. To deploy your own:

bash
Copy
Edit
# After setting up your GitHub repo:
vercel --prod
🧑‍💻 Author
Zahid Mohammed — Full Stack + AI Developer

GitHub | LinkedIn

