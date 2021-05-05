# Chpt 7

1. If you're using an input element in a form, what attribute controls the behavior of that input?  Action is required for each form element, and gives the URL for where the information will be received when submitted.  The Method attribute instructs which method to use: get or post. The get method adds the form values to the end of the URL while the post method (better) sends it hidden in the HTTP headers.

2. What element is used to create a dropdown list?  The select element is used to create a dropdown list.

3. If you're using an input element to send form data to a server, what should the type attribute be set to?  It varies by the specifics of the form action and information.  It might be "password" or "text" for example.

4. What element is used to group similar form items together? The fieldset element will group items together, usually surrounded by a border box.


# Chpt 13 and 15

1. Describe the differences between border, margin, and padding.  The border is around a box, outside of that is the margin, and inside of it is the padding.  So from outer to inner:  Margin, Border, Padding.

2. For a CSS rule padding: 1px 2px 5px 10px, what sides of the content box does each pixel value correspond to?  Top, right, bottom, left.  The measures start at the top and go clockwise.

3. Describe the difference between block-level and inline elements.  Inline elements are listed on one line, while block causes elements to form in a block (i.e. vertically instead of horizontal).

4. What is the role of fixed positioning, and why is z-index important in the scenario of using fixed positioning?  Fixed positioning places elements in relation to the window, rather than the containing element.  The z-index is important to give information about which element is on top when multiple elements overlap as can happen in fixed positioning.

5. What is the difference between a fixed and liquid layout? Fixed layout do not change size as the user increases or decreases the size of their browser window (and often given in pixel width).  Liquid layouts can stretch and contract as the the browser window size changes (and usually uses percentages).
