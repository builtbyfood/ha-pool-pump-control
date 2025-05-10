<header>

<!--
  <<< Author notes: Course header >>>
  Include a 1280×640 image, course title in sentence case, and a concise description in emphasis.
  In your repository settings: enable template repository, add your 1280×640 social image, auto delete head branches.
  Add your open source license, GitHub uses MIT license.
-->

# How to Use This Blueprint

</header>
<br>
<br>
Save this YAML in a file named pool_pump_schedule.yaml in your /config/blueprints/automation/ directory
<br>
In Home Assistant, go to Configuration → Blueprints
<br>
Find "Pool Pump Speed Schedule" and click "Create Automation"
<br>
Fill in the entities for each speed switch:
<br>
<br>
Low Speed: switch.sonoff_100204e49b_2
<br>
Medium Speed: switch.sonoff_100204e49b_3
<br>
High Speed: switch.sonoff_100204e49b_1
<br>
<br>

Adjust the season dates if needed (defaults match your specification)
<br>
Save the automation
