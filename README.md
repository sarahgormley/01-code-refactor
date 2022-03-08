# 01-code-refactor
01-Code-Refactor

For this homework assignment, I followed the acceptance criteria to make sure that the Horiseon webpage meets accessibility requirements and is optimised for search engines. 
To accomplish this, I ensured that the HTML used semantics, was in a logical structure, included alt tags for all images, had sequentially ordered heading attributes, and contained a descriptive title.

1. Adding semantic HTML elements. 
List of changes made: 
- Changed <div></div> on line 11 & 26 to <header> </header> as it contains the header text
- Changed <div></div> on line 13 & 25 to <nav></nav> as this contains the navigation links
- Then, changed CSS .header div to .header nav
- Then, changed CSS .header div ul to .header nav ul
- Then, changed CSS .header div ul li to .header nav ul li
- Changed <div></div> on line 28 & 50 to <main></main> because this is the main section of text on the webpage
- Changed <div></div> on line 29 & 35 to <section></section> because this is one of the main sections of the webpage
- Changed <div></div> on line 36 & 42 to <section></section> because this is one of the main sections of the webpage
- Changed <div></div> on line 43 & 49 to <section></section> because this is one of the main sections of the webpage
- Changed <div></div> on line 51 & 73 to <aside> </aside> as this panel displays on the side of the webpage
- Changed <div></div> on line 74 & 79 to <footer> </footer> as this information is inside the footer of the webpage

2. Changing elements into logical structure independent of styling and positioning
- Nil changes made at this time. HTML follows order that it presents on webpage

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
- 

5. Added descriptive title to webpage
- Changed <title> from 'website' to 'Horiseon: Marketing Agency' to further describe what the company does. 


Added '' around Calibri in .header nav to ensure that this font is recognised to be used if needed. 