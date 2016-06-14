---
title: "Practice"
published: true
morea_id: itunes2
morea_type: experience
morea_sort_order: 8
morea_summary: "ITunes Array"
morea_labels:

---

# Practice: ITunesArray

So far we've been working with composing shape objects with GUI Java classes. Now we're going to practice composing objects that only output to the console.

## Instructions

### Part I: `ITunesArray`

<!--{% include wod-times.html Rx="<15 min" Av="15-30 min" Sd="30-45 min" DNF="45+ min" %}-->


1. Open your Java Project called `ITunes_uLogin`
1. Create an `ITunesArray` class that: 
    * Stores a list of songs as an array, and initializes the list to be empty.
    * Has a constructor that takes the maximum capacity as a parameter.
    * Has a method `addSong` that takes a `Song` as a parameter and adds it to the next open position. What should happen when the array is full?
    * Has a `print` method that prints the entire song list using a for each loop. It shouldn't print empty (`null`) objects.
    * Has a `main` method that adds 3 songs to the `ITunesArray` class and prints them out by calling the `print` method.


*If you don't feel confident in Part I, **STOP. Do not** move on to Part II.*


## Part II: `ITunesArray` challenge methods

<!--{% include wod-times.html Rx="<10 min" Av="10-20 min" Sd="20-30 min" DNF="31+ min" %}-->


Add the following methods to the `ITunes` class and test them in `main`:

  * Create a `getTotalPrice` method that returns the total cost of the entire song list.
  * Create a `getMinimumPrice` method that returns a `Song` with the lowest price in the list

## Demonstration

In class.

<!--Once you've finished doing the WOD a single time, watch me do it:

{% include youtube.html id="cNWowv9ZkMs" %}

{% include wod-warning.html %}-->
