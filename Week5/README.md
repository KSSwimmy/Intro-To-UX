# WEEK 5: _Design Heuristics_

### Heuristics for Design

**From Knowledge to Guidelines** 

- Important to understand 
    - How people perceive 
    - How people remember 
    - How people act to pursue goals 

- How can system designs use this knowledge to inprove UX?
    - A: "Guidelines"

**Guidelines**

- There are many guidelines out there
    - Example: http://guidelines.usbility.gov/
    - Example: https://developer.android.com/design/index.html

- You could use any set of guidelines for an inspection 

- Choosing guidelines 
    - Are they well-supported and focused on user experience? 
    - Do they cover all the inmportant best practices? 
    - Do they apply to your platform/situation? 
    - Are they easy to use? 

**Jakob Nielsen's 10 Heuristics** 

- "Heuristic" means "rule of thumb" 
    - Slightly more general than a "guideline" 
- Derived from a systematic review of usability problems
- Intended to be a small, complete, and usable set 
- Able to be taught in a few hours
    - (though you get better with practice) 
- Well-supported by theories of perception and cognition

 ![10Heuristics](Week5Images/10Heuristics.png "10Heuristics")

---

### #1: Visibility of System Statues

**Visibility of System Statuses**

- Why? 
- Knowing that actions are available bridges the Gulf of Execution
- Knowing how the system responded bridges the Gulf of Evaluation 
- Echoes Norman's principles of Feedback and Constraints 

- **Feedback** 
    - Ex: Mouse hovering 

- **Available actions**
    - Things that you can do and can not do
![avalactions](Week5Images/avalactions.png "Available  actions")
- **General Availability** 
    - busy indicator 

  ![generalav](Week5Images/generalav.png "General Availability")

  - How users react to delay
    - Less than 100 milliseconds: "instantaneous" 
    - Up to 1.0 second: tolerable, but delay noticeable
    - Up to 10 seconds: annoying, but willing to wait 
    - More than 10 seconds: focus lost. on to something else 

- **Design guidelines** 
    - Strive for <100 msec response time 
    - Up to 1 second, no indicator needed 
    - From 1 o 10 seconds, use wait cursor 
    - Over 10 seconds, complete in the background, use progress indicators and estimates

---
### #2: Match Between System and Real World 


**#2: Match Between System and Real World**
- The system should speak the users' language, with words. phrases, and concepts familiar to the user, rather than system-oriented terms. Follow real-world conventions, making information appear in a natural and logical order. 

**Why?** 

1. Why is this important? Well, first, it allows us to take advantage of users existing schema or the associations that they already have between different pieces of information and how they're connected to goals and actions.

2. It also allows us to leverage perceived affordances and signifiers that suggest actions that are familiar to the users.

3. Reduces the difficulty of forming effective conceptual models because we're taking advantage of conceptual models that users already have.

4. It also allows us to leverage perceived affordances and signifiers that suggest actions that are familiar to the users, and it reduces the difficulty of forming effective conceptual models because we're taking advantage of conceptual models that users already have.


**Language**
Use words and phrases that are familiar to the user not system-oriented language.

**Metaphors**
![metaphor](Week5Images/metaphor.png "Metaphor")
So, for example, the user might infer that the shopping cart would also allow them to add multiple items, and to remove items, and even to abandon their cart without buying anything.

![metaphor2](Week5Images/metaphor2.png "Metaphor 2")
The document metaphor might suggest to users that they not only can create and save files, they can also delete them, they can copy them, and they can send or share them with other people.

It's important to make sure that systems that we design match the real-world expectations of users, so that they can take advantage of what they know from the real world and use it to effectively use the systems that we design.


---
### #3 - User Control and Freedom

**#3: User control and freedom** 

Why? 

- Mistakes are inevitable
- Support the 7 stages of action by allowing reformulated goals 
- Users employ trial and error to learn a new system 

![emexits](week5Images/emexits.png "Emergency Exits")

![undoRedo](week5Images/undoRedo.png "Undo Redo")

### #4 - Consistency and Standards

**#4 - Consistency and Standards**

Users should not have to wonder whether different words. situations, or actions mean the same thing. Follow platform conventions. 

Why? 

- Leverage users' schemas 
- Present a coherent conceptual model 

Being consistent allows us to present a coherent conceptual model, which makes it easier for users to learn how to operate the system effectively. 

Ex: 
"Search" vs "Submit query"
"Save" vs "Commit" 
"Crate" vs "New"

![consistencyex](week5Images/consistencyex.png "Consistency Example")

It's also important when designing a series or a suite of products to maintain consistency across those products, and we looked at this in an earlier lecture; but, for example, looking at the different Google apps for word processing and for spreadsheets, we see that a very similar layout is used for the menu bar and the formatting options. 

By deciding not to follow platform conventions, these website designers have created a system that's harder to use and harder to learn for somebody just coming to the system for the first time. 

---

### #5: Error Prevention 

**#5: Error Prevention**

Even better than good error messages is careful design which prevents a problem from occurring in the place. Either eliminate error-prone conditions or check for them and present users with confirmation option before they commit to the action. 

Why? 

Mistakes are common 
People don't see of read everything on the screen 
People make mistakes when typing, clicking, etc. 

![ErrorEx](week5Images/errorEx.png "Error Prevention Example")

![ErrorEx](week5Images/errorHandling.png "Error Prevention Example 2 ")

Preventing Errors before they happen if it's something risky. 

![ErrorEx](week5Images/risky.png "Error Prevention Example 2 ")

So, the key here is, wherever possible, you should try to prevent errors before they even happen, rather than just waiting for them to happen and helping users recover from it.

---

### #6 Recognition Over Recall 

**#6 Recognition Over Recall**

