# A data distributor using Google Sheets.
a simple information query system that I made for my school, scrubbed of all information and released open source. It uses free Google services like sheets and apps script, but requires HTML hosting (e.g. google sites/github pages).

## Collection of Links
The Sheet: https://docs.google.com/spreadsheets/d/1EFKHZYJk4w5KePJIDlo_4ULRcJYV65tfCiqSNmcZuuA/edit?usp=sharing   
Google Apps Script file: https://script.google.com/d/15wOJWA5am1g3yIwW-2hLszJqqphpm41lVk18u0LR8umvAy0o4oxKe7L9/edit?usp=sharing
  
  
## You may use these files in any way you like, just note that following default behaviours:  
1. Please change the links in the google apps script, and after deploying also edit the links in the HTML document   
2. Always ensure that the sheet you are using has "version 2.2" (or whatever text in the script that it is checked against in google apps script) **in cell A9**. Additionally, I highly recommend copying the testing sheet provided above. Column C is for identifiers, D is reserved for a future feature, and E onwardsd will be sent to the requester.  
3. Regular Expressions in the HTML file _cannot_ be stored in a variable. I've tried, and wasted time troubleshooting it, so nope! Also, if you're changing or removing the RegEx, do remember to change it on the Apps Script side too!  
I'll add more when I can recall :D   

## Things that I'm still working on ##
Password Fields that are hashed when travelling from client to server-side and Google sign-in
   
   
 Please feel free to email me at ansellee23@gmail.com or lee_jia_Hong_ansel@students.edu.sg for queries, comments, etc...
 I hope my project will be of use to you!
