# FUTURE_PE_02
README – AI Job Preparation Website (Task 2 Project)

Created by: Siya Poipkar
Platform: Wix Studio + Wix AI + Tidio + Zapier
Project Type: AI-Powered No-Code Website

📌 Overview

The AI Job Preparation Website is a fully functional no-code project built using Wix Studio, enhanced with Wix AI, Tidio Chatbot, and Zapier automations.
The website helps users prepare for internships and jobs by offering:

AI-powered Resume Rewriting

Intelligent Mock Interview Chatbot

Personalized Skill Gap Analyzer

Automatic Cover Letter Generator

Automated form handling & notifications via Zapier

Clean, modern UI created with Wix Studio

This project demonstrates the ability to integrate multiple AI tools, build user-friendly flows, automate backend tasks, and ship a complete working solution.

🎯 Project Goals

Build a modern website without coding (using Wix Studio).

Integrate multiple AI features that help job seekers.

Create an automated workflow using Zapier + Sheets/Email.

Deliver a live, testable site for evaluation.

Provide documentation for future interns or reviewers.

✨ Features
1. AI Resume Builder

Users upload/resume or paste text.

AI rewrites bullets using Wix AI (or OpenAI backend).

Output includes:

Rewritten bullet points

Skill keywords

Resume score

PDF download option

Prompt used:

Rewrite the following resume bullet points to be achievement-focused and keyword-optimized for the role 'Junior Frontend Developer'. Keep bullets short (8–14 words), use metrics where possible.

2. Mock Interview Chatbot (Tidio)

Interactive chatbot simulating real interview questions.

Evaluates answers using a backend AI prompt.

Returns:

Score (1–5)

2 improvement tips

A polished sample answer

Prompt used:

You are an interview evaluator. Score the answer 1–5, give two improvement tips, and rewrite a polished version (≤30 words). 
Answer: {USER_ANSWER}. Question: {QUESTION}.

3. Skill Gap Analyzer

Users choose their skills + target job role.

AI generates:

Personalized 8-week learning roadmap

6 modules

Resources & 2 practice projects

Prompt used:

User has skills: {SKILLS}. Target role: {ROLE}. 
Give an 8-week roadmap with modules, resources, and practice projects.

4. AI Cover Letter Generator

Creates a structured 300-word cover letter based on:

Resume text

Job title

Company

Prompt used:

Write a tailored 300-word cover letter for {JOB} at {COMPANY} using this resume: {RESUME}.

5. Automations (Zapier)

Zap 1 — Form Submission → Google Sheets
Stores user details & resume data.

Zap 2 — Form Submission → Slack/Email
Sends notification to admin.

Zap 3 — Resume Results → Email to User
Emails rewritten resume + improvements.

6. PDF Download Integration

Implemented using jsPDF in Wix Velo.

Converts AI results into a downloadable PDF.

import {jsPDF} from 'jspdf';
const doc = new jsPDF();
doc.text(resultText, 10, 10);
doc.save("resume-improved.pdf");

🧩 Tech Stack
Feature	Tool Used
Website Builder	Wix Studio
Copy/Content AI	Wix AI
Chatbot	Tidio
Automations	Zapier
Resume/Interview AI	Wix AI or OpenAI (optional)
Data Storage	Google Sheets
PDF Export	jsPDF (Wix Velo)
UI Design	Wix Studio
📂 Pages in the Website

Home

Resume Builder

Mock Interview

Skill Gap Analyzer

Cover Letter Generator

Resources

About

Contact

Results

📸 Screenshots Included

(Add these in your submission)

Home page

Resume Builder output

Mock Interview chatbot

Skill Gap Analyzer roadmap

Zapier workflow screenshots

Google Sheets record

📝 Testing Summary
Test	Status
Resume upload & rewrite	✔️ Working
Mock interview evaluation	✔️ Working
Roadmap generation	✔️ Working
Cover letter generation	✔️ Working
PDF download	✔️ Working
Zapier automations	✔️ Working
Mobile responsiveness	✔️ Verified
🔗 Important Links

Live Website: Add your published link here

Loom Demo Video: Add video link

Google Sheet (logs): Link to your sheet

Tidio Chatbot: Dashboard link

📄 File Deliverables

Include these in your final submission:

README.pdf (this file)

Prompts.txt (all prompts used)

TestResults.pdf (screenshots)

SiteLink.txt

Zapier-Screenshots folder

DemoVideo.mp4 or LoomLink.txt

🙋 About the Creator

I am Siya Poipkar, skilled in:

AI tools & automation

Frontend development (HTML, CSS, JS)

Creating modern, responsive websites

Basic editing & Canva design

This project reflects my ability to build AI-powered solutions using no-code tools efficiently.
