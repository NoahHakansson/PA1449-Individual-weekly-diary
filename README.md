# Weekly Diary - Noah Håkansson

## WEEK: 18

### This week: 10h

- Meetings/Group work 4h
- Individual work 6h

### Total in project: 328h

### ACTIVITY/TASKS & RESULT

| Task                                             | hours | Progress % | Result                                                                                         |
| ------------------------------------------------ | ----- | ---------- | ---------------------------------------------------------------------------------------------- |
| Work on task MAX-143 Fix PowerSlider             | 4     | 20         | Made progress on the PowerSlider issue but not completed yet.                                  |
| Bug fixes for logo and log-component positioning | 2     | 100        | Fixed positioning issues with the logo and log-component that were noticed during our meeting. |

### PLANNED ACTIVITIES/TASKS AND PROGRESS NEXT WEEK

| Planned task                          | Planned Progress % | Planned result                                                                                             |
| ------------------------------------- | ------------------ | ---------------------------------------------------------------------------------------------------------- |
| Planning of week 19                   | 100                | Discuss the progress of the past week and assign tasks from the sprint backlog to each member of the team. |
| Continue task MAX-143 Fix PowerSlider | 60                 | be mostly done with the powerslider fixes. To the point where it can start being tested for quality.       |

### PROBLEMS & SOLUTIONS

During week 18, my focus was mostly on my thesis, which took up a significant amount of time. As a result, I didn't make as much progress on project tasks as I would have liked. However, I managed to work on MAX-143 Fix PowerSlider and made some progress, though it is not completed yet. I also fixed a few bugs related to the positioning of the logo and log-component that we noticed during our meeting on Friday.

### REFLECTION

Week 18 was a bit slow in terms of project work, mainly due to my thesis taking up most of my time. I managed to work on task MAX-143 Fix PowerSlider and addressed some bug fixes related to the positioning of the logo and log-component. Next week, I plan to continue working on the PowerSlider issue.

## WEEK: 17

### This week: 24h

- Meetings 3h
- Group work 4h
- Individual work 17h

### Total in project: 322h

### ACTIVITY/TASKS & RESULT

| Task                                             | hours | Progress % | Result                                                                                        |
| ------------------------------------------------ | ----- | ---------- | --------------------------------------------------------------------------------------------- |
| Continue and finish frontend component (MAX-153) | 17    | 100        | Completed the CityOverview frontend component after addressing design concerns with the team. |
| Help a team member with task (MAX-84)            | 4     | -          | Assisted a team member in progressing with their task.                                        |

### PLANNED ACTIVITIES/TASKS AND PROGRESS NEXT WEEK

| Planned task                        | Planned Progress % | Planned result                                                                                             |
| ----------------------------------- | ------------------ | ---------------------------------------------------------------------------------------------------------- |
| Sprint planning for the last sprint | 100                | Define the goals and assign tasks for the final sprint of the project.                                     |
| Planning of week 18                 | 100                | Discuss the progress of the past week and assign tasks from the sprint backlog to each member of the team. |

### PROBLEMS & SOLUTIONS

This week, I focused on finishing the CityOverview frontend component (MAX-153). I faced challenges in handling references to many dynamically created objects in React, something I hadn't done before. I had to refactor my implementation multiple times until I was satisfied with the quality. The problem was specifically related to referencing these dynamic components from various places in the code.

After some back-and-forth with the team regarding the design, I was able to complete the component as planned.

I also helped a team member with their task (MAX-84) at the start of the week after our meeting on monday.

### REFLECTION

Week 17 was mostly about individual work, except for the meeting on monday, as valborg occurred this weekend, we had no meeting on friday. I managed to finish the CityOverview frontend component (MAX-153) after addressing design concerns and overcoming challenges related to handling dynamic objects in React.

As we enter the last sprint of the project next week, we'll have a sprint planning meeting to define our goals and assign tasks for the final phase. I'm excited to work with the team to wrap up the project on a high note.

