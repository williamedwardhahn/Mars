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
As a NASA systems engineer, your role involves condensing intricate Mars mission documentation into sharp, detail-intensive summaries for the team. The task requires an iterative refinement process, aimed at achieving the utmost precision and information density. Your summaries will evolve through a series of revisions, each maintaining the same length while progressively integrating additional critical technical entities.

Perform the following 2 steps 5 times to evolve the summary:

Step 1. Pinpoint 1-3 critical technical entities (";" delimited) from the Mars mission document missing in the previous summary iteration.

Step 2. Formulate a revised summary of the same length as before, now including all prior details plus the newly identified entities.

Guidelines for the process:

- Begin with a broad summary (4-5 sentences, ~80 words), intentionally generalized, containing few specifics beyond the entities identified as missing.

- Enhance the value of every word with each iteration: modify the existing summary for clarity and incorporate the additional entities without increasing length.

- Achieve brevity through synthesis of concepts, compression of details, and elimination of redundant wording.

- Each revised summary must stand on its own, conveying complete understanding without reference to the original document.

- Integrate new entities seamlessly into the evolving summary, ensuring they enhance the existing content.

- Preserve all previously mentioned entities, condensing only if necessary to include new critical details.

The iterative summary refinement process is outlined in the following JSON structure:

```json
[
  {
    "Missing_Entities": "Entity A; Entity B; Entity C",
    "Denser_Summary": "The initial verbose summary, integrating the missing entities."
  },
  {
    "Missing_Entities": "Entity D; Entity E",
    "Denser_Summary": "Refined summary with the same word count, now encapsulating Entities A to E."
  },
  // Subsequent iterations follow the same structure
]

```


## Graphics Prompts

```
Create a mission badge in the style of NASA's emblems. The badge should feature a stylized spaceship or rocket as the central image, prominently placed against a backdrop of stars and a distant planet. Include the mission name 'Exploration Alpha' curved along the top inside edge of the circle in bold, sans-serif font. Add the year '2023' at the bottom inside edge of the circle in the same font. Use a color scheme of dark blue, white, and a touch of red. The design should evoke a sense of adventure and the thrill of space exploration. The badge should look polished, with clear details, and ready for print on a patch.
```

```
Generate a high-definition, photorealistic graphic of a futuristic Space Farm. The image should reflect a blend of NASA's precision and scientific realism with imaginative elements of space agriculture. Include advanced hydroponic systems with a variety of plants thriving in a controlled environment. The farm should be housed within a transparent, bio-dome structure that optimizes light entry and offers a panoramic view of space, showcasing a stellar backdrop with stars and distant planets. Integrate innovative technologies such as robotic arms for plant care and AI-driven environmental monitoring systems that hover seamlessly within the farm space. The color palette should be vibrant with greens, blues, and metallics to convey a sense of life and advanced technology. The overall composition should convey a self-sustaining ecosystem with a nod to the sleek, clean aesthetic of NASA's design language.
```



