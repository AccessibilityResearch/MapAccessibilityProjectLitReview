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
special conductive filement called Trijexx Conductive.





## Conclusion



## Lessons Learned

1. 


## Questions

\newpage

\newpage

# References