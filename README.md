# Note for Agile SDLC

## Agile 4 Values

- Individuals & Interactions > Processes & Tools.</br>(Good relationship is more important than what tool they using to comunicate).
- Working Software (existance and working functionality) > Comprehensive Documentation (Sequence Diagram, UML Diagram, etc)</br>so developing the software should have more time and higher priority than writing the documentation.
- Costumer Collaboration > Contract Negotiation</br>(Team don't reject to client adjustment but still search way to collaborate with the client so we not build the product from scrath again).
- Responding to Change > Following a Plan</br>(e.g. changing tool if necessary even it not on the plan).

## Agile 12 Principles

- Satisfying the customer is highest prioirty.
- Develop software frequently with intervals between few weeks/few months.
- Working software is the primary measure of progress more than comprehensive documentation.
- Compete with other competitor by welcoming change requirement, even late in development.
- Code should be scalable and maintainable to allow rapid and continuous updates.
- Agile avoids idle time by involving all teams early — unlike waterfall where some teams wait for others to finish.
- Don’t build unnecessary features — even if it’s easy — unless the client needs it.
- Give the team environment and support they need, and trust them to get the job done.
- The team assign task to it self so they don't wait the manager to do it (the manager don't involved in everything).
- Business people and dev team must work together to give best solution for the business.
- Face to face conversation like pair programming or daily meeting.
- Always look forward performing in a better way. That why we have meeting called restrospective and Sprint Review.

## Comparison Flow Between Waterfall vs Agile

### Waterfall

1. Fixed Requirement
2. Estimate Resource
3. Estimate Time

### Agile

1. Fixed Resource
2. Fixed Time
3. Estimate Features

## User Story

    User stories are written to capture requirements from the user, 
the user stories must address both functional and non-functional characteristics.

## 5 Agile Requirement

### Theme

A Scrum theme is the highest level of the story hierarchy.</br>
A product owner further breaks down a theme into one/more epics.</br>
For example:

- theme for increase sale
- theme for get higher rating on the application store
- theme for have more number of repeat customer.

### Features

Feature is new capability provied to costomer.</br>
Feature Larger than the epic and the user story.</br>
For each theme we have more than one feature which will achieve the goal of each theme.</br>

### Epic User Stories

Medium size requrements that are decomposed from a feature.</br>
For example we have feature called manage profile data,</br>
we might have more than one epic that help the user manage the profile data.

### User Stories

Epic might require 2/3 or even 5 days of effort,</br>
however the user story should fit within single day.</br>
User story should finished within 2 or 4 hours for example.</br>

On the other hand, the feature might take one week or two weeks and</br>
the theme might be extended up to one month or more. So the user story is a</br>
requirement that contains a single action only.

### User Tasks

Actions required to develop a requirement of user story,</br>
those tasks should cover all aspect of:

- User Story
- Development
- Integration
- Deployment

Those task will be performed by moe than one team.

Not all agile project include those 5 type of requirement,</br>
for example in Jira only have user stories, epics, version and tasks.

## Practice Agile using JIRA

### Selecting Story Work Type

#### Bug

Tester write problem in the software for the developer to solve.

#### Task

Anything to be assigned to the team.

#### Story

Large user story, for example user story that should be done in 2 hour.

#### Epic

User story that need 40 hour of work to be implemented will be called Epic,</br>
an Epic can have many user stories that implement this Epic.</br>
For example: login functionality is an Epic.</br>
Epic not stored in backlog because backlog only store user stories.</br>
Before click the create button, we can check the create anoter button to create multiple user story with same Epic parent.

## Terms Used in Agile Scrum

### Sprint

For example project have fixed length 3 month,</br>
that project can be divide into 3 or 6 iteration.

### Product Increment

Each sprint results in a potentially releasable product (called an increment).
</br>Looping flow:

1. Build
2. Measure
3. Learn

### Product Backlog

The product owner manage priority list of planned product items.</br>
The product backlog evolves from sprint to sprint.

### Sprint Backlog

The product backlog written by product owner but</br>
the person who decides which user stories will be added to the sprint backlog is</br>
the whole team.

### Definition of Done

Definition of Done is list task that must be</br>
finished in order for this sprint to reach it's goal.

### Timeboxing

Inside sprint, you should only add task to the sprint back log if</br>
you expect can finish it. If not then the task</br>
moved back into the product backlog.</br>

#### PLanning Poker

We can do timeboxing by using planning poker at the beginning of the sprint.</br>
So the plan poker is an activity in which we give some point to each story,</br>
the point given by:

- Product Onwer
- Scrum Master
- Developer
- Tester

Each one of them separately chooses a point, this point represents</br>
the complexity and time of this user story. If they all agree on the same point,</br>
then this is the estimate of this user story.</br>

Plan poker point mostly follow fibonacci sequence.</br>
The smallest user story has an estimate of 1, for example: Contact Us Page.</br>
Then 2, 3, 5, 8, 13, 20 and so on, if > 20 than it called</br>
an epic and need to be divided into smaller user story.</br>

#### Only Time

Another way is estimate tasks only using time.</br>
For example: 1 hour, 2 hour and so on.</br>

Both of the way is correct.

### Tranparency

The dev team should report and update the sprint status on a daily basis at daily scrum meeting.</br>
Each team member explain the work yesterday what he is going to do today.</br>
And if there is any problems within that block of work.

## Scrum

Most companies that use Agile also use Scrum.</br>
Scrum Roles:

### Product Owner

Considered as the representative of the customer and also do backlog management.

### Scrum Master

Accountable for establishing Scrum as defined in the Scrum Guide.

### Development Team

Team who develops and tests the software.
