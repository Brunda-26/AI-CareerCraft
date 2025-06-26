# 🧠 AI Career Coach – Full Stack Web App

An advanced AI-powered career coaching platform built using **React 19**, **Next.js 15**, **Tailwind CSS**, **NeonDB**, **Prisma**, **Clerk Authentication**, **Inngest**, **Gemini API**, and **Shadcn UI**. This app helps users build resumes, write cover letters, prepare for interviews, and stay informed with industry insights — all in one place.

## 🚀 Features

- 🔐 **User Authentication** – Secure login and signup via Clerk.
- 📝 **Resume Builder** – Create professional AI-assisted resumes.
- 📄 **Cover Letter Generator** – Customized letters for any job role.
- 🎯 **Interview Preparation**
  - Generates random interview questions using Gemini API
  - Displays progress graph and score
  - Stores previous quiz answers for future review
- 📊 **Industry Insights** – Get AI-curated trends and suggestions.

## 🛠️ Tech Stack

- **Frontend**: React 19, Next.js 15, Tailwind CSS, Shadcn UI  
- **Backend**: Prisma ORM, NeonDB (PostgreSQL), Inngest (serverless functions), Gemini API  
- **Authentication**: Clerk  
- **Other Tools**: Axios, ReactMarkdown

## 🔗 Integrations

- 🔐 [Clerk](https://go.clerk.com/pkesmB9) – Authentication
- 🗄️ [Neon](https://fyi.neon.tech/4rc) – PostgreSQL database
- ⚙️ [Inngest](https://innge.st/yt-rsc2) – Serverless functions and workflows

## 📦 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/ai-career-coach.git
   cd ai-career-coach
   
2. **Install dependencies**
   ```bash
   npm install
   
3. **Configure environment variables**
   Create a `.env` file in the root directory of the project and paste the following:

   ```env
   DATABASE_URL=your_postgres_connection_string_here

   NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
   CLERK_SECRET_KEY=your_clerk_secret_key

   NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
   NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
   NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
   NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding

   GEMINI_API_KEY=your_google_gemini_api_key

4. **Run the development server**
   ```env
   npm run dev

## 🗃️ Database

- Uses NeonDB (PostgreSQL) with Prisma ORM.
- Stores user data, resumes, cover letters, quiz attempts, scores, and answers.

## 📖 Tutorial Reference

This project was developed with guidance from a YouTube tutorial: 🎥[Build a Full Stack AI Career Coach](https://www.youtube.com/watch?v=UbXpRv5ApKA)  
Special thanks to the instructor for their detailed walkthrough.

