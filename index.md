---
layout: layouts/home.njk
title: About Me
templateClass: tmpl-home
# eleventyNavigation:
#   key: about
#   order: 10
---

Hi, my name is Dustin and I'm a full-stack web developer in Calgary, Alberta, Canada.

I have always loved using computers to create things - whether it was creating my first Star Wars fanpage on `fan.starwars.com` in middle school, starting my own web design business to pay for my post-secondary education, or using an Arduino to make a real life laser maze when I was a youth pastor. I also enjoy [hiking](/hikes), [building things](/teardrop), and [making ice cream](/icecream).

You can also find me on [GitHub](https://github.com/nosecreek) and [LinkedIn](https://www.linkedin.com/in/dustin-lammiman/).

Here are a few projects I've been working on lately:

#### Grocery Tracker

_Grocery Tracker_ is a tool for saving money on your next trip to the grocery store. It keeps a price history using API data from 11 Canadian grocery chains, and can email you updates when your favourite products go on sale! Think [camelcamelcamel](https://camelcamelcamel.com/), but for groceries. I created it to track grocery inflation and help Canadians save money!

If you'd like to test it out without creating an account, feel free to use this demo login:  
Username: _demo_  
Password: _demo_

- Website: https://grocerytracker.ca/
- Technologies: React, Redux, NodeJS, MongoDB

#### Buckets Viewer

{% image "images/buckets-mockup.png", "Buckets Viewer", "(max-width: 400px) 200w, 400w", "buckets-mockup", "png" %}

[_Buckets_](https://www.budgetwithbuckets.com/) is a fantastic envelope-based budgeting software created by One Part Rain. Unfortunately, it doesn't have a mobile app yet. So, I created _Buckets Viewer_ as a web app for viewing these budget files online, which allows users to view their budgets from their phones! It works by opening the budget file (which is actually a SQLite file) from Google Drive or Dropbox.

A demo budget file is available [on GitHub](https://github.com/nosecreek/buckets-viewer/blob/b5900b688e19f8726f90c71fce17340b846fa7d8/Sample.buckets).

- Website: https://buckets.nosecreekweb.ca/
- GitHub: https://github.com/nosecreek/buckets-viewer
- Technologies: React, SQLite, OAuth

#### Nose Creek Web Design

_Nose Creek Web Design_ is a web design company I founded in 2009 to design, create, and host websites for local small businesses. This has included designing custom WordPress themes and plugins, including a complete RV Rental booking system. I have succesfully completed projects for over 40 different clients!

- Website: https://nosecreekweb.ca/
- Technologies: PHP, MySQL, WordPress, JavaScript, SCSS

#### Fantasy Hockey Helper

_Fantasy Hockey Helper_ is a tool for analyzing your weekly matchups in Yahoo! head-to-head fantasy hockey leagues. It uses data from the Yahoo! Fantasy API and the NHL API to predict how many points both you and your opponent will score in each of your league's categories. The algorithm calculates its prediction using each player's weekly schedule, injury status, and average stats from the current season.

- Website: https://fantasyhockey.fly.dev/
- GitHub: https://github.com/nosecreek/fantasy-hockey
- Technologies: React, NodeJS, OAuth