## WEEK: 16

### This week: 25h

- Meetings/Group work 9h
- Individual work 12h
- Pair programming 4h

### Total in project: 298h

### ACTIVITY/TASKS & RESULT

| Task                                                 | hours | Progress % | Result                                                                                    |
| ---------------------------------------------------- | ----- | ---------- | ----------------------------------------------------------------------------------------- |
| Small refactoring and cleanup of the backend system. | 2     | 100        | Made minor improvements to code quality, readability, and maintainability. Pending merge. |
| Work on frontend component of CityOverview (MAX-153) | 5     | 40         | Basic layout and functionality implemented, ongoing work.                                 |
| Help groupmate on task MAX-84 (pair programming)     | 4     | N/A        | Provided assistance and guidance in the development of the frontend settings component.   |

### PLANNED ACTIVITIES/TASKS AND PROGRESS NEXT WEEK

| Planned task                                       | Planned Progress % | Planned result                                                                                             |
| -------------------------------------------------- | ------------------ | ---------------------------------------------------------------------------------------------------------- |
| Continue CityOverview frontend component (MAX-153) | 90                 | Have the component mostly complete and ready for code review.                                              |
| Planning of week 17                                | 100                | Discuss the progress of the past week and assign tasks from the sprint backlog to each member of the team. |

### PROBLEMS & SOLUTIONS

This week, I made some small improvements to the backend system by refactoring and cleaning up the code. Although these changes were minor, they still contributed to a better codebase. Unfortunately, the merge request for these changes is pending due to a GitLab issue that occurred on Friday. We plan to discuss this issue with the company on Monday to find a solution.

During the development of the CityOverview frontend component (MAX-153), I encountered some challenges, but progress has been made. The task is still ongoing, and I will continue working on it in the coming week.

In the pair programming session, I helped a groupmate with their task (MAX-84) concerning the frontend settings component. This collaboration helped advance the task.

### REFLECTION

Even though the refactoring and cleanup of the backend system involved only minor changes, it still contributed to an improved codebase. However, the GitLab issue prevented me from merging the changes, which is something I plan to address with the company on Monday.

My primary focus this week was on the CityOverview frontend component (MAX-153), where progress has been made, and I will continue to work on it in the coming week, aiming to have it 90% complete and ready for code review.

The pair programming session allowed me to support a groupmate with their task (MAX-84) and foster a collaborative environment. This experience shows that teamwork and knowledge sharing are essential for the success of our project.

## WEEK: 15

### This week: 13h

- Meetings/Group work 6h
- Individual work 7h

### Total in project: 273h

### ACTIVITY/TASKS & RESULT

| Task                                          | hours | Progress % | Result                                            |
| --------------------------------------------- | ----- | ---------- | ------------------------------------------------- |
| Work on task #97 Fix power and damage system. | 3     | 100        | Merged MRs after some small changes after review. |

### PLANNED ACTIVITIES/TASKS AND PROGRESS NEXT WEEK

| Planned task        | Planned Progress % | Planned result                                                                                         |
| ------------------- | ------------------ | ------------------------------------------------------------------------------------------------------ |
| Planning of week 14 | 100                | discuss how last week went, and assign tasks from out sprint todo/backlog to each memeber of the team. |

### PROBLEMS & SOLUTIONS

We had some discussions about what is important or not to do in this next sprint as, we are pretty much done with our commitment other than the AI, part. Which is almost there. And the built out damage system with a lot more depth, than the current `if (power < neededPower) takeDamage(10);`, this is not a MVP requirement but something which would be very nice and give the simulation a more real feeling and not so static. So we decided this was a big priority this sprint. As well as general UI improvements, adding some new icons for different power plant types, and introducing a wind power plant that will have its power delivery dependent on a new variable in the simulation, wind speed. There weren't really any problems as everyone agreed on this being the most important things to work on next.

### REFLECTION

