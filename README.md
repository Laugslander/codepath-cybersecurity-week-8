# Project 8 - Pentesting Live Targets

Time spent: **3** hours spent in total

> Objective: Identify vulnerabilities in three different versions of the Globitek website: blue, green, and red.

The six possible exploits are:
* Username Enumeration
* Insecure Direct Object Reference (IDOR)
* SQL Injection (SQLi)
* Cross-Site Scripting (XSS)
* Cross-Site Request Forgery (CSRF)
* Session Hijacking/Fixation

Each version of the site has been given two of the six vulnerabilities. (In other words, all six of the exploits should be assignable to one of the sites.)

## Blue

Vulnerability #1: Session Hijacking/Fixation

![Walkthrough blue exploit 1](https://i.imgur.com/1PmVejt.gif)

Vulnerability #2: SQL Injection

![Walkthrough blue exploit 2](https://i.imgur.com/rsZAh08.gif)

## Green

Vulnerability #1: Username Enumeration

![Walkthrough green exploit 1](https://i.imgur.com/p7XIsg5.gif)

Vulnerability #2: Cross-Site Scripting

![Walkthrough green exploit 2](https://i.imgur.com/qGqluuR.gif)

## Red

Vulnerability #1: Insecure Direct Object Reference

![Walkthrough red exploit 1](https://i.imgur.com/Gvf572l.gif)

Vulnerability #2: Cross-Site Request Forgery

![Walkthrough red exploit 2](https://i.imgur.com/rVImgIc.gif)

## Notes

Describe any challenges encountered while doing the work

It took me some time to find out about the hacktool that shows the session ID, and I had to look up how to create the HTML script for changing the user data.
