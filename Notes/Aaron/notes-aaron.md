---
title: "Aaron's Research Review"
output: pdf_document
bibliography: aaron.bib
---

# Table of Contents

[TOC]

\newpage


# Visual Impairments and Mobile Touchscreen Interaction: State-Of-The-Art, Causes of Visual Impairment, and Design Guidelines

## Citation

[@doi:10.1080/10447318.2017.1279827]

## Background

This was an in depth look into what potential problems and solutions can arise from mobile touch screen interactions when used by people with visual impairments.
Along with the latter statement this paper also had a very in depth looks into causes of visual impairment. This portion of the paper does not pertain to us.

## Study

The portion of the paper we are making use of includes the summary of the design guidlines put forth by other (referenced) papers. No testing or surveys were done in this portion of the paper, it is simply a summation of previous guidelines.

## Results

The guideline summation is as stated:

> - Allow configurable visual settings. (studies show people with vis impairment will spend alot of time configuring settings)
 
> - Design for commercially-available wearable devices.
 
> - Design mobile device interactions to reduce encumbrance when using other accessibility devices
 
> - Detect and deal appropriately with unintended touch (possibly a toggle for touch)
 
> - Design usable touch gestures for people with visual impairments (favor landmarks of the device)
 
> - Deliver appropriate feedback for all visual abilities.
 
> - Deliver appropriate feedback during and after gesture articulation


## Questions

1. What does appropriate feedback look like in our case?


## Lessons Learned

\newpage


# Facilitating Route Learning Using Interactive Audio-Tactile Maps for Blind and Visually Impaired People
## Citation

[@10.1145/2468356.2468364]

## Introduction
This paper covers the information needed to develop a route for the visually impaired. This paper also aims to answer which are the most important landmarks and sounds to include in the route design.


## Study
The authors of the paper conducted a survey of 15 different mobility and orientation instructors. From the paper:
> An online survey study
The aim of the online survey study was to build on the
information obtained from the mobility instructor by
surveying others in the profession. The questionnaire
concentrated on detailed information of the type of
auditory features and landmarks they feel important in
guiding people with visual disabilities in route learning.


## Conclusion

From their results stated in the paper:

- All instructors serveyed claimed the use of landmarks and audio queues was optimal for developing a route.
- All instructors besides 1 developed their own maps.
- All instructors claimed that the use of landmarks that are immovable and permanent such as buildings and intersections where optimal.
- Ambient sounds such as running water, sounds from ground textures, and vehicle sounds are all important.
- Sound from ground textures ranked #1 most important sound for route development.
- Intersections and buildings ranked as the most important landmarks for route development.

## Lessons Learned

-Ambient sound should not be overlooked.
-Intersections are very important as well as traffic.
-Landmarks should be immovable and permanent.


## Questions

\newpage


# Investigating Accessibility on Web-based Maps:
## Citation

[@10.1145/2815169.2815171]

## Introduction
This paper presents results of an accessibility evaluation carried out with web-based map applications.
Three points of view were considered: experts on accessibility, evaluation tools, and final users (partially or totally blind users)


## Study
A number of problems was identified and none of the evaluated applications entirely meet the analyzed criteria.

__Below are the goals and questions for the following results__
>Goal1: Analyze web-based mapping systems, in terms of accessibility, from the point of view of experts in web accessibility.
>Question1: Which Success Criteria from WCAG 2.0 - Level A - are implemented by the web systems evaluated? 
>Question2: What level of compliance in WCAG 2.0 each web system can be classified?
>Metric1: Sum of Success Criteria that are not implemented by the systems, whereas the option given by experts in the questionnaire is “It does not meet”. This metric serves the > Question1 and shall be applied in each one of the analyzed systems.

The experts analyzed the five selected websites, searching for some infringement of the Success Criteria. Item by item, the experts had to answer if the Success Criteria was fulfilled on that specific website.

Guidelines Graded By Expert COMS: 
https://www.w3.org/TR/WCAG20/