We discussed about our next sprint and did some planning. It went well and we have a good plan for the next sprint and a backlog of things and an idea of what we will do on the last sprint as well, so we are ready when its the last 3 weeks for us to work on the project, so we finish it up properly and look for any remaining weirdness/bugs etc...

## WEEK: 14

### This week: 20h

- Meetings/Group work 2h
- Individual work 16h
- Pair programming 2h

### Total in project: 260h

### ACTIVITY/TASKS & RESULT

| Task                                          | hours | Progress % | Result                                                                  |
| --------------------------------------------- | ----- | ---------- | ----------------------------------------------------------------------- |
| Work on task #97 Fix power and damage system. | 3     | 18         | Task is now finally finished, reviews, and merged into the main branch. |

### PLANNED ACTIVITIES/TASKS AND PROGRESS NEXT WEEK

| Planned task        | Planned Progress % | Planned result                                                                                                                                |
| ------------------- | ------------------ | --------------------------------------------------------------------------------------------------------------------------------------------- |
| Planning of week 14 | 100                | discuss how last week went, and assign tasks from out sprint todo/backlog to each memeber of the team.                                        |
| Sprint planning     | 100                | Do sprint planning for the next sprint on thursday as the holidays messed with our schedule, and thursday is the first day we can all fit in. |

### PROBLEMS & SOLUTIONS

Finally fixed and merged fixes for the biggest main feature of the system, the power distribution and related to that the damage system. After making it work, I instantly noticed how I can make it better, now that I made it work and understand how its working I can make improvements to the implementation to make it less confusing for everyone else. The first solution had a lot och recursive functions, which in this system is hard to avoid as some objects, cities, can have cables that have cities, that have cables... and so on. So my first solution was to recursively go through all cities and cables when something was needed to be done. Which worked, but can be very hard for other members of the team and also KnowIT, to understand when it's time for them to take over the system. So after some changes, the simulation now keeps a list of all the cables, and a list of all the cities. So that we can easily just iterate over them when we need to check cities buildings damage etc. While the power distribution is still kept somewhat recursive as it needs to propagate throughout the system step by step.

### REFLECTION

Very productive week, and I think we are now in a much better spot to continue developing as the main backbone of the system that everything else depends on is in place. Now we can start to actually run the simulation, play around with templates/scenarios(different setups of cities and powerplants and cables) to see what works and is good for the user. Before we could only guess what might work. But now we can finally test and see what actually happens. We will be improving the damage system to be more realistic, which is something we could not start until the power distribution and super basic damage was done. So I am looking forward to actually play around with the simulation now and really see it come to life in the next sprint.

## WEEK: 13

### This week: 30h

- Meetings/Group work 5h
- Individual work 22h
- Pair programming 3h

### Total in project: 230h

### ACTIVITY/TASKS & RESULT

| Task                                                    | hours | Progress % | Result                                                                                                                                                                                                                                        |
| ------------------------------------------------------- | ----- | ---------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Work on task #97 Some bugs appeared since last week.    | 3     | 80         | Some bugs appeared during the review process and then after that i have been playing whack-a-mole with new bugs appearing after every other bug I fix. task #110 also exposed some bugs, but now I am pretty sure I got only bug left to fix. |
| Work on task #110 Multiple powerplants in a simulation. | 3     | 100        | Simulation should support multiple powerplants in a simulation that can connect to many cities. It's done, but as mentioned, revealed some bugs in the underlying power and damage system, which is good.                                     |

### PLANNED ACTIVITIES/TASKS AND PROGRESS NEXT WEEK

| Planned task                                                                                                                                                                                                                                                                                                                                                                                                                       | Planned Progress % | Planned result                                                                                                                                          |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Planning of week 14                                                                                                                                                                                                                                                                                                                                                                                                                | 100                | discuss how last week went, and assign tasks from out sprint todo/backlog to each memeber of the team.                                                  |
| Add more integration tests for issue #95 and fix the templates for simulations, as we planned that when the damage system was implemented we would notice that the simulation templates where not made in a good way, without actually seeing what happens in the simulation (damage, power draw depedning on temperature etc...) And this was as we planned the case, so finish up that part of this issue, to fix the templates. | 100                | New good templates that actually work and are "playable" where the user can do changes and not just instantly lose because there is never enough power. |

