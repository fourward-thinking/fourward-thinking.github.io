# Fourward Thinking

## Table of Contents
* [Overview](#overview)
* [Approach](#approach)
* [Mockup Page Ideas](#mockup-page-ideas)
* [Use Case Ideas](#use-case-ideas)
* [Beyond the Basics](#beyond-the-basics)
* [Team](#team)

## Overview

*The Problem*: ICS students often spend more time than they need on their homework and don’t learn the material as effectively as they could, because they study alone and do not leverage the power of face-to-face study groups with peer mentors.

*The Solution*: Study Buddy is an application for UHM ICS students to self-organize face-to-face study groups around a course and/or specific homework or project topic.

## Approach

To use Study Buddy, a student must login and set up their profile. The profile enables each student to list courses they have taken and for which they are willing to attempt to provide help (sensei), and courses they are currently taking and for which they might need help (grasshopper). Thus, all students are sensei in some courses and grasshoppers in other courses. Each student must also provide a head shot so that they can be visually identified.

Another section of the site lists all of the ICS courses. Within each course, it is possible to see the grasshoppers and the senseis. A grasshopper can propose a study session around a topic currently being covered in their course (for example, “Write my essay on configuration management”, and a time to meet within ICSpace (i.e. 8:30-9:30pm tonight)). This proposal generates a notification to all of the grasshoppers and senseis, and they can respond by saying they intend to come at some point during the time period.

There is an online calendar that shows all of the study sessions and who is attending.

There are two styles of use for Study Buddy:

1. You want to plan a group study session for later in the day or some subsequent day. In that case, you schedule the time period for sometime in the future.

2. You are having a problem right now. In that case, you can go into Study Buddy and schedule the session for “Right Now!”. This indicates you are right now in ICSpace and need help. All the other sensei and grasshoppers for that course will be notified, and hopefully a group will spontaneously form in a few minutes.

There must be admins who monitor the site and who users can contact if they suspect inappropriate behavior.

Important design goals for Study Buddy are:

* To encourage use of ICSpace among ICS students
* To minimize risk of inappropriate encounters by requiring all meetings to occur in ICSpace.
* To encourage face-to-face interaction among ICS students.

## Mockup Page Ideas
Some mockup pages to include:

* Landing Page
* User Home Page
* Admin Home Page
* User Profile Page
* Calendar Page
* Create Study Session Page
* Study Session Page
* Game Mechanic Page(s) (i.e. leaderboard, badges, etc.)

## Use Case Ideas
Whether or not the following bullet points list all pages or not, the completed use case should show an end-to-end scenario of using the system.

* New user goes to landing page, logs in, gets home page, sets up profile. (How do they learn how system works?)
* Admin goes to landing page, logs in, gets home page, edits site.
* User goes to landing page, logs in, requests study sesh.
* User is notified of study sesh, responds. (Can they respond via text message?)
* User checks their status with respect to game mechanics.

## Beyond the Basics
After implementing the basic functionality, here are ideas for more advanced features:

* Text message interface. See notifications, and reply to confirm attendance all through text message.
* Slack integration to facilitate notification and organization of meetings.
* A Slack Bot to suggest and help implement Study Buddy meetings.
* A rating system for meetings and sensei participation.

## Team

Fourward Thinking is designed, implemented, and maintained by Kaena Sylva, Aldwin Santos, Jayden Capistrano, and Joshua Scott.

Team Contract can be found [here](https://docs.google.com/document/d/1eQ3XoFDD-6ArQlqjSbglP0_gA7TwmLjyn-lzj64xbVA/edit?usp=sharing).
