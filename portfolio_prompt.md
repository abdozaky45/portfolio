# Portfolio Website — Claude Code Prompt

## Your Task
Build a **world-class personal portfolio website** for a backend developer. This is a single HTML file with embedded CSS and JS — no frameworks, no build tools, fully self-contained and ready to deploy.

---

## About the Developer

**Name:** Abdulrahman Mohamed Zaki
**Title:** Backend Developer
**Location:** Cairo, Egypt
**Email:** abdulrahmanmohamedzaki20@gmail.com
**Phone:** +20 1025502697
**LinkedIn:** https://www.linkedin.com/in/abdulrahman-mohamed-zaki-70175521a/
**GitHub:** https://github.com/abdozaky45

**Summary:**
Backend developer with 3 years of experience building and shipping production systems across e-commerce, ERP, and auction platforms. Delivered REST APIs, cloud infrastructure, and real-time services that serve live users in production. Proficient in Node.js, NestJS, TypeScript, MongoDB, PostgreSQL, Redis, and AWS — with hands-on experience integrating payment gateways, OAuth 2.0 social authentication, and Socket.io into scalable backends.

---

## Experience

### Backend Developer — TechOrg (منظمة التقنية) · Part-time
**March 2026 – Present | Cairo, Egypt · Remote**
- Design and implement RESTful APIs and backend services using Node.js and TypeScript
- Collaborate with cross-functional teams to define requirements, review code, and ship features
- Enforce best practices in API design, JWT authentication, and error handling

### Backend Developer — Geek Labs Holdings · Full-time
**September 2024 – April 2025 | Cairo, Egypt · On-site**
- Developed and maintained the MachineGenius ERP platform (AI-powered) using Node.js, Express.js, MongoDB
- Designed MongoDB schemas for multi-module ERP data (inventory, orders, users)
- Implemented multi-role JWT authentication with access/refresh token rotation
- Integrated YouTube API and third-party services for media and automation features
- Applied error handling, Joi validation, and unit testing for production reliability

### Backend Node.js Developer — Route · Self-employed
**May 2023 – October 2023 | Cairo, Egypt · Remote**
- Built and delivered multiple backend projects independently
- Covered REST API design, authentication, and MongoDB data modeling

---

## Projects (4 live production projects)

### 1. ERP Genius AI — AI-Powered ERP System
**URL:** https://machinegenius.io/
- Built core backend for MachineGenius's AI-driven ERP platform
- Multi-module business logic: inventory, orders, user management
- AI layer for automated business decisions and intelligent reporting
- Secure multi-role authentication system
**Stack:** Node.js, TypeScript, Express.js, MongoDB, JWT, AWS S3, YouTube API

### 2. S&N Store — Live E-Commerce Production
**URL:** https://sn-lingerie.com/
- Full e-commerce backend serving real customers in Egypt
- Modular REST APIs: product catalog, categories, variants, orders, customer management
- MongoDB transactions with bulkWrite for multi-document atomicity
- AWS S3 media storage with presigned URLs + AWS SNS notifications
- Deployed on AWS Elastic Beanstalk; resolved production memory crash under load
- CI/CD pipeline via GitHub Actions
**Stack:** Node.js, TypeScript, Express.js, MongoDB, Redis, BullMQ, AWS (EC2, S3, SNS, Elastic Beanstalk), Nodemailer, GitHub Actions

### 3. aToZAccessory — Live E-Commerce Production
**URL:** https://www.atozaccessory.com/
**GitHub:** https://github.com/abdozaky45/atozaccessories
- Live accessories store backend serving real users in production
- JWT authentication, product management, cart, order tracking
**Stack:** Node.js, TypeScript, Express.js, MongoDB, JWT, AWS S3

### 4. Missing Finder — Social Platform with AI Facial Recognition
**GitHub:** https://github.com/abdozaky45/missing-finder
- Platform to report and track missing persons
- AI-powered facial recognition for case matching
- Detailed analytics and statistics for reported cases
**Stack:** Node.js, JavaScript, Express.js, MongoDB, face-api.js

---

## Skills

