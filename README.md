# GCE CLK Campus Voice

*Your Campus, Your Voice – Connecting Every Voice at GCE CLK.*

GCE CLK Campus Voice is a smart and user-friendly communication platform designed for Government Engineering College Challakere (GCE CLK). The main purpose of this website is to connect students, teachers, and college management through a single digital platform. It helps students receive important announcements, share suggestions, and communicate their problems easily. Teachers can publish information about examinations, assignments, events, workshops, and other college activities.

Using HTML, we create the website structure, CSS (Tailwind CSS) makes the interface attractive, and JavaScript provides dynamic functionality, such as changing the website title, updating announcements, and handling button clicks.

The main goal of GCE CLK Campus Voice is to reduce communication gaps, save time, improve transparency, and make campus communication faster, easier, and more effective.

## Features

- Header with the app name, tagline and a "+ New Announcement" button
- Hero section: "What's happening on campus?"
- Category buttons (All, Academic, Events, Placement) that filter the announcement cards
- Announcement cards showing category, title, description, date and time
- "+ New Announcement" opens a form (category, title, description, date, time) and posts a new card at the top
- The browser tab title updates with the selected category
- Announcements are saved in the browser (localStorage), so they remain after a refresh
- Responsive layout with light and dark mode

## How to run

Unzip the folder and open `index.html` in any browser. An internet connection is needed because Tailwind CSS loads from its CDN.

## Project structure

```
gce-clk-campus-voice/
  index.html   page markup, Tailwind classes and JavaScript
  README.md    this file
```

## Next ideas

- Let students send suggestions and problems to the college
- Save announcements to a shared backend so everyone sees the same posts
- Sign-in for teachers and management, so only they can post
- Edit and delete announcements
