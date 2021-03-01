# moreCSSPractice

https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps

CSS is a stylesheet language, not a programing language and not a markup language.

p {
color: red;
}

The entire bit of code is a ruleset or rule. 'p' is the selector. Everything inside the curly brackets is the declaration. 'Color' is the property. 'Red' is the property value.

Most common types of selectors:

- Element selectors eg <div>
- id selectors eg #myImg01
- class selectors eg ".img-class"
- attribute selectors eg img[src] (excludes <img> w/o src)
- pseudo-class selectors eg a:hover - a specified element but css only applied when the element is in a specific state

"CSS layout is mostly based on the box model. Each box taking up space on your page has properties like:

- padding, the space around the content. In the example below, it is the space around the paragraph text.
- border, the solid line that is just outside the padding.
- margin, the space around the outside of the border." -https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/CSS_basics
