---
title: "Conducting Interviews" # Episode title
teaching: 120 # teaching time in minutes
exercises: 60 # exercise time in minutes
---

:::::::::::::::::::::::::::::::::::::: questions

## Questions

  - How do I know if a user is telling me everything they think honestly?
  - When and why should a user experience researcher go 'off script' and improvise questions during an interview?
  - How to balance what a user experience research wants to learn with how much time is optimal for questions?
  - How can I tell if questions are getting useful and relevant answers?
  - How do you know when you have enough data?

::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: objectives

## Objectives

  - Building rapport with introduction sections and building trust
  - How to encourage users to expand on their answers using the '5 whys' method
  - Craft useful followup questions with strategic improvisation
  - Implement strategies for managing time during an interview

::::::::::::::::::::::::::::::::::::::::::::::::


## Conducting Interviews

We covered in the 'Preparing your interview study' making a list of questions and possibly some tasks to ask users while you (and any supporting researchers) observe and note down data. Now we'll cover the processes that can be used in the interviews and 'course correcting' and improvising should your interview not quite be going to plan. Remember, your protocols, scripts, questions and tasks should be 'very good guidelines' and you won't ruin the credibility of information from an interview by deviating from your script, as long as you keep some good rules in mind and remember what your user experience research goals and research questions are.

::::::::::::::::::::::::::::::::::::: challenge

Without looking back at your notes from your previous exercise, can you write in your own words what your user experience research goal is, what you want to learn from what kind of user and how it relates to your overall research question and/or scientific focus?

| **Zarah’s example free-form goal, hopes and research question**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     	| **Your  example free-form goal, hopes and research question** 	|
|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------	|---------------------------------------------------------------	|
| Zarah's goal in talking to Ester is to learn more about the specific moments that are most different from how she uses her open source scientific software for soil-based plants to Ester's water-based plants. She wants to see how and when Ester has changed or modified a workflow or CLI command and what unique scripts she may have written or what ways water images are unique. She wants to try to find what tasks in the open source scientific software are the most difficult or time-consuming or those that Ester has had to 'hack' ways around to work. This helps Zarah to overall make a more proficient and broad computer vision tool for photographic plant recognition, potentially allowing for multi-disciplinary use of her open source scientific software in the future. 	| *Add your organised here*                                       	|

How does this differ from what you've written before and what aspects did you find harder to remember or express? Are there ways those can be simplified or made more manageable/memorable?

:::::::::::::::::::::::::::::::::::::::::::::::


## Building trust with users and leading into your user experience research questions

An important aspect of interview technique is setting a comfortable tone and allowing the user to speak their mind and use the words they find best to express their thoughts, opinions and experiences. If the user doesn't feel comfortable then they may hold back thoughts and experiences and 'self-edit'. 

After thanking the user for participating and briefly introducing yourself and the testing process you can then ask some 'warm up' questions or clarifications of what you think you understand of their role, work or common uses of the open source scientific software. You can also keep these tailored to your goal and have them lead into your other questions.

**Some warm up question might be:** 
*How is your research going, can you tell me about it?*
*(if the user has used the open source science software tool before) So, when was the first time you used this tool? Or When was the last time you used this tool?*
*How do you normally use this tool?*

