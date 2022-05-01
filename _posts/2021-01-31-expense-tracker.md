---
layout: post
title: Expense Tracker
subtitle: This program is a Kitty application that can keep track of shared expenses
cover-img: /assets/img/Piggy1.jpg
thumbnail-img: /assets/img/Python.png
gh-repo: JasonBallantyne/ExpenseTracker
gh-badge: [star, fork, follow]
tags: [data-engineering, sql, spark, hadoop, nosql, big-data]
---

This program is a basic Kitty application that can keep track of shared expenses.

Consists of three classes: 
- Individuals 
- Event 
- Fund

Individuals class consists of each person in the group of friends. Only prompts for the instance of name. Event class class consists of the event the friends attended.Requires the instances details and participants.

Event class contains the methods "activity" (to check if the payee is a participant, if so, adds them to the "complete" list). Otherwise prints to the effect that they have not signed up for the event.

Event class contains the method "validate" (called by "activity" to check the data entered is valid). Event class contains the method "reconcilliation_acc" (to find the total cost), then divided by the number of participants to get how much each person owes. Prints to that effect. Adds participants who owe money to a list and participants who are owed money to a separate list. Calls the liability method.

The liability method within the Event class details who owes who money and prints to that effect
The fund class prompts for 4 instances, consisting of:
- Info
- Event
- Cost
- Payee.
