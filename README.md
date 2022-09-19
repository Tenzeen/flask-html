#Part A: Create a new github repo called 'flask-html': 

Please follow along with lecture slides wk3b for tutorial associated with this assignment. 

Inside of the repo, please create at least 2 pages that are manually styled using HTML and CSS (no bootstrap). Each of the pages at a minimum should contain: 
- static text (e.g., headers or paragraphs) 
- at least one image (e.g., png, jpeg, etc...) 
- a button (does not need to be functional)
 
 Was unable to use:
 
 link rel="stylesheet" href="{{ url_for('static', filename='about_us_style.css') }}". 
 
 As well as:
 
 link rel="stylesheet" href="{{ url_for('static', filename='welcome_style.css') }}". 
 
 When I had a static folder and template folder connected via the (link rel="stylesheet" href="{{ url_for('static', filename='about_us_style.css') }}") code, the styles would not show up on the webpage.
 
 However, when I used link rel="stylesheet" href="about_us_style.css" with the about_us_style.css file located in the same folder as my html files, the  styles showed up.
 
 Could not find a solution for this.