### PROBLEMS & SOLUTIONS

As mentioned in the tasks section problems existed because of faulty code, not implemented following the design of the system. This was solved by rewriting it from scratch, by me and 2 more members. More rigorous testing and more strict quality control should be done before a new features code is accepted. As this code that was wrong was still reviewed and at first accepted by me and one more member as it looked good to us in the moment. This is therefore also our fault not noticing this sooner so that it could of been reworked instantly by that person submitting the code, instead of us noticing after.

### REFLECTION

I think this week we really took planning more seriously and I think it has helped with keeping us more organized and being much clearer what we need to do, you have a clearer picture if what needs to be done. We also adopted story points after our review meeting. As we have a gap in experience of the technologies we use, some take longer and some take a shorter time to deliver the same work. And story points feel like they will give us a good way to estimate complexity and how long a task will take depending on the person. We just need to get through or first sprint with story points to see what our velocity will be and what each members velocity will be as well. Then we will be able to plan even better coming weeks and sprints being able to estimate tasks much better based on our teams velocity.

## WEEK: 12

### This week: 35h

- Meetings/Group work 8h
- Individual work 21h
- Pair programming 6h

### Total in project: 214h

### ACTIVITY/TASKS & RESULT

| Task                                                                                            | hours | Progress % | Result                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| ----------------------------------------------------------------------------------------------- | ----- | ---------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Work on task #79 refactor backend; To refactor the structure of classes and how cables connect. | 3     | 100        | Cables are not held by either a powerplant or city, and the cable then keeps track of what city it is connected to and delivers power to the city, cities can then deliver to it's connected cables cities to enable serial connections where cities have cables with cities, than themselves can have cables with more cities and so on...                                                                                                                                                                                                                                                                                                                                  |
| Work on task #60 deep copy classes in TypeScript.                                               | 3     | 100        | Becuase of how JavaScript and therefore TypeScript works, deep copying class objects is not as trivial as just creating a copy. As any non trivial variables like numbers and string, wont get copied and instead a reference will be created. So functions for each class was implemented to make deep copying of that class possible, so no references are created for new simulations to old simulations and everything goes crazy.                                                                                                                                                                                                                                       |
| Work on task #38 Health bar for cities in frontend.                                             | 8     | 100        | Create a health bar for the frontend, so each city has a health bar above it that slowly animates going down when a building in the city takes damage. Also displays the cites health and max health in the health bar. Additionally added that when a building in a city is destroyed it's image gets set to grayscale, to visually show that it's destroyed to the user.                                                                                                                                                                                                                                                                                                   |
| Work on task #65 fix frontend to work with serial connected cities.                             | 3     | 100        | How the frontend currently extracts cities and cables from the `tick` and templates it gets sent from the backend was not working with serial connnections where cities can have cables with cities that can have cables with more cities etc... So we reworked the frontend to recursivly extract cities from these JSON objects, so we can display everything correctly. Also keeping track of each cables . Additionally added that when a building in a city is destroyed it's image gets set to grayscale, to visually show that it's destroyed to the user parent(powerplant or city) so we know where it should connect to in the calculations of the cable graphics. |
| Work on task #97 Rewrite backend power distribution and damage system.                          | 6     | 100        | The current implementation done was not done properly as discussed or follwing how the system is supossed to work, so it did not work at all. As this feature is already late, because of previous issues with computers breaking and bad communication with the rest of the team about it. It was therefore completely Rewritten by me, with the help from 2 other members during our friday group work/study session together, to make sure it is working properly for the customer on monday so we can finally show that it is working and we have implemented one of the key and most important features of the system.                                                  |

