# Awesome-Candidate-Sourcing-Platform

# Top Candidate Sourcing Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Talent Discovery, Candidate Matching, Resume Parsing & Recruiting CRM*
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Candidate Sourcing**. These tools help recruiters and talent acquisition teams discover candidates, match profiles to job requirements, parse resumes, and manage recruiting pipelines.

**Examples** include SeekOut, hireEZ, AmazingHiring, Fetcher, Entelo, Gem, SourceWhale, Loxo, Hiretual, and Juicebox (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom matching logic, and transparent candidate data — ideal for recruiting teams that need full control over their sourcing infrastructure without per-seat SaaS fees or vendor lock-in.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[SeekOut](https://seekout.com/)**
  AI-powered talent sourcing platform with access to 1B+ profiles. Provides diversity sourcing, candidate matching, and talent analytics.

- **[hireEZ](https://hireez.com/)**
  Recruiting CRM and sourcing platform (formerly Hiretual). Provides candidate discovery, outreach automation, and talent pooling with 800M+ profiles.

- **[AmazingHiring](https://amazinghiring.com/)**
  AI-powered technical recruitment platform. Sources software engineers from GitHub, Stack Overflow, and social networks with deep technical profiling.

- **[Fetcher](https://fetcher.ai/)**
  Automated sourcing and outreach platform. Uses AI to identify and engage candidates, with personalized email sequences.

- **[Entelo](https://www.entelo.com/)**
  Talent acquisition platform with predictive analytics. Provides diversity sourcing, candidate matching, and outreach automation.

- **[Gem](https://www.gem.com/)**
  Recruiting CRM and talent engagement platform. Provides sourcing automation, outreach sequences, and pipeline analytics integrated with ATS.

- **[SourceWhale](https://www.sourcewhale.com/)**
  Multichannel sourcing and outreach platform. Automates candidate engagement across email, LinkedIn, and phone.

- **[Loxo](https://www.loxo.co/)**
  Recruiting CRM with built-in sourcing, outreach, and ATS capabilities. Provides candidate discovery and pipeline management.

- **[Juicebox](https://juicebox.work/)**
  People search engine with natural language queries. Provides candidate discovery across LinkedIn and other sources.

## Open-Source GitHub Projects

### Applicant Tracking & Recruiting CRM

- **[OpenCATS](https://github.com/opencats/OpenCATS)**
  **The most established open-source applicant tracking system and recruiting CRM.** Free, community-maintained ATS designed for recruiters to manage the recruiting process from job posting through candidate selection and submission . Features candidate management with resumes, notes, status history, and recruiting activity; recruiting CRM with jobs, companies, contacts, and submissions; and full open-source control for self-hosting and code inspection . Actively maintained with PHP 8.4/8.5 modernization roadmap including search, API, and integration improvements . **Open source**.

- **[JobLeet](https://github.com/nixhantb/jobleet-ui)**
  Smart recruitment CRM platform connecting job seekers, recruiters, and companies. Features application tracking, personalized job recommendations, real-time notifications, analytics dashboard, communication system, resume builder, interview scheduling, role-based access control, talent pool management, and GDPR compliance. Built with Next.js 15 and TypeScript .

- **[HR-OS](https://github.com/rathishreya/HR-OS)**
  **AI-native hiring operating system** (FastAPI + React). Runs locally with zero keys using rule-based fallback, upgrades to full AI with credentials. Features candidate ingestion (paste or PDF/DOCX/TXT upload), resume parsing, embeddings, **explainable weighted AI scoring**, ranked pipeline, AI chat screening interview, stage management, and **MCP server** exposing 10 hiring tools. Tech stack: FastAPI + SQLAlchemy 2.0, SQLite/PostgreSQL, Claude/Ollama/rule-based AI, React 19 + Vite + Tailwind v4, Docker deployment. **Open source** .

### Resume Parsing & Candidate Matching

- **[ResumeParser](https://github.com/HarithaNetha8/ResumeParser)**
  AI-powered resume parsing tool built with Python. Extracts structured information including **Name, Email, Phone Number, Skills** from resumes in PDF, DOCX, and TXT formats. Uses NLP (NLTK/spaCy) for accurate parsing with REST API support. Tech stack: Python, Flask, PyMuPDF/pdfplumber, python-docx. **Open source** .

- **[candidate-scorer](https://github.com/soldera-org/candidate-scorer)**
  Hiring page crawler and candidate scorer. Chrome extension captures LinkedIn applications, then Python script scores candidates against job advert, culture, and interview documents using Claude API. **Open source** .

- **[job-scraper](https://github.com/anandanair/job-scraper)**
  AI-powered suite to automate job scraping, resume parsing, job-to-resume scoring, and application tracking via GitHub Actions. Scrapes LinkedIn and CareersFuture, parses resume using AI, scores jobs against parsed resume. Uses Supabase for storage, LiteLLM for model flexibility. **Open source** .

- **[LibMatch](https://github.com/)**
  Official implementation of **LibMatch**, an AI-powered proactive talent acquisition framework that matches job postings with qualified GitHub developers based on their **software library usage** (Annals of Data Science, 2026). Python-based. **Open source** .

### Job Boards & Talent Discovery

- **[OpenPostings](https://github.com/Masterjx9/OpenPostings)**
  Open-source ATS aggregator syncing job data from **110,000+ companies** across 80+ ATS platforms including Greenhouse, Lever, Workday, BambooHR, Ashoka, and government job sites. Pulls new job data at random, stores in database with 24-hour retention. Available as Android app and Windows installer. **Open source** .

- **[JobHuntTS](https://github.com/BaseMax/JobHuntTS)**
  Open-source job board platform with GraphQL API. Enables employers to post listings and job seekers to search and apply. Features job queries (getJobs, getJobById, getJobByTitle, getJobByCategory, getFeaturedJobs), user applications, bookmarks, reviews, and categories. Built with Express.js and GraphQL .

- **[GitCareers/ProgrammingJobs](https://github.com/GitCareers/ProgrammingJobs)**
  Free, open-source job board leveraging **GitHub Issues for job listings** and **Pull Requests for candidates to express interest**. Employers post via Issues, candidates apply via PR with skills and portfolio. Labels enable filtering by role, language, and location. **Open source** .

### AI-Powered Sourcing Tools

- **[LinkedIn Recruiter Assistant](https://github.com/junqing258/linkedin-job-assistant)**
  LLM-based Chrome extension for LinkedIn Recruiter search optimization. Converts natural language hiring requirements to precise LinkedIn search conditions, with semantic candidate ranking based on job description match. Tech stack: React 18, TypeScript, Vite, Tailwind CSS, OpenAI GPT-4 API. **Open source** .

- **[TalentLedger](https://github.com/C4rcer/talent-ledger)**
  Firefox extension for LinkedIn candidate tracking. Capture profiles with one click, log contacts against jobs, track outreach on Kanban board with reminders. Export to Excel, CSV, or ATS format (Greenhouse, Workable, Teamtailor). Everything stored locally — no account, no server. **Open source** .

- **[OpenJobs AI / People Skills](https://github.com/OpenJobsAI/openjobs-openclaw-skills)**
  OpenClaw Skills for recruiting, talent sourcing, and job search powered by OpenJobs AI. Includes people search, candidate-job matching, job discovery, and academic scholar search skills for AI assistants. Open source .

### Additional Strong Open-Source Options

- **ATS & Recruiting CRM**: **OpenCATS** (most established, actively maintained), **JobLeet** (modern Next.js), **HR-OS** (AI-native with MCP server) .
- **Resume Parsing**: **ResumeParser** (Python + NLP), **candidate-scorer** (Chrome + Claude), **job-scraper** (GitHub Actions automation) .
- **Job Boards**: **OpenPostings** (110K+ companies), **JobHuntTS** (GraphQL), **GitCareers** (GitHub Issues-based) .
- **AI Sourcing**: **LibMatch** (GitHub developer matching), **LinkedIn Recruiter Assistant** (search optimization), **TalentLedger** (local candidate tracking) .

**Frameworks for building custom systems**: Combine **OpenCATS** for the ATS/CRM foundation, **ResumeParser** for structured resume extraction, **HR-OS** for AI-powered candidate scoring and screening, and **OpenPostings** for job data aggregation. Add **PostgreSQL** for persistence and **Docker** for deployment.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Candidate sourcing platforms handle sensitive personal data; ensure compliance with GDPR, CCPA, and applicable employment regulations.
- **Open-source reality**: The open-source ecosystem for candidate sourcing is **developing but not yet equivalent to commercial platforms**. **OpenCATS** provides a mature ATS/CRM foundation . **HR-OS** offers AI-native hiring with explainable scoring . Resume parsing tools (**ResumeParser**, **candidate-scorer**) provide building blocks . However, commercial platforms (SeekOut, hireEZ, Gem) offer **1B+ candidate profiles**, advanced diversity sourcing, and enterprise-grade outreach automation that open-source alternatives cannot match without significant data partnerships and infrastructure investment.

---

**Made for recruiters, talent acquisition teams, HR technologists, and sourcing specialists.**
Let's make candidate sourcing more open, transparent, and effective.
