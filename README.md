# HTML Refactor For Accessibility

## Description 

This project was a refactor of existing HTML and CSS make it more accessible by means of adding semantic HTML elements and alt text for images. In addition to this, the overall code has been cleaned up and made to be more efficient, particularly in the CSS that previously had many redundant classes.

Please see a summary of changes below:

### HTML
* A title has been added that reads 'Horiseon Social Solution Services' rather than 'title'.

* Padding has been removed from the header.

* Previously in this code the sections were defined with non-semantic HTML elements, eg 'div class=header', rather than just using the 'header' tag. This has been fixed to use semantic HTML where possible.

* All images (except from the background image) now have alt-text describing them for accessibility purposes.

### CSS
* Many redundant classes have been removed and replaced with a single class applied too all necessary elements. For example, instead of having separate classes for 'search-engine-optimisation', 'online-reputation', and 'social-media-marketing', these are now all styled under the class 'key-features'

* Where possible, elements are now styled directly rather than having classes applied to them. For example the CSS now styles footer h2 rather than having a h2 with the class 'footer-heading'.

* The CSS rules have been reorganised. All HTML elements are styled first, before moving onto classes that are arranged in order of their appearance in HTML.


## Usage 

You can visit this site on GitHub pages at the following link:
https://callumquirky.github.io./html-refactor-for-accessibility/

Please feel free to view the GitHub repository here: 
https://github.com/callumquirky/html-refactor-for-accessibility

Here is a screenshot of the finished website:
![finished site screenshot](assets/images/finished-screenshot.png)
## License

This project used the MIT license.


---
