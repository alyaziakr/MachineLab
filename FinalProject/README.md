# Final Project 

# Overview:

This project at the end is a mechanism of a drawing automata. It a figure that will gesture that it is painting with a 3 frame drawing animation looping and at every mark of the hour (15, 30, 00) it will change the painting animation in the back in a zoetrope to show progress in the art work.

Fusion File: https://a360.co/3flWlIV

Final result from the front:

![](images/frontFinal.png)

Back:

![](images/backFinal.png)


# April 1st: Coming up with ideas
Theme Ideas:
- Old school animation/cartoons
- Cats: Like the famous cat clock but more with more cats and automatas
- Salvador Dali: Salvador dali style with a wacky clock + human figure automatas making unnatural movements
- The Pandemic: Credits to Carlos

Initial Concept: I decided on exploring the idea of COVID 19 and the pandemic and the first thing that stuck was the sentence that is said to everybody over and over again "wash your hands"

It is simple and not very complex right now but my idea is to have a a giant figure of an adrogynous human where their head and arms would move in an arc as if they were sneezing every fifteen minutes or so. As the arc is moving using a servo motor, while a stepper motor powers a cam that simulates water moving (Insperation from: https://www.youtube.com/watch?v=Djn1YRHZ8lQ). The clock itself would be a mechanical one on the face of the sink where the water is at.

Concept Art Work:

![](images/Concept.jpg)

Sneeze Motion:

![](images/FigureMotion.jpg)

Water Motion:

![](images/WaterMotion.jpg)

# April 6th

Main Idea: Art

Description: A figure moving to create a piece of art: the first 15 minutes mark the figure is in the process of starting the drawing. At the 30 minute mark the art work changes to a mid-way sketch and at the hour mark the art work is finished.

Initial Sketches:

Figure drawing movement mechanic:

![](images/initialMovement.png)

Art work zoetrope mechanic:

![](images/artworkMechanic.png)

# April 8th
  
  * Dimensions: *Still Trying to figure it out*
  * Materials: Acrylic or wood 
  * Fusion 360 implementation plan: 
    I will start of attempting to create the overall mechanic like a simple skeleton with just the movement linkage for the figure and the rotation of the zoetrope. After that I will add all the different parts like the two or three motors I would need from McMaster Carr and I'll try to create the body to the skeleton parts and put them together if that makes sense.
  * Machines used to fabricate: I'm not sure
  * How pieces are going to be attached: The linkages and joints etc. on the figure will be put together using screws and bolts, the other parts like the cam and the zoetrope would be glued together to create the circular shape on the flat surface. But I need to figure out how ill attatch it to the stepper motor underneath it that makes it rotate. 
  
  Images:
  
  ![](images/motionTrial.png)
  ![](images/motionTrial2.png)
  ![](images/motionTrialFull.png)

# April 13th

Created more detailed sketches and added estimated dimensions. I decided that I will attempt to replicate main bodies on fusion to make sure of the dimensions then I'll go back to my plan of creating the main skeleton of the machine.

Images:

Overall Image:
![](images/overallMachine.png)

Extra Details on the Zoetrope: One part I'm not sure of how to connect is the stepper motor. (Solution I ended up finding was getting a coupler)
![](images/zoetropeDetails.png)

# April 15 and 20

Worked on fusion model:

Created two different models one to work our linkages and one to build the final one with the dimensions

Created dimensions to figure out ratios and dimensions for the final model (that I now realize are too big):
![](images/dimensionsSS.png)

Dimension model work in progress:

![](images/modelWIP1.png)
![](images/modelWIP2.png)

The linkages model:

I couldn't figure out how to animate the linkage without moving it myself.

![](images/linkageAttempt1.png)

After help I used grounding and allowing all contact to be able to move the rest

# April 22

Redesigned parts of the mechanic because it was unbalanced before:

Sketch:
![](images/redesignSketch.png)

I remade the fusion project with better dimensions now because they previous one was too large
Fusion Progress:

![](images/newDimensions.png)
![](images/newFusion1.png)

# April 27

I worked more on the fusion model.

Issues and concerns: 

- Size of stepper motor hub: will it connect properly to the zoetrope and is the platform to prop it up and contain the motor properly?
- Are the slot sizes where the linkages/sticks are in big enough to work or would it break?
- Maybe the cam can be 3D printed because it's rather big/thick? 
- I’m also unsure of the hole sizes for the zoetrope

Images:

![](images/updateapril27.png)
![](images/topangle.png)
![](images/slotcloseup.png)

# April 29

Resolved some issues from last time:

I will be able to get the cam 3D printed as indeed it cannot be laser cut that thick.
The sizes of the linkages worked fine.

I added support for the torso shaft (1) as well as a clamping hub for the zoetrope (2).

1.

![](images/updateapril29_1.png)

2.

![](images/updateapril29_2.png)

# May 3

Close to final touches:

Combined the shaft and the cam

![](images/shaftcombination.png)

Added a hub to connect the stepper motor to the shaft

![](images/motorhub.png)

# May 4

Updated the stepper motor and hub/coupler to something that would work because the first one didnt have the notch that tightness the hole the shaft and motor would go into. 

![](images/coupler1.png)
![](images/coupler2.png)

# May 6

One issue that was brought up to me was that when I was gonna add the motor it would have no support so for final touches I've added support for both motors:

![](images/zoetropeMotor.png)
![](images/camMotor.png)

With the zoetrope motor it didn't have enough support so I ended up going back and adding two walls on the side:

![](images/support1.png)
![](images/support2.png)

# May 11th

At this point I've just been editing small aspects of the model like the support for the motors:
![](images/support3.png)
![](images/support4.png)

# Final Art for the zoetrope:

<img src="images/Painting_1.png" width="200"> <img src="images/Painting_2.png" width="200"> <img src="images/Painting_3.png" width="200">
</br>
<img src="images/Painting_4.png" width="200"> <img src="images/Painting_5.png" width="200"> <img src="images/Painting_6.png" width="200">
</br>
<img src="images/Painting_7.png" width="200"> <img src="images/Painting_8.png" width="200"> <img src="images/Painting_9.png" width="200">


# Discussion

Fabrication:
  I would like everything to be laser cut with the exception of the cam, shafts, couplers and zoetrope.
  
Other components needed:
  2 stepper motors, Hot glue to stick surfaces together, 8 3m screws to attatch stepper motor.
  
Remaining concerns:
  I'm not sure if I have any remaining problems, I am however concerened to see how it would end up being built I tried looking over everything a couple of times but I'm worried I might've missed something however that will only be resolved by getting a test build and trying to put everything together.
  
Difficulties and Learning Outcomes:
  At the beggining I really could not wrap my head around the movementand how it would physically be possible, I've changed the mechanic sketch a few times and my plan especially earlier on had huge issues like balance, they were designs that were some what close to the final plan but just not mechanisms that would have worked, there was also issues of working against the mechanical power. All the issues with the plan were resolved by thinking and visualizing the mechanic more while sketching more and more sketches. Taking breaks and looking back on the mechanic also helped in spotting issues I overlooked. Moving on I've mentioned these above but I also struggled with how to attatch the motors before being given the idea of couplers.
  
  By the end I feel like I've, of course, actually grasped how these mechanisms work because of the issues I mentioned throughout this documentation that I managed to overcome and resolve. Especially when thinking about new ideas I think about how for example linkages and cams would work well with said idea.
