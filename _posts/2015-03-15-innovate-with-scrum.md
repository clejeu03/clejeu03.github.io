---
layout: post
title:  "Innovate in a R&D team with the Scrum Method"
date:   2015-03-15 01:00:00
date:   2015-03-15 01:00:00
excerpt: "In RIT Paris, we use an adapted Scrum Method to manage our development. Here is why we decided to use it and how to adapt the standard Scrum to a Research and Development process like we have. ..."
categories: methodology
tags:  project management, scrum method, R&D
image:
  feature: mickey-1929.jpg
  topPosition: -50px
bgContrast: dark
bgGradientOpacity: darker
syntaxHighlighter: no
---
In RIT Paris, we use an adapted Scrum Method to manage our development. Here is why we decided to use it and how to adapt the standard Scrum to a Research and Development process like we have. 

### Why we decided to use Scrum ?
The Agile Methods are used by many developers worldwide, in small teams as well as in very big teams. Those methods have proven themselves efficient for the developers, for the clients and for the manager to get the product delivered in time and accordingly to the client's need. The Scrum Method is the most known among those Agile Methods. The iterative aspect of this method allow the team to be flexible and to respond to change in times and to provide high quality with a smart prioritization of tasks.

There are three pillars that need to be reminded to every member of a scrum team :
- The Feedbacks : the continuous measure of progresses is the key to find a match between user requirements and the team capacities
- The Demos: each and every sprint must be closed with a visual/runnable demo so everyone, client and team, can see the work's progresses
- The Cross-Functionnal Team : every member is involved from the beginning to the end of the project, regardless of his skills and background

``` In this post, I will not detailed what is Scrum and how it works. I will focus on its adaptation for the needs of a R&D team, and assume you are familiar you the vocabulary and the process.
There are plenty of resources all other the web about Scrum that you can visit if you are interested. For example :
 - [a very complete pdf guide](http://scrumreferencecard.com/ScrumReferenceCard.pdf) by Michael James
 - [a series of introduction videos to Scrum](https://www.youtube.com/watch?v=D8vT7G0WATM) by Collabnet
 - [the official website about Scrum Method](https://www.scrumalliance.org/why-scrum)
```

### Prior to a new Scrum process
It all begins with an idea, right ? In RIT we decided that if a member have a new idea, then this member becomes automatically Project Manager of this project. Scrum is meant for teams approximately from 3 to 8 people, so you can't launch your project alone. 

#### 1. Determine the roles

** The Product Owner (PO) - the What **

He is interfacing the Team with the Client, if he exists. If not, he defines what the project should do and show. He has the role of an external point of view on the project. And he works with the Project Manager and the Team so the Product Backlog reflects the needed features. It is his responsibility to consider which activities will produce the most business value, but he is not a developer in that project.

** The Project Manager (PM) - the How **

Project Manager is the leader of the development team, and often the creator of the project. In Scrum process, the Team manages itself, but the Project Manager has a vision of the project, that he assess with the Product Owner external insights. He is the technical leader of the project, and a developer on it.

** The Scrum Master (we don't use that role) **

The Scrum Master does everything he / she can to facilitate productivity, to help the team perform at their highest level. This involves removing any impediments to progress, facilitating meetings, and doing things like working with the Product Owner to make sure the product backlog is in good shape and ready for the next sprint. He is often seen as a coach for the Team.

#### 2. Do the State of the Art
The idea is a good first step, but in research as in private societies, the next steps will be to do a State of the Art to know the market, the concurrents, what has been done and what is missing.
In research area, that part can take several months depending on the scientific domain, the type of project and many other factors. And it is not compatible with an iterative process like Scrum.

#### 3. Define the MVP
Knowing the scientific history and business status around the project, it is time to define a product. The goal is the get the Minimum Viable Product definition and from that to draw the list of the required features for the "product". Is the Project Manager doing that work alone ? We advise people to find some advisor among their colleagues to regularly report to, so in case of loss of track, or unpredicted issues, the researcher is not by himself and can get a fresh view from this advisor. 

>The **Minimum Viable Product** is a Lean Startup concept. It is aimed to solve customer’s problems with very basic design and functional features. The point of successful MVP building is to maintain balance between usability and efficiency. More about it in this article from which I have taken the following picture.

With that definition under the shape of a list of feature you want your product or demo to have, then you are ready to prepare the Rakuten tool to the sprint.

### The Sprint Planning
At the beginning and the end of each sprint, the planning and the retrospective meetings are mandatory for every member of the Team, and the Product Owner and Project Manager. What is concretly a Sprint Planning meeting content :
1. The Product Owner has updated the priority of the User Stories before the meeting
2. Each Team member present its availibility for the coming sprint (ex : "i will be 50% on this project only")
3. The Project Manager takes the highest User Storie in the Product Backlog and detail it the entire Team, answer questions if there are.
4. Then the Team breaks down the User Story into small measurable technical tasks and the Project Manager writes them all 
5. All together they estimate the tasks
6. If the Team decides they can commit to all those technical tasks (considering the avaibility of every one), then the Project Manager go on with the second User Story.
7. The Team draw the line when they feel they will not longer commit to complete the tasks
8. The Sprint is planned
9. The project Manager defines a clear goal for the sprint, a deadline, and a meeting place for the demo

### Setup the board
At RIT we use JIRA for project management and issue tracking, like all Rakuten teams. The track progresses on all the Scrum project of a team, we set up a JIRA dashboard. If you look for the "RIT Paris Dashboard" among the dashboards you can have the following screen :
<div class="img img--fullContainer img--14xLeading" style="background-image: url({{ site.baseurl_posts_img }}jira.png);"></div>
This display our burndown charts for every project and the current status of all the project of the team. Thoses charts are directly linked the Story Point with which we estimate the tasks.

### The Story Points VS the Man-Hour
<div class="img img--fullContainer img--14xLeading" style="background-image: url({{ site.baseurl_posts_img }}story-point.png);"></div>
We decided to use the abstract Story-Point. A good key to correctly estimate tasks is to pick the biggest and the smallest tasks : they will be markers to size the backlog, respectively of 1 to 8 or 13 story points. Other tasks are relative.

> The most tricky part for us and still the most important thing to remember is : a Sprint cannot be changed once its started