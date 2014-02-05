# BadgeGrabber

##v0.1

A javascript function for finding assertions and handling them with a callback


###Dependencies
- jQuery


###Instructions

Include the [js/badgegrabber.js](js/badgegrabber.js) in your project. 

Call `BadgeGrabber.grab( $selector, attribute, callback, finishCallback );`

###Parameters

#####$selector 			

The jquery selector to find assertions 

#####assertionAttribute

The attribute name containing the assertion (e.g. data-url, href, rel)

#####callback

The function to call for every assertion collected

Returns:

- data - the badge assertion
- url - the assertion url
- $element - the original jquery Object the assertion was taken from

#####finishCallback

A function called when all assertions have been collected

###Examples

View [js/main.js](js/main.js) to view an implementation of the function

A working example of the code can be viewed here: [http://ht2dev.com/badgegrabber/](http://ht2dev.com/badgegrabber/)