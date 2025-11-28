# Ignitia 🚀  
An AI‑powered learning platform that creates personalized learning paths by integrating content from Coursera & Udemy with practical projects — designed for learners of all ages.

## 🌟 Overview  
Ignitia helps learners discover, follow, and complete curated learning paths.  
- It aggregates courses from major platforms (Coursera, Udemy) into a single dashboard  
- Generates personalized learning recommendations based on user profile  
- Allows learners to follow up with practical projects to reinforce skills  
- Provides analytics (progress, skill‑tracking) useful for both learners and institutions  

## 📁 Repository Structure  
Ignitia/
├─ backend/ — Node.js + Express server
├─ frontend/ — React (or Next.js) frontend
├─ data/ — (Optional) mock databases / JSON files
├─ README.md — This file
└─ … — Other configuration files (package.json, etc.)

## 🛠️ Features (MVP)  
- User authentication (signup/login) — currently mocked / local  
- Course listing aggregated from mock data (can be extended to real APIs)  
- Personalized learning path generation (mock logic now; extendable)  
- Dashboard with course cards — start courses or projects from UI  
- Project integration option for hands‑on practice  

## 🚀 Getting Started (Local Setup)  

### Prerequisites  
- Node.js (version 14 or higher) or bun / yarn / npm  
- (Optional) git — if you want version control  

### Steps  
```bash
# Clone repository
git clone https://github.com/yourusername/ignitia.git
cd ignitia

# Start backend
cd backend
npm install      # or bun install
npm run start    # or bun run index.js

# In a new terminal — start frontend
cd ../frontend
npm install
npm run dev      # or bun run dev
