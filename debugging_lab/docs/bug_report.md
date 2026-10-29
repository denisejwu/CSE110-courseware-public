# Lemon Clicker Bug Report

**Name:**
**Tickets solved:** <!-- e.g. 1, 2, 3, 5, 6 (at least five) -->

Copy the template below once for each ticket you solved. 

---

## Ticket <1>: <ticket Stats unavaliable>

### Actual cause

<!-- Which file and function was the bug in, and what was wrong with the code?
     Explain why that code produced the behavior described in the ticket. -->

**File / function:**
It was in teh src/screens/MenuScreen/MenuScreenController
in the functon loadStats from sever line 47
**What was wrong:**
What was wrong was that the file name was 'stat' when it should have been 'stats'

### Fix

<!-- What did you change, and why does that change fix the problem? -->

### How did you find it?
found it by refering to the other functions and say that they refer to the stats as stats instead of stat

#### Hypothesis testing

**What hypothesis ultimately led you to identify the buggy code, and why?**
the hypothesis is was made because you are unable to find the file then it mean either the file name is wrong or its getting the wrong file
#### Backward tracing

<!-- Start from the symptom you saw and work backwards, one step at a time,
     until you reach the buggy line. For each step, note where you looked
     and what you saw there. Add steps as needed. -->

1. **Symptom:** <!-- what you saw, e.g. text on screen, console error -->
looked the console f12
2. **Traced back to:** <!-- where that came from, e.g. a function, a request in the Network tab, a server log -->
when clicking f12 to inspect the page saw the error
3. **Traced back to:**
also f12 led me to the specific place the erro was cause
4. **Buggy code:** <!-- the file, function and line where the trace ended -->
It was in teh src/screens/MenuScreen/MenuScreenController
in the functon loadStats from sever line 47
<!-- It is okay to use your judgement here in limiting the number of traceback steps. We want to understand your 
    reasoning for how you discovered where the bug was -->

### Confirming the fix

<!-- How did you confirm the problem is gone? -->
I confirm the fix by being able to see the stats avalible instead of stats unavaliable on the screen, can check by being able ot get the api status
