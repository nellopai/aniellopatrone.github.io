---
title:  "What is... Data Science?"
layout: post
---

It depends who is asking (and whom you ask).

![Southwark Bridge, London, UK](/assets/images/southwark-bridge.jpg)
*Southwark Bridge, London, UK.*


Every once in a while I get asked a seemingly trivial (but somewhat loaded) question in different contexts: **What _actually_ is Data Science?**

Those situations include, for example, teaching of basic data literacy to subject-matter experts, collaborating with co-workers, and presenting to senior management.

Ever since the term has found its way into our language, many definitions have been claimed.
Yet, no universally agreed notion exists.
In this post, I argue that:

1. **No useful, complete, or timeless 'one-size-fits-all' definition exists**
1. **A definition should be given nevertheless and must include all data-related activities, be it for intellectual or commercial purposes**

While going through those two points, I will revisit the much-debated 2017 paper by David Donoho, ['50 Years of Data Science'](https://doi.org/10.1080/10618600.2017.1384734).
In his article, Donoho recapitulates from a statistician's point of view on more than five decades of data analysis since John Tukey's 1962 seminal work ['The Future of Data Analysis'](https://doi.org/10.1214/aoms/1177704711).

### No useful, complete, or timeless 'one-size-fits-all' definition exists

Whatever is necessary and helps to solve your problem using data **and** follows a scientific approach is data science.
Full stop.

Donoho's article starts with an attempt to characterise the current state of affairs around data science. I have clustered them in three main categories.

**Today's consensus definition.**
Donoho quotes curricula and definitions of emerging data science initiatives, mainly at universities.
The author summarises that today's 'consensus data science' is essentially '_a superset of statistics, machine learning, and technology to deal with big data_'.

Clearly, when creating a curriculum, universities need to balance certain criteria, such as duration of study, difficulty of the subject, job prospects of future graduates, or available faculty.

Without question, specialisations are required on university level and naturally result in a significant overlap between disciplines and departments (so do many traditional curricula).
Nevertheless, a practical approach seems to be at the very heart of many data science programmes (which is the same for many other applied curricula).

As a result, the quoted definitions can hardly be used to settle the debate.
They are, however, of great help to prospective students!

**Definition by motivation.**
Much to the regret of an academic, Donoho argues that modern data science developments, including above-mentioned curricula, are  motivated mainly by commercial, rather than intellectual, interest.

While I personally value an intellectual stance, what matters is the impact a field has, be it on an intellectual or on commercial level.

For example, the [UK Research Excellence Framework (REF)](https://www.ref.ac.uk/) evaluates impact, which it [defines](https://www.ref.ac.uk/media/1447/ref-2019_01-guidance-on-submissions.pdf) as '_an effect on, change or benefit to the economy, society, culture, public policy or services, health, the environment or quality of life, beyond academia_'.

Being able to demonstrate wider impact of (academic) research really is a great achievement.
Being able to show direct commercial applicability creates uplift.

**Definition through big data, skills, or jobs.**
Donoho argues that 'big data' is no useful criterion to distinguish data science from statistics (and potentially also from other disciplines).

Many disciplines have a long tradition of analysing plethora of data of all sizes, shapes, and varieties, although their approaches vary and range, for example, from sampling and aggregation all the way to large-scale number crunching and (near) real-time data processing.

His argument is spot on.
Many people practice data science on a daily basis using spreadsheets and basic statistics.

However, Donoho states that today's consensus data science merely encompasses coping skills to deal with (restrictions of) distributed computing and not so much skills to get to the root of the problem, which he claims is inference from data.

The key, I believe, is to understand that big data, skills, and jobs are interlinked in a circular manner, being inflated by one (hype) cycle after the other: Emergence of big data requires technology and skills for their analysis, which creates jobs and a demand for skilled graduates, who then go on and execute what they have been tought: big data.

I refuse any definition of data science that entails the 'big data, skills, and jobs' cycle by necessity as, to the best of my belief, many organisations simply have no need and are well-advised not to enter this territory.
The organisational, technical as well as the cost overhead are tremendous, and the complexity is hard to master.

Nevertheless, with data analysis having become a team effort with individuals increasingly creating more end-to-end data workflows, a possible entry point to big data should not be ruled out, but wisely chosen in the individual case.

### A definition should exist nevertheless and must include all data-related activities, be it for intellectual or commercial purposes.

Donoho's article proposes the definition of **Greater Data Science**, which consists of six divisions:
* Data gathering, preparation, and exploration
* Data representation and transformation
* Computing with data
* Data modelling
* Data visualisation and presentation
* Science about data science

It is a great first start.
However, I feel it falls short of several aspects.
While some of the responses to the article have addressed a potential lack of (software) engineering in this definition (see e.g. ['What "50 Years of Data Science" Leaves Out'](https://medium.com/@srowen/what-50-years-of-data-science-leaves-out-2366c9b61d3d) by Sean Owen), I would like to complement this view as someone who has worked in both academia and industry.

First, what every definition should include are inherent **principles and values** such as:
* Reproducibility of results, models, and software artefacts
* Open science and software culture that includes sharing and building on top of others' work
* Guidelines for practising ethical data science and ethics for creating trustworthy AI
* User experience aspects and human in the loop principles

--- just to name a few.

In all fairness, the reproducibility aspect and the open science movement are well discussed in Donoho's outlook for the next 50 years of data science.

Second, I would like to add a few aspects that I feel Greater Data Science is lacking:

**Communication and presentation skills.**
While both topics are mentioned in Donoho's article in the context of data visualisation, being able to communicate information and conclusions as a basis for decision making is a core competency of any great data scientist.

Conveying just the right level and amount of information to stakeholders or management is key in complex environments.
Even more so when practising in cross-functional teams.

**Domain and expert knowledge.**
A solid understanding of the subject is just as important as deep knowledge of statistics, maths, or computer science. 
Without knowing the domain in detail, even the brightest person will just arrive at trivial, well-known, or useless conclusions.

I am in favour of specialising in one well-chosen area.
It is relatively difficult, if not impossible, to simultaneously practice natural language processing on a high level, be an expert in image analysis for bio-medical applications, as well as to master machine learning for applications in the manufacturing and processing industry.

While it is of course impossible to include every possible subject in a data science curriculum, aspiring data scientists try master a subject on their own account early on.

**Translator skills.**
Guiding and directing internal data teams or external partners in executing data-science projects, and bridging the gap toward businesses require as much business understanding as they require data science knowledge.

Being able to develop a business case, and to derive the necessary data and model requirements is essential.
So is the ability to transform insights into process changes as well as to enable businesses to act upon recommendations.

It is not everyone's cup of tea to take ownership and practice leadership in a project.
Successful data-science projects, however, manage to bridge this gap.

**Project and people management skills.**
Finally, solid leadership skills are crucial for data-science projects.
This is due to the shear complexity of such endeavours.

Being able to frame and to conduct a data-science or machine-learning project well so that the risk of failure is minimised, and value is delivered early and frequently, requires considerable experience.
Recognising when to abort in a controlled manner is key in order not to pursue dead ends, waste resources, or leave behind scorched earth.
