
color
	Sets an element's text color
	hex (#111111)
	rgb (rgb(111, 111,111))
	hsl (hsl(11, 11%, 11%))
	rgba (255, 255, 255, 0.1-1.0)
	hsla (225, %, %, 0.1-1.0)

background
	linear-gradient(deg, rgb(), rgb())

background-image 
	Sets an element's background image.

background-color
	Sets an element's background color.
	hex (#111111)
	rgb (rgb(111, 111,111))
	hsl (hsl(11, 11%, 11%))

border-color
	Sets the color of the four borders.

border-style
	Specifies what kind of border to display.
	Options: dotted, dashed, solid, double, groove, ridge, inset, outset, none, hidden.

box-shadow
	Apply one or more shadows around an element.
	box-shadow: offsetX(px) offsetY(px) blurRadius spreadRadius color;
		offsetX positive value moves the shadow right, negative left.
		offsetY positive value moves the shadow down, negative up.

font-family
	Determines the font of an element.
	Ex. Times New Roman

font-size
	Sets the size of the font.
	Ex. 69px
	Ex. min(vw, em);

font-style
	Options: Normal, Italic, Oblique.

font-weight
	Affects the boldness of the text.
	Ex. "bold" or "100-900"

text-align
	Aligns text horizontally within an element.
	Ex. Center, left, right, justify

img
	Adjust the size of images without losing original proportions.
	Ex. width and height

padding
	Increases the space between the border of a box and the content.
	padding: top/bottom right/left;
	padding: top right/left bottom;
	padding: top right bottom left;

border
	Adds space between the margin and the padding.

border-left 
	shorthand for border-left-width, border-left-style, border-left-color.

border-radius
	Rounds the corners of an element.
	Defines the radius of the element's corners.

filter 
	Defines visual effects.
	Ex. Blur, saturation

transform
	Applies a 2D or 3D transformation to an element.
	Ex. Rotate, scale, move, skew

overflow
	Controls what happens to content that is too big to fit into an area.
	Ex. Visible, hidden, scroll, auto

margin
	Increases the space between the borders of a box and the borders of adjacent boxes.
	margin: top/bottom right/left;
	margin: top right/left bottom;
	margin: top right bottom left;

max-width
	Sets the maximum width of an element.

width
	Wide
	max(rem, vw);

height
	Tall

box-sizing
	Modify the box calculation.

display
	Controls how HTML elements appear on the webpage.
	Elements:
		block
			Elements will appear on the page stacked atop each other
		inline
			Elements appear in line with whatever elements they are placed beside.

justify-content
	Aligns items across the main axis (horizontal).

align-items
	Aligns items across the cross axis (vertical).

opacity
	How non-transparent something is.

aspect-ratio
	X / X;