## Conclusion
I will only be focusing on how google rated among the criteria.


### Expert COMS Eval:
Expert COMS evaluation of google:
>7 successes for google, 12 not met.
>These 12 not met include:
>1.1.1 - Text Alternatives: Provide text alternatives for any non-text content so that it can be changed into other forms people need, such as large print, braille, speech, symbols or simpler language.
>1.2.1 - Time-based Media: Provide alternatives for time-based media.
>1.2.2 - 
>1.3.1 - Adaptable: Create content that can be presented in different ways (for example simpler layout) without losing information or structure.
>1.3.2 - 
>1.3.3 - 
>1.4.1 - Distinguishable: Make it easier for users to see and hear content including separating foreground from background.
>2.1.1 - Keyboard Accessible: Make all functionality available from a keyboard.
>2.1.2 - 
>2.4.1 - Navigable: Provide ways to help users navigate, find content, and determine where they are.
>2.4.2 - 
>2.4.3 - 
>2.4.4 - 
>3.1.1 - Readable: Make text content readable and understandable.
>3.2.2 - Predictable: Make Web pages appear and operate in predictable ways.
>3.3.1 - Input Assistance: Help users avoid and correct mistakes.
>3.3.2 - 
>4.1.1 - Compatible: Maximize compatibility with current and future user agents, including assistive technologies.

### Tool Based Eval:
The tool-based evaluation aimed to identify success criteria that were not properly implemented by the analyzed websites.
>Google ranked lowest in all 5 tools.
>11 unmet by google based off of tool checking, the other 4 websites had a better score (6,4,7,8).

### End User Eval:

Functionalities graded the highest avg between 8 users:
>All 100% grade
>Activity 1: lookup for an address, using the search field;
>Activity 5: find the function buttons to "get directions" and "my places";
>Activity 6: use function "get directions" with start and end addresses; 
>Activity 7: use function “avoiding tolls” on a chosen path in a given address; 
>Activity 8: change the path to “walking”;

Functionalities graded the lowest on average:
>Activity 9: use the zoom feature on the map. 0%
>Activity 4: access photos of a given address, and read their descriptions; 0%
>Activity 3: switch between "Map" and "Satellite" views, using the website tools; 50%
>Activity 2: find out the name of a neighborhood with a supplied address;87.%

In Activities 4 and 9, not a single visually impaired user completed the tasks, indicating possible severe accessibility problems. 


## Lessons Learned

1. Google Maps has many accessibility needs to be met.
2. Expert COMS opinions do correlate to how the end user performs.
3. Tool based eval is not the best way but provides a decent evaluation
for more broad criteria.


## Questions

\newpage


# CapMaps - Capacitive Sensing 3D Printed Audio-Tactile Maps:
## Citation

[@10.1007/978-3-319-41267-2_20]

## Introduction
This paper presents us with ways to link audio with tactile maps in order to reduce 
the tactile complexity of the map. the major challenge of audio-tactile maps is 
linking the audio to the map in a presentable way. The way this is achieved in
this paper is by using conductive filement inside the 3D printed tactile map.
This conductive filement will transmit the touch from the map and produce audio
output from a mobile device. To demonstrate the effectiveness of this approach
they performed a study.


## Study
In order to actually produce the audio-tactile maps a duel headed 3D printer
was used, one head printed in standard PLA while the other head printed a
special conductive filement called Trijexx Conductive. On one side of the map there is a conductive flat portion. A touch of the user on the one side of the 3D
printed capacitive code is forked into multiple locations on the display’s surface, inducing the detection of multiple concurrent touches. Software analyzes concurrent touches and classifies them into normal touches and specific codes. Thus, the 3D printed tactile map is able to transmit information to the surface by a single touch. This also provides I nice landmark for users to determine the orientation of the map.

Next they performed a feasibility study that essentially tested whether or not the flat conductive material on the side worked well enough to transmit the scale of the map, GPS coordinates, distances, and orientation of the map to the real world. During the tests the users where able to obtain all of this information about the map features via double tap(name of feature), triple tap (type of feature), and a long tap(names of surrounding features).



