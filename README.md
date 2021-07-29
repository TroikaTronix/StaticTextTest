# StaticTextTest
Demonstration of NSTextField spacing issues for 10.14 vs. Earliser SDKs

This simple project illustrates an SDK introduced difference in the way that a non-editable NSTextField displays it's text.

If you build for the 10.14 SDK or later, the text in the window fits perfectly within the 11 pixel high frame of the single NSTextField item.

If you build for the 10.13 or earlier SDKs, an extra 3 pixels of space are added above the text, causing it to be cut off within the 11 pixel high frame.
