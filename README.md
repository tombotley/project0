# Project 0

Web Programming with Python and JavaScript

Project 0 Homepage

Screencast presentation: https://youtu.be/B5Ya17XSIlc


Objectives

•	Become more comfortable with HTML and CSS to design and style webpages.

•	Learn to use SCSS to write more complex stylesheets for your webpages.


Minimum requirements

•	At least four linked html pages.

•	At least one list, one table and one image.

•	At least one stylesheet with at least five CSS properties, five selectors, one #id selector, one .class selector and one @media query for smaller screens.

•	At least one Bootstrap 4 component and two Bootstrap columns with Bootstrap’s grid model.

•	At least one SCSS variable, one example of SCSS nesting and one use of SCSS inheritance.


What I have implemented

My homepage consists of four html pages. Each makes use of Bootstraps navbar component for the page header with links to each of the sites pages, my site brand logo and a collapsing menu for smaller screens.


Index.html

This is the front page of my website. In the body of the page, below the header there are three Bootstrap cards which describe the content of the website and serve as links to each page. 


About.html

This page contains a brief story of my life and makes use of the Bootstrap grid model to divide the text and images into two rows and two columns. Column reverse has been used for the second row so that with smaller screens the image in the first column is displayed at the bottom when the grid wraps into a single column. 


Nintendo.html

This page describes my passion for collecting Nintendo consoles and videogames. The content makes use of flex box to wrap the text and images into a single column for smaller screens. A table is used to display an ordered list of my favourite Super Mario games and a Bootstrap Carousel is included to show a selection of images of my collection.


Richmondpark.html

This page talks about one of my favourite places to visit, Richmond Park in London. It gives a short description of the parks history and features, there is a Bootstrap table with some of the species to be found in the park and then a gallery with some of my own photos captured during my many visits. The gallery is laid out using Bootstrap grid with a single row and five columns and styled with Bootstraps rounded image class.


Style.css/scss

CSS has been used to add styling to the page elements with multiple id and class selectors created, additional styling added to some of the Bootstrap classes used and pseudo-classes for mouse hover events. Sass has been used to compile the CSS file and includes variables for the sites theme colours, inheritance and nesting for the styling of lists within tables. The @media query is used to make changes to padding, margins and floating elements for screens with a maximum width of 768px in order to make content more compact for smaller devices. 
