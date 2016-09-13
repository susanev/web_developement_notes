# CSS Notes

## Selectors
* a.className: selects all a elements with a class of className
* * selects everything, p* will select every element inside of p
* a+b: selects all b elements that direclty follow a elements
* a~b: selects all b elements that follow a elements (does not have to be directly)
* a>b: selects all b elemetns that are direct children of a
* :first-child: selects all first child elements (:last-child too)
* p:first-child: selects all first child p elements (:last-child too)
* a:only-child: selects all a elements that are the only child of some element
* :nth-child(n): selects all elements that are the nth child (:nth-last-child(n) too)
* a:first-of-type: selects the first a element in any element (:last-of-type too)
* a:nth-of-type(n): selects the neth instance of a (also an+b)
* a b:only-of-type: selects b elements inside of a if its the only b
* a:empty selects all empty a elements
* :not(X): negation of whatever X selects
* Source: [CSS Diner](http://flukeout.github.io/)

## Specificity
* the more specific a selector, the more preference it is given when it comes to conflicting styles
* ID selectors have a value of 100, class selectors a value of 10 and HTML selectors a value of 1
* [Specifitcity Calculator](https://specificity.keegan.st/)
* Source: [HTML Dog: Specificity](http://www.htmldog.com/guides/css/intermediate/specificity/)
