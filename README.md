# Javascript Challenge v.1.3.0

This is a submission of a finished output for Betica

Using the provided HTML file, I have created a mobile web prototype that will list *ALL* the items separated by category. Based on the wireframe as a guide (wireframe.png). 

Submitted by: Jonathan Polancos.

### Regarding the Wireframe:
Please note that this is just a "wireframe" and we would expect you to apply some designs. Using Bootstrap or Foundation should suffice.

## Requirements:
* HTML5 and CSS3 required.
* Items should be dynamically added when the page loads.
* Please use Javascript only. We can reconsider jQuery... no other frameworks (ReactJS, AngularJS, Vue.js, etc...)

## Please answer the following questions:
* Please explain how did you come up with the solution. We would like to see your train of thought. - 
First I sorted out the items that is a category by finding objects that have non existing parents. 
This served as the Header and container in the HTML DOM which is appended dynamically using javascript.

Then those that do have a child is processed in a proper bootstrap presentation and is appended
to the div containers in category by appending it from getElementID(child's parent)


* Please explain any design decisions made (why you chose the design/framework, etc.) -

I chose the minimal and accurate design based on the wireframe that fits the requirements and fits as a mobile prototype.
I used available bootstrap themes for quicker development and better presentation.

* Please indicate tools that you used for coming up with your solution.

javascript 
bootstrap 
SASS 

* Choose one: Star Wars or Star Trek? Why?

Star Wars - In my opinion star wars has richer and deeper lore, better character designs and character development and I prefer the overall message of the story. Also due to nostalgia since I grew up watching them with my family.
