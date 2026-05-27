# Lab8-Starter

## [GitHub Page Live](https://amormio25.github.io/Lab8_Starter/)
## Lab partners: Amormio (me)

## Question: How are graceful degradation and service workers related?

From the assignment writeup, it was mentioned:

> _graceful degradation is when we start with max technology and hopefully address lower levels with grace_

This is related to service workers in the sense that when building applications, we build with the expectations that all features will be possible when online. Then, we address lower level details like when users might be offline, we'll need to be able to support them as well. So essentially we start with a full experience and degrade gracefully, where offline mode might have less performance and benefits, but users can still use the application offline through service workers.
