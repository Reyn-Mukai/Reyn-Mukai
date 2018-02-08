---
layout: essay
type: essay
title: The Formatting Paradigm
# All dates must be YYYY-MM-DD format!
date: 2018-02-07
labels:
  - ESLint
  - Formatting
---

<img class="ui small right floated spaced image" src="../images/eslint.png">

It is often said that no one can truly know everything about a subject. This notion is particularly true with programming, which has a remarkably short knowledge half-life. Programming and software can be implemented in innumerable ways and problems which seem insurmountable can be overcome from a different perspective. Information on the web can offer this different perspective, however getting that perspective is not always easy. Asking questions on forums is the ideal way to solve certain problems and asking smart questions is one of the best ways to receive advice. Having a clear understanding of what differentiates a smart question from a generic question often means the difference between receiving an answer and being left empty-handed. Using StackOverflow as a basis, two questions will be examined and reviewed.

Collaboration is one the cornerstones of programming. Some of the numerous tools at our disposal include version control in the form of git and creating libraries with well defined interfaces. When working with code itself, readability becomes paramount as it is necessary for other programmers to follow the logic of your code. One of the core components of this idea is “proper” formatting of code. 
Recently, I created a discussion with many of my computer engineering and computer science friends about how they would format their code and why. One of the astounding conclusions which I unearthed about this topic is that people generally share the same core concepts when formatting their code. The main differences lie in what concepts they choose to emphasize. One programmer decided to format his code with readability being paramount. This means all modifiers were spaced and constructs such as classes were separated into their own lines. The declarations were even spaced to align vertically into columns. On the other hand, I format most of my code without any unnecessary spaces and only used newlines in certain use cases such as classes. The reasoning behind my formatting style was to reduce the line length to increase readability with all forms of editors including command line editors.
In my ICS314 class, the class standardized the formatting of JS code with an ESLint linter. The code format used by ESLint was drastically different from my own style of formatting and slowed down my programming speed by a noticeable margin. However, when working in teams, it was much easier to debug code with a standard formatting scheme. Due to this, I myself has formed an appreciation of standardizing formatting. That being said however, this standardized formatting is only applicable within the domain of the ICS314 class and multiple code formatting styles are likely to be an issue for the foreseeable future.
