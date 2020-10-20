# Joseph Lyman

## October 19, 2020 - Faculty Advisor Meeting: Subcontractor Comments, Requirements Feedback, Research Suggestions, Modeling Suggestions

### Subcontractor Comments

* Do not let things get too complex, so that incorporating a Subcontractor detracts from our original plan. 
* Focus on creating:
   * A letter of understanding
   * Systems-level description of interfaces between our work and Subcontractor work. Minimize these to basic interfaces
* Do **not** provide a recipe, but rather a list of expectations
* Identify the specific subsystem for the Subcontractor work to focus on.
* Do **not** put excessive work on ourselves for defining the requirements associated with the power subsystem. This is a special situation considering the requirements from ECE 4900 and what is expected of Senior Projects
   * Some requirements that need to be identified by the Subcontractor should answer:
      * will the system control battery so it will shut off before draining?
      * what DC inputs should we be considering?

### Requirements Feedback

* (1-5) Prioritization is very important. Never going to be perfect, so focus on those higher priorities.
* Consider the use of "may" or other language to specify requirements that are rather desired features or possibilities
* What we previously identified as "environmental factors" are actually **operational conditions**, update accordingly
* ^ That being said, add an **environmental factors** section which addresses:
   * sand ingress
   * temperature
   * humidity
   * *may* want to consider FCC requirements in this discussion
* For **power requirements**
   * Specify *power quality* i.e. not "ringy", no "overshoot"
   * Safety, Weight, and Size are important factors
   * While researching *batteries*, include:
      * lifespan
      * implications of full discharge
      * can it sit out in the sun?
   * Set the standards, including those for *safety*
 
### Research Suggestions

* Recognize that the weight of the system will be determined by three components:
   * battery
   * speaker driver magnets
* We had previously identified **deliverable associated with each research suggestion**:
   * one powerpoint slide which summarizes research
   * within this slide, identify the associated **key assumptions** and **key performance characteristics**
* In order to *start formulating the subsystem diagrams*, **this deliverable** should include:
   * an initial high-level diagram of the relvant subsystem
* **concern: Bluetooth Streaming may not be possibly**... Can we explore alternative technologies?
   * Free-air optical transmission is possible... but lose the standards, lose the Commercial Off-The-Shelf (COTS) support
      * Omnidirectional IR Blaster
      * Would become a project in and of itself
   * **Look into LiFi** - is there anything to learn from this?
   * Transmitting at different frequencies? ISM Bands?
   * In any case, the question becomes *How to strike a balance with existing systems that can be easily integrated into our desing with minimal effort*

### Modeling Suggestions

* We will eventually break down the **High-level diagram** into subsystems... This can start taking place during requirements research^
   * For the "Control" block, this may include a *microcontroller* for managing customer inputs
* We must **keep all modeling efforts uniform** so that when our individual work is put together, it looks coherent
   * should not have inhomogenous diagrams
   * may want to specify standards for creating models
   * should use the same tool for creating these across all of our work
      * draw.io is good for drawings
      * on-shape is good for physical, 3D models
      * should have integration into Google Docs for easy collaboration
* For **Speaker drivers**
   * there are a lot of parameters you can ignore... or that will be determined by other constraints ( size, weight, cost )
   * You may want to consider 3D printing enclosures
   * Consider competing products: weight, size, drivers
   * could look into Bose's complex enclosure which achieves a "larger" effect in a smaller form factor.

## October 13, 2020 - Technical Advisor Meeting: Incorporating Subcontractor and Prioritizing Requirements

### Incorporating Subcontractor
We discussed with Mr. Paul white on how to incorporate a third party into our project, another student who will be focusing specifically on the Power System Design. The main points of this discussion were:
1. It is of utmost important to establish a **Subcontractor Statement of Work**.
1. It is especially important with a subcontractor to **have complete, fully-specified requirements** that are clearly relevant to the statement of work
1. Establish **milestones** which coincide with the progress necessary for successful project
1. It is appropriate to use **ranges** in place of fully-specified requiremenents; if you expect that requirement to change or need flexibility in the subcontractor's design.

Some more finer details we discussed were the specific relationship of the subcontractor in the project. We are serving as the project engineers, who have direct and utmost responsibility with the customer. We are held accountable for any and all work, including that of the subcontractor. For that reason, the Statement of Work is extremely critical to success. To the subcontractor, we are their customer and the statement of work must serve to **clearly outline the scope of their work** including a schedule and standards of work. We must decide to either provide the subcontractor with the freedom to develop their own process for completing the work, or that may be defined by the Statement of Work. In either case, **it is important to clearly communicate and agree upon the process**. Even if the subcontractor is working on their own process, this should be documented and agreed upon.

If a requirement which has been handed off to the subcontractor changes, we must:
1. notify the individual
1. get feedback from the subcontractor in terms of expected schedule change or cost change
1. Decide if the change is worth it

It is important that, as the one making changes, we offer flexibility for the subcontractor to absorb that change. If the subcontractor is requesting change, it is at our discretion whether or not to offer flexibility. 

### Prioritizing Requirements

