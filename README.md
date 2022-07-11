# Boston's Top Salaries

The purpose of this exercise was to convert JSON data into a JavaScript file in order to manipulate it more easily and eventually gather the five highest salaries Boston residents made in 2014.

### How Exactly Did I Do It???

After curling the JSON file onto my computer, I conveniently converted it into a JS file simply by establishing the variable "boston", thus creating one huge array (see boston.js file in code).

Like any other array, I was able to pull different Boston employees by their index number and manipulate the data as I normally would. Within the renderTopSalaries function, I created a variable which sorts through all of the employee salaries, thus creating a list of the salaries in numerical order. I then used the .slice method to isolate the top five salaries (see index1.html file in code).

### Where To Next?

Since the JSON file has been converted into a JavaScript array, one could easily manipulate the data however they wanted; finding the median salaries, finding the number of employees who made more than $90k, etc. 
