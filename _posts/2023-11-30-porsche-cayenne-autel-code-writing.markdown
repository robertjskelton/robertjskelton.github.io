---
layout: post
title:  "Porsche Cayenne (958) - Autel Code Writing"
date:   2023-11-30 8:05:14 -0400
categories: cars
---

![Coding](/images/coding/3.jpg)

To get my [Porsche Cayenne Android Auto upgrade](https://rskelton.com/porsche-cayenne-carplayretrofits-androidauto-install/) working well, I had to enable the Aux input for the PCM, which can only be done through a PIWIS (Porsche scan tool) at a dealer, some Porsche independent mechanics, or a high end scan tool with a code writing function. I found out that the [Autel Maxisys MS906BT](https://amzn.to/3QTdxsI) that a friend let me borrow has the code writing function, and so I used it to enable the Aux input and a few other nice features on my 2014 Porsche Cayenne Diesel.

To clarify, you are not writing code like programming, but more changing settings that are locked by default in the car menus. It is very simple to do, just requires scrolling through lots of menus, being pateint, and wishing you knew how to read German. 

![Coding](/images/coding/10.jpg)

To start, plug the OBD2 scanner in, turn on the Autel tablet, then go to Programming, then Coding. This will probably start a diagnostic test on your car that will take about 5 minutes, then you can get to work. 

![Coding](/images/coding/11.jpg)
![Coding](/images/coding/12.jpg)

# Boost Gauge 

First, I enabled a Turbo/boost gauge on the car computer, this is a hidden setting not available on the Cayenne Diesel. To get to this section, go to Instrument cluster / All / On Board Computer display configuration factory setting. This menu, and most menus, are mostly in German, but you will see where there are some settings numbered 1, 2, 3, 4. That is on your Vehicle display on your dash - those 4 lines correspond to each numbered setting. I set line 4 as "Boost Pressure", which is your turbo. 

![Coding](/images/coding/7.jpg)

But you're not done there for the boost gauge - you need to set the scale correctly, or else it will just show your boost as 1 Bar at all times. This range can be set in Instrument cluster / All / Additional coding, and "Max.Boost for turbo", set that as 2.55. Note in my pic below that I tried 2.60 - the car will reject a value higher than 2.55 Bar. Then you'll be able to see how your Turbo is actually being used. 

![Coding](/images/coding/2.jpg)
![Coding](/images/coding/1.jpg)

However, most people aren't familiar with Bar as the units for boost, we like PSI. So let's get that selectable. To do that, under Instrument Cluster / All / Bordcomputer Menukonfiguration, I enabled the followed 4 items. 1 of them allowed Boost pressure to be changed from Bar to PSI in your Instrument cluster settings in your car (not from the computer.) I'm not sure what the rest enabled, but it seemed to add a "Aux heater" option to my instrument panel. 

![Coding](/images/coding/16.jpg)
![Coding](/images/coding/18.jpg)

# Aux Input
For your Aux to be enabled, that is under the setting for PCM/CDR / All / Auxliary (yeah it is not spelled correctly, German). Select Auxliary, then Activated, then Write. 

![Coding](/images/coding/4.jpg)
![Coding](/images/coding/5.jpg)

I enabled the Phone section of my PCM here, as it was not enabled on my headunit. 

![Coding](/images/coding/6.jpg)

# Auto fold Mirrors
I'd also recommend enabling the Auto fold mirrors option, which is changable later in your car without a computer. This can be done in PCM/CDR / All / Additional equipment / Automatic folding mirror function.

![Coding](/images/coding/15.jpg)
![Coding](/images/coding/17.jpg)

# Seat Belt Chimes
I also disabled the seat belt chimes, under Instrument cluster / All / Coding Value. I always wear my seat belt, but this Cayenne seems to beep at me when sitting in the car with my seat belt on, it got annoying. I changed the 3 lines shown below.  

![Coding](/images/coding/9.jpg)

# Splash Screen
I even changed the splash screen for the dash From "Cayenne" to "Cayenne Diesel", also under Instrument cluster / All / Coding Value.

![Coding](/images/coding/13.jpg)
![Coding](/images/coding/14.jpg)

Those are all the changes I put in through coding on the [Autel Maxisys MS906BT](https://amzn.to/3QTdxsI). If you followed my guide, I bet you saw this screen a ton. And if you know any other cool tips or tricks in these menus, email me and I can add them to this list. 

![Coding](/images/coding/8.jpg)