# homework5.github.io
With this planner- you are able to input notes on the hour, hit save, and come back to the page later to see your schedule inputs for reference. 
The colors change with the hour for easier tracking of your day.

To make this simple daily planner interactive with js, I have added in some bootstrap rows in the html for lines 35-88.
These are all time blocks for the hour, designated with comments to show the start of the new horus between 9 am - 5 pm. 
In my js file, I added the moment in jquery to keep track of the time and day. 
I then added a for loop to interval through out the hours, so when the time passed the hour in a time block on the page, the color woudl change. This also works for the "present" and "future" color markers. This was done through jquery also with the ".class" in js which links back to the style.css page. 
To save the data to local storage , I used jquery also in line 33 of the js file. 
To pull the data stored in local storage so that a refresh on the page would still reflect your edits, I used jquery once again in line 27 of the js file.
