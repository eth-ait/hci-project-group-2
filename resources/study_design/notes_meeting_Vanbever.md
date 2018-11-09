# Meeting with Dr. Vanbever
Date: 07.11.2018

## Raw notes
Regex: Abstract graphs
Define equivalence classes -> Let operators name them

Load balancing for equivalence class
- Network forwards at prefix level
- Show at higher abstraction

Conflict: Display details vs. overview
- Diametric opposite way?

Live traffic map:
- Vary width according to capacity
- Operator can vary time period
- Time line
- Traffic gives you a weight —> Helps to have better view of network

Requirements:
- Way-pointing (included in security)
- Reachability is a precondition, basic requirement: Hierarchy
- Top spot: Reachability, Security?
- Organization of requirements, they are not flat —> leverage it, easier to display

Does it make sense to display paths?

Click on multiple of them?
- We don't combine requirements

When do you have violations? NetComplete gives correct config?
- What-If analysis with bomb/cutting
- Verify that NetComplete did what you want, will be mistakes, NetComplete maybe can’t satisfy —> show you counterexample —> net operator must go back and fix requirements
- Requirements might be wrong —> Can see typos
- Maybe see missed requirements
- Forgot to provide some requirement
- Good motivation for visualisation —> maybe focus more on that make project description more precise on this

Search tool in photoshop tools, drag path and then show requirement in search —> sketch visually search path
- Search aspect is important

Overview:
- Collapse edge access nodes, not show end devices —> graph separator (computing that is hard in praxis though, NP-hard)
- Important to mention that network can be gigantic —> Graph is big
- NetComplete: If sketch is precise, 100s of nodes are possible, but if they are loose, performance collapses
- Could expect up to 1000 nodes (without end devices, with edge devices)
- Swisscom ~100
- Switch ~50

Security:
- Groups of nodes that can’t communicate
- Make disconnected components, highlight them as a group

