---
layout: post
category: [journal]
tagline: "May 13, 2013"
tags : [tuesday, orem]
---
## Morning
Today I started work on the secondary jurisdiciton story. We want to be able to 
search by state inside of the United States and by provinces in some of the English 
speaking countries.

## Standup
I received some pointers on where to look to get started on the secondary 
jurisdiction story. Which controllers might contain code to help me as well as 
the template files.

## Afterwords
I have one solution that isn't the best, but it adds wildcard searches for the 
secondary jurisdictions. I'll have to continue working on this story to make the 
searches go faster without using wildcards.

- - -

### What I learned
+ Controllers are a great idea so that you only have to write one controller to manage all of your forms with a single controller

### What I still need to learn
+ How the lucene queries filter out only a particular countries records

### What I wish I had already learned
+ A better MVC definition so that I can write better controllers