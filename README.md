# RiseOS – Job & Networking Platform 🚀

A minimal full-stack web application inspired by LinkedIn, Upwork, and AngelList — built as part of the RizeOS Core Team Internship assessment.

---

## 🔧 Tech Stack

- **Frontend**: React.js + Tailwind CSS
- **Backend**: Node.js + Express.js
- **Database**: MongoDB Atlas
- **Authentication**: Session-based login & user context
- **Web3 (Planned)**: MetaMask integration using Ethers.js
- **AI Features (Planned)**: Resume parsing, job matching (NLP-based)

---

## ✅ Features Completed

### 👥 Authentication & Profile Management
- User Registration & Login
- Session persistence
- Profile Creation & Editing
- View Jobs Posted & Jobs Applied with response status

### 💼 Job Posting & Feed
- Post a job with title, description, skills, and budget
- View job listings in real-time feed
- Apply to jobs
- Job creators can view applicants & respond ("Yes", "No", "Not Answered")

---

## ⏳ Features In Progress / Planned

- 🔗 Blockchain Payment (MetaMask): Require platform fee before posting jobs
- 🧠 AI Resume Skill Extraction: Auto-fill skills from bio or uploaded resume
- 🤖 Job ↔ Candidate Matching: NLP-based similarity score
- 🔍 Search/Filter: Filter by skills, tags, and location
- 🌐 Deployment on Vercel / Render

---

## 💡 Go-To-Market Strategy (GTM)

**Target Users**: Students, early-career developers, startup founders  
**3-Month Growth Plan**:
1. Outreach to SRM + other colleges
2. Launch referral rewards
3. Instagram & LinkedIn mini campaigns

**Monetization**:
- ₹150/month Pro Subscription
- 2% commission on high-budget jobs (via Web3)

---

## 🧪 How to Run Locally

1. Clone the repo  
```bash
git clone https://github.com/NANDAN-30/RiseOS
cd RiseOS
Install dependencies

bash
Copy
Edit
cd client
npm install
cd ../server
npm install
Start the app

bash
Copy
Edit
# In /server
npm start

# In /client
npm run dev
