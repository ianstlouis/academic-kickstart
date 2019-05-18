+++
title = "Liz-Turn Robot"
date = 2019-04-22T16:30:58-07:00
draft = false
weight = 5

# Tags and categories
# For example, use `tags = []` for no tags, or the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []
categories = []
# external_link = "https://www.ianstlouis.com/machinelearning"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = "Boundary Classification"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Smart"
  
+++
# Liz-Turn  Robot 

The Project
------
<div style="float:right;"><iframe width="560" height="315" src="https://www.youtube.com/embed/NUTO_pad4yU" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>
<div>The Liz-turn Robot is an ongoing solo project, under my mentor Thomas Libby, through the CiBER Lab at UC Berkeley. This project aims to create a bio-inspired turning robot which utilizes novel mechanical design and construction through which our robot can employ similar movement to real lizards.

A large concern in the construction of the robot is its  _complexity._ The short-term achievable goal is to develop a robot that turns on a dime and can transition into a full sprint— just as a lizard can. To spark the challenge even further, where we diverge slightly from other biomimetic robotics research is the emphasis placed on a simple construction for the body and electronics. With this light build, the strategic placement of motors, batteries and articulated assemblages allows for a more clear and calculable effect from the movement mechanisms employed in the robot.

Above is a high-speed test of one of the earlier Liz-turn versions. In this particular round of tests, my interest was in what set of software and parameters were optimal to allow the robot to traverse various types of terrain. From a hardware perspective, it was apparent that the legs would have an issue with not knowing the location of incoming terrain to adjust the swing and stance phase of their gait. As such, it was necessary that the integrated controller must adjust for sudden increases in torque and rotational velocity due to both impact with obstacles and the initiation of the stance phase.

From a test similar to this one, I identified movement and stability issues with the hind legs which were temporarily mitigated by taping them in place.</div>

THE BUILD
------
The robot body is developed using the unique construction of a single layer of plastic film wedged between a two laser-cut sheet of hybrid matboard. This combined material gives the robot rigid walls and supports, joined together by plastic flexures where the matboard has been cut away. This construction is largely influenced by the work done by the Biomimetic Millisystems Lab at UC Berkeley, under Professor Ronald S. Fearing.

The robot is electronically powered by Arduino and manipulated by PID control in a hybrid of Matlab and Arduino programs communicating through an open serial port. The gear train and its housing is designed in SolidWorks and printed using a ProJet 3D printer. The cut file for the body is designed in AutoCAD and Adobe Illustrator, and laser cut.





| ![alt text](https://firebasestorage.googleapis.com/v0/b/resumeextractor-5b9bf.appspot.com/o/Screen%20Shot%202019-05-16%20at%209.13.44%20PM.png?alt=media&token=38c6bbad-de93-481c-ba12-0273644ac244 "Logo Title Text 1")  | ![alt text](https://firebasestorage.googleapis.com/v0/b/resumeextractor-5b9bf.appspot.com/o/Screen%20Shot%202019-05-16%20at%209.14.37%20PM.png?alt=media&token=813aaf4c-2f02-40e1-8262-e5482e5c0dcc "Logo Title Text 1")  | ![alt text](https://firebasestorage.googleapis.com/v0/b/resumeextractor-5b9bf.appspot.com/o/Screen%20Shot%202019-05-16%20at%209.14.23%20PM.png?alt=media&token=f237407b-0f38-46d7-a24b-7726ed22b410 "Logo Title Text 1")  |
|--:|---|---|

LOOKING FORWARD
------
There are very few biomimetic robotics teams whose designs exceptionally combine high-speed turning with the ability to lurch into a full-speed sprint, while still maintaining under-actuation. I am hoping that at the culmination of this project to put forth a design which successfully achieves this motion under the given constraints.

This combination of behaviors poses a difficult problem, considering the glass ceiling of complexity we have posed for our robot’s design. People, insects and animals have all mastered this mobility. It seems, then, like the solution may not be so far from our grasp. With a continual effort, I hope to make more progress in determining mechanical solutions inspired by such an anatomically masterful creation, with the hopes to further drive academia, research on the subject, and our understanding of mobile transportation.
