---
layout: post
title: "Physical Origins of the Pivotal Altitude"
date: 2022-03-13
tags: aviation CFI physics
---

A short discussion on the origins of the concept known as "pivotal altitude".

#### Background

If you've earned or are in the process of earning your commercial pilot certificate (single or multi) then you probably have heard of the concept known as the "pivotal altitude". Specifically, this concept is used in performing the maneuver known as "eights on pylons", which is a required maneuver on the commercial pilot check ride. It is a slightly advanced variation of the concept of "turns around a point", which is a required maneuver at the private pilot level. 

Both of these maneuvers are similar in that they are known as ground reference maneuvers, which are performed at lower altitiudes. They are useful (hence required) for demonstrating a pilot's ability to judge the effects of wind during an extended maneuver, while dividing attention, staying coordinated, and maintaining a specific attitude with respect to a particular ground reference. 

Turns around a point uses a single "pylon" or prominant ground reference point (such as a road intersection, building, or other distinguishable feature), whereas eights on pylons requires two points, spaced a certain distance apart. In the latter case, rather than flying a circle (over the ground) around the point, the pilot flies a figure eight pattern with the pylons at the centers of each of the "holes" in the figure eight. 

#### Why is the altitude important? 

In the eights on pylons maneuver, the pilot is required to maintain approximately 30 degrees of bank, at a constant power setting, while flying a consistent ground track with respect to two physical points on the ground. By using constant power, the airspeed is essentially constant, so given a required bank angle (say 30 degrees), to track our reference in a circular path we are restricted to a *specific* altitude. That altitude is called the **pivotal altitude**. Your ground speed (since this is a ground reference maneuver) is the key parameter here. Fly faster, and the pivotal altitude increases (more bank, increased rate of turn); Fly slower and the reverse is true. The desired bank angle only relates to your distance from the ground reference point. It will turn out to not affect the pivotal altitude at all (as we will see)!

#### Talk is cheap, show me the math

Let's assume we are flying in an aircraft in a level turn around a ground reference point at a height $H$ above the ground, with bank angle $\theta$, and that we are a radial distance $r$ from the reference object in question. Let's also call our airspeed $v_{t}$ (the $t$ is for "tangential" to the circular path). We then know that our centripedal acceleration (not centrifugal since we are not using a rotating reference frame) is given by

$$ a_{c} = \frac{v_{t}^2}{r} $$.

Great. Now what? 

Well, remember that in order to have a level turn, we need our weight (gravitational force) to be balanced by lift. Since we are in a bank, we know this is the vertical component of lift, whereas the horizontal component (with respect to Earth's surface) is the force causing us to turn. So, we can write an expression of Newton's Second Law in both the vertical and horizontal directions:

$$ \sum F_{x} = m a_{c} = L \sin \theta $$
$$ \sum F_{y} = 0 = L \cos \theta - mg $$

Solving for....

Stay tuned for the stunning conclusion!!!!
