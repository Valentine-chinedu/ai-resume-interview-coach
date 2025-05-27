This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.js`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.

# ✅ AI Resume & Interview Coach – Feature Checklist

## 🚀 MVP Features

### 🔐 Authentication & User Management

- [ ] User Sign Up / Login (NextAuth – Google/GitHub/Email)
- [ ] Protected dashboard routes
- [ ] User profile with name, email, and resume history

### 📄 Resume Upload & Parsing

- [ ] Upload resume (PDF/DOCX)
- [ ] Parse and extract plain text from uploaded file
- [ ] Store original and parsed resume in database
- [ ] Display parsed content for confirmation/edit

### 🤖 AI Resume Feedback

- [ ] Send resume content to AI (OpenAI or Gemini)
- [ ] Get structured suggestions:
  - [ ] Grammar & spelling
  - [ ] Tone and clarity
  - [ ] Keyword relevance (for selected job title)
  - [ ] ATS optimization tips
- [ ] Display feedback using collapsible suggestion cards

### 💬 Mock Interview Assistant

- [ ] Select job role (e.g., "Frontend Developer")
- [ ] AI generates role-specific interview questions
- [ ] Chat UI for user answers
- [ ] AI feedback on answers:
  - [ ] Clarity
  - [ ] Technical depth
  - [ ] Confidence
  - [ ] Suggestions

### 🧠 AI Integration

- [ ] AI prompt engineering for resume feedback
- [ ] AI prompt engineering for mock interview Q&A
- [ ] Context-aware responses with session history

### 💾 Storage & History

- [ ] Save resume feedback sessions
- [ ] Save mock interview sessions
- [ ] View history by date and resume version

---

## ✨ Optional Enhancements (Post-MVP)

### 🎙️ Voice & Accessibility

- [ ] Voice input for interview answers (Whisper)
- [ ] Text-to-speech for AI-generated questions
- [ ] Accessibility support (screen readers, keyboard nav)

### 📤 Resume Export & Sharing

- [ ] Export AI-enhanced resume as PDF
- [ ] Share resume feedback via public link

### 📊 Progress Tracker

- [ ] Charts for feedback scores over time
- [ ] Resume keyword improvement tracking

### 🛠️ Admin Dashboard

- [ ] View user and session analytics
- [ ] Monitor API usage
- [ ] Flag/report resume abuse

### 🧪 Developer Experience

- [ ] TypeScript + strict mode
- [ ] State management (Zustand or React Context)
- [ ] Prisma or Drizzle ORM
- [ ] CI/CD with Vercel
- [ ] .env config for API keys

---

## 🌐 UI/UX Features

- [ ] Tailwind + shadcn/ui for components
- [ ] Mobile responsiveness
- [ ] Toast notifications for status updates
- [ ] Dark mode toggle
