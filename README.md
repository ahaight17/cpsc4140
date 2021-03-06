# CPSC 4140 Human Computer Interaction

## Don Norman's Theories

### Seven Stages of Action
1. **Forming the goal**
    - Pretty self explanatory
1. **Forming the itention**
    - Plan to turn my goal into an intention to act
1. **Specifying an action**
    - Specify an action sequence
1. **Executing an action**
    - Perform this sequence
1. **Perceiving the state of the world**
    - Perceive the change
1. **Interpreting the state of the world**
    - Interpret the change
1. **Evalutating the outcome**
    - Evaluate the outcome

***

### The Gulf of Execution
The difference between intentions and allowable actions is the Gulf of Execution

*Ex. printing a document*
- **Failure to form an intention**
    - I didn't realize that I can print my document
- **Failure to forumlate an action sequence**
    - I don't know where to find the print button
- **Failure to execute the action**
    - Some other dialogue is open and preventing me from clicking buttons

### Gulf of Evaluation
The Gulf of Evaluation reflects the amount of effort that the person must exert to interpret the physical state of the system and to determine how well the expectations and intentions have been met.

*Ex. the default printer is wrong*
- **Failure to perceive the outcome**
    - I didn't notice the default printer in the dialogue
- **Failure to interpret the outcome**
    - I notice it but think it is the correct printer
- **Failure to evaluate the outcome**
    - I notice it is wrong but think it is a glitch

***

### Six Principles of Deisgn
1. **Visibility**
    - Users need to know their options and how to access them
1. **Feedback**
    - Every action needs a reaction. *Ex. sounds, animations, popup, etc.*
1. **Affordance**
    - The relationship between what something looks like and how it is used
1. **Mapping**
    - The relationship between control and effect. With good design, the controls should closely resemble what the effect. *Ex. the scroll bar represents where you are on the page*
1. **Constraints**
    - The limits to an interaction or interface. *Ex. screen size, an image peeking from the bottom of the page inviting users to scroll down*
1. **Consistency**
    - The same action needs to cause the same reaction. Every time. 

***

### Three Levels of Design
1. **Visceral Design**
    - Concerns itself with appearances. Refers to the perceivable aspects of design and how they make the user act/feel. Essentially the concept "branding".
        - Much of product design is now focused on visceral design
2. **Behavioral Design**
    - Has to do with the pleasure and effectiveness of use. Can be referred to as usability.
        - Interested in how quickly and accurately users can achieve their goals
3. **Reflective Design**
    - Refers to the rationalization and intellectualization of a product.
        - Can I tell a story about it? Do I identify with it? The highest level of emotional design.

***

### Images
Designers and users alike use images to reason about functions/uses of the system
- **Designer Image**
    - How the designer thinks the system should work
- **System Image**
    - How the system actually works
- **Use Image**
    - How the user thinks the system works

Most usability problems happen because of a mismatch of system and use images. 

**Why does this happen?**
- The designer creates the UI based on the system image
- The user has to infer the system image from the UI

***

### Mental Models
Don Norman reasons that irrespective of concept design, users will always have their own unique mental models rooted in personal experiences and worldviews. Mental models are based on beliefs, not facts, and **always in flux**. 
- **Mixed up mental models**
    - Many usability problems stem from users having mixed-up mental models that **confuse different parts of the system**
-  **Mental model inertia**
    - People tend to stick the familiar. New interaction styles can be difficult to adapt to and should only be implemented when they are **vastly** superior to old systems.
- **Acting on mental models**
    - When users erroneously interact with your system, it is often due to a discrepency in their mental model with the actual implementation. A designer has two options in this case:
        - Make the system conform to the user's mental model
        - Change the users mental model by designing a better UI

***

### Constraints
- **Phsysical constraint**
    - Object can only be used in one way
- **Cultural constraint**
    - Usability is determined by culture
- **Semantic constraint**
    - Use is determined by situation
- **Logical constraint**
    - Use should be intuitive because of relationship between spatial location, functional use, and end result

***

### Affordance
Refers to the ability of an object or a product to communicate its **function**
- **Signifiers**
    - An indicator that can be meaningfully interpreted in a way that increases affordance
- **Feedback**
    - An indicator to show what the reaction to a user action is

***

