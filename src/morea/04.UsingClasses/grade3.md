---
title: "WOD3: Modifying a class"
published: true
morea_id: grade3
morea_type: assessment
morea_outcomes_assessed:
  - outcome-classes
morea_sort_order: 1

morea_chartjs_data: "[4, 2, 1, 0]"
morea_chartjs_labels: '["Rx", "Av", "Sd", "DNF"]'
morea_chartjs_caption: |

  In this exercise, we updated Rectangle to add support for an outline.
    
---

<!--{% include assessment-chartjs.html %}-->

{%  include assessment-chartjs-wod.html Rx="< 10 min" Av="10-20 min" Sd="20-30 min" DNF="31+ min or incorrect"  %}

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