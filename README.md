# Codecademy_Capstone
Capstone project for Data Analytics and Visualization in Python

This is my capstone project for the Codecademy Pro Intensive Data Analytics in Python course.

# Background: We are analyzing the customer pipeline at a gym, MuscleHub, and how customers ultimately visit --> fill out an application --> purchase a membership.

Currently, all customers who visit take a fitness test prior to filling out an application. Based on some feedback, we worry this fitness test might actually be intimidating potential clients.

To determine if this was actually the case, we conducted an AB test as follows:

Visitors will randomly be assigned to one of two groups:

Group A will still be asked to take a fitness test with a personal trainer
Group B will skip the fitness test and proceed directly to the application

Goal: Determine if there is a difference between the 2 groups in number of memberships acquired

# Description of Data
The data used for this analysis is broken out into several tables:

visits
- contains information about potential gym customers who have visited MuscleHub

fitness_tests 
- contains information about potential customers in "Group A", who were given a fitness test

applications 
- contains information about any potential customers (both "Group A" and "Group B") who filled out an application. (Not everyone in visits will have filled out an application.)

purchases 
- contains information about customers who purchased a membership to MuscleHub.

