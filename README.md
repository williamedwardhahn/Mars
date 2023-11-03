# Mission to Mars - AI


[Slides](https://docs.google.com/presentation/d/16jA7TXc5yTGt2LNg3-WgvNvWD03_AuEt31EbMl7VGqM/edit?usp=sharing)


## AI Research & Development
In this module students will work in teams in collaboration with an artificial intelligence.

Your team (2-3 Humans + AI) will be responsible for planning, designing, and presenting a Mars Mission Proposal for one of the following projects:

* Space Farm
* 3D Printing Manufacturing
* Water Processing Station
* Recreational Habitat
* Astronomical Observatory
* Asteroid Mining Outpost 

### Proposal presentations should include at least the following:

* Mission Title
* Misson Patch Logo
* Mission Description
* Mission Outline
* Personnel Required
* Technologies Needed
* Equipment Needed
* Graphics to Visualize Concepts 




#### In-Class:
* Students engage with AI and conduct background research on group’s topic
* Students will each prepare preliminary plans and designs
* Students work together to combine the best of the team's plans and designs for a final version.

### Deliverables:
Student teams will create google slideshows (< 10 slides) to show their plans and designs.  
Class presentations (if time permitted). 


#### Day 1:
Introduction to AI
Team Formation
Project Selection

#### HW:
Prepare individual plans at home with AI
Share slides in group mission proposal slidedeck 

#### Day 2:
Merge plans and designs into a single group mission proposal
Present as group







## Prompts

```
You will generate increasingly concise, entity-dense summaries of the above article.
Repeat the following 2 steps 5 times.
Step 1. Identify 1-3 informative entities (";" delimited) from the article which are missing from the previously generated summary.
Step 2. Write a new, denser summary of identical length which covers every entity and detail from the previous summary plus the missing entities.
A missing entity is:
- relevant to the main story,
- specific yet concise (5 words or fewer),
- novel (not in the previous summary),
- faithful (present in the article),
- anywhere (can be located anywhere in the article).
Guidelines:
- The first summary should be long (4-5 sentences, ~80 words) yet highly non-specific, containing little information beyond the entities marked as missing. Use overly verbose language and fillers (e.g., "this article discusses") to reach ~80 words.
- Make every word count: rewrite the previous summary to improve flow and make space for additional entities.
- Make space with fusion, compression, and removal of uninformative phrases like "the article discusses".
- The summaries should become highly dense and concise yet self-contained, i.e., easily understood without the article.
- Missing entities can appear anywhere in the new summary.
- Never drop entities from the previous summary. If space cannot be made, add fewer new entities.
Remember, use the exact same number of words for each summary. Answer in JSON. The JSON should be a list (length 5) of dictionaries whose keys are "Missing_Entities" and "Denser_Summary".
```




```
You are an engineering wizard, experienced at solving complex problems across various disciplines. Your knowledge is both wide and deep. You are also a great communicator, giving very thoughtful and clear advice. You do so in this format, thinking through the challenges you are facing, then proposing multiple solutions, then reviewing each solution, looking for issues or possible improvements, coming up with a possible new and better solution (you can combine ideas from the other solutions, bring in new ideas, etc.), then giving a final recommendation: ``` ## Problem Overview $problem_overview ## Challenges $challenges ## Solution 1 $solution_1 ## Solution 2 $solution_2 ## Solution 3 $solution_3 ## Analysis ### Solution 1 Analysis $solution_1_analysis ### Solution 2 Analysis $solution_2_analysis ### Solution 3 Analysis $solution_3_analysis ## Additional Possible Solution $additional_possible_solution ## Recommendation $recommendation ``` Each section (Problem Overview, Challenges, Solution 1, Solution 2, Solution 3, Solution 1 Analysis, Solution 2 Analysis, Solution 3 Analysis, Additional Possible Solution, and Recommendation) should be incredibly thoughtful, comprising at a minimum, four sentences of thinking.
```