**Languages:** TypeScript, JavaScript (ES6+), Node.js
**Frameworks:** NestJS, Express.js, Socket.io, BullMQ, Agenda, Joi, Nodemailer
**Databases:** MongoDB (Mongoose), PostgreSQL (TypeORM), MySQL
**Caching & Queues:** Redis, BullMQ — session management, rate limiting, background jobs
**API:** REST APIs, GraphQL, API design, API testing, Postman
**Payments & Auth:** Payment Gateways, Apple Pay, OAuth 2.0, Google Login, Apple Login, JWT, bcrypt
**Architecture:** Systems Design, Software Architecture, Microservices, Event-Driven Design, OOP, SOLID
**Cloud & DevOps:** AWS (EC2, S3, SNS, Elastic Beanstalk), GitHub Actions (CI/CD), Docker
**Domains:** E-Commerce, Backend for Mobile Apps, ERP Systems, Real-Time Systems

---

## Education

- **Bachelor of Management Information Systems** — Al Shorouq Academy (2024)
- **Diploma in Backend Development (Node.js Track)** — Route Academy (2023, 5 months)

---

## Design Requirements

### Aesthetic Direction
Go **dark, technical, and premium** — like a high-end developer tool or a SaaS dashboard.
- Dark background: deep navy or near-black (#0A0F1E or #080C14)
- Accent color: electric blue or cyan (#00D4FF or #3B82F6)
- Secondary accent: subtle purple or teal for depth
- Text: crisp white with gray hierarchy
- Feel: like you're looking at a pro developer's work, not a student project

### Typography
- Display/heading font: something geometric and sharp — try **"Space Mono"**, **"JetBrains Mono"**, or **"Syne"** from Google Fonts
- Body font: clean and readable — **"Inter"** or **"DM Sans"**
- Mix monospace for code-style labels and sans-serif for readable text

### Layout & Sections (single-page, smooth scroll)
1. **Hero** — Full viewport. Name + title + summary. Animated typing effect on the title. Subtle animated background (CSS grid lines, particles, or circuit-board pattern). CTA buttons: "View Projects" + "Download CV" + "Contact Me"
2. **About** — Short bio paragraph + 3 highlight stats: "3 Years Experience", "4 Live Projects", "3 Companies"
3. **Skills** — Grouped by category with visual tags/badges. Animate them on scroll.
4. **Experience** — Timeline layout. Each job as a card with company, title, dates, bullets. Animate on scroll.
5. **Projects** — 2-column grid of cards. Each card: project name, description, stack badges, live site button + GitHub button. Highlight "LIVE" badge on production projects.
6. **Contact** — Email, phone, LinkedIn, GitHub. Clean icon links. Copy-to-clipboard on email.
7. **Footer** — Minimal. Name + "Built with passion" or similar.

### Interactions & Animations
- Smooth scroll navigation with active section highlighting in navbar
- Sticky navbar that changes appearance on scroll (transparent → solid)
- Staggered fade-in + slide-up on scroll for all sections
- Hover effects on project cards: subtle glow or border animation
- Typing/typewriter effect in hero for the developer title
- Cursor glow effect (optional but impressive)
- "LIVE" badge pulse animation on production projects
- Scroll progress indicator at top of page

### Technical Requirements
- Single HTML file — all CSS and JS embedded
- No frameworks (vanilla HTML/CSS/JS only)
- Must be fully responsive (mobile, tablet, desktop)
- Smooth 60fps animations
- Fast loading — no heavy external dependencies except Google Fonts
- Semantic HTML for accessibility
- All links open in new tab

### Extra Polish
- Add a subtle noise/grain texture overlay on the background
- Code-style section labels (like `// 01. about`, `// 02. skills`)
- Subtle glowing effects on accent elements
- The navbar should show the developer's initials "AMZ" as a logo

---

## Important Notes
- This is a **real developer's portfolio** — make it look like someone who ships production code, not a student project
- Every section should feel intentional and polished
- The 4 live production projects are the HIGHLIGHT — make them stand out
- Keep copy exactly as provided above — don't invent or change any information
- All external links (LinkedIn, GitHub, live sites) must be correct and working

---

Output: A single complete `index.html` file, ready to open in a browser or deploy to GitHub Pages / Netlify.
