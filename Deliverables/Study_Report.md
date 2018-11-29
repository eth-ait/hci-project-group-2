# Study Report 
## Study goals
#### How fast and how accurately can a new user verify a requirement in the network?
It is important for our personas to accomplish their tasks quickly and with little effort. Moreover, they want to reduce errors which could adversely affect the network. We thus decided to measure both speed and error rates of operators using our UI.

#### How easily and reliably can a new user perform a "what-if" analysis?
Performing “what-if” analysis is a core feature of our application: A user can delete nodes and edges in the network graph to simulate how the network requirements would be affected if a node or a link were to fail. Since this is a common action, we wanted to test if our UI helps users perform it with little difficulty.

#### Compare two methods to filter requirements.
During the design of our UI we noticed that we had to place a large emphasis on searching and filtering to support large networks with many requirements. We came up with two different approaches to filter requirements by the node they start / end / pass through: users can either specify the node by its name or select it in the network graph and use the radial menu. In our study we wanted to compare these two methods and determine which one our users prefer.

## Method
We were interested in how well users would perform certain tasks and if they could efficiently interact with the UI in general. Because our users are exclunetwork operators we wanted specific feedback from them rather than asking HCI experts to evaluate the correct use of general principles of our UI. Therefore, we chose to do a usability test instead of using a heuristic approach.

We created one task per study goal in the following way:
- To find out how fast and accurately a new user can verify a requirement, we asked the users to find one specific requirement in each of three different categories and to answer a short question about that requirement. We also asked them to estimate the time it took them to complete the task. Asking three very similar questions has the advantage that we are able to cope with the learning effect: As the users become more familiar with the UI and thus may become faster at completing the second and third task, we will be able to infer the time it would take an experienced user to complete such tasks.
- To assess how easily and reliably a new user can perform a "what-if" analysis, we created a task where they would delete an edge in the network graph and then had to determine the impact this had on the network requirements. We also asked them to give feedback on the difficulty of performing such a task.
- To compare the two methods to filter the list of requirements, we guided them to try both methods, using the filter text boxes or using the radial menu on the nodes, and then asked them which one they preferred.

In the end we asked them some general questions about our UI, which feature they liked most and which one they liked the least.


Taking our study goals into account we created a digital prototype to meet our needs and formulated a questionnaire, which we will now discuss in more detail.

#### Visual Mock-up ([see here](https://xd.adobe.com/view/1b2da1d3-f1cd-447b-4bae-9af20e070c4f-6d1c/?fullscreen))
We used Adobe XD to design our prototype. The environment of Adobe did not provide any measurement tools for the study but made it simpler to create a usable and distributable prototype. Since our UI will be highly interactive, it was only possible to simulate a limited subset of all possible interactions. Therefore our questions and tasks had to be very specific and straightforward.

#### Questionnaire ([see here](https://docs.google.com/forms/d/e/1FAIpQLScezn4NKkqSJVn5ywilecgBPvZDxEXtcfHE85JA9YDOrbKo0A/viewform?usp=sf_link))
Due to the limitations of our prototype we had to help our users to interact with the mock-up. This lead us to questions which focus strongly on the essential parts of our prototype and therefore our study.

We then split our study into two parts that both used the same prototype and questions.

First, we arranged a meeting with ETH network operators and observed them solving the tasks. But instead of written feedback, we asked them to think aloud and discuss anything they note while doing the tasks. Unfortunately, these network operators, who comprise our entire target group, were hard for us to reach. Therefore, we chose to meet the few we could contact in person and collected as much data as possible

Second, we sent out the prototype and a questionnaire to the ETH Networks Group. They are a good approximation of our target group as they are also network experts. We expected to reach more people and gather more data with this type of questionnaire.

## Protocol
For both parts the rough procedure is as follows:
1. Introduction (see below, one for interviews, one for online questionnaire)
2. Let participant complete task with clickable mock-up 
3. Participants fill out questionnaire or answer interview questions
4. Repeat 3 for all 3 tasks
5. Participant is dismissed

### Introduction (for interviews)
#### Welcome and Purpose
Thank you so much for coming in today. I wanted to give you a little information about what you will be looking at and give you time to ask any questions you might have before we get started.

Today we are asking you to serve as an evaluator of a prototype of a tool to verify and do a  what-if analysis of network configurations computed by NetComplete. NetComplete is a program that takes high-level requirements and computes optimized configurations for routers. We tried to design a UI that shows the result of that computation in a graph. The goal is that a network operator can evaluate, if the configuration meets his/her expectations and find flaws by conducting a what-if analysis in our UI. He/She can then go back to NetComplete and modify his/her requirements accordingly.

You will complete a set of tasks and our goal is to see how easy or difficult you find our UI to use.

#### Test Facilitator’s Role
I am here to record your reactions and comments about the prototype you will view. I have a colleagues helping me take notes and observe your interaction with the prototype. During this session, I would like you to think aloud as you work to complete the tasks. I will be able to offer hints if you are stuck. From time to time, I may ask you to clarify what you have said or ask you for information on what you were looking for or what you expect to have happened.

