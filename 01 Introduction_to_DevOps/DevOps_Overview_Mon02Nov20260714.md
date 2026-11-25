---
id: Mon02Nov20260714
aliases:
  - DevOps_Overview
tags:
  - DevOps
date: 02-11-2026 07:13:43
projects: "[[DevOps_Bootcamp|DevOps Certification]]"
---

# DevOps Overview

## Basic concepts

**Programming:** Creating software using differents programming languages.
It can be developed by a person or a team, by app or by feature or maybe a new
functionality.

**Software Testing:** Check the performance, how the new features behave. On
big software it may exist a dedicated developer to test the software and even
automated testing in order to release the feature or functionality.

**Release Software:** the precess of show the new feature to the users after 
testing the software, build it and run it on a server.

**Operations:** It is part of the software delivery cicle where the software 
run in *production*. It means the IT operation of running the created app into
the server intended to serve the app as a final product.

## The precess

In the concepts below, it is easy to identify to separated process that imply
differents responsabilities for developers and IT operations area, where in a 
traditional way to develop software, the develo[per team hand over the software
created to different team to deploy  that software and keep it avilable.

Part of this IT operations process include: 
- Integrate the new feature into the application.
- Avoid any down-time when upgrading or adding the new functionality.
- Care about the servers state. If a server crash, the app must continue working
- Handle the traffic, sometimes, millions of request by secounds.
- Make sure that the involved infrastructure and its performance is always the 
best.

It is easy to notice that they need 2 differents approach and knowledge and 
different tools. Software developers need more about programming languages,
frameworks, databases, software architecture, version control, etc.
It Operations needs more knowledge on Operating Systems, scripting, monitoring,
servers.

## The reality

As they have different responsabilities, knowledges and perspectives, the 
communication is very importan. However, in the practice this is complicated.
Both teams, do not have a framework to work together. They do not have the same
responsabilities or common requeriments or standars to work efficiently.

In the classic model, the IT operation team need some requied confurations for 
running tha app, like evironment variables, especific paths or folder the should
be setup in the servers, in summary they need to have prepared the environment
for the app be running.

So the development team hand over the instructions to the Operations team and 
they try to follow those instructions, as the deveopers do not have the knowledge
about the infrastructure capabilities or confurations, mostly the deployment 
fails because something is missing, or instructions are not clear, etc.

As consecuence of this classic clicle, a release takes long time and it was not 
efficient, so a solutions was nedeed to solve this issues where not standard or
misscommunication cause delays on release and money loses.

That solution was the **DevOps Culture** that in the begin was just an concept
or a way to work between **DEV**'s and **OP**'s that was borned in the way of
searching a common language for communicate the whole process.
Eventully, it beacomes to be a very well known role after realising that this 
culture has so many concepts and tools that one person or team was needed to 
handle the setup because the developers can not handle in their own role.

That way the DevOps engineer become to be a person in the midle of the developers
and the IT Operations team, being able to manage a common language between both
of them. Additionally, this last become to have his own skill set and know-how.

## The DevOps responsabilities

The core knowledge could be: CI/CD Pipeline. Test, build, push and deploy.

what help to acelerate the change of the old paradigma was the migration from
the traditional #Waterfall methodology to the #Agile methodology for developing
software faster.

> [!NOTE]
> For more context check about [Scrum](https://en.wikipedia.org/wiki/Scrum_(project_management))
> and [Kanban](https://en.wikipedia.org/wiki/Kanban) 