### PLANNED ACTIVITIES/TASKS AND PROGRESS NEXT WEEK

| Planned task                                                                                                | Planned Progress % | Planned result                                                                                                                                                                                                                                                       |
| ----------------------------------------------------------------------------------------------------------- | ------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Planning of week 13                                                                                         | 100                | discuss how last week went, and assign tasks from out sprint todo/backlog to each memeber of the team.                                                                                                                                                               |
| Meetings with teams about how buildings should take damage and maybe heal when they get enough power again. | 100                | We should of decided and sketched out and documented how this kind of things should happen, and have researched some things like how long houses can stay without power, hospitals and indutrsy in the real world so we can use this information for our simulation. |

### PROBLEMS & SOLUTIONS

Some people were sick this week and we didn't have to much to discuss on Monday, so we have all just been hard at coding, trying to work through our sprint backlog.

### REFLECTION

Has been a productive week for me, even tho i have spent more time on the issue i have than i thought, the product will benefit from more through testing and as this system is the base and most important part of the whole system i don't mind if it takes a bit longer to finish, most important is that it is as correct as we can get it. Before we start adding even more things too it, and things will be even harder to fix or maintain.

## WEEK: 11

### This week: 26h

- Meetings/Group work 12h
- Individual work 14h

### Total in project: 179h

### ACTIVITY/TASKS & RESULT

| Task                                                                                                  | hours | Progress % | Result                                                                                                                                                                                                                                                                                                                                   |
| ----------------------------------------------------------------------------------------------------- | ----- | ---------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Work on task #79 floating text with powerplant KWh                                                    | 2     | 100        | Frontend now shows a floating text with KWh.                                                                                                                                                                                                                                                                                             |
| Work on task #100 and #101 to send settings object from frontend and take in settings to the backend. | 9     | 100        | Now settings type exists in both back and frontend and we can send a whole settings object that the user will be able to change in the future to the backend and it can start a simulation with these settings at the moment only seed can be changes by the user, and a EasySettings object exists in the frontend that is the default. |

### PLANNED ACTIVITIES/TASKS AND PROGRESS NEXT WEEK

| Planned task                                                    | Planned Progress % | Planned result                                                    |
| --------------------------------------------------------------- | ------------------ | ----------------------------------------------------------------- |
| Planning of week 12                                             | 100                | Assign tasks from out sprint backlog to each memeber of the team. |
| Refactor code to actually deep copy class objects to fix a bug. | 100                | All buggy copies of objects should be fixes using lodash.         |

### PROBLEMS & SOLUTIONS

As was discussed in the hod meetings we have an issue with having enough time to plan our sprints properly and we don't write enough descriptions for tasks so they are clear and it's easy to understand what to do. We will try to split up out creating tasks to pairs and then go through them together after to be more effective and do more parallel work.

### REFLECTION

There are a lot of things about our team that works well and I think everyone is motivated to do a good job, and that is why we have still managed so well since everyone is trying their best and working hard. But we are not as effective as we could be and if we had better planning I think we could be a really effective team.

## WEEK: 10

### This week: 25h

- Meetings/Group work 6h
- Individual work 19h

### Total in project: 153h

### ACTIVITY/TASKS & RESULT

| Task                                                                                                                              | hours | Progress % | Result                                                                                                                                                                                                                                                                             |
| --------------------------------------------------------------------------------------------------------------------------------- | ----- | ---------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Work on task #69 sending ticks containing the game state and not just a number as before.                                         | 10    | 100        | Backend now sends a snapshot of the simulation state to the frontend each tick so the frontend can reflect changes in the UI.                                                                                                                                                      |
| Work on task #44 using the game ticks send in the frontend to show information about the simulation such as temperature and more. | 9     | 100        | Frontend now shows ticks elapsed vs max ticks which is gotten from the backend each tick, temeprature and current power production is also displayed in the UI. Types in typescript for a simulation tick are implemented to make developing easier for other members of the team. |

