---
layout: post
title:  "Days are getting longer..."
date:   2018-02-28 14:14:00 -0500
categories: OpenMTR Updates
---

Everyone has been keeping their noses to the grinding wheel this week and a lot of work has been accomplished with the addition of the Dev Tools page, Meet the Team page, OpenMTR refactors, and OpenMTRDemo UI improvements.

* Alan is working on adding a collapsible feature for the side bar on the website.

* Nick is now full time back on the OpenMTRDemo program.
His work includes taking each filter and adding it as its own class.
This will allow the user to apply multiple filters to one image even if it's the same filter.

* Bryan is still grinding away at the OpenMTR project and has fully isolated the dials on dial meters.
He also refactored the code to read in meter data in the form of JSON objects that had quite a bit more information.
Having more data will give us the ability to create a more refined decision tree when choosing which reading to obtain.
The advantage of using JSON is that if/when we turn OpenMTR into an API we can pass JSON objects back and forth.

* Todd is working out the kinks of setting up a layout for the team page which can be a bit of a challenge using jekyll.

* Matt, while in the midst of mid-terms, has still had time to review pull requests, fix merge issues in pull requests, and tweak the OpenMTRDemo main page UI.
He will continue to work on OpenMTRDemo this week to add a few more features to the main page of the application.
