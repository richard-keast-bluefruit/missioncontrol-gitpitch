---?color=linear-gradient(to right, #702ae0, #9257f2)
@title[MissionControl]

@snap[west text-25 text-bold text-white]
Mission Control<br>*So what is it?*
@snapend

@snap[east span-70]
@fa[rocket fa-5x fa-white fa-spin]
@snapend

@snap[south-west byline text-white text-06]
This is a story all about how my team got flipped-turned upside down.
@snapend

Note:

- This is our team project
- Started last July
- Driven by a perceived need for a "client portal" and to help us adhere to all aspects of BDD
- Inspired by a lot of BDD training last year, including Byran's in April

---
@title[TheVision]

@snap[north span-100]
### Mission Control - The Vision
#### *A Portal For All Project Stakeholders*
@snapend

@snap[west list-content-verbose span-100 text-purple text-09]
<br>
@ul[list-bullets-circles]
- Blast Off! (Discovery, three amigos, planning)
- The Mission (Development, Automated Testing)
- Re-entry (QA, manual testing, metrics)
- Touchdown (Reporting, Feedback, Retrospective)
@ulend
@snapend

Note:

- A portal that can offer different things to different stakeholders, in one place
- These are just working titles for an initial concept
- We'll learn and adjust this vision as we go on

---
@title[Glossary]

@snap[north-west list-content-verbose span-100 text-purple text-04]

# Glossary
### **Feature** - A living, evolving collection of rules and examples describing software functionality related to a specific purpose.
### **Rule** - Rules describe the behavioural boundaries of a feature.
### **Acceptance Criterion** - Same as a rule. 
### **Example** - Demonstrates one possible behaviour of a rule from the perspective of a specific user and should specify context, action and outcome. 
### **Scenario** - A formulation of an example written using domain terminology that acts as persistent business-readable documentation. In Mission Control, this is formulated using Gherkin. 
### **Stakeholder** - Anyone who gains value from the software.
### **User** - A stakeholder who uses the software. 
### **User Story** - A finite and functional increment of software providing value. 
### **Value Statement** - "As a..., I want..., So that..." / "In order to..., As a..., I want..."

@snapend

Note:

- I did a lightning talk at AOTB last year about being aware that these terms could have multiple definitions
- It was apparent during 3 Amigos that that was true
- So we wrote a Glossary for what these things mean within Mission Control

---
@title[BlastOff]

@snap[north span-100]
### Blast Off!
@snapend

@snap[west span-55 text-purple text-07]
#### Discovering requirements
<br>
@ul[split-screen-list text-08](true)
- Collaboration - multiple stakeholders
- Start with a User Story for a Feature
- Discover the rules
- Explore examples for each rule
@ulend
@snapend

@snap[east span-55 text-purple text-07]
#### Planning work
<br>
@ul[split-screen-list text-08](true)
- Writing acceptance tests (formulating examples)
- Estimating user story effort
- Splitting user stories into smaller stories
@ulend
@snapend

Note:

- Blast Off will cover discovery and planning
- These are just our initial thoughts based on our experience

---
@title[ProjectTimeline]

@snap[north-west]
@css[message white](<br> <br> Project <br> Timeline)
@snapend

@snap[north timeline idea]
@fa[calendar](31st Jul)
<hr><br>
@fa[lightbulb-o](Coding starts)
@snapend

@snap[north-east timeline launch]
@fa[calendar](9th Aug)
<hr><br>
@fa[rocket](v0.1)
@snapend

@snap[south-west timeline idea]
@fa[calendar](28th Aug)
<hr><br>
@fa[lightbulb-o](3 Amigos)
@snapend

@snap[south timeline launch]
@fa[calendar](8th Nov)
<hr><br>
@fa[rocket](v0.2)
@snapend

@snap[south-east timeline prototype]
@fa[calendar](21st Jan)
<hr>
@fa[cog](Automated Acceptance Testing)
@snapend

Note:

- We have spent very little time as a team on this project, spread out over half a year
- A lot of the coding was in my spare time
- The team was heavily involved in the 3 Amigos before Sprint 2, resulting in quite a difference between v0.1 and v0.2

---
@title[Sprint1]

### Sprint 1

---?image=template/img/mc/BlastOffV1.png&size=60%
@title[Release1]

Note:

- Sprint 1 was in an experiment to use the Targetprocess API to display an augmented feature file, replacing tags with hyperlinks to Targetprocess Test Plans and Test Cases.

---?image=template/img/mc/BlastOffV1TestPlan.png&size=60%
@title[Release1]

Note:

- Here's what is effectively a feature file as a Targetprocess Test Plan

---?image=template/img/mc/BlastOffV1TestCase1.png&size=60%
@title[Release1]

Note:

- Here's a scenario as a Test Case
- Notice it belongs to 3 Test Plans

---?image=template/img/mc/BlastOffV1TestCase1TestPlans.png&size=60%
@title[Release1]

Note:

- The User Story Test Plan
- The "Feature File" Test Plan
- The Sprint Test Plan, for the benefit of a release report

---?image=template/img/mc/BlastOffV1Sprint1TestPlan.png&size=60%
@title[Release1]

Note:

- Here's the Sprint 1 Test Plan

---
@title[3Amigos]

### 3 Amigos

---?image=template/img/mc/3Amigos.jpg&size=60%
@title[3Amigos]

---?image=template/img/mc/3Amigos2.jpg&size=60%
@title[ExampleMapping]

Note:

- We used Example Mapping to discover user stories, rules and examples

---?image=template/img/mc/3Amigos3.jpg&size=60%
@title[ExampleMapping]

Note:

- We used "The One Where" cards for examples to capture context and outcome

---?image=template/img/mc/3Amigos4.jpg&size=60%
@title[UIMockup]

Note:

- And we had conversations about what Blast Off should look like and actually do
- We captured white board drawings, to rememeber the conversations and used a slack channel to share them

---
@title[Sprint2]

### Sprint 2

Note:

- We managed to complete a few stories with the whole team mobbing.

---?image=template/img/mc/BlastOffV2.png&size=75%
@title[Release1]

Note:

- Release 0.2 looked completely different
- We sidelined Targetprocess and instead used text files to capture Features, User Stories, Rules, and Examples
- The displayed "Feature File" is a result of stitching together the relevent user stories
- This will evolve to look more like a Feature File
- User Stories will have their own pane to evolve Features

---
@title[AutomatedAcceptanceTests]

### Automated Acceptance Tests

---?image=template/img/mc/AutoTests.jpg&size=60%
@title[AutomatedAcceptanceTests]

Note:

- At the beginning of Jan, we mobbed on automating the acceptance tests for the work done so far
- From Sprint 3, additional tests will be created as part of the work on a User Story
- This will hopefully allow our testers to perform more exploritory/break testing for each release

---
@title[Sprint3]

@snap[midway span-55 text-purple text-07]
### Sprint 3, and beyond!
<br>
@ul[split-screen-list text-08](true)
- Dogfooding
- Ability to add user stories to evolve features
- Add rules and examples
@ulend
@snapend

Note:

- We want to be able to use Blast Off ourselves, to progress Blast Off
- The next steps for this are to...
- When we have time, of course!

---
@title[Questions #4]

@snap[east span-50]
![QUESTIONS-4](template/img/questions-4.png)
@snapend

@snap[south-west template-note text-gray]
Thank you for listening
@snapend