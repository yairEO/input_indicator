input_indicator
===============
Indicates the current cursor position on an Input field and how much text is occupying it. Easy to implement in any website without modifying the DOM at all

## [demo page](http://yaireo.github.io/input_indicator)

 
*   No images, pure CSS rendering
*   No extra DOM needed
*   Supports text selection direction (which isn't so trivial to achieve).
*   Accurate & dynamic, which means you can add or remove text and it will adapt.
*   Will only show if text is being overflowed
*   Uses Event-Delegation so don't worry about performance if you have a million input fields or dynamically-created ones


## Usage:
    // initialize
    $('input:text').inputIndicator();

    // initialize with setting the 'background-position'
    $('input:text').inputIndicator({ bgPos:'31px' });

    // destroy
    $('input:text').inputIndicator('destroy');

include the CSS file and style the indicator as you wish.

Mind that if you're changing the font-size and height of the input field you would also probably need to play a bit with the 'background-position' in the plugin's settings. You can also be creative and play with the CSS settings to change the way the indicator looks. 