## Conclusion
In conclusion this paper focused mostly on attaching audio descriptions to tactile 3D printed maps and discovered how interactive content should be structured to support navigation and orientation.


## Lessons Learned

1. 3D printed audio-tactile maps are feasible but have limited capabilities.
2. 3D printing a map that combines PLA and conductive material is time consuming yet effective for areas that aren't subject to change.



## Questions
Is there a way to automate designing the 3D maps with CAD (designing the maps seemed like the most time consuming part)?

\newpage


# Accessible smartphones for blind users: A case study for a wayfinding system:
## Citation

[@RODRIGUEZSANCHEZ20147210]

## Introduction
This paper starts of by introducing the problems with current smartphone accessibility and provides solid background on each issue: screen readers, each app having different layout, current accessible maps not being scale-able, storing audio locally vs web based that would require a connection, and provides and interesting statistic that 82% of blind people are aged 50
or over (Zajicek & Brewster, 2004) therefore smartphones are harder to make accessible since most people that age aren't attuned to using them in the first place. They also state that the age of going blind is a factor that should be considered. 


## Study
Before setting up the end-user testing they begin by developing an accessible navigation app that has a menu(current location, help, destination address, and information) based off of the smartphones landmarks(each corner). This app provides multi-model feedback, audio and tactile. To begin thier end-user testing they have 18 participants (9 partially blind, 9 fully blind) navigate from a building to a subway across 430meters while using the app. The feedback about the proper direction is constantly provided and the phone vibrates when the direction is the correct. These participants that are partially blind performed better both using just audio feedback and using multi-model. The fully blind participants actually halved thier travel time switching from audio only to multi-model. The app made use of a waypoint system, these participants would not simply go straight to the destination but instead follow waypoints sequentially. Something of note is that the authors supposed an idea that the users could comment on waypoints so that when another person takes the route they can hear the comment and hopefully be provided with helpfull info.
At the end of this study the participants where asked a series of questions:
> Q1) After the training, do you think the wayfinding application
software is easy to use for blind users?
> Q2) Is it easy to choose a specific destination?
> Q3) Is it useful that the wayfinding application contains physical
references on the route?
> Q4) Is there enough auditory feedback?
> Q5) When the auditory and tactile feedbacks are activated, is the
navigation better than when you are using only audio?

## Conclusion
>Multi-model is proven time and again that it is the ideal feedback medium (audio-tactile).

>From the authors results it is shown that partially blind participants perform better in all test cases.

>Questionaire results are shown in Table 1. shown that most features of the app are effective.

>All participants preferred the fixed regions.

>Constant feedback was preffered.

>A waypoint system is effective.

in the reverse path, the average time decreased down to 10 min for blind people
and 8 min for limited vision users. Furthermore, when users were
using the second mode (audio, touch screen and tactile feedback)
in the second trial, the time spent also decreased: 14 min for blind
people and 12 min for limited vision users when they are walking
from the building to the subway and the reverse path was the half
the time for both types of users. This fact is due to the users
learning both the path to follow and how to interact with the
wayfinding application of the smartphone. 

__We can conclude that the wayfinding application is well designed and
it is usable and accessible for visually impaired people__

## Lessons Learned

1. Constant feedback is preffered
2. A comment system may be effective?
3. Fixed regions for application design is preffered.
4. Multi-model strikes again.(very effective and preffered)



## Questions
> 1. Is this app still availible today?
> 2. How scalable is the GUI using device landmarks?
> 3. Which type of constant feedback is preffered(audio or tactile)?

\newpage


# Usability Evaluation of a Web System for Spatially Oriented Audio Descriptions of Images Addressed to Visually Impaired People:
## Citation

[@10.1007/978-3-319-07440-5_15]

