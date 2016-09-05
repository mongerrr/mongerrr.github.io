---
layout: post
title:  "Piston Dock"
date:   2016-09-05 22:01:00 +1000
tags:
- designs
- other
- piston dock
---

My first bike was a 2003 KTM 200 EXC (pictured below) which was an awesome little bike. After riding for a year, I decided it was time to change the piston, since the amount of hours on the bike from the previous was unknown, and I had already added 100 more hours to the bike. I didn't end up throwing the piston away, because I wanted to use it for something and because it was from my first bike. I never really knew how to use it, so it has been sitting in the shed for a couple of years. Now that I have some know how when it comes to 3D printing, I decided to clean it it up and make a 3D printed insert to turn it into a phone dock.

![My first bike](https://github.com/mongerrr/mongerrr.github.io/raw/master/resources/2016-09-05-piston-dock/ktm.jpg)

**The Design**

The insert is designed to fit snugly inside the piston, and have some support for the phone to stand upright. To allow for a charging cable, the insert has a hole and some grooves in it, and I also designed a 3D printed wrist pin with a slot in it to pass the cable through the existing hole in the piston. Just like my previous design, the files needed to modify this design, and print it to suit your own piston, [will be available on Github](LINK TO REPO).

I started off by soaking my piston in some degreaser for a couple of days to get rid of any carbon deposits. Once it was clean, I took a few measurements using some Vernier calipers to begin making the model. I am using [Openscad](http://www.openscad.org/) to make the model, so it would be relatively easy to change the model to suit measurements from any other motorcycle piston. The key measurements needed for the model are;
- Inner diameter of the piston
- Diameter of the wrist pin
- Depth of the inside of the piston
- Depth to the top of the wrist pin holding area (Does this have a proper name?)
- Gap between the wrist pin holding areas

Other numbers in the model are to adjust the position and size of the cable slots and the back support for the phone.

Here are some screenshots from OpenSCAD

![Piston Model 1](https://github.com/mongerrr/mongerrr.github.io/raw/master/resources/2016-09-05-piston-dock/model1.png)
![Wrist Pin Model 1](https://github.com/mongerrr/mongerrr.github.io/raw/master/resources/2016-09-05-piston-dock/model2.png)

**Printing the Design**

Since this print would be relatively small and inexpensive, I decided to look for some more interesting materials to print with instead of just the standard PLA plastic. One of the options I considered was 3D printed bamboo, since I was wondering what 3D printed wood would look like. In the end I chose to print in aromatic protopasta, since that was even more strange. Its a material that is supposed to look like a dark stained wood, but smell like coffee. For those of you who, like me, do not own a 3D printer, I would recommend using [3D Hubs](https://www.3dhubs.com) to get the insert printed reasonably cheaply.

Here are some pictures of the results.

![Piston 1](https://github.com/mongerrr/mongerrr.github.io/raw/master/resources/2016-09-05-piston-dock/dock1.jpg)

![Piston 2](https://github.com/mongerrr/mongerrr.github.io/raw/master/resources/2016-09-05-piston-dock/dock2.jpg)

![Piston 3](https://github.com/mongerrr/mongerrr.github.io/raw/master/resources/2016-09-05-piston-dock/dock3.jpg)

![Piston 4](https://github.com/mongerrr/mongerrr.github.io/raw/master/resources/2016-09-05-piston-dock/dock4.jpg)

![Piston 5](https://github.com/mongerrr/mongerrr.github.io/raw/master/resources/2016-09-05-piston-dock/dock5.jpg)

As mentioned above, the files needed to print or modify this design are freely available [here](LINK TO REPO). Tell me what you think in the comments below and if anyone else makes their own, I'd be more than happy to post your pictures on the blog.