### PLANNED ACTIVITIES/TASKS AND PROGRESS NEXT WEEK

| Planned task        | Planned Progress % | Planned result                                                    |
| ------------------- | ------------------ | ----------------------------------------------------------------- |
| Planning of week 11 | 100                | Assign tasks from out sprint backlog to each memeber of the team. |

### PROBLEMS & SOLUTIONS

Lots of things that were placeholders in the backend and frontend had to be changed and things had to be reworked and re implemented in both. As everyone else was implementing things based on the state of the project before i had to rework everything, it was quite a lot of work to merge and sometimes change their code to work with the new way. But integration hell is not something that cannot always be avoided and sometimes we just need to "waste" some time on merging a bunch of code when a lot of things change at once.

### REFLECTION

I had a productive week, and i think the same goes for my team. I had some personal things going on with my grandmother being in the hospital and was not able to go to our Friday meetings because of this. But my group kept me up to date in our discord.

## WEEK: 9

### This week: 21h

- Meetings/Group work 9h
- Individual work 10h
- Pair work 2h

### Total in project: 126h

### ACTIVITY/TASKS & RESULT

| Task                                            | hours | Progress % | Result                                                                                                                                                             |
| ----------------------------------------------- | ----- | ---------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Work on task #9 slider component for powerlines | 10    | 100        | Started work on and finished a slider component that popups when clicking a powerline and allows the user to change between 0-100 % power deliviery on that cable. |
| Group/Pair programming                          | 2     | 100        | Helped some people in the group with react and the components they where working in. Namely the start menu and log table.                                          |

### PLANNED ACTIVITIES/TASKS AND PROGRESS NEXT WEEK

| Planned task              | Planned Progress % | Planned result                                                                                                                                                                                          |
| ------------------------- | ------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Planning of week 10       | 100                | Plan our week together on our monday at KnowIT offices, and what each person will be doing during the next week. And how last week went for everyone and if there is something someone needs help with. |
| Demo with customer monday | 100                | Get some feedback from the customer and see what we should focus on next week, if the demo lives up to expectations.                                                                                    |

### PROBLEMS & SOLUTIONS

No real problems this week, everyone worked very well and we got a lot of stuff done in my opinion. Can not really complain.

### REFLECTION

Again I think we had a good productive week which is becoming a bit boring to say every single week. But I really think that this group is filled with motivated and good people that all want to do their best to contribute and do a good job, Attendance for meetings could be better for some members. But no one is not doing work and contributing with code towards a completed product which is still great.

## WEEK: 8

### This week: 23h

- Meetings/Group work 12h
- Individual work 7h
- Pair work 2h

### Total in project: 105h

### ACTIVITY/TASKS & RESULT

| Task                                                     | hours | Progress % | Result                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| -------------------------------------------------------- | ----- | ---------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Work on issue #26 base implementation of backend classes | 7     | 70         | Started on implementations of the classes what will be the actual simulation objects, like powerplant, buildings, cities and cables. Have encountered some problems as expected as we can not perfectly design how this big system will operate and do it in a smart way without starting to write code, I have had discussions with the rest of the team about descisions I have made and asked for advice, most basic things are implemented in the classes so that we can in future tasks continue and implement all of the advanced logic on a solid fundation of how everything is going to communicate and work. There are still some descisions about how the system will communicatate that we will have to discuss in future weeks. And that will probably change when we continue building the system as always happens, but that is why we work with agile development as it is almost always impossible that the first implementation of something is perfect and doesnt need changes. |
| Group work                                               | 6     | 100        | We took friday to prepare for our demo on monday with the customer coding together reviewing merge requests in GitLab and pair/group programming our way to a finished demo connection all the seperate frontend components to a working demo.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |

### PLANNED ACTIVITIES/TASKS AND PROGRESS NEXT WEEK

