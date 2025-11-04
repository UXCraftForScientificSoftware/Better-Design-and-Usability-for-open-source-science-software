---
title: "Connecting the dots and next steps" # Episode title
teaching: 60 # teaching time in minutes
exercises: 20 # exercise time in minutes
---

:::::::::::::::::::::::::::::::::::::: questions

## Questions

  - How do I present my results to my stakeholders and the open community? Are there differences in how I should present my results?
  - How can I start to prioritize my results with what to focus on and how to communicate that?
  - What resources are out there to help guide changes?
  - How can I make a case to continue user experience design to funders?


::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: objectives

## Objectives

  - Present results to your stakeholders/the OSS community
  - Prioritize user experience research results to plan and implement
  - Identify design and development resources to help guide changes
  - Make a case for user experience design to funders

::::::::::::::::::::::::::::::::::::::::::::::::


## Working in the open

Connecting the dots broadly encompasses how you communicate to whomever your stakeholders are, what you have discovered, how you went about that and what you will decide from here on. How you involve or do not involve stakeholders, community and peers in this process is largely your choice. Some processes we'll introduce are inclusive by default of being processes developed within open source software communities. However, you are the best judge of whether this is the right time for this process or not. It could be that you're still a growing open source scientific project and your community is small and growing in its understanding and competency, it could also be due to some policies and considerations from your host institution.

Read forward and be aware that these episodes are making some assumptions:
1. That you are working in the open and as transparently as you are able to be
2. That plan to involve other people in your open science community either now or in the future.
3. That you have an idea of how you'll structure decision making and governance should your project gain high involvement.

The minimum we would recommend you make transparent and open in your project is your assertions from your interpretations. A format such as 'We learned that users **(needed/wanted/had trouble)** with **(problem/task)** based on this data we extracted these common **(themes)** to inform this **(user statement)**. This is important to this project given our **(goal/research question/etc).**'.

Putting this in public documents, issues, discussions or wherever you want to put that is discoverable by those interested in your open source scientific project.


::::::::::::::::::::::::::::::::::::: challenge

Governance and the decision making process can feel like an overwhelming undertaking at any point of an open source project. The risks involved with not implementing some simple governance can have consequences and complications later in your project's life.

**Here we invite you to set out some simple governance and decision making processes regarding your user experience research by answering questions.**

**Would you like people to do user experience research for your project themselves by following your openly available examples? If yes (link examples)**

**Would you like individual contributors to choose what user experience research they do for your projects or should they look to any goals or roadmap documents?**

**Do you require an IRB process to be followed in order for the contribution to be made?**

**Can a user experience research contributor become a 'user experience maintainer' as in they can make user statements and assertions based on data to inform the direction of the open source scientific project?**

**When would they stop being a maintainer? (e.g. after a period of inactivity)**

**When will these governance/structure questions be revised/revisited by the project founder? E.g. 1 year, 2 years**

:::::::::::::::::::::::::::::::::::::::::::::::


## Prioritization processes

The next phase is the process of prioritising the synthesis findings in the context of your open source scientific projects's goals and/or roadmap. We'll save the in-depth process for a future resource and go over some of the basics.

::::::::::::::::::::::::::::::::::::: tab

### Weighted Matrix 
Identify and prioritize the most promising opportunities from multiple user experience research statements. This method helps with shared decision-making and helps overcome common biases. The matrix ranks potential user experience research opportunities against key success criteria.
The "criteria" represents the primary measures of your scientific open source software rated on a scale, as defined by yourself and/or your stakeholders.
A listing of "opportunities" represents the user experience research opportunities that elicit the most serious interest from the team. The method provides a structured process for discussion among stakeholders, shifting decision-making to a process grounded in success criteria, not personal opinions.

