Design documentation is what a brand book or a graphic standard manual is for graphic design projects – but for your website or app.

We use design documentation to keep the UI consistent, to quickly onboard new designers or team members and to ease the UI setup for developers.

A web or app design documentation may include:

<h3>1. Styleguide</h3>

- color styles
- typography styles
- effect styles (shadows, blurs, etc.)
- grids and layouts
- standard spacing elements
- brand assets
- communication tone&voice
- icon set
- photos
- guidelines on using these elements
- categorized UI components
  
<h3>2. Component library</h3>

- categorized UI components
- component specification, including variants and states (default, hover, focused, empty, loading, error, etc.)

<h3>3. Pattern library</h3>

- categorized patterns
- pattern specifications, usage guidelines, and examples of how to use them

<h3>4. App icon</h3>

App icons are a crucial part of a product’s visual identity and are often included in the Styleguide to ensure consistency across platforms. When creating app icons, it's essential to design versions for both iOS and Android, adhering to each platform's official guidelines and templates. Here you can find their official Figma templates to help you design app icons for your app: 

- [Figma template for Android app icons](https://www.figma.com/community/file/1131374111452281708)
- [Figma template for iOS app icons](https://www.figma.com/community/file/1387687009990313744)

However, when developing apps, we (especially developers and QA) work with different environments like production, staging and development to manage various stages of the process. To avoid confusion and make it easy to tell them apart, when needed, we have to create app icons with ribbons that show which environment they belong to. These icons help the team quickly identify the right version of the app and prevent mix-ups. Here is [our Figma template](https://www.figma.com/design/YJ8DCUje499dxvNNNvCehT/App-icon-ribbons-template?m=auto&t=Dr23tS6GAaFDygRH-6) which you can use to quickly add environment ribbons to your app icons.

<h2>When to document?</h3>

In short – **always**. But how you approach the documentation process will largely depend on the project size, complexity and, sometimes – timelines. Smaller, shorter projects may not require more than a concise set of guidelines, while complex, collaborative projects need more detailed and structured documentation to ensure consistency and quality in design.

Design pattern documentation, in particular, is useful for larger projects that involve multiple designers and developers, as it helps to ensure that everyone is on the same page throughout the project lifecycle. It can also help with projects that are intended to evolve, as it provides a solid foundation of building blocks for future design decisions and ensures consistency.

<h2>How to document?</h3>

There is no one-size-fits-all approach to design documentation. However, there are some best practices and general guidelines that you could try to follow.

For example, if you are working on a **short**, **in-and-out project**, let’s say – a web one-pager, chances are that you don’t need a particularly detailed design documentation. What you might do instead:

1. Create a single **UI design file** in Figma
  - Include UI of all screens in their various states (empty, loading, error, etc.)
  - Screens linked with arrows: Use arrows or connectors to indicate the flow between screens, clarifying which components lead to different parts of the application.
2. Add a separate page for your **basic styleguide** (e.g. colors, typography, grids and spacing, etc)
3. Add a separate page for your **main components**, with basic specifications, such as component states
4. If needed, add **small notes for developers** as a reminder of how a specific pattern is meant to behave and interact

<img width="2834" alt="1" src="https://user-images.githubusercontent.com/24880388/233973449-b6f0ecbc-c7e6-4f22-829f-0342c5e25943.png">
  
On the other hand, if you are just now building a foundation of what promises to be a **complex**, **long-term project**, with a potential to evolve even cross-platform, this is what you might want to do:

1. Create a **Figma project**
2. Create a **separate file for UI design**
3. Create a separate file for your **styleguide**, as a Figma project library
4. Create a separate file for your **components and patterns**, as a Figma project library
  - Map out and design all component variants
  - Map out all distinct design patterns
  - Add detailed specifications and guidelines for all design patterns
  - Show examples of pattern usage
  - Provide specifications for animations and transitions
5. Create a separate file for interactive prototypes

<img width="2834" alt="2" src="https://user-images.githubusercontent.com/24880388/233975678-80d7dc3c-34db-4b20-8d0d-8b9d12333577.png">

<h2>Useful links</h3>

Here are some best practice examples to get you started:

- [Material Design 3 - Web guidelines](https://m3.material.io/) 
- [Material Design 3 - Figma Design Kit](https://www.figma.com/community/file/1035203688168086460)
- [Ant Design System](https://www.figma.com/community/file/831698976089873405)
- [IBM Carbon Design System](https://www.figma.com/community/file/1127112416656936951)
- [Shopify Polaris Design System](https://polaris.shopify.com/patterns)
- [Design systems publication by Figma](https://www.designsystems.com/)