## Introduction
This paper starts by introducing the fact that 285 Million people are visually impaired and of those 39 Million are blind (worldwide). Next they present the fact that screen reader software is getting more advanced yet still generally lacks the ability to "read" digital images because it often lacks alternate text(html coding thing). This paper will present a software to address this issue as well as user backed testing. The user backed testing with verify the usefullness and the validity of the implemented solution. 

There are two main problems that are being addressed, firstly, alternative text is rarely properly placed/written. Secondly, the alternate text that is provided is insufficient.

It is difficult to write an image description that can cover various types of information that a visually impaired user could ever possibly need to understand.

The text description is insufficient to make users understand clearly the spatial arrangement of elements in the image.

The authors propose a solution to the spatial arrangement problem via tactile feedback. A basic solution is to create a tactile screen/display with pins or sensitive polymer membranes capable of forming complex outlines and shapes.

Expensive devices can remedy these issue's to a degree but cost in the thousands.
Instead the authors propose that a simple and cheap but no less effective solution is through multi-modal web based applications.

## Study
They developed a software prototype of a web technology called AudioImagem through which a sighted person is able to delimit areas within an image and associate audio descriptions to them. There are two forms of use in the app and these are: static mode and navigation mode. Static mode doesn't depend on cursor position(can place cursor anywhere and won't affect outcome). Their are two ways to get audio descriptions in static mode: short response and long response. Simply put they are short and long descriptions of the image. These descriptions rely on programmers/users to type out both descriptions for the images.

The next mode navigation mode is where a user can guide the cursor around the image and obtian descriptions based off of position on the image. Again, these descriptions rely on a real human to type them out.

In navigation mode if the cursor leaves the image the app will have an audio queue for which side the cursor left out of. 

The authors added a end-user test to determine the usefullness. 5 participants where monitored through cameras, keylisteners, screen recorder, and microphone, and tasked with a list of 12 tasks. 

__For Example:__
Task 2:
> Short description: “Photo of an autumn landscape”. (C key)
> Long description: “This is a photo of a bleak autumn day landscape. There is a street crossing the photo on the left and a leafy tree with orange leaves on the right side”. (L key)
> Task: “Observe the photo and describe as you understand it” (T key)

__Task List:__
>tasks 1 and 2 displayed landscape photos

>task 3 a drawing of the world globe

>task 4 a geographical map of Brazil

>task 5 an ecosystem flowchart

>task 6 a trigonometric table

>task 7 an algorithm flowchart

>task 8 a drawing of the kinds of cow meat

>task 9 a phase graph diagram of chemical substance

>task 10 a plan drawing of chessboard with all pieces

>task 11 a diagram of Daniel chemical cell

>task 12 a figure of the periodic chemical table

Each task was designed to take 5-10 minutes.


## Conclusion
In conclusion:
On average the 5 users spent 2 hours and 20 minutes to complete all tasks.
This meant it took 11.5 minutes on average per task.


| Users | Kind of disability| Screen reader experience | Tasks concluded |Tasks part. concluded | Tasks not concluded|Time test (hour)| Tablet (Pen or Finger)
| ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- |----------- |
| P1 | Low Vision |Yes  |11|0|1|1:59|Finger |
| P2 | Blind      | Yes |5 |1|4|1:58|F and P|
| P3 | Blind      | Yes |4 |4|2|2:43|F and P|
| P4 | Low Vision | Yes |9 |0|2|2:21|Pen    |
| P5 | Low Vision | No  |5 |0|7|2:49|Pen    |




## Lessons Learned

1. Screen reader experience matters when developing something like this.
2. 



## Questions
> 1. Can the use of AI speed up or improve this design?

\newpage


# Evaluating Fitts’ law on vibrating touch-screen to improve visual data accessibility for blind users:
## Citation

[@LAHIB201816]

## Introduction
The goal of this paper is to evaluate whether or not Fitts' Law can be applied to a vibrating touch screen in the context of blind users. In this case the blind users where either fully blind, blindfolded, or sighted.

