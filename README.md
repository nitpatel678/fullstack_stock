# TradeLens - Stock Market App — Alerts, Charts, AI Insights

> **Live Demo:** [Click here](https://tradelens-xi.vercel.app/)

> ⚠️ Important: Currently, the live email and summary of Inngest are not working in the live demo but it works fine in the development localhost mode.

This repository contains the code for **TradeLens**, an AI-powered modern stock market app built with **Next.js**, **Shadcn**, **Better Auth**, and **Inngest**. Track real-time prices, set personalized alerts, explore company insights, and manage watchlists.  

The admin dashboard allows managing stocks, publishing news, and monitoring user activity. Event-driven workflows power automated alerts, AI-driven daily digests, earnings notifications, and sentiment analysis—perfect for developers looking for a dynamic, real-time financial platform.

---

## ✨ Features

- **Stock Dashboard:** Track real-time stock prices with interactive line and candlestick charts, including historical data. Filter stocks by industry, performance, or market cap.  
- **Powerful Search:** Quickly find the best stocks with an intelligent search system.  
- **Watchlist & Alerts:** Create a personalized watchlist, set alert thresholds for price changes or volume spikes, and receive instant email notifications.  
- **Company Insights:** Explore detailed financial data including PE ratio, EPS, revenue, recent news, filings, analyst ratings, and sentiment scores.  
- **Real-Time Workflows:** Powered by Inngest for price updates, alert scheduling, automated reporting, and AI-driven insights.  
- **AI-Powered Alerts & Summaries:** Personalized market summaries, daily digests, and earnings report notifications.  
- **Customizable Notifications:** Fine-tune alerts and notifications based on watchlists and preferences.  
- **Analytics & Insights:** Gain insights into user behavior, stock trends, and engagement metrics.  

---

## ⚙️ Tech Stack

- **[Next.js](https://nextjs.org/):** Full-stack React framework with SSR and API routes.  
- **[Shadcn](https://shadcn.com/):** Open-source customizable and accessible React components.  
- **[TailwindCSS](https://tailwindcss.com/):** Utility-first CSS framework.  
- **[TypeScript](https://www.typescriptlang.org/):** Strongly typed JavaScript superset.  
- **[Better Auth](https://betterauth.com/):** Authentication & authorization library with email, social logins, and MFA.  
- **[Inngest](https://www.inngest.com/):** Event-driven workflows and background jobs.  
- **[Finnhub](https://finnhub.io/):** Real-time financial market data API.  
- **[MongoDB](https://www.mongodb.com/):** NoSQL database.  
- **[Nodemailer](https://nodemailer.com/):** Node.js email sending library.  
- **[CodeRabbit](https://coderabbit.ai/):** AI code review assistant.  

---

## 🤸 Quick Start

### Prerequisites

Ensure you have the following installed:  

- Git  
- Node.js  
- npm (Node Package Manager)  

### Clone the Repository

```bash
git clone https://github.com/nitpatel678/fullstack_stock.git
cd tradelens
```

### Install Dependencies
```
npm install
```
### Setup Env
```
NODE_ENV='development'
NEXT_PUBLIC_BASE_URL=http://localhost:3000

# FINNHUB
NEXT_PUBLIC_FINNHUB_API_KEY=
FINNHUB_BASE_URL=https://finnhub.io/api/v1

# MONGODB
MONGODB_URI=

# BETTER AUTH
BETTER_AUTH_SECRET=
BETTER_AUTH_URL=http://localhost:3000

# GEMINI
GEMINI_API_KEY=

# NODEMAILER
NODEMAILER_EMAIL=
NODEMAILER_PASSWORD=
```

### Run the project
```
npm run dev
npx inngest-cli@latest dev
```

Do Add A Star :)
