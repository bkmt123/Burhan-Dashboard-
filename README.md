# Burhan's Command Center — README
### *URD Solutions · Locked In*

---

## What This Is

A personal life operating system — a single HTML file that runs entirely in your browser. No accounts, no servers, no subscriptions. Everything you enter is saved locally on your device using browser storage and persists between sessions.

Eight tabs cover every domain of your life: daily execution, FE exam prep, business operations, podcast, life planning, and Omega Psi Phi fraternal knowledge.

---

## How to Open It

1. Download `burhan-dashboard.html`
2. Double-click it — opens in any browser (Chrome, Edge, Safari, Firefox)
3. Bookmark it or save to your home screen for daily access

> **Data warning:** All data lives in your browser's local storage on the specific device and browser you use. Clearing site data or switching browsers will not carry your data over. Use the same browser on the same device every time.

---

## Tab-by-Tab Guide

---

### Overview

The home screen. Opens every session with a live date and a snapshot across all areas.

| Stat | What It Shows |
|---|---|
| Tasks Done Today | Completed vs. total tasks added today |
| FE Study Progress | Overall % of topics marked done |
| Podcast Episodes | Total published episodes |
| Deals in Pipeline | Total acquisition deals tracked |

Below the stats: a live preview of pending tasks for today and the next FE study topics in the queue.

---

### Daily Tasks

**Recurring Templates** — Create named task templates with a category and frequency (Daily, Weekdays, Weekly). Hit **+ Today** to instantly stamp any template onto today's task list. No more retyping the same daily items.

**Task Categories:**
- Work
- FE Study
- Business
- Personal
- Podcast

Each category gets its own color. Tasks are grouped by category and date. Older tasks from previous days appear below today's list.

**Actions:** Check to complete · ✕ to delete · Add via input field or Enter key

---

### FE Study

**Stats bar:** Completed topics · In Progress · To Do · Days to Exam countdown

**Overall Progress bar** — fills as you mark topics done. Set your target exam date to activate the countdown.

**Study Topics (18 total):** Click any topic to cycle its status:
`To Do → Active → Done`

Topics covered:
Mathematics, Probability & Statistics, Ethics & Professional Practice, Engineering Economics, Statics, Dynamics, Mechanics of Materials, Materials Science, Fluid Mechanics, Thermodynamics, Heat Transfer, Electrical Circuits, Structural Analysis, Geotechnical Engineering, Transportation, Construction Management, Environmental Engineering, Surveying

**Pomodoro Timer** — Three modes: Focus 25 · Short Break 5 · Long Break 15. Animated ring counts down. Each completed session is logged with a timestamp. Today's session history is displayed below.

**Study Notes** — Free-text area to log what you covered each session.

---

### Business

#### URD Solutions

**Active Projects** — Fully dynamic. Hit **+ Add Project** to open the modal:
- Project Name
- Client / Owner
- Location
- Status: Active / Bidding / Closeout / On Hold
- Target Completion date
- Notes

Each project card shows a colored left border by status (green = active, gold = bidding, blue = closeout, grey = on hold). Click the status badge to cycle it. ✕ to remove.

The counter shows `active / total` (e.g. `2/3`).

**Open RFIs and Subcontractors** — Editable number fields. Type a value and it saves automatically.

**Notes textarea** — Action items, wins, next steps for URD.

#### Acquisitions Pipeline

A 4-column Kanban board: **Prospect → Due Diligence → Negotiation → Closed**

Hit **+ New Deal** to add a deal with: name, type, estimated value, and notes. Move deals forward or back with one click. Remove with the Remove button.

---

### Podcast

**Locks & Loaded tracker.** Stats across the top: Total · Scheduled · Published · Ideas

Hit **+ New Episode** to open the modal:
- Episode Title
- Guest (or Solo)
- Status: Idea / Scheduled / Recorded / Published
- Record / Air Date
- Notes

Published episodes are auto-numbered. Filter episodes by status using the dropdown. Edit or remove any entry.

---

### Life Plan

#### Milestones

Fully editable milestone timeline. Pre-loaded with six default milestones:

1. Launch URD Solutions *(Completed)*
2. Pass FE Exam *(In Progress)*
3. Move — New Chapter *(In Progress · Late July 2026)*
4. Marriage *(Future)*
5. First Acquisition Closed *(Future)*
6. Locks & Loaded — 50 Episodes *(Future)*

**Actions on each milestone:**
- **✎ Edit** — opens modal to update any field
- **Status badge** — click to cycle: Future → In Progress → Done (dot color updates automatically)
- **↑ ↓** — reorder milestones up or down
- **✕** — remove permanently

**+ Add Milestone** — top-right button opens modal with fields for title, status, target date/timeframe (free text — write "Q4 2026", "In View", anything), and notes.

#### Notes Columns

