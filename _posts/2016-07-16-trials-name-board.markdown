---
layout: post
title:  "Trials Name Board"
date:   2016-07-16 22:01:26 +1000
tags:
- designs
- trials
- name_board
---
For my first design, I have made a front name board for trials bikes. When I was looking for a name board for my own trials bike for competitions, I was wondering why anyone didn't have a fancier looking name board. I was sure that I was not the only person wondering this, so I decided to try to make them for whoever is interested.

The design would also look good on any pit bike too. To view a live preview and download the 3D model and its source code, [visit the project page on GitHub](https://github.com/mongerrr/Openmoto1/)

Here is photo of the name board on my bike

![Mockup](https://github.com/mongerrr/mongerrr.github.io/raw/master/resources/2016-07-16-trials-name-board/mockup.jpg)

**Design Features**
- Easy mounting to the forks using cable ties
- Shape of the board allows for the use of preprinted 2016 Honda CRF50 graphics
- The back of the board includes a loop for a pen, and a small bar to clip a scorecard to, for club trials

**Design Process**

As this was my first design, I decided learn about some different design techniques. I started with a plastic mockup which had the general shape that I wanted, but did not have any of the cable tie guides, pen loop and bar on the back. The next step form here was to get the mockup 3D scanned, to get an early model. For this, I got the help of James Tawadros at the UTS 3D lab, who was great to deal with and I would recommend him for anyone who wants to do something similar.

Once I had this model, I began to manipulate the shape slightly, and add the mounting points, the pen loop and the scorecard bar. The software I used for this was [Openscad](http://www.openscad.org/), which allows for modelling the the pieces parametrically. Once the model was finished, I exported the design as a .stl file and then used [Meshlab](http://meshlab.sourceforge.net/) to remove any internal edges where components off the model intersected. The final .stl produced with Meshlab is ready for 3D printing.

**Design Issues**

When designing this part, I looked to the community for ideas and feedback. This raised some good ideas, and also some things for me to look into. The idea of having a pen loop and scorecard bar, was one of the suggestion made by the [trials community](http://www.trials.com.au), which I thought was a great idea.

The main issue that was raised by the community was concerns over the use of such a part with Motorcycling Australia's General Competition Rules. I was quite sure that the part would be sufficient to meet the GCR requirements, and to remove any doubt, I contacted Motorcycling Australia to seek guidance on the the issue. Their response indicated that the name board was fine to use, as long as the graphics had a clear background and 25mm tall lettering. They also gave a suggestion that any flashings on the graphics should be in a neutral colour, to avoid any confusion with other classes. For example, my original clubman graphics had a white background for clubman class with blue and yellow flashings on the graphics to match my bike's Sherco colours. The advice I got from MA was that blue and yellow are colours used for B grade and C grade, so to reduce confusion, I should use black flashings or something similar. I ended up using carbon flashings on my graphics and that was fine for competition rules.

**Producing the Design**

I will be posting another article with some suggestions for 3D printing the part based on different copies of the part that I have had printed.

**Pictures**

The overall 3D design

![3D model](https://github.com/mongerrr/mongerrr.github.io/raw/master/resources/2016-07-16-trials-name-board/3d_model.png)

A photo from a Wollongong MCC club trial. Notice the change in my graphics to carbon flashings.

![Club Trial](https://github.com/mongerrr/mongerrr.github.io/raw/master/resources/2016-07-16-trials-name-board/club.jpg)

A 3d print of the part showing the front and back. I will go into detail on this in a future post. This one was printed in 2 parts and has a visible seam.

![ABS Front](https://github.com/mongerrr/mongerrr.github.io/raw/master/resources/2016-07-16-trials-name-board/abs_front.jpg)

![ABS Back](https://github.com/mongerrr/mongerrr.github.io/raw/master/resources/2016-07-16-trials-name-board/abs_back.jpg)

If you appreciate my designs and would like to fund my future designs, I would greatly appreciate if you [made a donation](https://paypal.me/mongerrr).

Tell me what you think in the comments below
