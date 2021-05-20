---
title: Drivetrains & Wheels
description: Common wheel and chassis configurations
---

The best drive train:
- is more **important** than anything else on the robot
- meets your **strategy** goals
- can be build with your team **resources**
- rarely needs **maintenance**
- can be **fixed** within 4 minutes
- is more **important** than anything else on the robot

Basics
- Know your resources (manufacturing, cost, design, etc)
- Use strategy to inform choices:
    + Speed, power, shifting, mobility
- Use most powerful motors on drive train
- When testing the drive train, **weigh it down**. (Don't drive 1/2 the robot)
- Stress test early, implement fixes (not duck-tape and super-glue)
- Give software **TIME to work**
- Give drives **TIME to drive**
- Plan for sensor locations early




<!-- ## Types of Wheels

### Traction Wheels

### Omni Wheels

### Mecanum Wheels
 -->


## Types of Drivetrains
Drivetrains combine wheels and chassis elements to provide a movable foundation for robots.

### Tank Drive
Tank Drives are very common in the FRC community. 

- Left and right sides are driven independently
- Often the center wheels are dropped 1/16" - 3/16" to make turning easier

Pros:
- Simple & inexpensive
- Software well supported
- Easy to drive
- Potential for high pushing force

Cons:
- Less agile than other drivetrains
    + Can be diffucult to turn.

#### West Coast / Live Axle
A West Coast drivetrain is a type of tank drive where the wheel axles are only supported on one side.
- cantilevered wheels
- allows for wider robots

### Omni-directional drivetrains

#### Swerve / Crab
- Wheel modules rotate on vertical axis to control direction
- typically four traction wheels, one in each robot corner

Pros:
- Potential for high speed and/or pushing force
- Very Agile (can move in all directions)
- Simple wheels

Cons:
- Requires custom modules and extra motors (2 per module)
- Very complex, expensive to build
- Challenging to program
- Heavy when compared to tank drive

#### Slide / H-Drive
- Similar layout to tank dive
- Uses only omni-wheels

Pros:
- Fairly easy to design & build (Note: Critical for wheels must be on the same plane. Easier with CNC machining)
- Very Agile (can move in all directions)

Cons:
- Very little potential pushing force
- Extra wheel(s)/motor(s)/gearbox(es) required

#### Mecanum
- Similar layout to tank drive
- Each wheel must be driven independently
- Must use 4 mecanum wheels

Pros:
- Fairly easy to design & build (Note: Critical for wheels must be on the same plane. Easier with CNC machining)
- Very Agile (can move in all directions)

Cons:
- Wheels are expensive
- Extra motor(s)/gearbox(es) required
- Minimal braking ability
- Difficulty on inclines
- Very little potential pushing force
- Challenging to program & drive

#### Holonomic Drive
- 4 omni wheels at 45° or 3 at 120°
- Each wheel must be driven independently

Pros:
- Agile
- Immediate turning
- Easy to design and build

Cons:
- No brakes
- Difficulty on inclines
- Very little potential pushing force
- Challenging to program and drive
- Extra motor(s)/gearbox(es) required

## Robot Speed
- Too Fast
    + won't have enough torque to move
    + Leading to hard to control
- Too Slow
    + too much torque causing wheels to slip
    + too slow to be effective

Rule of thumb:
- Single speed gearbox, 8-12 ft/s
- Two speed gearbox, 18 ft/s to 4 ft/s

### Wheel Size
Wheel Size can have a large impact on your design.

- Smaller Wheels
    + Less gear reduction needed
    + less weight
    + Lower center of gravity (less prone to tipping)
- Larger Wheels
    + Lower RPM for the same linear velocity (less tread wear)
    + Larger sprocket to wheel diameter ratio (less tension on chain/belts)

### Number of wheels


{{<columns markdown="true">}}
##### 2 Wheel Drive
Pros:
- low resistance turns

Cons:
- challenging to drive
- easily defended
- lower pushing force (less friction)
- may not turn at robot center
<--->
##### 4 Wheel Drive
Pros:
- long wheel base

Cons:
- One set of wheels needs to be omni
- challenging to drive
- easily defended
- lower pushing force (less friction)
- may not turn at robot center
<--->
##### 6 Wheel Drive
Pros:
- great turning with high traction wheels with dropped center
- full pushing force potential

Cons:
- extra wheels add weight
<--->
##### 8 Wheel Drive
Pros:
- great turning with high traction wheels with dropped center
- full pushing force potential

Cons:
- extra wheels add weight
- more power transmission complexity
{{</columns>}}