To evaluate Fitts' Law the authors produced thier own app that would be used to record the data and calculate Fitts' Law along with relevant data points. This app was made to study the ability of blind users to tap specific shapes on a touch-screen while varying different parameters: mainly(target distance/size, and angle of attack). 



This paper's highlights:

> Reviews the literature on Fitts’ Law and visual data accessibility solutions for blind users.

> Studies the ability of blind users to point to shapes(circles) on a vibrating touch-screen (VTS).

> Varies different pointing task parameters: target distance, target size, and angle of attack.

> Fitts’ Law can be applied for blind users using a VTS when varying target distance and target size.

> Fitts’ Law is not verified for blind users using a VTS when varying the angle of attack.

Aside from everything stated above, this experiment was conducted NON-multi-modally.

## Study
As the expirement protocol three pointing task experiments where performed in which 1 parameter changed per experiments.

> 1. Distance variation from target
> 2. Size variation of target
> 3. Angle of approach variation

Every experiment first contained a "Mapping/Learning" phase where the user would point(__not touch/tap__) to both points with the help of a test overseer. 

Firstly each user would be told, the experiments to be conducted, the nature of each experiment, the tasks to be completed, as well as how to handle the vibrating touch-screen, environment (e.g., how targets are presented on the vibrating screen, control buttons, etc.). In addition, test subject profile data (e.g., name, age, gender, type of blindness: since birth or after birth, etc.) is recorded at this stage. After this stage the users would enter the actual testing phase where they were tasked with touching given points on the screen.


__Experiment 1:__
The goal of this experiment is to prove the following hypothesis: A pointing task performed by a blind user on a vibrating touch-screen is affected by the distance between the source and the target points following Fitts’ Law.

The distance being varied was ranged between 120, 200, and 240 pixels on a 1280x800 screen with a density of 149 pixels per inch and a 10.1 inch screen size.

The size of the target is fixed and the angle is fixed at 180 degrees(horizontal).

__Experiment 2:__
The goal of this experiment is to prove the following hypothesis: A pointing task performed by a blind user on a vibrating touch-screen is affected by the size of the source and the target points following Fitts’ Law.

The target size being varied ranged between 40, 60, 80, and 90 pixels using the same screen configuration as above. 

Because the targets are circles the size refers to the diameter of the circle.

The distance is fixed and the angle is fixed to 180 degrees(horizontal).


__Experiment 3:__
The goal of this experiment is to prove the following hypothesis: A pointing task performed by a blind user on a vibrating touch-screen is not affected by the angle between the source and the target points, following Fitts’ Law.

The angle being varied ranged between 0, 30, 60, 90, 120, and 150 degrees.

The distance is fixed to 120 pixels and the target size is fixed to 40 pixels.

__Users/Testers:__
Twenty-nine testers,  aged between 21 and 30 years old, participated in the experimental evaluation:
> i) six Blind Since Birth (i.e., BSB)(1 female and 5 male)
> ii) seven Blind After Birth (i.e., BAB)(5 females and 2 males)
> iii) sixteen Sighted (8 females and 8 males).

 The authors asked half of the sighted testers (4 females and 4 males) to conduct the experiments Blindfolded (i.e. BF), whereas the other half conducted the experiments sighted  (so that  we could  compare and contrast results)

All  in all,  each  tester  performed: 4  (runs of  Experiment 1)  x 3 (distance variations) x 25 (pointing trials) + 3 (runs of Experiment 2) x 4 (size variations) x 25 (pointing trials) = 600 pointing trials.  


## Conclusion

>- Results of Experiments 1 and 2 show that MT (movement time) and Err (tapping error percentage) for all groups of users tend  to  concur  with  Fitts’  Law,  where  both  average  MT and  Err  increase with  increasing  target distance  (1)  and decreasing target size (2). In other words, both hypotheses of Experiments 1 and 2 have been verified.

>- Results of Experiments 1  and 2  also show  that BAB testers produce  the highest  MT and  Err levels,  followed by  BF testers and then BSB testers.

