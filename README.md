# Council-Note-PartA

## Description

### Purpose

The CouncilNote app will enable users, such as residents, workers and council staff, to report problems in a council area, and keep other users updated. Examples of problems can include "street lights out" on a certain road, "tree down" on a certain footpath, overgrown weeds, rubbish dumped in a wrong location, parking issues, or lost pets. CouncilNote will also feature a Notices section for users to post about activities, events and other fun happenings in the council area.

CouncilNote will be particularly useful for large council areas, in terms of population and land area, such as in London, Sydney, New York, and the Shire of East Pilbara, which has the largest land area in Australia, larger than Victoria and Tasmania combined. With CouncilNote, council staff in Newman, WA, and others across the area, can be informed about problems and hazards happening on roads hundreds of kilometres away, for instance. For London, for example, Notices can be posted about the latest exhibitions, street markets and music events, as there is always something happening in London.

### Functionality and features

- It is intended for council staff, such as a council representative, to be authorised as admin, and have some moderation control over users' posts, such as for in case posts are inappropriate or illegal, according to the relevant laws. A council staff rep can delete users' posts if they are deemed inappropriate or illegal.

- Every user of CouncilNote will Register and Login in order to use this app, which can help ensure the legitimacy of users and their posts and comments.

- Every user will have their own UserProfile, MyProfile, which will include an "about" section which can be filled in and edited by the user, and users can upload a profile photo of themselves. UserProfiles will include a list or record of recent Problems and Notices posts by users. Hence, with the UserProfiles, users can know about regular contributors for instance, and some of the topics of their posts. Functionality for users to close their account may be included on MyProfile in future.

- There will be CRUD functionality on all Problems and Notices posts, and comments on posts will be deleted when the posts are deleted.

- The Problems and Notices pages will feature pagination to allow users to search for previous posts, and each post will display the date it was added.

- The Problems and Notices pages will each feature an input form for users to submit their Problem or Notice. Users will firstly input a title and description of the Problem or Notice.

- On Problems and Notices posts, there will also be the ability for users to upload a photo related to the Problem or Notice.

- Problem posts will also feature coloured symbols, Red and Yellow, to indicate whether the Problem is Urgent or should be dealt with Soon. Users will select either of these, as relevant, before submitting a Problem form. 

- Problem posts will feature a comments section, such as for users to indicate the status of the Problem. Likewise, Notice posts will feature a comments section, such as for users to keep updated on the latest happenings.

The designs of the Problems, Notices, and MyProfile pages, as displayed in the Wireframes, are partly based on personal experiences of using bulletin boards and blogs pages, such as those which feature an input form which slides up from the bottom of the page, both for adding and editing posts. There is a bulletin board I use which also features a profile page of each user, which includes a list of their recent posts. So some of these features and designs are intended for CouncilNote.

Below are some examples of the Urgent and Soon symbols I intend to try out and implement during development of this app, whichever looks and works the best on the Problem posts.


#### Yellow Square symbol

![Yellow Square](./docs/yellow-square.svg)

#### Red Square symbol

![Red Square](./docs/Red-Square.svg)

#### Red Dot symbol

![Red Dot](./docs/Red-Dot.svg)

#### Yellow Dot SOON symbol

![Yellow Dot SOON](./docs/SOON-yellow-dot.svg)

#### Yellow Square SOON symbol

![Yellow Square SOON](./docs/SOON-yellow-square.svg)

#### Red Dot URGENT symbol

![Red Dot URGENT](./docs/URGENT-red-dot.svg)

#### Red Square URGENT symbol

![Red Square URGENT](./docs/URGENT-red-square.svg)

### Target audience

The target audience of CouncilNote is anyone who lives and works in a particular council area, and who is interested in this source of communication and information. The target audience can include council staff themselves, along with residents and other workers in that council area.

### Tech stack

- Front-end: React is used to faciliate the client-side logic of the application, including the  components which handle the sending and retrieval of data to and from the back-end. HTML, CSS Bootstrap, and Javascript are implemented to facilitate responsive designs and features for the users.

- Back-end: Express.js, Mongoose and Node.js are used to handle the server-side logic of the application.

- Database: MongoDB is used to store data of Users, including their login information, the UserProfiles, Problems, Notices, and Comments.

