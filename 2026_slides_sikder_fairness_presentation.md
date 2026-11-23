---
marp: true
theme: default
footer: 'S. Sikder | DRA ToT'
paginate: true
author: "Sujit Sikder"
description: "Digital Research Academy – Train the Trainer"
style: |
  section {
    justify-content: flex-start;
    font-family: Arial, Helvetica, sans-serif;
    padding: 46px 58px;
    color: #1f2933;
  }

  h1 {
    color: #174a2a;
    font-size: 2em;
    margin-bottom: 0.35em;
  }

  blockquote {
    border-left: 7px solid #52be30;
    background: #edf8e9;
    padding: 0.5em 0.8em;
    margin: 0.6em 0;
  }
---


<!-- title slide--> 



# __FAIRness__

> Presentation  Preparation, Collaboration and Sharing 


### Duration:** 60 minutes

### Date: 20th November 2026 

### Prepared for: DRA ToT session

![bg right 40%](./assets/DRA_LogoColourPos.png)

<!--DRA logo source--https://drive.google.com/drive/folders/1JzXhbG5aFwlEAJYwSk3nFDOYfBXUI49i)-->


---

![bg 90%](./assets/course_plan.png)

---

# __Sujit Kumar Sikder__

> Academic background in spatial planning, working with geoinformation

**Senior Scientist**, 
Research Data Centre - [IOER FDZ](https://ioer-fdz.de)
Research Area: [Spatial Information and Modeling](https://www.ioer.de/en/research/spatial-information-and-modelling),
Leibniz Institute of Ecological Urban and Regional Development - [IOER](https://www.ioer.de) 
Dresden, Germany. 



### Freelance Trainer at __Academy for International Cooperation (AIZ) | GIZ__

--- 

# Why do we need to learn on this topic? 

<!--- Webslide Alex: https://slides.ad.ioer.info/haclathon-presentation/#/
-->


---

![](https://upload.wikimedia.org/wikipedia/commons/thumb/8/8b/FAIR_data_principles.svg/1920px-FAIR_data_principles.svg.png) 

> Wilkinson, Dumontier, Aalbersberg, et al. (2016), The [FAIR Guiding Principles](https://doi.org/10.1038/sdata.2016.18) for scientific data management and stewardship. Sci Data 3, Nature.

<!-- Image Credit: https://commons.wikimedia.org/wiki/File:FAIR_data_principles.svg -->

---

# Tell us your story?

---

## Garcia L, Batut B, Burke ML, Kuzak M, Psomopoulos F, Arcila R, et al. (2020) __Ten simple rules for making training materials FAIR.__ PLoS Computational Biology 16(5): e1007854. [DOI](https://doi.org/10.1371/journal.pcbi.1007854)

![bg right 80%](./assets/plos_paper_10_rules_fair_training.png)

---
# FAIRness Wheel

![bg right  90%](./assets/10_steps_fair_presentation.png)

[Wiegers et al. (2019)](https://doi.org/10.5281/zenodo.3593257)

---
![bg fit 90%](./assets/10_steps_fair_presentation.png)

---
# PART 2
---

![bg 70%](./assets/course_plan.png)

---

![bg fit 80%](https://libraries.mit.edu/app/uploads/sites/4/2020/11/FAIRNotOpen-e1604960355240.png) 

<!--Image credit: (https://libraries.mit.edu/app/uploads/sites/4/2020/11/FAIRNotOpen-e1604960355240.png) -->

---

# Trend in [Open X](https://learn.opengeoedu.de/opendata/vorlesung/hintergruende/timeline)

![](./assets/open_data_trend_opengeoedu.png)

---
## Not only FAIR - [CARE Principles](https://www.gida-global.org/care) for Indigenous Data Governance

![](https://images.squarespace-cdn.com/content/v1/5d3799de845604000199cd24/1567592451970-2R8XFL670QNMAGDRV7ED/Be+FAIR+and+CARE.png?format=2500w)

---

## Our data (digital objects): **FAIR**
## We should: **CARE**
## User can: **TRUST**
## Let's be **OPEN**, if Possible
## Why not __ELSA__ (Ethical, Legal and Social Aspects)

---

![bg 70%](./assets/insight_figure.svg)

---

# PATHWAYS

## 1. PREPARE + SHARE
## 2. PREPARE + SHARE +  COLLABORATE 

---

![bg 50%](https://marp.app/assets/marp.svg)


---

# WHAT IS __MARP__ ?
 
 > A Markdown-based framework
 
 - Create presentation slides
 - Human-readable text for both people and machines
 - Highly interoperable 


---
# WHAT IS __MARKDOWN__ ?



```text 
Example: Text

# Heading 1
## Heading 2

Example: Image
![name](.my_image.png)

Example: Web content

![name](./asset/.my_image.png)

```
file format `.md` 




---
# WHAT ABOUT __LEARNING CURVE__ ?

- Use your favourite IDE - for example, VS Code
- Basic skills in **Markdown syntax**

> We can be artists with some  skills: `HTML`  `css` syntex

---

# EXPORTABLE FORMATS

> `.md` -export to - 
>> PDF
>> HTML

### Also PPTX __if you miss it so much - your drug__

---
# READY TO SHARE

## Now, if you want to __share__ all the presentation materials, use a preferred repository (best practice)

> Conforming to curation policies and requirements

Presentation (local)
> Version control - `git` (release)
>> FAIR publication repository - `Zenodo` 

---

# REUSABILITY | REPRODUCIBILITY | REPLICABILITY

- Keep slide content, structure and styling in version control.
- All content is an object that can be tracked.

> A good practice is to keep your input digital objects (keep metadata and citations)  including documentation at the same location
> - for example figure sources (`draw.io`  files) and code books, if possible
> - citations as  `.bibtxt`


---

# COMMENT - I do not like the default styles

> Customise - themes, layouts and web technologies to meet presentation needs.


![](./assets/defult_marp.png)

> Start minimal `.default`; try to customize if you really know what you are doing.

---

# We are done with the __Pathway 1__


--- 

# COLLABORATION

#### Share source files and track changes in a __Git-based workflow__, e.g., CI/CD.

![](./assets/git_workflow.png)


---
# __GIT__ IS COMPLEX !!

> I am not a software or code person!
> I am a software person - Marp has a CLI too :)

### It can help if collaborators clearly define __roles__ and have complementary __skills__

---
<!-- _class: invert -->

![bg right 90%](./assets/2026_11_19_vs_code_screen_fairness_slide.png)

# QUICK DEMO

---


# ARE THERE ANY ALTERNATIVES?

- [Quarto](https://quarto.org/)
- [Slidev](https://sli.dev/)
- [reveal.js](https://revealjs.com/)
- [Remark.js](https://remarkjs.com/)
- [Presenterm](https://github.com/mfontanini/presenterm)

---
# COMMITMENT AND REFLECTION


## What is __one change__ you will make to your __next presentation__ to improve its FAIRness?

## Which pathway will you follow from tomorrow: __Pathway 1__ or __Pathway 2__?




---
# Thank you for your attention!


<img src="https://upload.wikimedia.org/wikipedia/commons/0/06/ORCID_iD.svg" alt="ORCiD" width="20" style="vertical-align:middle;"> [ORCiD](https://orcid.org/0000-0002-0265-7394)  
<img src="https://upload.wikimedia.org/wikipedia/commons/c/ca/LinkedIn_logo_initials.png" alt="LinkedIn" width="20" style="vertical-align:middle;"> [LinkedIn](https://de.linkedin.com/in/sujit-sikder-a4971523)

Website: https://ssujit.github.io




