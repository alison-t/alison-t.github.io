---
layout: essay
type: essay
title: Learning and Growing
date: 2020-09-04
labels:
  - Software Engineering
  - Learning
---

## Everyone Needs Goals

<img class="ui medium right floated rounded image" src="../images/goal.jpg">

Going into ICS 314: Software Engineering I with little understanding of what software engineering is and much less experience with the topic, my main goal of this semester is to have a greater grasp on the field. So far, I have seen the course will involve Web development, which is quite intriguing. At the moment, the idea of being able to write the code to maintain a Webpage, much less a Website, seems impossible. Hopefully, the ICS 314 course will prove otherwise.

Outside of the expected intention to learn to code from a class with programming focuses, I would hope to have greater insight into the field of Computer Science and maintaining a professional presence on the Internet.

As graduation from college approaches, it has become more pressing to figure out what my post-graduate plans are and careers of interest. While I am still trying to find what career fields suit my interests, skills, and values, I hope that this course, and the future courses I am enrolled in, will provide me with some of the experiences necessary to figure it out. Despite only pursuing a minor in Computer Science, I plan to absorb as much knowledge as I can through the classes I do take. I believe Computer Science and programming are important skills to gain and apply to any field as our society progresses technologically.

## ... And Means of Achieving Them

Stepping away from school and career, the professor has designed the ICS 314 course to utilize his own "Athletic Software Engineering" pedagogy which puts focus on practice and competency, where acquiring skills is viewed as greater than just the ability to explain a concept. This system, I think, reflects views on learning, in general, that extend towards understanding over memorization.

The "athletic" approach to learning puts focus on active and almost-daily use of the skills taught throughout the ICS 314 course. This consistent exposure through the Workout-of-the-Day (WOD) focus our practice on the specific concepts being covered in the modules for the week and, despite being a bit difficult, the format makes for greater understanding of why some solutions work and how to approach the problems differently. The practice also makes it easier to find, fix, and avoid errors in the programs we type. A major example for me, would be the use of `this` in class functions.

For one of our WODs, we had to implement a `Menu` class, which contained various instances of `MenuItem`s. In my first attempt, I had written:

```
class Menu {

	constructor() {
  	this.items = [];
  }
  
  addMenuItem(item) {
  	items.push(item);
  } ...
```

This gave me the error that "items" was not defined. For a while, I was not sure how to fix it since I thought the constructor did the declaring and defining for me. Turns out, I missed the crucial step of putting `this.` before the class' variable I was referencing. While small, the five characters can make or break the function and the knowledge to look out for this particular mistake in my work proved useful in other WODs. Where this mistake kept me from completing an in-class, practice WOD, the practice of looking for the error and knowing how to correct it helped me finish the graded in-class WOD within the time-limit.

In the same way practicing different scales and songs on an instrument, having different conversations in a language being learned, or running through different drills in sports improve one's skill and assists in a well-rounded use of it, the consistency and differentiation between WODs have helped to improve my skills with JavaScript. This excites me about the course and what I will learning from it, along with its shaping of my approach to picking up anything new.
