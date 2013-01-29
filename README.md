input_indicator
===============
Indicates the current cursor position on an Input field and how much text is occupying it. Easy to implement in any website without modifying the DOM at all

**Usage:
    // initialize
    $('input:text').inputIndicator();

    // initialize with setting the 'background-position'
    $('input:text').inputIndicator({ bgPos:'31px' });

    // destroy
    $('input:text').inputIndicator('destroy');

include the CSS file and style the indicator as you wish.