#### Test Participant’s Role
- I am going to be asking you to look for some information on the prototype and tell me how easy or difficult it was to find the information. These activities are all about how easy we have made it for people to use the UI.
- If you have any questions, comments or areas of confusion while you are working, please let me know.
- If you ever feel that you are lost or cannot complete a task with the information that you have been given, please let me know. I will put you on the right track.
- I may ask you other questions as we go and we will have wrap up questions at the end.

Do you have any questions before we begin?

### Introduction (used for clickable mock-up)
Thank you so much for participating in this test for our UI design. Our prototype is a tool to verify and do what-if analysis of network configurations computed by NetComplete. NetComplete, as you may know, is a program that takes high-level requirements and incomplete network sketches and computes optimized configurations for routers. We are designing a UI that shows the result of that computation in a graph. The goal is that a network operator can evaluate, if the configuration meets his/her expectations and find flaws by conducting a what-if analysis in our UI. He/She can then go back to NetComplete and modify his/her requirements accordingly.

We want you to complete a small set of tasks in an easy mock-up version of our UI and fill out a questionnaire about the design so we can improve the current prototype.

The mock-up prototype is a very simple version of the UI we came up with and has very limited capabilities that should show-case what could be possible. Objects that cannot be interacted with are greyed out. Try to do the tasks in the specified order. If you get stuck in the UI doing a task use the 'Home' button to get to the initial state of the mock-up.

## Results

### In-person meeting

In our meeting with the ETH network administrators on Friday 16.11. we received the following feedback:

#### Very detail-focused feedback

In general the feedback the network operators provided was rich in details, but it mainly targeted the features of NetComplete and not our UI. The network operators also requested many features, which lie outside the scope of both our UI and NetComplete. For example, they requested the network graph to dynamically show the status of all nodes and links.

#### Difficulties with the mock-up

Unfortunately the little UI feedback we received mostly focused on limitations of our mock-up. For example, they wanted to move around the network graph, but there was no way to implement such a feature in Adobe XD. Also they sometimes got confused when certain features worked in some places but not in others. That was the case because we implemented the functionality we needed to test our goals but they were more interested in freely exploring the mock-up than solving tasks.

#### Virtual views vs physical networks

In our UI we solely focused on the physical connections between machines. However, the ETH network operators mostly deal with virtual networks deployed on these physical machines and connections.

#### Distance to high-level requirements

The network operators weren’t used to the high-level requirements that NetComplete uses. From their practical point of view, they disagree with the definition of some of our requirements. For instance, they remarked that unequal cost load balancing would not be possible with OSPF.

#### Current lack of automation

In their current work flow the network operators configure every switch by hand. We had the impression that this makes it hard for them to have trust in a system such as NetComplete, since it takes automation one step further from deployment to configuration and is thus even more abstract.

### Questionnaire

#### Demographics

The average age of our users was 27, with a standard deviation of 2.74. All of them were male. We don’t have the age of one participant, since that question was only added later.

#### Requirement lookup tasks

We asked the users to find a specific requirement in each of three different categories and to answer a short question about it. 

![Results of Task 1.1 - Connectivity](/img/study_report/find_requirement_task_1_connectivity_small.png)

Users were asked to find the “N-Connectivity” section and had to find a specific requirement and interpret it. The correct response was “3 paths”. All users chose the correct answer.

![Results of Task 1.2 - Security](/img/study_report/find_requirement_task_2_security_small.png)

Users were asked to look at a specific “Security” requirement and answer a comprehension question about it. The correct response was “router_17”. All users chose the correct answer.

![Results of Task 1.3 - Load balancing](/img/study_report/find_requirement_task_3_load_balancing_small.png)

Users were asked to find the “Load Balancing” section and had to find a specific requirement and interpret it. The correct response was “router_37 -> router_16”. All users chose the correct answer.

Average perceived time for requirement lookups:
![Task 1 - Average perceived lookup time](/img/study_report/find_requirement_avg_time.png)

We also asked the users to estimate the time it took them to complete the task. We asked three very similar questions to cope with a potential learning effect (users may become faster when they get used to our UI). 

We collected the perceived time in 15s time steps. The disadvantage of asking users for their opinion on how long it took them to answer a task is that this measurement is not very precise and may be biased. We used this method because it was not possible to arrange meetings with enough network specialists and measure the time ourselves. We think that this measurement is nonetheless helpful, because it still shows whether users feel they can solve a task quickly. 

In the resulting graph we could not see a learning curve. It is possible that there is not much learning effect or it could be that our measurements were not precise enough to show the improvement. We also asked users if they think they got faster finding requirements. The results are displayed in the pie chart below (it has only eight answers, since we added this question later). Half of the users answered that they thought they got faster, so it could also be that we did not see the learning curve because of the coarse grained time measurement of 15s intervals.

Overall the average stayed around 30 seconds, which means that all users perceived that they were quite fast to answer the question (from 15 seconds to 1.5 minutes, they chose the second lowest as their perceived time).

![Task 1 - Learning effect](/img/study_report/find_requirement_learning_effect_small.png)

#### What-if Analysis using the bulldozer tool

![Task 2 - What-if analysis results](/img/study_report/what-if_answer_small.png)

