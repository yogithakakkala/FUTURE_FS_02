🚀 LeadFlow CRM — Client Lead Management System
Future Interns · Full Stack Web Development · Task 2
A fully functional Mini CRM system to manage client leads generated from website contact forms — built from scratch with zero dependencies.
🔗 Live Demo
👉 View Live Site
📸 Features
✅ Core Requirements (All Implemented)
Feature
Status
Lead listing (name, email, source, status)
✅
Lead status updates (New → Contacted → Converted)
✅
Notes & follow-ups per lead
✅
Secure admin login
✅
Public GitHub repository
✅
⭐ Bonus Features
Feature
Status
Search & filter leads
✅
Timestamp tracking
✅
Analytics dashboard
✅
Conversion funnel
✅
Lead source breakdown
✅
Weekly activity sparkline
✅
Real-time activity feed
✅
Sort by any column
✅
Quick status toggle inline
✅
Keyboard shortcuts
✅
🛠 Tech Stack
Layer
Technology
Frontend
HTML5, CSS3, Vanilla JavaScript
UI
Custom CSS (no framework)
Storage
localStorage (client-side persistence)
Charts
Canvas API (hand-built)
Fonts
Google Fonts — Syne + DM Sans
Hosting
GitHub Pages
📁 Project Structure
FUTURE_FS_02/
├── index.html     # App shell, login screen, all views & modals
├── style.css      # Complete dark-theme CSS (600+ lines)
├── app.js         # All business logic — auth, CRUD, charts, analytics
└── README.md      # This file
⚙️ Setup Instructions
Option 1 — Run Locally
git clone https://github.com/YOUR-USERNAME/FUTURE_FS_02.git
cd FUTURE_FS_02
# Open in browser (no build step needed!)
open index.html
Option 2 — GitHub Pages (Live)
Fork or push to your GitHub repo named FUTURE_FS_02
Go to Settings → Pages
Set source to main branch / root
Your live URL: https://YOUR-USERNAME.github.io/FUTURE_FS_02
🔐 Admin Login
Field
Value
Email
admin@leadflow.com
Password
admin123
📋 How It Works
Lead Lifecycle
Website Contact Form
        ↓
   [New Lead]  →  [Contacted]  →  [Converted]
        ↓               ↓               ↓
   Add Notes       Follow Up       Client! 🎉
Data Flow
User Action → JavaScript → localStorage → UI Update
All data persists in the browser's localStorage — no backend server required to run.
✨ App Walkthrough
Login with admin credentials
Dashboard — see stats, pipeline chart, lead sources, and activity feed
All Leads — full table with search, filter, sort, and inline status change
Add Lead — modal form with name, email, phone, source, status, notes
Notes — per-lead follow-up history
Analytics — conversion funnel, source breakdown, monthly trend
💼 Business Value
This CRM solves real business problems:
✅ How quickly can I see new leads? → Live dashboard with counts
✅ Can I track follow-ups easily? → Per-lead notes history
✅ Can I see which leads converted? → Conversion funnel & rate
🏆 Skills Demonstrated
DOM manipulation & event handling
localStorage for data persistence
Canvas API for custom charts
Responsive CSS Grid/Flexbox layouts
Authentication flow (client-side)
CRUD operations without a framework
Data filtering, sorting & searching
Real-time UI updates
👨‍💻 About
Built for Future Interns Full Stack Web Development Internship — Task 2 (2026)
Repository naming: FUTURE_FS_02 (Track: FS)
"I built this system to manage real clients." — Task Objective ✅
