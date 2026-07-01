<!-- README.md -->
<!-- GitHub Profile README – Newspaper Style -->
<!-- Designed for Yuvraj Singh | July 2026 -->

<!-- ███████████████████████████████████████████████████████████████████ -->
<!-- MASTHEAD – SVG-based (see assets/svg/masthead.svg)                -->
<!-- ███████████████████████████████████████████████████████████████████ -->

<p align="center">
  <img src="assets/svg/masthead.svg" alt="The Yuvraj Singh Chronicle" width="800">
</p>

<!-- Edition & Date -->
<p align="center" style="font-family: Georgia, serif; font-size: 14px; color: #756B5A; letter-spacing: 2px; border-top: 1px solid #756B5A; border-bottom: 1px solid #756B5A; padding: 6px 0; margin: 0 10%;">
  <span style="text-transform: uppercase;">Volume I • Issue I</span> &nbsp;|&nbsp; 
  <span style="text-transform: uppercase;">New Delhi, India</span> &nbsp;|&nbsp; 
  <span style="text-transform: uppercase;">July 2026</span> &nbsp;|&nbsp; 
  <span style="text-transform: uppercase;">Open Source Edition</span>
</p>

<!-- Tagline -->
<p align="center" style="font-family: 'Times New Roman', serif; font-size: 20px; color: #3D3D3D; font-style: italic; margin-top: 4px;">
  “Build it to break. Then rebuild it stronger.”
</p>

<!-- ███████████████████████████████████████████████████████████████████ -->
<!-- LEAD STORY – About Me                                               -->
<!-- ███████████████████████████████████████████████████████████████████ -->

## The Developer Who Tests Until It Breaks

**Yuvraj Singh** doesn't just write code—he designs systems that can withstand the unexpected.  

A Computer Science undergraduate at the University of Delhi (Class of 2026), Yuvraj's engineering philosophy was shaped early by a hackathon experience that forced him to think like an adversary. At **HackArena 2.0**, he built *ADVERSA*, a tool that intentionally feeds malformed data to APIs to uncover hidden failure modes. That project crystallised a conviction: *if you don't know how your system fails, you don't really know how it works.*

Since then, he has applied that mindset across the stack—from building a full‑featured ERP system with role‑based access control to deploying an AI‑powered visibility platform for local businesses. His work is characterised by pragmatic choices: caching for speed, strict validation for safety, and thoughtful architecture that scales without heroics.

In early 2026, Yuvraj contributed a fix to **NeutralinoJS**, resolving a Gdk‑CRITICAL assertion error on Linux—a subtle bug that surfaced only in headless environments. The pull request was merged into the main repository, marking his first open‑source contribution to a production framework.

Outside the terminal, he has organised the **ICET‑AICS 2026** conference, managing logistics for 200+ participants across hybrid tracks. He is currently seeking a software engineering internship or full‑time role where he can apply his skills in backend development, API design, and AI integration to build reliable, business‑critical systems.

<br>

<!-- ███████████████████████████████████████████████████████████████████ -->
<!-- QUICK FACTS (Side-by-Side)                                        -->
<!-- ███████████████████████████████████████████████████████████████████ -->

<table align="center" style="width: 80%; border-collapse: collapse; background: #F7F2E8; border: 1px solid #B9AD9A;">
  <tr>
    <td style="padding: 12px; vertical-align: top; width: 33%; border-right: 1px solid #B9AD9A;">
      <strong style="font-family: Georgia, serif; color: #1D1D1D;">🎓 Education</strong><br>
      <span style="font-size: 15px; color: #3D3D3D;">B.Sc. Computer Science</span><br>
      <span style="font-size: 14px; color: #756B5A;">University of Delhi · 2023–2026</span>
    </td>
    <td style="padding: 12px; vertical-align: top; width: 33%; border-right: 1px solid #B9AD9A;">
      <strong style="font-family: Georgia, serif; color: #1D1D1D;">💼 Status</strong><br>
      <span style="font-size: 15px; color: #3D3D3D;">Open for internships / roles</span><br>
      <span style="font-size: 14px; color: #756B5A;">Remote · On‑site (New Delhi)</span>
    </td>
    <td style="padding: 12px; vertical-align: top; width: 33%;">
      <strong style="font-family: Georgia, serif; color: #1D1D1D;">📬 Connect</strong><br>
      <span style="font-size: 15px; color: #3D3D3D;">
        <a href="mailto:yuvrajgoswamigir@gmail.com" style="color: #8A7150; text-decoration: none;">Email</a> · 
        <a href="https://linkedin.com/in/uvgoswami" style="color: #8A7150; text-decoration: none;">LinkedIn</a>
      </span>
    </td>
  </tr>
</table>

<br>

