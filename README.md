PhishGuard — AI-Powered Email Phishing Detection

PhishGuard is a real-time AI platform that analyzes incoming emails and detects phishing attempts instantly. Paste any email — subject, body, links — and the AI evaluates whether it's a phishing attack, scores the risk level, explain attempts.

Phishing emails are the #1 vector for cyberattacks. Traditional spam filters miss sophisticated attacks that use legitimate-looking domains, urgency tactics, and social engineering. Employees and users cannot always identify phishing emails manually — and one wrong click can compromise an entire organization.

PhishGuard uses *Google Gemini 2.0 Flash* to read and understand email content the same way a human security analyst would — detecting deceptive language, suspicious links, impersonation tactics, and psychological manipulation patterns in real time.



## ✅ Features

- *Real-time Email Analysis* — Paste email content and get instant AI verdict
- *Risk Score (0–100)* — Clear threat level with detailed explanation
- *Threat Indicators* — AI explains exactly why an email is suspicious
- *Moderation Actions* — Mark as Phishing, Warn, or Safe — all logged
- *Community Health Score* — Track your overall exposure
- *Threat Map* — Visual breakdown type of attempts
- *Audit Log* — Full history of every analyzed email with timestamps

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | React 18 + TypeScript |
| Styling | Tailwind CSS |
| Animation | Framer Motion |
| AI Engine | Google Gemini 2.0 Flash |
| Auth | Firebase Authentication |
| Database | Firebase Firestore |
| Build Tool | Vite |

---

## ⚙️ How to Run

### Prerequisites
- Node.js 18+
- Google Gemini API key → [aistudio.google.com](https://aistudio.google.com)
- Firebase project with Auth + Firestore enabled

### Installation

bash
# 1. Clone the repository
git clone https://github.com/nkhtmmdv/Caspian-Code
cd phishGuard

# 2. Install dependencies
npm install


### Environment Variables

Create a .env file in the *project root* (same level as package.json):

env
VITE_GEMINI_API_KEY=your_gemini_api_key_here
VITE_FIREBASE_API_KEY=your_firebase_api_key
VITE_FIREBASE_AUTH_DOMAIN=your_project.firebaseapp.com
VITE_FIREBASE_PROJECT_ID=your_project_id
VITE_FIREBASE_STORAGE_BUCKET=your_project.appspot.com
VITE_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
VITE_FIREBASE_APP_ID=your_app_id


### Start

bash
npm run dev


Open [http://localhost:3000](http://localhost:3000)

---

## 🔍 How It Works

Email arrives (subject + body + links)
           ↓
Gemini 2.0 Flash analyzes:
  • Sender domain — is it legitimate?
  • Urgency / Fear tactics present?
  • Brand impersonation attempt?
  • Suspicious links detected?
  • Social engineering indicators?
           ↓
Risk Score: 0–100
Verdict: PHISHING / SUSPICIOUS / SAFE
           ↓
Moderator takes action → Logged to audit trail



## 👥 Team

| Name | 
|------|------|
| *Nihat Mamedov* | Team Lead |
| *Meltem Qasimova* | 
| *Fidan Aslanova* | 
| *Celal Hummatli* | 

---

## 📄 License

Apache 2.0
