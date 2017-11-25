# 2017 Agile Development Cheat Sheet
Based on recent studies about agile development. The goal here is to have a starting point and references for people to study Agile development related practices in 2017.

## Index
1. [Scrum](#1-scrum)
2. [XP](#2.-xp-extremme-programming)
3. Kanban
4. [Scaling Agile](#4.-scaling-agile)  
  4.1 [Scrum of Scrums](#4.1-scrum-of-scrums)  
  4.2 [Nexus](#4.2-nexus)  
  4.2 LeSS  
  4.4 SAFe  
5. Agile vs Legacy  
  5.1 Gartner BiModal  
  5.2 To speed IT (McKinsey)  
  5.3 Cinefin  
6. [Product prioritization techniques](#6.-product-prioritization-techniques)  
7. [Facilitating retrospective](#7.-facilitating-retrospective)  
  7.1 [4L's](#7.1-4ls)  
  7.2 [Mad, Sad, Glad](#7.2-mad-sad-glad)  
  7.3 [Sinking boat](#7.3-sinking-boat)  
8. [Spotify Agile Model](#8.-spotify-agile-model)
9. [References](#9.-references)

## 1. Scrum
- Simple
- Transparency
- Inspection
- Adaption
- Iterative and incremental
- Product Backlog
  - Grooming
- Sprints  
  - Sprint Goal
  - Sprint Planning
  - Sprint Backlog
  - Sprint review
  - Daily Scrum
- Definition of Done (DoD)
- Members
  - Scrum Team
  - Scrum Master
  - Product Owner
  - Stakeholders (chicken)
- Monitoring
  - Burn down chart
  - Cumulative work

## 2. XP (Extremme Programming)
- Engineering oriented
- Continuous Integration
- Pair Programming
- Test Driven Development
- Small releases
- Planning game
- Spike development
- Collective code ownership
- Metaphors
- Coding standards
- Sustainable pace
- Simple design

## 4. Scaling Agile
- Multiple frameworks/tools
- Simplest to most complex

### 4.1 Scrum of Scrums  
- A.k.a meta Scrum
- One representative from each team
  - Scrum master?
- Daily scrum with all these representatives
  - Sync everything in that meeting
  - completions
  - next steps 
  - impediments 
  - on behalf of the teams they represent
  
### 4.2 Nexus 
- Augment scrums
  - One new role
  - Expanded events and artifacts
- [Life cycle](https://s3.amazonaws.com/scrumorg-website-prod/drupal/2016-09/NexusPoster17x11.pdf)
- Nexus
  - Unit
  - 3 to 9 Scrum teams
- One extra team
  - Integration team
  - Responsible for all integrations
  - Members from Scrum teams can be part of Nexus team
  - Nexus work takes precedence as impacts more people
- Product backlog
  - Should be detailed enough before teams can start working on it
  - Dependencies must be identified and preferably resolved
  - Backlog distribution should be made to minimize dependencies
- Daily Scrum
  - Nexus daily occurs first
  - Identify dependencies and integration problems
  - Use it as input for Scrum daily so teams can plan their work accordingly
- Influences technical architecture
  - Architecture can simplify synchronization and scaling problems
### 4.2 LeSS  
### 4.4 SAFe  

## 6. Product prioritization techniques

- Right technique depends on goal
  - Internal vs External
  - Quantitative vs Qualitative
- Kano (questions)
- QFD (house)
- Opportunity cost
- Buy a feature (game)
- Story mapping
  - Map following business flow order
  - Activities
  - Backbone
  - User tasks
  - Slices releases and development strategy
- MoSCoW
  - Must
  - Should
  - Could
  - Won't
- Prune Tree (meh)
- Speed Boat
  - Pain driven
- Financial analysis

## 7. Facilitating retrospective  
- Like a negotiation
  - Separate people from the problem
  - Interests and not positions
  - Objective criteria
- Opportunity to:
  - learn
  - build trust
- No blaming
- Everybody has to participate
- Try not to favor extroverts and HIPPO (highest paid person opinion)

### 7.1 4L's  
- Liked
- Learned
- Lacked
- Longed for

### 7.2 Mad, Sad, Glad  
- Mad
- Sad
- Glad

### 7.3 Sinking boat
- Variation of speed boat prioritization technique
- Sail (good stuff)
- Anchor (bad stuff)

## 8. Spotify agile model
- Pillars: 
  - Autonomy
  - Direction
  - Community
- Squads
  - Cross functional
  - TA - Testing automation
  - QA - Quality assistance
- Tribe
- 1 Tribe -> N Squads
- Chapter
  - Same role 
  - Cross squads
- Guilds
  - Same role
  - Cross tribes
- Squads/tribes structure reflect communication requirements
- Heavily based/dependent on software architect
  - Release train (leaves no matter what)
    - Feature flags
  - One click deploy
  - Continuous integration
  - Limited blast radius and partial rollout
- Culture
  - Mistakes are not punished
    - Otherwise people hide them
  - Failure recovery > failure avoidance
  - Blame is not handed off to other people
    - Squad who builds it, owns it
  - Optmize for value
  - Measure impact and not output
  - Data > opinion
- Health check
  - Systemic problems
- New ideas
  - Think it
    - PR Story
    - Metrics (what does success looks like?)
  - Build it
  - Ship it
  - Tweak it  
  - Repeat
  
## 9. References
- [Scrum Guides](http://www.scrumguides.org/)
- https://foldingburritos.com/product-prioritization-techniques/
- [Getting to Yes](https://www.amazon.com/Getting-Yes-Negotiating-Agreement-Without/dp/0143118757/)
- https://en.wikipedia.org/wiki/Extreme_programming_practices
- [Scaling Agile @ Spotify](https://www.youtube.com/watch?v=jyZEikKWhAU)
- http://jpattonassociates.com/wp-content/uploads/2015/03/story_mapping.pdf
- https://www.agilealliance.org/glossary/scrum-of-scrums/
- https://scrumorg-website-prod.s3.amazonaws.com/drupal/2016-09/NexusGuide%20v1.1.pdf?nexus-file=https%3A%2F%2Fscrumorg-website-prod.s3.amazonaws.com%2Fdrupal%2F2016-09%2FNexusGuide%2520v1.1.pdf
