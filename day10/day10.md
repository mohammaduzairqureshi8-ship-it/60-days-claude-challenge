#prompt:

You are an expert full-stack web developer and personal branding designer.
Build a complete, modern, single-file personal portfolio website using HTML, Tailwind CSS (CDN), and vanilla JavaScript for this person:
=== PERSONAL INFO ===
Name: [Your Name]
Title: [e.g., 'Data Science Enthusiast | GenAI Builder']
Location: [City, Country]
Email: [email]
LinkedIn: [URL]
GitHub: [URL]
About: [2-3 sentences about yourself]
=== SKILLS ===
Technical: [Python, ML, SQL, etc.]
Tools: [VS Code, Jupyter, Power BI, etc.]
Soft Skills: [Leadership, Communication, etc.]
=== PROJECTS ===

1. [Project Name] — [1 line description] — Tech: [stack]
2. [Project Name] — [1 line description] — Tech: [stack]
3. [Project Name] — [1 line description] — Tech: [stack]
   === EXPERIENCE & ACHIEVEMENTS ===

- [Internship / Hackathon / Certification]
- [Award / Rank / Notable achievement]
  === DESIGN PREFERENCES ===
  Mode: Dark/Light toggle
  Style: Modern, minimal, premium
  Colors: [e.g., Purple + Teal, or Blue + Orange]
  Font: Clean sans-serif display font
  === REQUIREMENTS ===
  Include these sections:
- Hero (name, title, typing animation, social links)
- About Me
- Skills (animated bars + tech tags)
- Projects (cards with tech tags)
- Achievements & Certifications
- Contact (form + direct links)
- Dark/Light mode toggle
- Mobile responsive
- Smooth scroll animations
- Active nav highlighting
- Single HTML file, no build step
- Tailwind via CDN
- SEO meta tags included
  Optional:
- If a resume is uploaded, extract details automatically.
- If a profile photo is uploaded, use it in the portfolio.
- Generate recruiter-friendly content and project descriptions from resume data.
  Return only the complete HTML code.

output:

Viewed a file, created a file, read a file · 1 note
Viewed a file, created a file, read a file · 1 note
Here's your complete portfolio — pulled entirely from your resume. Everything is in a single HTML file. Here's what's packed in:

Sections built: Hero with typing animation (cycles through 5 titles), About with stat grid, Skills with animated bars + color-coded tag groups, Projects (all 3 — AI Interview Agent, OCI App, NutriScope), Achievements timeline, and a Contact section with mock form + direct links.

Design decisions made for you:

Dark default with teal (
#14b8a6) + indigo accent — avoids the generic cream/terracotta or neon-green defaults
Syne display font (bold, distinctive) paired with DM Mono for labels/eyebrows and Inter for body
Grid dot texture on the hero, ambient glow orbs, no over-animation
Skill bars fill on scroll-into-view — the single animated moment, kept deliberate
Recruiter-friendly touches:

Open-to-internship status badge (green pulse dot)
Each project card has a proper value-prop description beyond what's in the resume
NutriScope is called out as front-end-only with zero dependencies — that's a flex
"abtalks" is woven in naturally across hero, about, and achievements
To make it yours:

Replace the GitHub link (currently https://github.com) with your actual profile
Optionally swap the email in the <a> tag to a mailto link with a subject line
Add your photo — drop an <img> tag in the about section's stat grid column

Uzair portfolio

- [📄 HTML File Open Karne Ke Liye Yahan Click Karein](./portfolio.html)
