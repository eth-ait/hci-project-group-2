# Notes on changes in first iteration of the prototype

- Search integrated in requirements tab
    - From, To, Via, Prefix box
    - Highlight searched nodes
    - Scale graph on right to left side, autoscaling to focus the graph on the selected nodes
        - Right lower corner: deactivate autoscaling switch / checkbox, when off, make red border around screen to show that it's paused
- Instead of inspect routerA: 
    - From: *
    - Via: A
    - To: *
    - Prefix: *
- Info about node (IP, mask) when hovering over it
- All nodes are labelled with their names (maybe not when zooming out)

Redesigned toolbar only contains the following items:
- Pointer 
    - Left click: Display circular menu with options: from, via, to
    - Right: Move around in the graph
- Magnifying glass: Zoom in/out (same functionality on scroll wheel)
- Move icon: Move in graph (same as right click)
- Bulldozer: Destroy nodes or edges
- Lasso: Select group, add more with ctrl/shift, right click to name —> Afterwards only display group
