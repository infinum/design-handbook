Tidiness and organization of files and project folders is an essential part of your job. More and more of our projects are becoming long-term, so this is an important segment for us. This love story is dedicated precisely to that :)

We usually store our project files in project folders on Google Drive. Keep your folders clean and tidy. Old and outdated documents should be archived (filed in an *Archive* subfolder) to avoid clutter.

**Working on local files is a no-no**, but there are some situations where we can't avoid this (files are huge/somebody else is also working with it). In that case, you **must** upload the files later on to Google Drive.

We currently take care of 4 things:

1. Project folders (in alignment with PM)
2. File tidiness
3. Versioning
4. Export

## 1. Project organization

- It is up to you to set up the project folder and keep it up to date.
- You are also in charge of maintenance **but in collaboration with the PMs.** PMs and developers usually may use the Resources folder here and there for documentation. Designers use everything else, so most of the responsibility is yours.
- If the project already exists,  in cooperation with the PM, organize it according to the instructions we have outlined. 
- 📚 Mandatory reading: [Keep It Clean: Project Folder Organization Template](https://infinum.com/the-capsized-eight/keep-it-clean-project-folder-organization-template)

### New projects

When starting a new project, ping David when you start working on UI. We will schedule 2 meetings: 

- First meeting – the designers and reviewers agree on how to approach the organization of a new file.
- Second meeting (scheduled three weeks after the first one) – we will check the project's status, open the review task and write down things that need to be fixed.

After the second meeting, further reviews will be transferred to the design coordinator. From that moment, the design coordinator is responsible for executing the review task.

### Ongoing projects

- Design coordinators are responsible for ongoing projects they oversee.
- If something is not ok, the design coordinator will open the tasks in the [Team: Design > File reviews](https://app.productive.io/1-infinum/projects/1888/tasks?board=108220&filter=MjQzOTky) board and, together with the designer, write down all the issues that need to be fixed.
- A designer should write an estimation of the task, ping the project PM, and ask for approval of those hours.
- If the PM declines the requested hours, they must write down an explanation in the same task. (If the PM is not added to the project, ping a TL, and they will add him). When we get the explanation, the design coordinator should move the task to the "Not reviewed" column and add the "Inactive/PM approved" tag to it.
- If the PM approves the request, the designer should put a deadline on the task and finish it by then.
- If the designer is no longer scheduled on the project, they still need to mention the task on our weekly design scheduling meeting and request hours to solve the file review task at some point. 
- If you see that you won't be able to complete something within the agreed deadline, you should write that in the task and postpone the deadline. The deadline can be moved once. If the tasks are not solved within the agreed deadlines, the designer will receive a 🟨 yellow card from their team lead. Designers shouldn't leave messy files behind them because it makes the job harder for the rest of the project team and for designers who will take over at some point.


## 2. File tidiness

### Naming convention

If a colleague takes over your project, the naming convention will help them onboard faster. Here are a couple of pointers:

- You should never have two screens with the same name.
- Name the screens meaningfully. Mention the flow and description of the screen. This will help developers, clients, and colleagues understand what's happening on the screen more straightforward.
- Logical page order and page names will keep everyone on the same page. Separate different flows into pages.
- Keep a consistent naming convention, and grid-align the frames.

Naming conventions for **Pages**:

- Onboarding
- Home
- Notifications
- Archive

Naming conventions for **Screens (Frames)**:

- *Flow - Name of the screen - State*
- Onboarding - Language picker - Selected
- Schedule - New visit - Filled
- My profile - Appliance details - Software version
- Rooms - Floor view - Tags


### Flows

Sub-flows will make it easier to locate screens in an extensive feature flow. For example, you'll find a "Checkout" flow more easily if it's highlighted instead of drowned in a complete "Store" flow. Oh, and let it breathe! Visually distance flows for more straightforward navigation through the file. 

### Components

Master Components (or Symbols) allow you to reuse elements easily across your document's Artboards and Pages, so try to use them as often as you can. When creating them, use [Auto Layout](https://help.figma.com/hc/en-us/articles/5731482952599-Using-auto-layout) and [Variants](https://help.figma.com/hc/en-us/articles/360056440594-Create-and-use-variants) to optimize your workflow.

Bounds are also a must so that the assets of the same type (icons, images) are the same in size, thus making the developers' job a bit easier. Keep symbol names logical and tidy. Use them regularly!

### Styleguide

To make our files/projects more organised and consistent, we use an appropriate style guide (web, Android, or iOS - depending on a project). Working with the style guide as you go along with the project will make your life easier later on. We set all the elements in the style guide as symbols, so every change you make will automatically update in the style guide as well. Just so you have an overview of all the things that are, or need to be, included there is a checklist Artboard that needs to be updated/checked as the project moves along. You can find our set of reusable templates for your project in Figma.

### Archive and work in progress

Save all versions of your designs; you'll never know when you might revisit a draft or scrap. Put those screens aside for safe-keeping in one of these ways:

- A separate flow (use different color or icon)
- A separate page in the file (Archive page)
- A separate file (include "archive" in the file name)

It's important to highlight those screens somehow. If another designer views your file, they need to know what's not final within a second. Cross out those we are not implementing (or you think that the client will change their mind). The line should have a thicker stroke (〜50px) and Infinum red (you know the red hex code by heart, right? 😃) with 50-70% opacity.

### Notes

Feel free to leave notes under screens or flows. Sometimes a screen flow can be complicated, decisions questionable, things are happening in the background, and after a few months — you're not sure why you made that decision. Create a note component and help yourself and others after you.

### Legacy projects

Sometimes we need to update something or add a feature in an old legacy project that no one opened in years. They do not follow our current standards. For these projects, we should have a status explanation on the first page. This explanation should have hold information about missing or broken things in the file and the reason for why they can't be fixed (due to a fixed budget, the client didn't want it or some other reason).

When creating new features for a legacy project, follow our current guidelines (create text styles, group flows, use components, etc.).


## 3. Versioning

**Figma** autosaves all your work and creates versions on its own, but it's not so easy to navigate through auto-generated versions, so make sure you **save versions on your own after** finishing a specific task or a chunk of work. Versioning in Figma is as easy as it gets; click **File → Save to version history** and name it in a way that makes sense and is easy to find.

# Why all this bureaucracy?

There are no problems while you're working by yourself, but if something comes up while you are on vacation and someone needs to jump in ASAP... Well, that might be a problem. If a colleague doesn't know where everything is, a 15-minute task can quickly become several hours of soul searching and digging. All the latest files should be online in some form (Figma, Abstract or Google Drive).

We support creative clutter, but it's a good idea to do a 15-minute cleanup once a week to keep everything tidy. It would be the best if you did this every day for a few minutes when you're finished with work, or while doing some kind of recap in your head (I understand that sometimes there is no time for that).

Take half an hour on **Mondays (schedule it like it's fun) and go through your projects (active ones and those that you think will be active for some time). Clean them up a bit if you haven't already.** If that cleanup takes too much time, make a plan and work it out over the upcoming weeks parallel with ongoing tasks.
