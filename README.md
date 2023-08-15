Hosted Link: 
# Youtube Clone

![image](https://github.com/kaverichougule/Youtube_Clone/assets/101037685/6b4ba13b-3849-4bdb-95d6-f8ba0b67689d)
![image](https://github.com/kaverichougule/Youtube_Clone/assets/101037685/ee0bd71f-e903-47db-9418-3126efe8c636)
![image](https://github.com/kaverichougule/Youtube_Clone/assets/101037685/189e3c9e-b498-4f84-8d75-8c12b7fcb35d)

HTML Code:
'header': Represents the header section. <br>
'h1': Displays the main heading of the page. <br>
'div class="gallery"': Contains the photo gallery. <br>
A series of 'img' elements: Each displays an image with a source URL and alternative text. <br><br>
CSS Code: <br>
*: Applies the box-sizing property to all elements.

body: Sets overall styling for the entire page.

margin: Removes default margin.
font-family: Sets the default font.
background: Sets the background color.
.header: Styles the header section.

text-align: Centers text horizontally.
text-transform: Makes the text uppercase.
padding: Adds spacing around the content.
background-color: Sets the background color.
color: Sets the text color.
border-bottom: Adds a colored border at the bottom.
.gallery: Styles the photo gallery container.

display: flex: Turns the container into a flex container.
flex-direction: row: Arranges items in a row.
flex-wrap: wrap: Allows items to wrap onto the next line.
justify-content: center: Centers items horizontally.
align-items: center: Centers items vertically.
gap: Sets the gap between items.
max-width: Limits the width of the container.
margin: Adds margin around the container.
padding: Adds spacing inside the container.
.gallery img: Styles the individual images.

width: Sets the width of the image.
max-width: Limits the maximum width of the image.
height: Sets the height of the image.
object-fit: Adjusts how the image fits within its container.
border-radius: Adds rounded corners to the image.
.gallery::after: Creates an invisible pseudo-element after the gallery.

content: Adds content to the pseudo-element.
width: Sets the width of the pseudo-element (creates a gap on the right).
