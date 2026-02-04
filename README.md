# ai-study-career-copilot
1. Project goal
Designed and developed a full-stack web application that helps students plan learning goals, track study activity, and receive AI-generated feedback based on real usage data. Implemented authentication, dashboards, data visualisation, and AI-driven insights using React, Node.js, PostgreSQL, and OpenAI API.
2. Tech stack
   Frontend
- React( Vite)
- Tailwind CSS
- Chart library
   Backend 
- Node.js + Express
   Database
- PostgreSQL
   AI
- Open AI API
- endpoints :
    - /ai/feedback
    - /ai/recommendation
4. MVP features
   4.1. Authentication
    * Purpose: To identify users and store their personal data 
    * Features: 
         Register/ Login
         JWT or session-based auth
   **Notes:** No social login/ password reset or email verification for MVP yet
   4.2. Goals
    * Purpose: Let users define learning/ career objectives and recieve AI recommendations
    * Features:
        1. Create a goal (e.g: “Master React in 6 weeks period, land a SWE job at company XYZ , etc
        2. AI will then generate: 
            - Suggested study schedule/roadmap
            - 3-5 curated resources ( docs, Youtube. Tutorials )
     **Notes:**     No skill-level personalization yet
   4.3. Study Logs
    * Purpose: To track user daily progress
    * Features: 
        1. Logs that display:
            - Date
            - Duration
            - Topic
            - Notes ( Notion-style)
     **Notes:**    No tags, attachments or rich text support yet
   4.4. Dashboard
    * Purpose: To view uses’s progress in figures for better visualisation 
    * Features:
        1. Total hours studied/ not studied
        2. Progress per goal ( % or bar ) ( will upgrade to user’s preferences )
    **Notes:**  Weekly summaries and advanced charts will be postponed once the core features are finalized      
4.5. AI feedback
    * Purpose: Help users identify strengths, gaps, and next steps.
    * Features:
    - On-demand “Get Feedback” button
    - AI scans user goals + study logs
    - Returns:
        - Strengths
        - Gaps
        - 2–3 actionable suggestion
    **Notes:** No automatic notifications or historical comparisons yet.
5. AI features/endpoints
- /ai/feedback
- /ai/recommendation
