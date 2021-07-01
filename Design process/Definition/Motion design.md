Since the introduction of smartphones, motion design has become a vital UX tool. When utilized right, it makes using technology feel natural, responsive, and more enjoyable.

Adding motion to user interfaces means doing a lot more than decorating. Animation is a functional element used for giving feedback to an action and helping users understand the app's hierarchy and flow of information. 
 

# When to use motion

Before adding animations to a web page or app, ensure that their **goal and purpose are well-defined**. When considering an animation, contemplate the following questions:

- Where would the user’s attention otherwise be focused at the time when the animation occurs?
- How frequently will one user encounter it during one session?
- Is it triggered directly by a user’s action or indirectly (upon page load, while scrolling, or by some other unrelated activity)?
- Is the goal to:
    - attract users’ attention, so they notice something and act on immediately?
    - show continuity in a transition between the states of an object?
    - indicate a relationship between objects that are already in the user’s focus of attention?

Once you worked out the purpose, think about **how to visually approach solving the problem by using motion**: 

- **Feedback** - Provide instant and relevant feedback about a completed action and keep the user enlightened about what is happening..
- **State-change** - Draw attention to and explain changes on the page. Changes in the state of an element, revealing and hiding of content, or shifts to another area of content are all common areas for transitional animations. Communicate state changes that are not triggered by users’ actions.
- **Spatial and navigation metaphors** - Signal to users the direction in which they are moving within a process or hierarchy; this supplemental cue can make navigation through a complex IA more intuitive and understandable.
- **As a signifier** - Help users understand how to interact with UI elements. The direction (or other attributes) of the motion signifies the type of acceptable actions. For example, a card that expands from the bottom of the screen towards the top signals to the user that it can be closed by pulling down. A new card that comes from the right of the screen signals that it can be closed by swiping it to the right.


# Animation types

## Transitions

![](/img/designprocess-motion-1.gif)

Motion design comes in to help users understand the app flow between screens, making the navigation easier. Another way to use motion design in transitions is during loading times. Why not shorten the waiting time with an interesting animation? Animations help hold users' focus while the device is downloading the necessary data.

## Micro-interactions

![](/img/designprocess-motion-2.gif)

Micro-interactions are events used to create an engaging moment with the user. Most of the time, the animation starts with a trigger (user action) that causes a reaction, letting the user know what’s happening, making the navigation inside an app or a website easier. We can divide micro-interactions into four steps:

**1. Triggers** — Initiates a micro-interaction

- **User-initiated trigger** — the user has to initiate an action (e.g. buttons)
- **System-initiated trigger** — software detects certain qualifications are being met and initiates an action (e.g. notifications)

**2. Rules** - what happens once a micro-interaction is triggered<br>
What happens when the user clicks this button? Are they directed to a new page? Will it add a product into their shopping cart? The same goes for system-initiated triggers.

**3. Feedback** - Lets people know what’s happening.<br>
Anything a user sees, hears, or feels while a micro-interaction is happening is feedback.

**4. Loops and Modes** - determine the meta-rules of the micro-interaction.<br>
What happens to a micro-interaction when conditions change?

Micro-interactions have to be **unobtrusive, brief and subtle.**

## Superfluous animations

![](/img/designprocess-motion-3.gif)

Surely, animations can also be simply decorative – as long as they don’t negatively affect user experience. These animations can create a positive experience for the user on a page that's inherently negative (empty states, onboarding flow).

# Interaction styleguide

<p align="center"><iframe style="border: 1px solid rgba(0, 0, 0, 0.1);" width="100%" height="450" src="https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Ffile%2FYCDdaMiHHl7NMh7j8D0yku%2FInteraction-template-WIP%3Fnode-id%3D1%253A9&chrome=DOCUMENTATION" allowfullscreen></iframe></p>

We've created this [interaction styleguide](https://www.figma.com/file/YCDdaMiHHl7NMh7j8D0yku/Interaction-library-WIP?node-id=188%3A102) to help designers (and devs) define and point out places in the app or website where these interactions occur.

You can also use some of our defaults for loading states, pressed states, hover states etc.

# The tools

## Principle

[Principle](https://principleformac.com/) — ease of creating animated flow from different applications or web screens through predefined animations allows motion designers to quickly and easily create an animated prototype.

Another big advantage of this software is the easy way of [importing screens](https://principleformac.com/docs.html#import) from the other design software, such as Sketch and Figma. 

🔗 [Principle: Documentation](https://principleformac.com/docs.html)<br>
🔗 [Principle: Tutorials](https://principleformac.com/tutorial.html)

## After Effects

[Adobe After Effects](https://www.adobe.com/products/aftereffects.html) has always been the most widely used animation tool. Being a more complex tool than Principle, more oriented towards explanatory videos and long-term animations, it is emerging as an essential interface animation tool.

While Principle allows us to create a fast flow and prototypes to present the main interactions of an application, After Effects lets us explore the creation of more complex effects and interactions.

One of the main reasons for the popularity of this software among motion designers is the [Bodymovin](https://github.com/airbnb/lottie-web) plugin, which allows the export of more complex shape animations to code, making it easier for developers to implement them.

## Lottie

[Lottie](https://lottiefiles.com/) renders animations exported from After Effects through the [bodymovin](https://github.com/airbnb/lottie-web) plugin. This makes integrating animated assets in apps and websites quick and easy. There's a [step by step tutorial that can be found on Design Islands.](https://design.infinum.com/case/using-lottie)

Although some After Effects features are not yet supported, this library is growing, allowing for the export of more complex shapes, masks, trim paths, solids, and alpha matte effects.

The community is continuously growing – check out more [great examples already created by the Lottie community](https://lottiefiles.com/account/dashboard).

## Motion for WordPress projects

Here are a couple of libraries that can come in handy when creating landing pages with Wordpress:
- [GreenSock](https://greensock.com/gsap)
- [anime.js](https://animejs.com)
- [barba.js](https://barba.js.org)

## 📚 Recommended reading

- [UI Movement](https://uimovement.com/) (Examples of UI Animations)
- [InVision's Animation Handbook](https://www.designbetter.co/animation-handbook)
- [Creating Usability with Motion](https://medium.com/ux-in-motion/creating-usability-with-motion-the-ux-in-motion-manifesto-a87a4584ddc) (Article)
- [How Motion Design Applies to UI](https://infinum.com/the-capsized-eight/motion-design-ui-design) (Article)
- [Motion Design Is the Future](https://blog.prototypr.io/motion-design-is-the-future-of-ui-fc83ce55c02f) (Article)
- [Motion Design School](https://motiondesign.school/) (Course)
