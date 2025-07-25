# 💰 AI Finance Platform

> An **AI-powered financial management platform** that helps you track, analyze, and optimize your finances with real-time insights and smart automation.  
> Deployed live on **Vercel** for instant access!

[![Next.js](https://img.shields.io/badge/Next.js-13-blue)](https://nextjs.org/) 
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.3-blueviolet)](https://tailwindcss.com/)  
[![Status](https://img.shields.io/badge/Live-Demo-brightgreen)](https://your-vercel-app-url.vercel.app)

---

## 🔗 Live Demo

👉 https://your-vercel-app-url.vercel.app

---

## 💡 Project Overview

This platform is an **AI Finance Management App** that empowers users to monitor and optimize their financial health. It provides a personalized dashboard powered by AI/ML analytics to track expenses, budgets, and suspicious activities in real-time.

Key features include:

- Real-time spending alerts  
- Automated weekly/monthly summaries by email  
- Intelligent insights using machine learning  
- Secure user authentication and data storage via Supabase  
- Responsive, modern UI built with Next.js and Tailwind CSS

---

## 🧠 How It Works

The platform collects your transaction data securely and applies AI models to:

1. Detect unusual transactions and alert you immediately  
2. Analyze spending patterns and suggest budget improvements  
3. Automatically send email notifications about your financial status  
4. Schedule periodic jobs for summaries and alerts using Inngest

---

## 📸 Screenshots

### 📊 Dashboard  
![Dashboard Screenshot](public/screenshots/dashboard.png)

---

## 🛠️ Tech Stack

- **Next.js** (React framework)  
- **Tailwind CSS** (UI styling)  
- **Prisma** (ORM for database)  
- **Supabase** (Backend-as-a-Service)  
- **Inngest** (Serverless job scheduler)  
- **SMTP / Resend API** (Email notifications)  

---

## 🚀 How to Run Locally

```bash
git clone https://github.com/your-username/ai-finance-platform.git
cd ai-finance-platform
npm install --legacy-peer-deps
cp .env.example .env
# Fill environment variables in .env file
npx prisma generate
npx prisma migrate dev --name init
npm run dev
```

---

## 📄 License

This project is licensed under the **MIT License**. Feel free to use, modify, and distribute it.

---

## 👨‍💻 Author & Support

Made with ❤️ by **[Braj Narayan Awasthi](https://www.linkedin.com/in/braj-narayan-awasthi-33193a274)**

If you find this project useful:

🌟 **Star** the repo  
🐛 **Report issues or request features**  
🔁 **Fork and customize for your needs!**

---

## 📝 Note

🚧 This project is still under development. Upcoming features include:

- 🧠 AI-Based Saving Recommendations  
- 📅 Budget Planning & Monthly Goals  
- 📊 Export Reports (CSV / PDF)  
- 🔐 Two-Factor Authentication (2FA)  
- 🧾 Expense Categorization using Machine Learning  

---
