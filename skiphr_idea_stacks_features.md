# SkipHR — Autonomous Recruitment & Proctoring System
### Next-Gen B2B SaaS Platform

## 💡 The Idea
**SkipHR** is a zero-cost, enterprise-grade B2B SaaS recruitment platform powered by an orchestrated suite of autonomous AI agents[cite: 8]. It eliminates manual friction through an end-to-end multi-agent workflow, anti-cheat security, and market-dominating killer features[cite: 8, 16].

---

## 🛠️ The Tech Stack
* **Frontend:** Next.js (App Router), Tailwind CSS, TypeScript, LiveKit WebRTC Client SDK, `face-api.js` (TensorFlow.js)[cite: 11].
* **Backend:** Python FastAPI, asynchronous database connection pooling.
* **Database & Security:** Raw PostgreSQL with explicit parameterized queries, browser lockdown, and biometric verification[cite: 11, 14].
* **AI & Cloud Services:** Groq / Gemini LLM APIs, LiveKit Cloud (Real-time voice/video), Resend API[cite: 10, 11].

---

## 🚀 End-to-End Workflow Phases

### Phase 01: Company Profile & Job Details Input
* **Corporate Metadata:** HR enters company profile, location settings, branding requirements, and criteria[cite: 9].
* **Target Skill Thresholds:** Defines exact technical skills, experience floors, and required behavioral parameters[cite: 9].
* **Multi-Channel Publish:** System automatically syndicates formatted job postings across selected board APIs[cite: 9].

### Phase 02: Resume Parsing & Timezone Scheduling
* **AI Resume Parsing:** Incoming resumes are instantly scored and mapped against job criteria via LLM agents[cite: 10].
* **Timezone Calculation:** Intelligent engine auto-detects candidate timezone and presents open interview slots[cite: 10].
* **Secure Link Dispatch:** Candidate confirms slot and instantly receives secure WebRTC interview room link[cite: 10].

### Phase 03: AI Voice Interview & Anti-Cheat Lockdown
* **Live WebRTC Voice AI:** Conversational agent conducts natural spoken interview using resume context[cite: 11].
* **Browser Lockdown:** Enforces full-screen mode, blocking external AI tools, tabs, and google searches[cite: 11].
* **Gaze & Vision Tracking:** `face-api.js` flags looking away or secondary persons, reducing trust score[cite: 11].

### Phase 04: Evaluation Report & 1-Click Decision
* **Structured Transcript:** HR dashboard aggregates voice transcripts, technical scores, and proctoring logs[cite: 12].
* **1-Click Confirmation:** Recruiter reviews summary and clicks button to confirm acceptance or rejection[cite: 12].
* **Automated Email Dispatch:** System automatically sends professional selection or rejection emails instantly[cite: 12].

---

## 👑 Killer Features

### 1. Collaborative Live Coding Sandbox
* **In-Browser IDE:** Candidates write functional code live while the AI agent observes logic in real time[cite: 13].
* **Voice-Guided Hinting:** AI speaks up to nudge candidates if stuck, mirroring a senior tech lead interaction[cite: 13].
* **Automated Unit Testing:** Unit tests run instantly upon submission to grade correctness automatically[cite: 13].

### 2. Deepfake & Audio Biometric Verification
* **Voice Biometric Match:** Verifies speaker identity matches initial audio sample to block proxy interviewers[cite: 14].
* **Liveness Video Guard:** Prevents video spoofing and blocks pre-recorded loops played into webcams[cite: 14].
* **Verified ID Certificate:** Generates a zero-trust identity verification badge attached to the HR report[cite: 14].

### 3. Automated AI Reference Calling
* **Automated Reference Outreach:** System automatically emails past managers listed on resume to complete voice check[cite: 15].
* **Autonomous Q&A Agent:** Voice agent interviews references safely without human HR intervention required[cite: 15].
* **Credibility Scoring:** Delivers a verified reference score straight to the final HR confirmation dashboard[cite: 15].