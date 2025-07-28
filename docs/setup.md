# ⚙️ Setup Guide

Follow these steps to get the project running locally.

---

## 🧱 Prerequisites

- Node.js (v18 or higher)
- PostgreSQL database
- Git

---

## 📦 Installation

1. **Clone the repo**

```bash
git clone https://github.com/YOUR_USERNAME/livetracker.git
cd livetracker
```

2. **Install dependencies**

```bash
npm install
```

3. **Create a `.env.local` file**

```env
DATABASE_URL=postgresql://USER:PASSWORD@HOST:PORT/DATABASE
```

4. **Push schema to database**

```bash
npx prisma db push
```

5. **Start the server**

```bash
npm run dev
```

> Visit [http://localhost:3000](http://localhost:3000) to use the app locally.
