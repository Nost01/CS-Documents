Specificity Rules (Multiple Selectors)
	1. The more class selectors, the more specific, thus taking precedence.
	2. #id takes precedence over .class
	3. Isn't affected by whether it's a chaining selector or descendant combinator.
	4. Child element has higher precedence over Parent.

Rule Order
	1. If every other specificity factor is considered but there are still conflicts, the rule that was the last defined is applied.

