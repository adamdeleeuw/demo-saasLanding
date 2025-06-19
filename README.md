# ProdSaas — Modern SaaS Landing Page
*A full-stack SaaS landing template built in days to demo rapid Next.js/TypeScript delivery.*

[![Live Demo](https://img.shields.io/badge/live-demo-brightgreen)](https://demo-saas-landing.vercel.app/)
[![MIT License](https://img.shields.io/badge/license-demo-blue.svg)](LICENSE)

> **Disclaimer:** No payment or back-end is wired in the public demo.

---

## 1. Why I Built It
Modern SaaS startups need landing pages that **load fast, look premium, and convert**—without agency overhead. This template proves you can launch a beautiful, responsive, and accessible SaaS site in a weekend, ready to extend into a full product.

## 2. Thought Process & Design
- **User flow:** Land → see value prop → scan features/pricing → sign up or contact (≤ 90 s).
- **Design priorities:** Clean, modern branding, Tailwind palette, zero layout shift.
- **AI leverage:** Used shadcn/ui and Vercel v0 for scaffolding, then hand-tuned layouts, TypeScript, and accessibility.

## 3. Tech Stack & Architecture
| Layer        | Details                                                      |
|-------------|--------------------------------------------------------------|
| **Framework** | Next.js 14 (App Router) • React 18 • TypeScript             |
| **Styling**   | Tailwind CSS • shadcn/ui • Lucide icons                     |
| **Fonts**     | Inter via next/font                                         |
| **Infra**     | Deployed on Vercel; static assets in `/public`              |
| **CI/Dev**    | Push to Git, Vercel auto-builds and deploys                 |

## 4. Core Features
| Feature                | Impact                                             |
|------------------------|---------------------------------------------------|
| 🏠 **Hero Section**     | Drives visitors to sign up or learn more          |
| 💡 **Feature List**     | Highlights SaaS value props with icons            |
| 💰 **Pricing Table**    | Responsive, clear, and conversion-focused         |
| 🧑‍💼 **Testimonials**   | Auto-rotating, builds trust                       |
| 📧 **Newsletter Form**  | Collects leads, validates client-side             |
| 🧭 **Smooth Nav**       | Easy scroll, mobile menu, accessible              |
| 📱 **Mobile First**     | Fully responsive, touch-friendly                  |
| 🎨 **Modern Palette**   | Clean gradients, soft backgrounds                 |

## 5. Quick Start (Local)
```bash
git clone https://github.com/adamdeleeuw/demo-saasLanding.git
cd demo-saasLanding
npm install
npm run dev    # http://localhost:3000
```

## 6. Future Improvements 📈
- Stripe checkout for SaaS signups
- Cypress e2e for full nav + form flow
- SEO meta auto-generate from content
- Cloudinary CDN for on-the-fly image transforms
- PWA manifest + offline docs
- Fully integrate the "sign up/in" functionality

## 7. What I Learned 🧠
- 🚀 **SEO-First Development:** Leveraged Next.js for high Lighthouse scores and fast loads.
- 🛠️ **Modern Frontend Stack:** Built scalable UI with React, Tailwind, and shadcn/ui.
- 🧩 **Component-Driven Architecture:** Modular design for easy expansion.
- 🧪 **Automated Deployments:** Used Vercel for CI/CD and fast iteration.
- 📈 **Performance Optimization:** Tuned images, assets, and code splitting.
- 🤝 **Collaboration & Version Control:** Used Git and GitHub for source control and teamwork.

## 8. License

Released under the MIT License—free for learning, adaptation, and remixing.

## About Me

I’m Adam de Leeuw, a second-year Computer Engineering student at UBC. I build product-quality demos and production apps fast by blending low-overhead tech with AI tooling, then document the process for teammates and clients.

[Connect with me on LinkedIn](https://www.linkedin.com/in/adamjdl/)