| Planned task                     | Planned Progress % | Planned result                                                                                                       |
| -------------------------------- | ------------------ | -------------------------------------------------------------------------------------------------------------------- |
| Planning of week 9               | 100                | Plan our week together on our monday at KnowIT offices with the customer                                             |
| Demo with customer monday        | 100                | Get some feedback from the customer and see what we should focus on next week, if the demo lives up to expectations. |
| Fix some bugs in the frontend    | 100                | At the moment there are some small visual bugs in the frontend that needs to be sorted out next week.                |
| Create start menu for simulation | 100                | Now we dont have a start menu and instead you instantly get to the simulation page.                                  |

### PROBLEMS & SOLUTIONS

There are visual bugs and some weirdness in the react frontend, as someone with more experience in react, that are obviously wrong or badly implemented, but this is to be expected as people are completely new to react they have to of course learn. But as people get more used to it and how to work with it properly I think that things will improve over time and things like this wont happen as much.

### REFLECTION

This week was very productive, a lot of people did a lot of good things. We made some good progress in our understanding of AI and how we are going to tackle using RL for training an AI to play with the simulation. We had a lot of progress with our design in the frontend and implemented the design we had in Figma very well. Some things are of course only placeholder or non functional at the moment, but that is to be expected. I personally worked a little bit with the rest of the team helping with React and the frontend in out group work meeting on Friday as I have some experience with react i wanted to let others work in it now in the beginning to be able to get an understanding from the ground up. I worked on making some basic classes with the easy functions implemented that we had decided on and to leave the rest empty, and some functions that we obviously need are not added at the moment. They will be in future sprints by other team members as we split up work on different classes and parts of the backend. But it's good to have a basic skeleton to work from. And also helps us visualize what we will need to implement and change in our backend design and logic to make the simulation work and communicate in a smart and effective way, that wont be impossible to maintain and update with new functionality.

## WEEK: 7

### This week: 23h

- Meetings/Group work 13h
- Individual work 4h
- Pair work 6h

### Total in project: 82h

### ACTIVITY/TASKS & RESULT

| Task                  | hours | Progress % | Result                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| --------------------- | ----- | ---------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Setup CI/CD           | 3     | 90         | CI/CD is done, only some small changes will be needed, after we implement testing in the frontend repo. Setting up CI/CD went pretty smoothly as I have done it before many times on GitHub, but as this was on GitLab it required a little bit of reaserch before implementing it. But it was pretty straight forward and easy.                                                                                                                                                                        |
| Random generator/seed | 7     | 100        | A class was created that provides functions for generating random numbers that are deterministic as JavaScript has no seeded deterministic random generator built in. Most of the time went to reaserch on good random generator algorithms and hashing algorithms to hash the seed. But overall the result is a very good random generator for the purpose we need it for of being able to generate random events in the simulation, that can be seeded to always generate the same events every time. |

### PLANNED ACTIVITIES/TASKS AND PROGRESS NEXT WEEK

| Planned task                         | Planned Progress % | Planned result                                                                                                                                                                             |
| ------------------------------------ | ------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Planning of week 8                   | 100                | Plan our week together on our monday at KnowIT offices                                                                                                                                     |
| Implement hashing of settings object | 100                | A settings JSON object from the user should be hashable by this class or function/s so user settings can be easily saved in the users URL in one hashed string containing the JSON object. |
| Demo with customer monday            | 100                | Get some feedback                                                                                                                                                                          |

### PROBLEMS & SOLUTIONS

This week went on quite smoothly as we all did work in pairs, the problem that appeared this week was to make our random generator give satisfactory results. We tried a few different ways to generate number, but found that we would get the same results regardless of seed after a while because how we were manipulating the seed to generate a different number each time the random function was called. The thing that caused this was the hashing algorithm we had chosen at first was hashing the seed, and was generating to similar results. After switching out the hashing algorithm with another one, that is more robust and that also allows for a seed in the form of a number we could provide a number each iteration and generate a different hash from the same seed. Giving us faster performing and more robust randomness.

