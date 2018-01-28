---
title: Developer Workflow
layout: default
permalink: /developer-workflow/
---

## Branch Names
Branch names need to be descriptive and dasherized. Examples of good branch names are as follows:
<br/>`matt-add-developer-workflow`
<br/>`bryan-fix-submit-button`
<br/>`nick-create-website-post`
<br/>`alan-update-documentation`
<br/>`todd-refactor-submit-method`

## Commit Messages
Well formatted commit messages will aid in the ability to follow the history of the project.
For our project we will use 5 types of commit messages:
- ### chore
  These messages will be associated with creating or deleting files within a project.
  <br/> An example of a chore commit message :
  <br/>`chore: Created new developerWorkflow page`
- ### refactor
  These messages will deal with code refactors big or small.
  <br/>An example of a refactor commit message:
  <br/>`refactor: Reworked GetPathFromUser method`
- ### update
  These messages will deal with updating of dependencies, posts, or out of date information.
  <br/>An example of an update commit message:
  <br/>`update: Updated gemoji dependency to 3.0.1`
- ### fix
  These messages will be used in regards to fixes the developer implements.
  <br/>An example of a fix commit message:
  <br/>`fix: Fixed bug that sometimes crashed the program when submitting data`
- ### feat
  These messages will be used when a developer implements a new feature.
  <br/>An example of a feat commit message:
  <br/>`feat: Implemented a new button that users can click to submit information`

## Pull Request Messages
Pull Request Message need to be formed exactly like commit messages but this will be an overview of what you did in your development branch that you want merged.

## Code Reviews
Code reviews are an integral part of the developer workflow. Developers need to receive feedback from time to time to highlight our weaknesses and strengths. There are a few good rules to keep in mind when doing a code review:

- Rule 1: Always try to find something positive.
- Rule 2: Take your Time!
- Rule 3: Review about 400 lines of code per hour.
- Rule 4: Do not review code for more than 60 minutes without a break.

Always remember the golden rule and treat others how you would like to be treated.<br/>
>Reviewing code is like kicking the developer in the ribs. A good reviewer can get a thank you for each kick dished out.
