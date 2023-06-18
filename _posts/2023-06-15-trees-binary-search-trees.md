---
title: Weekly check-in: Trees and Binary Search Trees
author: Tammy Metz
excerpt_separator: <!--more-->
---

## Agile check-in

### What did you do last week?
- Learned about trees and binary search trees
- Learned some Jekyll tricks so I could keep a running list of my posts on the main page
- Filmed and uploaded [video of me attempting a problem about a binary tree](https://www.youtube.com/watch?v=xFqrQWX9bAw).  It did not go well.
- Wrote [reflection of video](#reflection-on-this-weeks-video)
<!--more-->

### What do you plan to do this week?
- Review tries
- Choose a question and film it -- possibly another binary tree question, but almost certainly a question needing recursion
- Write reflection of the video

### Are there any impediments in your way?
- No

### Reflection on the process you used last week, how can you make the process work better?
- I think I have a good schedule now.  


## Reflection on this week's video

### Video link
[Click here for video](https://www.youtube.com/watch?v=xFqrQWX9bAw)

### I need to get used to
- Handling dead air and not knowing what to do next.  This is a small bullet point, but a HUGE deal, and will make a big difference for me.

### Things I'm thinking about
- I keep getting stuck on recursion things.  I have learned it over and over, so I think it's more of a confidence thing (and needing more practice I guess?).  Now that I realize this, it will be good to choose problems that involve recursion when possible (a safe bet when working with trees at least)

### What went well
- It was good that I explained what I was thinking to do recursively even if I didn't think that would actually work.  Need to do this more.

### What could go better next time
- When I was trying to come up with a solution for an array of values, I was meaning to reverse one of the arrays, but I never said it out loud and forgot to code it.  
- Now that I have looked at solutions, I learned the following:
  - My base case should have checked whether root itself was None
  - all solutions implemented a new recursive function within the isSymmetric function.  This was surprising to me, and it feels like this is not something I've ever seen before, but I'm sure that I must have?  At any rate, it's something to keep in mind.
  - They key logic was checking left.right vs. right.left
  - One solution used a stack as an iterative solution 
