# Stories

## How to Estimate a Story (Story Pointing)
Story Points are a relative estimate of effort not an estimate of time. The goal of story points is to allow a team to predict how much work they can get done. 

Stories don't have to be estimated with points, it is often useful to think of stories as t-shirt sizes "s, m, l, xl." This helps keep the team from trying to tie story points back to some number of days
* Example
    * 1 = extra small
    * 2 = small
    * 3 = medium 
    * 5 = large
    * 8 = extra large
You don't want to allow for too many options, this will lead to analysis paralysis. Remember, story points are a rough estimate, we don't want to spend too much time trying to pick the perfect number. 

### If stories don't have to be estimated with points then why are they so commonly used?
Because with numbers we can use statistics. Using story points we are able to calculate velocity(the amount of points completed per iteration.) This allows the team to more easily predict how much work they will do next sprint and over the course of several sprints.  

### Setting the gold standard: how new teams start estimating
The first stories which are estimated in a project are your golden stories. All future estimates of complexity should relate back to these. These are the standard to which all other stories will be compared.

As a team decide on a range. Make sure it does not allow for too many options. 

#### Example pointing standard: 
The team decides on 1-8 of the fibonacci sequence, so 3 is a medium 1 is extra small, and 8 is extra large. 

Why use Fibonacci? [Here is a good article](https://www.mountaingoatsoftware.com/blog/why-the-fibonacci-sequence-works-well-for-estimating) explaining why it is better than simply using a standard sequence of numbers.

### Example Estimations
* Example: 
    * Login is a story of medium effort so the team decides to estimate it at a 3
    * Logout is a lot simpler than login, so the team decides to make that a 1
    * Next sprint the team needs to estimate a story for allowing the user to change their email. The team decides this is more complex than logout but less complex than login, so they estimate it at a 2. 

Notice how in the example we did not discuss time, but always talked about effort / complexity. This is how story points should be thought of. 

These estimates are not meant to be precise, they are meant to be quick and easy. 

### Story pointing strategies 
* Planning poker
    * Every developer has a deck of cards which contains only the numbers of acceptable story points
        * Each developer picks a card and keeps it hidden
        * All developers reveal their cards at once
    * There are online tools for this for remote teams
* Flying Fingers
    * Each developer puts their hands behind their back with some number of fingers held up
    * Someone counts down from 3
    * Everyone reveals their fingers at once

For each of the strategies, once the numbers have been revealed 
* If there is an obvious winner simply pick that
* If there are a range of estimates or a number of outliers then stop, and have a discussion on why until a consensus is reached

## Story points are relative
* Story points should always be estimated relative to a previous stories
  * The exception to this is the first stories you create in a new project, there will be no previous stories to relate the new ones

Story points are by definition relative and unique to each team (thus comparing your velocity to another teams velocity is pointless).

## Story points are arbitrary 
* Story points themselves don't matter, a 3 on one team could be the same amount of effort as a 30 on another team
* The team 

## Refinement
Also known as grooming, refinement is what we call the process of going through stories as a team. During refinement the team is ensuring there is shared understanding of the requirements and then estimating the story points. 

It is important that the team has read the stories before refinement starts. The PO should send out the stories ahead of time and the devs should ask questions and get some clarification before hand.

Here is what the [2020 Scrum Guide](https://scrumguides.org/scrum-guide.html#artifacts-productbacklog) has to say about refinement:
> Product Backlog refinement is the act of breaking down and further defining Product Backlog items into smaller more precise items. This is an ongoing activity to add details, such as a description, order, and size. Attributes often vary with the domain of work. 
>
>The Developers who will be doing the work are responsible for the sizing. The Product Owner may influence the Developers by helping them understand and select trade-offs.

### Engagement
It is important to have high engagement from all the team members who attend the session. Here are some tips for increasing engagement. 
* Smaller meetings: the less people on a meeting the more likely each individual is to feel compelled to participate 
* For remote: turn videos on!
  * The individual team members will feel a lot more engaged if they can see each other
  * Facial expressions are an important piece of how humans communicate, without video we lose this

### When is refinement?
Many teams schedule refinement as a separate, regular meeting. It does not have to be this way. While this may be beneficial for new teams, it is not necessary.

Not all team members need to be present to refine a story. 

## Tips and Gotchas

### Tips
* Always send out your 

### Gotchas

#### Story Point Inflation
If you notice that your velocity keeps going up it could be that you are experiencing point inflation. Make sure to reference back to those first stories. Does the amount of effort you estimated a 3 as line up to what you are currently estimating a 3 as? If not, why? 

Watch out for the following
* Management should not be using velocity as a metric 
  * The velocity number is only useful within a team, not compared between teams. Remember, story points are relative to each other and arbitrarily decided upon by a team. Another team may use a completely different set of numbers.  
* Technical debt making stories require more effort
    * This can easily happen after some time on a project
    * As a project grows larger, if a team did not spend sufficient time optimizing the architecture, writing tests, decoupling, ect, then each new feature will become more complex to write
        * If you notice the story points for what would have been a smaller story at the beginning going up this is a signal to tackle your technical debt 

## Continued reading
* https://www.scrum.org/resources/blog/myth-14-refinement-required-meeting-entire-scrum-team
* Clean Agile by Robert C. Martin