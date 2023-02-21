## Design implementation reviews

The beginning of the development marks the beginning of the design reviews. Review design early and review it often. A good rhythm is doing it weekly. A good day for that is Thursday. Book a Thursday in the calendar.

Sit down with the developer, open the design project, and write down the corrections in the comments while explaining to the developer the reasons for corrections (so the developer can learn how to understand the design better and be able to catch all nuances of the design). Follow up on the implementation of the corrections in the next design review. If the project is unavailable on Zeplin, open a Design review task on Productive (open subtasks for each correction - it is easier to follow up in this way). Attach screenshots with marked corrections and comments to the Productive task if stuff gets complicated.

Sometimes the design reviews may be frustrating because of the slow implementation of the past reviews, but it is crucial to keep on. Remember, there might be higher priority issues; in the end, it’s all about collaboration.


## Latest build

If you're reviewing a mobile app, check **[Tryout apps](https://tryoutapps.com/users/sign_in)** for the latest builds on iOS and Android.

## Development and testing environments

A test environment is any space in which software undergoes a series of experimental uses. To fully grasp the definition of a test environment, consider how a typical app gets deployed and managed. There are times when developers make clones of the main codebase and deploy them separately to iron out bugs and glitches in different virtual machines. The location and state of these parallel apps are what we’re calling test environments.

We typically have four environments along any software’s lifecycle:

- **Development:** This is where developers spend time writing the first lines of code. From here, an app transforms from concept into the MVP.
- **Testing:** This is where application testing is conducted to find and fix errors.
- **Staging:** A staging environment is meant to simulate production as much as possible.
- **Production:** The last environment in software development, this is where new builds/updates are moved into production for end users.

## Types of testing environments

Testing environments are a critical part of the software development lifecycle. Before moving to production, the app will have undergone test executions looking to break it in a safe environment.

Listed below are the most common types of testing environments and the ones you will often hear about from software testers and developers:

- **Performance Testing:** Measures how fast an app responds to an interaction. Various aspects of an app, such as page load speeds, input processing, stability, and so on, are tested in this environment.
- **System Integration Testing (SIT):** The main purpose of system integration testing is to check if all modules, such as code modules, individual applications, and client and server applications, can communicate with each other as per share the same database.
- **User Acceptance Testing (UAT):** UAT is conducted to check if the application meets the business requirements of the end users. This is the final stage of testing. If the features and functionalities of the application satisfy the end user, the app is moved to the production environment.


## Test devices

When checking implementation, we use mobile devices from our Test Lab. Each office has its own Test lab, usually consisting of a shelf with test devices. For instance, in the Zagreb office, all test devices can be found on the 7th floor next to the QA team.

Device claiming is described in detail in our **[General Handbook](https://infinum.com/handbook/general/doing-your-work/test-devices)** and the **[QA Handbook](https://infinum.com/handbook/qa/onboarding/test-devices-and-accounts).**

We're working a lot more remotely, so you'll need to check implementation from time to time even if you don't have physical devices on hand. That's where **[BrowserStack](https://app-live.browserstack.com)** comes in - its an emulator of a lot of different platforms, desktop and mobile devices where you can load app files to test them out. The credentials are in 1Password.
