| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Outline 

Topic: Stress steals sleep in high-pressure jobs

Sleep is critical to health, productivity, and well-being, but many high-pressure jobs make it difficult to get enough rest. Using the Lifestyle and Sleep Patterns dataset, I will explore how stress levels in demanding occupations (e.g., doctors, software engineers, and sales representatives) are linked to sleep duration and quality.My goal is to tell a story that goes beyond simple correlations: to show which jobs are most affected by stress-driven sleep loss, and to connect these findings to the real world challenges students and young professionals face as they prepare for demanding careers.


1. Setup = Why sleep matters

Start with a simple truth: “Sleep is one of the most important factors for our health, but it’s often the first thing we give up in demanding careers.”
Then introduce a clear chart that shows the recommended 7–9 hours of sleep alongside the actual averages from the dataset.
The takeaway: most people aren’t getting enough rest and those in high pressure jobs are struggling the most.

2. Tension = Stress is the thief of sleep

Next, I’ll introduce stress as the main antagonist: “Stress steals sleep, and some jobs pile it on more than others.” Maybe a scatterplot of stress levels against sleep duration will make this clear, with clusters of doctors, engineers, and sales representatives all trending toward higher stress and shorter nights. The message is simple but powerful the data shows that in these careers, stress consistently cuts away one to two hours of rest.

3. Insight = Who suffers the most?
   
Focusing on occupations brings the data to life. Doctors stand out with the highest stress and the shortest nights of sleep, a reflection of relentless schedules and constant pressure. Sales representatives also struggle, combining high stress with higher BMIs and frequent insomnia, clear signs that their work challenges go beyond just rest. Engineers appear in the middle ground, with moderate stress and slightly longer sleep, though the quality of that sleep is often lower. To humanize these patterns, I’ll use bar charts alongside persona style cards that capture the lived reality of each group. The takeaway is simple: not all jobs affect rest equally some careers truly “steal” more sleep than others.

4. Resolution = What it means for us

To wrap it up, I’ll bring the story back to my audience graduate students and young professionals on the verge of entering high pressure careers. A final chart will highlight the cycle: high stress leads to less sleep, which in turn leads to poorer health and lower performance. The key message is clear: “As we prepare to enter these demanding roles, managing stress and building healthy routines may be just as important as sharpening our technical skills.”
The project will close with a simple but memorable frame: “Sleep is not wasted time, it’s the foundation for performance.”


## Initial sketches
  
![IMG_1510](https://github.com/user-attachments/assets/3e27ac1d-f498-4974-9972-b5fec8c53f17)
<img width="1380" height="980" alt="output (1)" src="https://github.com/user-attachments/assets/02beb810-7c52-48b3-9354-98a82b967c1a" />

For now, these are simple drafts I can show, but they will need refinement whether through new graphics or improvements to the current bar chart and scatterplot. I’ve realized during this class that while it’s tempting to add more visuals and “fancier” elements, I’m leaning toward keeping things as straightforward as possible. My current vision is to focus on clarity making sure the data’s meaning is explicit and easy to understand rather than overly complex.

# The data
> A couple of paragraphs that document your data source(s), and an explanation of how you plan on using your data. 

Sources
 link : https://www.kaggle.com/datasets/minahilfatima12328/lifestyle-and-sleep-patterns?resource=download  
 
 Primary dataset: Sleep Health and Lifestyle Dataset (CSV provided).

 Variables of interest: Occupation, Stress Level, Sleep Duration, Quality of Sleep, Heart Rate, BMI Category.

I will subset the data to focus on high-pressure jobs (doctors, engineers, sales reps). Then, I’ll compare average stress levels and sleep duration across occupations, analyze correlations, and create personas to illustrate “what a typical worker looks like” in each role.

This analysis will allow me to tell a story about how stress patterns across occupations affect sleep outcomes. The dataset is already clean (no missing values) and is publicly available for educational purposes.

| Name                             |                 URL  |      Description |
|----------------------------------|----------------------|------------------|
| Sleep Health and Lifestyle Dataset|  https://www.kaggle.com/datasets/minahilfatima12328/lifestyle-and-sleep-patterns?resource=download|Contains demographic, lifestyle, and sleep-related variables for 374 individuals.     |

# Method and medium
I will use Tableau to clean and analyze the dataset, creating clear and effective visuals that highlight the key relationships in the data. Python may be used in a supporting role for quick checks or exploratory summaries, but the primary analysis and visualization will be done in Tableau. My narrative will then be assembled in Shorthand (or ArcGIS StoryMaps) to provide an interactive, stand alone experience. Finally, the GitHub Pages site will link to the Shorthand project and include all supporting materials such as the dataset, markdown, and sketches.