- Testing: Insomnia and Jest

- Project Management: Trello, Notepad file

- Source Control: Git, Github

- Deployment: Netlify or Heroku

## Dataflow Diagram

When drawing up this dataflow diagram, I endeavoured to follow the conventions of dataflow diagrams, mainly Yourdon and Coad, along with my ideas and understanding of the app structure so far.

![Dataflow Diagram](./docs/dataflow-diagramEdit1.png)

## Application Architecture Diagram

![Application Architecture](./docs/Application-architecture1.png)

## User Stories

The users of CouncilNote will be council staff of whichever council wants to use this app, anywhere in the world, along with residents and other workers in that area.

#### Council Staff
- As a council staff member, such as a Mayor or Councillor, I want to receive information and updates about certain problems from residents and workers in my council area.

- As a council staff member, I'd also like to hear about the events, activities and other fun happenings in my council area, via the Notices posts and comments.

- As a council staff member, I'd like another way to inform residents and other workers of council initiatives, via the Notices posts and comments.

#### Residents

- As a resident, I want to be able to inform and update people on certain events and activities I'm hosting in the council area, via the Notices posts and comments.

- As a resident, I want another way to know about upcoming events and activities nearby, via the Notices posts and comments, and I would like to know about other locals, via their UserProfile information.

- As a resident I want to be able to directly inform council staff and others of problems I encounter in the area, such as street lights not working, lost pets or fallen trees.

#### Other Workers

- As a worker, such as a business owner, I want to be able to inform council staff and others in the council area of certain problems, such as with managing parking or rubbish.

- As a worker, such as a restaurateur, I would like another way to inform people in my area of certain events and promotions at my business.

- As work crew member, I can keep council staff and residents up to date about certain problems which are being solved or handled, via the Problems posts and comments.

## Wireframes

I have drawn up the wireframes in this Miro board, to the best of my understanding of React Bootstrap so far, and how the app will piece together accordingly:

https://miro.com/app/board/uXjVLAhsPcw=/

#### Mobile: Login, Create Account, Problems

![Mobile1](./docs/CN-mobile1a.jpg)

#### Mobile: Nav Hamburger, Problem Form, Notices

![Mobile5](./docs/CN-mobile5.jpg)

#### Mobile: View UserProfile, Notice Form, Notices Comments

![Mobile6](./docs/CN-mobile6.jpg)

#### Tablet Login

![Tablet Login](./docs/CN-TabletLogin.jpg)

#### Tablet Problems

![Tablet Problems](./docs/CN-TabletProblems.jpg)

#### Tablet Notices

![Tablet Notices](./docs/CN-TabletNotices.jpg)

#### Desktop Login

![Desktop Login](./docs/CN-desktopLogin.jpg)

#### Desktop MyProfile

![Desktop MyProfile](./docs/CN-desktopMyProfile2.jpg)

#### Desktop Problems page with comments

![Desktop Problems Comments](./docs/CN-desktopProblemComments.jpg)

#### Desktop Problems Form

![Desktop Problems Form](./docs/CN-desktopProblemForm.jpg)

#### Desktop Problems page

![Desktop Problems](./docs/CN-desktopProblems2.jpg)


## Screenshots of Trello board

I have used Trello to plan and keep track of the stages of development of this app in the coming weeks, such as when certain stages should be achieved and completed by.

#### Trello Overall

![Trello1](./docs/Trello-overall.png)

#### Trello Dataflow Diagram

![Trello2](./docs/Trello-CN2.png)

#### Trello Application Architecture Diagram

![Trello3](./docs/Trello-CN3.png)

#### Trello Wireframes

![Trello4](./docs/Trello-CN4.png)

#### Trello Starting Coding

During the week of 17 Nov to 24 Nov 2024, I started some coding, at least trialling, of the frontend and backend to see how this MERN app will piece together and work, and to have some ideas for the Dataflow Diagram, Application Architecture Diagram and Wireframes.

![Trello5a](./docs/Trello-CN5a.png)

![Trello5b](./docs/Trello-CN5b.png)

![Trello5c](./docs/Trello-CN5c.png)

#### Trello Successful Deployment

![Trello6](./docs/Trello-CN6.png)
