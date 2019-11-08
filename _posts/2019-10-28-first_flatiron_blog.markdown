---
layout: post
title:      "First Flatiron Blog"
date:       2019-10-28 05:55:33 -0400
permalink:  first_flatiron_blog
---


My first project for Flatiron is complete! 

![](https://media.giphy.com/media/3o7abldj0b3rxrZUxW/giphy.gif)


I must say it was fun, sometimes stressful, but overall enjoyed it. Was especially excited as I had to switch cohorts due to added stress from work. But now, after leaving my past job, I am able to dedicate more time to Flatiron, and being able to make it past Project 1, I am finally ahead of where I was before.


**Project 1 Details**

We were giving a dataset on house prices in King County, Washington. From here, we were to view what features would be most important for our target audience. I, and probably 90% of Flatiron, viewed it as if we are presenting this data to potential flippers to understand what they should do to a home to boost up the prices. Okay! Seems simple, then after taking out null values, I was there confused wondering what to do now?!?!!?!

![](https://images.app.goo.gl/cvYNg9Pks2sPTKuQ8)

I am not used to open-ended projects. Was use to the Learn curriculum, where they told us how to manipulate data and they told us exactly what to do, but now I was lost.lol. After a talk with my Cohort Lead James, I realized I could drop data if it made sense for what I was trying to do. So thinking about the few Home Flipping shows I watched growing up (ok more like a million of them. I was a teenager during the major housing bubble so there were so many of those shows lol), I realized a first-time flipper is gonna need to work with a home he/she can realistically handle. Homes with more than 10 bedrooms? DROPPED! Homes worth over $1million? DROPPED! Homes over 3500 sq ft? DROPPED! Homes with lot sizes over half-acre? DROPPED! Fears of dropping?.....well.....dropped. My table was smaller, and my skews in certain variables were sexier:

![](https://imgur.com/a/kacSjzO)

*before*
<img src='https://raw.githubusercontent.com/melvingonzalezjr/dsc-v2-mod1-final-project-online-ds-ft-100719/master/student_new/output_16_0.png' width='380'> *after* <img src="https://raw.githubusercontent.com/melvingonzalezjr/dsc-v2-mod1-final-project-online-ds-ft-100719/master/output_33_0.png" width='380'>



Okay! Only geeky future data scientists get excited with data looking more "normal" and in the process look less normal to normal people.lol. But I am a proud geek 🤓🤓🤓. From here, came time to start working on my data, and separating Categoricals from continuous. But those darn ordinal features get me confused.lol. No one right answer as to whether to use them as categoricals(this is why I went into STEM fields, there IS suppose to be a simple answer not intrepretation!!). My rule of thumb for this project was if the numbers were related to each other, then keep data as is. For example, the homes had different Grades, indicating the quality of fixtures/renovations to home. But, a home with Grade 8 was not 2x as fancy as a home with Grade of 4. So Grade, Condition, Month_sold, and Zipcode were all categoricals to me, and I used them as such.

**Modeling Time**

- Was impressed with my first model. R2 was .815, but had 25 p-values over .05!! 😰😰😰
 - So then, I remembered how I looked at all my features as permanent features or features I can change/renovate.
- Using just the most important features I can renovate, my p-values dropped to 13, but R2 was down to .42!😵😵 NEXT!
- Using just the more permanent features, my p-values were also at 13, and my R2 went up to .54! 🤨🤨
*Getting there*

Used my original model, but having zipcode as my only categorical(it was the only categorical for permanent features).
- R2 jumped .781 and only 6 high p-values 😎😎😎

So, because I wanted to have at least two permanent features, and two features I can change, I used zipcode, latitude, sqft_living, and the grade.

- Final model came w/ R2 of .80, but p-values over .05 did jump to 12. Pretty happy with the trade off. Not too many p-values compared to all the subcategories within Zipcode and Grade.


**Non-tech stuff**

Doing a PowerPoint(ok Google Slides since I'm poor) was harder than I thought. It probably had been a decade since I last had to make slides for a presentation. Glad Google Slides has themes to help with making it look pretty. Definitely need to devote some free time to learn more about the features within PowerPoint/Google Slides.

When I had to do my video, I found a 7min video taking over an hour :( This was due to me stuttering, or getting lost in thought, or not knowing when to shut up. But finally got myself to finish a 7min video I was proud of.

*In the future, I would like to...*

Learn more about making presentations and actually presenting them. Look up tricks of the trade. Coding is cool and all, but in the real world, if I cannot communicate clearly to someone who cries at the thought of math, then what is the point?!?!?! This future data scientist will strive to be a well-rounded human-being. 4 more months til graduation!!! 
