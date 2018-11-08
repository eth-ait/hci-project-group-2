# Study Goals

    TODO

First sketch, work in progress.

## Study goal or (research) questions

- How easily can a new user verify a requirement?
- How good can a new user perform a "What-If" analysis?
- How well does the user interface match the users expectations?

## Method

We use usability testing because we have specific tasks and are interested in how well users can perform them and how good they can manage the UI in general. Therefore usability tests with real users makes more sense than letting experts evaluate heuristics.

## Protocol

    TODO

Basic idea: 
- Conduct questionary with a clickable mockup with people from the network group of Laurent.
- Do interview / Wizard-of-Oz style tests with networks operators.

1. Greeting 
2. Basic overview

### Task 1

1. Describe task: Through how many distinct paths is firewall\_1 connected to border\_router25?
    - [ ] 2 paths
    - [x] 3 paths
    - [ ] 4 paths

Sample set of actions:
1. Filter from: firewall\_1 to: border\_router25
2. Click reachability requirement
3. Click 3-connectivity from firewall\_1 to border\_router25
4. Look at visualisation

### Task 2

1. Start setup: Start page, left requirements, right graph
2. Ask the user to destroy the edge between router\_13 and router\_37
3. Ask the user to figure out which requirement is now violated
    - Answer: Open

Sample set of actions:
1. Select scissors tool from tool list
2. Identify edge between router\_13 and router\_37
3. Destroy that edge
4. Note red light in requirements tab
5. Expand reachability section
6. Identify violated requirement (also marked with a red light)

### Task 3

Questionaire:
1. Show tool bar, ask users what icons will do

### Task 4

1. Start setup: Start page, left requirements, right graph
2. Find which requirements affect router\_17?

Possible paths:
- Right click -> Context menu -> Inspect node -> Requirements on left
- Fill out node in the via filter
- Use via tool -> Select router\_17
