# Week 2

## Weekly Goals

1. Use all of week 1's skills (don't underestimate the importance of this)
2. Break one class into two classes that work together, while maintaining test coverage
3. Unit test classes in isolation using mocking
  - Mocking exercise. 
  - Dependency injection exercise. 
4. Explain some basic OO principles and tie them to high level concerns (e.g. ease of change)
  - Exercise to test application of OOP principles.
  - Research forwarding and polymorphism.
5. Review another person's code and give them meaningful feedback

#### Plans to achieve:

Eóin suggests treating 1-4 in descending order of priority, so I have used this to formulate my plan for the week.

1. Continue using strict TDD process. Consolidate exisiting knowkedge of OOP principles by doing the [OOP_1](https://github.com/makersacademy/skills-workshops/tree/master/week-1/oop_1) exercise on encapsulation on Monday. Continue to request feedback for pairing, improving each day. Ensure I follow an effective Debugging process when I encounter bugs. 
2. Use Simple Checkout exercise on Tuesday to demonstrate this skill. Timebox to Tuesday as I have explored this skill already in Afternoon and Weekend challenges.  
3. Further explore mocking by beginning [Mocking_1](https://github.com/makersacademy/skills-workshops/tree/master/week-1/mocking_1) exercise on Wednesday and Thursday morning. On Friday morning, explore [Dependency Injection](https://github.com/makersacademy/skills-workshops/blob/master/practicals/object_oriented_design/dependency_injection.md).
4. Use Monday to do OOP_1 (see above). Tuesday lunctime, research abstraction and inheritance, and if there's time forwarding and polymorphism. Wednesday lunchtime, look at cocepts in [OOP_2](https://github.com/makersacademy/skills-workshops/tree/master/week-2/oop_2) and [OOP_3](https://github.com/makersacademy/skills-workshops/tree/master/week-2/oop_3). 
5. Code review on Monday?

## Daily Goals

#### Monday 18th May
- GOAL: 
  - To apply my knowledge of OOP principles. 
  - Get feedback on goal setting.
- PLAN: Begin the exercises in [OOP_1](https://github.com/makersacademy/skills-workshops/tree/master/week-1/oop_1).
- EVIDENCE: 
  - I completed the exercise in OOP_1, and will ask for feedback on the code snippet from a coach.
  - Send Week1.md to Eóin to ask for feedback.
- FEEBACK:
- **OOP Principles**
  - SELF-ASSESSMENT: I followed along with the video attached to the OOP_1 skills workshop, and then when the video ended prematurely, I went ahead and did the encapsulation exercise, seperating the methods into two classes, as well as creating a private method in the Calculator class. I feel I understood the principle of encapsulation that the exercise aimed to teach, and I was able to apply that principle.
  - COACH: Very useful feedback from Alice - I suitably demonstrated encapsulation as a principle, but could improve on that with dependency injection, which will also help me to isolate my tests. Alice also recommended I change the name of the Printer class to Formatter in order to reflect what the class does. I also learnt that to move a responsibility to another class is an OOP pattern called delegation. 
- **Goal Setting**
  - SELF-ASSESSMENT: I’ve found the process really helpful - I’ve found my goals to be realistic, though I have had to lower my expectations about what I can reasonably ‘finish’ in a week. On Week 1 my plan for the week did change, and I got a little bit worried about changing my focus - I had to relinquish my aim to do Debugging exercises as it took my longer than planned to do Birthdays, and I was worried that I wouldn’t be able to achieve the goal. But I can rest safe in the knowledge that I'll be using debugging frequently!
  - COACH: Really [positive feedback from Eóin](https://drive.google.com/open?id=1RiDjDdrdme0RFeVZSJIzfV86btWRH4mp) about my Week1 portfolio.

#### Tuesday 19th May
- GOAL: 
  - To understand the process of breaking one class into two and be able to apply this skill whilst still maintaining test coverage.
  - To define 'abstraction' and 'inheritance'. 
  - To be able to create a Domain model diagram - Class and Sequence. 
- PLAN: 
  - Begin the Simple Checkout exercise highlighted in kick-off - perhaps use this to also explore mocking?.
  - Use brief time after lunch to make notes on OOP principles.
  - Attend the workshop that covers this and do the exercises asked. Use this skill to create a diagram for my Simple Checkout.
- EVIDENCE: 
  - Ask for some feedback on the exercise from a coach, as well as self-assessment. 
  - Be able to explain to another person what I have researched and made notes on - peer group on Friday morning?
  - Also ask for coach feedback on Simple Checkout diagrams and README.
- FEEDBACK:
   - SELF-ASSESSMENT: I don't feel like I got much done on the Simple Checkout, as I only managed to create the repository and begin on the Domain Model DIagram after lunch. I'm a little confused about how the "split" is going to happen - my plan creates four classes initially, but I think if I follow the user stories and feature test as I go along, only fulfilling each requirement at a time, I should get to the point where I need to split the 'Item' class into a Basket. I wonder if the basket becomes a subclass of Items?

#### Wednesday 20th May
- GOAL: 
  - To continue with the aim of breaking one class into two.
- PLAN:
  - Continue with the Simple Checkout exercise.
- EVIDENCE:
  - Given that I might not be able to finish Simple Checkout, it may be worth doing a screen recording of my work in order that a coach can see it. In tandem with the README it will help to show my approach. Also, gem installs - RSPec and Simplecov?
  - Be able to explain to another person what I have researched and made notes on - peer group on Friday morning? Consider creating a presentation to illustrate my knowledge of OOP as I go along.
- FEEDBACK:
  - SELF-ASSESSMENT: I managed to do a really great sequencing diagram for Simple Checkout and after sharing that with another member of my cohort I realised that I could use mocking and dependency injection in this exercise. Consequently, I can reformat my plan for the week and spend Thursday and Friday on this exercise, rather than doing individual exercises for mocking and dependency injection. As such, I've decided to stick with sending a completed repo to a coach next week.
  
#### Thursday 21st May
- GOAL:
  - To continue applying my knowledge on how to break a class into two, and also use mocking and dependency injection.
  - To define 'forwarding', and 'polymorphism'.
- PLAN:
  - Continue with the Simple Checkout exercise, using it to demonstrate the knowledge of mocking and dependency injection that I learned yesterday.
  - Research and make notes on the aforementioned OOP principles. 
- EVIDENCE:
  - Examples of both doubles and method stubs in my Simple Checkout tests.
  - Being able to explain these concepts to my peer group. 
- FEEDBACK:
- **Breaking a class into two, mocking, and dependency injection**
  - SELF-ASSESSMENT: Although I didn't get to actually breaking the Checkout class and delegating its private formatter method, I did use doubles and method stubs to test my classes in isolation. I feel like I've got a good grasp of testing with doubles now, even using an each block to stub in different return values for my check_price method in my Checkout class. 
- **OOP Principles** 
  - SELF-ASSESSMENT: I didn't manage to get on to defining 'forwarding' and 'polymorphism' today as I was helping another member of my cohort with the Simple Checkout exercise. I will move this research over to the weekend. 

  
#### Friday 22nd May
- GOAL:
  - To use dependency injection.
- PLAN:
  - Perform the last stage of the Simple Checkout class, delegating the format_price method to a Formatter class, and use dependency injection to be able to test both Checkout and Formatter in isolation. 
- EVIDENCE:
  - A completed repository should be sufficient to demonstrate the skills I've set out to apply. I may also take a screen recording of this last stage in the process, in order that I can suitably evidence this week's goal of breaking a class into two. 
- FEEDBACK:
  - **Breaking one class into two**
  - SELF ASSESSMENT: I am really pleased with my completed SimpleCheckout, and feel that I have suitably understood and applied my goals this week.
  - COACh: Eóin gave me really positive feedback on my [SimpleCheckout](https://github.com/NikitaDouglas/SimpleCheckout). ALthough I added a layer of potentially unecessary complexity with the `buy_item` method, defined on the `Item` class, I suitably demonstrated a sound knowledge of the principles involved.


## Reflection


### Question 1

*Did you meet all of your goals to the standard you set at the start of the week?*

Yes, I think I did. I maintained my practice of Week1's goals, as well as applying mocking, doubling, dependency injection, and extraction with the SimpleCheckout exercise. I enjoyed Code Review and feel that I gave good feedback. 


### Question 2

*What would you change/improve moving forward?*

I feel like I'd benefit from understanding when to use sub-classes, and to better understand the difference between forwarding and delegation in order that I can show my knowledge of these OOP principles in practice. 

