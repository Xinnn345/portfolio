
---
title: Home
---

.hero-section {
  background: linear-gradient(135deg, #142B45, #267C78);
  color: white;
  padding: 55px 40px;
  border-radius: 18px;
  margin: 20px 0 35px;
}

.hero-section h1,
.hero-section h2,
.hero-section p {
  color: white;
}

.hero-section h1 {
  font-size: 42px;
  margin: 15px 0 5px;
}

.hero-section h2 {
  font-size: 23px;
  font-weight: normal;
  margin: 0 0 20px;
}

.hero-eyebrow {
  letter-spacing: 2px;
  font-size: 12px;
  font-weight: bold;
  color: #D9ECE8 !important;
}

.hero-buttons,
.contact-buttons {
  display: flex;
  flex-wrap: wrap;
  gap: 12px;
  margin-top: 25px;
}

.primary-button,
.secondary-button,
.contact-button {
  display: inline-block;
  padding: 11px 20px;
  border-radius: 8px;
  font-weight: bold;
  text-decoration: none !important;
}

.primary-button {
  background: white;
  color: var(--navy) !important;
}

.secondary-button {
  border: 1px solid white;
  color: white !important;
}

.primary-button:hover,
.secondary-button:hover,
.contact-button:hover {
  opacity: 0.82;
}

.highlight-grid {
  display: grid;
  grid-template-columns: repeat(4, minmax(0, 1fr));
  gap: 15px;
  margin: 20px 0 35px;
}

.highlight-card {
  background: var(--light-bg);
  border: 1px solid #E1E8ED;
  border-radius: 12px;
  padding: 20px 12px;
  text-align: center;
}

.highlight-card h2 {
  color: var(--teal);
  font-size: 23px;
  margin: 0 0 8px;
}

.highlight-card p {
  color: var(--muted);
  margin: 0;
  font-size: 14px;
}

.skill-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 16px;
  margin: 20px 0;
}

.skill-card {
  background: var(--white);
  border: 1px solid #E1E8ED;
  border-left: 4px solid var(--teal);
  border-radius: 10px;
  padding: 20px;
}

.skill-card h3 {
  margin-top: 0;
  font-size: 18px;
}

.skill-card p {
  margin-bottom: 0;
}

.project-grid {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 16px;
  margin: 20px 0;
}

.project-card {
  background: var(--light-bg);
  border: 1px solid #E1E8ED;
  border-radius: 12px;
  padding: 20px;
}

.project-card h3 {
  margin-top: 0;
  font-size: 18px;
}

.project-card a {
  font-weight: bold;
}

.contact-button {
  background: var(--navy);
  color: white !important;
}

.footer-message {
  text-align: center;
  color: var(--teal);
  font-style: italic;
  font-weight: bold;
  margin-top: 40px;
  padding: 20px;
  background: var(--light-bg);
  border-radius: 10px;
}

@media (max-width: 700px) {
  .hero-section {
    padding: 35px 22px;
  }

  .hero-section h1 {
    font-size: 32px;
  }

  .highlight-grid {
    grid-template-columns: repeat(2, minmax(0, 1fr));
  }

  .skill-grid,
  .project-grid {
    grid-template-columns: 1fr;
  }
}

<div class="hero-section" markdown="1">

<p class="hero-eyebrow">DATA ANALYTICS · BUSINESS INTELLIGENCE
</p>

# Hello, I'm Lily!

## Aspiring Data Analyst

I transform raw data into meaningful insights through data analysis, visualization and business-oriented problem-solving.

Currently pursuing a **Bachelor of Applied Science in Data Analytics with Honours at Universiti Malaysia Pahang Al-Sultan Abdullah (UMPSA)**.

I enjoy exploring datasets, identifying patterns and communicating analytical findings that support better decision-making.

<div class="hero-buttons">

<a href="projects.md" class="primary-button">Explore My Projects →</a>

<a href="experience.md" class="secondary-button">View My Experience</a>

</div>

</div>

---

## Professional Highlights

<div class="highlight-grid">

<div class="highlight-card">
<h2>3.97 / 4.00</h2>
<p>Current CGPA</p>
</div>

<div class="highlight-card">
<h2>2027</h2>
<p>Expected Graduation</p>
</div>

<div class="highlight-card">
<h2>SQL · Python</h2>
<p>Data & Programming</p>
</div>

<div class="highlight-card">
<h2>Power BI</h2>
<p>Business Intelligence</p>
</div>

</div>

---

## About Me

I am an undergraduate Data Analytics student with an interest in transforming data into practical insights.

Through academic projects and industrial training, I have developed experience in data processing, statistical analysis, database management, data visualization and research support.

