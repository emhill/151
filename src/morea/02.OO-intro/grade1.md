---
title: "WOD1: Hello Me"
published: true
morea_id: grade1
morea_type: assessment
morea_outcomes_assessed:
  - outcome-eclipse
morea_sort_order: 1

morea_chartjs_data: "[1, 1, 5, 0]"
morea_chartjs_labels: '["Rx", "Av", "Sd", "DNF"]'
morea_chartjs_caption: |

  In this exercise, we created a new Java project from scratch in eclipse, printed something, and exported the project & uploaded it to canvas. Overall, an excellent start to the semester!
  
---

<!--{% include assessment-chartjs.html %}-->

{%  include assessment-chartjs-wod.html Rx="< 3 min" Av="3-5 min" Sd="5-10 min" DNF="11+ min or incorrect"  %}

<!--<link rel="stylesheet" href="http://cdn.oesmith.co.uk/morris-0.4.3.min.css">
<script src="//cdnjs.cloudflare.com/ajax/libs/raphael/2.1.0/raphael-min.js"></script>
<script src="http://cdn.oesmith.co.uk/morris-0.4.3.min.js"></script>

<div class="well" style="width: 550px">
  <div id="assessment" style="width: 500px; height: 250px"></div>
  Follow the Eclipse project workflow we'll be using for the rest of the semester. "Satisfactory" indicates that working Java code was submitted, but that the Eclipse project was flawed in some way.
</div>

<script>
Morris.Bar({
  element: 'assessment',
  hideHover: false,
  data: [
        { y: 'Excellent (%)', num: 12 },
        { y: 'Satisfactory (%)', num: 12 },
        { y: 'Unsatisfactory (%)', num: 1 },
        ],
  xkey: 'y',
  ykeys: ['num'],
  resize: true,
  labels: ['Students']
});
</script>
-->