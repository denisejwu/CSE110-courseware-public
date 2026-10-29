# Lemon Clicker Bug Report

**Name:**
**Tickets solved:** <!-- e.g. 1, 2, 3, 5, 6 (at least five) -->

Copy the template below once for each ticket you solved. 

---

## Ticket <3>: <ticket Lemon 4 Stops>

### Actual cause

<!-- Which file and function was the bug in, and what was wrong with the code?
     Explain why that code produced the behavior described in the ticket. -->

**File / function:**
src/screen/gamescreenview randomize lemon position fucntion

**What was wrong:**
it was rounding the numbers to be whole numbers
### Fix

<!-- What did you change, and why does that change fix the problem? -->

### How did you find it?
I found it because I was looking at the randomizer =lemon position because i knew the error was there
realized that it was rounding the numbers

#### Hypothesis testing

**What hypothesis ultimately led you to identify the buggy code, and why?**
The hypothesis is that if it keep rounding the number of the positions of the lemon they will only land in the same 4 spots simply because of the math equation without the rounding it will allow for more various positions

#### Backward tracing

<!-- Start from the symptom you saw and work backwards, one step at a time,
     until you reach the buggy line. For each step, note where you looked
     and what you saw there. Add steps as needed. -->

1. **Symptom:** <!-- what you saw, e.g. text on screen, console error -->

2. **Traced back to:** <!-- where that came from, e.g. a function, a request in the Network tab, a server log -->

3. **Traced back to:**

4. **Buggy code:** <!-- the file, function and line where the trace ended -->

<!-- It is okay to use your judgement here in limiting the number of traceback steps. We want to understand your 
    reasoning for how you discovered where the bug was -->

### Confirming the fix

<!-- How did you confirm the problem is gone? -->
confirmed the fix by testing if the lemon was no longer in the same 4 spots 

