# AI Finance Platform - Built by Vikash Chahar 🔥🔥

A modern, full-stack AI-powered finance management platform built with Next.js, featuring intelligent transaction categorization, budget tracking, and financial insights.

## Features

- 🤖 AI-powered transaction categorization using Google Gemini
- 💳 Multi-account management with real-time balance tracking
- 📊 Interactive dashboards and financial analytics
- 🔐 Secure authentication with Clerk
- 📱 Responsive design with Tailwind CSS and Shadcn UI
- 🗄️ PostgreSQL database with Prisma ORM
- 📧 Email notifications with Resend
- 🛡️ Security with ArcJet protection

## Tech Stack

- **Frontend**: Next.js 15, React 19, Tailwind CSS
- **UI Components**: Shadcn UI, Radix UI
- **Authentication**: Clerk
- **Database**: PostgreSQL with Prisma
- **AI Integration**: Google Gemini API
- **Email Service**: Resend
- **Security**: ArcJet
- **Background Jobs**: Inngest

## Environment Setup

Create a `.env` file in the root directory with the following variables:

```env
# Database Configuration
DATABASE_URL="postgresql://username:password@localhost:5432/ai_finance_platform"
DIRECT_URL="postgresql://username:password@localhost:5432/ai_finance_platform"

# Clerk Authentication
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY="your_clerk_publishable_key_here"
CLERK_SECRET_KEY="your_clerk_secret_key_here"
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding

# Google Gemini AI
GEMINI_API_KEY="your_gemini_api_key_here"

# Email Service (Resend)
RESEND_API_KEY="your_resend_api_key_here"

# Security (ArcJet)
ARCJET_KEY="your_arcjet_key_here"
```

## Getting Started

1. Install dependencies: `npm install`
2. Set up your environment variables
3. Set up PostgreSQL database
4. Run database migrations: `npx prisma migrate dev`
5. Start development server: `npm run dev`


