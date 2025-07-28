This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

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

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.# 🧠 LiveTracker — Habit Tracking App

A full-stack habit tracker built with **Next.js**, **Tailwind CSS**, **Prisma**, and **PostgreSQL** — designed for speed, security, and scalability.

---

## 🚀 Tech Stack

- **Frontend**: Next.js 14 (App Router)
- **Styling**: Tailwind CSS
- **Database**: PostgreSQL with Prisma ORM
- **Auth**: Auth.js (OAuth + Credentials)
- **Hosting**: Vercel

---

## 📦 Features

- ✅ User authentication
- ✅ Create new habits
- ✅ Assign days (Sun to Sat) per habit
- ✅ Responsive weekly grid layout
- ✅ Professional Git workflow
- 🔜 Streak tracking and visual stats (coming soon)

---

## 🛠️ Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/YOUR_USERNAME/livetracker.git
cd livetracker
```

### 2. Install dependencies

```bash
npm install
```

### 3. Set up environment variables

Create a `.env.local` file:

```env
DATABASE_URL=postgresql://USER:PASSWORD@HOST:PORT/DATABASE
```

### 4. Push Prisma schema to the DB

```bash
npx prisma db push
```

### 5. Start the dev server

```bash
npm run dev
```

---

## 🗂️ Project Structure

```
/app            → Next.js App Router pages
/components     → UI and layout components
/lib            → Utility functions
/prisma         → Prisma schema and seed
/docs           → Project documentation
```

---

## 🧪 Scripts

```bash
npm run dev       # Start local dev server
npm run build     # Build for production
npm run lint      # Run ESLint
```

---

## 📄 License

MIT — [yourname](https://github.com/YOUR_USERNAME)


