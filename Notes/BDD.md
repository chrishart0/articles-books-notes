# BDD Summary

BDD is a process which helps ensure the right thing is being delivered, as desired by the business/PO.

"BDD = business sleeps better, TDD = devs sleep better"

# There are 3 main steps to BDD

## Discovery

- For a story
- Have a "Discovery Workshop"
- Conversation between Developers, PO, other people who would be useful in determining the correct functionality
  - Should have minimum of the *three amigos* 1 dev, 1 QA, 1 product person
- Deep dive into user story to find concrete examples
- Should last no longer than 25-30 minutes
  - If the workshop is lasting much longer this could signify the story should be split, there is too much complexity
    - Exceptions for the first few workshops while the team is getting the hang of it
- Discovery Workshop format continued reading:
  - https://cucumber.io/docs/bdd/discovery-workshop/
  - Example Mapping
    - https://cucumber.io/blog/bdd/example-mapping-introduction/
    - https://cucumber.io/docs/bdd/example-mapping/
    - https://www.youtube.com/watch?v=JuWEQsE7Hlo
  - https://johnfergusonsmart.com/feature-mapping-a-simpler-path-from-stories-to-executable-acceptance-criteria/
  - https://jennyjmar.com/2016/04/16/bdd-discovery-and-oopsi/

## Formulation

- Document examples in a way which can be automated to check for agreement
- Test cases are:
  - Written in collaboration with PO
  - Are written in plain language
    - **Use Gherkin**
- Some teams do this in Discovery Workshop, some do not

## Automation

- Automated tests which run the examples from the Formulation step
  - **Use Cucumber**

 

## BDD Details

BDD finds concrete examples to develop shared understanding among team of what is to be worked on

BDD *is not* comprehensive testing
* BDD *is* building an understanding of requirements using examples written in ubiquitous language

"BDD = business sleeps better, TDD = devs sleep better"

**The conversations are much more important than the tool!**

BDD is all about the conversation between the technical and non-technical individuals to make sure everyone has a shared understanding of what is to be done.