<!-- ███████████████████████████████████████████████████████████████████ -->
<!-- DIVIDER                                                            -->
<!-- ███████████████████████████████████████████████████████████████████ -->

<p align="center">
  <img src="assets/svg/divider.svg" alt="— ✦ —" width="600">
</p>

<!-- ███████████████████████████████████████████████████████████████████ -->
<!-- FEATURED PROJECTS – Newspaper Features                             -->
<!-- ███████████████████████████████████████████████████████████████████ -->

# Featured Projects

> *A selection of recent work — from enterprise systems to AI‑powered tools.*

---

### ① Enterprise ERP System for Consultancies

*Building a modular, secure backend for client and document management.*

**The Problem**  
Consultancies often juggle multiple clients, applications, and documents across spreadsheets and email. A centralised system was needed to track applications, manage user roles, and maintain an audit trail.

**The Solution**  
A REST API built with Node.js, Express, TypeScript, and Prisma, backed by PostgreSQL. The system implements three‑tier RBAC (Admin, Staff, Client), JWT authentication with refresh tokens, and secure PDF uploads (multer with MIME‑type filtering and 10 MB limits). Pagination ensures scalable staff workflows, and Zod validates all incoming payloads.

**Tech Stack**  
`Node.js` · `Express` · `TypeScript` · `PostgreSQL` · `Prisma` · `Zod` · `JWT` · `Multer`

**Lessons Learned**  
Designing a clean domain model upfront saved countless hours later. Indexing foreign keys and using cascading deletes carefully kept the database performant and consistent.

