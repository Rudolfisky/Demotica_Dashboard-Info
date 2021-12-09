# Demotica-Dashboard: Dashboard Design | How do i make a clean yet informative Dashboard?
In this document I will use the DOT research framework in order to establish a good dashboard design for my project. 

## What dashboard designs have other people made?
In order to make a dashboard myself, I need an understanding of how other people tackled this problem. In order to aquire this knowledge, I will be doing a available product analysis.
### Dashboard on hardware
On [this link](https://computertotaal.nl/artikelen/internet-thuis/zo-maak-je-een-eenvoudig-dashboard-voor-je-domoticasysteem/) I found a tutorial for making a raspberry pi with a display that acts as a dashboard for a MQTT broker. This kind of dashboard is one that runs on a device dedicated to displaying that dashboard.
![related image](https://api.reshift.nl/modules/media/show_image/569967/?width=640&crop=center)
### Android Dashboard application
[This link](https://play.google.com/store/apps/details?id=app.homehabit.view&hl=nl&gl=US) leads to an playstore app that allows the user to create their own dashboard using within the app. The dashboard can be made up to the user own specs using multiple popular integrations like MQTT, home assistant, Domoticz and more.
![related image](https://play-lh.googleusercontent.com/m1KCENqg8pVep7qdtcdrYjJtVnd--lH_t_7KP8phH-WuebTzTULqoSsQxt16IHIah_8=w2560-h1315)
<br/><br/>
### In conclusion
There are a lot diffrent ways to make a demotica dashboard, almost all of them are customizable. Most of Dasboards take the form of a piece of hardware dedicated to displaying said dashboard, or are mobile applications. 

## What are some good dashboard guidelines?
In order to start working on a design, I first need to know what makes a dashboard a good dashboard. 
With some help from [this website](https://www.eleken.co/blog-posts/dashboard-design-examples-that-catch-the-eye) I had found a few things to keep in mind for when designing my dashboard.<br/>
Firstly, a good dashboard should require the user to look for no longer then 5 seconds for all required data.<br/>
Secondly, the user should be able to see the most important things first.<br/>
Last but not least, the user should not be overwelmed with data.

## What are my dashboard requirements?
before I start working on possible wireframe designs, I will have to sum up my dashboard requirements.
The requirements are as follows:
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
On the main page I have only put the essentials. you can see the indoor, outdoor and graph along with a fullscreen and settings button.
On a side note, the cube in the top left is supposed to be a cog wheel.
![dashboard-pc.png](https://github.com/Rudolfisky/Demotica_Dashboard-Info/blob/development/Media/dashboard-pc.png?raw=true)
![dashboard-mobile.png](https://github.com/Rudolfisky/Demotica_Dashboard-Info/blob/development/Media/dashboard-mobile.png?raw=true)
### Settings
In the setting I have put some more technical settings regarding api call intervals.
Same as with the mainpage, the button on the top left is supposed to be the back button with a back arrow.
![settings-pc.png](https://github.com/Rudolfisky/Demotica_Dashboard-Info/blob/development/Media/settings-pc.png?raw=true)
![settings-pc.png](https://github.com/Rudolfisky/Demotica_Dashboard-Info/blob/development/Media/settings-mobile.png?raw=true)
<br/><br/>
An alternation on the first design using dropdowns instead of buttons.
<br/>
![settings-pc.png](https://github.com/Rudolfisky/Demotica_Dashboard-Info/blob/development/Media/settings-mobile-alt1.png?raw=true)
