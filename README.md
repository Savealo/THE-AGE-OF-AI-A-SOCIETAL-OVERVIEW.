INTRODUCTION
Objective of the Project
This project set out to understand how Artificial Intelligence (AI) is reshaping people’s lives, jobs, and the industries they work in. It looks beyond the hype to explore how everyday workers, students, and professionals are actually experiencing AI in their studies and workplaces.
Through surveys and dashboards, the project focuses on some of the questions:
1.	Where is AI being used most? – Which industries and job types are adopting AI tools quickly, and which are falling behind?
2.	What is AI doing to jobs? – Is AI creating new opportunities, making work easier, or replacing tasks that people used to do?
3.	Are people ready for the future of work? – How confident are workers in using AI, and what role does training play in building that confidence?
4.	How does society feel about AI? – What are people’s biggest hopes and fears — from job security to data privacy to misinformation?
5.	Who is ready to adopt AI now? – Which groups (by industry, job level, or experience) feel most confident, and who still needs support?
At its core, the project’s goal is to provide insights that can guide organizations, schools, individuals and governments. By understanding where AI is helping, where it’s causing concern, and where the gaps are, the study offers practical recommendations to make sure AI becomes a tool for opportunity, growth, and fairness, rather than fear or exclusion.

Problem Being Addressed
Artificial Intelligence is already part of our daily lives — from chatbots to online learning tools — but people don’t always know whether it’s here to help them or replace them. Workers are asking: “Will AI take my job, or will it make my job easier?” Students wonder if AI will give them an edge, or if it will make their skills irrelevant before they even graduate.
The challenge is that AI isn’t spreading evenly. While tech companies are racing ahead, other industries like healthcare, education, and government are slower to adapt. This creates a gap between those who are ready for the future of work and those who risk being left behind.
On top of that, most people using AI today have had to teach themselves. They don’t always have access to proper training, which means their confidence is low and their understanding is patchy. Without structured learning, the benefits of AI could stay in the hands of a few, instead of reaching everyone.
And beyond skills, there are deeper societal worries: job losses, bias in algorithms, fake content, and even the question of who should control AI. These fears show that AI isn’t just a tool — it’s also a source of anxiety about the future.
In short, the problem is simple but urgent: AI is moving faster than people’s ability to adapt. If we don’t close the gaps in skills, confidence, and trust, society risks turning AI into a divider rather than a unifier.

Key Datasets
The backbone of this project is the AI and Workforce Impact Survey, which collected 323 responses from individuals across different industries, job levels, and backgrounds. The cleaned dataset forms the basis of all analysis, charts and dashboards.

STORY OF DATA

Data Source: The data was obtained from survey questions
Data Collection Process: The data was collected through a structured online survey. The survey was designed to capture people’s real experiences with AI.
Data Structure: This dataset contains 323 responses across 30 survey questions/variables, covering demographics, AI usage, job impact, training, confidence, and societal perceptions.
 
Important Features and Their Significance: 
1.	Timestamp - When the person filled out the survey; helps track response patterns.
2.	Current Status - Whether they’re employed, unemployed, freelancing, or studying; tells us who AI is affecting right now.
3.	Occupation/Job Title - The kind of work they do; shows which roles are feeling AI’s impact the most.
4.	Industry - The sector they belong to (tech, healthcare, business, etc.); reveals where AI adoption is strongest or weakest.
5.	Years of Work Experience - How long they’ve been in the workforce; helps spot generational or experience-based differences in AI use.
6.	AI Use in Workplace/Study - A simple “yes or no” on whether AI is part of their environment; shows how widespread AI really is.
7.	AI Tools Used -Names the tools (e.g., ChatGPT, Grammarly); tells us which tools are most trusted and popular.
8.	Frequency of AI Use - Daily, weekly, occasionally, or never; measures how central AI has become in people’s routines.
9.	Impact of AI on Job/Study - Whether AI caused major, minor, or no changes; shows how disruptive AI feels in daily tasks.
10.	Ways AI Has Impacted Role/Field - From automation to skill-building; reveals what’s changing in work and study habits.
11.	Skills Sufficient for AI Use - Whether people feel their current skills are enough; signals gaps in readiness.
12.	Key Skills for AI Future - What skills they think will matter most; gives a roadmap for future training priorities.
13.	Perception of AI in Industry- How people view AI in their sector (positive, negative, neutral); reflects industry-specific attitudes.
14.	Perception Category - Groups perceptions into categories; simplifies comparison across industries.
15.	AI Job Creation vs Replacement – Whether AI is seen as a job creator or job killer; highlights the core employment debate.
16.	Interest in AI Training - If they want training; shows how eager people are to learn.
17.	Comments on AI’s Impact – Open-ended thoughts; provides personal stories and feelings beyond numbers.
18.	Primary Purpose of AI Tools – Why they use AI (learning, productivity, creativity, etc.); shows the human motivation behind adoption.
19.	Confidence in Using AI Tools (1–5) – A score of their confidence; measures how comfortable people feel with AI.
20.	Confidence in Using AI Tools (Category) – Groups confidence as low, moderate, or high; easier for bigger-picture analysis.
21.	First Experience with AI Tool – How they felt at first (positive, negative, neutral); captures the “first impression effect”.
22.	Job Roles Reduced Due to AI – Whether they’ve seen roles cut; tells us if AI fears are becoming reality.
23.	New Roles Introduced by AI – Whether they’ve seen new jobs appear; tracks AI-driven opportunities.
24.	Examples of New Roles – Specific job names people mentioned; adds real-world evidence of change.
25.	Formal AI Training Received – Whether they had structured training; shows how people are learning — formally or self-taught.
26.	Reasons for Yes/No – Why they trained or didn’t; helps uncover barriers like cost, time, or access.
27.	Preferred Training Format – Online, in-person, mentorship, etc.; reveals how people want to learn AI.
28.	Biggest Concern About AI – Job loss, privacy, misinformation, etc.; reflects what worries people most about AI in society.
29.	Organisations Managing AI Risks – Do people feel companies are handling risks well? Shows trust levels in institutions.
30.	Who Should Regulate AI – Whether government, tech companies, or both; tells us who people trust to set the rules.

