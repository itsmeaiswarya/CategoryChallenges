# CategoryChallenges
## Description
   Warmup 
   Points: 150
   Find the "SOURCE" of the problems :P 
   Flag Format: inctfj{some_l33t_string} 
   [Challenge Link:](http://168.119.123.141:6070/)
   Category
   Web

## Initial Analysis
   since it's said to find the source of the problem, we move to the website with the link given and right click, then open 'view source page' to find the flag. 

## Further Analysis

* The steps included are:
  1. Visit the website with the link given and then right click and choose 'view source page' option.
  2. Then scroll down through the source page and you will find 3rd part of the flag given as html comments 
  **<!-- The third part of the flag : "_challenge}" -->**.
  3. Now reading the source code from beginning you will find a link "css/main.css" open it and scroll to last to find 2nd part of the flag as comments 
  ** /* The second part of the flag : "15_a_warm_up" */ **
  4. Back to the source page you will find a link "js/main.js" open it and scroll to last to find 1st part of the flag as comments in java script
  ** /* The first part of the flag : "inctfj{7his_" */ **
  
## Flag
inctfj{7his_15_a_warm_up_challenge}