### KJ Technique
A sort method to help work through a problem space and prioritize focus from a complicated range of ideas and information. It focuses on one question and sets stakeholders to work on the same task at the same time. Everyone in the group writes as many problems, data, insights, or opinions as they can, informed by the user experience. By assigning each attribute to one of five categories, user values regarding satisfaction can be revealed. 
- Required (atari mae or "quality element") are the baseline features that must be included e.g. privacy, safety, and security. 
- Desired (ichi gen teki or "one-dimensional quality element") are attributes that when included, increase the perceived value/use of the product.
- Exciter/Delighter (mi ryoku teki or "attractive quality element") are a source of surprise based on latent user needs, improving measures of satisfaction. 
- Neutral (mu kan shin or "indifferent quality element") represent features that users don't have strong feelings for either way.  
- Anti-feature (gyaku or "reverse quality element") attributes provide insight into what you should leave out of a product.


:::::::::::::::::::::::::::::::::::::::::::::::

Both these methodologies can be grounded in your open source science software's goals and/or your overall research question.

When it comes to selecting and surfacing what user statements and data are important, use your best collective judgment to select which data you will focus on. You can't focus on everything and there will likely be disagreements, especially around scope and technical feasibility.
This isn't just about what you and your stakeholders working on the open source science software think is important, but what the users from your user experience research think are important. Each time you select a theme as important, be sure to ask yourselves "Do the users think this is important as well as the myself/my stakeholders?".
Focus now on the themes and how they relate to your goals/research question rather than the perceived difficulty of technical implications. For example, by selecting 'reducing errors' it doesn't mean you have to do complex technical improvements. It's just acknowledging the importance of the topic and how it should be considered in the future to align with user expectation and need.

If further defining and scoping your user experience research statements is needed, we also recommend looking into SMART objectives, especially for those user statements that emerge as the most needed, critical or relevant to your goals/research question. SMART method means: Specific, Measurable, Achievable (or Assignable), Realistic (Relevant), Time-bound. These are typically given some written context and scored 1-5. 1 being a low score and 5 being a high score.


::::::::::::::::::::::::::::::::::::: callout

For example:
*"We learned that users **had trouble being sure that any new underwater plant images would be of the same quality** when **they wanted to use them to create plots, graphs etc.** Based on this data we extracted the common **themes of #hacks, #standards, #benchmarking, #error avoidance, problem solving, processes and optimisation** to inform the user statement '**As a** PhD researcher researching the effects of complimentary underwater plant ecosystems on the health of those water-ecosystems, **I want to** be confident that the image I'm using are 'good' examples measured against an example/baseline image and be certain of that image accuracy **so that** I can process images without double checking and being concerned about the accuracy and more confident'. This is important to this project given our goal of finding where our users of our plant computer vision OSS find the most problems in their processes and where we can help them complete their unique tasks towards their research best?'."*

:::::::::::::::::::::::::::::::::

This statements scoring:
**Specific** - 4/5 - this statement specifically references a section of the process most if not all users will take but from a unique user type perspective. It lacks detail on the nature of standardisation practices.
**Measurable** - 3/5 - This statement has a measurable element of time reduction for eliminating the photo-checking behaviour for this user (and other similar users). Testing how much time it takes and how much confidence is needed to avoid checking is critical.
**Achievable (or Assignable)** - 2/5 - This statement does identify a specific section of a workflow and one users' specific work-around but outside of that example, broadly this being achievable is unknown. 
**Realistic (Relevant)** - 5/5 - This statement directly describes a problem that slows the user down and makes them prone to errors that take a long time to recover from.
**Time-bound** - 3/5 - This statement has a sense of time boundaries given the time it takes to perform the specific task can be quantified re. Time and then measured to reduce the time. The work can also then be 'stopped' when this task time has been reduced and/or improved.

This statement therefore has a fairly high score for SMART. Though these scores for applying SMART this statement could be further defined and detailed, a rough estimate can also be usefully applicable.

Applying SMART then allows us to assign a rough prioritisation process:
1. **Do now** - High scores on SMART.
2. **Do soon** - Lower SMART scores but there is still a clear positive impact on users.
3. **Idea for the future** - Lower SMART scores and hard to see the impact without further user research.
4. **Blue sky thinking** - Lowest SMART scores and lacks some critical knowledge or infrastructure to even discuss.

The user statements that have high SMART scores are typically those with more clarity, definition and applicability to a project. SMART when combined with KJ technique or a weighted matrix moves you further towards a clear, assertive and relevant design assertion and decision that when/if challenged, can be referred to.

