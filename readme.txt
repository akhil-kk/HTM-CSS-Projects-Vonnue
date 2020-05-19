Video -1

1. HTML is a mark up language - note a pgming language
2. structure content using tags.
3. <a> </a>, <p> </p>
4. CSS - cascading style sheets - style web page
5. css- changes position, colors, effcets, font size.
6. install live server extension -- from extensions in vs code.

video -2 

1. <strong> </strong> -  tage makes bold text
2. <h1>....<h6> tags for heading
3. <p> for paragraph
4. <ul> stans for unordered list. inside <ul> start <li> tags.
5. <div> mark up different sections - no visula effect on html - used in css
6. <span>- behaves like aparagraph tag
7. <br> page break.
8. <img src="image name" alt="what is that pic">

video -3

1. HtML web forms- used to capture info - login forms, email, contact forms etc.
2. begins with <form> tag
3. <label> for adding label to input field
4. input types text, radio, email, number, password, text area.
5. id must be unique.
6. palce holders - text that we see inside input field.
7. submit - submit the form  - input type = submit.
8. required attribute - for mandatory inputs.

video - 4

1. css - a list of rule sets
2. slectors - div, li.
3. decalartion - set of property value pairs.
4. eg. li {
	   color: red;
	  }
5. styling inside html and keepin a seperate stylesheet
6. inline elemets - has css limitations, dont take space more that their content needs.
   eg. span, img, strong, em
7. Block level elements - takes whole width of page, p, div, h1, h2,h3, form
8. margin, padding-  spaceing properties
9. margin for inline elements - to sides only.
10. inline ---> block : display: inline-block.

video - 5

1. tag an individual element -  give a class- define class by .class {}
2. tag.class1.class2 {} - for taging common classes.
3. id - like classes.. used in JS 
4. begins with #
5. to cutoom an anchor tag - a[href="link"] { rules}
6. inheritance : inherited from parrent - can use "inherit" like margin: inherit (inherits margin from parrent)
 
video - 6

1. HTML - 5 semantic tags - makes code meaningful 
2. <main> for the content of web page
3. <section> - defines a certain section (blog, contact)
4. <article>- eg. blog post
5. <aside> content related to an article-placed aside
6. <header> -nav, title,<footer> -footer of website.

video -7 

1. chrome developer tools - debug website, inspect elements
2. inspect - elements - outline of document- edit attributes, delete attributes
3. can edit and test in chrome inspect.
4. sources tab - tree of files in the project
5. preview- the work on different devices using the phonebutton.

video - 8

positon and layout

1.  position - static, relative, absolute, fixed, sticky
2. static - default. can be used in resettingthe position.
3. Relative - shift the position relative to its original position.
4. fixed - An element with position fixed; is positioned relative to the viewport.
5. absolute - position absolutely relative to its closest parrent.
6. sticky -  mixture of static and sticky
7. 13:17 - font size in em
8. 17:02 - z-index
9. 22:05 - white space no wrap
10. 22:44 margin auto
11. 24: 33 sticky
12. 36:08 forms field modification.

video - 9

pseudo classes , pseudo elements

1. used to target difeerent states of an element in the code eg. hover, focus, first child
2. eg. nav li a:hover {}, 02:55 , img hover { postion: relative
					      top : 4px;}
3. focus----- 06:00,  :focus
4. valid , 07:45     eg. form input:valid { border }
5. first child --means fisrt li inside nav --09:00 eg: nav li:firstchild {attributes}
6. pseudo elemenst 12:07 eg: article p::first-line {}
7. article p::first-letter {}
8. p::selection { background-color:red}  14:30
9. p::after { content: '...'}  15:25

