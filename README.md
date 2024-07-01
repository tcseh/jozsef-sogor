# Home assignment for the UI/UX Developer position

Dear candidate,

This repository serves as the working environment for your home assignment. You
have 10 hours to solve the tasks described below. Please document your work
precisely, so that we understand every detail of your solution.

## Table of Contents

1. [Summary](#summary)
2. [Requirements](#requirements)
3. [What we will evaluate](#what-we-will-evaluate)
4. [Suggestions](#suggestions)

## Summary

The goal of this programming exercise is to create a single page app to display and search Start Wars characters using [Swapi](https://swapi.dev/).

You can use any Front-end framework (Angular preferably, React, Vuejs etc.)
You should create a design too in any interface design tool (Figma preferably, Sketch, InVision etc).

## Requirements
- On page load display all characters returned from the endpoint `https://swapi.dev/api/people/`
  - Display the visible amount shown and the max result count
- Add a select so the user can sort the results by:
  - A-Z
  - Z-A
  - Male
  - Female
- Add a details view so the user can see more information about the selected character (e.g.: height, mass, hair_color, number of films)
- BONUS: Add a search bar to the top of the page. When a user types a character name and clicks search, it should call `https://swapi.dev/api/people/?search=` and update the results.
- The page should be responsive, ensure the layout looks respectable on mobile and tablet viewpoints.
- Open a pull request with the link to the design

## What we will evaluate

- Your code will be evaluated by: semantics, structure, legibility, size, among other factors.
- The git history will be evaluated.
- Our tech stack here is Angular, NGRX, Nx, SCSS and Bootstrap, we would like you to use the same stack, but it's ok if you use a different one.

## Suggestions

- The search feature is a BONUS, spend time on it only if you have some extra.
- It is not a problem if you run out of time, at the end of the allocated timeslot open a pull request with what you have by then
- Some parts of the exercise are deliberately not defined properly, so that you have some freedom to decide ( with this we are testing your decisions, as well ;) )

In case you have any questions regarding the data or the task itself, feel free to reach out to Tamás Cseh ( tcseh@iquantsolutions.com ).

Many thanks for taking the time and for dedicating effort to the exercise.