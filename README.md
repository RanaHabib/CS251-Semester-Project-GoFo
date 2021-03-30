# CS251: Software Engineering I

## Assignment 2 – Project Description v1.

Cairo University, Faculty of Computers and Artificial Intelligence

## GoFo

## Go Football

## Introduction

This document describes the initial requirements of the project that we will start in assignment 2 and continue in assignments 3 and 4. It is the initial description received from the client. It might not be complete or unclear. Your job is to ensure full understanding of what the client wants. You can use **questions, interviews,** or other means to collect information from the client.

## Product Owner

The product owner is the client you will serve and satisfy his needs with this project.


## The Motivation for This Project

Thursday night is a good day to play football with friends, right? You called your friends Zyad Amr Abdelrahman and Mostafa Ashraf Mostafa to call the gang and book two hours at any playground near to you. They searched more than one playground to find the best one that is the nearest, most affordable and of course available at the time you need.

Zyad and Mostafa failed to do the booking, so they called Basel Abdelmonem Mohamed and Bishoy Tarek Azer to help search in their areas. They all failed to find a booking at the needed hours because it such a busy day. You all spent a lot of time, transportation cost and effort to go to all these playgrounds or call the owners. Frustrated with this scenario that happens often, the group got a brilliant idea. They decided to build a system for booking playing hours in football playgrounds. This is going to be a very cool application. The initial set of requirements they have is below.

## Project Description v1.

Our system is a booking system for football playgrounds. It serves the players and playground owners as well. An administrator oversees the overall operations of the system and ensures that


# CS251: Software Engineering I

## Assignment 2 – Project Description v1.

Cairo University, Faculty of Computers and Information

no fraud takes place. Anyone can register himself on the system and create a profile. He can see the playgrounds near to him or in a specific area or all of them.

**Playground owner.** This is the person who wants to register his playground. He first registers himself on the system and creates a profile like any user, with his name, ID and password, email, phone and default location. Then he requests registering a playground and adds its name, its location, its size, the available hours, the price per hour and the cancellation period. A playground is not active until approved by the administrator who may check if information given is true.

The administrator has the right to delete a playground or suspend it. This is usually the case if the owner does some fraudulent activities like double booking or if the playground gets a lot of complaints from the players. Then the administrator can activate it again or delete it completely.

The owner can set and change the hours available for booking for his playground. He can view his bookings. And he can check the money in his eWallet.

An eWallet is an electronic payment system used to allow players to pay for the bookings they make and allow ground owners collect their money. It is externally connected with a service like Fawry that allows players to add money to their eWallet and ground owners to take the money from it. Any user can check the money in his eWallet or transfer some of it to another eWallet. Adding money to the eWallet happens outside the system boundary.

**Player.** This is a person who is interested in booking a playground. He registers with the system and creates a profile as described above. He can display the playgrounds near to him or in a specific location on specific dates. He can filter them by the hours and date he selects. He can book a time slot of 1 or more hours if available and not booked. Booking includes (1) Checking available grounds and time slots (2) Selecting the free time slot(s) he wants (3) Calculating the total price (4) Paying the amount from his eWallet to the eWallet of the owner (5) The system updates the status of the booked slot(s) so no one else can book it, and optionally (6) The player can send invitation to his team members via email. To make this last step easy, he can create his favorite team and store their names and emails. Then he can select the entire team. Or he can enter individual names and emails or select the team and then modify some players. A player can also cancel a booking if within the cancellation period.

## Useful Tools to Use

```
1 - ArgoUML, Creatly, Visual-Paradigm or any suitable tool for creating a use case model and use case descriptions.
2 - https://trello.com/ to help you organize your tasks. Divide and assign to team members.
```

