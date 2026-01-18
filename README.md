# 🤖 AI SEO Topic Clusterer
**with CrewAI & SerpAPI**

> **Transform messy keyword lists into clean, intent-aware topic clusters and production-ready content briefs with AI-powered SEO agents.** ⚡

---

## ✨ Features

### 🎯 **Core Functionality**
- 🤖 **Multi-Agent CrewAI Pipeline** - Strategist, Researcher, and Editor agents collaborate to produce clusters and briefs
- 🔍 **SerpAPI Integration** - Real Google SERP data (organic URLs, People Also Ask, related searches, SERP features)
- 📊 **Intent-Aware Clustering** - Automatically groups keywords by semantic similarity, intent, and SERP overlap
- 📝 **Content Brief Generation** - Production-ready briefs with titles, angles, outlines, and FAQs
- 🎨 **Interactive Playground** - Chat-style interface to paste keywords, run the crew, and inspect results

### 🎨 **Beautiful UI/UX**
- ✨ **Modern 2025 Design** - Glassmorphism, gradients, micro-animations, and smooth transitions
- 🌙 **Dark/Light Mode** - Full theme support with system preference detection
- 📱 **Fully Responsive** - Optimized for desktop, tablet, and mobile (WCAG 2.1 Level AAA compliant)
- ♿ **Accessible** - Semantic HTML, keyboard navigation, focus states, high contrast
- 🎯 **Intuitive Interface** - Clean, user-friendly design with real-time feedback

### 📊 **Advanced Features**
- 📈 **Real-Time Agent Activity** - Live progress indicators for Strategist, Researcher, and Editor agents
- 🗺️ **Interactive Cluster Visualization** - Force-directed graph and list views with filtering
- ✏️ **Brief Editor with Live Preview** - Edit content briefs with real-time markdown preview
- 🚀 **OpenAI-Enhanced Briefs** - AI-powered suggestions for SEO tips, content angles, FAQs, and structure
- 📤 **Export Functionality** - Export results as JSON, CSV, or Markdown
- 🔗 **Shareable Results Links** - Generate compressed, shareable URLs for results
- 🔍 **Advanced Filtering & Search** - Filter by priority, intent, search keywords, and sort options
- ⌨️ **Keyboard Shortcuts** - Power user shortcuts for faster navigation
- 📊 **SERP Evidence Display** - View top URLs, People Also Ask, and related searches per cluster

### 🚀 **Performance & Reliability**
- ⚡ **Redis Caching** - SerpAPI results cached to reduce API calls and improve speed
- 🔄 **Background Job Processing** - Asynchronous job system with polling for long-running tasks
- 💾 **Supabase Integration** - Persistent storage for profiles, projects, messages, and jobs
- 🎯 **Rate Limiting** - Built-in rate limiting for SerpAPI calls
- 🔒 **Schema Isolation** - Database schema isolation for multi-tenant support

---

## 🏗️ Tech Stack

### **Backend** 🐍
- **FastAPI** - Modern Python web framework
- **CrewAI** - Multi-agent framework for SEO agents
- **OpenAI API** - GPT-4.1-mini for LLM-powered clustering and brief generation
- **LangChain OpenAI** - LLM integration layer
- **Python 3.11+** - Latest features and performance

### **Frontend** ⚛️
- **Next.js 15** - React 19 with App Router
- **TypeScript** - Type-safe development
- **Tailwind CSS** - Utility-first styling
- **shadcn/ui** - Beautiful component library
- **Lucide Icons** - Modern icon set
- **next-themes** - Theme management
- **react-force-graph-2d** - Interactive graph visualization
- **react-markdown** - Markdown rendering

### **AI & External APIs** 🤖
- **OpenAI** - GPT-4.1-mini for clustering and brief generation
- **SerpAPI** - Real Google SERP data enrichment
- **CrewAI** - Multi-agent orchestration

### **Database & Cache** 💾
- **Supabase** - PostgreSQL with schema isolation (`seo_topic_clusterer`)
- **Upstash Redis** - Serverless caching and job queue

### **Deployment** 🚀
- **Railway** - Backend API service deployment
- **Vercel** - Frontend web service deployment

---

### 🏠 Homepage
*Beautiful landing page with hero videos, feature highlights, and clear value proposition*

### 🎮 Playground
*Interactive interface for running CrewAI agents, viewing clusters, and editing briefs*

### 📊 Dashboard
*Comprehensive dashboard with stats, activity, and cluster overview*

---

## 📖 User Guide

### 🎮 Using the Playground

1. **Navigate to Playground**
   - Go to `/playground` from the homepage
   - Or click "Try live crew" in the navigation

2. **Enter Keywords**
   - Paste your keyword list (one per line, or comma-separated)
   - Example: `SEO tools, keyword research, content optimization, backlink analysis`
   - Supports any number of keywords

3. **Run the Crew**
   - Click **"Run Crew"** button
   - Watch real-time agent activity:
     - **SERP Researcher** - Analyzing SERP data
     - **Topic Strategist** - Creating clusters
     - **Brief Editor** - Generating content briefs

4. **Explore Results**
   - View clusters in interactive graph or list view
   - Filter by priority (high/medium/low) or intent (informational/transactional/navigational)
   - Search clusters by keyword
   - Click on clusters to see detailed briefs

5. **Edit Briefs**
   - Click **"Edit Brief"** on any cluster
   - Use the live preview editor to customize content
   - Save changes (stored in browser localStorage)

6. **Enhance with AI**
   - Click **"Enhance with AI"** in the brief editor
   - Get AI-powered suggestions for:
     - SEO tips and best practices
     - Alternative content angles
     - Additional FAQs
     - Related topics
     - Structure recommendations

7. **Export or Share**
   - Click **"Export"** to download as JSON, CSV, or Markdown
   - Click **"Share"** to generate a shareable link

### 📊 Using the Dashboard

1. **View Stats**
   - Total clusters generated
   - Agent activity metrics
   - SERP cache health

2. **Explore Clusters**
   - Browse all generated clusters
   - Filter and search functionality
   - View SERP evidence per cluster

### ⌨️ Keyboard Shortcuts

- `Ctrl/Cmd + Enter` - Submit form / Run crew
- `Ctrl/Cmd + R` - Reset / Clear results
- `Ctrl/Cmd + K` - Open keyboard shortcuts modal
- `Esc` - Close modals / Cancel actions

---

## 🎨 Customization

### Theme Options
- ☀️ **Light Mode** - Clean, bright interface
- 🌙 **Dark Mode** - Easy on the eyes
- 🖥️ **System** - Follows OS preference (default)

### View Modes
- 🗺️ **Graph View** - Interactive force-directed graph visualization
- 📋 **List View** - Compact list with all cluster details

### Filter Options
- **Priority** - High, Medium, Low, or All
- **Intent** - Informational, Transactional, Navigational, Mixed, or All
- **Search** - Filter clusters by keyword
- **Sort** - By name, priority, intent, or keyword count

---

---

## 👨‍💻 Creator

**Created by Derril Filemon**

---

## 🙏 Acknowledgments

- **OpenAI** - For GPT-4.1-mini API
- **CrewAI** - For multi-agent framework
- **SerpAPI** - For Google SERP data
- **Supabase** - For database & persistence
- **Upstash** - For Redis caching
- **Railway** - For backend deployment
- **Vercel** - For frontend deployment
- **shadcn/ui** - For beautiful components
- **Next.js Team** - For the amazing framework

---


<div align="center">

Made with ❤️ and ☕ by [Derril Filemon](https://github.com/derril-tech)

</div>