The user was asked to use the bulldozer tool to destroy an edge in the graph and look for the implication of this action. There was an indicator light in the requirement group where one was violated. The user had to find the violated requirement, which was “Reachability from router_13 to router_37”. All users were able to complete the task and gave the right answer.

![Task 2 - What-if analysis difficulty](/img/study_report/what-if_difficulty_small.png)

The users thought the bulldozer tool was not very hard to use. From the comments we learned that the activation of the bulldozer tool and its use needs to be explained better. A suggestion was to change the cursor to another symbol and maybe give a better tutorial so that the use of the tool is clearer. Someone also mentioned that the cut edge was not highlighted clearly enough.

![Questions - Usefulness of what-if analysis](/img/study_report/what-if_bulldozer_effect_small.png)

The majority of the users were convinced of the usability of the tool but there were also users who thought the cut edges need to be better highlighted but liked the immediate changes in the requirements list to the left (the checkmark changes to a cross) if a requirement failed because of the cut edge.

#### Comparing filter textboxes with radial menus

![Task 3 - Comparison between radial menu and filter textboxes](/img/study_report/filter_vs_radial_menu_small.png)

The majority of our testers preferred the radial menu (4 - 6) over the classic filter box (1 - 3) to do a simple lookup task.

#### General questions

In the following graphs one stands for “strongly disagree” and five for “strongly agree”.

![Questions - Amount of information displayed](/img/study_report/information_amount_small.png)

User feedback suggests that the screen was sufficiently simple and clear.

![Questions - Difficulty of navigation through requirements](/img/study_report/requirement_navigation_small.png)

The users thought the UI was easy to navigate through. The participant who gave a score of 1 explained in the comments field that he was frustrated by the limitations of the mock-up.

![Questions - Difficulty of tasks](/img/study_report/tasks_easy_small.png)

This feedback implies that the UI helped our users complete their tasks.

![Questions - Prioritization of important information](/img/study_report/information_highlight_and_prio_small.png)

The feedback shows that most of the information is properly highlighted. However, there is still room for improvement.

![Questions - Understandable visualization of information](/img/study_report/requirement_visualisation_small.png)

The visualisations of the various requirements were understandable. One user commented that the visualisations were very useful to understand the requirements.

![Questions - Preferred way of searching requirements](/img/study_report/preferred_searching_method_small.png)

The majority of our testers preferred the radial menu as a tool to accomplish their tasks. Some users additionally liked other filtering methods, too. User comments suggested that we should keep both filter variants because they complement each other (for larger graphs you might want to filter first, for smaller the radial menu is faster).

We would like to mention that it is possible that the filtering textboxes performed worse because of our prototype design.In our mock-up tool, users were not able to type into the textboxes themselves. Instead, we had to provide a list of suggestions that they could choose from. However, this artificially limits the user and creates a very different user experience.

#### Further comments:

The radial menu was appreciated as well as the split design of the requirements list on the left and the graph on the right. The visualisation of the requirements were also positively received.

It was mentioned that the mock-up tool is annoying because it heavily limits actions.

## Implications

We will have to discuss with Dr. Tsankov whether and to what extent our UI should implement virtual networks, or more generally, to which level of detail we should display the network configuration. Furthermore, there are lots of small technical details, that we should clear up with Dr. Tsankov. For example, what is the relevant data that needs to be displayed when hovering over a node. Or that they wished to see real time sensor data of the network. However, we think our project doesn’t focus on creating a general purpose network monitoring tool. 

What’s more, there were many conflicts between what NetComplete provides and what a real user appears to need. The network operators communicated that they would prefer a more dynamic UI that also shows node and link failures and can apply real time configuration changes. We think that NetComplete was designed for a different use case, but due to a lack of expert knowledge on our part, it doesn’t make much sense if we act as intermediaries between network operators and the NetComplete team. Rather, we will forward this feedback to our stakeholder, so that the NetComplete team can get in contact with their potential users directly.

### Getting back to our study goals

#### How fast and how accurately can a new user verify a requirement in the network?

Our users were able to accurately identify the network requirements. Also they perceived themself to be reasonably fast. It seems that our current prototype achieves this goal.

#### How easily and reliably can a new user perform a "what-if" analysis?

In the in-person interviews we received the feedback that it is unclear what the function of the bulldozer tool is. To improve this, we should either find a more intuitive icon or use a tutorial. 

For the online questionnaire we used a quick tutorial and guided the users so that they don’t get stuck while performing a task. That is why we didn’t receive much feedback in this direction from the online responses. The users there were normally able to easily and reliably use our bulldozer tool to do a “what-if” analysis. This implies that with a little introduction, user approve of our general design of a “what-if” analysis and can perform it without problems.

We could improve the design of the bulldozer tool to make it more obvious that it is active. Also we should consider marking the cutted edges clearer.

#### Compare two methods to filter requirements

The users seemed to really like the radial menu so we should definitely focus on this input method in our UI. During our in-person interview, one valuable comment was that the radial menu likely works better in small network graphs, whereas filtering is essential for larger graph. Therefore it makes sense to keep both options available.
