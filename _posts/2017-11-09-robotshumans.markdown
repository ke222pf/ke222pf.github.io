---
layout: post
comments: true
title:  "how I implemented robots.txt and humans.txt"
date:   2017-11-09 10:37:27 +0100
categories: General
---
## Robots and Humans
I made new files for both `robots.txt` and humans.txt in src. in robots.txt i implemented user-agent: * which means that it applys to all robots, and Dissallow: / this means that robots should not be able to enter the site. Whit `humans.txt` i implemented contact information about me, so other people can see whos behind the site.

humans.txt is a txt file that holds information about the people that is involved with the site.

robots.txt lets the robot know if it can enter any pages or not. though this insent guaranteed the the robots is going to follow your command. its more a guide line.
### Humans.txt
```
Chef:Karl Erelöf
Contact: ke222pf [at] ke222pf@student.lnu.se
Twitter: @Erelof
From:Stockholm, Lidingö, Sweden
```
### Robots.txt
```
User-agent: *
Disallow: /
```