<header>

<!--
  <<< Author notes: Course header >>>
  Include a 1280×640 image, course title in sentence case, and a concise description in emphasis.
  In your repository settings: enable template repository, add your 1280×640 social image, auto delete head branches.
  Add your open source license, GitHub uses MIT license.
-->

# Blueprint Features

</header>
<br>
<b>Customizable Entities:</b>
<br>
You can select which switch entities control each speed (1500rpm, 2500rpm, 3000rpm)
<br>
<br>
<b></b>Configurable Seasons:</header>b>
<br>
You can set the start and end dates for the cool season through the UI <br>
The warm season is automatically calculated as the remaining time of the year
<br>
<br>
<b>Preset Schedules:</b>
<br>
Maintains your specified time schedules for each speed in both seasons:
<br>
Cool Season: Low speed at 5:02-9:02 & 17:02-21:02, Medium speed at 9:03-17:01, High speed at 21:03-23:58
<br>
Warm Season: Low speed at 6:02-18:32 & 20:32-22:32, Medium speed at 2:03-5:03, High speed at 0:02-2:02
<br>
<br>
<b>Clean Operation:</b>
<br>
Turns off all speeds before activating the appropriate one
<br>
Checks for changes every minute
<br>
Only one speed will be active at any time
<br>
How to Use This Blueprint
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
<br>
<br>
Adjust the season dates if needed (defaults match your specification)
<br>
Save the automation
