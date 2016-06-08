---
title: "PHW6"
published: true
morea_id: itunes
morea_type: experience
morea_sort_order: 7
morea_summary: "ITunes"
morea_labels:

---

# PHW6: ITunes

So far we've been working with composing shape objects with GUI Java classes. Now we're going to practice composing objects that only output to the console.

## Instructions

### Part I: `Song` & `ITunes` basic

{% include wod-times.html Rx="<15 min" Av="15-30 min" Sd="30-45 min" DNF="45+ min" %}


1. Create a new Java Project called `ITunes_uLogin`
1. Create a new `Song` class with:
    * **4 Fields:** for a song's title, artist, album, & price
    * **2 Constructors:** a default with no parameters and one with a parameter for each field
    * **9 methods**: getters & setters for each field, and toString.
      * You can automatically generate getters & setters in Eclipse by right-clicking anywhere in the class and going to `Source > Generate Getters & Setters` and clicking `Select All`.
      * `toString` is a special [Java method](https://docs.oracle.com/javase/7/docs/api/java/lang/Object.html#toString%28%29) that returns a string representation of an object. When we don't define a `toString` method and we try to print an object, we get its [location in memory](http://www.dreamincode.net/forums/topic/209515-basics-of-tostring/) instead!
1. Create an `ITunes` class that: 
    * Stores a list of songs as an `ArrayList`, and initializes the list to be empty.
    * Has a method `addSong` to the `ITunes` class that adds a song to the `ArrayList`.
    * Has a `print` method that prints the entire song list using a for each loop.
    * Has a `main` method that adds 3 songs to the `iTunes` class *without* using the default constructor, and prints them out by calling the `print` method.


*If you don't feel confident in Part I, **STOP. Do not** move on to Part II.*


## Part II: `ITunes` challenge methods

{% include wod-times.html Rx="<10 min" Av="10-20 min" Sd="20-30 min" DNF="31+ min" %}


Add the following methods to the `ITunes` class and test them in `main`:

  * Create a `getTotalPrice` method that returns the total cost of the entire song list.
  * Create a `getMinimumPrice` method that returns a `Song` with the lowest price in the list

## Demonstration

In class.

<!--Once you've finished doing the WOD a single time, watch me do it:

{% include youtube.html id="cNWowv9ZkMs" %}

{% include wod-warning.html %}-->
