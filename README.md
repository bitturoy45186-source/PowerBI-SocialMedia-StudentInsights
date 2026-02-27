# PowerBI-SocialMedia-StudentInsights
This Power BI project analyzes how student social media usage impacts sleep patterns, academic performance, mental health, and relationship dynamics. The dashboard was designed to provide actionable insights for multiple stakeholders, including academic advisors, mental health counselors, institutional researchers, and students themselves.


The goal is to provide actionable insights for multiple stakeholders:
- Academic Advisors → monitor academic performance vs. social media usage
- Mental Health Counselors → track sleep, mental health, and addiction scores
- Institutional Researchers → analyze country‑ and gender‑level trends
- Students & Counselors → drill into individual student profiles

🔧 Technical Highlights

- Data Modeling:
   . Loaded Excel sheets (Student Details & Platform Details)
   . Established 1:1 relationship on Student_ID in a star schema
   . Added a custom Date Table for time intelligence


- Data Preparation:
   . Created calculated columns (e.g., Health Band, Conflict Level)
   . Built measures for averages, percentages, and counts (e.g., Avg Sleep Hours, % Affected Academically)


- Time Intelligence:
   . Simulated monthly trends using CALENDAR() and DATESYTD()


- Report Pages:
   . Executive Overview: KPIs, addiction scores, usage trends, gender distribution
   . Mental Health & Lifestyle: country vs. health band, scatter plots, sleep vs. age
   . Academic Impact: usage vs. academic level, platform impact
   . Relationships & Conflicts: conflict levels, relationship status distribution
   . Interactive Story View: bookmarks for gender vs. academic level perspectives
   . Drill‑Through Student Profile: individual demographics, sleep, usage, conflicts, mental health

- Interactivity:
   . Slicers for gender, country, academic level, and age range
   . Bookmarks for storytelling views
   . Drill‑through for personalized student insights


 📈 Key Insights
   . Students with >5 hours daily social media usage sleep ~2 hours less on average.
   . Addiction scores above 7 strongly correlate with academic performance impact.
   . Conflicts over social media are most common among students in relationships.
   . Gender differences are subtle: females average slightly higher daily usage than males.



