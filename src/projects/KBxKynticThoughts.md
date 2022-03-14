---
title:   Kyntic
context: proj
author:  Huxley Marvit
date: 2022-01-08
---

#flo #ref #incomplete

***

# Kyntic? sure!

[the repo](https://github.com/TheEnquirer/kyntic)
[the designs](https://www.figma.com/file/i2i4nugfhshJLqCwftb4wf/kyntic?node-id=0%3A1)



gradient:
https://cssgradient.io
background: rgb(171,197,197);  
background: linear-gradient(90deg, rgba(171,197,197,1) 0%, rgba(199,196,225,1) 50%, rgba(163,115,144,1) 100%);

inspo: https://miro.medium.com/max/2000/1*9XUTmFn8Ok0CeJ2QkI1_ig.png

auth: https://www.youtube.com/watch?v=oXWImFqsQF4&ab_channel=NaderDabit
or, https://www.pullrequest.com/blog/authentication-with-nextjs-and-supabase/


## database planning
*alright.*


have a table with

| uuid     | user | date   | data...                        |
| -------- | ---- | ------ | ------------------------------ |
| nanoid() | jeff | Date() | all the data in multiple cells |
| nanoid() | alb | Date() | all the data in multiple cells |
| nanoid() | alb | Date() | all the data in multiple cells |
| nanoid() | jeff | Date() | all the data in multiple cells |
and ect.

have another table, which stores user specific things:

| user | global data |
| ---- | ----------- |

#### global data
| workouts | activities |
| -------- | ---------- |

#### logging data
| date | mood | sleep | exercise (json?) | screen time | activities | notes | tics? tic data? | perceived severity? |
| ---- | ---- | ----- | ---------------- | ----------- | ---------- | ----- | --------------- | ------------------- |

mood: int
sleep: int
screen time: int
perceived severity: int
notes: text
exercise: json
activities: json

[[KBxKynticDesignReviewNotes]]


##  view screen!

https://hypeserver.github.io/react-date-range/
daily radar chart?

## possible additions
something that tells you what you have tracked at the top of the log screen




