### REFLECTION

This was a interesting week a it was the first week of our team actually writing code, so now we could actually see how all our preparations have gone. We also decided to do our first sprint in pairs (pair programming), and I think this was a very good decision as the experience level in the group is as any group varying, so we can easier keep track of progress of 5 pairs compared to 10 Individuals, as well as the pairs hopefully keeping each other in check. I think this has worked out well, and we had a good first week of the sprint, where we managed to deliver on what the customer asked for to be done for a demo on Monday next week. Since we decided early on that we would require code reviews and try to involve everyone in all code that is written to spread knowledge of the codebase and make sure everyone know what Is going on. I personally learned a few nice things about JavaScript/TypeScript as how the socket.io websocket library works from doing code reviews of other members code. And by requiring that we all write tests for all features we implement I had a chance and will continue to learn about the jest JavaScript/TypeScript testing framework as the course goes on. Relating to the quality assurance lectures, definition of done was mentioned, which is something we use in our issues/tasks in GitLab, which is very nice when developing to have clear definition to refer too, to assure that the feature is implemented properly.

## WEEK: 6

### This week: 21h

- Meetings/Group work 16h
- Seminar 3h
- Individual work 2h

### Total in project: 59h

### ACTIVITY & RESULT

We created a risk analysis on Monday and continued on requirements and creating our backlog. The rest of the week was mostly continuing work on our backlog to prepare for sprint 1. We did also meet on Wednesday with a guy studying the AI program to have some discussions about how we can train our AI, what model to use and other things, he provided us with some good resources.

### PROBLEMS & SOLUTIONS

Again we had some problems with GitLab, we started out using issues and in the issues creating tasks. But we noticed the tasks are quite limited in what you can write in them. and assigning of tasks in a issue is not great. What we found instead is milestones that can contain issues. So we converted our big issues into milestones and our tasks into issues in this milestone instead.

### REFLECTION

Same as last week I think it was a productive week. I feel like we are quite well prepared for sprint 1.

## WEEK: 5

### This week: 16h

- Meetings/Group work 11h
- Lego 4h
- Individual work 1h

### Total in project: 35h

### ACTIVITY & RESULT

This week we continued on creating issue and tasks for our backlog. We finished the main issues for our MVP. Next week we will continue breaking these issues into smaller tasks. And assign them to the team for sprint 1.

### PROBLEMS & SOLUTIONS

We have had some issues with GitLab and their boards and backlog features, but after some looking around we have managed to find a nice way to work with it.

### REFLECTION

Was a good and productive week, we are almost done with preparations so that we can hit the ground running on sprint 1.

## WEEK: 4

### This week: 19h

### Total in project: 19h

### ACTIVITY & RESULT

We all joined a discord server group together and started talking and getting to know each other. Worked on canvas assignments. We have contacted the customer and decided what time a meeting would work for all of us. We had a meeting at their office this Monday and stayed there working together and discussing our assignments and presentation. Me and the other requirements engineer wrote down some requirements based on the small amount of verbal info we have gotten so far from the customer, and we are planning to discuss this at our next meeting next Monday. We also had our team and LeSS presentation. Lastly on Friday we all gathered in Space lab and discussed all the requirements together improving and adding a lot if information. We also started discussing some libraries and technologies that we are going to use. As we are going to use `Node.js` and we need web sockets we have decided on the `socket.io` library.

### PROBLEMS & SOLUTIONS

We had some problems deciding what language we wanted to use. At first we decided to use GoLang as it was stated as one of the options in the first document from the customer. But then they said we can't use GoLang and have to choose between JavaScript and Java. We were split on this decision, so we took a vote and JavaScript won with 6/10 votes.

### REFLECTION

I think we have had a good and productive week considering it is only they first week, we have gotten to know each other better and laughed a lot which I think is very important if we are going to work together for 6 months as a successful team.
