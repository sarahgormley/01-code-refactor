# 01-code-refactor
01-Code-Refactor

For this homework assignment, I followed the acceptance criteria to make sure that the Horiseon webpage meets accessibility requirements and is optimised for search engines. 
To accomplish this, I ensured that the HTML used semantics, was in a logical structure, included alt tags for all images, had sequentially ordered heading attributes, and contained a descriptive title.

1. Adding semantic HTML elements. 
List of changes made: 
- Changed div & /div on line 11 & 26 to header & /header  as it contains the header text
- Changed div & /div on line 13 & 25 to nav & /nav as this contains the navigation links
- Then, changed CSS .header div to .header nav
- Then, changed CSS .header div ul to .header nav ul
- Then, changed CSS .header div ul li to .header nav ul li
- Changed div & /div on line 28 & 50 to main & /main because this is the main section of text on the webpage
- Changed div & /div on line 29 & 35 to section & /section because this is one of the main sections of the webpage
- Changed div & /div on line 36 & 42 to section & /section because this is one of the main sections of the webpage
- Changed div & /div on line 43 & 49 to section & /section because this is one of the main sections of the webpage
- Changed div & /div on line 51 & 73 to aside & /aside as this panel displays on the side of the webpage
- Changed div & /div on line 74 & 79 to footer & /footer as this information is inside the footer of the webpage

2. Changing elements into logical structure independent of styling and positioning
- Nil changes made at this time. HTML follows order that it presents on webpage.

3. Adding alt attributes to images and icons
- Added alt="Teamwork Horiseon Header image" on line 27 in class="hero". This was done because the .hero class in CSS contains an image. 
- Added alt="optimisation image" on line 30. This was done so there is an alt tag for the image in the 'Search Engine Optimisation' section for accessibility requirements. 
- Added alt="Reputation management graph" on line 37. This was done so there is an alt tag for the image in the 'Online Reputation Management' section for accessibility requirements. 
- Added alt="Social Media Marketing" on line 44. This was done so there is an alt tag for the image in the 'Social Media Marketing' section for accessibility requirements. 
- Added alt="Lead Generation Icon" on line 54. This was done so there is an alt tag for the image in the 'Lead Generation' aside section for accessibility requirements. 
- Added alt="Brand Awareness" on line 61. This was done so there is an alt tag for the image in the 'Brand Awareness' aside section for accessibility requirements. 
- Added alt="Cost Management" on line 68. This was done so there is an alt tag for the image in the 'Cost Management' aside section for accessibility requirements. 
- Added alt="love" on line 76. This was done so there is an alt tag for the heart icon in the 'Made with love by Horiseon' footer for accessibility requirements. 

4. Putting Heading attributes in sequential order
- Heading attributes are already in order.

5. Added descriptive title to webpage
- Changed title from 'website' to 'Horiseon: Marketing Agency' to further describe what the company does. 

6. Technical Acceptance
- Added id="search-engine-optimization" on line 29, so that clicking the 'Search Engine Optimisation' link in the nav bar will direct to the description in the Main Section.

7. CSS changes
- Changed class for Main Sections (Search Engine Optimisation, Online Reputation Management & Social Media Marketing) to .sectionclass. 
- Next, I combined .search-engine-optimisation, .online-reputation-management & .social-media-marketing into one class called .sectionclass. This is because all the CSS in these classes was identical. 
- Then, I combined search-engine-optimisation img, .online-reputation-management img & .social-media-marketing img into one class called .sectionclass img. This is because the CSS for the image classes were identical. 
- Lastly, I combined search-engine-optimisation h2, .online-reputation-management h2 & .social-media-marketing h2 into one class called .sectionclass h2. This is because the CSS for the heading classes were identical. 

- Changed class for Aside Section (Lead Generation, Brand Awareness & Cost Management) to .benefit. 
- Next, I combined .benefit-lead, .benefit-brand & .benefit-cost into one class called .benefit. This is because all the CSS in these classes was identical. 
- Then, I combined .benefit-lead img, .benefit-brand img & .benefit-cost img into one class called .benefit img. This is because all the CSS for the image classes were identical. 
- Lastly,  I combined .benefit-lead h3, .benefit-brand h3 & .benefit-cost h3 into one class called .benefit h3. This is because all the CSS in these heading classes was identical. 

- Added '' around Calibri in .header nav, .sectionclass, & .benefits to ensure that this font is recognised to be used if needed. 
- Rearranged order of CSS document so that the CSS code is in the same sequential order as the webpage. 
- Added CSS comments to each CSS rule