# Team Task Plan — One-Stop Personalized Career & Education Advisor (Team of 6)

## 👥 Component Ownership with System Roles

### 🔧 1. Student Profile Module

**Owner:** Dev A

- Handles student onboarding and profile creation (skills, interests, grades, location).  
- Validates input and stores structured data in Postgres DB via Drizzle ORM.  
- Provides APIs for frontend to fetch and update profile info.  

**Input:** User form data (skills, interests, grades, location)  
**Output:** Stored profile records, validation errors, API responses  

---

### 🔧 2. Career & College Recommendation Engine

**Owner:** Dev B

- Computes personalized career and college suggestions using rule-based or ML scoring.  
- Matches student profile → careers → suitable colleges.  
- Returns top 3 recommendations with scores/weights.  

**Input:** Student profile data  
**Output:** Recommended careers, colleges, scoring metrics  

---

### 🔧 3. Resources & Guidance Module

**Owner:** Dev C

- Curates and links relevant articles, webinars, mock tests for suggested careers.  
- Optional: mentorship chat/Q&A integration.  
- Serves API endpoints for frontend to fetch resources.  

**Input:** Recommended careers/colleges, curated resources  
**Output:** Resource lists per career, optional chat responses  

---

### 🔧 4. Dashboard / Analytics Module

**Owner:** Dev D

- Visualizes student progress, career matches, and top analytics (e.g., most matched careers).  
- Provides web/mobile dashboards with interactive charts.  
- Optional: generates simple reports for judges/demo.  

**Input:** Profile data, recommendation outputs  
**Output:** Dashboard data, visualization API responses  

---

### 🎨 5. UI/UX, Design & Presentation

**Owners:** Designer 1 (Girl), Designer 2 (Girl)

- Designs mobile + web UI (React Native + Next.js) based on smooth user flows.  
- Creates mockups, prototypes, and visual assets.  
- Handles presentation preparation, PPT, and brainstorming session for demo/storytelling.  

**Input:** User journey flows, feature requirements  
**Output:** UI mockups, design assets, presentation slides  

---

### 🔧 6. Backend API & Frontend Integration

**Owner:** Dev E

- Implements NestJS APIs for profile, recommendation, and resources modules.  
- Connects frontend with backend endpoints.  
- Handles authentication, session state, and secure data access.  

**Input:** Frontend requests (profile, recommendations, resources), auth credentials  
**Output:** API responses, auth tokens, error messages  

---

### 🔁 Shared Responsibilities

- Collaborate on deployment workflow (Vercel, Render, Docker)  
- Maintain consistent endpoint contracts and data schemas  
- Work together on test coverage, debugging, and bug fixes  
- Ensure smooth frontend-backend communication and UX consistency  
- Prepare demo flow and visual assets for judges presentation  

