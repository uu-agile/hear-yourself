# Joseph Lyman

## September 10, 2020

Ooh you can filter Kanban boards by assignee name: "assignee:j-lyman"

**SCRUM Meeting, Duration: 8 Minutes**
* What I did yesterday.

I reveiwed our Assignment 2 document, and converted my action items to Issues in GitHub. Two action items that I have since added are Project Definition Statement and Risk Management Plan. I finished the Definition Statement yesterday.

* What I will do today.

I have decided that, with 10 open issues, if I finish 3 each day I can complete by Sunday. Today I will work towards ID risks and suggesting a RMP
1. Outline factors which could change our project (scope, features, etc)
1. Summarize the associated risks in terms of their impacts, triggers, and our response.
1. Describe imapcts to our schedule.

* What is standing in my way.

I cannot think of anything.

We will take tomorrow off and meet again for SCRUM meetings Saturday and Sunday both at 11:00 A.M.




## September 9, 2020

We decided on *three global milestones*:
1. Integrated Management Plan
1. Design & Testing
1. Implementation & Reflection

**At the end of this sprint, we should answer in reflection:**
1. Was the use of GH "Projects" to track Sprint progress effective?
1. Was the use of GH "Milestones" to track Milestone progress effective?
1. What did we think about the labels? Could they be used more constructively?
1. Were there any features about the Task Management process that could be added/improved?
1. What was your biggest barrier/slowdown this sprint?
1. Overall, what can we change about the way we plan/execute/track a Sprint? Will this change with feedback inputs?

Today my main achievement was to convert my action items as outlined in today's team meeting to Issues in GitHub. This was ultimately very helpful for realizing the level of work to be done and putting it into perspective, because it gives me a simple task to do while my mind can wander on those action items and how I might respond.

I found that the easiest way to convert was to create a separate Word document where I will write the text blocks associated with each action time, breaking them into chunks that I would generally say take anywhere from 15 minutes to an hour. Although at this moment, it seems pretty arbitraty to define.

It is diffucult to marry the complexity of action items to the duration of the sprint/magnitude of the deliverable. There should be an optimum balance between information tranparency and simplicity.

It seems that one added benefit of this process is that Yusaf and I are able to leverage our own work strategies and organization practices. So long as we can transparently display our progress, systematic coherency is possible. In a way, this enables a self-regulatory response to the issue described above. 

In order to give Yusaf admin capabilities, I forked the "hear-yourself" project from my personal account and it is now associated with an organization, "uu-agile." The task management methods that I devised yesterdays still apply. I demonstrated this workflow to Yusaf and we agreed that we will use it for one week with a *trial sprint*.

