# 🏗️ Architecture Overview

This project is a full-stack habit tracker with modern tooling and professional structure.

---

## 🧠 Stack

- **Frontend**: Next.js (App Router)
- **Styling**: Tailwind CSS
- **Database**: PostgreSQL via Prisma ORM
- **Authentication**: Auth.js (NextAuth)
- **Deployment**: Vercel

---

## 📁 Folder Structure

```
/app            → Page components using Next.js App Router
/components     → Shared UI components
/lib            → Utilities (helpers, date functions, etc.)
/prisma         → Prisma schema, client, and seed file
/docs           → Internal developer documentation
```

---

## 🔗 Database Relationships

- `User` ↔ `Habit`: Linked by `userEmail` field
- Each `Habit` has booleans for `sun` through `sat` for weekly tracking
