# Description

This is an assignment to build a responsive ecommerce web page. Nav and product container div will use flexbox. Sidebar/aside is a module that changes layout and location based on window size. Submitting the mailing list signup form results in user feedback on the page. Clicking a product's “add to cart” or “remove from cart” button updates cart count at top.

Students may use the provided mockups to guide their design to whatever extent they like. Matching the mockups is not required.

## Provided Materials

  - basic HTML and CSS
  - JSON list of products in script.js file
  - reset.css
  - images for all products
  - suggested design mockups

## Assignments

Lesson 03:

  - Make design decisions about how you'd like your site to look. You can use the provided mockups to guide your design to whatever extent you'd like- feel free to implement them exactly or make up your own design completely.
  - Code basic CSS for page. `reset.css` file should remain as it is. `main.css` file can be added to, changed, or completely redone.
  - `nav ul` and `.item-container` elements should be styled as flexbox containers. Implement a responsive grid system of your own design, or use a library, or don't use a grid at all. Be sure all important size values are proportional (em, rem, %).
  - We'll continue working on the CSS for this project throughout the course, in particular making it more responsive. The styling does not have to be perfect after this assignment. It's fine to change or add to the HTML as necessary for your styling.

Lesson 05:

  - Write a JS form handler function to be triggered on form submit. It should print to the console a friendly message that includes the value of the form element with name "email". Something like "Thanks for signing up for our mailing list, bobross@example.com!"

Lesson 06:

  - Serve appropriately sized images. Use GIMP or another photo-editing program to resize all images to more reasonable, consistent dimensions. This includes product images, the logo, and any background or other images you've included.

Lesson 07:

  - Write Javascript function that toggles the inclusion of a product in the "cart".
  - Add/edit HTML as necessary to trigger the function on click of a button for each product.

Lesson 08:

  - Write CSS that uses media queries to change layouts/style based on device size. There shoud be at least one obvious layout change in addition to elements fluidly changing width.
  - Finish styling the page.

Lesson 09:

  - Write Javascript that causes the total number of items in the cart to display next to the cart icon when that total changes.
  - Write Javascript that displays the friendly message on form submit in the page, not in the console.
  - Update the HTML and CSS as necessary to accomodate these changes.
  - Update the Testing section of this README with your own information.

