---
layout: post
title: What's my First Test in TDD
description: >
  While Following TDD, what should be the first test to write.
categories: [tech]
tags:       [TDD, Testing, CodeQuality, Design]
sitemap: false
image: /assets/tech/WhatsMyFirstTestInTdd/label.jpg
comments: false
---
0. this unordered seed list will be replaced by toc as unordered list
{:toc}

_Prerequisite (for TDD not this Blog) : knowing the basic of Testing Framework you are going to use and various kinds of Asserts helps_

# Are We Testing the Implementation

## Unit Test

means smallest Piece that can be tested

## What is the Smallest Piece in code?

its generally a Method (from Java perspective) or Function (from some other language)

_now by Definition_ : Developers start testing a particular method and Hence we Call them Unit Test

Now After some day people start to change the implementations, some test went irrelevant hence not working and Disabled temporarily (eventually forever) or some are partially working and Hence the tests starts to break due to Refactoring. **WHICH IS HYPOCRISY**

Core Reason why Developers made tests were to give them confidence to do Code changes frequently including Refactoring , now Same Tests are breaking with simple changes and Developing fear in Developer Mind to do the changes.

### Problem :

with the Above process was we wrote a method and then tested that method with a Unit Test , Rather we should have Stepped up our code with TDD, i.e. Test First and then write functionality into code

# But Question comes in mind, What should be First Test :

we are use to writing code , so we tend to break the bits and methods in our brain and in the end do same thing as above. and hence lead to same thing.

## Test Are Requirements

We need to test the requirements not the implementation as that can change anytime, hence we don’t need to be worried about the code that we will write from start, First thing We should keep in mind is we are Documenting the Code in form on Test Cases.

# Conclusion

As Developers we tend to say or Explain Tests are done so that we can have **Scalable , Modular ,High Quality Code** _which to Customers and Developers many a times seems like vague words and to make things worse Some teams go and Highlight Code Coverage as a Standard , and Demonstrate More the Better._

Rather We need to See Tests as Documented REQUIREMENTS.

So we document the requirement using the Test Code in GIVEN , WHEN , THEN format and See things from BDD perspective

and focus on more Developer Oriented Advantage

**DOCUMENTED REQUIREMENT** : Requirements are not Vague now as they are documented as part of Test.

If the Implementation change then Test Should not change.

**EASIER REFACTORING** : This forces us to refactor code in right manner , rather than making complicated Domains First and Then writing Repetitive and Complex Test Later

Is it All to get Started?

Obviously not, Requirement comes up as **TOP-DOWN** approach , however Unit Test are smallest piece of code hence are at method level and are **BOTTOM-UP**

_Mapping these both comes as next challenge, Next Blog Coming up._


# References

[1. How I Test](http://railscasts.com/episodes/275-how-i-test) 

[2. Fun Video Developers will definitely love this.](https://www.youtube.com/watch?v=a6oP24CSdUg)
