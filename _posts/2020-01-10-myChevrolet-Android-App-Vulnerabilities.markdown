---
layout: post
title:  "myChevrolet Android App Vulnerabilities"
date:   2020-01-10 12:00:14 -0400
categories: tech
---

![App](/images/mychevy/1.jpg)

I recently sold my 2016 Corvette, and previously I had set up my car with the myChevrolet app on my Android phone. This app lets you lock and unlock your car, turn on the horn, and if your car is an automatic transmission (mine was a manual), you can remote start your car. Pretty sweet, right?

Well, it turns out you never lose access to your car, even after you sell it. I sold my Vette on October 29, 2019. It has been over 90 days since I sold my car to Sarasota Ford, and then they sold the car to another customer. However, I still have access to unlock and lock my old car, turn on the horn, and more importantly see the location of the car!

![App](/images/mychevy/8.jpg)

# Background
Chevy and OnStar partner to sell you location data in the app, which I never paid for. However there is a feature of the app that lets you track your driving habits, in order to get discounts on insurance. The app will tell you when and where your car performed hard braking, hard acceleration, when you drove at night, etc. It can send this info to Progressive or other insurance providers to prove you drive safe, and should get a discount. This was useful info when I used Turo to rent my Vette, before the [Great Turo Fiasco of 2019](https://rskelton.com/My-Turo-Claim-Horror-Story).

You can also view this data yourself, apparently even after you sell the car. So I can see where and when my old Corvette was driven, where the new buyer lives, where the new buyer works, what locations the new buyer visits, all of which are shown in a censored screenshot below. The uncensored version shows me the full address. I can unlock the car. If it was an automatic transmission, I could also start the car.

![App](/images/mychevy/9.jpg)

# Replication Steps
Here are the steps to replicate this in the myChevrolet app.

**1. Open the app**

[App](/images/mychevy/2.jpg)

**2. Click Smart Driver**

![App](/images/mychevy/3.jpg)

**3. Click More Trip Detail Views.**
![App](/images/mychevy/4.jpg)
![App](/images/mychevy/6.jpg)
![App](/images/mychevy/7.jpg)

**4. Click timeline to see exact address**
![App](/images/mychevy/9.jpg)

You can also view other trips from the same day, or select other days to see location data and driving habits
![App](/images/mychevy/5.jpg)

This is a major security flaw. Chevrolet and GM need a process to verify that owners of cars linked to app still own their car regularly. I have reported this security issue to GM on HackerOne.
