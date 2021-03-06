---
title: "PHW8"
published: true
morea_id: pwod6
morea_type: experience
morea_sort_order: 6
morea_summary: "Forest"
morea_labels:

---

# PHW8: Forest

In class we saw how to compose objects to create a BoxCar class, and in [PHW6]({{ site.baseurl }}/morea/06.Composition/pwod5.html) you created a Tree class. Now we're going to create another composite shape: Forest.

{% include wod-times.html Rx="<25 min" Av="25-50 min" Sd="50-75 min" DNF="75+ min" %}

## Instructions

1. If you haven't been following along in class, download the [Picture Project]({{ site.baseurl }}/morea/06.Composition/Picture_tree.zip) and import it into your workspace.
1. Create a new `Forest` class with:
    * Fields: at least 3 Trees (using a Collection such as ArrayList recommended). When drawn, the trees should overlap a little bit. For example: <BR>
    <a href="forest.png"><img src="forest.png" width="100"/></a>
    * A constructor with 4 parameters: `x`, `y`, `width`, & `height`. The width & height represent the overall width & height of the forest, *not* an individual tree.
    * A `paint` method that has a `Graphics` parameter and calls the corresponding draw methods for the trees.
1. Test your new `Forest` class by replacing your `Tree` field(s) in the Picture class. 
1. Modify the position & sizes in the Picture class to change the look of your forest(s). Look at how easy it is to aggregate (i.e., reuse) components!

<!--## Demonstration


Once you've finished doing the WOD a single time, watch me do it:

{% include youtube.html id="Oq0Nc5ZLYHc" %}


### My Final Project

[Picture_forest.zip](Picture_forest.zip)

{% include wod-warning.html %}-->
