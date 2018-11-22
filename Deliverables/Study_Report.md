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
Due to the limitations of our prototype we had to help our users to interact with the mockup. This lead us to questions which focus strongly on the essential parts of our prototype and therefore our study.

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
`TODO`

## Implications
`TODO`
