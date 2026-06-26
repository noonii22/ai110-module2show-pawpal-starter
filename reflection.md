# PawPal+ Project Reflection

## 1. System Design

* Add a pet
* Add the owners walking time preference
* Show tasks for the day

### Main objects needed for the system:
* Pet object that holds info like: name, breed, gender, weight, activity level, bool for needs meds
* Ownser object that holds info like: name, activity level, preferences object maybe
* Perferences object for the time slots owner has available and what time they prefer to walk the pet
* Pet appointments object so when the date and time pet needs grooming, medication and other scheduling factors 
* Daily schedule object that lists tasks and daily things to do and can be add, delete, and edit functions on it with task object
* Task object that allows ability to have name, duration, priority and type of task
* Scheduler object that takes all other objects like preferences and tasks and fits the tasks into the alotted prefernce times



**a. Initial design**

- Briefly describe your initial UML design.
- What classes did you include, and what responsibilities did you assign to each?

**b. Design changes**

- Did your design change during implementation?
- If yes, describe at least one change and why you made it.

---

## 2. Scheduling Logic and Tradeoffs

**a. Constraints and priorities**

- What constraints does your scheduler consider (for example: time, priority, preferences)?
- How did you decide which constraints mattered most?

**b. Tradeoffs**

- Describe one tradeoff your scheduler makes.
- Why is that tradeoff reasonable for this scenario?

---

## 3. AI Collaboration

**a. How you used AI**

- How did you use AI tools during this project (for example: design brainstorming, debugging, refactoring)?
- What kinds of prompts or questions were most helpful?

**b. Judgment and verification**

- Describe one moment where you did not accept an AI suggestion as-is.
- How did you evaluate or verify what the AI suggested?

---

## 4. Testing and Verification

**a. What you tested**

- What behaviors did you test?
- Why were these tests important?

**b. Confidence**

- How confident are you that your scheduler works correctly?
- What edge cases would you test next if you had more time?

---

## 5. Reflection

**a. What went well**

- What part of this project are you most satisfied with?

**b. What you would improve**

- If you had another iteration, what would you improve or redesign?

**c. Key takeaway**

- What is one important thing you learned about designing systems or working with AI on this project?
