# Handbook

# Table of Contents
1. [Introduction](#introduction)
2. [Task estimation in scrum](#task-estimation-in-scrum)
3. [Coding standards](#coding-standards)
4. [Code reviews](#code-reviews)

## Introduction

### 1.1 Welcome
As a new employee, you will receive a written handbook of best practices.
This document outlines the general best pratices you must follow during the development of a project. Please read it carefully.

### 1.2 Purpose of this Handbook
This Employee Handbook is designed to provide you with information about working
conditions and practices you must follow.
You will learn about Task estimation in scrum process and the coding standards you must follow to help your co-workers understand your code.
The last part is about code reviews, you must keep in touch with your co-workers work.
The information contained in this Handbook applies to all our employees. Following
the policies described in this Handbook is considered a condition of continued
employment. However, nothing in this Handbook alters an employee’s status.
You are responsible for reading, understanding, and complying with the provisions of
this Handbook. Our objective is to provide you with a positive and safe work
environment.

## Task estimation in scrum

__Links:__
- [Tactical Project Manager - Estimating efforts hours in projects](https://www.tacticalprojectmanager.com/estimating-effort-hours-in-projects)
- [GitConnected - Learn task estimation secrets](https://levelup.gitconnected.com/learn-task-estimation-secrets-644e8cbca89e)
- [Team Gantt - How to estimate projects](https://www.teamgantt.com/guide-to-project-management/how-to-estimate-projects)
- [Jeremy Phelps - Simple guide to software task estimation](https://jeremyphelps.com/blog/simple-guide-to-software-task-estimation.html)
- [Mindtools - Estimating time accurately](https://www.mindtools.com/pages/article/newPPM_01.htm)
### 2.1 Topics introduction
Task estimation is a very crucial subject, especially if you're working in sprints, following the AGILE Scrum method. The scrum master will plan the differents issues and tasks for the sprint, he needs an estimation of every tasks so he can assign people on these, splitting them fairly and efficiently across team members. Time estimating, as important it is, is also a very uncertain science, you only know the right answer once the task is finished, but then it's too late because this information is worth only if we have it during the planning phase. We will discuss the do's and dont's of task estimating.
### 2.2 Important guidelines
- Use your experience
- Ask validation from senior team members
### 2.3 Topics
One of the hardest question you could ask to a developer would probably be "how much time do you need to complete the following task ?".
There are lots of differents systems out there, some use points, other system directly use time units as a man-days.
You will find yourself in the situation of estimating a task you never done before, so you'll have to take in consideration the learning time and possibles issues you will encounter during the development phases.
Since you cannot just pick a skill and multiply it by the amount of times it is required and then sell it to your boss or your client, you have to find a way to estimate every task and minimizing the margin of error.

The idea is that the more time you spend on the estimation, the more accurate it will be. But then, if you spend too much time on it, then it will be more expensive than a poorly accurate estimation. We have to find the right balance on time estimation, practice is the key here.
When it comes to the technique and how to foresee the time estimation, it pretty much always come down to experience.
First solution is to use your own experience, try to keep track of the time spent on similar tasks so you can use this data to be the most accurate possible in the future.
In the case of a new technology, or a new technology stack, don't take the risk, take time to identify the problems and study them correctly, doing a POC could also be a solution.
Another way to solve this problem, or a way to be more accurate, is to ask an expert or a colleague, so he will be able to help you and comment on your decisions.
Every feedback is good to hear during this phase of the planning.
It will help you find a smart solution and estimate your time accurately.

When your tasks are estimated, you will have to write it down and save it so everybody in the team will be able to have the same information about this matter.
Very different solutions exist in this regard, from simple Kanban board tools to a very complex cluster of various tools in order to have a complete overview of the task, the time estimation, the progress and the different unforeseen issues that the support service will give as feedback for us.
The use of Kanban board can be very helpful when it comes to plan the different issues and sort them by relevance and priority.
But it lacks a real time management module and make the presentation of the data very hard to overview for the manager.
That's why other complex solutions are available for bigger projects.
If your project is simple, and does not need a long-time support, a simple Kanban board as Trello of the board in GitLab tool is enough.
On the other hand, if your solution needs a better overview of the multiple tasks and also have a crucial need of support in the long run, more complex tools as Jira should be considered.

## Coding standards

__Links:__
* [Medium](https://medium.com/@psengayire/the-importance-of-coding-standards-and-conventions-in-the-software-development-team-how-they-can-5d252556a05#:~:text=Coding%20standards%20are%20collections%20of,methods%20for%20a%20programming%20language.&text=Without%20the%20coding%20conventions%2C%20every,code%20in%20the%20near%20future.)
* [Wikipedia](https://en.wikipedia.org/wiki/Coding_conventions)
* [Geeksforgeeks](https://www.geeksforgeeks.org/coding-standards-and-guidelines/)
* [isocpp](https://isocpp.org/wiki/faq/coding-standards)
* [aversan](https://www.aversan.com/coding-standards-and-best-practices-2/)
### 3.1 Topics introduction
Coding standards are collections of rules and guidelines that determine the programming style, procedures, and methods for a programming language. Using the right one will help you write cleaner code.
Without coding conventions, every individual in a team would settle their own coding styles. It would not be easy to maintain and debug the code in the near future.

### 3.2 Important guidelines
* Easy team integration
* Increased code quality efficiency and easy for maintaining
* Reduce code complexity
* Reduce development cost
* Naming Convention
* File and folder Naming and Organization
* Formatting and Indentation
* Commenting and Documenting
* Classes and Functions
* Testing
* Code Linters
### 3.3 Topics
The developer's world has too much coding standards. It is important in a software development to select the better one. Those coding standards depends on the language used, i.e. in C++ you would not use the same coding standard as with Java or PHP. It will also depend on the company. You will have three best options, the easiest option is to follow a coding standard which already exists, another way will be to follow a coding standard and make small change because it does not feat with your company rules. The last option will be to create your own coding standards.

The most difficult for a developer is to follow or work with another developer who does not use the same coding standards. During the development you must create new folders and files. It is important to use the same naming convention and folder structure to save as much time as possible when you are looking for a specific file. i.e an asset like a picture or a font.
Read code from someone else can be hard when the naming conventions are not the same. For example all class names must be in PascalCase and the variables must be in camelCase. If you use an opposed standards convention for the naming, the other person could not understand what your code is supposed to do really fast. Our team will lose time and the development cost will be increased.
When you are working in a team on the same project an important part is the testing. Two co-workers could be working on the same feature, and without testing, the other co-worker could break your part without knowing what he is doing. Testing has this role to insure no one broke your work with additional code.
All developers does not have the same abilities or the same skills. It is important to comment and document. It will make it easy for the other co-workers to understand what is happening in your class, your function or your package. Without comments, the developer must read and understand the whole concept to work with it. Again, it will increase the time, so the development cost.
The indentation is also important to increase the code readability. A bad indentation will make the code really hard to understand.
The last important point on Coding Standards is to use tools to help you to increase your code quality. Here we are talking about Code Linters; It is a tool which analyze your source code looking for problems. It will reduce errors in production, but also make readable, maintainable and more consistent code. With this tool you will avoid syntax errors which is the most basic and more vital type of checks that a linter can provide.

There are no bad coding standards, the important is to follow the same coding standards during all the software development. The coding standard must be defined at the start of the development. Everyone who is working on the project must also follow this coding standard to insure the good work of the software development.

## Code reviews

__Links:__
* [Definition - GeeksForGeeks](https://www.geeksforgeeks.org/secure-code-review-assessment/)
* [How To - ItNext](https://itnext.io/performing-a-code-review-1297967683f6)
* [Best Practices - Trisha Gee](https://trishagee.com/presentations/code_review_best_practice/)
* [Mindset - Medium](https://medium.engineering/the-code-review-mindset-3280a4af0a89)
* [Experience from Google - FullStory](https://www.fullstory.com/blog/what-we-learned-from-google-code-reviews-arent-just-for-catching-bugs)
* [Efficient code review - Rahul Nath](https://www.rahulpnath.com/blog/code-review/)

### 4.1 Topics introduction
Code review is a systematic peer review of software source code and is similar to the process that takes place in a reading committee, the objective being to find bugs or potential vulnerabilities or to correct design errors prior to the software release, thus improving its quality, maintainability and security.

### 4.2 Important guidelines
* Code maintanibility
* Bugs & security threats prevention
* Collaboration & team cohesion
* Documentation
* Knowledge sharing
* Refactoring
* Accountability
* Time saving

### 4.3 Topics

#### Why ?
Even if simple errors like syntax or careless mistakes are catched by linters and unit or integration tests, some can pass through the vigilence of automated tools. It has been revealed that more than half of the errors are spotted by code reviews [source](http://www.ifsq.org/finding-ia-2.html).
Also, this is not because a code complete its purpose that it means it is good : performance and security must also be verified.

The experience of peers, whether it be on the language used, the project itself or its environment is then used in this process, not only to catch the error, but to share the knowledge, the developer will learn from him : its mentoring. Furthermore, it widdens the overall understanding of the project and facilitates future collaborations.

Finally, catching an error as soon as possible is deadly time and cost efficient, as the fix cost exponentially raises depending on the delay between the release and the reveal of the defect. Fixing it later could lead in more errors, as an abyssal technical debt.

#### How ?
The review should not be used as a way to ask for help about issue, it is only a process of validation, not of progression, unless issues are revealed and fixes are requested, possibly with suggestions given by the lecturer, which then reconduct to another code review.

As a lecturer, above all, remain benevolent, the author of the code may not be experimented and will not learn by being mocked. Also, do not hesitate to ask questions when you find something strange. Explain clearly what may cause a problem and highlight the involved lines. This is also the best moment to teach good practices, like clearer or more efficient ways of coding.

As a requester, make a clear request resuming what your code should realise, avoid at all cost commmits or comments like "Fixes", explain what you do. Your lecturer have to know before reading what he will dig into, and remain open minded, this is not a critic of your work but a valorisation of it.

Also keep in mind that if a discussed item is regularly raised, it should be considered to update the guidelines or create a best practice file to avoid it, especially for newcommers.

#### When & how long ?
The code review should not be performed at any time, it remains usefull only if it remains time efficient. This is therefore very important to request it only after the code has been commented, and tested, unless you want your lecturer to lose his time, and his sanity. Imagine it like an interview, you would only present yourself well dressed and prepared. This creates a kind of peer pressure, which will make you pay more attention on your work, consequently enhancing its quality.
Even if you fear it, the review must not be dismissed, everyone has to pass through them; even an experienced developer can fails, the difference between a good or a bad one only resids on its capacity to iterate when it does.

Documentation is the key to quick understanding, so don't hesitate to comment some lines, even something that seems obvious to you may not be clear to your colleagues.

#### What ?
Not only your code should be reviewed, but also tests, you may for example have forgotten to test a feature that your code should fullfill or a special case that may make it crash. Same goes for documentation, it is the greater source of maintanibility, botched, it might ruin it all.

#### Who ?
The review concerns the writter and at least one another programer, it is not required that this be a superior. Technically, even an unexperimented person can spot a difference between your task specifications and what you produced.

To conclude, do not forget that the first lecturer should be yourself.

<img src="https://miro.medium.com/max/1020/1*uDyb9W5jE0sVDHjPkG_o7w.png" align="left" width="500"> A situation to avoid, both parties must rely on the other one, but never lean on the fact his work will be done by someone else.
