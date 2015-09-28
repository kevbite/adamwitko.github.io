---
layout: post
title:  "The Problem With 'Testers'"
date:   2015-09-25 00:00:00
last_modified_at: 2015-09-25 00:00:00
excerpt: "Why the go-to model for testers is wasted time and how they should fit in to the delivery process."
categories: testing
tags:  testers, development, delivery, functional, non-functional
image:
  feature: problem-with-testers.jpg
  topPosition: -50px
bgContrast: dark
bgGradientOpacity: darker
syntaxHighlighter: no
---

For the past few years I have proclaimed to my team mates that we should be hiring developers not testers. From further experiences I
do believe this bold and controversial statement to still be true but only for certain types of testing.

### So what types of testers am I talking about?

Every company I have worked for has hired a group of testers to write automated tests that exercise the functionality changed by the 
development team. I find this quite odd as each of these companies have strived for developers to be involved from idea conception, to coding,
deployment and operational support. So naturally writing and maintaining automated tests at the various levels is a requirement. 
This however stomps on the toes of these testers who seem to be duplicating effort but typically don't understand the code level detail of the 
system being changed. These testers therefore require developer involvement to remove blockers when a code level change has introduced failure. 
I have seen a lot of wasted developer work hours due to the ownership of higher level tests being the responsibility of non-developers.

### OK, so should we just go all out and fire the test team?

Well for a long time I would have responded with a "Yep!!", maybe even a "Please!!!".  I now believe testers should be freed up to pursue other types of testing that really add additional value - not just as a confidence booster that someone with the title of Tester has checked those pesky developer's code. I predict your traditional tester would feel challenged, excited and a lot more keen to perform non-developer-introduced-behavioural types of testing. Let the developers write
automated end-to-end tests and permit your testers the time to understand characteristics of your system that your company usually sees as a 'nice to have'. I'm talking about 
testing disciplines such as security testing, load testing, performance testing, penetration testing and even your bog standard exploratory testing.

Giving your test team the time and freedom to understand the characteristics of the system outside of the functioning behaviour will 
create a better understanding of the traditionally labelled 'non-functional' aspects of your system. Having this kind of understanding 
within the delivery team allows a developer to appreciate the value the testers are contributing in addition to the behavioural changes implemented
for a business requirement.

### To summarise

Employ testers who are interested in specialising in one or more testing disciplines. They will gain valuable knowledge within the 
delivery team in regards to the technical behaviours of your system without being seen as a hinderence, blocker, effort multiplier or seat filler. I know I would!  

-- Adam

