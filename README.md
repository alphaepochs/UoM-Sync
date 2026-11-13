# UoM Sync (Campus Gap Planner)

> A lightweight web application designed to help international students at the University of Manchester visualize timetable gaps, synchronize free time, and manage timezones.

## 🎯 The Problem
Existing university calendars only tell you *where* and *when* your classes are. However, international students often struggle with:
1. **Fragmented Timetables**: Figuring out if a 2-hour gap is enough time to go to City Centre or grab a proper meal.
2. **Timezone Confusion**: Constantly calculating the time difference when coordinating with family or friends back home.
3. **Finding Sync Time**: Struggling to find a common free slot for group projects or social meetups.

## ✨ MVP Features (Our Scope)
1. **.ics Import**: Seamlessly parse standard UoM timetable files (`.ics`).
2. **Gap Visualization**: A clean, interactive UI showing daily gaps between classes.
3. **Timezone Converter**: Automatically convert class times to a secondary (home) timezone for easy communication.
4. **"Same Free Time" Matching**: A simple heatmap allowing a small group to see when everyone is simultaneously free.

## 🧠 Core Principles
*   **Privacy First**: No real `.ics` files will be committed to this repository. Processing happens locally/client-side.
*   **No Hardware / No Hardware APIs**: Pure software logic.
*   **Zero Social Risk**: No anonymous forums, no trading, just a pure utility tool.

## 👥 Team Roles & Responsibilities
*(To be finalized during the team meeting)*

*   **Tech Lead & Backend**: [你的名字] — Responsible for `.ics` parsing logic, timezone handling, core gap calculation engine, and API design.
*   **Frontend Developers**: TBD — Responsible for UI/UX design, calendar visualization, and interactive heatmaps.
*   **Data & Research**: TBD — Curating mock data, campus building locations, and testing scenarios.
*   **QA & Documentation**: TBD — Writing test cases, preparing the final poster, and recording the demo video.

## 🚀 Tech Stack (Proposed)
*   **Backend**: Python (FastAPI or Flask)
*   **Frontend**: React or Vue.js (TBD)
*   **Database**: JSON/In-memory (Keep it lightweight for the MVP)
*   **Data Parsing**: `icalendar` / `recurring-ical-events` libraries.

## 🛠️ Development Workflow
1.  **Issues**: All tasks are tracked in the "Issues" tab. Please assign yourself to a task before starting.
2.  **Branches**: Never push directly to `main`. Create a feature branch (e.g., `feat/frontend-ui`, `fix/timezone-bug`).
3.  **Pull Requests (PRs)**: Submit a PR when your feature is ready. The Tech Lead will review and merge.

## ⚠️ Note on AI Usage
We acknowledge the use of AI tools to accelerate development and drafting. All AI-generated code/architecture will be reviewed and tested by the team before merging. 

---
*Created by the UoM Sync Team.*
