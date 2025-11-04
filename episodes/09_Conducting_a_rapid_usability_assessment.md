---
title: "Conducting a rapid usability assessment" # Episode title
teaching: 60 # teaching time in minutes
exercises: 20 # exercise time in minutes
---

:::::::::::::::::::::::::::::::::::::: questions

## Questions

  - How do I better understand what a user is thinking or expecting as they progress through a task?
  - How do I support users to move through blocks and errors without offering the solution and biasing their task?
  - How can I observe task completion and also take notes?

::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: objectives

## Objectives

  - Prompt participants to think aloud and describe their actions
  - Assist participants with error recovery and keeping the user on task
  - Taking notes on data whilst also not missing any user activity on tasks

::::::::::::::::::::::::::::::::::::::::::::::::

## Preparing for this episode

Parts of this episode has been made into a teachable workshop and can be access here: [https://github.com/jlcohoon/ux-design-strudel/blob/main/episodes/conducting-study.md](https://github.com/jlcohoon/ux-design-strudel/blob/main/episodes/conducting-study.md)

Ahead of this lesson you should have completed the ['Preparing your rapid usability assessment'](https://uxcraftforscientificsoftware.github.io/Better-Design-and-Usability-for-open-source-science-software/04_Preparing_your_rapid_usability_test.html). That lesson should have allowed you to prepare a 'script', 'task plan' or some amount of guidance on what you intend to ask users to do and answer in your rapid usability assessment.

Much of the guidance offered in the lesson ['Conducting Interviews'](https://uxcraftforscientificsoftware.github.io/Better-Design-and-Usability-for-open-source-science-software/08_Conducting_interviews.html) can apply to conducting a rapid usability assessment. In particular, take time to review ['Recording, taking notes and data collection'](https://uxcraftforscientificsoftware.github.io/Better-Design-and-Usability-for-open-source-science-software/08_Conducting_interviews.html#recording-taking-notes-and-data-collection) as one of the primarily unique aspects of recording and taking notes in a rapid usability assessment is, depending on the speed a user usesusers their software/technology as you take notes you may miss micro interactions like where a user moves their mouse cursor, what text they might type and then re-type. In particular rapid usability assessments 'rapidness' means that simultaneous observation and note taking can be intense. Asking users to slow down, to double check what action they just did or what they just wrote is all ok as well as trying to understand, discover and record the pace at which these users naturally work. 

::::::::::::::::::::::::::::::::::::: callout

Take some time to go through the same task you'll be asking a user to go through (if you are able to e.g. have all relevant software/technology etc.). 
Roughly time how long this takes and make a note of the steps involved for yourself. 
By mapping this out, you can isolate the specific parts of a task that you want to be sure to observe closely and carefully.

:::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: discussion

Discussing your tasks and/or questions with another person that is at the same or similar level of familiarity as the users that you intend to test with can uncover any unclear or leading language in the tasks and/or questions.

:::::::::::::::::::::::::::::::::::::::::::::::


## The think aloud protocol 

An important aspect of conducting your rapid usability assessment is to remind users, as they perform tasks, to 'think out loud' and/or describe their thinking, expectations, habits or confusion while they are performing their tasks.

At the start of the usability test you can establish that you want the user to 'think aloud'. A sample statement might sound something like:
*"We want to hear your thoughts as you go, so please think aloud as you do tasks. Feel free to speak your mind. We are not testing you, we are testing the software/prototype/technology/process."*

If you are specifically rapid usability testing a prototype or a version of your open source science software that doesn't have fully operational functions then you can state:
*"We're still working on it, so it might not work as you expect. We wanted to get your feedback early in the process. So telling us your expectations and needs as you perform tasks can help us improve it for you and other future users"*

While you observe what the user did do, what they tried to do, and what they avoided doing or missed, you can ask certain probing questions to better understand problems or motivations of the user. 

**Examples of these probing questions:**
- What are you thinking?
- What are you looking for? Are you looking for something specific and can you describe what you are looking for?
- Why do you think this happened? (in reference to an error or a 'mistake')
- Can you give me more detail as to why you did that action or think that?

With your probing questions and asking users to think out loud, be sure to take into account the time you have for your tasks and questions. Interrupting users that are concentrating on a task (even when they are already thinking out loud) means they can take time to 'get back into' the task and complete it. Be sure to balance how often you probe with questions, interrupt and clarify the user's thinking and expectations and focus on your most critical questions according to your goals for the user experience research  and your overall research question.

Don't be worried if the testers offer direct solutions - that's a common reaction. 
Solutions statements can sound like:*"I want the technology to automatically know when I've added a second plant image from the same plant or around the same time as another photo."* Here a user offers a solution that they believe will solve their problem. But wait! You need to find out the meaning and cause of their need and why they think that's a good idea. 
Use a method like the 'Five Whys' process from the 'Conducting Interviews' episode to explore what the user wants or needs to be able to do.


::::::::::::::::::::::::::::::::::::: challenge

Take a look at the task prompts and user descriptions in the below table. Fill in the gaps where you think a follow up probing question could gain further information or insight.

| **Task description**                                                                                                  	| User response/action                                                                                                                                                                                                                                                                                     	| Probing question                                                                                                                                                                                                                             	|
|-----------------------------------------------------------------------------------------------------------------------	|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------	|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------	|
| Can the user add a new data entry?                                                                                    	| The user starts by spending time finding a data set from their recent data in order to add a new entry. They spend time scanning through cells on a spreadsheet and they are reading silently                                                                                                            	| I notice you've started by looking at a dataset. Can you tell me what you're thinking and why right now? Is there a reason why you started with that?                                                                                        	|
| Show me how you would explore alternative models to train your data on?                                               	| The user hovers over a search function and also uses control + f to search the page for a term related to their research. They say out loud that they are scanning the list of models available and visually ignoring those related to their research in order to find other models to train their data. 	| Can you tell me more about anything you expected to be able to see/do when exploring alternative models? *(here the interviewer is vaguely prompting the function of search to see if the user has any thoughts regarding filtering function)* 	|
| Can you go through this installation process and complete the appropriate requirements/dependencies for the software? 	| *Add your answer here*                                                                                                                                                                                                                                                                                   	| *Add your answer here*                                                                                                                                                                                                                       	|


:::::::::::::::::::::::::::::::::


## Helping users recover from an error

During your rapid usability testing, you may find that users come across problems, errors or places where they get 'stuck'.

It's important to resist the urge to explain your software, correct their mistakes, or defend your choices. Give users plenty of time to solve their own problems/errors or answer your questions/prompts. Don't be afraid of silence or gaps in conversation, sometimes users need time to think and respond (let them know that's okay). 

If asked, you can choose whether or not to indicate to the user whether you've seen this problem or error before. You can prompt them to please try to solve their own problem because it's often important to see how users recover from errors.
If a user is stuck for over 2 minutes on the same problem you can step in to help in order to continue the rapid usability test's plan or you can ask if they'd like to start the task again. You'll likely know the quickest or easiest way to solve this problem from your own usage or checking over the tasks when preparing.

If the user hasn't encountered an explicit error or problem but they're unsure if they've performed the task correctly, they may ask you to confirm whether they are correct or not. This is particularly tricky when they have perhaps misunderstood a task or they have taken an unknown route to solving a task that you did not want to test,

In these situations it's a good idea to remind the user that what they think is correct is the most interesting aspect of the tasks/questions for you. You can try repeating what a tester said or did back to them and clarify their actions - ask them if you understood what they did in order to perform the task or solve a problem correctly. You absolutely can ask a user to pause at a point that feels comfortable to you both and ask them to perform a specific set of actions/functions in order to get to the parts of an experience you need to test. Using your best judgement here is what you'll need to rely on.

Ensuring a user understands a task/question and you can repeat it back to them is especially important if you're testing with someone who is speaking in a language that they don't use often.


:::::::::::::::::::::::: callout

Take a look at one of your tasks in your rapid usability test plan
Try mapping out what the most common ways a user can solve this are and any potential anomalous ways that users could complete that task. 
What are some ways to clarify the task/question to ensure the users proceed down the path that you want to observe and gather data on without being too explicit? 

:::::::::::::::::::::::::::::::::

## Simultaneous observation and note-taking

Taking notes, observing users, thinking about how to prompt and respond to users - there's a lot to remember and do during rapid usability testing. Having more than one user experience research here can help, one person can focus on note taking and the other observing the users behaviour and/or screen/technology and prompting. But not everyone has access to more people to help. Other ways you can manage the work-load is to record audio or video of the rapid usability test (with consent) or do screen recordings if a user is using a device with screen recording capabilities.

We recommend you review the section 'Recording, taking notes and data collection' in the episode 'Conducting Interviews' to cover advice on note-taking generally as well as sorting, tagging and theming data ahead of the analysis process.

If you're conducting the rapid usability test online, you can ask a user to 'share their screen' if the technology you and they are using has that functionality and often these technologies also allow for video and/or audio recording. It's important that you can see what the user is seeing so that you're sure you know what they're talking about and whether they are progressing the task as you intended. Some of these technologies also allow for transcription of what is said with time stamps for when. These are helpful when looking back at written data and checking what part of a task was performed when and what was said.

If you don't have access to help or these technologies, then ensuring you're not trying to cover too many tasks/questions in the time you have and going slowly will help you gather accurate data, which is more useful than volumes of inaccurate data.

Lastly, a great way to get additional useful feedback is, at the end of the rapid usability test, to ask if there's anything else they'd like to share with you - sometimes the most interesting insights come after the test is finished and the perceived pressure's off the user.

Further resources can be found here:[https://sprblm.github.io/devs-guide-to/conducting-a-user-test/](https://sprblm.github.io/devs-guide-to/conducting-a-user-test/)


::::::::::::::::::::::::::::::::::::: discussion

Based on your knowledge of your tools, what combination of technologies, people based-support or processes do you think will help you to maintain good data collection as well as observing the user?

:::::::::::::::::::::::::::::::::::::::::::::::


:::::::::::::::::::::::: keypoints

## Key points

### The think aloud protocol 

- Going through the tasks yourself or with another person that meets the criteria of your users can help you understand how feasible your tasks and questions are in relation to timings.
- Ensure your 'think aloud' probing questions are related to your goals for user experience research and/or your overall research question. Be sure to balance how often you are probing.


### Helping users recover from an error

- Users often take different pathways to complete a task than you anticipated. They also often encounter errors even if you've tested extensively for error states. Planning for how long you're happy to have users divert from the pathway you want to test is up to your own judgment.

### Simultaneous observation and note-taking

- Using technology and people-based support can help you gather more data that can be checked against transcripts and time stamps but if in doubt about what you have access to, go slow, be accurate and stay realistic about the balance of observation and data note-taking.


:::::::::::::::::::::::::::::::::