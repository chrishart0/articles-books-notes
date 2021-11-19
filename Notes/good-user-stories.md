# Good User Stories

## What is a User Story

Simple, it is the story of a user. A user story is a description of a change in function to a system which is always described from the perspective of the user. 

Here is another way to phrase it: "A user story is simply a description of a change in system behavior from the perspective of a user. It describes something a user wants to do with the system or wants the system to do for them that it doesn’t do today." ([Richard Lawrence](https://www.humanizingwork.com/the-humanizing-work-guide-to-splitting-user-stories/))

User Stories describe customer journey and document business value. 

User stories are not a list of technical tasks which need to be accomplished in order to achieve business value, user stories describe that value from the perspective of the customer. "It’s a description of a person wanting to accomplish something in your system." ([Richard Lawrence](https://www.humanizingwork.com/the-humanizing-work-guide-to-splitting-user-stories/))

### The 4 questions

User stories answer 4 questions
* Who wants the thing?
* What do they want?
* Why do they want it?
* How do I know when I'm done implementing the thing?

Note that no where in the user story are there are requirements for how to implement the user story. A user story **should not describe implementation details**, just functionality.

#### Story Formats

There are a few formats that help us to answer these questions. 


##### Narrative
Typically there will be a narrative to answer *who, what and why* then Acceptance Criteria to answer *how do I know I'm done*.

> As a... (who)
> I want... (what)
> So that... (why)

or 

> In order to... (why)
> AS a... (who)
> I want... (what)

What template is used by the team is not important. What is important is that the who what and why are answered.

**Example**

## INVEST

INVEST are a set of criteria which describe a good user story. 

* Independent
* Negotiable
* Valuable
* Estimable
* Small
* Testable

## Vertical Slices

All the work required to deliver an increment of  value, this is what a vertical slice is. That may mean touching many layers of the application or it may mean only touching one layer, whatever is required to deliver value.

"A work item that delivers a valuable change in system behavior such that you’ll probably have to touch multiple architectural layers to implement the change. When you call the slice *done*, the system is observably more valuable to a user." ([Richard Lawrence](https://www.humanizingwork.com/the-humanizing-work-guide-to-splitting-user-stories/))

What we can contrast vertical slices with horizontal slices. A horizontal slice is an increment of work divided along lines of the architecture which, when finished, is not independently releasable. 

![Layers Shrek](assets/good-user-stories/Vertical-Slice-Shrek.png)
![Vertical Slice 1](./assets/good-user-stories/Vertical-Slice-1.png)
![Vertical Slice 2](assets/good-user-stories/Vertical-Slice-2.png)

Remember the INVEST criteria. In order to make all stories valuable vertical slicing is requisite. 

Not all INVEST criteria are made the same. In the beginning, there was independence and the devs negotiated the best solution with the customer, and it was good. Then sprint planning came, and independence, Valuable, small, and testable became most important, and the negotiableness was lessened, and it was still good.

The point is, the further out a story is from being started, the less details we want. As the team gets closer to picking up a story, they need to be working out the technical details and having the needed conversation with the customer and business to assure there will be no blockers when the story is picked up. In this way, the story is highly negotiable in the beginning, as the story gets closer to being started the story become less negotiable but an accurate estimate become more reasonable and the ability to deploy the story independently and delivering value becomes more possible.

### Example 1

As a user customer of Starbucks
I want to order a drink with 30 ingredients
So that I can make a Tick Tok to show it off

## Story Splitting

As I see it, our goals are twofold:
* Fast feedback
* Small, iterative releases of value

Story splitting is a critical tool in achieving these goals. Story splitting allows the team to get small stories, allowing us to achieve those goals. 




More Resources
* [The Humanizing Work Guide to Splitting User Stories](https://www.humanizingwork.com/the-humanizing-work-guide-to-splitting-user-stories/)

Job stories as an alternative to user stories
https://www.mountaingoatsoftware.com/blog/job-stories-offer-a-viable-alternative-to-user-stories