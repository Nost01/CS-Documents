HTML elements to which CSS rules apply

Universal Selector
	* indicates a universal selector, where it will apply to every element

Type Selector
	Selects all elements of the given element type (div, p, h1-h6 etc...)

Class Selector
	Selects all elements with the given class, by using a period followed by the class name.
	Can also apply multiple classes to a single element.
	
	.class-name {
	property: value;
	}

ID Selector
	Selects an element with the given ID by using a hashtag followed by the ID name.
	An element can only have one unique ID and cannot be repeated on a single page.
	
	#ID-name {
	property: value;
	}

Grouping Selector
	Can group various selectors together that share the same properties.
	
	.selector-one, .selector-two {
	same-property-one: value;
	same-property-two
	}

Chaining Selector
	Can specify elements with multiple classes.
	
	Ex. class="subsection header" and class="subsection preview"
	To specify the element with preview second class:
	
	.subsection.preview {
	property: value;
	}
	
	Similarly, class="subsection header" and class="subsection" id="preview"
	
	.subsecation#preview {
	property: value;
	}

Descendant Combinator
	Combine multiple selectors so that it will only cause elements that match the last selector to be selected if they have an ancestor that matches the previous selector.
	
	Ex. The CSS would only apply to elements with "contents" with its parent being "ancestor".
	<div class="ancestor">
		<div class="contents"
		</div>
	</div>
	<div class="contents"></d> (CSS will ignore this line, since it doesn't have an "ancestor")
	
	.ancestor .contents {
	property: value;
	}