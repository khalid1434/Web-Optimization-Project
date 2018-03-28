##Running the project:

- I used ngrok software side by side with Python in order to get live link to use it in PageSpeed Insights website.


##Changes made in CSS file:

- CSS file has been inserted as inline script in index.html, since it's a very small file and it will not affect the performance very much
comparing to using external CSS file that will generate a "Get request". We always try to avoid requesting many external files 
as much as we can.


##Changes made in images:

- It was very helpful that I stored the images locally, again for the same reason avoiding requesting external resources.
- Also, images have been optimized in size to minimize the time needed to load them.



##Changes made in index.html:

- Google font request was moved to the end of the document to gain faster loading.
- media="print" was added to print.css file to avoid loading it unless the user asks to have printable page.
- async was added to analytics.js file to avoid render blocking.


##Changes made in main.js file:

- I avoid declaring the variables inside loops to ger rid of accessing the same variable for several times.
- Some medthods were replaces like "querySelectorAll", because it takes a while to be performed. 
- style.width was very helpful which took me sometime to figure it out LoL :)



My Regards
Khalid 

