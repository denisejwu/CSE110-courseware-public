# Lemon Clicker Bug Report

**Name:**
**Tickets solved:** <!-- e.g. 1, 2, 3, 5, 6 (at least five) -->

Copy the template below once for each ticket you solved. 

---

## Ticket <2>: <ticket Best Score always shows 0>

### Actual cause

<!-- Which file and function was the bug in, and what was wrong with the code?
     Explain why that code produced the behavior described in the ticket. -->

**File / function:**
server/index.tx function app.get
**What was wrong:**

### Fix

<!-- What did you change, and why does that change fix the problem? -->
I changed the less than sign to greater than
### How did you find it?
found it because I needed to understand how stat was being used

#### Hypothesis testing

**What hypothesis ultimately led you to identify the buggy code, and why?**

#### Backward tracing

<!-- Start from the symptom you saw and work backwards, one step at a time,
     until you reach the buggy line. For each step, note where you looked
     and what you saw there. Add steps as needed. -->

1. **Symptom:** <!-- what you saw, e.g. text on screen, console error -->
the error was that the best was alwasy 0
2. **Traced back to:** <!-- where that came from, e.g. a function, a request in the Network tab, a server log -->
I traced it first in the menuscreenview lines 77-80
3. **Traced back to:**
from there i went to server index
4. **Buggy code:** <!-- the file, function and line where the trace ended -->
I looked at the code and try to understand what was going on and then realized that best was alway less than any number
<!-- It is okay to use your judgement here in limiting the number of traceback steps. We want to understand your 
    reasoning for how you discovered where the bug was -->

### Confirming the fix
I can confrim that i was fixed because now it shows best higest score to be indicated no longer says best is always 0
<!-- How did you confirm the problem is gone? -->