>- Results of Experiment 3 show that MT only marginally varies with varying angles of the target, which concurs with Fitt’s Law: given that angle variation is not a parameter in Fitt’s mathematical model.

>- Yet, results of Experiment 3 show that average Err levels are seriously affected by changes in the angle of the target, where Err is highest with steep angles (e.g., 120° and 60°), and lowest with close to flat (e.g., 0°) angles. Err is highest with BAB testers, followed  by  BF  and then BSB.  Given  the  latter, we can state  that  Experiment  3’s  hypothesis  is not verified: A pointing task performed by a blind user on a vibrating touch-screen seems to be affected by the angle between the source and target points. 



## Lessons Learned

1. Fitts' Law can be applied to touchscreens with blind users when the distance and target size are being considered but not when angle is being considered.
2. a single medium of feedback is still affective in this context. (varying distance and size).
3. 


## Questions
> 1. I wonder if the reason for the varying angles producing more error is because of the practice the had from the previous 2 experiments.
> 2. Will the use of multi-modal feedback be able to be evaluated by Fitts' Law and if so, will it improve the MT and decrease error rate?
> 3. Will using a plethera of vibration motors in the device improve performance?

\newpage


# The Reliability of Fitts’s Law as a Movement Model for People with and without Limited Fine Motor Function:
## Citation

[@10.1145/3373625.3416999]

## Introduction
The goal of this paper is determine how affective Fitts' Law is on subjects with limited fine motor skills. It does not cover anything about visually impaired peoples or blind people. However, this paper may still be relevant to our research.

This paper will explore specifically the test and re-test reliability of Fitts' Law in terms of throughput and model fit. 

## Study
__Apparatus:__
> Microsoft Surface Book 2 laptop measuring 13.1" by 9" set as 3000 x 2000 resolution running the Windows 10 operating system, using 8 GB RAM.

__Test Procedure:__
> "Each participant took part in two sessions, which were at least four and at most 48 hours apart. In each session,participants performed 10 target acquisitions for 5 target widths (W : 8, 16, 32, 64, 128 px) × 3 target distances (A: 256, 384, 512 px), for a total of 15 A×W conditions and 10×15 = 150 target acquisitions. Each acquisition was a single attempt to click a 1-D vertical“ribbon target” (Figure 1). The target sizes and distances were decided based on typical icon sizes and the distances between the elements present in conventional user interfaces such as Web pages. To account for learning efects, the order of the conditions was randomized across sessions and participants, as is standard practice in Fitts’s law studies. Participants were instructed to perform the tasks as quickly as possible while conforming to an error rate between 4-8%, equating to a total of 6-12 target misses per session. Participants were given the choice to practice the tasks before the start of the session. However, none of the participants chose that option and found the instructions sufcient. Additionally, participants were encouraged to take breaks in between the A×W conditions but not during the trials."

Participants were tested over 15 Distance×Width conditions in each of the two sessions, resulting in a total of 10×15×2 = 300 trials per participant.
With 50 participants, a total of 50×300 = 15, 000 trials were produced and analyzed in this study.

## Conclusion
Results suggest that Fitts’s law provides low test-retest reliability. Importantly, the test-retest reliability of Fitts’s throughput metric was 4.7% lower for people with limited fine motor function.

> "Additionally, we found that the model ftness of Fitts’s law as measured by Pearson correlation coefcient, r, was .89 (SD=0.08) for people without limited fine motor function, and .81 (SD=0.09) for people with limited fine motor function. Taken together, these results indicate that Fitts’s law should be used with caution and, if possible, over multiple sessions, especially when used in assistive technology evaluations"

## Lessons Learned

1. Reliablity of re-testing Fitts' Law is sketchy especially when evaluating with impaired users.
2. When testing for accessibility reasons, multiple testing sessions should be utilized.


## Questions
> 1. Will this apply to blind participants?
> 2. Can we make assumptions relating to blind participants?

















\newpage


# References