# Weekly Diary - Noah Håkansson

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
| Group/Pair programming                          | 2     | 100        | Helped out some people in the group with react and the components they where working in. Namely the start menu and log table.                                      |

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