| Field | Purpose |
|---|---|
| Vision Statement | Where you're going and why — the big picture |
| Gratitude / Reflection | Daily reflection, what you're learning |
| Marriage & Life Planning Notes | Intentions, timelines, qualities, duas |

---

### Ω Omega

Your personal Omega Psi Phi knowledge system. Built to grow with you.

#### Header
Shows the day streak — increments every day you study. Study anything in this tab to keep the streak going.

#### Knowledge Progress
Overall mastery percentage bar + individual bars for all 6 knowledge categories. Fills as you mark cards learned and answer quiz questions correctly.

**Categories:**
- Founders
- Cardinal Principles
- History
- Traditions
- Notable Ques
- Service & Uplift
- 📁 My Files *(appears once you upload documents)*

#### Daily Lesson
10 rotating deep-read lessons covering: the founding night, why Manhood comes first, the Scholar tradition, first at an HBCU, Carter G. Woodson, the Que Dawg, prostate cancer service work, Perseverance, Ernest Everett Just, and chapter structure.

Hit **Next Lesson** to advance · **Mark Learned** to log it and move on.

#### Flashcard Drill
50+ Q&A cards across all 6 categories. Select a category pill to filter. Click the card to flip from question to answer. Navigate with Prev / Next. Cards are tracked as you study.

#### Quick Quiz
Pulls a random question from the full library and generates 4 multiple-choice options. Correct answers mark that card as learned and update progress bars. Score tracked for the session.

#### Ask the Omega Scholar (AI)
Powered by Claude AI. Ask anything about Omega Psi Phi:
- Founders and their legacies
- Cardinal Principles in depth
- Notable members
- Chapter structure and districts
- Traditions, calls, symbolism
- Service programs
- History and culture

Responds as a knowledgeable, proud Que. Answers are informed by both the built-in knowledge base and any documents you have uploaded.

#### Knowledge Library
Browse all 50+ facts organized by category. Click any card to mark it learned. Learned cards show a green ✓.

#### 📁 Private Knowledge Base

Upload your own fraternity documents to expand the hub's knowledge base.

**Supported formats:** PDF · TXT · MD · DOCX (up to 4MB each)

**What happens when you upload:**
1. File is read and text is extracted (PDFs processed via Claude)
2. Claude analyzes the content and generates 8–12 custom flashcard Q&A pairs from your document
3. Cards are saved privately to your browser and immediately available

**Where uploaded knowledge flows:**
- Appears in the **📁 My Files** flashcard category
- Included in the **All** category mix
- Included in **Quiz** questions
- Injected as context into the **AI Scholar** — it knows what's in your files

File library shows name, size, cards generated, and status. ✕ to remove a file and all its cards.

#### My Omega Notes
Personal free-text area for reflections, things to ask your brothers, or anything fraternal you want to remember.

---

## Data & Storage

| Item | Detail |
|---|---|
| Storage method | Browser local storage |
| Syncs between devices | No |
| Internet required | Only for AI Scholar, PDF extraction, and Google Fonts |
| Clearing browser cache | Will erase all saved data |
| File format | Single `.html` file |

**Best practice:** Use the same browser on the same device every day. Chrome is recommended for best compatibility.

---

## AI Features (Require Internet)

| Feature | Location | What It Does |
|---|---|---|
| Omega Scholar Chat | Ω Omega tab | Answers questions about Omega Psi Phi using Claude AI |
| KB Card Generation | Private Knowledge Base | Extracts flashcards from your uploaded documents |
| PDF Text Extraction | Private Knowledge Base | Reads PDF content via Claude when uploading |
| Custom Daily Lesson | Private Knowledge Base | Can generate lessons from your uploaded content |

If you are offline, all non-AI features (tasks, FE tracker, Pomodoro, Kanban, milestones, flashcards, quiz, notes) work normally.

---

## Quick Reference — What Lives Where

| What you want to do | Tab |
|---|---|
| Add a task for today | Daily Tasks |
| Add a recurring task template | Daily Tasks |
| Mark FE topics | FE Study |
| Set your exam date | FE Study |
| Run a Pomodoro session | FE Study |
| Add or remove a project | Business |
| Track RFIs and subcontractors | Business |
| Move an acquisition deal | Business |
| Log a podcast episode | Podcast |
| Add or edit a life milestone | Life Plan |
| Write your vision statement | Life Plan |
| Study Omega flashcards | Ω Omega |
| Take a knowledge quiz | Ω Omega |
| Ask the AI about Omega history | Ω Omega |
| Upload a fraternity document | Ω Omega → Private Knowledge Base |

---

## File Info

| Property | Value |
|---|---|
| File name | `burhan-dashboard.html` |
| File type | Single HTML file |
| Internet required | Partial (AI features only) |
| Accounts required | None |
| Data location | Browser local storage |
| Compatible browsers | Chrome, Edge, Safari, Firefox |

---

*Built for a man who plans with intention and executes with discipline. URD Solutions · Que Psi Phi · Locked In.*
