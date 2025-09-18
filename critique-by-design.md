| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Insurance costs diffe

## Step one: the visualization


link: https://data.world/makeovermonday/2020w20
<img width="1806" height="1030" alt="Screenshot 2025-09-18 at 12 30 06 PM" src="https://github.com/user-attachments/assets/8c491f9c-09d9-493a-ae6c-0dc07c0d5b8d" />

I selected this visualization for two reasons. 
First, the topic is highly relatable  almost everyone has experience with car insurance, and differences in premiums across states can have a big financial impact. It’s the type of data where a clear and honest presentation matters because readers might use it to make personal or policy decisions. Second, the original design uses a radial “spoke” layout, which is visually striking but not very effective for comparison. The format makes it difficult to see differences between states, rank states, or understand the gap between minimum and full coverage policies. In other words, it sacrifices clarity for aesthetics, which makes it a strong candidate for critique and redesign.


## Step two: the critique


- **Purpose & Message:**  
  The chart aimed to show how car insurance costs vary by state and highlight the difference between minimum and full coverage policies. However, the radial layout distracted from this message and made ranking or quick comparisons nearly impossible.

- **Information & Data:**  
  The data itself (annual cost by state, for both policy types) was clear and sourced publicly. But the visualization missed an opportunity to provide additional useful context, such as regional patterns or state income levels for affordability comparisons.

- **Design & Encoding:**  
 Showing costs as the length of the circle’s spokes made it hard to compare states accurately. States on opposite sides of the circle couldn’t be compared easily, and the layout forced viewers to rotate mentally to interpret values.

- **Color & Accessibility:**  
  Purple and pink distinguished the two coverage types, but the palette didn’t clearly signal meaning. The design relied heavily on color without accessible alternatives like direct labeling or stronger separation.

- **Annotations & Storytelling:**  
  The chart had minimal annotations. There were no callouts for key states (like Michigan, which had the highest costs) or contextual notes explaining why some states differed dramatically. As a result, the narrative was weak.

- **Audience Fit:**  
  For a general audience of drivers and consumers, the design fell short. Most readers would want to know quickly: “Where does my state rank?” or “Which states are the most and least expensive?” The layout didn’t make this easy.

**Summary of critique:**  
The visualization was attractive but confusing. It drew attention because of its circular format, but this came at the cost of clarity. It was hard to see exact values, spot trends, or compare across states. A redesign needs to simplify the encoding side by side bar charts, while maintaining audience engagement.

## Step three: Sketch a solution
First Draft

<img width="2960" height="1566" alt="Screenshot 2025-09-18 at 5 53 05 PM" src="https://github.com/user-attachments/assets/ecdef0ba-2ce2-418f-82d1-6697fc25618e" />
<div class='tableauPlaceholder' id='viz1758232561920' style='position: relative'><noscript><a href='#'><img alt='Cost of insurance in different states ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Co&#47;Costofinsurance&#47;Costofinsuranceindifferentstates&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Costofinsurance&#47;Costofinsuranceindifferentstates' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Co&#47;Costofinsurance&#47;Costofinsuranceindifferentstates&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                <script type='text/javascript'>             
  var divElement = document.getElementById('viz1758232561920');             
  var vizElement = divElement.getElementsByTagName('object')[0];         
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';        
  var scriptElement = document.createElement('script');                
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';         
  vizElement.parentNode.insertBefore(scriptElement, vizElement);            
</script>

LINK: https://public.tableau.com/views/Costofinsurance/Costofinsuranceindifferentstates?:language=enUS&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link
Here I tried to compare the insurance difference and max and min values in side by side. Maybe visually, it doesn't look great, but attempting to show simple relation meaning to the people.



## Step four: Test the solution

Questions to ask: 

- Can you tell me what you think this is?(Q1)

- Can you describe to me what this is telling you?(Q2)

- Is there anything you find surprising or confusing?(Q3)

- Who do you think is the intended audience for this?(Q4)

- Is there anything you would change or do differently?(Q5)

Results: 

_Don't identify or share personally identifiable information (PII) about the people you spoke to._


| Question | Interview 1                                       | Interview 2       |
|----------|---------------------------------------------------|---------------------------------------------------------------------------|                 
|  Q1      | states with with numbers                          |Insurance price with different places                                      |
|  Q2      | states car insurance with different values        | Prices differences                                                        | 
|  Q3      | subtitle descriptions are unclear                 | Same for the bottom titles                                                |
|  Q4      | car owner who are moving to different states      | Thinking about different car opportunity insurances                       |        
|  Q5      | more clear on title and color is common confused  | Colors and subtitles, maybe considering dotplots or somet different charts|                                  

Synthesis: 

_What patterns in the feedback emerge?  What did you learn from the feedback?  Based on this feedback, come up with what design changes you think might make the most sense in your final redesign._

I agree for the people mentioning about colors and subtitles, even might be considering different charts. I fully agree with with that. 

## Step five: build the solution
![IMG_1509](https://github.com/user-attachments/assets/fd172305-e964-46dd-9f31-8d1a61de3664)

 this is my second draft. Which is more clear in terms of implication. Now i used Tableau to make it look like this
<div class='tableauPlaceholder' id='viz1758232796732' style='position: relative'><noscript><a href='#'><img alt='Car insurance Costs by State(2020)- Full vs Minimum Coverage ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Co&#47;Costofinsuranceineachstates&#47;Sheet2&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Costofinsuranceineachstates&#47;Sheet2' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Co&#47;Costofinsuranceineachstates&#47;Sheet2&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                <script type='text/javascript'>               
  var divElement = document.getElementById('viz1758232796732');      
  var vizElement = divElement.getElementsByTagName('object')[0];            
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';     
  var scriptElement = document.createElement('script');              
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';        
  vizElement.parentNode.insertBefore(scriptElement, vizElement);  
</script>

<img width="2954" height="1426" alt="Screenshot 2025-09-18 at 5 50 26 PM" src="https://github.com/user-attachments/assets/c0daf442-4af3-4d46-bb2a-26fd67f180d8" />




LINK: https://public.tableau.com/views/Costofinsuranceineachstates/Sheet2?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link


My first draft used a side-by-side bar chart with Tableau’s default colors (orange, blue, and red). While it showed both minimum and full coverage by state, feedback from colleagues highlighted that it was hard to compare the differences, the color choices didn’t carry meaning, and the chart felt overcrowded. Based on this feedback, I redesigned the visualization as a dot plot with connecting lines. I chose green for minimum coverage to suggest affordability and positivity, and red for full coverage to emphasize higher cost. I also sorted states by full coverage to make Michigan’s extreme high and Maine’s low cost immediately visible, and formatted labels as currency for precision. These changes transformed the visualization from a cluttered bar chart into a cleaner, more intuitive design.


## AI acknowledgements
I ask Gen AI about my visuon into reality, when i use tableau, couldn't make a line between full coverage to minimum coverage. GenAi make step by step process to help me to figure out this problem. In terms of new visualization, my roommate suggested me about the possible solution to about the drawing in above.
