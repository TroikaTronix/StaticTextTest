# StaticTextTest
Demonstration of NSTextField spacing when setting the deployment target to macOS 10.13 or earlier.

This simple project illustrates an SDK introduced difference in the way that a non-editable NSTextField displays it's text depending on the deployment target.

If you build with the deployment target set to 10.14 or later, the text in the window fits perfectly within the 11 pixel high frame of the single NSTextField item.

But if you build with the deployment target set to 10.13 or earlier,  an extra 3 pixels of space are added above the text, causing it to be cut off within the 11 pixel high frame.