You might have noticed that these are all **open questions**. They prompt for longer answers than a 'yes' or 'no' and aims to gently learn about the users behaviours, baseline usage of tools and also build some connection between the user and the interviewer. During the warm up question phase, you can also respond to the same question you ask the user or a question they might ask you (as long as it doesn't give away the other questions and prompts in the interview!). A back and forth warm up phase might look like:

**Researcher:** *Thanks for taking the time to speak with me [explains the protocols and details]. Do you have any questions or clarifications?*
**User:** *No, that sounds fine*
**Researcher:** *Before I start with my scripted questions, I'd love to know more about your research and where you are in your research journey?*
**User:** *Oh it's been [explains about the research and its current state]*
**Researcher:** *I heard you mention about the software we'll be talking about, Can you tell me more about [scripted question about software]?*


:::::::::::::::::::::::: callout 

## Practice
 
Try out building rapport building with people you know and see how you can bring in a subject you're interested in after rapport building. Make a note of any themes, content or statements that have previously helped you build rapport.


:::::::::::::::::::::::::::::::::


## Encouraging users and the '5 whys' method

The '5 Whys' (also known as conversation laddering) is a tactic to help user experience researchers discover a root motivation or cause of a problem for a user they are speaking with and move closer to an actionable statement. During an interview or user testing you may hear a statement about a user action or problem.

Statement from a typical user might sound like: 
*I [the user] do not password protect my shared files.*
*I [the user] do not read the CLI text unless it's an error.*
*I [the user] always make sure to run two similar photos through the command.*

There are many assumptions we can make based on these statements. In an interview setting, This is your opportunity to expand on that statement to get more information because this is vital information for finding solutions. If you assume a user's problem without asking "why", you could eventually build a solution that doesn't help. Asking "why" can help you arrive at the root cause. If you ask "why" several times, you journey deeper into the problem space and collect more details. "Five" is just an example - it could take less than five "why" questions, or it may take a few more. And you may discover that you have more than one root motivation, like in the example below.

Example of a conversation that employs the Five Whys technique:

| **The why's** 	| **Researcher questions**                                                               	| **User answers**                                                                                                                                                                                                                                                  	|
|---------------	|----------------------------------------------------------------------------------------	|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------	|
| *1st 'why'*     	| Researcher: Why do you always make sure to run two similar photos through the command? 	| User: Well, it's because i want to check over the results                                                                                                                                                                                                         	|
| *2nd 'why'*     	| Researcher: Why do you want to check over the results?                                 	| User: Because I don't trust that two similar photos will show similar or the same results                                                                                                                                                                         	|
| *3rd 'why'*     	| Researcher: Why don't you trust that the results will be similar?                      	| User: I'm not sure which variations in a photograph, if any are going to affect results so i run two similar ones to see if the command is not accurate                                                                                                           	|
| *4th 'why'*     	| Researcher: Why do you worry about the command being accurate?                         	| User: If the command isn't accurate then the hypothesis i base my research on based on how the common in the software produces results then i could make bad research                                                                                             	|
| *5th 'why'*     	| Researcher: Why are you concerned with making inaccurate or bad research hypotheses?   	| User: Well, this means i would have to re-do more than just the one image command task, i'd have to re-do other parts of my research so i want to be sure of how accurate the command is when dealing with photos and I don't want to see suspicious differences. 	|


You can see how the conversation progresses the more 'whys' are asked. We can discover the root problem, concern or worry that a user wants to avoid by doing the initial action that stated. This can help us inform how we solve a problem, instead of 'building a feature in our open source scientific software that allows for two image processes at once' we can instead explore other ways to help users feel confident that an image is accurately processed.

It can sometimes feel odd to keep asking your tester 'why' so we suggest a few different ways of phrasing the 'why':
*Can you explain why that's the case?*
*Can you give me more detail as to why you think that?*
*Why do you think this happened?
*Is there another aspect of what you described that you want to expand on? (Notice how there's no 'why' word in this statement but it still asks 'why' in another way!)*

There is a certain amount of 'clarifying' that can be done with user motivations. A follow-up clarification can look like:

*It sounds like in your circumstances you are concerned with the level of accuracy with which an image is being processed and what conditions might affect an image being processed and lead to a less-accurate result. By running two similar images you are trying to see if slight differences make any impact on results. Does that sound right?*


::::::::::::::::::::::::::::::::::::: challenge

Look at the questions below and fill in the gaps where the researcher can ask a follow up 'why' question.

| **The why's** 	| **Researcher questions**                                                           	| **User answers**                                                                                                              	|
|---------------	|------------------------------------------------------------------------------------	|-------------------------------------------------------------------------------------------------------------------------------	|
| 1st *'why'*     	| Researcher: Why don't you password protect your files when you want to share them? 	| User: Well, it's because files need to be shared quickly with my colleagues in the field when they're out on a critical task. 	|
| *2nd 'why'*    	| Researcher:                                                                        	| User:                                                                                                                         	|

| **The why's** 	| **Researcher questions**                                                      	| **User answers**                                                                                                                                          	|
|---------------	|-------------------------------------------------------------------------------	|-----------------------------------------------------------------------------------------------------------------------------------------------------------	|
| *1st 'why'*     	| Researcher: Why is it that you do not read the CLI text unless it's an error? 	| User: Sometimes there so much text to read in the CLI that i only pay attention to the text when i see red text or a message with 'error' in the sentence 	|
| 2nd *'why'*     	| Researcher:                                                                   	| User:                                                                                                                                                     	|

For now, it's ok to guess what the users will say (or what might you say) in response to the 'why' question. Practicing how to form these follow up exploratory questions is the first step to improving during interviews.

You can take this practice further and take a question from your sample script in the 'preparing your interview study' episode and imagine an answer from a user and progress through '5 whys'.

:::::::::::::::::::::::::::::::::


## Improvising questions, guiding discussion and remembering you goal/research question

There are a number of strategies and methods you can use to bring a user experience interview back around to your goal/research question. Many of these are subtle ways of slowing down the users on the topic they've deviated to from your goal/research question or dodging them by asking you questions and clarifications about what you are trying to understand about them. 

| **What the user does**                                                                                                                      	| **What you can do to course-correct**                                                                                                                                                                                                                             	|
|---------------------------------------------------------------------------------------------------------------------------------------------	|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------	|
| When a user goes on an unrelated tangent from the question, goal or topic you asked                                                         	| Sorry to interrupt, I think you moved onto a [tangent topic]. I want to return to speak about [goal topic] and then if we have time, we can speak more on [tangent topic]. Here's the question again and roughly where you got before [tangent topic]             	|
| A user starts to focus on complaints and saying disparaging things about the software generally or another related (or unrelated) software. 	| It sounds like you're having a lot of challenges and issues with this software. Can you tell me more about what you wanted to do and what you expected to happen rather than focus on the specific bad function/thing that happened please.                       	|
| The user reflects your question back at you (the interviewer) either by asking 'what do you think' or re-framing the question back.         	| I'm here to find out about what you think about and what your answers to these questions are. There's no 'correct' or 'wrong' answers and I want to hear what you think about [topic]. I'll happily tell you about what I think once the interview has concluded. 	|
| The user gives very short one word answers to explorative questions                                                                         	| Do you have anything else to say on this [topic] or is this all that you experience on the [topic]?                                                                                                                                                               	|


These kinds of things occur rarely and as long as you remember that your goal is to find out about the other person try to remain invested in their responses but aware of how you commenting can affect and bias further statements. A good number of users, even those that display confidence can become hesitant and nervous when their opinions don't seem to match the interviewers. It's also much harder to respond with a 'No, I don't think that but I do think x'. Avoiding language that means a user needs to contradict or disagree with you means you'll encourage even those that are on the more shy and reserved side to speak their minds.

**When it comes to improvisation, there are some good general rules:**
- Reframing questions and offering different ways of explaining or asking can help users better understand what you're asking - if the user asks 'can you repeat the question or re-frame it?' then don't be afraid to ask what part was confusing or unclear
- If the user starts talking about a new, surprising or unexpected experience, opinion or insight but it's still related to your goal, topic or research question, allowing the users to continue is fine as long as you reassess the time you have for your other questions
- Users might offer information to later questions or prompts at the start of an interview. You can either choose to pause them and state you'll return to that subject later or you can allow them to continue and keep track of which later questions/prompts have already been covered.
- A user might give you an exciting new idea for a goal, question or topic during an interview that you didn't anticipate in your preparation - you can choose to pursue it in the moment or you can make a note to include it in future interviews and include it onwards into your next interviews. This might mean you have a data gap you need to fill, but you can always ask users back for short conversations to fill in the gap.


::::::::::::::::::::::::::::::::::::: challenge

Take a look at the below questions from a user experience research guide. The first one has an example of how the question can be re-framed. Fill in the spaces for the questions that have yet to be re-framed.

| **Original script question**                                                                                                                                                                                                                                             	| **Re-framed question**                                                                                                                                                                                                                                   	|
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------	|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------	|
| Can you tell me how a new user might start using your open source scientific software?                                                                                                                                                                                   	| Imagine you are a brand new user, you can tell me/describe to me what kind of users are the most likely to be using your open source scientific software. Tell me what they would do first? What is the first essential step in your opinion/experience? 	|
| Show me what a user does when they want to do [description of a task]. Specific example: If a user wants to start to build a new AI-driven virtual cell in order to predict a behaviour they are interested in, can you show me how they would access an existing model? 	| I'm interested in seeing how you think through and take steps towards using an existing model and apply it to a new AI-driven cell behaviour observation. Take me through each step please.                                                              	|
| I'm interested in seeing how you work with this open API for lattice cryptography. Talk me through why and show me how you'd use an API here?                                                                                                                            	| *Add your answer here*                                                                                                                                                                                                                                   	|
| Can you talk me through how you find astronomical data and information that applies to your research?                                                                                                                                                                    	| *Add your answer here*                                                                                                                                                                                                                                   	|

:::::::::::::::::::::::::::::::::


::::::::::::::::::::::::::::::::::::: callout

Remember when reframing the question it's tempting to either simplify or to mistakenly give a 'preference' on how you want the question answered. There's no perfect formula for re-framing and improvising but using your best judgement is a good idea.

:::::::::::::::::::::::::::::::::


## Time management strategies for user interviews

When preparing your interview guide, you can attribute rough timings to questions alongside the question such as *'Ask the user to show me their commonly used open source scientific software tools'* (10 mins) and this can give you an idea of how long you'll allocate for a user to talk to this topic. 
Generally, it's always better to finish early than to go over time. So planning for less questions than the total time you have is advised. Typically, people can participate in a user experience interview for between 20 minutes and 60 minutes. When you go over 60 minutes adding in breaks are essential and ensuring you have a variety of questions, tasks and topics is key. This is a relatively advised limitation to attention spans and energy levels to engage with questions. 

Make sure to prioritise both pacing/progression of questions as well as attempting to prioritise the questions/prompts you are most interested in asking that relate back to your goals and research question. 

Try not to rush or hurry a user when they are answering a question and allocate time for users to think, change their mind, adapt their answers or talk around the question subject. Anything that rushes or interrupts the user can also interrupt and divert the answer that they were in the process of giving.

If it helps you to set your own timers for questions/prompts to help you know when you can move on then you can do so subtly or you can let the user know that you're setting timers so you can respect the user's time they've offered the best. Remind a user that they are not being 'timed' to complete tasks or answer questions in the most efficient manner - you're interested in their natural behaviour patterns and responses but the timer is there to ensure respect.

Remember that you can always ask for more time at another point to cover questions you might not have gotten to or perhaps these questions can be cut from your interview question guide given they were not a priority.


## Recording, taking notes and data collection

When conducting an interview the typical method of data collection is audio/video/screen recording the interview and/or taking written notes of some form. 
If you handwrite notes, it is recommended that you take digital photos of those notes in order to maintain back-ups and to potentially share them in an open source location/repository.

It is strongly advised to gain written and vocally recorded permission from the user you are interviewing that they consent to recording and note taking.

For audio, video and any identifying imagery we recommend not making these open source in order to protect the identity of your users.

Remember to clarify in documentation any shorthand or jargon that may be said in a user recording or taken in written notes.

When it comes to sorting your notes as you go or preparing a method for more efficient analysis of notes in the synthesis and analysis phase, you can choose how much you'd like to prepare ahead of the interview. Taking notes underneath a question/prompt heading can help you remember what question/prompt a response is in relation to or you can set up certain 'tags' or 'themes' to get a head-start on a thematic analysis process. Be sure to take notes for different user participants on different documents/pages/sections to ensure that data from one user doesn't initially get mixed with others. We recommend giving user participants code names in your notes to obfuscate any identifying information from your notes. You can also do codes for specific info that could identify the user participant such as institution name/affiliation, role/position or a particular OSS or tool name. 

We briefly covered 'how much data is enough data to be significant' in 'Choosing a research method' where we covered whether 5 users is enough users to show significant trends/leanings in user experience research data. When it comes to knowing if you have enough data, assessing how much time you have to collect data, how many users you have access to (or time to recruit users) and the time taken to analyse and understand the data can help inform your choice of 'how much data is enough data?'. Arguably this challenge can come down to you answering the question of 'Has the data I've collected allowed me to make an informed decision on how to improve my open source scientific software?'. If you feel confident in making an informed decision or change/intervention that can be further studied then this is often enough data.


::::::::::::::::::::::::::::::::::::: challenge

**Read the following scenarios and answer questions individually:**
What issues can you foresee for Zarah in each of the following scenarios? 
What approaches could you take to mitigate those issues? 

- Zarah was able to record and transcribe their session using Zoom and they also had someone else do a rough transcription while the session was conducted. Zarah took notes themselves too.
- Zarah's user has asked them not to record the session and Zarah does not have anyone else available to help take notes.
- Zarah was using a tagging structure for her written notes and another person helping was asking the questions. When they discussed, the person helping had their own opinions of categories of the responses they remembered along with specific jargon used

:::::::::::::::::::::::::::::::::


::::::::::::::::::::::::::::::::::::: discussion

When time is up, we will return to the group to discuss everyone's responses to the challenge/exercise.

:::::::::::::::::::::::::::::::::


:::::::::::::::::::::::: keypoints

## Key points

### Building trust with users and leading into your user experience research questions

- Review your goals, objectives and hopes for your user experience research
- Understand the purpose of a warm up question or statement and how to help users feel comfortable speaking with you about their thoughts, experiences and opinions.


### Encouraging users and the '5 whys' method

- Understand how to ask varied 'why' questions to get to the root causes of a problem.
- Clarifying by repeating what you think those root causes are back to the user can help you be confident about your understanding of the users root causes.


### Improvising questions, guiding discussion and remembering you goal/research question

- Being able to re-frame or improvise based on new information/context a user can offer in an interview needs to be assessed 'in the moment' and is a skill you build proficiency at as your practice.
- Build and form strategies for when users are not forthcoming with information, resistant or reflect questions back at you. Remember, any user experience researcher can get caught out if that's the user's intention in the interaction. 


### Time management strategies for user interviews

- Setting timers or allocating certain time for questions can help you keep track of what timings you are working with.
- Ensure that the timings don't interfere with the user's natural behaviour and responses.

### Recording, taking notes and data collection

- What's most critical is that you capture data of some sort, be it video, audio, written or a combination of these.
- You can choose to add tags or themes to notes as you capture the data but it's not a strongly advised requirement at the data collection stage.
- One of the ultimate purposes of interviews is about gathering enough information from outside your own experience in order to make well-informed decisions.



:::::::::::::::::::::::::::::::::