EduBot — College Enquiry AI Chatbot
A modern, elegant AI-powered college enquiry chatbot built with pure HTML, CSS, and JavaScript. Zero dependencies, zero backend required. Drop it into any college website instantly.

✨ Features

50 pre-loaded Q&A pairs covering all major college enquiry topics
Smart keyword matching — finds the best answer even with partial or casual questions
Typing animation — realistic bot response simulation
Quick suggestion pills — one-click common questions
Auto-resize input — textarea grows with your message
Fully responsive — works on mobile, tablet, and desktop
Dark premium UI — elegant deep-navy theme with subtle animations
Zero dependencies — no React, no Node.js, no backend, no API key needed
Instant deploy — single HTML file, works offline


📋 Topics Covered (50 Questions)
CategoryQuestions🎓 AdmissionsProcess, eligibility, documents, dates, management quota💰 FeesB.Tech fees, hostel fees, installments, MBA fees, refund policy📚 CoursesAll programs, B.Tech specializations, lateral entry, BCA, online courses📝 ExamsPattern, attendance, grading, schedule, re-evaluation🏠 Hostel & CampusHostel, facilities, Wi-Fi, sports, library timings💼 PlacementStatistics, companies, preparation, internships🚌 TransportBus routes, timings, pass fees🎉 Student LifeClubs, fests, events, dress code👨‍🏫 FacultyQualifications, PhD ratio, student-faculty ratio🏆 AccreditationNAAC, NBA, AICTE, university affiliation🏥 ServicesMedical, counselling, anti-ragging, student portal💳 Financial AidEducation loans, government scholarships🌍 InternationalForeign student admissions🚀 StartupIncubation center, E-Cell

🚀 How to Use
Option 1 — Standalone
Just open college-chatbot.html in any browser. Done!
Option 2 — Embed in your website
html<iframe src="college-chatbot.html" width="100%" height="700px" frameborder="0"></iframe>

🛠️ Customization
Update College Name
Find in HTML: <h1>EduBot</h1> and <p>COLLEGE ENQUIRY ASSISTANT</p>
Update Fees / Answers
All answers are in the KB array in the script section. Find the question and edit the a: field.
Add New Questions
javascript{
  q: "Your new question?",
  a: "Your answer with <strong>bold</strong> and <ul><li>lists</li></ul>",
  tags: ["keyword1", "keyword2"]
},
Change Colors
css:root{
  --accent:  #5b8df6;  /* Change to your college color */
  --bg:      #0c0e14;  /* Background color */
}

📁 Files
college-chatbot.html   ← Everything in one file
README.md              ← This file

🔮 Future Upgrades

Connect to Claude API / OpenAI for truly intelligent answers
Add voice input via Web Speech API
Build admin panel to update Q&A without touching code
Add Hindi / regional language support


Free to use for educational institutions. No backend, no cost.