However, there are other ways to prioritize user statements and data. You can prioritize based on how feasible the implementation is, how 'painful' a user rates a task/feature to their daily lives/processes or you can leave the prioritization completely up to users and allocate them the power to vote on the features or improvements they need/want the most. You can find resources on those processes in some product management work the [Superbloom Design completed with the Turing Institute's open source projects here](https://penpot.app/penpothub/libraries-templates/oss-product-management).


::::::::::::::::::::::::::::::::::::: challenge

Take a look at the below goal/research question and the subsequent prioritised and selected user statements. You'll see that the example uses some SMART methodology as well as a rough quarters (a calendar year split into 4 sections) road map outline in order to add some permanence to these priorities. These user statements have been shortened for ease to read.

**Goal:** Where are our users of our plant computer visioning OSS finding the most problems in their processes and where can we help them complete their unique tasks towards their research best?

| **Quarter 1**                                                                             	| **Quarter 2**                                                                                                                 	| **Quarter 3**                                                                                                       	| **Quarter 4**                                                                                                  	|
|-------------------------------------------------------------------------------------------	|-------------------------------------------------------------------------------------------------------------------------------	|---------------------------------------------------------------------------------------------------------------------	|----------------------------------------------------------------------------------------------------------------	|
| Improve clarity of error messaging when using commands/prompts to plot graphs and charts. 	| Improve accuracy of processing images without users double checking and being concerned about the accuracy and more confident 	| Make sure documentation is easy and accessible to contribute to when a user has a unique workflow and/or processes. 	| Similar image auto recognition and apply same commands/prompts and/or suggest to run the same commands/prompts 	|
| S = 4 M = 3 A = 3 R = 5 T= 4                                                              	| S = 3 M = 4 A = 2 R = 5 T= 3                                                                                                  	| S = 3 M = 4 A = 2 R = 2 T= 2                                                                                        	| S = 3 M = 1 A = 1 R = 2 T= 2                                                                                   	|


These have been prioritized in order of which is the SMARTest user statements first. That doesn't have to be the only rationale you use to prioritize, as long as you have a clear and evidence based reason to prioritize a less SMART user statement you could choose to put that one first.

Now take a look at these additional SMART user statements, where would you add these into the rough roadmap and why.

1. Guides and documentation for internal institution contributors to get involved in helping to maintain and develop the open science software. 

Specific = 2 Measurable = 4 Achievable = 3 Realistic = 3 Time-bound= 1

2. Feature to benchmark/standardise underwater images automatically

Specific = 3 Measurable = 3 Achievable = 1 Realistic = 1 Time-bound= 1

3. Sample images and recommended prompts/commands in the CLI for first time users included in install packages.

Specific = 5 Measurable = 4 Achievable = 5 Realistic = 5 Time-bound= 4

4. Better accuracy for underwater thermal/temperature plots and imaging outputs to be detected based on inputted environmental data e.g. water type (sea, fresh etc.) and location images was taken. Possible metadata able to be ingested.

Specific = 5 Measurable = 4 Achievable = 4 Realistic = 4 Time-bound= 3

| **Quarter 1**                     	| **Quarter 2**                     	| **Quarter 3**                     	| **Quarter 4**                     	|
|-----------------------------------	|-----------------------------------	|-----------------------------------	|-----------------------------------	|
| *Add your roadmap statement here* 	| *Add your roadmap statement here* 	| *Add your roadmap statement here* 	| *Add your roadmap statement here* 	|
| *Add your SMART score here*       	| *Add your SMART score here*       	| *Add your SMART score here*       	| *Add your SMART score here*       	|

:::::::::::::::::::::::::::::::::

## Finding resources to help guide changes in your open source scientific software

There are plenty of resources available to you to help guide both prioritization and the other aspects we've covered across this lesson regarding making confident design decisions for your open source scientific software.

Notable examples of what can help guide changes in your open source scientific software can be found in looking at existing tools and software both within and outside of the sciences. You can find good examples of 'good practice' in GUI (Graphical User Interfaces) and also good examples of design without a GUI (like in the command terminal/CLI). 

When it comes to CLI design, accessibility and information structure/hierarchy is profoundly important. [You can watch Hartmut Obendorf of Canonical's talk about designing for CLI here](https://youtu.be/1D_8HnsfWkU) and find out more about good accessibility at the [A11y Project](https://www.a11yproject.com/).

When it comes to projects that have a GUI/UI then you can look towards the tools and software that you use as well as best practices like [Heuristic Evaluation methods](https://www.nngroup.com/articles/how-to-conduct-a-heuristic-evaluation/). Many organizations, companies and individuals have now created Design Kits or UI Systems for people making tools that have GUI. Tools such as [Tailwind CSS](https://tailwindcss.com/) and [Github's Primer UI](https://primer.style/). These kits/systems are great to look to for inspiration, reference or even use in implementations where possible. Many of these design UI kits have accessibility guidelines already considered and have been tested for usability.

You can find domain specific Design systems like [STRUDEL](https://strudel.science/) which was created specifically by designers working alongside scientists and researchers at Lawrence Berkeley National Lab Scientific Data. This system has been created and maintained with scientific workflows and tasks specifically in mind and therefore you can know when you use them, that other scientific projects have tested these before.


:::::::::::::::::::::::: discussion

What design kits or systems are you familiar with or have heard of? If you haven't heard of these before, take some time to find one online and take a look at some of the UI elements. How might these work in your specific scientific context?

:::::::::::::::::::::::::::::::::


## Making the case to continue and sustain user experience research

You've reached the end of the lesson content for ** Better Design and Usability for Open Source Science and Research Software**. This isn't the end of how you make better, more informed design decisions for open source scientific software but these episodes have equipped you with the foundational and fundamental skills needed to engage with your project in order to investigate user goals and needs in a structured, data driven way. This has led to you being able to define the users and behaviours you want to study/observe through gathering, sorting and interpreting that data into prioritized lists. From here you can

Investing in user experience research aims to help clarify and merge both your needs as open source science project founder/maintainer and what those using your project need. The return on user experience time and energy investment is often most clearly expressed in the form of coherent and clarity of the journey to prioritized decision making of what you will focus on building and improving. In that way, the benefits of user experience research are how clearly it allows for user needs to be communicated and combined with other goals, transforming into more openly communicated improvements, user satisfaction and subsequent benefits to those impacting research and science discoveries using these tools and software.


:::::::::::::::::::::::: discussion

Spend some time reflecting on what you've learned and how it impacts your work. In what ways can these processes be communicated to your peers, institutions and funders in order to help them understand the value of user experience research and how it can inform project development?

:::::::::::::::::::::::::::::::::


:::::::::::::::::::::::: keypoints

## Key points

### Working in the open

- Making a minimum effort to be open and transparent with your user experience research, as long as your institution's policies and procedures allow, will help your open source science software project be sustainable for the long term.
- Governance and decision making in your open science software project doesn't need to be long and highly detailed. It can serve a limited purpose of transparency for a period of time.


### Prioritization processes

- Prioritizing processes and methods are about clarity, evidence, communication and often about getting all stakeholders and involved parties in agreement on what should be focused on at what time.
- As long as an assertion can be made for a prioritisation that is grounded in the user data and subsequent statements, then prioritization follows.
- Prioritization is most beneficial and useful to people external to your open science software project so they can understand what to expect and roughly when to expect it. This can also help them to know when and how to offer assistance and contributions as well as signalling to funders and institutions that you're thinking about users beyond yourself and how your open source science software fits into the wider user-base.


### Finding resources to help guide changes in your open source scientific software

- There are resources and references online that can help any kind of specific open source science project improve. 
- UI kits and design systems are existing and established ways that people have implemented UI for users. They often specialise in a certain type of software, tool or user-type.

### Making the case to continue and sustain user experience research

- Articulating and communicating the value of user experience research is often in the time saved in the journey from user data to prioritized project improvements, drawing direct lines between what users need and what is improved.

:::::::::::::::::::::::::::::::::