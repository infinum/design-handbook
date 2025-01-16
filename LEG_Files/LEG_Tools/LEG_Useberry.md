Useberry is a **user-testing platform that uses your clickable prototype to get actionable insights from real users**. You can use it for both moderated and unmoderated sessions. It supports Card Sorting, Tree testing, Surveys, and 5-second tests as well, so you can go wild and combine different techniques in your study.

Useberry works with prototypes for desktop, mobile, or tablet products. You can **import the prototypes from Figma** simply by copying the URL of the prototype. Then you create tasks and pose questions to see how they react to your product. There are some Useberry-specific prototyping rules that can help you avoid troubleshooting. 

To conduct research with Useberry, you can use Infinum’s professional Useberry account. Set your research goals, sign in, add a project and let the tasks flow! There is a dedicated handbook chapter that can help you define user tasks that will allow you to achieve research goals.

After the testing, you get a UX report based on the participants' behavior and the answers they've given. Useberry tracks and **records user interactions, such as clicks, scrolls, and taps**. This allows you to see exactly how users are interacting with the product or system, and to identify any issues or pain points that users may be experiencing. 

Additionally, Useberry **provides heatmaps**, which provide visual representations of user behavior and can be used to identify patterns and trends in user interactions. All data can be filtered and segmented based on different criteria, such as demographics.

If you like looking at spreadsheets, you can get a .csv file with results; if you like vibrantly visualized and interactive results, Useberry prepares a lot of graphs for you.

To summarize, creating a Useberry is **a mid-game move**. You'll first have to cover the foundations of usability testing by doing these three:

- Defining research goals and checking with the client if they're ok with it
- Defining user tasks that would allow you to achieve research goals
- Preparing a Figma prototype that lets you do 1. and 2.

## Preparing the Figma prototype for Useberry

Some **Useberry-specific prototyping requirements** need to be respected if you want the two to work together. And it’s not really a 2-minute plug & play action, be ready to spend some time working on this. 

After a couple of years of trial and error and Useberry troubleshooting, we have distilled some advice that can help you prepare your prototype for Useberry. Please let Nina know if you think we need to update or add some of the advices 🙂

- **Start with creating a separate Usability testing prototype file in Figma**. Uploading your regular (usually huge) design file to Useberry will probably end up in Useberry crashing, and you in troubleshooting. Unlink component libraries from the prototype file as it contributes to information overload.
- **Useberry supports interactive components as well**. In this case, please be careful to enable interactive components manually on every single task that uses them! Otherwise, the heat maps will not be synced with the screens users were clicking on.
- **Clean unnecessary screens and flows**, leave just the ones you need for the testing (plugin Clean can help).
- Sometimes, you might even need to **compress your high-resolution images** and videos to optimize your Figma file and prototype. Plugin named Downsize can help you with this part.
- **Useberry supports Figma overlay functionality**. So feel free to use it!
- **All the components that are on the screens have to be in the frame.**
- **Untangle different tasks’ flows**. If you have two or more intersecting flows, participants can jump between tasks in the middle of the mission, and get stuck in a maze. This also means that sometimes you will have to make three homepages, each for a different flow/task. 
- **You can create more than one flow for each mission**, as Useberry lets you test multiple paths that represent different ways your users can achieve their goal. 
- **Keep it real and remove any placeholder or dummy content**. Trust us on this one, participants tend to fixate on illogical placeholder content, which makes their feedback less useful. Try to align the content with tasks participants have to perform during the study and keep the information consistent on all screens (names, phone numbers, payment amounts, language, etc.). 
- **Don’t test keyboard, data picker and other standard interactions.** When the user taps on the input field, just fill it in with data. You don’t need to mock the process of typing on the keyboard. The user presses any letter on the keyboard and input miraculously appears in the input field.
- **Design a simple success screen.** It can help your research participants review and comment on the last screen of the mission at their own pace, as Useberry would remove it after a delay of a couple of seconds.
- **Name your screens meaningfully.** In Useberry, you have to manually select the starting screen for each mission. When you have more screens that look the same, naming them meaningfully can help you select the right one (by meaningfully, we mostly mean naming them “Task 1”, “Task 2”, etc.).
- Set the permissions for your Figma file and prototype to **"Anyone with the link can view"**. If you don't, the prototype preview will not load and testers won't be able to view your prototype in the test. When the sharing permissions are set right, simply copy the Figma prototype URL and paste it into Useberry to start building your test.
- **If you make any changes after importing the prototype, sync it manually**. Your Figma prototype will not be updated automatically in Useberry. 
- **Check the study preview** before putting it in the hands of users. Previewing is a great way to ensure your study flows nicely, and that your users see what you want them to see. So, test the prototype yourself (or ask for a new couple of eyes) to make sure there are no broken links or missing elements.
- **Check the study preview on different-sized devices and adjust the design if needed.** Keep in mind that your prototype is not that responsive. Sometimes it happens that users don’t see the button at the bottom of the screen as their screen size is too small.
- **Duplicate the Useberry file before publishing it.** Otherwise, you won't be able to correct that small mistake you made while prototyping when you find it. 

We hope these 2300 tips helped you import a prototype and publish study without a lot of hassle. If you end up with an error screen after going through all of these tips & tricks — ping Nina, or check [Useberry’s help resources](https://intercom.help/useberry/en/collections/2582558-figma).


