# AI Deal Intelligence Dashboard (SvelteKit Demo)

This is a focused frontend demo built with **SvelteKit** and **TailwindCSS** to demonstrate practical skills.

The project simulates a lightweight interface for analyzing potential business partners using mock data and AI-style outputs — inspired by the real-world functionality of tools powered by LangChain, ElasticSearch, and Django (mocked).

## Features

### 🔍 Search & Filtering
- Text-based company search
- Sector filter dropdown
- Supports advanced query syntax  
  Example: `sector:fintech AND risk:<0.5`
- Simulated async behavior with loading states (ElasticSearch-style filtering)


### 📊 Results Table
- Paginated, sortable columns:
  - Company Name
  - Sector
  - Risk Score
  - AI Summary (short preview)
- Mobile responsive layout

### 🧠 AI Summary Modal
- Click a row to open a modal with a detailed summary
- "Ask AI" button triggers a simulated LangChain-style response (streamed text)

### 🌙 UI/UX Polish
- TailwindCSS design system
- Dark mode toggle
- Fully responsive across screen sizes

## Tech Stack

- [x] SvelteKit
- [x] TailwindCSS
- [x] Mock data (JSON) simulating Django backend
- [x] Streaming UI simulating LangChain agents

## Notes

- No real backend: all data and responses are mocked for simplicity
- Code is modular and component-based for clarity and reuse
- Designed to resemble real-world async UIs in fintech tools

## Time Spent

I plan to deliver a live demo and code repo within Approximately **48–72 hours**.
