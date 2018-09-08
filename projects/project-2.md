---
layout: project
type: project
image: images/beatriz-perez-moya-111685-unsplash.jpg
title: Bank Records Editor
permalink:
date: 2018-08-30
labels:
 - C
 - C++
 - Business
summary: For my ICS 212 class, I created a customer-records editing program with a text interface and external storage capability.
---
<img src="/images/bank.png">
<img class="ui medium right floated rounded image" src="/images/rawpixel-602154-unsplash.jpg">

The final project for ICS 212 was a bank records editing program that combined several previous assignments into a single program. Each of the earlier assignments was an exercise in learning program structure and basic memory management in C. There were in fact two versions of the project, one in C and another in C++ that took use of the Object-Oriented features of the language, similar to Java, but both made use of 75-85% of the same core code. This was an individual project, something every student in the class had to do by themself.

It was difficult to integrate different files into a single project, so a bit of strategy was required to overcome this challenge. Portioning off entire sections of code was necessary to focus on individual components, and maintaining functionality throughout was the highest priority, that is, ensuring changes in one component did not alter the behavior of another in unanticipated ways. This required working on the program in something of a logical manner: a functioning menu was needed before any selections could be made, then adding records must be the next section to work, since the other sections were deleting records, printing records, searching records, and such. The entire project was an individual assignment.

The things I learned from this project were mostly memory management in C, that is, dealing with pointers effectively and making use of the heap properly, how to use the basic C standard IO functions, and the basic C string functions. I also gained a basic feel of C++, and learned to make use of some of its famous capabilities, such as operator overloading and passing-by-reference. Generally speaking, it was my first attempt at creating a basic user interface, with functioning controls and responses, which taught me to conceive of my own programs from a user perspective, which I had really not done before. I also learned how to debug quickly, which might have been the most important thing overall.
