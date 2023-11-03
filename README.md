# Mission to Mars - AI

## Time Delay - Mission Control Message Board
[Mission Control](https://docs.google.com/presentation/d/1ZrRykfEF3jC3ioVThevr4T3Wx6dh1J_tBEObaAnqKXo/edit?usp=sharing)

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
* Solar Power Array
* Interplanetary Communication Hub
* Spaceport and Launch Facilities
* Waste Recycling and Reclamation Center
* Medical and Research Laboratory
* Off-Earth Manufacturing Plant
* Spacecraft Docking and Repair Bay
* Habitat Expansion Module
* Extraterrestrial Geology Lab
* Zero-Gravity Experimentation Chamber
* Space Weather Monitoring Station
* Deep Space Telescope
* Interstellar Probe Command Center
* Cosmic Ray Research Facility


### Proposal presentations should include at least the following:

* Mission Title
* Misson Patch Logo
* Mission Description
* Mission Outline
* Mission Details
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




## Example AI Conversations
[Meta Prompt](https://chat.openai.com/share/277adf28-667b-4948-b095-ea00d78f0da2)
[Space Farm](https://chat.openai.com/share/cac1b11b-dc82-4924-a39f-fc264dd29fb2)


## Prompts

```
You will generate increasingly concise, entity-dense summaries of the above information.

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


## Graphics Prompts

```
Create a mission badge in the style of NASA's emblems. The badge should feature a stylized spaceship or rocket as the central image, prominently placed against a backdrop of stars and a distant planet. Include the mission name 'Exploration Alpha' curved along the top inside edge of the circle in bold, sans-serif font. Add the year '2023' at the bottom inside edge of the circle in the same font. Use a color scheme of dark blue, white, and a touch of red. The design should evoke a sense of adventure and the thrill of space exploration. The badge should look polished, with clear details, and ready for print on a patch.
```

```
Generate a high-definition, photorealistic graphic of a futuristic Space Farm. The image should reflect a blend of NASA's precision and scientific realism with imaginative elements of space agriculture. Include advanced hydroponic systems with a variety of plants thriving in a controlled environment. The farm should be housed within a transparent, bio-dome structure that optimizes light entry and offers a panoramic view of space, showcasing a stellar backdrop with stars and distant planets. Integrate innovative technologies such as robotic arms for plant care and AI-driven environmental monitoring systems that hover seamlessly within the farm space. The color palette should be vibrant with greens, blues, and metallics to convey a sense of life and advanced technology. The overall composition should convey a self-sustaining ecosystem with a nod to the sleek, clean aesthetic of NASA's design language.
```



