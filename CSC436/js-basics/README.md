# js-basics

github url: https://github.com/njchimmy/js-basics/tree/master/CSC436/js-basics

- chicagoStartupsReverse manually reverses the master list of startups and returns an array of the reversed list. It does not call .reverse(). 
- In renderReversed Elements, chicagoStartupsReverse is now called, and there are two additional lines of code to add a css style class for text padding. Lengths of each string are printed next to the string in the console.
- Added css classes for padding for the lists and for the html body
- Added bootstrap stylesheet and buttons with bootstrap button styling
- Implemented whitespace and special character trimming with regex in cleanAndCountCharacters()
- Implemented helper function displayCountCharacters to count and render all characters using an object to create a character map. Lowercase and Uppercase are counted separately. Whitespaces are not counted.
-Created initReverse and initToggle to create containers for both lists.
- toggleDisplay():
- Implemented garbage collection - toggled list elements are removed and re-added when switching between div and span.
- A direction flag was added to the var flags object to store the state of the list to switch between div and span
- init functions for Reverse and Toggle were added, they behave similar to initCount()
- Invoked the function expression by adding () to display the homework instructions in the console.


# log
commit (HEAD -> master, origin/master)
Date:   Tue Sep 24 22:58:59 2019 -0500
    fixed regex to ensure only one whitespace between words where there were multiple

commit 
Date:   Tue Sep 24 22:53:10 2019 -0500
    Built in bootstrap styling. Added padding to html body and text throughout for better spacing.

commit 
Date:   Mon Sep 23 23:34:47 2019 -0500
    Added color to buttons. Added functionality to count characters and display next to Toggle list

commit 
Date:   Sun Sep 22 19:42:23 2019 -0500
    added background-color css class style to Toggle and Reverse buttons, removed from text background

commit 
Date:   Sun Sep 22 19:24:09 2019 -0500
    added background-color css class style to text on Reverse and Toggle clicks

commit 
Date:   Fri Sep 20 23:44:46 2019 -0500
    added initToggle fn to create Toggle button. Completed toggleDisplay function to change list direction on click

commit 
Date:   Fri Sep 20 19:55:07 2019 -0500
    completed function to print homework instructions

commit 
Date:   Wed Sep 18 21:27:51 2019 -0500
    completed reverse function to reverse order of chicago startups array

commit 
Date:   Wed Sep 18 21:14:43 2019 -0500

    first commit