According to the customer, each requirement should be given a priorty ranking according to a proper scale (1-5, least-most priority). It is then our job to devise a scheme for determining the complexity of the requirement: How long will it take to complete the associated work? This question can be answered by a weight factor (0-1 most-least complexity), then an **absolute priority** is obtained by multiplying the priority by the weight factor. 
e.g. if a requirement is of utmost priority to the customer, but impossibly complex, the absolute priority = 5*0 = 0, and will be near the bottom of the rankings.

If something like in this example occurs, that is the customer has high priority, but the requirement is very demanding on the development team, we can account for this with the absolute priority and communicate this concern to the customer. One possiblity is that, if the requirement can be broken down further, the corresponding physical component can be broken into smaller pieces that, collectively, take a long time to complete, but are individually digestable within our capability.

## October 7, 2020 - Start of Sprint 3

Last time we cleaned up the tasks that were on Sprint 2, removing those which our industry advisor Paul identified as unnecessary at this moment in time. 

Today, I created a new project Kanban board for Sprint 3, and realized that perhaps what we should have done was *not* made any changes to Sprint 2 project, but instead create this new one for Sprint 3... That way, we can visually see in the GitHub Project tab that we had unfinished tasks in Sprint 2, which were left uncomplete because they were low priority at that time. This may be something to keep in mind moving forward, that **it may actually be helpful to keep as much information as possible** rather than deleting anything. We create a new sprint project and move forward, but can look back when it is relevant to see exactly what we had set aside!

## October 6, 2020 - Individual Presentation Feedback/Requirements Research Areas for Sprint 3

### Individual Presentation Feedback
Items to fix in our Individual Design Presentations/*also applicable to Project Overview*
1. Put Advisors on Title Slide
1. Acknowledge our customers
1. Include a final slide with images of the team/contact info

Tips for presentations
1. Sticky note by camera to encourage you to look at it.

Items to Improve on
1. It is still confusing what the division of responsibility is in the project. **create a clear, concise diagram to depict this**. Dr. Rasmussen's suggestion is to update the high-level block diagram with indicators of which subsystem is under whose responsibility. We may even relate this to our existing team diagram

### Requirements Research Areas

We took the requirements feedback from advisors (October 5th) and developed a list of research areas which will further develop these requirements more specifically **to be unambiguous and testable**. These research areas are summarized in our [Requirements Research Objectives](https://docs.google.com/document/d/1mivIBVqfgy0YCjiVbYlZA_OXDGn95niegF6tkLaUonk/edit?usp=sharing).

Another note is that we previously realized our original division of responsibility was premature and not evenly distributed in work load. We are thinking that, by organizing the requirements into distinct groups, that these categories will become a *new* set of responsibilities that are more evenly distributed.

## October 5, 2020 - Requirements Feedback from Advisors

Today, we met to review comments that our Technical and Faculty advisors offered on our Requirements Outline from the last sprint. The most prominent feedback stems from a lack of technical knowledge on our part. So, *it should be our priority in the net sprint to flush out technical ambiguities*. More general notes are
* **All requirements should be testable**
* **Requirements are still ambiguous and need to be further refined. Further research will uncover more requirements**

More specific comments can be found in the [Initial Requriements Outline](https://docs.google.com/document/d/1bQqTBTZVdF1-LQCF3sIWCffZA2er5Wri69iT8PXGsEc/edit?usp=sharing)

## September 29, 2020 - Customer Review Meeting #2

During this last sprint, we took the original features that we had identified with the customer and mapped them into requirements.During this Customer Review Meeting, we discussed these requirements with the customer to refine them into agreement among all stakeholders. These requirements are summarized in the [Inital Requirements Outline](https://docs.google.com/document/d/1bQqTBTZVdF1-LQCF3sIWCffZA2er5Wri69iT8PXGsEc/edit), and will be continued to be refined through further sprints/feedback.

## September 16, 2020 - Customer Review Meeting #1

Today we had our first customer meeting. We introduced the project from its socio-political implications of restoring human modes of interaction with shaping the world they live in.

Through a conversation with customers we identified a particular technological direction, is driven by the desire to add flexibility in modern DJ'ing. See the details [here](https://uu-agile.github.io/hear-yourself/CRM1).

## September 13, 2020

**SCRUM Meeting**
1. What I did yesterday.
I finished summarizing risks in terms of triggers, impacts, and responses. I started describing standard SE processes and the product development process. I have been working on defining my individual milestones.
1. What I will do today.
I will finish a lot. I plan to finish a discussion on the benefits of Agile including its social implications. I plan to reate the block diagram of our process & platform. I will finish a description of how to adjust schedule and budget according to our risks.
1. What is standing in my way.
Still, I am finding myself over-fulfilling each task. I need to get more comfortable producing the minimally functional solution.

## September 12, 2020

It is difficult to come up with appropriate responses to risk factors. Sometimes I come up with a response and it seems more like something to do now in anticipation rather than as a response to the risk as it arises... *Is that the point?*

## September 11, 2020

I am having trouble keeping up with my tasks. I have a tendency to over-design/over-think, so I am finding myself spending hours researching just *just risk factors* alone.
    * I think a much better approach is to quickly accomplish tasks **with the goal of a minimally-functional solution**
    * This is in fact one of the principles of Agile...makes sense :)
    
*Note: We may want to put the DUE DATE in our Sprint title of GitHub*

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