I enjoy working with data from different domains, understanding real-world problems and exploring how analytical techniques can help organisations make informed decisions.

My interests extend beyond traditional data analysis to business intelligence, machine learning and the application of technology in solving practical challenges.

---

## What I Bring

<div class="skill-grid">

<div class="skill-card">
<h3>📊 Data Analytics</h3>
<p>Data cleaning, exploratory data analysis (EDA), statistical analysis and identifying meaningful patterns.</p>
</div>

<div class="skill-card">
<h3>📈 Business Intelligence</h3>
<p>Developing reports, visualisations and dashboards using Excel and Power BI to communicate analytical findings.</p>
</div>

<div class="skill-card">
<h3>💻 Programming & Data Science</h3>
<p>Using Python and R for data processing, analytical projects and introductory machine learning applications.</p>
</div>

<div class="skill-card">
<h3>🗄️ Database & SQL</h3>
<p>Working with relational databases, SQL queries, data organisation and structured data management.</p>
</div>

</div>

[Explore My Technical Skills →](skills.md)

---

## Featured Projects

I apply my technical knowledge through academic and personal projects involving data analysis, business intelligence and technology.

<div class="project-grid">

<div class="project-card">

<h3>Bakery Sales Analysis</h3>

<p>Analysing sales performance, customer behaviour, product trends and promotional effectiveness for a fictional home-based bakery business.</p>

<p><strong>Tools:</strong> PostgreSQL · SQL</p>

<a href="projects.md">Explore Projects →</a>

</div>

<div class="project-card">

<h3>Healthcare Data Warehouse</h3>

<p>Designing a healthcare data warehouse and applying SQL-based analytical techniques to explore structured healthcare information.</p>

<p><strong>Tools:</strong> SQL · PostgreSQL · Power BI</p>

<a href="projects.md">Explore Projects →</a>

</div>

<div class="project-card">

<h3>Customer Complaint Risk Detection</h3>

<p>Applying machine learning and natural language processing to identify customer complaints requiring further attention.</p>

<p><strong>Tools:</strong> Python · Machine Learning · NLP</p>

<a href="projects.md">Explore Projects →</a>

</div>

</div>

[View All Projects →](projects.md)

---

## Experience & Academic Journey

### Research & Data Support Intern

**Cardas Research & Consulting Group | 2026**

Gained practical exposure to market research through consumer research, industry research and mystery shopping activities.

Key areas of involvement:

- Research data collection and organisation.
- Excel-based data processing and reporting.
- Data verification and consistency checking.
- Industry information research and report preparation.

[Explore My Industrial Training →](experience/crcg.md)

### International Academic Experience

**Chinese Government Scholarship International Summer School**

Hebei University, China | 2025

Participated in an international academic and cultural exchange programme, gaining exposure to Big Data, Artificial Intelligence, Digital Finance, Data Analytics, E-commerce and Digitalisation.

[Explore My International Experience →](experience/hebei-summer-school.md)

---

## Education & Achievements

**Bachelor of Applied Science in Data Analytics with Honours**

Universiti Malaysia Pahang Al-Sultan Abdullah (UMPSA)

October 2023 – April 2027 (Expected)

**Academic Achievements**

- CGPA: 3.97 / 4.00
- Dean's List: 2023/2024 and 2024/2025
- Chinese Government Scholarship International Summer School, Hebei University (2025)
- Participant, ISM Challenge III 2024

---

## Let's Connect

I am always open to connecting with professionals, exploring opportunities and learning from people working in data analytics, business intelligence and technology.

If you are interested in my projects or would like to discuss potential opportunities, feel free to reach out.

<div class="contact-buttons">

<a href="https://github.com/Xinnn345" class="contact-button">GitHub ↗</a>

<a href="https://www.linkedin.com/in/lim-deng-xin/" class="contact-button">LinkedIn ↗</a>

<a href="mailto:dengquan422@gmail.com" class="contact-button">Email ↗</a>

</div>

<p class="footer-message">Turning data into insights, one project at a time.</p>

<div class="hero-section" markdown="1">

<p class="hero-eyebrow">DATA ANALYTICS · BUSINESS INTELLIGENCE
</p>

# Hello, I'm Lily!

## Aspiring Data Analyst

I transform raw data into meaningful insights through data analysis, visualization and business-oriented problem-solving.

Currently pursuing a **Bachelor of Applied Science in Data Analytics with Honours at Universiti Malaysia Pahang Al-Sultan Abdullah (UMPSA)**.

I enjoy exploring datasets, identifying patterns and communicating analytical findings that support better decision-making.

<div class="hero-buttons">

<a href="projects.md" class="primary-button">Explore My Projects →</a>

<a href="experience.md" class="secondary-button">View My Experience</a>

</div>

</div>

