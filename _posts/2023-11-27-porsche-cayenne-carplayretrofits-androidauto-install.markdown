---
layout: post
title:  "Porsche Cayenne - CarPlayRetrofits Android Auto/Carplay Install"
date:   2023-11-28 8:05:14 -0400
categories: cars
---

![AA](/images/aa/10.jpeg)
![AA](/images/aa/7.jpg)

I bought the [carplayretrofits.com Android Auto/Carplay head unit upgrade](https://carplayretrofits.com/products/carplay-andrioid-auto-plug-and-play-kit-for-porsche-pcm-3-1) for $480, this is how the install/support went. 

After the product arrived, I read the install instructions. Apparently this unit sold by carplayretrofits.com is actually a [Isudar board](https://amzn.to/3GnR6H6), which are known for being slow and buggy, but the seller claims they are modified with a different chipset, ram, ram controller, audio controller and custom firmware. If I had known this was an Isudar board with a 200% markup, I would not have bought it. These can be bought cheaply from Amazon and Ali Express. 

Removal of the stock headunit was pretty straightforward, however I don't recommend using the [sellers instructions](https://cdn.shopify.com/s/files/1/0721/0847/4648/files/CPRF.pdf?v=1690511085). The removal head unit removeal instructions linked are for a Macan, which is very different than a Cayenne for the PCM removal. Basically, you need to remove the [2 air vents](https://www.youtube.com/watch?v=2v_dnikEjzM), then 4x TX27 screws, then the radio will pull right out. 

![AA](/images/aa/3.jpg)

Once removed, take your PCM unit inside, then mostly follow the instructions. The separation of the PCM unit requires a [Torx 8 screwdriver or bit](https://amzn.to/417KrdW), which I did not own. Mine had a Sirius XM board on it, which I removed completely. The instructions tell you to remove 3 screws and then install standoffs, and include different heights. If you have no other boards, use the small standoffs. I used the smaller ones once I removed the XM board. If you have other boards, use the taller standoffs. The standoffs install with a 5mm socket. 

![AA](/images/aa/1.jpg)
![AA](/images/aa/2.jpg)

Before seating and installing the new card, make sure you plug in the ribbon cables from the new package. This part is glossed over in the install instructions. Other than that, install the cables as indicated. 

![AA](/images/aa/4.jpg)

Once you are ready to go back to the car, this is a instruction that is completely missed by the seller - you need to remove the fiber audio cable from the stock connector (2 orange cables), and plug that into the same spot on the NEW power cable attached to the back of your PCM. This connection makes sound happen, so you'll want it. This step is shown in the Isudar install video, [here.](https://youtu.be/I-OjeOMdo-E?si=6aerbiFAI2mT4KT9&t=337) If you skip this step, you won't have any audio.

![AA](/images/aa/6.jpg)

Once installed, you need to select the AUX input on your stereo. This is something than can only be enabled by a dealer or a person with the PIWIS Porsche scan tool, which is also not something indicated by the seller. The local dealer quoted $300 to enable the AUX input. I ended up borrowing an [Autel Maxisys MS906BT](https://amzn.to/3QTdxsI) from a friend, which let me enable the aux input and a few other fun settings, but it took a while to find.

![AA](/images/aa/8.jpeg)
![AA](/images/aa/5.jpg)

So I was able to get Android Auto and CarPlay to launch, however I could not get sound except through the stock radio or CD player until I used the Autel code writer function. I found a workaround before I got aux enabled, which was to use the Aux Bluetooth input. This meant my phone was connecting to PCM as a BT device, and to Android Auto as a BT device. So 2 BT connections, and it DRAINED my phones battery. Also the way to launch the custom interface is pretty slow - you have to hold the INFO button for 3 seconds, and it's just generally slow. 

Eventually, when I got the Aux input enabled, it was a bit quicker and less of a drain on my phones battery and resources. It also launches pretty quick and goes directly to Android Auto on start. So overall, I'd recommend a CarPlay/Android Auto upgrade, but would not buy from [carplayretrofits.com](https://carplayretrofits.com/products/carplay-andrioid-auto-plug-and-play-kit-for-porsche-pcm-3-1). I would probably consider the [Mr 12 Volt option](https://www.mr12volt.com/collections/porsche/products/p2000-pcm31mm), which doesn't use the Aux setup at all to do audio. 

![AA](/images/aa/9.jpeg)
