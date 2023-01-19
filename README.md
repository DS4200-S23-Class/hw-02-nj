# hw-02
hw-02 - Static Webpage

Link to GitHub Pages: `[insert your clickable hyperlink here]`

Clone this repo and work locally. Be sure to push the final version of your code (and any significant updates along the way) before submitting. 

## Purpose

The purpose of this assignment is to practice more advanced HTML and CSS, as well as data and task abstraction.  

## Instructions

1. Resources to support this assignment are provided in the Resources section below.  

1. You can find a reference for what your final webpage should look like in the "reference" folder of your cloned directory. 

1. Create a GitHub Page for your repo and add the link to your GitHub Page above where you see `[insert your clickable hyperlink here]`. 

1. Using the index.html file included in your repo and an *external* stylesheet (no styling should be done inline; it should all be done via external css), please do the following: 

   - Make all font on your webpage Arial. 
   - Add a title: "hw-02".
   - Add a div with the id "data-abstraction". Inside of this div:
      - Add a div with the class "info". Inside of this div: 
         - Add a centered header: "Dataset Types".
         - Add a table with a blue header row. The table should have three columns: Data, Link, and Dataset Type. Add a row to the table for each dataset in the data folder of your cloned repo. 
      - Add another div with the class "info". Inside of this div:
         - Add a centered header: "Data Types". 
         - For each dataset you have, add a left-aligned header with the name of the dataset (UFO, Airports, Google-Web). Under the header, add an unordered list that lists the datatype of the columns and rows in the dataset. For any datasets that include attributes, list the attributes and their types as sub points in the list. 
   - Add a div with the id "task-abstraction". Inside of this div: 
      - Add a centered header: "Task Abstraction". 
      - Use [flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) css to make two columns. Inside of each colum:
         - Add one of the images in the img folder of your cloned repo. Make the image centered in the column. 
         - Under each image, identify the high, medium, and low level actions of the visualization shown in the image, and the target(s) of those actions. This text should be left-aligned in the columns and in a font color of your choosing (but make sure it is readable).  
   - Add a div with the id "decoration". Inside of this div:
      - Add a row of evenly spaced, alternating, circles and rectagles (you should use [SVG](https://www.w3schools.com/graphics/svg_intro.asp)'s'). The shapes can be whatever colors you choose. The circles should have 50% opacity, and the rectangles should have a border. The spacing of the shapes should be maintained as the page width changes (see the reference video). If the mouse hovers over a rectangle, it should temporarily change color. If the mouse hovers over a circle, a border should be temporarily added.        
   - Add a centered header to the bottom of your page. The header should say "Acknowledgements" in font smaller than the font used for your first header. Under this header, add a div. Inside of this div add a bulleted list of the resources you used to complete this assignment.  

## Resources 

* [HTML Page on w3schools](https://www.w3schools.com/html/default.asp). (On the left-hand side of the page there is a menu bar with links to various topics.) 

* [CSS Page on w3schools](https://www.w3schools.com/css/default.asp). (On the left-hand side of the page there is a menu bar with links to various topics.) 

* [DOM](https://www.geeksforgeeks.org/dom-document-object-model/). Focus on what the DOM is, and ignore how to manipulate it with JavaScript for now (we will look at this later).

* [HTML Basics](https://www.geeksforgeeks.org/html-introduction/?ref=lbp). (On the left-hand side of the page there is a menu bar with links to various topics.) 

* [HTML Graphics - SVG's](https://www.geeksforgeeks.org/html-svg-basics/?ref=lbp)

* [Advanced SVG's](https://learn-the-web.algonquindesign.ca/topics/advanced-svg/)

* [HTML Tags](https://www.geeksforgeeks.org/html-tags-complete-reference/?ref=lbp)

* [Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)

* [SVG](https://www.w3schools.com/graphics/svg_intro.asp)

## Data Citations 

* UFO sightings https://www.kaggle.com/datasets/NUFORC/ufo-sightings?resource=download 
* Google Web https://snap.stanford.edu/data/web-Google.html 
* Airports https://geo-massdot.opendata.arcgis.com/datasets/17eb7e286f4e4942aeef500f5ef6bfcd_0/explore?location=42.023945%2C-71.694162%2C8.00&showTable=true 
* Graphs https://www.nytimes.com/interactive/2021/06/29/upshot/portland-seattle-vancouver-weather.html 

## Submission

* Be sure to push all changes to your repo and follow all instructions above. 
* Submit your assignment on Gradescope  
