---
layout: post
title:  "Ferrari 360 - Momo Steering Wheel"
date:   2025-01-30 08:05:14 -0400
categories: cars
---

![momo](/images/momo/12.jpg)

I replaced the factory steering wheel in my Ferrari 360 wheel for pretty cheap. This procedure should work for all Ferrari 360s and the airbag equipped models of the Ferrari 355. Note that I do lose my airbag here - that's not a complaint, as my air bag is 25 years old and I don't trust that it still works anyways. 

Parts Needed:
* [Hill Engineering Momo Boss Hub(SWS-355B F355 Steering Wheel Spacer
)](https://www.ricambiamerica.com/sws-355b-f355-steering-wheel-spacer.html)
* [Momo Steering Wheel](https://amzn.to/42w0FjL) - I got one with yellow stitching to match my interior
* [3.3 ohm .5 watt resistor, or similar](https://amzn.to/3WFbBrj)
* [Horn Button](https://www.ebay.com/itm/154687784793?_skw=momo+ferrari+horn&itmmeta=01JJVQEN631YMQTXEDNK5ZEK8R&hash=item24041c4759:g:U5gAAOSwZI5mOOj-&itmprp=enc%3AAQAJAAAA0HoV3kP08IDx%2BKZ9MfhVJKknbIwvbUQbfYVcCw6dzScE3B7OMdktFWycCneCJ9%2FcnZg4lIS3xHOohsDxEp1bl3y2UeBbNFA3JNcTBYNnoJMqDAANz6C5gRFQkGT6TD5jHOS6WrOtdoVGrbjdpiEr7Ht8yKS9iWiU6EvFdMhGk%2FPbXZk6dN6mZ138Qfjvo1H1avJnqQ%2Fu0YK26dN23IPmYzqjC2qvC2e2YAQ9DB6NF9A2x5qgQyy%2B123ZtDPsMeQkAvC3qjEpWpXgU%2FVdNfP8xlg%3D%7Ctkp%3ABk9SR5jTuveWZQ) - my steering wheel came with a Momo button, but I used a Ferrari Prancing Horse button instead. A 58mm horn button fit perfect. 
* [Blue Loctite](https://amzn.to/3WBriQo)

![momo](/images/momo/1.jpg)

Tools
* [T30 TamperProof / Security Torx Bit](https://amzn.to/3WAU183) - this is used for 2 screws on your factory steering wheel
* [Hex 5 bit or Allen Key](https://amzn.to/3Cq6Nzn)

This is a pretty simple install. 

First, turn off your battery! You are working with the airbag which can be dangerous if it has power. You have a battery cutoff switch in the frunk. I like to lay a blanket covering the the frunk/bumper area so I don't accidentally close the frunk while the power is off. 

![momo](/images/momo/2.jpg)

Then, pop the covers off on the backside of your steering wheel, your fingers should work, if not a small flat head will. 

![momo](/images/momo/3.jpg)

Remove the 2x Torx 30 security screws. 

![momo](/images/momo/4.jpg)

This is all that is holding your air bag in, so disconnect it now. 

![momo](/images/momo/5.jpg)

Remove the 4x 5mm Hex bolts holding on the steering wheel, marked in blue paint on my picture. 
 
![momo](/images/momo/6.jpg)

Disconnect the 2 connectors (ground and power for the horn buttons) and remove the steering wheel. 

![momo](/images/momo/8.jpg)

Your next step is to install the Boss Hub adapter, however I think it'd be easiest to go ahead and hook up a connector to ground. My steering wheel came with 2 spade connectors on wires - hook a wire up to ground to make that connection longer for your new horn button. 

![momo](/images/momo/7.jpg)

Then install your boss hub, routing the 3 wires (ground, power, airbag) through the hub. There are 4x 5mm Hex screws that attach it to the factory mounting point - use a tiny bit of blue loctite on it when installing. I didn't torque these, but they're on pretty snug. 

![momo](/images/momo/9.jpg)
![momo](/images/momo/10.jpg)

Almost done! Your hub is on, time to install the wheel using the 6 included Hex screws. Mine came with 6 short and 6 longer screws, I used the longer ones and installed in a star pattern, just hand tight. 

![momo](/images/momo/11.jpg)

Finally, you have the 3 connections to make. For your air bag, put the resistor across the 2 leads and either electrical tape or heat shrink it. This will trick the Airbag ECU to think an air bag is installed, so it won't show an air bag light on your dash. I have read that resistors near 3.3 ohms  will work to mimic the resistance in the factory air bag, however ones as high as 10ohms did not work. Various Fchat threads indicated that 3ohm, 3.3ohm and 4.7ohm resistors worked. If you don't have a resistor, your air bag light will light up on the dash, and apparently it takes a SD1 or SD2 (expensive Ferrari scan tool) to disable. So this part is important if you don't like dash lights!

![momo](/images/momo/13.jpg)
![momo](/images/momo/14.jpg)
![momo](/images/momo/15.jpg)
![momo](/images/momo/16.jpg)

For the other two connectors, the one we added the extension to is your ground, this goes on the outside of the horn button's connection. The final one with the stock plastic adapter is the power, I bent the horn power connector a bit to make this fit. 

Turn the battery on and test your horn before seating the horn button for good. Done!

![momo](/images/momo/12.jpg)

I did not have a good connection on my resistor to start, therefore I had the Air Bag light come on. Fortunately, my [Autel AP200](https://amzn.to/4hzwcp8) with the Ferrari module (an additional $22) was able to read and clear the Air Bag code. I initially tried cutting the leads on the resistor shorter - don't do that. Use the long leads, put them all the way in, then secure the resistor. 