🔗 [Repository](https://github.com/uv-goswami/vipasa) · [Docs](https://github.com/uv-goswami/vipasa/blob/main/docs/API.md) *(if available)*

---

### ② NewsPulse – Real‑Time News Aggregator

*Stay informed with a curated feed from multiple sources.*

**The Problem**  
Staying on top of breaking news across different domains often requires visiting multiple websites or relying on noisy social media feeds.

**The Solution**  
A TypeScript-based application that aggregates headlines from various RSS/API sources and presents them in a clean, filterable interface. (Built with modern React and Node.js; details can be found in the repository.)

**Tech Stack**  
`TypeScript` · `React` · `Node.js` · *(additional specifics from the project)*

🔗 [Repository](https://github.com/uv-goswami/news-pulse) · [Live Demo](https://your-demo-link.com) *(if available)*

---

### ③ AiVault – AI Visibility Platform for Local Businesses

*Helping small businesses boost their online presence with AI‑generated metadata and scorecards.*

**The Problem**  
Local businesses struggle to rank in search results because they lack the time and expertise to optimise their online content.

**The Solution**  
A full‑stack platform with a FastAPI backend and a React frontend. The system integrates Google Gemini API to generate SEO‑friendly metadata (keywords, insights, intent labels) and computes a visibility score with actionable recommendations. Client‑side caching (REQUEST_CACHE Map) and server‑side caching (5‑minute TTL) achieve sub‑100ms page loads. Dynamic public pages include JSON‑LD and auto‑generated sitemap.xml for crawlers.

**Tech Stack**  
`Python` · `FastAPI` · `React` · `PostgreSQL` · `SQLAlchemy` · `Gemini AI` · `Docker` · `AWS S3` · `Render`

**Lessons Learned**  
Caching is not a silver bullet—cache invalidation logic must be carefully designed to avoid serving stale data. Also, integrating LLM APIs requires robust error handling and fallback strategies.

🔗 [Repository](https://github.com/uv-goswami/AV) · [Live Demo](https://aivault-frontend.onrender.com) *(if still up)* · [AWS S3 Hosted](http://aivault-frontend-portfolio.s3-website.ap-south-1.amazonaws.com/)

---

### ④ Job Tracker AI – Smarter Job Application Management

*Automate the matching of your resume to live job listings.*

**The Problem**  
Manually scanning job boards and tailoring applications is time‑consuming and repetitive.

**The Solution**  
A full‑stack portal built with React (Vite) and Node.js (Fastify), using Upstash Redis for session management and API caching. The system uses the Google Gemini API and pdf‑parser to extract text from uploaded resumes, then matches against live job listings from the JSearch API, highlighting the best fits.

**Tech Stack**  
`React` · `Node.js` · `Fastify` · `Redis (Upstash)` · `Gemini AI` · `JSearch API`

🔗 [Repository](https://github.com/uv-goswami/job-tracker-ai) · [Live Demo](https://job-tracker-ui-79a8.onrender.com)

---

<!-- ███████████████████████████████████████████████████████████████████ -->
<!-- DIVIDER                                                            -->
<!-- ███████████████████████████████████████████████████████████████████ -->

<p align="center">
  <img src="assets/svg/divider.svg" alt="— ✦ —" width="600">
</p>

<!-- ███████████████████████████████████████████████████████████████████ -->
<!-- OPEN SOURCE CONTRIBUTIONS                                          -->
<!-- ███████████████████████████████████████████████████████████████████ -->

## Open Source Contributions

**Neutralinojs** – *Merged PR #1636*  
Fixed a `Gdk‑CRITICAL` assertion error on Linux that occurred when the framework attempted to centre a window in environments without a primary monitor. The patch ensures graceful fallback, improving the framework's robustness on headless setups.

🔗 [Pull Request](https://github.com/neutralinojs/neutralinojs/pull/1636)

---

<!-- ███████████████████████████████████████████████████████████████████ -->
<!-- EXPERIENCE & EDUCATION                                            -->
<!-- ███████████████████████████████████████████████████████████████████ -->

## Professional Timeline

| Year | Role / Event | Details |
|------|--------------|---------|
| **2023 – 2026** | B.Sc. Computer Science | University of Delhi – coursework in DSA, OOP, DBMS, Cryptography, Software Engineering. |
| **April 2026** | Student Organizer, ICET‑AICS 2026 | Managed logistics for 200+ hybrid participants; coordinated volunteers and session chairs; issued 200+ certificates. |
| **2026** | Open Source Contribution | Merged PR to NeutralinoJS – fixed window‑centering bug on Linux. |
| **2026** | Hackathons | Singularity Vibeathon (offline AI assistant) · HackArena 2.0 (ADVERSA adversarial testing tool). |

---

<!-- ███████████████████████████████████████████████████████████████████ -->
<!-- SKILLS – Editorial Layout                                          -->
<!-- ███████████████████████████████████████████████████████████████████ -->

## Technical Skills

<table style="width: 100%; border-collapse: collapse; background: #F7F2E8;">
  <tr>
    <td style="padding: 10px; border: 1px solid #B9AD9A; width: 25%;"><strong>Languages</strong></td>
    <td style="padding: 10px; border: 1px solid #B9AD9A;">TypeScript · Python · JavaScript · SQL · C++</td>
  </tr>
  <tr>
    <td style="padding: 10px; border: 1px solid #B9AD9A;"><strong>Backend</strong></td>
    <td style="padding: 10px; border: 1px solid #B9AD9A;">Node.js · Express · FastAPI · PostgreSQL · Prisma · MySQL · Redis · JWT · Zod</td>
  </tr>
  <tr>
    <td style="padding: 10px; border: 1px solid #B9AD9A;"><strong>Frontend</strong></td>
    <td style="padding: 10px; border: 1px solid #B9AD9A;">React · Vite · React Router · Axios · Vanilla CSS</td>
  </tr>
  <tr>
    <td style="padding: 10px; border: 1px solid #B9AD9A;"><strong>Cloud &amp; DevOps</strong></td>
    <td style="padding: 10px; border: 1px solid #B9AD9A;">AWS (S3, EC2) · Docker · Render · Linux · Git</td>
  </tr>
  <tr>
    <td style="padding: 10px; border: 1px solid #B9AD9A;"><strong>AI &amp; Integration</strong></td>
    <td style="padding: 10px; border: 1px solid #B9AD9A;">Gemini API · LLM fallback · Prompt engineering · PDF parsing</td>
  </tr>
  <tr>
    <td style="padding: 10px; border: 1px solid #B9AD9A;"><strong>Other</strong></td>
    <td style="padding: 10px; border: 1px solid #B9AD9A;">REST API design · OpenAPI/Swagger · CI/CD · SEO (JSON‑LD, sitemap) · Postman</td>
  </tr>
</table>

<br>

<!-- ███████████████████████████████████████████████████████████████████ -->
<!-- GITHUB STATISTICS – Financial Report Style                        -->
<!-- ███████████████████████████████████████████████████████████████████ -->

## GitHub Activity Report

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=uv-goswami&show_icons=true&theme=graywhite&hide_border=true&bg_color=F7F2E8&title_color=1D1D1D&icon_color=8A7150&text_color=3D3D3D" alt="GitHub Stats" width="48%" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=uv-goswami&theme=graywhite&hide_border=true&background=F7F2E8&stroke=B9AD9A&ring=8A7150&fire=8A7150&currStreakLabel=1D1D1D" alt="Streak" width="48%" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=uv-goswami&layout=compact&theme=graywhite&hide_border=true&bg_color=F7F2E8&title_color=1D1D1D&text_color=3D3D3D" alt="Top Languages" width="50%" />
</p>

<!-- Visitor Counter -->
<p align="center">
  <img src="https://api.visitorbadge.io/api/visitors?path=uv-goswami&label=Readers&countColor=%238A7150&style=flat" alt="visitors" />
</p>

---

<!-- ███████████████████████████████████████████████████████████████████ -->
<!-- ACHIEVEMENTS & CERTIFICATIONS – Side-by-Side                      -->
<!-- ███████████████████████████████████████████████████████████████████ -->

<table style="width: 100%; border-collapse: collapse; background: #F7F2E8; border: 1px solid #B9AD9A;">
  <tr>
    <td style="padding: 12px; vertical-align: top; width: 50%; border-right: 1px solid #B9AD9A;">
      <h3 style="font-family: Georgia, serif; color: #1D1D1D; margin-top: 0;">🏆 Achievements</h3>
      <ul style="list-style: none; padding-left: 0;">
        <li style="margin-bottom: 8px;"><strong>Singularity Vibeathon 2026</strong> – Built a fully offline AI assistant using a lightweight local LLM.</li>
        <li style="margin-bottom: 8px;"><strong>HackArena 2.0 Delhi Zonals</strong> – Created ADVERSA, an adversarial testing tool for Python APIs.</li>
        <li><strong>NeutralinoJS PR</strong> – Merged bug fix for Linux window‑centering.</li>
      </ul>
    </td>
    <td style="padding: 12px; vertical-align: top; width: 50%;">
      <h3 style="font-family: Georgia, serif; color: #1D1D1D; margin-top: 0;">📜 Certifications</h3>
      <ul style="list-style: none; padding-left: 0;">
        <li><strong>Infosys Springboard</strong> – Python Fundamentals I &amp; II, Agile &amp; Software Engineering</li>
        <li><strong>OnWingspan</strong> – Python Foundation, OOP, DBMS I &amp; II, NoSQL, Agile Scrum</li>
      </ul>
    </td>
  </tr>
</table>

<br>

<!-- ███████████████████████████████████████████████████████████████████ -->
<!-- REPOSITORY INDEX – Categorised                                     -->
<!-- ███████████████████████████████████████████████████████████████████ -->

## Repository Index

A curated list of other projects, experiments, and academic work.

| Category | Repositories |
|----------|--------------|
| **Featured** (above) | [vipasa](https://github.com/uv-goswami/vipasa) · [news-pulse](https://github.com/uv-goswami/news-pulse) · [AV](https://github.com/uv-goswami/AV) · [job-tracker-ai](https://github.com/uv-goswami/job-tracker-ai) |
| **Research & Experiments** | [adversa](https://github.com/uv-goswami/adversa) · [College-Discovery-Platform](https://github.com/uv-goswami/College-Discovery-Platform) · [GraphOne](https://github.com/uv-goswami/GraphOne) |
| **Academic & Coursework** | Data-Structure · OS · CN · DAA · DBMS · WebProgramming · TOC · Cryptography · ML · Cloud-Computing · etc. |
| **Forks & Contributions** | neutralinojs · neutralino.js · urBackend · EnterpriseRAG-AI · GSOC2026 |

---

<!-- ███████████████████████████████████████████████████████████████████ -->
<!-- CONTACT – Classifieds Section                                     -->
<!-- ███████████████████████████████████████████████████████████████████ -->

## Classifieds

<p align="center" style="font-family: 'Courier New', monospace; font-size: 14px; border: 2px solid #756B5A; padding: 16px; width: 70%; margin: 0 auto; background: #F7F2E8;">
  <strong style="font-size: 18px;">📬 AVAILABLE FOR HIRE</strong><br><br>
  <span style="color: #1D1D1D;">Full‑stack developer · Backend engineer · AI integrator</span><br>
  <span style="color: #3D3D3D;">Open to internships and full‑time roles — remote or on‑site in New Delhi.</span><br><br>
  <span style="color: #756B5A;">
    ✉ <a href="mailto:yuvrajgoswamigir@gmail.com" style="color: #8A7150;">yuvrajgoswamigir@gmail.com</a> &nbsp;·&nbsp;
    🔗 <a href="https://linkedin.com/in/uvgoswami" style="color: #8A7150;">linkedin.com/in/uvgoswami</a> &nbsp;·&nbsp;
    🐙 <a href="https://github.com/uv-goswami" style="color: #8A7150;">github.com/uv-goswami</a>
  </span>
</p>

<br>

<!-- ███████████████████████████████████████████████████████████████████ -->
<!-- FOOTER                                                              -->
<!-- ███████████████████████████████████████████████████████████████████ -->

<p align="center" style="font-family: Georgia, serif; font-size: 13px; color: #756B5A; border-top: 2px solid #B9AD9A; padding-top: 12px; margin-top: 20px;">
  <span style="letter-spacing: 1px;">THE YUVRAJ SINGH CHRONICLE</span><br>
  <span style="font-size: 11px;">Printed digitally by GitHub Press · Open Source Edition · Updated Continuously</span><br>
  <span style="font-size: 10px;">Built with Markdown &amp; HTML · All content © 2026 Yuvraj Singh</span>
</p>
