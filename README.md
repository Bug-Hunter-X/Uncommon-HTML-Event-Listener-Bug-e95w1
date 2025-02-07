# Uncommon HTML Event Listener Bug

This repository demonstrates a subtle bug related to adding event listeners in HTML.  The `bug.html` file shows the incorrect implementation where multiple event listeners are attached to the same element using different methods. The correct implementation is shown in `bugSolution.html`.

The bug is particularly hard to catch because the syntax of both event listener methods is valid; however, their combination can lead to unexpected behavior. One event listener might override the other, causing one of them to fail.