---
title: "Choosing a research method for design" # Episode title
teaching: 180 # teaching time in minutes
exercises: 60 # exercise time in minutes
---

:::::::::::::::::::::::::::::::::::::: questions

## Questions

  - What distinguishes any method from another, e.g. are there different user experience method types? 
  - How will learners know which methods are the right ones for their user experience research?
  - What ethical considerations do learners need to take into account when choosing a user experience method?
  - How can a user experience research plan affect method selection?


::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: objectives

## Objectives

  - Articulate your motivation for conducting user experience research
  - Define a target user audience for the user experience research
  - Develop an appropriate recruitment strategy based on the chosen target user audience
  - Identify potential risks of participation in user experience research and ways of addressing those risks
  - Identify who (if anyone) will conduct and assist with your user experience research
  - Determine what method (or methods) are appropriate for your open source scientific software


::::::::::::::::::::::::::::::::::::::::::::::::

## What is your motivation and/or or goals for doing user experience research?

In the [introductions example](https://uxcraftforscientificsoftware.github.io/Better-Design-and-Usability-for-open-source-science-software/introduction.html#problem-scenario), Zarah’s motivation for doing user Experience Research was partly because she saw lots of bugs being described by other users of her open source scientific software and partly a curiosity to learn and understand a user (Ester) that uses her open source scientific software differently does their own work.

Zarah is interested in solving current documented problems for herself and other users and also exploring what other potential problems users that are not like Zarah could come across now or in the future. Zarah is motivated by both the now and improving for the future.

## Questions to ask yourself

- What is your goal? 
- What do you hope to learn? 
- Who do you want to learn from and why?

</br>

::::::::::::::::::::::::::::::::::::: challenge

In this exercise you're going to spend time thinking about your project, whatever stage it's in (idea mode or a fully working open source science project) and define and describe it. This is a series of simple and clear statements that communicate the intended use of a product or service.

### Zarah's example

| **Define your project and who it is primarily for**                                                                                                                              	| For scientists and researchers to measure plant traits (aka phenotypes) from images. It is command/script based and works within some web applications. It creates documents that contain code, outputs and documentation.          	|
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------	|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------	|
| **Describe what your tool/software does in an ideal scenario**                                                                                                                   	| Ideally a scientist who has images of plants wants to use the tool to batch-process, quickly process or see what plant traits the tool will offer from an image. Ideally they use the commands/prompts in a development environment 	|
| **State one user experience research goal? (e.g. reduce user errors during data input)**                                                                                         	| To ensure that images of plants submerged in water are able to be processed accurately and in a usable way.                                                                                                                         	|
| **List any critical constraints or limitations of your open source scientific software (e.g. It is written in a particular coding language, it cannot do complex computations)** 	| My open source science project is command based and can be used in certain web applications. There is no GUI. It is written in Python. It has certain limitations on what outputs are possible/available.                           	|


**Add your own**

| **Define your project and who it is primarily for** |  *add your answer here* |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------	|---	|
| **Describe what your tool/software does in an ideal scenario**                                                                                                                   	|  *add your answer here*	|
| **State one user experience research goal? (e.g. reduce user errors during data input)**                                                                                         	|  *add your answer here*	|
| **List any critical constraints or limitations of your open source scientific software (e.g. It is written in a particular coding language, it cannot do complex computations)** 	|  *add your answer here*	|

:::::::::::::::::::::::::::::::::::::::::::::::


::::::::::::::::::::::::::::::::::::: discussion 

## Discussion

Do you notice any key words or themes in your answers?

Are there any open questions related to the **'Questions to ask yourself'** that were difficult to answer?

:::::::::::::::::::::::::::::::::


## Choose and find your target user audience

You may have found that while describing your project and who it is primarily for, you have a good idea of who is already using or interested in your open source science software. You may want to continue to focus on these people and make things better for them. However, it's useful to begin to describe and define the subtle ways that even similar users are different from each other as well as the bigger differences between types of users. Having an idea of the 'type' of person you want to learn more about and some key information about their needs, behaviours, goals and challenges is a good idea before you choose a method and build out your user experience research. This helps you target the method, process and questions towards the key information and insights that you have questions about with your user audience. 

There are some categories you can generalise:


:::::::::::::::::::::::: tab

### Power User

A power user is typically someone who knows every function in a tool, technology or software and is an 'expert' either by their own standards or a standard set by other 'authorities' in relation to the tool, technology or software. They are likely to use a tool, technology or software frequently and instruct others on proficient use.


### Novice User

A novice user is typically someone who knows very little about a tool, technology or software, uses minimal aspects of its functionality and/or uses it very infrequently. They consider themselves to be beginners or use other tools, technologies or softwares more commonly. 


### Contributor User

A user that is on any spectrum of novice to power user but also participates in processes of contribution which allows them access to a tool, technology or software configuration or adaption. These users have a level of familiarity or proficiency that can be determined by the ways in which they contribute e.g. if they are a code contributor they might use the tool, technology or software and also contribute code improvements and fixes. These users are primarily characterised by not only potentially using the tool, technology or software but also how they participate. Some contributor users can be contributors and not use the tool, technology or software.  


### 'Tourist' User

A tourist user can be described as a user that takes a look around the tool, technology or software, perhaps even uses it briefly, downloads or onboards it but doesn't stick around. Either using once and deciding for whatever reason, they will no longer use it or removing the tool, technology or software from their device/s.

:::::::::::::::::::::::::::::::::


We encourage you to choose from one of these archetypes or generalise a user that you are not familiar with and want to learn more about how they use or could use your open source science software. It is advisable to stay away from descriptors that could be too broad such as a user type like 'a teacher'. A more specific user would be 'A teacher that instructed undergrads on basic Python' or 'Basic Python teacher'.

You can spend more time developing a more comprehensive [user persona document](https://github.com/sprblm/The-Design-We-Open/blob/main/Design%20Templates/Personas/COSCUP%202023%20-%20The%20Design%20We%20Open%20-%20persona%20-%20blank.jpg) (also known as a 'proto-persona') or [utilize existing user persona documents made public](https://usable.tools/personas/). User personas typically include some demographic data that is relevant to understand how, why and when a user might interact with a tool, technology or software and should ideally focus on goals, needs, barriers and behaviours more so than demographic data.

As for how many users to do user experience research with, you can choose and make a judgement on whether 1 user or 30 users are what you'd prefer to speak to. There is some 'popular' advice from back in the year 2000 that [testing with 5 users minimum](https://www.nngroup.com/articles/why-you-only-need-to-test-with-5-users/) allows for majority and minority problems to arise. This was [challenged in 2014](https://www.researchgate.net/publication/200553185_Why_and_when_five_test_users_aren't_enough) but the advice that can be generalised here is to test with as many users as it takes to get significant information on a data point.


:::::::::::::::::::::::: callout

It's ok to make some informed assumptions and 'best guesses' about user audiences. These form a hypothesis about their potential needs, goals and behaviors that can be confirmed or challenges in the user experience research data.


:::::::::::::::::::::::::::::::::


:::::::::::::::::::::::: discussion

What kind of user do you want to learn from most? You can decide based on a number of factors including:

- What kind of user you know least about
- What kind of user uses your tool, technology or software the most
- The kind of user you want more of to use your tool, technology or software
- The kind of user that can make a significant impact on your tool, technology or software if they use it and/or talk about using it

There are some resources out there to help you identify what kinds of users and stakeholders are the most important to you and your tool, technology or software. Various forms of [Stakeholder Mapping](https://miro.com/app/board/uXjVKTK-cw8=/?share_link_id=841194464327) can help you identify these users, understand their impact on your tool, technology or software and also map out their expectations, goals and concerns.

:::::::::::::::::::::::::::::::::


## Identifying risks and ethics in user experience research

If you're familiar with academic and research institutions, you may have come across or needed to complete ethics policies, procedures and forms. This is often to ensure that everyone involved in a research project is well protected and aware of any potential risks to health and wellbeing participating in the research might raise.

When performing user experience research outside of an institution that enforces ethics policy procedures, ethical considerations are at the discretion of the person planning, performing and collecting data about users on behalf of the open source science software. There are some good guidelines we recommend in order to protect yourself and others, but how you conduct ethics procedures are dependent on you and your open source science software's policy model.


:::::::::::::::::::::::: callout

## Guidelines

- Provide a way for users that participated in user experience research to have information redacted, changed or stricken from public and private records. An email contact usually suffices.

- Gain informed consent to participate in user experience research from participants and ensure you don't deviate from what they consent to discuss. Depending on the country and laws, certain individuals e.g. underage/children, those with severe mental health impairments are unable to give informed consent. Be aware of your local and national laws. [https://www.nngroup.com/articles/informed-consent/](https://www.nngroup.com/articles/informed-consent/) 

- Provide reasonable documentation and information for users participating in user experience research. Information that helps them to be as prepared as they need to be without biasing their responses can be a delicate balance. Use your best judgement. For example, many user experience researchers offer questions and prompts to users that are responding in an additional/second language in order to ensure they have time to read and understand in that additional/second language.

- Be aware of how any incentives may bias you or the users you interact with. There's plenty that can influence behaviour and responses and accounting for these means your research will remain as objective and honest as possible.

- When making your user experience research plans, processes and data public in an open source way, ask users that participate what level of identifying information they are comfortable with being open and public. Avoid making public any data that could negatively affect them currently or in the future. [https://www.nngroup.com/articles/privacy-and-security/](https://www.nngroup.com/articles/privacy-and-security/)

- When recording data try to keep any words or statements that a user says as close to their word choice as possible. This avoids the risk of incorrectly capturing data or inferring an inaccurate meaning. Remember it's ok to ask your users to clarify and explain their own meanings during the user experience research.

- Be aware of your body language and what words you use in interactions with users during all stages of the user experience research. Discounting, trivializing or dismissing users own points of views, processes and expressions will likely mean you receive less forthcoming responses.

- Remember that even a topic you think is low-risk or innocuous can raise some stressful and uncomfortable responses. Be sure to prioritise comfort and safety for yourself and your participants.


:::::::::::::::::::::::::::::::::


:::::::::::::::::::::::: testimonial

## I'm a design researcher

I'm a design researcher who was doing some user experience research for an open source software technology with people that had experienced violent events and/or genocide events. It was important to hear about what users experienced and how technology can support them in peace and reconciliation work and we had to take extra precautions and consider what we asked users to answer or do. We gave users options to opt-out of certain topics and also provided some psychological support for everyone involved when investigating this topic.

The testimonial might appear to describe a more extreme example. Plenty of science and research deals with difficult topics, from medicine to astro-physics. When we're interacting with other humans to discover their needs, we should take care and attention in how we interact. 

:::::::::::::::::::::::::::::::::


::::::::::::::::::::::::::::::::::::: challenge

**Read the following scenarios and answer two questions individually:**

1. What issues can you foresee for Zarah in each of the following scenarios? 
2. What approaches could you take to mitigate those issues? 

- Zarah has gotten permission to record the session using Zoom, meaning they will also have access to a transcription of the session. 
- Zarah holds a session that covers highly technical material and uses a substantial amount of jargon.
- Zarah used Zoom to record and transcribe their session, then immediately saved it to a drive that their whole department can access.
- Zarah has a transcript excerpt where a person describes their very unique research project and decides to do a web search on them. 

:::::::::::::::::::::::::::::::::


::::::::::::::::::::::::::::::::::::: discussion

When time is up, find someone who shares a user, scientific topic or concern with yourself to discuss your responses to the challenge/exercise.

:::::::::::::::::::::::::::::::::

## What user experience research methods are available to you?

As of July 2022 NnGroup states that there are [up to 20 different user experience research methods](https://www.nngroup.com/articles/which-ux-research-methods/) (and likely many more!) commonly used that you can choose from. These range from well-established methods to more recent, experimental methods as well as methods that range across learning about the attitudes of users and those that learn about the behaviours of users (attitudes and behaviours can be aligned or mis-matched depending on the user and their context).
This also includes methods that are focussed primarily on how a user directly uses and/or manipulates a software, tool or technology (both scripted and unscripted or a ‘please perform X function’ verses ‘Please use the software, tool or technology as you naturally would’) and those that center learnings outside of the direct use of the software, tool or technology such as learning about what a user does before and after using a software, tool or technology, methods are are not directly observational by the researcher (e.g. surveys and focus groups) or general user experience information that helps to inform a software, tool or technology but isn’t directly about the functions of a software, tool or technology. 

You can think about this in terms of what users **do** and what users **say**.

Most methods can involve gathering qualitative and quantitative data. However, quantitative data when reported by users risks being approximations and inaccurate. Though it is sometimes useful to look at how many times users report they perform an action versus a ‘machine’ collected version of that data.


:::::::::::::::::::::::: tab

### Interviews

The researcher and the user can be in the user's own environment, either physical e.g. a lab office and digital or their device they use the software or whatever combination of these that the user defines as their ‘natural space’ or in a third space without the user’s typical ‘context’. Interviews broadly seek to ask questions or prompt the users to speak to their experiences with software, tools or technology. Sometimes they demonstrate or describe out loud to a researcher how they perform a task. 


### Usability testing/User testing

A user is typically brought to a user experience test lab or another third space in order to, one to one be presented with prompts, tasks or scenarios and to as naturally as they are able to with the tools, technology and software available to them in this third space, complete the tasks/prompts to the best of their ability. Usability testing can direct users to only use specific tools, technology and software to solve a problem or more exploratory ways could include the user choosing what tools, technology and software they would use to complete tasks/prompts.

### Surveys

Typically a recording of opinions and responses from users through a series of questions. Limited usually to a rough approximation of attention your user might likely spend on a series of questions.  Surveys are mostly written responses (physically or digitally depending on whether hand written is a key component of what you want to learn). Surveys can be reflective, asking about tasks and opinions about what users have done and memory recall based or if digital, can be configured to appear during or shortly after a task has been completed.

### A/B testing (aka multivariate testing)

A way of testing different visuals, graphics, options or designs by randomly allocating  different percentages of users to interact with different versions. The results are then typically compared to see whether any particular variant has a positive or negative affect on user task completion or user behavior.

### Focus groups

A group of any number of manageable users are typically led by a facilitator through a series of discussions and/or prompts to respond verbally, written or a combination of both. More rarely, focus groups are led by the users themselves in order to surface user-led specifics. 

### Participatory design

A methodology that is led by the users primarily, with or without a suggested structure or goal in order to surface amongst them what is critical to their user needs and how that should be expressed and/or solved. This method attempts to be ‘hands-off’ in terms of allowing users to arrive at whatever conclusions as a group they come to.

:::::::::::::::::::::::::::::::::


:::::::::::::::::::::::: callout

You can find more examples of methodologies in the external resources [https://www.nngroup.com/articles/which-ux-research-methods/](https://www.nngroup.com/articles/which-ux-research-methods/) and [https://www.nngroup.com/articles/research-methods-glossary/](https://www.nngroup.com/articles/research-methods-glossary/).

Including books on the subject like [Universal Methods of Design](https://www.google.com/url?q=https://books.google.co.uk/books/about/Universal_Methods_of_Design.html?id%3DuZ8uzWAcdxEC%26redir_esc%3Dy&sa=D&source=docs&ust=1762166454441782&usg=AOvVaw2yKxLJ6D-v63sZAGB95H3p)

:::::::::::::::::::::::::::::::::


:::::::::::::::::::::::: testimonial

## Zarah speaks to another scientist in their lab

In the example in the introduction, Zarah wanted to make sure she could speak to Ester in Ester’s own lab. Zarah not only wanted to ask Ester questions and see how Ester used her tools, technology and software, but also what Ester's own lab (context) looked like and functioned like. Towards the end of the user experience research Zarah was able to ask some questions about both Ester's computer setup, common tasks and practices but also why her lab was set up in the way that it was and how many other scientists shared that space with her. With this information Zarah could gather contextual data like ‘Ester works with 3 other scientists that also use my open source science software’ and ‘The lab has an area that has ocean water tanks that the computers are separate from’. These are pieces of information that can help Zarah make hypotheses and assumptions about how to optimize or better her open source science software for Zarah and her team.

:::::::::::::::::::::::::::::::::


:::::::::::::::::::::::: challenge

Identify a user experience research method that can be used in the example open source scientific software based on their goals and constraints. These open source scientific software are based on real projects but named differently.

| **Open source scientific software name** 	| **Brief description**                                                                                                  	| **A goal and user/audience type**                                           	| **Method that could be used and why** 	|
|------------------------------------------	|------------------------------------------------------------------------------------------------------------------------	|-----------------------------------------------------------------------------	|---------------------------------------	|
| Plantimg                                 	| An OSS that helps plant scientists detect plant traits using images. Python based. Command Line Interface (CLI) based. 	| Users that are learning how to use the OSS for the first time.              	| _[Add your answer here and why]_      	|
| ArrayOSS                                 	| Scalable storage of tensor data for scientific computing. Python library.                                              	| A user that is unsure they have the correct configuration of dependencies.  	| _[Add your answer here and why]_      	|
| Cellexplorer                             	| Visually explore data to understand human tissue and cells. No-code UI.                                                	| A user that has mostly used code-tools and is looking to try no-code tools. 	| _[Add your answer here and why]_      	|


:::::::::::::::::::::::::::::::::


:::::::::::::::::::::::: discussion

Connecting the methodology explorations to ethical considerations. Do you see any ethical concerns in the proposed user experience research with these open source science software projects or the users indicated?

:::::::::::::::::::::::::::::::::


:::::::::::::::::::::::: challenge

Build out two methods that you think best fits two different open source science softwares, audience/user focus, constraints and goals.

| **Open source scientific software name** 	| **Brief description** 	| **A goal and user/audience type** 	| **Method that could be used and why** 	|
|------------------------------------------	|-----------------------	|-----------------------------------	|---------------------------------------	|
|                                          	|                       	|                                   	|                                       	|
|                                          	|                       	|                                   	|                                       	|


:::::::::::::::::::::::::::::::::


:::::::::::::::::::::::: discussion

Discuss between one-three strengths and limitations for each of the methods in the context of your open source science software.

A strength might be that you have access to a certain type of user you want to visit in their context so doing a contextual inquiry would be accessible.

A limitation might be that a usability test would require a user to have all the required dependencies and also relevant research data on a device that the user does not regularly use, so requires your users to bring certain assets with them.


:::::::::::::::::::::::::::::::::
















:::::::::::::::::::::::: keypoints

## Key points

### Motivation

- Being able to describe and articulate your open source science software’s functionality, limitations and intentions helps you to better define a specific user experience research goal.
- Themes and recurring details can help you identify what is important or meaningful in how you (and others) describe your open source science software.

### Choose and find your target user audience

- Like defining your open source science software’s functions and goals, describing and defining the kinds of users and their needs, traits and expectations helps you to narrow your focus to types of users based on a needs and/or behaviour.
- There are resources that can extend this learning for you in the form of audience and stakeholder mapping exercises that explore more prompts for you to think about users.
- Staying away from broad generalisations of users and specifying what actions and behaviours the users have.

### Identifying risks and ethics in user experience research

- Ethical considerations can be different depending on the kind of users you’re focusing on, the type of open source science project and what (if any) sensitive subjects might arise.
- Lean towards caution and comfort and make sure to adhere to any policies that you might be beholden to as per your institutional affiliation.

### What user experience research methods are available to you?

- There are a long list of methods available to those that conduct user experience research.
- Using details from your open source science software definition, audience definitions and what goals you have to learn about can help you narrow down what methodology you want to use.
- If In doubt, default back to a method you feel confident about and comfortable with. Getting the method process 100% right isn’t as important and practicing and gaining experience doing user experience research.

:::::::::::::::::::::::::::::::::