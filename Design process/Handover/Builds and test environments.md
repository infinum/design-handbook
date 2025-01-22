## Latest builds

Check out [Tryout apps (🔒 Internal use)](https://tryoutapps.com/users/sign_in) for the latest builds for both iOS and Android.

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

Device claiming is described in detail in our **[General Handbook](https://infinum.com/handbook/general/everyday-processes/equipment-handling/test-devices)** and the **[QA Handbook](https://infinum.com/handbook/qa/onboarding/test-devices-and-accounts).**

We're working a lot more remotely, so you'll need to check implementation from time to time even if you don't have physical devices on hand. That's where **[BrowserStack](https://app-live.browserstack.com)** comes in - its an emulator of a lot of different platforms, desktop and mobile devices where you can load app files to test them out. The credentials are in 1Password.
