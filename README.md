## Hi there 👋

Hi, I’m a Software Engineer with experience spanning COBOL mainframe development, backend automation, and modern web platforms. I’ve worked with enterprise systems built on COBOL, DB2, VSAM, and CICS, supporting large-scale transaction processing while also developing automation tools and backend services using modern technologies. I enjoy building systems that automate workflows and bridge legacy mainframe environments with modern applications.

---

## 🚀 Featured Automation Projects

### 🧱 1. Job Application Automation & Job Scraping Platform

**Overview:**  
A large-scale automation platform that scrapes job listings and automatically applies to jobs across 35+ platforms including **Indeed, Monster, Reed, GoHire, Manatal**, and other HR portals.  
The system performs form filling, file uploads, captcha solving, and generates AI-powered answers to screening questions all running continuously on the cloud.

**Key Highlights:**

- Developed scalable scrapers using **Python**, **Zyte**, and **Playwright** or **Selenium**.
- Integrated **AI-generated screening question answers** using LLM APIs.
- Built a **Chrome Extension** for direct user-side job automation.
- Deployed automation scripts to **AWS Lambda** for 24/7 uptime.
- Implemented proxy rotation and CAPTCHA solving for anti-bot protection.

**Tech Stack:**  
`Python`, `Playwright`, `Zyte`, `AWS Lambda`, `MongoDB`, `CapSolver`, `Docker`, `Chrome Extension`, `LLM`

[Auto Apply Example](https://github.com/Howlmaster/GoHire_AutoApply)

[Job Scraper Example](https://github.com/Howlmaster/Job_Scraper)

---

### 🧱 2. Queensland Transport Slot Monitor (Selenium + Twilio)

**Overview:**  
A lightweight automation tool that monitors the **Queensland Transport** driving test booking site. It automatically checks for available time slots and sends a **WhatsApp notification** via **Twilio API** when a test slot within 2 weeks is found.

**Key Highlights:**

- Used **Selenium WebDriver** for site monitoring and parsing.
- Integrated **Twilio API** for real-time WhatsApp notifications.
- Added Email notifications to client's email via SMTP
- Designed for **scheduled execution** using scheduler.
- Included retry logic and exception handling for robust uptime.

**Tech Stack:**  
`Python`, `Selenium`, `Twilio API`, `BeautifulSoup`, `Scheduler`, `Docker`

[Booking Slots](https://www.service.transport.qld.gov.au/SBSExternal/application/CleanBookingDE.xhtml?dswid=5627)

---

### 🧱 3. TLS Connect Booking Automation (Playwright)

**Overview:**  
An automated system built with **Playwright** to manage and book **TLS Connect (visa appointment)** slots.  
It can log in, handle reCAPTCHAs, and book available slots intelligently with session management.

**Key Highlights:**

- Automated complete booking workflows including authentication and form submission.
- Managed **session persistence** for multi-run logins.
- Built to handle dynamic UI elements and network delays.
- Implemented error handling and async task orchestration.

**Tech Stack:**  
`Python`, `Playwright`, `asyncio`, `Proxy Rotation`, `2Captcha`, `Docker`

[Stake.com](https://stake.com/)

---

### 🧱 Chrome Extension Automation for Betting Platform (Stake.com)

**Overview:**  
Developed a **Chrome Extension** that automates key workflows on a major online betting platform.  
The system handles **real-time betting odds monitoring, automated wager placement, and account management** all while maintaining undetectable browser behavior to avoid anti-bot systems.  
This project was built as part of a large-scale backend automation framework designed to synchronize user activity across multiple betting accounts and APIs.

**Key Challenges & Solutions:**

- **Anti-bot Evasion:**  
  Implemented **human-like Playwright interactions** (mouse movement, delay randomization, DOM event simulation) to bypass advanced anti-detection mechanisms and Cloudflare Turnstile.
- **Session Persistence:**  
  Built secure session and cookie handling using **Chrome Storage API** and **JWT-based authentication** between the extension and backend server.
- **Dynamic Odds Scraping:**  
  Designed a **real-time WebSocket listener** and **DOM mutation observer** for continuous odds updates and instant reaction to betting events.
- **Concurrency Control:**  
  Integrated **ThreadPoolExecutor** and **async coroutines** for simultaneous bet processing across multiple user sessions.
- **Scalable Infrastructure:**  
  Deployed backend automation on **AWS ECS with Docker**, enabling distributed Chrome instances running in isolated containers.

**Tech Stack:**  
`Python`, `Playwright`, `JavaScript (Chrome Extension)`, `AWS ECS`, `Docker`, `MongoDB`, `WebSocket`, `Cloudflare Bypass`, `2Captcha API`, `Asyncio`, `JWT Auth`

---

## ⚙️ Core Expertise

- **Web Development** — Backend design, REST APIs, and scalable data pipelines.
- **Web Automation** — Browser-based bots for booking, scraping, and form filling.
- **Web Scraping** — Large-scale structured data extraction from dynamic websites.
- **Cloud Deployment** — Containerized automation deployed on AWS & Docker.
- **AI Integration** — Using LLMs for text generation and intelligent automation.

---

⭐ _Focused on building reliable, scalable, and intelligent web automation systems._
