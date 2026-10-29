# Lemon Clicker Bug Report

**Name:**
**Tickets solved:** <!-- e.g. 1, 2, 3, 5, 6 (at least five) -->

Copy the template below once for each ticket you solved. 

---

## Ticket <5>: <ticket LeaderBoard Undefined>

### Actual cause

<!-- Which file and function was the bug in, and what was wrong with the code?
     Explain why that code produced the behavior described in the ticket. -->

**File / function:**
src/screen/resultscreen/resultmodel and veiw
one was in the const and the other was in update leaderboard
**What was wrong:**

### Fix

<!-- What did you change, and why does that change fix the problem? -->
I renamed the timestamp to be time

### How did you find it?

I found it because I was reading on how the screenresult was getting the entres and it shows that it has to get the infomration from the server and tehn from there i fixed it
#### Hypothesis testing

**What hypothesis ultimately led you to identify the buggy code, and why?**
so what led me to it was that after figuring out that the server was the one that gave the informaton to result screen I had to see how the results screen was showing and then from there I compared the constants that were being called and found that they have to have the same name so I changed the name timestamp to time that way it is consistent.

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
confirmed the fix by also eventually playing the game and seeing that the expected value is being shown which shows that it was now working correctly

