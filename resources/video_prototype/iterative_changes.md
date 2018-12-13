# Iterative changes to the paper prototype

## Merging the requirements list and the search tab

After our meeting with Dr. Vanbever, we noticed that searching and filtering would be a much more important part of our UI than we had initially anticipated, as there could be thousands of requirements in a larger network. As such, we removed the search tab and moved the search bar to the top of the requirements tab. Adding search terms would immediately filter the list of requirements displayed below. Finally, merging these two tabs also means that users would no longer have to switch between tabs.

## Splitting the search textbox into multiple filters

To facilitate the search itself, we made four searchboxes: “from”, “to”, “via”, and “prefix”. “From” lets users filter requirements by the node they start at, and “to” filters by the node a requirement ends at. “Via” includes all nodes that are affected by a requirement in some way. “Prefix” filters routes by the destination IP of the routed packets.

Compared to the single search bar we had in the paper prototype, these more specific filters allow the user to narrow down the requirement they’re looking for far more easily and quickly.

## Removing the ‘Inspect’ tab
As remarked by Dr. Tsankov and Dr. Vanbever, the inspect tab wouldn’t provide much useful information to the user, except for the list of requirements that affect the router being inspected. Moreover, it would have been difficult to fit the potentially huge list of requirements into that tab if we also needed space to display other information about the router.
We thus decided to split that functionality. To find the list of requirements that affect a specific router, the users could just use the newly introduced “via” filter in the requirements tab. The rest of the more detailed information neatly fits into tooltips in the graph: We can display information about a node in a tooltip when a user hovers their mouse pointer over it, and we can display the IPs of the connected network cards when a user hovers over a link.

## Showing names in the graph view
In our paper prototype, we didn’t show the names of the nodes in the graph and would instead have that information displayed in the “Inspect” tab. However, users need to be able to quickly identify nodes in the graph, so it’s essential that the names are shown in that graph, too.

## Simplifying the toolbar
We reworked our toolbar between our paper prototype and our digital version. Most importantly, the scissors and the bomb icon were merged into the bulldozer icon, thus having only one icon for simulating link and node outages.
The selection icon was replaced by the lasso icon, while we removed the hand icon (which was supposed to move a single node around) and added the zoom. Also, they were rearranged, puting the most important one, the cursor, at the top.

## Adding a border to the graph during a what-if analysis
When we showed the mock-up to the ETH network administrators, it became clear that we needed a clear visual indicator for when the network graph contained simulated node or link failures. Before the questionnaire was sent out, we fixed this by adding a red border around the network graph and displaying the text “‘What-if’ analysis”. For the video, we made the border blue and changed the text to “Simulation”, because that just looked much better.

## Splitting the “Security” category into “Waypointing” and “Blocking”
Our paper prototype and mock-up used the term “Security requirement” for requirements that prevent traffic from flowing through some node, and for those that force traffic to flow through some nodes. This made the UI harder to use, as the term “security” doesn’t directly imply what those requirements actually do. Therefore, we decided to split this category into “blocking requirements” and “waypointing requirements”.
