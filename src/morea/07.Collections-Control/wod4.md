---
title: "WOD"
published: true
morea_id: wod4
morea_type: experience
morea_sort_order: 4
morea_summary: "Timer"
morea_labels:

---

# WOD4: Timer

So far we've been working with composing shape objects with GUI Java classes. Now we're going to practice creating a `Timer` class that outputs to the console & uses if statements. Your `Timer` class will count up from 0 and print "You have no time left!"

{% include wod-times.html Rx="<10 min" Av="10-20 min" Sd="20-30 min" DNF="31+ min" %}

## Instructions

1. Write down your start time on your notecard.
1. Create a new Java Project called `Timer_uLogin`
1. Create a new `Timer` class with:
    * **Fields** to store: the time elapsed (seconds or minutes) and the time limit. *Think about what types these should be.*
    * A **constructor** that takes the time limit as a parameter. What should the time elapsed be initialized to?
    * A `tick` method that increments the time elapsed. If the time elapsed is greater than or equal to the limit, print "You have no time left!"
    * A `time_left` method that returns how much time is left.
    * A `print` method that prints out useful information for the timer. *Think about what information you want to know when you look at a timer that's counting up.*
1. Test your `Timer` class by writing a `main` method that creates a new `Timer` stored in a local variable, `timer`, that counts up to 3. Call `tick` 3 times, printing your `timer`'s status after each call. Do you correctly print when there is no time left?<BR>
Here is an example output:<BR>
Time: 0<BR>
Time: 1<BR>
Time: 2<BR>
You have no time left!<BR>
Time: 3<BR>

3. Export your program by right-clicking on your project folder, and selecting `Export > General > Archive File`. Name the file `Timer_uLogin.zip`.
2. Upload the file to the assignment page on canvas.
4. Write down your stop time on your notecard.
