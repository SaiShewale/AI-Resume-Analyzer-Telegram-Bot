# AI Resume Analyzer Telegram Bot

An AI-powered Resume Analysis Bot built using **n8n**, **Telegram Bot API**, and **DeepSeek AI**. The bot analyzes resumes against a specified job role and provides detailed feedback, ATS scoring, skill gap analysis, and actionable improvement recommendations.

## 🚀 Features

- Resume upload through Telegram
- Automatic PDF text extraction
- Job-role-specific resume analysis
- ATS compatibility scoring
- Skill gap identification
- Keyword optimization suggestions
- Detailed section-wise feedback
- Conversation memory support
- AI-powered recommendations using DeepSeek

## 🛠️ Tech Stack

- n8n
- Telegram Bot API
- DeepSeek AI
- LangChain Agent
- PDF Parser

## 📋 Workflow

1. User uploads a resume PDF via Telegram.
2. The bot extracts text from the resume.
3. User provides the target job role.
4. DeepSeek AI analyzes the resume.
5. A detailed report is generated with ratings and recommendations.

## 📊 Analysis Sections

- Formatting & Structure
- Contact Information & Header
- Professional Summary
- Technical Skills
- Professional Experience
- Education & Certifications
- Projects & Additional Sections
- ATS Optimization & Keywords
- Soft Skills & Leadership
- Overall Recommendations

## 🎯 Use Cases

- Students preparing for placements
- Internship applications
- Resume reviews
- ATS readiness checks
- Career guidance

## ⚙️ Setup

### Clone Repository

```bash
git clone https://github.com/your-username/AI-Resume-Analyzer-Telegram-Bot.git
cd AI-Resume-Analyzer-Telegram-Bot
```

### Configure n8n

1. Import the workflow JSON into n8n.
2. Add Telegram Bot credentials.
3. Add DeepSeek API credentials.
4. Activate the workflow.

## 💬 Example

**User:** Uploads Resume.pdf

**Bot:**  
Thank you for sharing your resume. Which job title should I use for this analysis?

**User:** AI/ML Engineer

**Bot:**  
Generates a complete resume analysis report with ATS score, strengths, weaknesses, missing skills, and improvement suggestions.

## 🔮 Future Improvements

- DOCX support
- Resume-to-JD matching
- Cover letter generation
- Resume rewriting
- Recruiter dashboard
- Multi-language support

## 👨‍💻 Author

Sai Shewale

---

⭐ If you found this project useful, consider giving it a star.
