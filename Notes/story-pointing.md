# Stories
![Big Brain](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/wotel6xfxfmjwdodwyii.jpeg)

*Realistic representation of how you will actually look when you finish reading this article and show off your story pointing knowledge to your friends, family, and co-workers.*

### Preamble
[Cross-Post from Medium Post](https://medium.com/contino-engineering/you-are-using-story-points-wrong-how-to-make-story-points-suck-less-c641c34ce63)

Amongst people in the software industry there is a lot of confusion around story points. This blog is my summary of great minds opinions on the topic of story points with some of my own opinions throw in as well.

Story points are part of scrum, right? No. Go read the scrum guide([link](https://scrumguides.org/scrum-guide.html)) yourself, there is no mention of story points or even user stories. Don't adopt story points as a default, adopt them because they are solving a problem. 

The goal of this article is not to give the reader a set of hard rules. Instead, the reader should work to understand this as a starting point and then evolve into what best suits the team.

Got a question or disagree with something? Leave it in the comments. 

## What are Story Points?
Story points are an *arbitrary*, *imprecise*, and *relative* estimate of *effort*, *complexity*, and *uncertainty*.

### Relative
Story points are relative to previously sized stories. 

![Big Brain Relative vs Small Brain Time](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/7ickrb9ilgl19lieyrya.jpeg)

### Arbitrary
A team invents their own pointing system. The first story sized is given an arbitrary point value as decided by the team, from then on stories are sized in relation to that story. 

This means that the first sets of stories won't be as useful as they have nothing to be relative to and many assumptions have to be made. The first stories are intended to be the first step in making future relative decisions, so this is okay.


### Size Parameters
What goes into a size?
* Complexity
* Uncertainty
* Effort

Learn from the past to improve future estimates!

### Story Points are Not
* Estimate of time
    * Very difficult to estimate time, hard to get right
    * Story points trade off precision to make estimating easier 
* Exact end dates
* Exact time spent
* Time tracking
* For comparing team's output
    * Story points are, by definition, relative and unique to each team 
        * Thus, comparing one team's velocity to another team's velocity is pointless(*pun intended*)
    * Once points leave a team they are useless

## Why Story Points?
Story points are an imprecise forecast of a team's capacity/velocity, helping to develop shared understanding, and useful in negotiating task priority.

Before deciding to use story points it is crucial to have a good understanding of why you want to use them. What benefits will the team get from story points? What are the downsides? 

Nowadays(2021), many experts recommend not using story points at all. Mostly, this sentiment comes from companies being tempted to weaponize story points against their developers. [Read more about the no story points debate here.](https://rigidity.medium.com/agile-waste-story-points-pt-1-a9df2572d0a3)

Why should we use story points? Why not just estimate time?
* Cost of estimation is low
    * Imprecise, allows us to more quickly make estimations
* High accuracy and low precision
    * Relative sizing requires less effort to be accurate than time based estimations
        * Asking how complex / effortful is this thing compared to that thing is much easier than estimating how long it will take
    * Imprecision of story points allows for quick estimation


### Purposes
*Please note that this is a contentious topic, there is debate on what all uses story points should be put.*

#### Negotiating Priority
* "If you want A by the end of the month then we are going to have to push B until next month."
* Stops the team from committing to doing to much in a period(iteration)
    * A metric to be used to push back against excessive work and prevent burn-out
* **Helps the team to say no**
    * "Provides healthy boundaries for the team"
    * Be careful not to show the numbers, they are for the product team's use only
        * Don't allow story points to be turned into a currency
* Useful for using stories on a [prioritization matrix](https://www.atlassian.com/team-playbook/plays/prioritization-matrix)

![Dilbert priorities comic](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/xwcwuvrzgmjs8g5d3e3d.gif)

#### Shared Understanding
* If a story is sized, it shows the team has developed a shared understanding of what it will take to complete it
* Story points are a prompter for conversation to get the whole to understand what will go into completing the task
* **"What are you thinking so I can think like that?"**
    * Get in the same head space about everything which will go into a story
        * Example: 
            * John: "This is about a 1, we just need to make a quick update to the Shaw-Fujikawa Translight function."
            * Jill: "You're forgetting we have not implemented automated testing for rupture generation, this will be a 3."

#### Slicing Signal
A signal that a task has not been broken down enough
* "That is a lot of points, has this been broken down enough?"
* "Can this fit into the iteration?"

## How to use Story Points

- Make sure to remember the first few iterations the estimates will be highly inaccurate, over time this will improve
- Map story points to approximate effort/complexity/uncertainty

### Story Pointing Frameworks
There are a number of frameworks for story points. 

Here are a few, listed below:

- T-shirt sizes (S, M, L, XL) (easy to start with)
- Integers: tools like Jira can provide burndown charts, scope creep indicators and other metrics when using integers
    - Standard: (1, 2, 3, 4, 5, ect)
    - Fibonacci-style scale (0, 1, 2, 3, 5, 8)
        - Fibonacci-style scale without 2 (0, 1, 3, 5, 8)
            - "Less is more"
        - Why use Fibonacci? [Here is a good article](https://www.mountaingoatsoftware.com/blog/why-the-fibonacci-sequence-works-well-for-estimating)
- Time based (antiquated, not recommended)
    - **Caution:** these are not recommended for reasons documented elsewhere in this article
        - [Read more here on why story points are better than time](https://www.scruminc.com/story-points-why-are-they-better-than/)
    - Time
    - [Ideal Time](http://www.extremeprogramming.org/rules/iterationplanning.html)

#### Tips for Choosing a Framework
Items to consider when the team is deciding on their story pointing framework

#### Less is more
You don't want to allow for too many options, this will lead to analysis paralysis. Remember, story points are meant to be imprecise, we don't want to spend too much time trying to pick the perfect number. 

We are trading off precision for ease of use on purpose. 

#### Upper Limit
Decide on an upper limit of effort/complexity (e.g. your team may decide that for them a 13 is "too large for one feature/story")

If a story breaks the upper limit then it needs to be broken down into smaller pieces. 

#### Have it your way
Teams should pick their own standard, it shouldn't be imposed by anyone else. Remember, story points are to be used by the team for themselves. 

### Planning for new teams
![Dilbert estimation comic](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/6kecfosbqyrbqjo31p7o.jpeg)

When a new team comes together their estimates will be difficult to agree on and very uncertain, that's okay, they don't have a point of reference yet.

Find 1-2 well defined/known stories and understand "what a 1 vs 3 vs 5 looks like". Once the team has these stories, they can start to use *relative estimation*.

#### Golden Story
Some teams use what is called a *golden story*. This is the first story estimated for a product. It is then used as a point of reference throughout the lifecycle of the product. 

For another take on golden stories checkout [this article on the Blizzard Computing blog](https://medium.com/r/?url=https%3A%2F%2Fblizzardcomputing.com%2Fwp%2Fblog%2Findex.php%2F2016%2F06%2F27%2Fwhy-estimating-stories-in-agile-is-painful-part-1%2F).

#### Example of a team developing a pointing standard: 
The team decides on 1-8 of the fibonacci sequence, so 3 is a medium 1 is extra small, and 8 is extra large. 

##### Example Estimation
* Login is a story of about medium size, the team guess, so they decide to size it as a 3
* Next sprint, the team sizes logout
    * 3 parameters
        * **Complexity:** Logout is a lot simpler than login
        * **Effort:** There will be a lot less work to do than with login
        * **Uncertainty:** Since the team just worked on login, the uncertainty is low, they are familiar with the code around this functionality and have a good idea of what needs to be done
    * Assessing logout in relation to Login, the complexity is lower, there is less effort needed, and the uncertainty is low
    * The team decides to size logout as a 1
* The following sprint, the team needs to estimate a story for allowing the user to update their email
    * 3 parameters
        * **Complexity:** Updating email touches a lot of pieces, the UI, the API, the DB, as well as having the user verify the new email
            * Certainly less complex than login but probably a bit more complex than logout
        * **Effort:** The complexity suggests the effort will be between logout and login
        * **Uncertainty:** There isn't too much uncertainty here, the team has sent emails from the application before and nothing else is too experimental
    * The team decides this is larger than logout but smaller than login, so they estimate it at a 2. 
* Next up, the business has asked us to port over 102 static pages from an old application 
     * 3 parameters
        * **Complexity:** Complexity is very low, these are just simple html and css pages which need to be copied over, maybe a few small css changes here and there just make them fit in
        * **Effort:** Effort is high, there are 102 pages to port over, largely this is an effort in using copy and paste
        * **Uncertainty:** The uncertainty is low, just some basic pages added to the UI
    * While the complexity and uncertainty are low, the team decides, in relation to the other stories, this should be sized the same as login due to the large amount of effort it will take to move over all the pages over
    * The story gets a 3

##### Example Takeaways

Notice how in the example we did not discuss time, but always talked about effort, complexity, and uncertainty. This is how story points should be thought of. 

These sizes are not meant to be precise, they are meant to be quick and easy. 

## What to watch out for

### Talking about days
Remember to use relative effort/complexity/uncertainty, not time.

### Spending too much time discussing process intricacies  
Don't get stuck in the weeds. 

Don't get stuck in the weeds. If there are some "3s" and a "5" then don't spend a lot of time discussing if you should introduce a "4"

### Management manipulating with the team's points
![Dilbert manipulating estimates comic](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/ygzl6etb0dsyfdem578a.jpeg)


## What happens when the team doesn't agree?

The team votes at the same time to avoid influencing each other, in human psychology that's called anchoring.

The team then discuss the sizes to achieve consensus.

### Achieve shared understanding
The team discuses the story with the goal of achieving shared understanding.

#### Figure out why the team does not agree
Is there something part of the team isn't thinking about? Refer back to the example in the Develop Shared Understanding section.

Maybe less experienced devs are estimating higher due to more uncertainty on their part. In this case, pick a team norm for how to handle this and move on quickly. Some possible norms would be taking the average if there is a wide range or taking the larger size if the sizes are close. 

The pattern to avoid is spending many minutes during a team-wide meeting debating back and forth. If the story needs more more work, drop it and save it for later, don't waste the whole teams time.

## History
The term 'Story points' originated in the late 1990s from the XP concept of "ideal time". Ron Jeffries may have been the originator of this term.

Read more about story point history here: 
* https://ronjeffries.com/articles/019-01ff/story-points/Index.html
* Origins section: https://www.agilealliance.org/glossary/points-estimates-in/


How to work within an imposed framework will vary from team to team.

## More Resources:
### Blogs
* [Story Points by Martin Fowler](https://martinfowler.com/bliki/StoryPoint.html)
* [Myth 14: Refinement is a required meeting for the entire Scrum Team](https://www.scrum.org/resources/blog/myth-14-refinement-required-meeting-entire-scrum-team)
* [Why Estimating Stories In Agile Is Painful, Part 1](https://blizzardcomputing.com/wp/blog/index.php/2016/06/27/why-estimating-stories-in-agile-is-painful-part-1/)
* [Allthethings Prioritization Matrix](https://www.atlassian.com/team-playbook/plays/prioritization-matrix)
* [Story Points Revisited](https://ronjeffries.com/articles/019-01ff/story-points/Index.html)
* [](https://medium.com/contino-engineering/you-are-using-story-points-wrong-how-to-make-story-points-suck-less-c641c34ce63)

### Videos
* [What are Story Points? by Mountain Goat Software(Mike Cohn)](https://www.youtube.com/watch?v=VsSaolMtkKU&vl=en)

### Books 
* [Clean Agile by Robert C. Martin](https://www.oreilly.com/library/view/clean-agile-back/9780135782002/) - p64-p81