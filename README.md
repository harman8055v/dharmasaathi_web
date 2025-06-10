# DharmaSaathi Web

**Spiritual Matchmaking for Modern India**

DharmaSaathi is India’s first spiritual matrimony and conscious dating platform—connecting yogis, meditators, seekers, and spiritual explorers for meaningful, dharma-based relationships and marriage. This is not your typical matrimony or dating clone—it’s built for deep compatibility, trust, and authentic connections.

---

## 🌟 Live Preview

[www.dharmasaathi.com](https://www.dharmasaathi.com)  
*(Replace with your actual deployment URL)*

---

## 🚀 Key Features

- **Modern, Swipe-based Discovery**  
  - Tinder/Aisle style swipe cards (like, pass, superlike, undo, filters)
  - Real-time matching and notifications

- **Deep, Multi-step Onboarding**  
  - Collects personal, professional, spiritual, and lifestyle details  
  - Photo gallery (min 1, up to 6), KYC/ID upload, completeness meter

- **Advanced Profile Management**  
  - Full profile edit, privacy controls, photo crop/reorder, verified badge

- **Matching & Messaging**  
  - Mutual likes create matches  
  - Real-time chat (Supabase Realtime), typing indicators, read receipts (premium)

- **Who Liked Me & Who Viewed Me**  
  - See who has liked or viewed your profile  
  - Free users see blurred previews; premium users get full access

- **Premium Membership & Payments**  
  - Unlock unlimited swipes, more superlikes, profile boosts, incognito mode, and more
  - Razorpay-powered checkout, instant upgrade/downgrade

- **Admin & Moderation**  
  - Report/block users, admin dashboard, KYC verification, analytics

- **Safety, Trust, and Privacy First**  
  - All profiles must verify by email/OTP  
  - KYC/ID badge, privacy settings, incognito browsing (premium)

---

## 🛠️ Tech Stack

- **Frontend:** Next.js 14 (React, SSR), TypeScript, TailwindCSS
- **Backend/DB:** Supabase (PostgreSQL, Auth, Realtime, Storage)
- **Payments:** Razorpay (INR, UPI, cards, wallets)
- **CI/CD & Hosting:** GitHub, Vercel
- **Other:** PWA-ready, fully responsive, SEO optimized

---

## 📁 Repository Structure

/pages — Next.js route pages (home, discovery, matches, profile, etc.)
/components — React components (swipe card, onboarding, chat, filters, etc.)
/lib — Supabase client, utilities, API helpers
/styles — Tailwind and global CSS
/public — Images, icons, logo
/hooks — React custom hooks
PRD.md — Product Requirements Document (full MVP spec)
AGENTS.md — Agent/dev guide for Codex and contributors
db_schema.md — Database schema (Supabase/PostgreSQL)
.env.example — Example environment variable file


---

## 📝 Setup & Installation

**1. Clone this repository**

git clone https://github.com/YOUR-USERNAME/dharmasaathi_web.git
cd dharmasaathi_web

**2. Install dependencies

npm install

**3. Set up environment variables

Copy .env.example to .env.local and fill in your actual keys:

NEXT_PUBLIC_SUPABASE_URL=your-supabase-url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your-supabase-anon-key
NEXT_PUBLIC_RAZORPAY_KEY_ID=your-razorpay-key-id
# (Do NOT expose secret keys on frontend!)

**4. Run the app locally

npm run dev

**5. Deploy
Push to GitHub → Vercel will auto-deploy if connected.

📚 Documentation
PRD.md — Full product requirements (features, flows, logic)

AGENTS.md — Developer/AI agent guide (structure, style, workflow)

db_schema.md — Database schema

💡 Contributing
Pull requests, ideas, and suggestions are welcome!
Please read PRD.md and AGENTS.md for contribution guidelines.

🙏 Credits & License
Created by Harman Batish
MIT License.
Built with ❤️ for India’s spiritual seekers.

📬 Contact
For feedback, support, or partnership:
harman@dharmasaathi.com
Instagram: @dharmasaathi