---

## Professional Highlights

<div class="highlight-grid">

<div class="highlight-card">
<h2>3.97 / 4.00</h2>
<p>Current CGPA</p>
</div>

<div class="highlight-card">
<h2>2027</h2>
<p>Expected Graduation</p>
</div>

<div class="highlight-card">
<h2>SQL · Python</h2>
<p>Data & Programming</p>
</div>

<div class="highlight-card">
<h2>Power BI</h2>
<p>Business Intelligence</p>
</div>

</div>

---

## About Me

I am an undergraduate Data Analytics student with an interest in transforming data into practical insights.

Through academic projects and industrial training, I have developed experience in data processing, statistical analysis, database management, data visualization and research support.

I enjoy working with data from different domains, understanding real-world problems and exploring how analytical techniques can help organisations make informed decisions.

My interests extend beyond traditional data analysis to business intelligence, machine learning and the application of technology in solving practical challenges.

---

## What I Bring

<div class="skill-grid">

<div class="skill-card">
<h3>📊 Data Analytics</h3>
<p>Data cleaning, exploratory data analysis (EDA), statistical analysis and identifying meaningful patterns.</p>
</div>

<div class="skill-card">
<h3>📈 Business Intelligence</h3>
<p>Developing reports, visualisations and dashboards using Excel and Power BI to communicate analytical findings.</p>
</div>

<div class="skill-card">
<h3>💻 Programming & Data Science</h3>
<p>Using Python and R for data processing, analytical projects and introductory machine learning applications.</p>
</div>

<div class="skill-card">
<h3>🗄️ Database & SQL</h3>
<p>Working with relational databases, SQL queries, data organisation and structured data management.</p>
</div>

</div>

[Explore My Technical Skills →](skills.md)

---

## Featured Projects

I apply my technical knowledge through academic and personal projects involving data analysis, business intelligence and technology.

<div class="project-grid">

<div class="project-card">

<h3>Bakery Sales Analysis</h3>

<p>Analysing sales performance, customer behaviour, product trends and promotional effectiveness for a fictional home-based bakery business.</p>

<p><strong>Tools:</strong> PostgreSQL · SQL</p>

<a href="projects.md">Explore Projects →</a>

</div>

<div class="project-card">

<h3>Healthcare Data Warehouse</h3>

<p>Designing a healthcare data warehouse and applying SQL-based analytical techniques to explore structured healthcare information.</p>

<p><strong>Tools:</strong> SQL · PostgreSQL · Power BI</p>

<a href="projects.md">Explore Projects →</a>

</div>

<div class="project-card">

<h3>Customer Complaint Risk Detection</h3>

<p>Applying machine learning and natural language processing to identify customer complaints requiring further attention.</p>

<p><strong>Tools:</strong> Python · Machine Learning · NLP</p>

<a href="projects.md">Explore Projects →</a>

</div>

</div>

[View All Projects →](projects.md)

---

## Experience & Academic Journey

### Research & Data Support Intern

**Cardas Research & Consulting Group | 2026**

Gained practical exposure to market research through consumer research, industry research and mystery shopping activities.

Key areas of involvement:

- Research data collection and organisation.
- Excel-based data processing and reporting.
- Data verification and consistency checking.
- Industry information research and report preparation.

[Explore My Industrial Training →](experience/crcg.md)

### International Academic Experience

**Chinese Government Scholarship International Summer School**

Hebei University, China | 2025

Participated in an international academic and cultural exchange programme, gaining exposure to Big Data, Artificial Intelligence, Digital Finance, Data Analytics, E-commerce and Digitalisation.

[Explore My International Experience →](experience/hebei-summer-school.md)

---

## Education & Achievements

**Bachelor of Applied Science in Data Analytics with Honours**

Universiti Malaysia Pahang Al-Sultan Abdullah (UMPSA)

October 2023 – April 2027 (Expected)

**Academic Achievements**

- CGPA: 3.97 / 4.00
- Dean's List: 2023/2024 and 2024/2025
- Chinese Government Scholarship International Summer School, Hebei University (2025)
- Participant, ISM Challenge III 2024

---

## Let's Connect

I am always open to connecting with professionals, exploring opportunities and learning from people working in data analytics, business intelligence and technology.

If you are interested in my projects or would like to discuss potential opportunities, feel free to reach out.

<div class="contact-buttons">

<a href="https://github.com/Xinnn345" class="contact-button">GitHub ↗</a>

<a href="https://www.linkedin.com/in/lim-deng-xin/" class="contact-button">LinkedIn ↗</a>

<a href="mailto:dengquan422@gmail.com" class="contact-button">Email ↗</a>

</div>

<p class="footer-message">Turning data into insights, one project at a time.</p>
