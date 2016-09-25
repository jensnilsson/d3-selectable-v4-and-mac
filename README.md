# d3-selectable-v4-and-mac

update of d3-selectable to work with v4 of d3.js also added functionality for using cmd on mac.

Original repo:
https://gist.github.com/jo/4068610
By: Johannes J. Schmidt, TF 

Provide selection capabilities for DOM elements, geared to `<select multiple>`.

* `click`: select element
* `ctrl + click`: add element to current selection
* `click + move`: select elements while dragging
* `ctrl + a`: select all elements within focused list
* `ctrl + shift + a`: deselect all elements within focused list
* `ctrl + click + move`: toggle selection while dragging
* `shift + click`: select range from nearest last selected element to clicked element
* `shift + ctrl + click`: add range to current selection
* `shift + click` between selected elements: select all between first and last selected element
* `home`: select first element
* `ctrl + home`: add first element to selection
* `end`: select last element
* `ctrl + end`: add last element to selection
* `up`: select element before first selected element
* `ctrl + up`: add element before first selected element to selection
* `down`: select element after last selected element
* `ctrl + down`: add element after last selected element to selection
