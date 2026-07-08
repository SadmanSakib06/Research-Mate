# 📚 Research Mate 

A modern research assistant dashboard built with **React**, **TypeScript**, **Vite**, and **Tailwind CSS**. Designed to streamline academic workflows through AI-assisted paper summarization, citation management, and intelligent research support.

---

## ✨ Features

- 📄 AI-assisted research paper summarization
- 🔍 Keyword extraction and highlight-ready summaries
- 📝 Citation management interface (APA, MLA, IEEE)
- 💬 Integrated chatbot for research assistance
- ⚡ Fast and lightweight architecture powered by Vite
- 🎨 Responsive interface built with Tailwind CSS
- ♻️ Modular component-based design

---

## 📸 Preview

![Dashboard Preview](demo.png)

---

## 🛠️ Built With

- React
- TypeScript
- Vite
- Tailwind CSS

---

## 🧠 AI Integration

The frontend is designed to communicate with AI-powered backend services, including:

- Research paper summarization
- Large Language Models (LLMs)
- Citation formatting services
- Research assistant chatbot APIs

Example request:

```ts
await fetch("/api/summarize", {
  method: "POST",
  headers: {
    "Content-Type": "application/json",
  },
  body: JSON.stringify({
    text: paperContent,
  }),
});
```

---

## 📁 Project Structure

```text
ResearchMate-Dashboard/
├── src/
│   ├── components/
│   ├── pages/
│   ├── hooks/
│   ├── utils/
│   ├── App.tsx
│   └── main.tsx
├── public/
├── package.json
├── vite.config.ts
└── README.md
```

---

## 🚀 Getting Started

### Clone the repository

```bash
git clone https://github.com/SadmanSakib06/Research-Mate-Dashboard.git
cd Research-Mate-Dashboard
```

### Install dependencies

```bash
npm install
```

### Start the development server

```bash
npm run dev
```

Open your browser:

```text
http://localhost:5173
```

---

## ⚙️ Available Scripts

```bash
npm run dev
npm run build
npm run preview
```

---

## 📌 Project Status

🚧 Prototype

This project demonstrates the frontend architecture of an AI-assisted research dashboard. Backend AI services are represented through planned API integrations.

---

## 🔮 Future Improvements

- 🤖 LLM-powered paper summarization
- 📑 Semantic paper search
- 📚 PDF parsing and annotation
- ☁️ Cloud synchronization
- 🔍 Intelligent literature review assistant

---

## 📄 License

MIT License.