*Extra Challenge*: Incorporate unit tests with [Qunit](https://qunitjs.com/).

*Extra Challenge*: Code a popup that toggles between hidden and displayed when user clicks on cart icon. It should show information about items in the cart (maybe list of their names, but up to you).

*Extra Challenge*: Serve appropriately sized images for user's device. Create multiple sizes of each image, and serve the appropriate one using the `srcset` and `sizes` attributes on the `img` tags. This will require naming all of the images consistently, e.g. "ombre-infinity400.jpg", "ombre-infinity200.jpg". [More](https://css-tricks.com/responsive-images-youre-just-changing-resolutions-use-srcset/) about [srcset](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/img)

*Extra Challenge*: Use browser storage to save details about a user's cart so when they revisit the page, it's in the same state as when they left it. [More about browser storage](https://www.w3schools.com/html/html5_webstorage.asp)

*Extra Challenge*: Dynamically generate the HTML for product listings from the JSON objects in script.js.

## Requirements

  - Site layout looks good on all sizes of devices. At a minimum, elements are proportionally styled and aside element changes location and layout at different screen sizes. This should be tested using a variety of devices and at least one online browser compatiblity testing tool.
  - Nav and product container elements are styled using flexbox.
  - Appropriately sized images are served.
  - User can add and remove items from their cart, which changes cart count number at top of page.
  - This README is updated to include information about the testing steps taken to ensure site quality.
  - Site is live on GH Pages hosting.

## Grading
Each weekly assignment will be graded independently. There will not be a final grade for the entire project.

## Testing
[update this section with information about the testing steps you took to ensure site quality]



  ---Research for user base for Ecommerce Project BELOW---
  
  
  ---WHO---                                            ---CHARACTERISTICS AND SCENARIOS---                          ---IMPACT---

  - Age and Age Groups                                  All ages.                                                    Low
  
  - Personal Life-style                                 Skiers (and the like), People who live in cold               Low
                                                        Regions.
                                                        
  - Gender                                              Both, in equal numbers                                       Low
  
  - Language                                            English first, Mongolian, Estonian, Finnish,                 Low
                                                        Swedish, and Russian. 
  
  - Education                                           Any or none                                                  Low
  
  - Learning Preference                                 N/A                                                          N/A
  
  - Work Attributes/Type Of Career                      Any                                                          Low
  
  - Expectations                                        Ease of use, simple transactions,                            High
                                                        and quality detailed description and pic                         
                                                      
  - Existing Knowledge                                  Personal taste mostly                                        Low
  
  - Web and Computer Exp.                               Low                                                          Low
  
  
  
  ---HOW---
  
  - What device                                         Desktop, tablet, mobile                                      High
  
  - Connection speed                                    Standard broadband                                           Med
  
  
  
  ---WHERE---                             
  
  - Users Location                                      Regional, possible worldwide                                 Med
  
  - Place where page is read                            Work, home, office, on the go                                Low
  
  
  
  ---WHY--- 
  
  - Why users seek the content                          Gifts, traveling, change of seasons                          High
  
  - Importance of content                               Clear descriptions, and high quality                         High
                                                        images.
                                                        
  - How they found page                                 Google, other search engines, ads, or                        Low
                                                        word of mouth.
                                                        
                                                      
  ---WHEN---                
  
  - When it's read                                      Work breaks, free time, home, waiting rooms,                 Low
                                                        Late nights when family is sleeping (for gifts)
  
                                               --------THIS ENDS USER RESEARCH---------
    
    
    
    
    
    -----BROWSER TEST RESULTS BELOW-----
    
    CHROME- Everything works and looks good, responsive. No errors.
    
  * FIREFOX-  Page looks good, responsive, mailing list submit has a reference error (EVENT IS NOT DEFINED).
    
    MICROSOFT EDGE- Everything works and looks good, responsive. No errors.
    
    INTERNET EXPLORER 11- Everything works, and looks good, responsive. No errors. 
    
    
    
    
    ----SPEED TESTS BELOW----
    Site tested on PINGDOM
    
    Test results from SAN JOSE, CA
    PERFORMANCE GRADE:  B (89)
    LOAD TIME: 1.30s
    FASTER THAN: 83% of tested sites
    PAGE SIZE: 897.7kb
    REQUEST: 19
    
    Test results from NEW YORK CITY, NY
    PERFOMANCE GRADE: B (89)
    LOAD TIME: 1.20 s
    FASTER THAN: 85% of tested sites
    PAGE SIZE: 794.5kb
    REQUEST: 19
    
    Test results from MELBOURNE, AU
    PERFORMANCE GRADE: B (89)
    LOAD TIME: 3.17s
    FASTER THAN: 50% of tested sites
    PAGE SIZE: 897.9kb
    REQUEST: 19
    
    *ALL AREAS TESTED FOR LEVERAGE BROWSER CACHING AND RECIEVED "F"
    
    PAGE SPEED INSIGHTS:
    (OPTIMIZATION SUGGESTIONS)
    ----DESKTOP----
    1. OPTIMIZE IMAGES
    2. ELIMINATE RENDER BLOCKING JS AND CSS IN ABOVE-THE-FOLD CONTENT
    3. LEVERAGE BROWSER CACHING
    4. MINIFY CSS
    5. MINIFY JS
    
    ----MOBILE---
    1. ELIMINATE RENDER BLOCKING JS AND CSS IN ABOVE-THE-FOLD CONTENT
    2. LEVERAGE BROWSER CACHING
    3. OPTIMIZE IMAGES
    
    
    
    
    ----RESPONSIVENESS TEST RESULTS BELOW----
    
    ----DEVICE/SCREEN SIZE----                               ----SUMMARY----
    
    24" DESKTOP/1920X1200                                    Looks good, font is a little too small
    20" DESKTOP/1600X900                                     Good to go
    10" DESKTOP/1024X600                                     Good to go
    
    APPLE IPAD MINI/768X1024                                 Looks good, buttons for add/remove too small
    NEXUS 9/ 1024X765                                        Good to go
    
    APPLE IPHONE3,4,4S/ 320X480                              ALL MOBILE, GOOD TO GO!
    SAMSUNG GALAXY S5, S6, S7/ 360X640
    GOOGLE PIXEL/ 411X731
    
    ---Tests were done using following websites:
    
    https://tools.pingdom.com/   PINGDOM
    
    http://responsivedesignchecker.com/   RESPONSIVE WEB DESIGN CHECKER
    
    BROWSER TESTING DONE ON ACTUAL BROWSERS ON LAPTOP, AND DESKTOP (BOTH WINDOWS OPERATING SYSTEMS)
    
    https://developers.google.com/speed/pagespeed/insights/   PAGE SPEED TOOLS
    
    
                                      ----END OF REPORT---- 
                                      
    
    