## Neilson's Heuristics and Guidelines
1. **Visibility of system status**
    - The user should always know where they are, what they are doing, and the result of any actions they take through appropriate feedback
1. **Match between system and the real world**
    - The system should speak the language of the user; it should be intuitive and easily understandable
1. **User control and freedom**
    - Users should be able to exit their current state easily and rapidly
1. **Consistency and standards**
    - Users spend most of their time on websites that aren't yours. Follow standard conventions or risk confusing your users and adding to their mental load
1. **Error prevention**
    - Prevent avoidable errors through user confirmation actions (pop-up dialogues) or through layout design
1. **Recognition rather than recall**
    - Show all objects and actions available to the user or risk adding to their mental load
1. **Flexibility and efficiency of use**
    - Beginner users should not be overwhelmed with the interface and master users should be able to tailor their interface to speed up common and repeated actions
1. **Aesthetic and minimal design**
    - More information = more mental load. Think Google.com
1. **Help users recognize, diagnose, and recover from errors**
    - Error messages should: state the problem, why it happened, and give users the option to quickly and easily recover
1. **Help and documentation**
    - Give the user all the resources they need to use the product as intended

***

## Design Principles for Screens

### Layout
- **The screen should contain at least 65% white space, ideally 80%**
- **White space should be evenly distributed across the upper and lower halves of the page**
- **Screen layout should be more or less vertically symmetrical**

### Elements
- **Avoid unnecessary colors and embellishments**
- **Add emphasis only when necessary**

### Navigation
- **Should pass the "trunk test":** 
    - If a user dropped somewhere random on the website, will they know where they are?
- **Users should always know:**
    - Which site they're on
    - Where on the site they are
    - How to get back to the previous page and where can they go from here
    - How they can get home
    - How they can get help
- **Create clear visual hierarchy to reflect the task, not the program**
- **Visually group subtasks**
- **Keep recurring elements in consistent locations**

***

## Design Principles for Menus

### Types
- **Textual, graphical or combination**
- **Linear or spatial**
- **Static, pull-down, pop-up**
- **Single or multiple choice**
- **Isolated or hierarchical**
- **Pie menus**

### Elements
- **Show items that can be selected**
- **Show items that currently cannot be selected (deemphasized**
- **Show items that have already been selected**
- **Show the presence of submenus**

### Naming
- **Should be short and meaningful**
- **Must be clearly different from other options**
- **The most significant word should come first in multi-word menu names**
- **Be consistent**

### Length/Order
- **Menus should be kept between 5 and 8 items**
- **Longer menus should:**
    - Group items by task
    - Have a natural sequence
- **Should not be nested more than 2 or 3 levels**
- **Frequently used items should go at the top**
- **Conflicting or "dangerous" items should not be grouped together**

### Icons
- **Icons should be recognizable, distinguishable, and pleasing**
- **Form, color, and size and much more important than detail**
    - Abstract icons are actually easier to recognize
- **Similar objects or functions should be assigned similar icons**
- **Textual labels make it easier for beginners**

***

## Design Principles for Forms

### Label Positioning
- **Position form labels where you see fit**
    - Make them close (but not too close)
    - Use visual connectors if the space between label and form is large

### Input Format
- **Allow flexible input format**
- **Communicate when a special format is required**
    - Units (like $, ft., mph) and separators (like -, /) should be part of the label
    - Give examples like “mm/dd/yy”
- **Mark required fields**
- **Split long alphanumeric codes in groups of 2-4 characters**
    - Allow users to easily advance with Tab key or auto-advance

***
## Special Considerations for Web
- **Use linear or hierarchical link structure**
- **Make use of "breadcrumbs" a.k.a. showing users how they got where they are**
- **Don't break the back button**
- **Links should indicate they are links:**
    - Underlined
    - Color
    - Buttons
    - Items in columns (menu)
    - Textual hints
    - Mouse rollover
    - Changing cursor icon
    - Semantics
- **Links should indicate their action**
- **Make use of site maps and global site search**
- **Design webapps like standalone programs**

***

## Special Considerations for Mobile Design
- **Infinite scrolling**
- **Enable zooming**
- **Make use of gestures**
- **Have consistent placement of familiar elements**
- **Hide information/controls in menus**
- **Make use of targeted information**

