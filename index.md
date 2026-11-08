# Summer Garvais

**Email:** kgarvais@ucsd.edu

**Section:** DSC 180A, Section 14
**Mentors:** Nathan Hui, Siena Okuno

---

## Quarter 2 Project Brainstorm

**What is the most interesting topic covered in your domain this quarter?**

I think the most interesting topic we covered in our domain this quarter was the potential sources of error. Investigating
how different fluctuations in camera calibrations, drone hover-height changes, and white-balance could all disrupt our modeling was very
interesting. It is rare when working with tabular data, at least in my experience, to have to worry about things like this so it felt like good
real world experience to consider all of these error sources.

**Describe a potential investigation you would like to pursue for your Quarter 2 Project.**

I'd like to investigate how 3D vs. 2D segmentation differed in its effectiveness around steep elevation changes. Currently, in our orthomosaic, steep elevation
changes are somewhat neutralized but by stitching images together, but it may be interesting to see if that still impacts the effectiveness of our model.

**What is a potential change you'd make to the approach taken in your current Quarter 1 Project?**

I'd like to do more planning upfront at the start of the quarter to ensure we are not spending lots of time on tasks that don't impact our final product. I spent some time
this quarter on some algorithms that ended up not being relevant to our final envisioned goal, which was a bit frustrating. So, I'd like our approach to change towards being more
methodical and explicit about what is necessary at the start.

**What other techniques would you be interested in using in your project?**

I'd like to compare our model to an object detection model in the training process. This would be implemented when our model makes a series of segmentations
which total up to a number of objects detected. At a certain threshold, if the model does not pick the accurate number of objects it is asked to reconsider and favor
an object number closer to the object detectors output. This would require our object detection model to be tuned to distinguish plant species however, which we may not have
time to implement.
