ANATOMY OF SVG:
1.) xmlns - stands for “XML NameSpace”. This specifies what dialect of XML you’re using. In our case, that dialect is the SVG language spec. Without it, some browsers will not render your image or will render it incorrectly.
2.) viewBox - defines the bounds of your SVG. When you have to define the positions of different points of the elements in your SVG, this is what that’s referencing. It also defines the aspect ratio and the origin of your SVG. So it’s doing quite a lot! Be sure to play around with different values in the example above to get a feel for how it affects the shapes.

What is an XML Attribute ? 
An XML attribute is a property that is used to define the properties of an XML element. It is a key-value pair that is used to define the properties of an XML element. The attribute value is always enclosed in quotes.

What are some situations where you wouldn't want to use SVG ? 
They are not the best ways to display images on the web, or using the contents of the image if your linking them in inline html

What is a CSS Preprocessor ?
Essentially the middle man from converting your css framework code to vanilla css code. The reason is because normally browsers cannot read the framework and only transcript vanilla css.

CSS ADVANCED SELECTORS:
Three different selectors:
1. > - child combinator, which specifies exactly which child element you want to change in your hmtl markup (main > div > div{}) --> this would grab the div with the class of "wrapper" that is a child of the main element.
2. + - adjacent sibling combinator, which specifies that the element that is directly after another element in the DOM tree. (div + p{}) --> this would grab the first p element that is immediately preceded by a div element.
3. ~ - general sibling combinator, which specifies that the element that is anywhere after another element in the DOM tree. (div ~ p{}) --> this would grab all p elements that are immediately preceded by a div element.

