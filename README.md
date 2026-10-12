# MindMap (Doc-Hoc) – Intelligent Study Companion with Adaptive Learning AI

> **Version 3.0: Smart Education + Innovation**  
> *Theme: EdTech Innovation & Smart Learning Systems*  
> *Aligned with Bureau of Indian Standards (BIS): IS 19450:2025, IS/ISO/IEC 24751, IS/ISO 21001:2018*

---

## 🌟 Overview
**MindMap (Doc-Hoc)** is an AI-powered smart study assistant that blends the structural organization of **Obsidian** with the analytical second-brain synthesis of **NotebookLM**. Wrapped in an engaging, minimalist UI inspired by **Instagram’s design philosophy** (story pills, sunset gradient accents, dark mode, smooth micro-animations), the platform transforms passive notes into an active, multi-sensory educational experience for Gen-Z students.

---

## 🚀 Key Features

### 1. 🌳 Tree-Structured File Organization (Obsidian Paradigm)
- Automatically categorizes uploaded notes into hierarchical main folders and branched skill-trees.
- Models **prerequisite relationships** (e.g. *Math Basics* → *Linear Algebra* → *Neural Networks* → *Transformers*).
- Full Obsidian-style sidebar with search, tag filtering, folder expand/collapse, and mastery status rings.

### 2. 🧠 Neural "Second Brain" Synthesis (NotebookLM Paradigm)
- For each concept node, the second brain generates:
  - Formal Definition & Principles
  - Real-world Educational Applications
  - Synthesized Concept Analysis
  - Key Takeaways & Competencies
- **🎙️ Voice-Narrated Overview**: Built-in Text-to-Speech via the browser's native **Web Speech API** featuring speed adjustment (1.0x, 1.25x, 1.5x, 2.0x) and dynamic audio frequency waveforms.

### 3. ⚡ Multi-Sensory Interactive Flashcards
- **3D Card Flip**: Realistic 3D card physics with flip animations.
- **Custom Font Picker**: Modern Sans (Inter), Classic Serif, Dyslexic/Monospace, and Aesthetic Script.
- **Instagram-Inspired Themes**: Instagram Sunset, Cyber Neon, Royal Gold, Sage Emerald, and Obsidian Dark.
- **Multi-Sensory Sounds**: Synthesized in real-time via the **Web Audio API** (card swoosh, harmonic success chimes, tactile clicks) with zero external asset dependencies.
- **SM-2 Spaced Repetition**: Adaptive review scheduling with *Again (1d)*, *Hard (3d)*, *Good (7d)*, and *Easy (14d)* rating intervals.

### 4. 🏆 Gamified Adaptive Quiz Arena & Socratic Chatbot
- **Adaptive Quiz Engine**: Multiple-choice testing with immediate feedback, detailed explanations, combo streak multipliers, and XP rewards.
- **Confetti Celebrations**: Conquering a node triggers a triumphant fanfare and particle bursts (`canvas-confetti`).
- **Doc-Hoc AI Tutor**: Conversational Socratic AI tutor answering queries and guiding active recall.

### 5. 📊 Automated Visual Reports & Competency Matrices
- Real-time retention index tracking, mastery distribution bars, and focus time analytics.
- **IS/ISO 21001:2018** competency matrix mapping nodes to Bloom's Taxonomy levels.
- **1-Click Export**: Download standard-compliant JSON-LD packages.

### 6. 🇮🇳 Bureau of Indian Standards (BIS) Conformance
- **IS 19450:2025**: E-textbook structure and Dublin Core metadata validation (`dc:title`, `dc:creator`, `dc:subject`, etc.).
- **IS/ISO/IEC 24751**: Individualized e-learning framework supporting **Visual**, **Audio**, and **Kinesthetic (Active Drill)** modalities.
- **IS/ISO 21001:2018**: Quality management and objective educational outcome tracking.

### 7. 🤖 Google Gemini API Integration
- Supports user-provided Gemini API keys (compatible with `gemini-2.0-flash` and `gemini-1.5-flash`).
- Enter and test your key via the top navbar button ("Connect Gemini") with live connection feedback.
- **Zero-Bug Offline Fallback**: Features a rich built-in intelligent engine so all features, graphs, flashcards, and quizzes run 100% out of the box even before an API key is plugged in!

---

## 🛠️ Tech Stack
- **Framework**: Next.js 16 (Turbopack, App Router)
- **Frontend**: React 19, TypeScript, Tailwind CSS v4, Framer Motion, Lucide Icons
- **3D Visualization**: Three.js, `@react-three/fiber`, `@react-three/drei`
- **Audio & Speech**: Web Audio API (tactile synthesis), Web Speech API (TTS narration)
- **AI**: Google Gemini API (`@google/genai`) + Next.js API Routes

---

## 🏃 Getting Started

### 1. Run Development Server
```bash
cd frontend
npm run dev
```
Open [http://localhost:3000](http://localhost:3000) in your browser.

### 2. Build for Production
```bash
cd frontend
npm run build
npm run start
```
