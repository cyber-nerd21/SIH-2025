# Team Task Plan — One-Stop Personalized Career & Education Advisor (Team of 6)

**Note:**  
- 1 person can take 2–3 responsibilities.  
- 2–3 people can collaborate on a single responsibility.  

---

## 1️⃣ Student Profile Module (Dev A)
- [ ] Handle student onboarding and profile creation (skills, interests, grades, location)  
- [ ] Validate input and store structured data in Postgres DB via Drizzle ORM  
- [ ] Provide APIs for frontend to fetch and update profile info  

**Input:** User form data  
**Output:** Stored profile records, validation errors, API responses  

---

## 2️⃣ Career & College Recommendation Engine (Dev B)
- [ ] Compute personalized career and college suggestions (rule-based or ML scoring)  
- [ ] Match student profile → careers → suitable colleges  
- [ ] Return top 3 recommendations with scores/weights  

**Input:** Student profile data  
**Output:** Recommended careers, colleges, scoring metrics  

---

## 3️⃣ Resources & Guidance Module (Dev C)
- [ ] Curate and link relevant articles, webinars, mock tests for suggested careers  
- [ ] Optional: mentorship chat/Q&A integration  
- [ ] Serve API endpoints for frontend to fetch resources  

**Input:** Recommended careers/colleges, curated resources  
**Output:** Resource lists per career, optional chat responses  

---

## 4️⃣ Dashboard / Analytics Module (Dev D)
- [ ] Visualize student progress, career matches, and top analytics (e.g., most matched careers)  
- [ ] Provide web/mobile dashboards with interactive charts  
- [ ] Optional: generate simple reports for judges/demo  

**Input:** Profile data, recommendation outputs  
**Output:** Dashboard data, visualization API responses  

---

## 5️⃣ UI/UX, Design & Presentation (Designer 1 & Designer 2)
- [ ] Design mobile + web UI (React Native + Next.js) based on smooth user flows  
- [ ] Create mockups, prototypes, and visual assets  
- [ ] Prepare presentation, PPT slides, and brainstorming content for demo  

**Input:** User journey flows, feature requirements  
**Output:** UI mockups, design assets, presentation slides  

---

## 6️⃣ Backend API & Frontend Integration (Dev E)
- [ ] Implement NestJS APIs for profile, recommendation, and resources modules  
- [ ] Connect frontend with backend endpoints  
- [ ] Handle authentication, session state, and secure data access  

**Input:** Frontend requests, auth credentials  
**Output:** API responses, auth tokens, error messages  

---

## 🔁 Shared Responsibilities (All Team Members)
- [ ] Collaborate on deployment workflow (Vercel, Render, Docker)  
- [ ] Maintain consistent endpoint contracts and data schemas  
- [ ] Work together on test coverage, debugging, and bug fixes  
- [ ] Ensure smooth frontend-backend communication and UX consistency  
- [ ] Prepare demo flow and visual assets for judges presentation  


