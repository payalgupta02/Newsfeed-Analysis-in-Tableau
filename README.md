## Newsfeed Analysis in Tableau

### Project Overview
This project analyzes user engagement with the Newsfeed feature of a learning platform. The Newsfeed acts as a social community where learners share milestones (certificates, levels, goals, streaks) or post manually. Engagement occurs via likes and comments. The analysis covers activity from **January to May 2023** to understand posting behavior, post-type performance, and overall engagement trends.

### Business Problem & Objective
The Newsfeed was designed to boost learner engagement and community interaction. Despite high posting activity, it was unclear which post types truly encourage participation or drive meaningful interaction.  

**Objectives:**  
- Examine posting and engagement patterns across post subtypes.  
- Identify which post types resonate most with learners.  
- Measure overall user participation levels.  
- Recommend strategies to improve engagement quality and content balance.

### Dataset & Tools
**Dataset:** Newsfeed activity logs including Posts, Likes, Comments, and User Activity  
**Period Covered:** Jan–May 2023  
**Key Fields:** Post Date, Post Subtype, Number of Posts, Number of Likes, Number of Comments, User Visits, User Engagement

**Tableau dashboard/story URL:** https://public.tableau.com/views/NEWSFEEDFEATUREANALYSISOF365DataScience/Dashboard1?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

**Tools Used:**  
- **Excel:** Data exploration, validation, and initial profiling  
- **Tableau Public:** Data visualization, calculated fields, and dashboard creation  

### Methodology
1. **Data Access & Setup**  
   - Imported the provided `.twbx` file into Tableau.  
   - Exported underlying data to Excel for exploration.  

2. **Exploration (Excel)**  
   - Verified record counts and checked for missing values.  
   - Explored distributions of posts, likes, comments, and activity metrics.  

3. **Visualization Development (Tableau)**  
   - Created KPIs and individual charts in separate sheets.  
   - Built calculated fields (e.g., Avg Likes per Post).  
   - Applied sorting, filters, and formatting for clarity.  

4. **Dashboard Consolidation**  
   - Combined all charts into a single Newsfeed Analysis Dashboard.  
   - Applied global filters (time period, post subtype).  
   - Added a Story extension to highlight post-conversion rates.
<img width="1223" height="718" alt="image" src="https://github.com/user-attachments/assets/8c41f91c-0a76-49ed-9e9d-c7e3a927f0f9" />

### Key Insights
1. **Posting Trends:**  
   - Post volumes are consistently high, mainly driven by automated updates (Levels and Course Certificates).  
   - Average likes per post remain very low, signaling a gap between quantity and meaningful interaction.  

2. **Post Conversion Analysis:**  
   - High volume, low conversion: Levels (22,313 posts, 2%) and Collections (9,376 posts, 2%)  
   - Low volume, high conversion: Text posts (150 posts, 164%), Career Track Certificates (144 posts, 49%), Goals (1,616 posts, 48%)  
   - Moderate performers: Course Certificates (14%) and Streaks (17%)  

3. **User Behavior:**  
   Learners engage most with posts that are:  
   - **Useful:** Text posts sharing insights  
   - **Aspirational:** Career Track Certificates  
   - **Personal:** Goals  

4. **Automated updates**, though abundant, generate little interaction.

### Recommendations
- **Reduce Feed Noise:** Limit visibility of automated updates (Levels, Collections).  
- **Promote High-Value Posts:** Encourage more Text posts and Career Track Certificate sharing.  
- **Engagement Nudges:** Add prompts like “Share what you learned today” to inspire meaningful content.  
- **Content Mix Balance:** Surface engaging posts more frequently to foster an interactive, knowledge-driven feed.

### Conclusion
While the Newsfeed is flooded with automated posts, real engagement comes from personal, aspirational, and knowledge-driven content. By focusing on high-conversion post types, the platform can create a richer community experience and enhance learner interaction.


