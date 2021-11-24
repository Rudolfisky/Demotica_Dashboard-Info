# Demotica-Dashboard: Dashboard Design
In this file i will note down the possible design choices and ux requirements the related to the front end.

## Research
In order to start working on a design, i first need to know what makes a dashboard a good dashboard. 
With some help from [this website](https://www.eleken.co/blog-posts/dashboard-design-examples-that-catch-the-eye) i had found a few things to keep in mind for when designing my dashboard.
Firstly, a good dashboard should require the user to look for no longer then 5 seconds for all required data.
Secondly, the user should be able to see the most important things first.
Last but not least, the user should not be overwelmed with data.

## Requirements
the requirements are as follows:
1. The dashboard must display inside the temperature acurate to 10 seconds
2. The dashboard should have a fullscreen mode for dedicated tablets and dedicated monitoring devices
3. The dashboard should display a graph with averages from previous data such as:
  1. Average from previous hours 
  2. Average from previous minutes
  3. Average from previous days
4. The dashboard should have settings where one can change both graph and temperature display settings.
5. The dashboard should be able to switch to darkmode for oled devices
6. The Dashboard Must show the outside temperature.

## Designs
### Mainpage
On the main page i have only put the essentials. you can see the indoor, outdoor and graph along with a fullscreen and settings button.
On a side note, the cube in the top left is supposed to be a cog wheel.
![dashboard-pc.png](https://github.com/Rudolfisky/Demotica_Dashboard-Info/blob/main/Media/dashboard-pc.png?raw=true)
### Settings
In the setting i have put some more technical settings regarding api call intervals.
Same as with the mainpage, the button on the top left is supposed to be the back button with a back arrow.
![settings-pc.png](https://github.com/Rudolfisky/Demotica_Dashboard-Info/blob/main/Media/settings-pc.png?raw=true)