Data Limitations or Biases
1.	Small Sample & Representation – 323 responses give insights but may not fully represent all industries or workers.
2.	Online Bias – Since it was an online survey, responses mostly came from digitally active people, leaving out those with limited internet access.
3.	Self-Reporting – Answers reflect people’s feelings and perceptions, which may not always match reality.
4.	Geographic Scope – The data reflects mostly local/regional experiences, so findings may not apply globally.
5.	Snapshot in Time – The survey captures one moment; AI adoption is evolving quickly, so views may change.
DATA SPLITTING AND PREPROCESSING
Tool used: excel 
Before analyzing the survey responses, the dataset went through a careful cleaning process to make sure the information was accurate, consistent, and ready for visualization.
Steps Taken:
1.	Removing Duplicates
I Checked for repeated entries where respondents may have submitted the survey more than once.
No duplicates was found. 
2.	Standardizing Column Names
The original survey had long and inconsistent question titles (e.g., “What is your current occupation or job title?”).
These were shortened and standardized (e.g., “Occupation/Job Title”) to make the dataset easier to work with.
3.	Handling Missing Values
Some respondents skipped questions or wrote “N/A”.
These were either cleaned into a uniform label (e.g., “Not Applicable”, “None”) or left blank where appropriate.
4.	Categorizing Responses
Free-text responses like “civil servant”, “Civil Service”, or “govt worker” were standardized into one category (e.g., “Civil Servant”).
Years of experience were grouped into clear ranges (0–1 year, 2–5 years, 6–10 years, 10+ years) and further categorized into levels depending on years of experience using Power BI grouping feature. 
Confidence levels were recoded into Low, Moderate, High for easier comparison.
5.	Splitting Multi-Choice Answers
Some questions allowed multiple answers (e.g., AI Tools Used).
These were separated with commas and standardized so tools like “chat gpt”, “ChatGPT”  will be recognized as “ChatGPT”.
6.	Consistency in Categorical Data
Yes/No answers were cleaned into consistent values (e.g., “Y”, “Yes”, “YES”  “Yes”).
Training types (e.g., “Mentorship”, “Mentorship or coaching”) were harmonized.
7.	Adding New Analytical Columns
Categories like “Confidence in AI (1–5)” were recoded into Confidence Category using excel formular for simpler analysis.
Perceptions of AI were grouped into categories (Positive, Negative, Neutral) using excel formular. 

DATA SPLITING AND ANALYSIS
Tool used : Power BI

Dependent Variable
AI Use in Workplace/Study 
AI Tools Used
Frequency of AI Use
Impact of AI on Job/Study 
Ways AI Has Impacted Role 
Confidence in Using AI Tools 
Formal AI Training Received
Preferred Training Format
Job Roles Reduced Due to AI
New Roles Introduced by AI
Biggest Concern About AI
Perception of AI in Industry
Who Should Regulate AI


Independent Variables 
Current Status 
Occupation/Job Title
Industry 
Years of Work Experience
Demographic context 


STORY OF THE DATA

The data for this project comes from 323 people who shared their experiences with Artificial Intelligence (AI) through an online survey. These respondents included students, full-time employees, freelancers, and even those currently unemployed, giving us a mix of perspectives from different industries and career stages.
The survey asked questions that painted a full picture of how AI is affecting people’s lives. It captured who they are (their job status, industry, and years of experience), how they use AI (tools, frequency, and impact on work or study), and how they feel about it (their confidence, concerns, and hopes for the future)
Stakeholders of the Project
a.	Students and Job Seekers
b.	Employees (Junior, Mid, Senior Levels)
.
c.	Employers and Business Leaders
d.	Educators and Training Institutions
e.	Policymakers and Regulators
f.	Technology Companies
g.	Researchers and Analysts
h.	Society at Large
What Success means to the industry

1.	Widespread AI Adoption with Purpose – AI improves productivity, decision-making, and creativity.
2.	Jobs Transformed, Not Destroyed – automation creates new opportunities and roles.
3.	A Skilled and Confident Workforce – workers at all levels receive training and feel confident with AI tools.
4.	Trust and Ethical Use of AI – industries address bias, misinformation, and privacy concerns transparently.
5.	Collaboration Between Humans and AI – AI augments human work rather than replacing it.
6.	Fair and Inclusive Growth – AI benefits reach all industries and groups, not just a few sectors.

