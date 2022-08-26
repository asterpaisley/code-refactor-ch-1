# code-refactor-ch-1
[Live Link](https://asterpaisley.github.io/code-refactor-ch-1/)

--CHALLENGE DESCRIPTION--
Given the starter code I looked for non semantic HTML elements that could be replaced with semantic tags. I commented out div elements and replaced them with more specific tags like header, nav, main, section, aside and footer. I then commented out the corresponding div elements in the css file, and adjusted the classes to match with the new semantic tags. 
There were many lines of repeated code in the css file that could have been simplified. To condense this code I created two new id's #sidebar and #forward. In the index I commented out the unique classes under main and replace with #forward. This allowed me to condense 1/3 directions in css for that section. I did the same for the .aside element, commenting out the unique classes and replacing the new id #sidebar. 