---
layout: post
title:  "GX470 Android Headunit and Backup Camera Install"
date:   2019-03-07 09:00:14 -0400
categories: cars
---

![Headunit](/images/lexus/headunit/backup.jpg)

I installed a new Android headunit in my 2007 Lexus GX470, complete with a reverse activated backup camera. The install took about 5 hours over the course of a few days, and here is how I did it.


### Parts Needed:
* [9 inch Android Headunit with Canbus](https://www.aliexpress.com/item/9-inch-car-radio-for-Toyota-Prado-120-2004-2009-Quadcore-Android-6-0-car/32801839608.html?spm=2114.search0104.3.24.5edff7d9xxAsrB&ws_ab_test=searchweb0_0,searchweb201602_1_10065_10068_10130_10890_10547_319_10546_317_10548_10545_10696_453_10084_454_10083_433_10618_10307_537_536_10902_10059_10884_10887_321_322_10103,searchweb201603_6,ppcSwitch_0&algo_expid=c0b5c1d2-1f43-48c9-8027-ff2257719e95-3&algo_pvid=c0b5c1d2-1f43-48c9-8027-ff2257719e95&transAbTest=ae803_5)
* [Backup Camera](https://amzn.to/2XJWMnt)
* [Bluetooth OBDII Adapter (optional)](https://amzn.to/2EL3NLR)

![Headunit](/images/lexus/headunit/parts.jpg)

So ordering the headunit is a little sketchy. It's from Aliexpress in China, and will take 2-4 weeks to arrive. This one comes with external GPS, microphone, a WiFi antenna, works with the existing aux input, and has 2 USB female cables to attach.

There seems to be only a few aftermarket headunits made for the non-Nav GX470, and the fine folks on [GXOR](https://www.facebook.com/groups/LexusGXOR) seem to think this is the best option. If you have a navigation equipped GX470, the best option is a Tesla-style massive screen. It costs quite a bit more and makes the air conditioned buttons integrated into the touch screen, which I would hate. Luckily I don't have that model!

### Install
First, take out any CDs in your current headunit. I forgot to do this. If you want to buy my old headunit, it comes with 6 great CDs!

![Headunit](/images/lexus/headunit/remove_air.jpg)

Then, remove the two trim pieces on either side of the shifter, using a flat head screwdriver or a plastic trim puller. I used a screwdriver.

Then remove the 2 air conditioner vents. Lift gently from the bottom, where the trim pieces were holding them in. These 2 pieces are supposed to be very expensive to replace, so be very careful.

Then, remove the connector from each side. The drivers side has the hazard light connecter, the passenger side has the passenger air bag light.

![Headunit](/images/lexus/headunit/left_air.jpg)

![Headunit](/images/lexus/headunit/right_air.jpg)

Now you can pop out and unplug the coin/ash tray and the cigarette lighter, located below the air conditioning controls.

Take the 6 10mm bolts out of the radio harness.

You basically have 3 pieces to your center stack.
1. Top - Clock/MPG display
2. Middle - Headunit, what we're replacing
3. Bottom - A/C controls

![Headunit](/images/lexus/headunit/screws.jpg)

Start taking screws out of the existing Lexus headunit. There were a lot of screws to remove these 3 parts, and I didn't document it, but prepare to spend a while on this. Also, you don't reuse MOST of these screws, I had a ton left over. Once done un-screwing, remove all the connecters and remove the whole thing from the car. I did this, and it made it much easier to install the new head unit into the metal harness.

![Headunit](/images/lexus/headunit/removed.jpg)

Note that the 10mm bolt, about where your knee is when driving (and shown just above my knee in the following picture), connects the harnesses that supply power. When testing your install, you'll need to screw that in all the way. This is something I found out later while debugging.

![Headunit](/images/lexus/headunit/10mm.jpg)

Once you have the pieces out of your car, you can install the new headunit into the same spot. The air conditioning controls will clip in below it. I installed the top piece after I had inserted the rest back into the car.

![Headunit](/images/lexus/headunit/schematic.jpg)

As far as connections go, this was pretty simple. Connect like to like connectors where you can find them. I ran the USB female connectors into the glove box, since I won't use them often and didn't want to mount them. I ran the GPS module behind the dash, and stuck it up as high and far back as I could, then used the supplied 3M backing tape. It gets a very good signal, even when not exposed. I chose not to mount the microphone that was included with the headunit, as the included mic on the front of the headunit seemed to do a good enough job for my uses. The WiFi antennae is short and is attached to the back of the headunit.

![Headunit](/images/lexus/headunit/chrome.jpg)

You'll also want to run your wiring for the reverse camera. For the part behind the headunit, wire the yellow into the backup camera input (9) and tap the reverse cable in. For the run to your back door, you'll need to do this on the passenger side, because of the way the rear door opens. I ran my wire behind the glove box and under the plastic tray on the seats, all the way to the 3rd row area.

![Headunit](/images/lexus/headunit/grommet.jpg)

This is where it gets more complicated. You'll need to run the wiring through the grommet thing seen above(hardest and most painful part of this whole project), and into the rear door area. There is almost no room inside the grommet to run the cable, so this will take some time. The rear door should paneling should be removed, which is pretty easy.

Damage from running the wiring through the grommet into the rear door.

![Headunit](/images/lexus/headunit/damage.jpg)

The wiring for the rear camera is simple. Connect the reverse power wire that you ran from the headunit (red), and the power wire (red) from the camera to the reverse light power wire, which is red with blue stripe. I used the passenger side reverse light since it was closer. Seal that connection with some solder.

![Headunit](/images/lexus/headunit/camera_wiring.jpg)

The yellow video cable from the camera connects to the RCA that you ran from the headunit. The ground (black) from the camera connects to any ground on the rear door, there are a quite few bolts you can use.

![Headunit](/images/lexus/headunit/installed.jpg)

At the headunit side, make sure you plug the yellow from the rearview camera into the correct video input. I did not do that the first time, and had to take apart my dash again. You want to use input 9, the rearview input.

![Headunit](/images/lexus/headunit/camera.jpg)

To mount the rear camera, I drilled 2 very small holes in the black plastic part directly above the license plate. I put the 2 camera screw in there with the camera, then ran the wire through where the drivers side license plate light was at. However, then the light wouldn't stay in its spot, since it had a wire blocking the seal. I drilled out a very small notch into that opening for the light, just big enough for the wire to run through. I placed the wire in there, seen below, then the light would stay.

![Headunit](/images/lexus/headunit/wire.jpg)

### Thoughts

I love the headunit. This was my first car audio install other than replacing speakers. The install was relatively easy, the inside of the car looks much nicer, and the audio is much better than flipping through radio stations or CDs. I have a 2007 GX470, which means it came with an aux port, and that is still functional with this headunit. The only downsides so far are that the screen became slightly unglued in the bottom left, probably because of the Florida heat. Maps are a little tricky, since this headunit is not always on an internet connection. So far, I've had success using Google Maps with a large portion downloaded locally onto the Android headunit. Still, this was a great $300 spent.

### Apps I recommend
* [Torque Pro](https://play.google.com/store/apps/details?id=org.prowl.torque)
* [Car Launcher FREE](https://play.google.com/store/apps/details?id=com.autolauncher.motorcar.free)
* [Pandora](https://play.google.com/store/apps/details?id=com.pandora.android)
* [Google Play Music](https://play.google.com/store/apps/details?id=com.google.android.music)

[Torque](https://play.google.com/store/apps/details?id=org.prowl.torque) is an awesome app for reading car diagnostics. I bought Torque Pro in 2011, and it has been used very often to read, diagnose, and clear engine codes, as well as get real time statistics from your car. You can connect to Torque using the OBDII interface in your car, and by using a Wifi or [Bluetooth OBDII adapter](https://amzn.to/2EL3NLR).

![Headunit](/images/lexus/headunit/torque.jpg)

[Car Launcher](https://play.google.com/store/apps/details?id=com.autolauncher.motorcar.free) is a simple launcher application that makes the Android interface a little more car friendly. The buttons are bigger, you can dim the screen with one click, set the few applications you actually use on your home screen. It works well for me. The layouts are also customizable. 

![Headunit](/images/lexus/headunit/launcher.jpg)

Both [Pandora](https://play.google.com/store/apps/details?id=com.pandora.android) and [Google Play Music](https://play.google.com/store/apps/details?id=com.google.android.music) can download music and play offline. Some use Spotify or other apps. You can also plug in a USB filled with music into your USB inputs, play music on your phone over Bluetooth, or Wifi tether to your headunit and let the headunit do the audio while online.

![Headunit](/images/lexus/headunit/bt.jpg)

The backup camera is great so far. I think every large car should have one, and this one works especially well with the [reverse lights](https://amzn.to/2SWAmN5) I have. This camera also has the backup lines built in to the camera feed, so you don't have to enable them in the Android settings

![Headunit](/images/lexus/headunit/backup.jpg)

Plus the dogs love it.

![Headunit](/images/lexus/headunit/dogtax.jpg)
