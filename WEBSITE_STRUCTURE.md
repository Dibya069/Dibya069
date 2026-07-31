# 🌐 Portfolio Website Structure

## 📊 Website Sections Overview

Your portfolio website has **7 main sections**:

```
┌─────────────────────────────────────────────┐
│  🏠 NAVIGATION BAR (Sticky)                │
│  • Dibyajyoti Mohanty (brand)              │
│  • Links: Home, About, Experience,         │
│    Skills, Projects, Education, Contact    │
│  • Mobile hamburger menu                   │
└─────────────────────────────────────────────┘

┌─────────────────────────────────────────────┐
│  1️⃣ HERO SECTION                           │
│  • Name: Dibyajyoti Mohanty (neon green)   │
│  • Title: AI/ML Engineer | Generative AI   │
│  • Description: Production-grade AI systems│
│  • CTA Buttons: Get In Touch, Download CV  │
│  • Social Links: GitHub, LinkedIn, Email   │
│  • Scroll indicator                        │
│  Background: Dark gradient with green glow │
└─────────────────────────────────────────────┘

┌─────────────────────────────────────────────┐
│  2️⃣ ABOUT SECTION                          │
│  • Professional summary                    │
│  • Key achievements (80% QA reduction...)  │
│  • Core expertise areas                    │
│  Background: Dark black (#060913)          │
└─────────────────────────────────────────────┘

┌─────────────────────────────────────────────┐
│  3️⃣ EXPERIENCE SECTION (Timeline)          │
│  • 5 positions with detailed bullets       │
│  1. Movius (Current - SDE AI Engineer)     │
│  2. ATG (Generative AI Engineer)           │
│  3. Freelance (AI/ML Consultant)           │
│  4. Cognizant (Programmer Analyst)         │
│  5. Stack System (Software Developer)      │
│  Design: Vertical timeline with green dots │
│  Background: Matte dark (#0a0e27)          │
└─────────────────────────────────────────────┘

┌─────────────────────────────────────────────┐
│  4️⃣ SKILLS SECTION (14 Categories)         │
│  • Languages & Core Libraries (6 skills)   │
│  • AI/ML Frameworks (9 skills)             │
│  • Machine Learning (5 skills)             │
│  • Deep Learning (9 skills)                │
│  • Generative AI & LLMs (10 skills)        │
│  • Computer Vision (6 skills)              │
│  • Speech & Audio AI (8 skills)            │
│  • Databases (8 skills)                    │
│  • GPU & AI Infrastructure (9 skills)      │
│  • Version Control & DevOps (7 skills)     │
│  • Cloud & MLOps (8 skills)                │
│  • Web Frameworks & APIs (4 skills)        │
│  • Development Tools (6 skills)            │
│  • AI Domains (5 skills)                   │
│  Total: 90+ skills                         │
│  Design: Cards with green glow on hover    │
│  Background: Dark black (#060913)          │
└─────────────────────────────────────────────┘

┌─────────────────────────────────────────────┐
│  5️⃣ PROJECTS SECTION (5 Projects)          │
│  1. AI-Powered NPC System                  │
│     • LangChain, LangGraph, Llama 3.3      │
│  2. Multi-Agent AI Assistant               │
│     • Memory, Flask, React                 │
│  3. Enterprise Conversation Intelligence   │
│     • RAG, ChromaDB, Deepgram              │
│  4. AI Sales Call Analysis                 │
│     • Speaker diarization, Llama-3         │
│  5. AI Tattoo Generator                    │
│     • DALL·E 3, Stable Diffusion XL,       │
│       ControlNet, MediaPipe, DeepLabv3+    │
│  Design: Project cards with tech badges    │
│  Background: Matte dark (#0a0e27)          │
└─────────────────────────────────────────────┘

┌─────────────────────────────────────────────┐
│  6️⃣ EDUCATION SECTION                      │
│  • B.Sc. Information Science &             │
│    Telecommunication                       │
│  • Ravenshaw University (2022)             │
│  • Focus areas & relevant coursework       │
│  Design: Card with graduation cap icon     │
│  Background: Dark black (#060913)          │
└─────────────────────────────────────────────┘

┌─────────────────────────────────────────────┐
│  7️⃣ CONTACT SECTION                        │
│  • Email card with icon                    │
│  • LinkedIn card with link                 │
│  • GitHub card with link                   │
│  Design: Interactive cards with glow       │
│  Background: Matte dark (#0a0e27)          │
└─────────────────────────────────────────────┘

┌─────────────────────────────────────────────┐
│  🔽 FOOTER                                  │
│  • Copyright 2024                          │
│  • "Built with ❤️ and code"                │
│  Background: Deep black (#060913)          │
└─────────────────────────────────────────────┘
```

## 🎨 Color Scheme (Matte Black & Green)

```css
Primary Green:   #00ff88  (Neon green - accents, highlights)
Secondary Green: #00cc6f  (Darker green)
Accent Green:    #00ffaa  (Bright green glow)

Dark BG:         #0a0e27  (Dark blue-black)
Darker BG:       #060913  (Deep black)
Card BG:         #151a30  (Card backgrounds)

Text Light:      #e4e4e7  (Main text)
Text Muted:      #a1a1aa  (Secondary text)
Border:          #1f2937  (Subtle borders)
```

## ✨ Interactive Features

- ✅ **Smooth scrolling** to sections
- ✅ **Active navigation** highlighting
- ✅ **Scroll animations** (fade-in on scroll)
- ✅ **Hover effects** with green glow
- ✅ **Mobile responsive** with hamburger menu
- ✅ **Typing effect** on hero subtitle
- ✅ **Card animations** on hover (lift + glow)
- ✅ **Gradient backgrounds** with subtle effects

## 📱 Responsive Breakpoints

- **Desktop**: Full layout (>768px)
- **Tablet**: Adapted grid (768px)
- **Mobile**: Single column, hamburger menu (<768px)
- **Small Mobile**: Optimized text sizes (<480px)

## 🗂️ File Structure

```
portfolio/
├── index.html                    # Main HTML (261 lines)
├── styles.css                    # All styling (730+ lines)
├── script.js                     # JavaScript (142 lines)
├── Dibyajyoti_Mohanty_Resume.pdf # Resume PDF
├── README.md                     # Documentation
├── SETUP_GUIDE.md               # GitHub Pages setup
├── CUSTOMIZATION_TODO.md        # Final todos
├── WEBSITE_STRUCTURE.md         # This file
└── .gitignore                   # Git ignore file
```

## 📈 Content Statistics

- **Total Sections**: 7
- **Work Experience**: 5 positions
- **Skills Categories**: 14 comprehensive categories
- **Total Skills**: 90+ technologies and tools
- **Projects**: 5 major production-grade projects
- **Social Links**: 3 (GitHub, LinkedIn, Email)
- **Lines of Code**: ~1,500+
- **Color Scheme**: Matte Black & Neon Green
- **Contact Info**: Fully updated
  - Email: dibyamohanty069@gmail.com
  - GitHub: https://github.com/Dibya069
  - LinkedIn: https://www.linkedin.com/in/dibyajyoti-mohanty-4a72501b2/

---

**Status**: ✅ 100% Complete - Ready to Deploy! 🚀
**Remaining**: Nothing! All customization done
**Ready to Deploy**: YES! Follow SETUP_GUIDE.md to go live
