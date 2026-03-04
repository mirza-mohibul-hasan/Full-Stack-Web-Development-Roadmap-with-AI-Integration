# 🚀 6-Month Full Stack Web Development + AI Integration Roadmap

> **A complete, structured roadmap for Juniors to go from Zero → Full Stack Developer with AI Integration skills.**  
> Curated for junior developers learning together. Every phase includes the tech stack, timeline, and hands-on projects.

---

## 📌 Table of Contents

- [Overview](#overview)
- [Tech Stack](#tech-stack)
- [Phase 1 – Foundations (Weeks 1–4)](#phase-1--foundations-weeks-14)
- [Phase 2 – Frontend Development (Weeks 5–10)](#phase-2--frontend-development-weeks-510)
- [Phase 3 – Backend Development (Weeks 11–16)](#phase-3--backend-development-weeks-1116)
- [Phase 4 – Databases & APIs (Weeks 17–19)](#phase-4--databases--apis-weeks-1719)
- [Phase 5 – AI Integration (Weeks 20–22)](#phase-5--ai-integration-weeks-2022)
- [Phase 6 – Full Stack Projects & Deployment (Weeks 23–26)](#phase-6--full-stack-projects--deployment-weeks-2326)
- [Final Capstone Project](#final-capstone-project)
- [Resources](#resources)
- [Tips for the Team](#tips-for-the-team)

---

## Overview

| Total Duration    | 6 Months (26 Weeks)                     |
| ----------------- | --------------------------------------- |
| Weekly Commitment | 6–8 hours/day                           |
| Phases            | 6                                       |
| Projects          | 10+ (Mini + Major)                      |
| Final Output      | 2 Deployable Full Stack AI-Powered Apps |

---

## Tech Stack

### Frontend

| Technology            | Purpose                    |
| --------------------- | -------------------------- |
| **HTML5 + CSS3**      | Structure & Styling        |
| **JavaScript (ES6+)** | Core Language              |
| **React.js**          | UI Framework               |
| **Tailwind CSS**      | Utility-first Styling      |
| **Next.js**           | Full Stack React Framework |

### Backend

| Technology     | Purpose             |
| -------------- | ------------------- |
| **Node.js**    | Runtime Environment |
| **Express.js** | Backend Framework   |
| **REST APIs**  | API Architecture    |

### Database

| Technology     | Purpose                 |
| -------------- | ----------------------- |
| **PostgreSQL** | Relational Database     |
| **MongoDB**    | NoSQL / Flexible Data   |
| **Prisma ORM** | DB Queries & Migrations |

### AI & Tools

| Technology              | Purpose                 |
| ----------------------- | ----------------------- |
| **OpenAI API (GPT-4o)** | Text Generation & Chat  |
| **Vercel AI SDK**       | AI Streaming in Next.js |
| **LangChain.js**        | AI Chains & Agents      |
| **Pinecone / pgvector** | Vector Search (RAG)     |

### DevOps & Deployment

| Technology           | Purpose             |
| -------------------- | ------------------- |
| **Git + GitHub**     | Version Control     |
| **Vercel**           | Frontend Deployment |
| **Railway / Render** | Backend Deployment  |
| **Docker (basics)**  | Containerization    |

---

## Phase 1 – Foundations (Weeks 1–4)

> **Goal:** Get comfortable with the web, Git, and JavaScript before touching any framework.

---

### 📅 Week 1 – How the Web Works + HTML & CSS (7 Days)

**Topics:**

- How the internet works (HTTP, DNS, Browsers)
- HTML5 – Semantic tags, forms, tables, media
- CSS3 – Box model, Flexbox, Grid, Responsive Design
- CSS Variables, Transitions, Animations

**Days Breakdown:**
| Days | Topic |
|---|---|
| Day 1–2 | How the web works, HTML basics |
| Day 3–4 | HTML forms, tables, semantic tags |
| Day 5–6 | CSS Box Model, Flexbox |
| Day 7 | CSS Grid + Responsive Design |

**🔨 Mini Project: Personal Portfolio Website v1**

- Build a static portfolio with: Header/Nav, About section, Skills section, Contact form (HTML only)
- Features: Responsive layout, Flexbox/Grid usage, Hover animations

---

### 📅 Week 2–3 – JavaScript Fundamentals (14 Days)

**Topics:**

- Variables, Data Types, Operators
- Functions, Scope, Closures
- Arrays, Objects, Destructuring, Spread/Rest
- DOM Manipulation & Events
- Fetch API, Promises, Async/Await
- ES6+ features (Arrow functions, Template literals, Modules)
- Error Handling, LocalStorage

**Days Breakdown:**
| Days | Topic |
|---|---|
| Day 1–2 | Variables, Types, Operators, Conditionals |
| Day 3–4 | Functions, Scope, Closures |
| Day 5–6 | Arrays, Objects, Loops |
| Day 7–8 | DOM Manipulation, Events |
| Day 9–10 | Fetch API, Promises |
| Day 11–12 | Async/Await, Error Handling |
| Day 13–14 | ES6 Modules, LocalStorage, Review |

**🔨 Mini Project: Weather App**

- Features: Search city by name, Fetch live weather from OpenWeatherMap API, Show temperature/wind/humidity, Save last 5 searches in LocalStorage, Responsive UI

---

### 📅 Week 4 – Git, GitHub & Developer Tools (7 Days)

**Topics:**

- Git: init, add, commit, push, pull, branch, merge
- GitHub: Repos, Pull Requests, Issues, README
- VS Code tips, Chrome DevTools
- Terminal basics (Linux/Mac commands)

**Days Breakdown:**
| Days | Topic |
|---|---|
| Day 1–2 | Git basics (local) |
| Day 3–4 | GitHub (remote, PRs, branches) |
| Day 5 | VS Code extensions & shortcuts |
| Day 6 | Chrome DevTools deep dive |
| Day 7 | Group: Create GitHub org, push all projects |

**🔨 Activity:**

- Push all Week 1–3 projects to GitHub with proper README files
- Create a GitHub profile README
- Practice branching strategy (main → dev → feature branches)

---

## Phase 2 – Frontend Development (Weeks 5–10)

> **Goal:** Master React and build real interactive UIs.

---

### 📅 Week 5–6 – React.js Core (14 Days)

**Topics:**

- JSX, Components, Props
- State with useState, useEffect
- Conditional Rendering, Lists & Keys
- Event Handling
- Component Communication (Props Drilling)
- React DevTools

**Days Breakdown:**
| Days | Topic |
|---|---|
| Day 1–2 | JSX, Functional Components, Props |
| Day 3–4 | useState, Re-rendering |
| Day 5–6 | useEffect, Side Effects |
| Day 7–8 | Forms in React, Controlled inputs |
| Day 9–10 | Component composition, Lifting state |
| Day 11–12 | Lists, Conditional rendering |
| Day 13–14 | React DevTools + mini exercises |

**🔨 Project: Task Manager App**

- Features: Add/Edit/Delete tasks, Mark complete, Filter by status (All/Active/Done), Persist with LocalStorage, Clean responsive UI with Tailwind CSS

---

### 📅 Week 7 – Advanced React (7 Days)

**Topics:**

- useContext (Global State)
- useReducer
- Custom Hooks
- React Router v6 (Multi-page SPA)
- Code Splitting & Lazy Loading

**Days Breakdown:**
| Days | Topic |
|---|---|
| Day 1–2 | useContext, useReducer |
| Day 3 | Custom Hooks |
| Day 4–5 | React Router v6 |
| Day 6–7 | Code splitting, Lazy loading |

**🔨 Mini Project: Upgrade Task Manager → Multi-page**

- Add: Dashboard page, Task Detail page, Profile page, Context-based theme toggle (Dark/Light mode)

---

### 📅 Week 8 – Tailwind CSS + Component Design (7 Days)

**Topics:**

- Tailwind CSS utility classes deep dive
- Responsive design with Tailwind
- Building a Design System (colors, spacing, typography)
- shadcn/ui or DaisyUI component library
- Figma basics (reading & implementing designs)

**🔨 Project: UI Clone Challenge**

- Pick any popular website (Airbnb, Notion, Stripe landing page)
- Clone the frontend design using React + Tailwind
- Focus on pixel-perfect layout, responsiveness, animations

---

### 📅 Week 9–10 – Next.js Fundamentals (14 Days)

**Topics:**

- Next.js vs React (When & Why)
- App Router (Next.js 14+)
- Server Components vs Client Components
- File-based Routing
- API Routes (backend in Next.js)
- SSR, SSG, ISR (rendering strategies)
- Image Optimization, Metadata

**Days Breakdown:**
| Days | Topic |
|---|---|
| Day 1–2 | Next.js setup, App Router, routing |
| Day 3–4 | Server vs Client Components |
| Day 5–6 | Fetching data in Server Components |
| Day 7–8 | API Routes |
| Day 9–10 | SSR vs SSG vs ISR |
| Day 11–12 | Layouts, Loading states, Error boundaries |
| Day 13–14 | Metadata, Next/Image, Next/Font |

**🔨 Project: Blog Platform (Frontend)**

- Features: Homepage with post list, Individual post page (dynamic route), Category filter, Search functionality, Dark mode, Fully responsive

---

## Phase 3 – Backend Development (Weeks 11–16)

> **Goal:** Build real APIs and understand server-side logic.

---

### 📅 Week 11–12 – Node.js + Express.js (14 Days)

**Topics:**

- Node.js: Event Loop, Modules, File System, Streams
- Express.js: Routing, Middleware, Request/Response cycle
- REST API design principles
- CRUD operations
- Error handling middleware
- Environment variables (.env)
- Postman / Thunder Client for API testing

**Days Breakdown:**
| Days | Topic |
|---|---|
| Day 1–2 | Node.js fundamentals |
| Day 3–4 | Express setup, basic routing |
| Day 5–6 | Middleware, req/res deep dive |
| Day 7–8 | RESTful API design |
| Day 9–10 | CRUD with in-memory data |
| Day 11–12 | Error handling, validation |
| Day 13–14 | API testing with Postman |

**🔨 Project: Notes API (REST)**

- Endpoints: `GET /notes`, `POST /notes`, `PUT /notes/:id`, `DELETE /notes/:id`
- Features: Input validation, Proper status codes, Error messages, Pagination

---

### 📅 Week 13 – Authentication & Security (7 Days)

**Topics:**

- JWT (JSON Web Tokens)
- bcrypt for password hashing
- Auth middleware (protect routes)
- Refresh tokens
- Cookies vs LocalStorage for token storage
- Rate limiting, Helmet.js, CORS

**Days Breakdown:**
| Days | Topic |
|---|---|
| Day 1–2 | JWT basics, sign/verify |
| Day 3–4 | Register/Login endpoints, bcrypt |
| Day 5 | Auth middleware, protected routes |
| Day 6 | Refresh tokens |
| Day 7 | Security: Rate limit, CORS, Helmet |

**🔨 Project: Auth System**

- Features: Register, Login, Logout, Protected route access, Password hashing, JWT with refresh token

---

### 📅 Week 14–15 – Databases (14 Days)

#### PostgreSQL + Prisma (Week 14)

**Topics:**

- Relational DB concepts (tables, relations, keys)
- SQL: SELECT, INSERT, UPDATE, DELETE, JOINs
- Prisma ORM: schema, migrations, queries
- One-to-Many, Many-to-Many relations

**Days Breakdown:**
| Days | Topic |
|---|---|
| Day 1–2 | PostgreSQL setup, SQL basics |
| Day 3–4 | JOINs, constraints, indexes |
| Day 5–6 | Prisma setup, schema design |
| Day 7 | Prisma queries, migrations |

**🔨 Upgrade Notes API → Connect to PostgreSQL with Prisma**

---

#### MongoDB + Mongoose (Week 15)

**Topics:**

- NoSQL concepts (documents, collections)
- MongoDB Atlas (cloud setup)
- Mongoose: schemas, models, queries
- When to use SQL vs NoSQL

**Days Breakdown:**
| Days | Topic |
|---|---|
| Day 1–2 | MongoDB Atlas setup, CRUD |
| Day 3–4 | Mongoose schemas & models |
| Day 5–6 | Queries, population (relations) |
| Day 7 | SQL vs NoSQL comparison project |

---

### 📅 Week 16 – File Uploads, Email & Real-time (7 Days)

**Topics:**

- File uploads with Multer + Cloudinary
- Sending emails with Nodemailer / Resend
- WebSockets with Socket.io (basics)
- Server-Sent Events (SSE) – used in AI streaming

**🔨 Mini Project: Chat App Backend**

- Features: Real-time messaging with Socket.io, Rooms, User join/leave events

---

## Phase 4 – Databases & APIs (Weeks 17–19)

> **Goal:** Connect Frontend + Backend. Build your first Full Stack app.

---

### 📅 Week 17–18 – Full Stack Integration (14 Days)

**Topics:**

- Connecting Next.js frontend to Express API
- Using Axios / fetch in Next.js
- Next.js API routes vs separate Express backend
- Authentication flow (Frontend ↔ Backend)
- Form handling with React Hook Form + Zod validation
- SWR / React Query for data fetching

**Days Breakdown:**
| Days | Topic |
|---|---|
| Day 1–3 | Connect React frontend to Express API |
| Day 4–5 | Auth flow (Login → JWT → Protected pages) |
| Day 6–7 | React Hook Form + Zod |
| Day 8–9 | SWR / React Query |
| Day 10–11 | Error states, Loading states, Toast notifications |
| Day 12–14 | Full Stack CRUD with auth |

**🔨 Major Project 1: Expense Tracker App** _(Full Stack)_

- Stack: Next.js + Express + PostgreSQL + Prisma
- Features:
  - User authentication (Register/Login)
  - Add/Edit/Delete expenses
  - Categories & Tags
  - Monthly summary dashboard with charts (Recharts)
  - Filter & Search
  - Responsive UI with Tailwind

---

### 📅 Week 19 – Third-Party APIs & Integrations (7 Days)

**Topics:**

- Working with external REST APIs
- OAuth 2.0 (Google Login, GitHub Login) with NextAuth.js
- Stripe for payments (basics)
- Webhooks

**🔨 Mini Feature Add-on:**

- Add Google OAuth to Expense Tracker
- Add a Stripe "Premium Plan" page (no real payment needed)

---

## Phase 5 – AI Integration (Weeks 20–22)

> **Goal:** Integrate real AI features into web apps using APIs and modern tools.

---

### 📅 Week 20 – OpenAI API + Vercel AI SDK (7 Days)

**Topics:**

- What are LLMs? How does GPT-4o work?
- OpenAI API: Chat Completions, Tokens, Pricing
- Streaming responses (SSE)
- System prompts, temperature, max tokens
- Vercel AI SDK (`useChat`, `useCompletion`)
- Prompt Engineering basics

**Days Breakdown:**
| Days | Topic |
|---|---|
| Day 1 | LLM concepts, OpenAI playground |
| Day 2–3 | OpenAI API in Node.js |
| Day 4–5 | Streaming with SSE in Express |
| Day 6–7 | Vercel AI SDK in Next.js |

**🔨 Project: AI Chat App**

- Stack: Next.js + Vercel AI SDK + OpenAI GPT-4o
- Features:
  - Chat interface (like ChatGPT)
  - Streaming responses
  - Custom system prompt (set AI persona)
  - Chat history (per session)
  - Copy message, Regenerate response
  - Markdown rendering for AI responses

---

### 📅 Week 21 – RAG (Retrieval Augmented Generation) (7 Days)

**Topics:**

- What is RAG and why it matters
- Vector Embeddings (OpenAI text-embedding-3-small)
- Vector Databases (Pinecone or pgvector)
- Chunking documents
- Semantic search

**Days Breakdown:**
| Days | Topic |
|---|---|
| Day 1–2 | Embeddings concept, OpenAI Embeddings API |
| Day 3–4 | Pinecone setup, store & query vectors |
| Day 5–6 | Build RAG pipeline (Embed → Store → Retrieve → Generate) |
| Day 7 | Evaluate RAG quality |

**🔨 Project: PDF Chatbot (RAG)**

- Features:
  - Upload a PDF
  - Parse & chunk text
  - Embed chunks → store in Pinecone
  - Ask questions about the PDF
  - AI answers with context from the document
  - Show source page references

---

### 📅 Week 22 – AI Agents + LangChain.js (7 Days)

**Topics:**

- What are AI Agents?
- LangChain.js: Chains, Tools, Agents
- Tool calling (function calling with OpenAI)
- Building a simple agent with web search tool
- Structured outputs with Zod + AI

**🔨 Mini Project: AI Research Assistant**

- Features:
  - User gives a topic
  - Agent searches the web (Tavily API)
  - Summarizes findings
  - Returns structured report (Title, Summary, Key Points, Sources)

---

## Phase 6 – Full Stack Projects & Deployment (Weeks 23–26)

> **Goal:** Ship production-ready apps. Learn DevOps basics.

---

### 📅 Week 23 – Deployment & DevOps Basics (7 Days)

**Topics:**

- Vercel deployment (Next.js apps)
- Railway / Render (Node.js + PostgreSQL)
- Environment variables in production
- Custom domains
- CI/CD with GitHub Actions (basic pipeline)
- Docker basics (Dockerfile, docker-compose)

**Days Breakdown:**
| Days | Topic |
|---|---|
| Day 1–2 | Deploy Next.js to Vercel |
| Day 3–4 | Deploy Express + PostgreSQL to Railway |
| Day 5 | GitHub Actions: auto-deploy on push |
| Day 6–7 | Docker basics |

**🔨 Activity:** Deploy all previous projects (Expense Tracker, AI Chat App, PDF Chatbot)

---

### 📅 Week 24–26 – Final Capstone Projects (21 Days)

**Each team member builds ONE of these (or collaborate on all 3):**

---

### 🏆 Capstone Project 1: AI SaaS – "SmartDocs"

_Document management with AI-powered search and chat_

**Stack:** Next.js 14 + Express + PostgreSQL + Prisma + OpenAI + Pinecone + NextAuth + Stripe

**Features:**

- Google/GitHub OAuth login
- Upload and manage documents (PDF, TXT)
- AI Chat with any document (RAG)
- Folder organization
- Share documents via link
- Free tier (3 docs) + Paid tier (unlimited) via Stripe
- Usage analytics dashboard
- Deployed on Vercel + Railway

---

### 🏆 Capstone Project 2: Full Stack Social App – "DevConnect"

_A Twitter/X-like platform for developers_

**Stack:** Next.js + Express + MongoDB + Mongoose + Socket.io + Cloudinary + NextAuth

**Features:**

- Auth (Google OAuth + Email)
- Create posts with Markdown + code blocks
- Like, Comment, Repost
- Follow / Unfollow users
- Real-time notifications (Socket.io)
- Profile with avatar upload (Cloudinary)
- Search users and posts
- Trending topics (hashtags)
- Deployed on Vercel + Render

---

### 🏆 Capstone Project 3: AI Productivity App – "FlowAI"

_All-in-one AI workspace: Notes + Tasks + AI Assistant_

**Stack:** Next.js + Prisma + PostgreSQL + OpenAI + Vercel AI SDK + React DnD

**Features:**

- Auth with JWT
- Rich text notes editor (Tiptap)
- Kanban task board with drag & drop
- AI Summarize any note
- AI Generate tasks from a description
- AI Writing assistant (improve, shorten, translate)
- Pomodoro timer
- Calendar view for tasks
- Deployed fully on Vercel

---

## Final Capstone Project

| Item             | Details                                   |
| ---------------- | ----------------------------------------- |
| **Duration**     | Weeks 24–26 (3 weeks)                     |
| **Team Size**    | 1 per project OR 3 collaborating          |
| **Deliverables** | Live URL, GitHub Repo, README, Demo Video |
| **Presentation** | 15-min demo + code walkthrough            |

---

## 📊 Full Timeline Summary

| Phase   | Weeks | Focus                       | Key Project                     |
| ------- | ----- | --------------------------- | ------------------------------- |
| Phase 1 | 1–4   | HTML, CSS, JS, Git          | Weather App, Portfolio          |
| Phase 2 | 5–10  | React, Tailwind, Next.js    | Task Manager, Blog              |
| Phase 3 | 11–16 | Node, Express, Auth, DB     | Notes API, Chat Backend         |
| Phase 4 | 17–19 | Full Stack Integration      | Expense Tracker                 |
| Phase 5 | 20–22 | AI Integration, RAG, Agents | AI Chat App, PDF Chatbot        |
| Phase 6 | 23–26 | Deployment, Capstone        | SmartDocs / DevConnect / FlowAI |

---

## Resources

### Free Learning Resources

| Resource         | Link                             |
| ---------------- | -------------------------------- |
| The Odin Project | https://www.theodinproject.com   |
| freeCodeCamp     | https://www.freecodecamp.org     |
| JavaScript.info  | https://javascript.info          |
| React Docs       | https://react.dev                |
| Next.js Docs     | https://nextjs.org/docs          |
| Prisma Docs      | https://www.prisma.io/docs       |
| OpenAI Docs      | https://platform.openai.com/docs |
| Vercel AI SDK    | https://sdk.vercel.ai            |
| LangChain.js     | https://js.langchain.com         |

### YouTube Channels

- **Fireship** – Quick concept videos
- **Web Dev Simplified** – Deep dives
- **Theo (t3.gg)** – Next.js & modern stack
- **Jack Herrington** – Advanced React & AI
- **freeCodeCamp YouTube** – Full tutorials

### Practice Platforms

- **LeetCode** – DSA (1 easy problem/day recommended)
- **Frontend Mentor** – UI challenges
- **roadmap.sh** – Visual roadmaps

---

## Tips for the Team

### 🤝 Team Workflow

1. **Daily Standup (15 min):** What did you do? What will you do? Any blockers?
2. **Weekly Code Review:** Each person presents their project to the others
3. **Pair Programming:** Spend at least 2 hours/week coding together
4. **GitHub Collaboration:** Use branches, PRs, and code reviews on each other's code

### 💡 Learning Tips

- **Build > Watch.** For every 1 hour of tutorial, spend 2 hours coding
- **Break things on purpose.** Understanding bugs teaches more than perfect code
- **Google is not cheating.** Every developer googles. Learn to search effectively
- **Document as you go.** Write README files for every project
- **Teach each other.** If one person learns something, they explain it to the other two

### ⚠️ Common Mistakes to Avoid

- Tutorial hell – Don't watch 10 tutorials. Build after 1
- Skipping fundamentals – Don't jump to React without knowing JS well
- Not using Git – Commit every day, no matter how small
- Building in isolation – Show your code, get feedback
- Perfectionism – Ship ugly working code before beautiful broken
