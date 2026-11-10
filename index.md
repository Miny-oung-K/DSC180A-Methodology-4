---
layout: default
title: Methodology Assignment 4
---

# Methodology Assignment 4

**Name:** Minyoung Kim  
**UCSD email:** mik061@ucsd.edu  
**Section:** D19  
**Mentor:** Victor Mince

**What is the most interesting topic covered in your domain this quarter?**

The most interesting topic to me is using machine learning to connect body gestures and sound through an interface that users can train themselves. Our project explores mapping sounds to body gestures and then allowing users to produce sounds through those gestures. I find the personalization especially interesting because people could choose movements that feel natural to them. This could support creative expression for dancers and artists, and it could also be explored as a communication tool for people with speech impairments.

**Describe a potential investigation you would like to pursue for your Quarter 2 Project.**

For Quarter 2, I would like to investigate how much training data a user needs to create a reliable personalized gesture-to-sound mapping. Users could record a small set of gestures and associate them with sounds or short recorded phrases. I would compare performance with different numbers of training examples and test the mappings in a later session to see how well they handle changes in movement. I would evaluate gesture recognition accuracy, response time, and how easy users find the interface to learn. As a possible extension, I would explore a small phrase-selection prototype for communication, starting with a limited set of phrases rather than attempting full speech generation.

**What is a potential change you'd make to the approach taken in your current Quarter 1 Project?**

One change I would make is to add an explicit calibration and correction step to the interface. Instead of having users record examples and immediately rely on the resulting mapping, the interface could let them test each gesture, see which sound the model selects, and add examples when it makes a mistake. I would also include a neutral or "no gesture" state to reduce accidental sound triggers. I would compare the mapping before and after this feedback step using new recordings, measuring both correct selections and unintended activations.

**What other techniques would you be interested in using in your project?**

I would be interested in using pose estimation to represent body movement as joint positions, along with temporal models that recognize gestures over several frames. This could help distinguish gestures that look similar in a single frame but move differently over time. I would also like to explore transfer learning to reduce the number of examples each user needs to provide and active learning to ask users for examples the model is uncertain about. Finally, usability testing would help us understand whether the gestures are comfortable and whether the sounds respond quickly enough for communication or performance.
