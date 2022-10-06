# bgmeter
Rainmeter skin for displaying BG values from Nightscout

This is a simple skin that displays your current glucose value and trend arrow. Data is pulled from [Nightscout](http://www.nightscout.info/). It changes color based on the BG value. Going from red to green as the value changes from the low to the middle value, and changing from green to red as the value changes from the middle to the high value. By the default the values are 70, 120, and 200, but they can be changed.

## Setup
1. Clone/download this repository to your skins folder
2. Update the settings.inc.sample file to specify the URL to your Nightscout app. You can also change the low, middle, and high values if you wish
3. Save the file as settings.inc and load the skin
