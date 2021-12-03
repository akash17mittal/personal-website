---
title: Decision Support System
date: 2020-04-30T12:16:04.987Z
summary: "**Decision Support System (DSS)** is a web application developed for
  government officials in India. It helps in managing the schedule, bringing in
  all the data of the city/district at a single place, and supporting decisions
  related to maintaining law and order & efficient implementation of schemes."
draft: false
featured: false
tags:
  - deploy
links:
  - url: https://dss-iitd.herokuapp.com/
    name: Web Service
    icon_pack: far
image:
  filename: featured.png
  focal_point: Smart
  preview_only: false
---
**Decision Support System (DSS)** is a web application developed for government officials in India. It helps in managing the schedule, bringing in all the data of the city/district at a single place, and supporting decisions related to maintaining law and order & efficient implementation of schemes.

The backend is developed in python (Django) and the frontend in ReactJS. Some of the key features include:

* **Calendar:** One can set the priority of different events and tag them. It also enables you to add notes/minutes of meetings to events.
* **Search:** It is always hard to find past events in standard calendars. DSS comes with a superb search functionality where you can search your past events with keywords in meeting notes, tags, event names, etc. It gives you a list of your calendar entries satisfying the search criterion. One use case is, if you add the same tag to the periodic meetings, on searching with the tag, it will give you a sequence of all the related meetings with that tag for easily viewing all the meeting notes from the past meetings.
* **Learn from the past**: One can define different types of events/happenings for e.g. natural calamities, crimes, organizing gatherings, etc. with multiple properties. It allows you to log the learnings from these events as well, such as "what logistics were to be arranged", etc. In the future, one can fetch the learnings from similar past events based on the properties of the event.

It is still under development, so there may be some UI level bugs, sorry :(