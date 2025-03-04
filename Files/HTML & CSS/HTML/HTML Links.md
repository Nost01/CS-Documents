
Creating a link in HTML
	Anchor tags with an *href* attribute
	<a href="destination">Link Text Content</a>

Opening links in a new tab
	Add a *target* attribute and set it to "_blank"
	<a href="destination" target="_blank">Link Text Content</a>

Opening links with security measures
	Add a *rel* attribute with values:
	*noopener* which prevents the opened link from gaining access to the webpage itself
	*noreferrer* which prevents the opened link from knowing which webpage or resource has a link to it
	<a href="destination" rel="noopener noreferrer">Link Text Content</a>

Absolute Links
	Links to pages on other websites on the internet
	<a href="https://www.google.ca">Google</a>

Relative Links
	Links to other pages within the repository/website
	<a href="index.html">Home Page</a>
	Ex. If index is located in the "pages" directory
	<a href="./pages/index.html">Home Page</a>
		"./" specifies that it should start looking for the file/directory relative to the current directory