PRE-ANALYSIS
Potential Analysis Questions
1.	Which industries report the highest and lowest confidence in using AI tools?
2.	What factors (job title, years of experience, training) influence AI confidence?
3.	How often is AI used in workplaces vs study environments?
4.	What are the most common AI tools used across roles?
5.	What is the perceived impact of AI on jobs (positive vs negative)?
6.	Are organizations creating new roles at the same rate that old roles are being reduced?
7.	What training formats are most preferred by different stakeholder groups?
8.	What are the top concerns about AI (job loss, ethics, bias, misuse)?

Potential Insights
1.	Identification of industries with strong AI adoption vs lagging sectors
2.	Confidence gaps between students, early-career professionals, and experienced workers
3.	Insights on AI tool popularity (e.g., ChatGPT vs chatbots vs image generators)
4.	Correlation between formal AI training and confidence in usage
5.	Mapping of job roles reduced vs new roles introduced  net impact of AI
6.	Recognition of skills in demand for the AI future (critical for workforce development)
7.	Stakeholder-specific recommendations (e.g., employers  invest in AI training, educators  update curriculum, regulators  set clear standards
IN-ANALYSIS

IN ANALYSIS OBSERVATIONS

AI Use Across Industries
1.	Out of 323 people, 209 (65%) said they use multiple AI tools, while only 7 (2%) reported never using AI.
2.	120 people (37%) use AI daily, while 139 (43%) use it occasionally. Weekly users were fewer, and complete non-users made up a small minority.
3.	By sector, Tech professionals are leading adopters, followed closely by students and even unemployed respondents, who are using AI as a way to stay relevant or learn new skills.
4.	In contrast, healthcare showed mixed results — it ranked as one of the top industries using AI, yet also had a notable group of respondents reporting “never used an AI tool.”
Impact of AI on Jobs
1.	225 respondents (70%) said they had not seen jobs reduced due to AI.
2.	However, 213 people (66%) reported that AI has already automated tasks they used to do manually.
3.	When it comes to new jobs, only 7 respondents clearly identified new roles created by AI.
4.	Most people described AI’s impact as task-level changes: automation, requiring new skills, or efficiency boosts.

AI Skills & Future of Work
1.	Out of 323, 178 respondents with formal training reported high confidence in AI.
2.	In total, 283 respondents said they were interested in receiving AI training, showing a strong appetite for learning.
3.	At the same time, 260 respondents admitted they had never received formal training — instead, most taught themselves.
4.	Confidence levels were strongest in tech-related roles (33.5%), while non-tech industries showed lower confidence.

Societal Perceptions & Risks

1.Top concerns:
i.	Job loss – mentioned by 38 respondents.
j.	Data privacy – raised by 30 respondents.
k.	Loss of creativity – 22 respondents.
l.	Misinformation and fake content – 22 respondents.
2.	By career stage, junior employees (149 respondents) were far more optimistic about AI, while only 28 senior staff expressed enthusiasm.
3.	On regulation, the split was clear:
a.	128 respondents (39.6%) said government should regulate AI.
b.	120 (37%) said it should be a shared responsibility.
c.	75 (23%) placed the responsibility mainly on tech companies.

5.	Confidence & Readiness to Adopt AI
4.	Out of all respondents, confidence broke down as:
a.	178 (55%) – High confidence
b.	108 (33%) – Moderate confidence
c.	37 (12%) – Low confidence
5.	Confidence was highest among daily users of AI, showing a direct link between practice and confidence.
6.	By industry, healthcare workers reported the highest confidence levels, despite mixed adoption figures earlier.
7.	By career level, junior employees were the most ready to adopt AI, while mid- and senior-level workers were less confident.

IN ANALYSIS RECOMMENDATIONS
AI Use Across Industries
1.	Embed AI into workflows: Integrate AI tools into daily processes so workers move from “occasional” to “daily” adoption.
2.	Target lagging industries: Launch industry-specific AI adoption programs for slower sectors like healthcare and government.
3.	Formalize student access: Universities should include AI literacy courses so students’ informal use becomes structured learning.

 Impact of AI on Jobs
1.	Reskilling over replacement: Build structured reskilling programs that prepare workers for higher-value tasks as AI automates routine work.
2.	Highlight new opportunities: Create career awareness campaigns showing workers the new roles AI is enabling (e.g., AI trainers, auditors, ethicists).
3.	Policy safety nets: Governments should support transition programs to ensure workers displaced by automation have pathways into new jobs.


    AI Skills & Future of Work
1.	Expand formal training: Companies and universities should partner to deliver low-cost AI certification programs.
2.	Close access barriers: Address obstacles like cost and time by offering flexible online/self-paced learning models.
3.	Sector-specific upskilling: Tailor training programs for each sector (e.g., AI for healthcare diagnosis, AI in education).
4.	Mentorship pipelines: Encourage experienced AI users to mentor peers through structured peer-learning initiatives.


    Societal Perceptions & Risks
1.	Ethical frameworks: Establish clear ethical AI guidelines (privacy-first policies, fairness audits).
2.	Multi-stakeholder regulation: Governments, tech companies, and institutions should co-regulate AI, balancing innovation with accountability.
3.	Awareness campaigns: Run public education drives to address misinformation and bias concerns.
4.	Generational bridge programs: Provide executive-level workshops for senior staff to reduce resistance and balance optimism vs caution across age groups.

Confidence & Readiness to Adopt AI
1.	Hands-on exposure: Set up AI sandbox environments where employees practice safely before integrating AI into real work.
2.	AI champions model: Empower confident junior staff to serve as AI ambassadors, guiding peers and seniors.
3.	Confidence-building pathways: Design tiered training programs (Beginner → Intermediate → Advanced) to raise low- and moderate-confidence groups.
4.	Cross-industry learning: Encourage industries like healthcare (with high confidence) to share adoption strategies with less confident sectors.

POST-ANALYSIS AND INSIGHTS
The survey data paints a vivid picture of how people are living through the rise of Artificial Intelligence (AI). After analyzing the charts and responses, several clear insights emerge:

1. AI is Here, But Not Fully Embedded
Out of 323 respondents, most people are already using AI tools — with 209 (65%) saying they rely on more than one tool. Yet, the majority use them only occasionally (43%) rather than daily. This tells us AI is present but not yet indispensable in many industries. Adoption is strongest in tech, education, and even among unemployed respondents using AI for learning, but patchy in areas like healthcare and government.
Insight: AI adoption is real and growing, but it has not yet become a natural part of everyday workflows.

2. AI is Changing Work, Not Destroying It
The fear of mass job loss is not reflected strongly in the data — 70% said no roles had been eliminated in their field. However, 213 people (66%) said AI had already automated some of their tasks. Only 7 respondents pointed to new roles being created.
Insight: People feel AI most at the level of tasks, not jobs. The bigger risk is not unemployment, but the need for workers to adapt to new ways of working.

3. Training is the Key to Confidence
The strongest pattern in the data is the link between training and confidence. Of the 178 who received formal training, most reported high confidence in AI use. Yet, 260 respondents had no structured training and relied on self-teaching. At the same time, nearly 283 people said they wanted training opportunities.
Insight: Curiosity and interest are very high, but without accessible and affordable training, many remain unsure. Training is the bridge between fear and empowerment.

4. Society is Hopeful, But Wary
When asked about concerns, respondents raised job loss (38 mentions), data privacy (30 mentions), loss of creativity (22 mentions), and misinformation (22 mentions). Younger and junior-level workers tend to be more optimistic, while seniors are more cautious. On regulation, opinions were split: about 40% said government, 37% said shared responsibility, and 23% said tech companies.
Insight: People want AI, but they also want it to be safe, ethical, and accountable. Trust in regulation is not yet settled, showing the need for collaboration between government and industry.

5. Confidence Grows With Use
Confidence levels broke down into: 178 (55%) high, 108 (33%) moderate, and 37 (12%) low. Those who use AI daily are the most confident, while those who rarely engage with it feel left behind. Interestingly, the healthcare sector reported high confidence, despite uneven adoption.
Insight: Confidence is not just about training — it comes from hands-on experience. The more people use AI, the more comfortable they become.

 The Big Picture
This survey shows that AI is already part of people’s lives, but adoption is uneven. For most, AI has changed tasks, not eliminated jobs. Workers want to learn, but lack structured training opportunities. Society is cautiously optimistic, but concerns about job security, privacy, and misinformation remain strong. Confidence comes from practice those who use AI daily feel ready for the future, while others are hesitant.
Overall Insight: The success of AI adoption will depend not on the technology itself, but on how industries, educators, and governments support people with training, clear rules, and opportunities to use AI responsibly and confidently.

DATA VISUALIZATIONS & CHARTS

     IMPACT OF AI USE ON JOBS


 <img width="975" height="513" alt="image" src="https://github.com/user-attachments/assets/0d81f0e1-8e2b-42ea-bd33-c1e613d1732f" />


What the Chart Shows:
How AI is affecting jobs - whether it’s reducing roles, creating new ones, or simply automating tasks.
Key Details:
o	225 respondents (70%) said no jobs have been reduced in their field.
o	213 (66%) said AI has automated parts of their work.
o	Only 7 people mentioned new roles being created.
Why It Matters:
The fear of “AI taking all the jobs” doesn’t match reality yet. Instead, people are experiencing task-level change - repetitive work is being automated, but full job roles remain. The real challenge is reskilling workers to thrive in this new environment

 		INDIVIDUAL CHARTS
    Response on New Roles Introduced by AI


 <img width="423" height="402" alt="image" src="https://github.com/user-attachments/assets/680c4bb5-a2ee-425e-ab19-2a5f9aee9ce3" />

Insight: A majority (188 respondents, 58%) indicated no new roles were introduced by AI in their field.
89 respondents (27.5%) were uncertain, while only 46 (14%) acknowledged that new roles had emerged.
Interpretation: This shows that while AI adoption is visible, its role-creation potential is still limited. Most employees perceive AI as automating or modifying existing tasks rather than creating entirely new positions.
Response on Job Roles Reduced Due to AI
											
<img width="567" height="331" alt="image" src="https://github.com/user-attachments/assets/e0cb1cbf-154d-4a7b-8988-b38471f5ccfd" />
 
Insight: 225 respondents (~70%) reported no reduction in roles due to AI.
47 (~15%) confirmed roles were reduced, while 49 (~15%) were unsure.
Interpretation: Despite fears, job elimination is not widespread in this dataset. AI seems more complementary than destructive at this stage, though pockets of displacement exist.
Response on Ways AI Has Impacted Role/Field
<img width="603" height="413" alt="image" src="https://github.com/user-attachments/assets/1aa60af5-0bb7-4c33-8126-13ded350eda6" />


   
Insight:
Automation dominates: 213 respondents said AI automated tasks and improved efficiency.
64 saw no real impact, while 38 noted role replacement, and only 7 mentioned new role creation.
Interpretation: The primary effect of AI so far is task-level automation, not wholesale role creation or replacement. This reinforces the idea that AI is currently a productivity tool, not a job destroyer or creator.
Response on New Roles Introduced by AI (Donut Chart)
		 

<img width="460" height="321" alt="image" src="https://github.com/user-attachments/assets/30a8c588-9ba8-4a3d-a2ce-44fd92f44cdf" />




Insight: This chart reaffirms the first one with percentages:
58.2% said No
27.5% were Not sure
14.24% said Yes
Interpretation: The donut visualization highlights the imbalance — significantly more respondents are skeptical or uncertain about AI’s role in job creation.
New Roles Introduced by AI & Job Roles Reduced Due to AI by Frequency of AI Use


   <img width="883" height="423" alt="image" src="https://github.com/user-attachments/assets/ccb8ce92-b8f4-412d-aa0c-a97e58770586" />

Insight:
Those who use AI daily/occasionally reported some new role creation but also minimal job reductions.
Interestingly, respondents who never use AI still perceived job reductions (possibly influenced by external narratives rather than direct experience).
Interpretation: The frequency of AI use does not strongly correlate with job creation or reduction — showing that perceptions of AI’s impact vary across experience levels.










AI USE ACROSS INDUSTRIES

 <img width="975" height="477" alt="image" src="https://github.com/user-attachments/assets/59dd0b6a-72a7-444e-8d75-0a945d1edaa4" />


What the Chart Shows:
A breakdown of AI adoption across industries, job types, and frequency of use. It also highlights the share of people using multiple AI tools vs none.
Key Details:
o	209 people (65%) use multiple AI tools.
o	7 respondents (2%) reported no AI use at all.
o	120 (37%) use AI daily, while 139 (43%) use it occasionally.
o	Tech and student groups show the highest adoption; healthcare is mixed, with both high usage and pockets of non-users.
Why It Matters:
This chart shows AI is spreading fast, but not evenly. It is deeply rooted in tech and education but needs stronger integration in healthcare, public service, and other slower-moving industries.

INDIVIDUAL CHARTS


Formal AI Training Received by Confidence in Using AI Tools


 <img width="536" height="438" alt="image" src="https://github.com/user-attachments/assets/a659d7d5-0a32-46f2-83c2-1074a00468bf" />

Insight:
178 respondents with formal AI training reported high confidence.
108 had moderate confidence, and 37 had low confidence.
Interpretation: Formal training directly correlates with confidence. The more structured the training, the more comfortable respondents feel applying AI tools in their work/study.











Perceptions on Skills Sufficient for AI Use

<img width="904" height="433" alt="image" src="https://github.com/user-attachments/assets/5e5022f7-f3f1-4347-833f-104cb043a39e" />

     
Insight:
141 respondents believe they have sufficient skills.
105 feel they are somewhat prepared.
45 say they lack sufficient skills, while 26 are unsure.
Interpretation: A majority feel prepared, but a significant portion (around 22%) either lack skills or are uncertain. This indicates a skills gap that training programs could bridge.





Interest in AI Training

<img width="542" height="402" alt="image" src="https://github.com/user-attachments/assets/ab6ba7ce-6f0f-44ed-a3ec-d007be6a4345" />

     
Insight:
293 respondents expressed interest in training, versus just 26 who did not.
Interpretation: Demand for AI training is overwhelmingly high. Organizations can leverage this interest by providing upskilling opportunities, which would also reduce AI-related job insecurity.

Occupation/Job Title by Confidence in AI Use


<img width="461" height="398" alt="image" src="https://github.com/user-attachments/assets/610ccc65-cfe6-462f-9a31-356a92206ed2" />

 
Insight:
Tech respondents (33.5%) dominate in confidence.
Students and unemployed individuals together represent nearly 45%, showing eagerness to adapt.
Business roles form a smaller portion (21%).
Interpretation: Confidence is highest in tech-oriented groups, but other categories are catching up. This highlights a broad-based willingness to integrate AI across industries.






Number of AI Tools Used by Formal AI Training Received

<img width="530" height="394" alt="image" src="https://github.com/user-attachments/assets/9c45fbf1-21dd-4bf9-b901-f7751f62cd29" />

   
Insight:
260 respondents with no formal training still reported using AI tools.
Only 63 with training use tools.
Interpretation: While training boosts confidence, tool adoption is happening organically without it. Many are self-learning via online platforms or trial-and-error, suggesting informal learning is a major adoption pathway.


CONFIDENCE & READINESS TO ADOPT AI
	 

<img width="975" height="537" alt="image" src="https://github.com/user-attachments/assets/941683ef-01cc-4f82-8c68-484b2fb5d472" />


What the Chart Shows:
The relationship between AI training, confidence, and future readiness. It also highlights interest in training formats.
Key Details:
o	178 people with formal training showed high confidence.
o	260 respondents had no formal training.
o	283 people expressed interest in AI training.
o	Confidence is strongest among tech professionals (33.5%).
Why It Matters:
Training is the game-changer. Where formal learning exists, confidence is high. But the majority are self-taught, showing high curiosity but weak institutional support. This highlights the urgency of affordable, structured training programs.
INDIVIDUAL CHARTS  
Confidence in Using AI by Formal AI Training

<img width="450" height="408" alt="image" src="https://github.com/user-attachments/assets/162396a3-a11c-4e25-a0b9-e5ebc5784321" />

 
Insight:
260 respondents (80.5%) reported no formal AI training, while only 63 (19.5%) had training.
Interpretation: Despite limited formal training, many are still engaging with AI. This suggests a reliance on self-learning and informal methods, which may affect depth of understanding.

 Confidence in Using AI Tools

<img width="502" height="408" alt="image" src="https://github.com/user-attachments/assets/9717d6ff-a345-4d69-be13-9bf33108432f" />


Insight:
178 respondents report high confidence.
108 report moderate confidence, and 37 report low confidence.
Interpretation: The majority feel confident, showing that experience and exposure outweigh formal training in driving AI confidence.

Confidence in Using AI Tools by Frequency of AI Use

<img width="673" height="410" alt="image" src="https://github.com/user-attachments/assets/51cfd1ef-ca76-41dc-9668-3ea94b4868ff" />

 
Insight:
Occasional users (139) and daily users (120) show the highest confidence.
Weekly (36) and never-users (20) lag significantly.
Interpretation: Frequency of engagement strongly correlates with confidence. Those using AI regularly are naturally more comfortable.







Confidence in Using AI Tools by Category of Work Experience

<img width="719" height="388" alt="image" src="https://github.com/user-attachments/assets/60e813a9-c37e-421b-a621-1a9a77e6db35" />

 
Insight:
Junior level employees (149) and entry-level employees (100) show the highest confidence.
Confidence drops at mid-level (46) and senior level (28).
Interpretation: Younger/less experienced professionals are more adaptable to AI tools, while older, more senior staff are relatively less confident. This could reflect generational gaps in digital skills.
Confidence in Using AI Tools by Industry Group

<img width="483" height="388" alt="image" src="https://github.com/user-attachments/assets/f68406da-3825-46cd-80a8-d5c05335432c" />

     
Insight:
Health (60) and Business (56) sectors lead in AI confidence.
Education (36) and Tech (25) follow, while Creative/Media and Food & Beverages trail at 23 each.
Interpretation: Surprisingly, healthcare professionals show the highest AI confidence — possibly reflecting exposure to AI diagnostic tools. Business adoption is also strong, while tech respondents are fewer but expectedly skilled.
Confidence in Using AI Tools Category by Frequency of AI Use

<img width="603" height="383" alt="image" src="https://github.com/user-attachments/assets/b63db3dc-e711-4142-9428-ecca472c0553" />

 
Insight:
Occasional users (139) and daily users (120) dominate, together accounting for the majority of confident AI users.
Weekly users (36) and never-users (20) represent a much smaller portion.
Interpretation: This confirms that exposure drives confidence. Even occasional use builds familiarity, while non-users remain the least confident. It highlights the importance of hands-on experience in AI adoption rather than only training.







SOCIETAL PERCEPTIONS & RISKS


<img width="975" height="491" alt="image" src="https://github.com/user-attachments/assets/84f7f221-3811-40e9-93f9-59c494f7bdad" />

 
What the Chart Shows:
How people feel about AI’s broader impact on society, including risks, regulation, and perceptions across different levels of experience.
Key Details:
o	Top concerns: job loss (38), data privacy (30), misinformation (22), loss of creativity (22).
o	Junior employees (149) show the most optimism; only 28 senior staff reported positive perceptions.
o	Regulation split: 40% (government), 37% (shared responsibility), 23% (tech companies).
•	Why It Matters:
This chart captures the emotional side of AI. It shows that while people see opportunities, they also worry about fairness, safety, and control. The generational divide signals that younger workers are ready to embrace AI, while senior staff need reassurance and guidance.
INDIVIDUAL CHARTS
Perception of AI in Industry by Industry Groups

<img width="834" height="442" alt="image" src="https://github.com/user-attachments/assets/3f4fba54-58be-4eab-8858-d199e3879806" />

 
Insight:
Business (230) and Health (219) sectors show the highest positive perception of AI.
Education (139) and Food & Beverage (93) follow.
Tech (91) ranks lower than expected, while Construction (55) and Banking/Finance (60) lag.
Interpretation: Business and healthcare are most receptive to AI, while traditional industries remain skeptical. Interestingly, the tech sector shows moderate perception, possibly due to higher awareness of risks.






AI Tools Used by AI’s Impact on Role/Field

<img width="811" height="446" alt="image" src="https://github.com/user-attachments/assets/45302802-a425-4087-a599-c3a3a8bf5390" />

   
Insight:
Automation dominates (200+ respondents), with AI improving efficiency.
60+ saw no real impact, ~40 noted role replacement, while very few (under 10) reported new task creation.
Interpretation: Society views AI mainly as a tool for efficiency, not for job creation. Concerns about replacement exist but remain secondary.

Perception Category by Category of Work Experience

<img width="560" height="431" alt="image" src="https://github.com/user-attachments/assets/045bb1a2-a5d4-481f-911e-6694b975c125" />

 
Insight:
Junior-level (149) and entry-level (100) workers have the strongest positive perceptions.
Mid-level (46) and senior-level (28) perceptions are weaker.
Interpretation: Younger employees are more optimistic and adaptive, while senior staff may be cautious due to job security or lack of exposure.
Who Should Regulate AI


<img width="475" height="431" alt="image" src="https://github.com/user-attachments/assets/c3dd3c2c-929a-4f65-ab40-5c378e655374" />

 
Insight:
Technology companies (61, 39.6%) top the list.
Shared responsibility (57, 37%) and Governments (36, 23%) follow.
Interpretation: Respondents prefer self-regulation by tech firms, but many also support collaborative governance. Few believe governments alone should regulate, reflecting skepticism about government capacity to manage AI.






 Biggest Concern About AI

<img width="588" height="433" alt="image" src="https://github.com/user-attachments/assets/3a002cad-efbb-4303-b98e-c895942e4795" />

     
Insight:
Job loss (38) and data privacy (30) are the top concerns.
Loss of creativity (22) and misinformation/fake content (22) follow.
Interpretation: Concerns are practical and job-focused, with job security being the biggest fear. Ethical issues (creativity, misinformation) are recognized but not prioritized compared to economic risks.










CONFIDENCE & READINESS TO ADOPT AI

<img width="975" height="537" alt="image" src="https://github.com/user-attachments/assets/d77f2166-1e3e-479c-aa0c-53bda97c65dc" />

 
What the Chart Shows:
Levels of confidence in AI adoption by industry, job level, and frequency of use.
Key Details:
o	178 (55%) reported high confidence, 108 (33%) moderate, 37 (12%) low.
o	Confidence is highest among daily users.
o	Healthcare workers reported unexpectedly high confidence compared to other fields.
o	Junior staff lead in readiness, while mid- and senior-level staff lag.
Why It Matters:
Confidence is not just about training — it grows with hands-on experience. This chart shows that adoption is being driven from the bottom-up (junior staff), not from leadership. Without closing this confidence gap, industries risk a two-speed workforce, where some move ahead while others fall behind.
INDIVIDUAL CHARTS
		Confidence in Using AI by Formal AI Training

<img width="546" height="368" alt="image" src="https://github.com/user-attachments/assets/982d32df-21a2-4506-bbcf-458a9a0afb0a" />

     
Insight:
260 respondents (80.5%) lacked formal AI training.
Only 63 (19.5%) had undergone formal training.
Interpretation: The majority are self-taught, showing a reliance on informal methods (online tools, peer learning). Training programs remain an untapped opportunity to raise structured competence.
Confidence in Using AI Tools

<img width="556" height="408" alt="image" src="https://github.com/user-attachments/assets/ad662b2a-ae10-4d91-8066-089157e181df" />

       
Insight:
High confidence: 178 respondents
Moderate confidence: 108
Low confidence: 37
Interpretation: Despite limited formal training, overall confidence is high, suggesting that practical exposure and everyday use matter more than training certificates.

Confidence in Using AI Tools by Frequency of AI Use

<img width="892" height="410" alt="image" src="https://github.com/user-attachments/assets/f83a0a7c-c3cc-4cb8-a368-446dbaf738af" />

     
Insight:
Occasional users (139) and daily users (120) dominate in confidence.
Weekly (36) and never-users (20) lag significantly.
Interpretation: Frequency of interaction is the key driver of confidence. Even occasional use fosters comfort, whereas lack of exposure hinders confidence.





Confidence in Using AI Tools by Category of Work Experience

<img width="950" height="388" alt="image" src="https://github.com/user-attachments/assets/c32e1081-e4aa-4b92-b414-e15e4883c0fb" />

   
Insight:
Junior level (149) and entry level (100) workers show the highest confidence.
Mid-level (46) and senior level (28) trail behind.
Interpretation: Younger employees are more adaptable, while senior professionals may face challenges due to legacy work habits or lower digital fluency.

Confidence in Using AI Tools by Industry Groups

<img width="656" height="388" alt="image" src="https://github.com/user-attachments/assets/25d01249-aac1-448b-8bdc-ae226abdec62" />

     
Insight:
Health (60) and Business (56) sectors lead.
Education (36) and Tech (25) follow.
Creative/Media (23) and Food & Beverage (23) lag.
Interpretation: Confidence is high where AI has tangible practical applications (healthcare diagnostics, business analytics). Surprisingly, tech has fewer confident users—possibly because they are more critical of AI’s limitations.

Confidence in Using AI Tools Category by Frequency of AI Use

<img width="574" height="383" alt="image" src="https://github.com/user-attachments/assets/0bcbc60d-2191-42e2-b055-f17e19666c21" />

 
Insight:
Occasional users (139) and daily users (120) remain the largest confident groups.
Weekly (36) and never-users (20) are far fewer.
Interpretation: This reinforces the earlier finding that hands-on use outweighs formal training. Regular exposure = higher confidence.







KEY OBSERVATIONS, INSIGHTS & ACTIONABLE RECOMMENDATIONS TAILORED TO:
1.	Government agencies
2.	Small and Medium Enterprises (SMEs)
3.	Large corporations
4.	Educational institutions
5.	Individual workers and students
6.	Different Job Sectors:
•	Marketing & Media
•	Finance
•	Healthcare
•	Legal and compliance 
•	Manufacturing and Logistics 

Government Agencies
Observations:
•	40% of respondents believe government should regulate AI.
•	Concerns around job loss (38 people) and data privacy (30 people) are strong.
Insights:
•	People want trustworthy oversight, but they also expect innovation support.
•	Regulation should balance safeguards and opportunities.
Recommendations:
•	Create national AI literacy programs to close skill gaps.
•	Develop AI ethics frameworks for privacy, bias, and misinformation.
•	Offer transition support (scholarships, retraining grants) for workers in disrupted industries.

Small and Medium Enterprises (SMEs)
Observations:
•	Most respondents use AI only occasionally (43%), showing SMEs lag in full adoption.
•	Lack of structured AI training is a major gap.
Insights:
•	SMEs often lack resources to invest heavily in AI but can benefit the most from efficiency gains.
Recommendations:
•	Adopt low-cost AI tools (automation, chatbots, analytics) to stay competitive.
•	Partner with local training providers to upskill employees affordably.
•	Focus on incremental adoption: start with small AI projects before scaling.

Large Corporations
Observations:
•	Workers report task automation (66%), but few see new roles created.
•	Many employees lack confidence due to limited training access.
Insights:
•	Large firms are adopting AI, but failing to communicate new opportunities or train at scale.
Recommendations:
•	Build structured reskilling pathways for employees.
•	Create AI centers of excellence to test tools and train staff.
•	Publicize new AI-related roles (e.g., AI governance, AI strategy) to reduce workforce anxiety.

Educational Institutions
Observations:
•	Students are among the highest AI adopters, often self-taught.
•	283 respondents want AI training, but access is low.
Insights:
•	Schools and universities are not keeping pace with student demand for AI education.
Recommendations:
•	Integrate AI literacy into the core curriculum.
•	Offer industry-linked training programs (AI in healthcare, AI in finance).
•	Build AI labs to give students hands-on experience.

Individual Workers and Students
Observations:
•	178 people with training report high confidence; 260 without training are less confident.
•	Junior employees are more optimistic than senior ones.
Insights:
•	Personal growth depends on seeking AI learning opportunities.
Recommendations:
•	Workers: take self-paced online courses or mentorships to stay relevant.
•	Students: use AI as a learning partner, but also pursue formal certifications.
•	Senior professionals: engage in executive-level AI workshops to stay competitive.

 By Job Sector

 Marketing & Media
•	Observation: AI adoption is high (content generation, analytics) but concerns about misinformation are significant.
•	Insight: Trust and authenticity are key in this sector.
•	Recommendation: Train teams in AI-assisted creativity and establish fact-checking workflows with AI tools.

 Finance
•	Observation: Strong AI use in automation and data analysis, but privacy and bias remain concerns.
•	Insight: Confidence is tied to ethical risk management.
•	Recommendation: Adopt AI compliance standards and train staff in AI for risk assessment and fraud detection.

 Healthcare
•	Observation: Healthcare workers show high confidence, but adoption is uneven.
•	Insight: AI is trusted where it helps diagnosis and efficiency but resisted where human care feels threatened.
•	Recommendation: Expand AI training for healthcare professionals, focusing on augmented decision-making rather than replacement.

Legal and Compliance
•	Observation: Low awareness of new AI-related roles; strong concerns about bias and accountability.
•	Insight: AI is seen as both a tool and a risk to fairness.
•	Recommendation: Train legal teams in AI ethics, governance, and compliance. Establish AI audit roles within firms.

 Manufacturing and Logistics
•	Observation: Workers mainly see automation of repetitive tasks; new AI-enabled roles are not recognized.
•	Insight: Fear of job loss is higher in this sector compared to service industries.
•	Recommendation: Focus on reskilling workers into higher-value tasks like robotics maintenance, AI-driven supply chain optimization, and quality assurance.

 Final Word
Each stakeholder has a role to play:
•	Governments must regulate fairly and educate broadly.
•	SMEs should adopt cost-effective AI step by step.
•	Large corporations must reskill and communicate clearly.
•	Educational institutions need to lead in AI literacy.
•	Workers and students must invest in their own learning.
•	Sectors must tailor AI use to their unique opportunities and risks.

REFERENCEE:  https://data.mendeley.com/datasets/b89t4x2c2y/1
https://www.kaggle.com/code/devraai/enterprise-genai-adoption-and-productivity-anal
