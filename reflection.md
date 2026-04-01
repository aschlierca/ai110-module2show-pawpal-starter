# PawPal+ Project Reflection

## 1. System Design

**a. Initial design**

- Briefly describe your initial UML design.
  Initial UML connects User->Pet->DailyShow, Generator separate
- What classes did you include, and what responsibilities did you assign to each?
  Users: manage info, trigger schedule, add&edit tasks
  Generator: create schedules
  Pet: store pet info and preferences
  DailyShow: display pet tasks

**b. Design changes**

- Did your design change during implementation?
  Yes
- If yes, describe at least one change and why you made it.
  Added is_due to check task timing

---

## 2. Scheduling Logic and Tradeoffs

**a. Constraints and priorities**

- What constraints does your scheduler consider (for example: time, priority, preferences)?
  time, priority, preferences
- How did you decide which constraints mattered most?
  time prioritized because it controls scheuduling

**b. Tradeoffs**

- Describe one tradeoff your scheduler makes.
  more detailed code
- Why is that tradeoff reasonable for this scenario?
  Reasonable because it improves readability

---

## 3. AI Collaboration

**a. How you used AI**

- How did you use AI tools during this project (for example: design brainstorming, debugging, refactoring)?
  Using for debugging and brainstorming
- What kinds of prompts or questions were most helpful?
  task-specific questions

**b. Judgment and verification**

- Describe one moment where you did not accept an AI suggestion as-is.
  when it was overcomplicated
- How did you evaluate or verify what the AI suggested?
  verified manually by comparing tasks

---

## 4. Testing and Verification

**a. What you tested**

- What behaviors did you test?
  Adding users/pets, sorting tasks, marking complete, filtering
- Why were these tests important?
  To test the core functions of the app

**b. Confidence**

- How confident are you that your scheduler works correctly?
  mostly confident
- What edge cases would you test next if you had more time?
  overlapping pet break times

---

## 5. Reflection

**a. What went well**

- What part of this project are you most satisfied with?
  completed functionality successfully

**b. What you would improve**

- If you had another iteration, what would you improve or redesign?
  I would fix Streamlit bugs and refine UI

**c. Key takeaway**

- What is one important thing you learned about designing systems or working with AI on this project?
  AI suggestions may overcomplicate or hallucinate
