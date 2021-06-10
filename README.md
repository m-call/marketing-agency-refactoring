# Marketing Agency Refactoring

Refactoring the existing code of a marketing agency's website to make it more accessible.


## Changes

- Added a descriptive title for the title element in index.html
- Added comments and spacing for code clarity in index.html and style.css
- Condensed benefit-lead, benefit-brand, benefit-cost classes into one class benefit-details in style.css
- Removed benefit-lead, benefit-brand, benefit-cost classes for h3 and changed it just h3 to affect all h3 element tags in style.css
- Removed benefit-lead, benefit-brand, benefit-cost classes for img and added the new benefit-details to the img element in style.css
- Added alt properties to all img elements for accessibility in index.html
- Added id identifier to the search-engine-optimization div tag so that the link will work when clicking it in the navbar in index.html
- Added semantic elements to increase efficiency and organization in index.html
- Deleted header and footer classes and changed them to element selectors for the header and footer in style.css
- Removed unneccessary div elements in index.html
- Condensed search-engine-optimization, online-reputation-management, social-media-marketing classes into one new class called marketing-features and used that class for the referenced elements h2 and img elements in style.css
- Added comments for clarification in index.html and style.css

## Functionality and Accessibility
- The website has a fully function navigation bar. If you click a navigation bar element you will be taken to the correlating section on the page.
- The images have alternative text for accessability in the case that an image does not properly load on the page.

## Screenshot
![ScreenShot](assets/images/01-html-css-git-homework-demo.png)