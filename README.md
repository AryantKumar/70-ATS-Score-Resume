# 📄 ATS-Optimized Resume Template (80+ ATS Score)

By **[Aryant Kumar](https://github.com/AryantKumar)** — A professionally crafted LaTeX resume template engineered to **score 80+ on Applicant Tracking Systems (ATS)** while maintaining a clean, modern design that appeals to human recruiters.

---

## 🎯 What is an ATS Score?

An **Applicant Tracking System (ATS)** is software used by employers to filter resumes before they reach human eyes. It scans your resume for:

- **Keywords** matching the job description
- **Proper formatting** and structure
- **Standard section headings**
- **Consistent date formats**
- **Contact information** completeness

> **This template is designed to pass ATS filters with a score of 80% or higher** by following all best practices outlined below.

---

## ✅ ATS Optimization Checklist

| # | Optimization Rule                        | Status |
|---|------------------------------------------|--------|
| 1 | Use standard section headings            | ✅      |
| 2 | No tables, columns, or text boxes        | ✅      |
| 3 | No images, logos, or graphics            | ✅      |
| 4 | No headers or footers for critical info  | ✅      |
| 5 | Standard fonts (Arial, Calibri, Georgia) | ✅      |
| 6 | Font size between 10–12pt               | ✅      |
| 7 | Single-column layout                     | ✅      |
| 8 | Consistent date format (MMM YYYY)        | ✅      |
| 9 | PDF output (preserves formatting)        | ✅      |
| 10| Clear contact info at the top            | ✅      |
| 11| Keywords from the job description        | ✅      |
| 12| Bullet points for experience entries     | ✅      |
| 13| Quantified achievements (numbers/%)      | ✅      |
| 14| No special characters or icons           | ✅      |
| 15| Proper use of bold for emphasis          | ✅      |

---

## 📐 Template Structure

The resume template follows this **ATS-friendly structure** with standard section names:

```
┌──────────────────────────────────────┐
│           FULL NAME                  │
│   Email | Phone | Location | Links   │
├──────────────────────────────────────┤
│         PROFESSIONAL SUMMARY         │
│  2-3 lines with target keywords      │
├──────────────────────────────────────┤
│            EXPERIENCE                │
│  Company | Role | Dates              │
│  • Achievement with metrics          │
│  • Achievement with metrics          │
├──────────────────────────────────────┤
│             PROJECTS                 │
│  Project Name | Tech Stack | Link    │
│  • Description with impact           │
├──────────────────────────────────────┤
│           TECHNICAL SKILLS           │
│  Category: Skill1, Skill2, Skill3    │
├──────────────────────────────────────┤
│            EDUCATION                 │
│  Degree | University | Dates | GPA   │
├──────────────────────────────────────┤
│         CERTIFICATIONS               │
│  Certification Name — Issuer (Year)  │
└──────────────────────────────────────┘
```

---

## 🔑 Key Principles for 80+ ATS Score

### 1. Keyword Optimization
- **Mirror the job description**: Use the exact phrasing from the job posting.
- **Include both acronyms and full forms**: e.g., *Machine Learning (ML)*.
- **Place critical keywords** in the Summary, Skills, and Experience sections.

### 2. Formatting Best Practices
- **Single-column layout** — ATS parsers struggle with multi-column designs.
- **Standard headings** — Use "Experience" not "Where I've Worked."
- **No graphics or icons** — ATS cannot read images; use plain text only.
- **Consistent bullet style** — Use simple round bullets (`•`).

### 3. Achievement-Driven Bullets
Write each bullet using the **CAR method**:
- **C**hallenge — What problem did you face?
- **A**ction — What did you do?
- **R**esult — What was the measurable outcome?

**Example:**
> Reduced API response time by 40% by implementing Redis caching layer, handling 10K+ requests/min in production.

### 4. Skills Section Strategy
Organize skills by category for both ATS parsing and human readability:
- **Languages:** Python, JavaScript, TypeScript, Java, C++
- **Frameworks:** React, Node.js, Django, Spring Boot
- **Databases:** PostgreSQL, MongoDB, Redis
- **Tools & Platforms:** Docker, Kubernetes, AWS, Git, CI/CD

---

## 🛠️ How to Use This Template

### Prerequisites
- A LaTeX distribution installed:
  - **Windows:** [MiKTeX](https://miktex.org/) or [TeX Live](https://tug.org/texlive/)
  - **macOS:** [MacTeX](https://www.tug.org/mactex/)
  - **Linux:** `sudo apt install texlive-full`
- Or use **[Overleaf](https://www.overleaf.com/)** (online, no install needed)

### Build Steps

```bash
# Clone this repository
git clone https://github.com/AryantKumar/70-ATS-Score-Resume.git
cd 70-ATS-Score-Resume

# Compile the LaTeX file to PDF
pdflatex resume.tex

# (Optional) If using BibTeX references
bibtex resume
pdflatex resume.tex
pdflatex resume.tex
```

### Using Overleaf
1. Go to [Overleaf](https://www.overleaf.com/)
2. Create a **New Project → Upload Project**
3. Upload `resume.tex`
4. Click **Recompile** to generate the PDF

---

## 📁 File Structure

```
resume/
├── README.md          # This file — documentation & ATS tips
└── resume.tex         # LaTeX resume template (main file)
```

---

## ✏️ Customization Guide

### Editing Your Information
Open `resume.tex` and edit the placeholder fields:

| Placeholder             | Replace With              |
|-------------------------|---------------------------|
| `Your Full Name`        | Your real name             |
| `your.email@example.com`| Your email address         |
| `+1-234-567-8900`       | Your phone number          |
| `City, State`           | Your location              |
| `linkedin.com/in/yourname` | Your LinkedIn URL       |
| `github.com/yourname`      | Your GitHub URL            |

### Tailoring for Each Job
1. **Read the job description** carefully.
2. **Identify 10–15 keywords** (skills, tools, qualifications).
3. **Incorporate those keywords** naturally into your Summary, Experience, and Skills sections.
4. **Reorder your bullet points** so the most relevant ones appear first.

---

## 📊 ATS Score Testing

Test your resume using these free tools:

| Tool | URL | Notes |
|------|-----|-------|
| **Jobscan** | [jobscan.co](https://www.jobscan.co/) | Compare resume vs. job description |
| **Resume Worded** | [resumeworded.com](https://resumeworded.com/) | AI-driven score & suggestions |
| **SkillSyncer** | [skillsyncer.com](https://www.skillsyncer.com/) | Keyword matching analysis |

---

## 📝 Tips for Maximum Impact

- **Keep it to 1 page** (for less than 10 years of experience).
- **Use action verbs** to start each bullet: *Developed, Implemented, Designed, Led, Optimized, Reduced, Increased, Automated*.
- **Quantify everything**: Numbers, percentages, dollar amounts, and time saved.
- **Save as PDF** to preserve formatting across all platforms.
- **File name convention**: `FirstName_LastName_Resume.pdf`

---

## 📄 License

This template is free to use and modify for personal and professional purposes. Attribution is appreciated but not required.

---

## 👨‍💻 Author

Created by **[Aryant Kumar](https://github.com/AryantKumar)** — feel free to connect!

---

> **⭐ Star this repo if you found it helpful! Good luck with your job search!**
