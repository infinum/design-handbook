## Overview of Maze

[Maze](https://maze.design/) is one of your tools for [conducting usability testing](https://infinum.com/handbook/books/design/design-process/discovery/usability-testing). It's a user testing platform that uses your clickable prototype to get actionable insights from real users. 

Maze works with **prototypes for desktop, mobile or tablet apps**. You can import the prototypes from Figma, Invision, Marvel or Sketch, by copying the URL of the prototype. Then you create missions (tasks) and pose questions to see how they react to your product.

<br>After the testing, you get a UX report based on the participants' behavior and the answers they've given. You can choose: if you like looking at spreadsheets, you can get a .csv file with results; if you like vibrantly **visualized and interactive results**, you can click on the report Maze has prepared for you.

Creating a Maze is a mid-game move. You'll first have to cover the foundations of [usability testing](https://infinum.com/handbook/books/design/design-process/discovery/usability-testing) by doing these three:
<br>1. Defining **research goals** and checking with the client if they're ok with it
<br>2. Defining **user tasks** that would allow you to achieve research goals
<br>3. Preparing a **Figma prototype** that lets you do 1. and 2.

For 1. and 2. please read the chapter about [usability testing](https://infinum.com/handbook/books/design/design-process/discovery/usability-testing).

## Preparing Figma prototype

### Build prototype in a fresh Figma file
Big Figma file means a slow loading time of your Maze. In extreme cases, it might cause your Maze to crash. The reason? Maze loads up all the visuals in the file regardless of whether they're in the prototype or not.

### Untangle different tasks' flows
Trust us on this: If you have two or more intersecting flows, participants will find it and cross to the part of the product you didn't want them to see yet. In Maze, there's **no "Restart task"** button, so if participants got stuck somewhere and can't get back to the current task's flow -- they ARE STUCK and can't get back to the current task's flow. They'll need to give up on that task.<br>
<br>How to tackle that? Separate flows in the prototype. If it's necessary, make three homepages, each for a different flow/task. Maze let's you set a different starting screen for each task, so participants won't know that you got three homepages.

![](/img/tools-maze-7.jpg)

### Add hints
You're not testing users' recall of task instructions, but whether or not they can perform these tasks. It might make sense to give participants a little hint about what they're supposed to **choose among different options** on some screens. Make your hints distinct so that users to confuse them for part of UI.

![](/img/tools-maze-8.jpg)

### Keep it real
Most participants won't notice your designs aren't pixel-perfect, but they'll see illogical amounts, names, and changes from screen to screen. People get fixated on these things, which makes their feedback less useful. Try to check these three boxes:
<br>- **Consistent information** on all screens (names, phone numbers, payment amounts, language, etc.),
<br>- **Realistic information** the user would encounter in the real world (don't put just one obvious item or too many options to choose from on a screen),
<br>- **Working links** for most of the buttons that are usually clickable.

### Plan for information-oriented tasks
Sometimes you'll want to test if people can find some information in the app. Maze needs people to tap on something to recognize it as a task completed. You'll need to account for that: create a success screen in the prototype (a simple thumb up will do) that's triggered when the user taps on the information on the screen.

![](/img/tools-maze-9.jpg)

## Setting up your Maze

### Import your prototype
You'll need to **create a new project**. If we've reached the limit of active projects, ping colleagues in the #maze Slack channel and check which projects can be archived. It's hard to miss the input box where you should copy/paste your protoype's link. It will take Maze a few moments to load everything app, and you're ready to roll.

![](/img/tools-maze-1.jpg)


### Missions
You'll build your Maze out of blocks, *missions* being the most important ones.

![](/img/tools-maze-2.jpg)

Steps in creating a mission
<br>1. Add a new **mission block**
<br>2. Define **task's title**. Good practice: start with a verb, make it short, don't mention keywords on the screen, and use user-like language, not UX/UI or dev lingo.
<br>3. Write a **description** that gives users some context or data they'll need to input (create hints in prototype if necessary).
<br>4. Choose your **starting screen**
<br>5. **Click through the prototype** to define the ideal path(s) of completing the task. Maze counts those as "direct successes". Your prototype might allow users to get to the final screen using a different path, and that's ok -- these will be "indirect successes". 

When participants get to path's final screen, they'll get a "Well done" message within 0.2 seconds. Don't put any important information on that screen because it will leave participants hanging.


### Questions
After each mission, you should have **a follow-up question**. Ask people how easy is it to perform the task or find the information. Ease of use is the best predictor of real-life usage. These numbers will give your report objectivity and make it easier to communicate delight and pain points to the client.

Steps in creating a follow-up question:
<br>1. Add **opinion scale** block
<br>2. Write the **specific question**, not a generic one. *How easy was it to create your account?* is better than *How easy was it to do this?* Later, it will be easier to find a specific question in the report.
<br>3. Set the scale to **five points**
<br>4. Write the **left and the right label**. Usually, these are *Very hard* and *Very easy*

![](/img/tools-maze-4.jpg)

Of course, you can ask participants other types of questions. There are yes/no, multiple selection, and open-ended questions. Choose the ones that fit your testing best.<br>Use different kinds of questions to mix things up a bit for participants. Show them a part of the screen and ask them what they think some UI element means. Or, ask them how they perceive the tone and voice of the app. 



### Conditional logic
Imagine you just failed at something, and then someone asks you *"How easy was it?"*, you'd be agitated, wouldn't you? Thankfully, you can avoid that in Maze.<br><br>You can set conditional logic for each question: what's the next block participants see depending on their answer to a question or success in a task. E.g., the user gives up on task → they'll skip the ease of use question. Or, they're your client's customer → they skip a few onboarding tasks.

![](/img/tools-maze-10.jpg)

### Prototype refreshing
If you catch a typo or a link leading users to a wrong screen in your prototype, you can always refresh the prototype Maze uses. Go to any of the mission blocks and click "Refresh my prototype". Important: **Maze sometimes adds a random screen** to already defined paths, so double-check your paths after refreshing the prototype.

![](/img/tools-maze-11.jpg)

### Preview Maze and missions
Take your Maze on a test drive as often as possible. Copy/paste the preview link **to your mobile browser** and see if everything works as you've envisioned. You can preview specific missions; you don't have to go through the whole Maze to check your second to last mission.


### Customize welcome and thank you screens
Default options do a good job in English, but you should write your messages if you're testing in Croatian or some other language. 
<br>On the welcome screen, add your client's logo, so people have a visual cue they're in the right place. Write "Welcome" in your language of choice and translate the English instructions.
<br>Keep Thank you screen short and sweet.

![](/img/tools-maze-12.jpg)

## Publishing and reporting
Maze will warn you that there's no tweaking past that point. Double-check if everything's fine, and then PUSH THE BUTTON.

![](/img/tools-maze-6.jpg)

Share the link with the client or send it directly to your participants. [Look up here](https://infinum.com/handbook/books/design/design-process/discovery/usability-testing#remote-usability-testing) how to prepare your participants for Maze.

### Individual tester's data
You can see how each tester has solved your Maze. If there are some participants you want to omit from the report, you can **delete their data**.

### Closed for business
When testing is done, stop recording the data for your Maze. If you don't, some participants or someone from client's team might **accidentally start a Maze session**, which will then be a part of reported data. Better safe than sorry.

### First click metric
The first click is a powerful **discoverability metric**, but it's a bit hidden in Maze. How to open it? Click on published Maze → click on one of the missions → click on Aggregated paths → in the upper left corner, click on All clicks → Select just 1st click.

![](/img/tools-maze-13.jpg)

Maze report will give you a lot to work with. You can find some tips and tricks for creating a usability report in our [Usability testing chapter](https://infinum.com/handbook/books/design/design-process/discovery/usability-testing#3-analysis).

### When in doubt...

...visit [Maze Help Center](https://help.maze.co/hc/en-us) (specifically their [Usability Testing](https://maze.design/guides/usability-testing) article) or ask a colleague (Design or QA) who worked in Maze before.
