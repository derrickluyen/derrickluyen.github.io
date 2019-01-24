---
layout: project
type: project
image: images/oml.jpg
title: Math Team
permalink: projects/mathteam
date: 2019-01-23
labels:
  - Math Team
  - Oahu Math League
  - McKinley High School
summary: I competed in the Oahu Math League for 4 years as a student at McKinley High School on the Math Team.
---

<img class="ui medium left floated image" src="../images/mckinley.jpg">
<img class="ui medium right floated image" src="../images/math.png">

Math Team was basically a team where we competed against other schools in the Oahu Math League. There were two sides: JV and Varsity. JV consists of 9th and 10th graders while Varsity consisted of 11th and 12th graders for the most part. In this league, we have a total of seven meets throughout the school year in order to see which school has the best Math Team. Over the course of the four years that I competed in (2013-2017), our school's team placed 3rd in JV in 2013-2014, 2nd in JV in 2014-2015, 3rd in Varsity in 2015-2016, and 3rd in Varsity in 2016-2017. 

For this project, I was mainly just a team member for my first three years. I worked my way up the ladder and eventually in my senior year, I became one of the captains of the Math Team. As a captain, my role was to teach workshops to the underclassmen, make the schedule for Math Team, and basically just assist any and all members who needed help. I tried my best to provide an enjoyable learning environment while I was teaching and one of my main focuses was to make sure my members were comfortable with me so that they felt that they could approach me. The reason I did this was because when I was working my way up, I remember being shy about asking questions even though I needed help but the previous captains were all friendly and approachable so that made it easier.

Here is some code that illustrates how we read values from the line sensors:

```js
byte ADCRead(byte ch)
{
    word value;
    ADC1SC1 = ch;
    while (ADC1SC1_COCO != 1)
    {   // wait until ADC conversion is completed   
    }
    return ADC1RL;  // lower 8-bit value out of 10-bit data from the ADC
}
```

You can learn more at the [UH Micromouse Website](http://www-ee.eng.hawaii.edu/~mmouse/about.html).



