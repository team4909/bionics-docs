---
title: Differential Swerve
---

## What is Differential Swerve?

In a traditional coaxial swerve module module rotation (changing the heading of the wheel) and module transation (wheel rotation) are controlled by independent motors.

Differentail swerve uses the opposing rotation of the two drive motors to create translation and the rotation in the same direction to create rotation.

This video has a nice demo:
{{<youtube Y1XtXkTUXsI >}}

## Software
The software can easily become complex and diffucult to understand.

We found that using the simplyfing assumption that we should do our math in units of RPM causes a relativley simple set of formulas to fall out.

