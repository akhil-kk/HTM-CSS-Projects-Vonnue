 	HTML

1. HTML (HyperText Markup Language) is the most basic building block of the Web. It defines the meaning and structure of web content.
2.  HTML tags
	<html>-Defines an HTML document.
	<head> -Contains metadata/information for the document.
	<body> -Defines the document's body.
	<h1>....to  <h6>- Defines HTML headings. h1 the largest to h6 the smallest
	<p> -Defines a paragraph tag.
	<br> -line break.
	<blockquote>- Defines a section that is quoted from another source.
	<a> -Defines a hyperlink. Used for inserting urls to other sites or same site
	<em>- Defines emphasized text. Usually in italics
	<strong> -Defines text in bold
	<form>- Defines an HTML form for user input.
	<label>- Defines a label for an element.
	<input> -Defines an input control.
	<select>- Defines a drop-down list.
	<button>- Defines a clickable button.
	<img> -Defines an image.
	<ul> -Defines an unordered list.
	<ol>-Defines an ordered list.

3. HTML semantic tags -Semantic HTML or semantic markup is HTML that introduces meaning to the web page rather than just presentation.
   HTML5 semantic tags define the purpose of the element
   semantic tags:
   
	<main> - For the main content of a web page
	<section> - Defines a certain section of a web page (eg. blog list, contact info)
	<article> - Defines a bit of the content which makes up an article(eg a blog post)
	<aside> - Defines some content related to something else (eg: similar blog posts)
	<header> - For the header of a website - contains the nav, title etc
	<footer> - For the footer of a website - contact information, copyright notice etc

 CSS

1. CSS position property
  
  	position: static;  (default) - Position in document flow

	position: relative; Position relative to default position via top, right, bottom, and left properties

	position: fixed; Position to a fixed location on the screen via top, right, bottom, and left properties 

	position: absolute; Position relative to ancestor absolute element via top, right, bottom, and left properties

	Fixed position (0,0) is top left corner.

2. Additional properties: 
 	
	background-image: image for element's background

	background-repeat: should background image be displayed in a repeating pattern.

	font, font-family, font-size, font-weight, font-style: font information for text

	text-align, vertical-align: Alignment: center, left, right cursor - Set the cursor when over element

3, visibility peoperties : 

	display:  none;   - Element is not displayed and takes no space in layout.
	 
	display: inline; - Element is treated as an inline element.
 
	display: block; - Element is treated as a block element.

	display: flex;  - Element is treated as a flex container. 

	display: grid;  - Element is treated as a grid container.

	visibility: hidden; - Element is hidden but space still allocated.

	visibility: visible; - Element is normally displayed

4. pseudo-classes: A CSS pseudo-class is a keyword added to selectors that specifies a special state of the element to be selected.
 	
	hover - Apply when mouse is over the element.
	Eg: p:hover, a:hover {  
		background-color: yellow; 
		} 

 CSS Flexbox

1. Flexbox is a new CSS display type that controls position, size and spacing of elements relative to their parrent elements and each other
2. Works great responsively
3. Apply a disply type of flex to the parrent container. Then the children elemets in that container directly becomes flex elements.
4. We can control how they shrink and grow.
5. sample parrent container    eg; .flex-container {
				       display: flex
						    }
6. Default behaviour of felx items : stack left to right
7. flex-grow is used to expand elements into available space and the rate at which it expands into that available space is governed by the number given. 
   It is all relative to the other container next to it
   
   eg: flex-grow: 1;

8. flex-shrink is the opposite of flex-grow. It determines the rate at which it shrinks as the browser gets smaller. 
   The bigger the shrink rate the more it shrinks
   
    eg: flex-shrink: 1;

9. flex-wrap prevents elements from going off page when a minimum width is specified

   eg: flex-wrap: wrap;

   There are "wrap-reverse", "no-wrap" values available for flex-wrap

10. Flex-basis - is similar to minimum width. 
    eg: flex-basis: 200px;

   if we apply minimum width to the boxes and shrink the window, scroll bar apperas after a point where minimum width of the screen is less than than applied min width.
   where as if we apply flex-basis the boxes will shrink as normal and no scroll bar will appear.

11. Flex-basis, flex-grow and flex-shrink can be combined to one property called flex.
    
    eg: flex 1 0 200px; first number denotes flex-grow, second denotes flex shrink, third denotes flex basis.

12. "justify-content: center"  (applied to container for aligning contents to center), flex-end, flex-start, space-between, space-arround  options are also available for alignment.

13. text-indent: -10000 shrink text off the screen.
14. flex-flow -- control the flow of all the flex elements in the container. can be don as column flow and row flow.
    eg: flex-flow: column;      // The main axis of flex flow is column wise.
        flex 1 0 200px; 	//here the flex basis 200px controls the height of the column.

15. justify content property is only applied to the main axis.
                                      
16 "align-items" is used to align the flex items in the cross axis flow.
    eg: align-items: center;
17. change the order of th elements in a flex box using order.
   eg.  .one{order: 0;}  // if we change the 0 to 1, this one goes to last.
	.two{order: 0;}
	.three{order: 0;}
 