This trial sprint will have the Project Overview as deliverable (Due Monday, Spetember 14th **by 5:00 P.M.**) and tasks that we outlined in our [Assignment 2](https://docs.google.com/document/d/1_UEt8V5hJuX-R8StRv7V6QATfcV-3DKuZ1dPLVP2kH4/edit?usp=sharing) document. Tomorrow we begin with our first SCRUM meeting. The SCRUM meeting will only be 5 minutes long, and each member must briefly state:
1. What I did yesterday.
1. What I will do today.
1. What is standing in my way.

When we finished our team meeting today, we decided that the answer to "What I did yesterday" will be to convert our action items (as outlined in Assignment 2) to "Issues" that may be utilized within our task management workflow. The answer to "What I will do today" depends on those action items as assigned to us and what we have time for. I'm not sure at this moment that anything is standing in our way.

However, I do feel some things uncomfortable already:
1. The integration with GitHub to Discord is annoying and not very useful. I was making frequent changes and was being bombarded with notifications as I made them. This is not a bad thing, but I was not finding it useful. I especialy think that if we want the Discord server to become a hub for feedback from our stakeholders that we should make all notifications meaningful... As a team, the notifications could be more intense, but I really want to focus on *graphical* task management. It would be nice to be able to check with one glance the progress of our current sprint, milestone, and Kanban board.
1. I am finding it somewhat cumbersome to deal with the webpage as a hub. I forget the URL, it changed a bunch since I forked the repository, etc. But now I *hope* the repository details are somewhat fixed. To combat the cumbersomeness, I have added the project webpage as the default starting point when I open my browser.
1. I like that the webpage files are stored in a separate branch, "gh-pages," but it is already tricky for me to assign scope. I mean that the main repository should have documents such as team journals, etc. BUT I had to move these into "gh-pages" branch to get them to display as webpages. **Perhaps I can find a way to display 'main' files even if the webpage is hosted from "gh-pages"???**

## September 8, 2020

### Google Docs Landing Page

Today I worked mostly on creating a landing page for our Google Documents. I added this to our webpage. I would like for the webpage to become the main "hub" for this project. This is where customers may suggest features, access meeting scheduling, observe design progress. This is where engineers can quickly navigate to any design-related documents, graphics, etc. This is where project managers, professors, and other stakeholders can check on progress/catch errors.

The [webpage](https://uu-agile.github.io/hear-yourself/) is organized as follows:
* Homepage (README.md) 
 * About Us
 * Documents (to google docs)
 * Team Journals

 I have not yet linked the journals. I want to make sure Yusaf is aware of this integration. I think
 
 ### Organizing and Visualizing Progress
 
 I also worked on the process and strategy behind assigning "cards" in the "Projects" Tab of GitHub. After exploring how to best utilize that feature, I have devised the following which is up for revision:
 * Projects are used to track the progress of *sprints*. The duration of sprints may change, they are faster-moving and are used to digest the goals and objectives within each **milestone**. Sprints should also have deliverables.
 * Milestones are used to track our progress through the Product Development Cycle. These are longer-term: Program Planning, Design & Verification, and Implementation. These can be defined in terms of deliverables. Milestones are identical to those used in ECE 4900. *Note:* Milestones are tracked in the "Issues" tab of GitHub, just to the left of "New Issue".
 * Labels are used to track deliverables.
 
 *When properly set to Automated* the Projects will automatically track Issues as new "cards" which are placed on a Kanban board. This is our workflow surrounding Issues, Projects, Milestones, Labels.
 1. *Project meetings* - We identify all **Issues** (action items) related to our current **Sprint**, assign those **Issues** to team members, and identify which deliverable (**Label**) they relate to.
 1. At the end of team meeting, we add these **Issues** in GitHub so that tracking will begin automatically
 1. When we individually start working on our assigned **Issues**, we must manually move the associated cards from "To-Do" to "In-Progress". This can be found in the "Projects" tab of GitHub.
 1. When we finish an **Issue**, we do not need to move the card into "Done". That **Issue** is closed by the assignee, and GitHub will automatically move the card to "Done"
 
 In this way, the Projects tab will be the forefront of tracking progress of tasks as they relate to sprints. The Issues tab will be where we mostly interact with these tasks (because comments can be exchanged, discussions, etc. within an Issue). Also in the Issues tab we can observe the progress toward our current Milestone. 

## September 7, 2020

Today Yusaf and I finished our first assignment for Senior Capstone class. We have a good, basic meeting organization that includes:
* weekly team meetings
* weekly advisor meetings (which alternate bi-weekly between Jon Davies and Paul White)
* daily SCRUM meetings

I think the most difficult part will be learning GitHub fast enough that we are able to leverage its functionalities to the fullest potential. I am confident that this challenge will not be too much of a blockade, since Yusaf and I are already learning quickly about how to use GitHub.

I have also created a Discord server for the project. I think this would ideally be a great way for users and engineers to interact with the project/each other whenever. I have organized the roles as follows:
* admin - the only role which may make changes to the server
* engineers - have access to team communications
* users - have access to everything except team communications

We can only see how strongly this is utilized once the project is underway. It was quick to create, and potentially useful.

**Some things to remember**
* **We are *Agile*... we are NOT confined to one workflow, team management scheme, communication platform**
* **Do not rush into design or implementation. The Systems Engineering framework is there to digest the project thoughtfully**
* **I want to develop the project's website more.**
  * right now, we have a basic high-level overview of the project.
  * I would like this website to be the easiet way for Yusaf and I to navigate the project's documents, and an approachable way for the public to observe and track our progress.
  * I like [this project's page](https://prodfreebies.github.io/)
  * Add: link to project journals
  * Add: Link to Documents landing page
  * Add: link to Discord server
