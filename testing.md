<h1 text-align="center">
    <a href="https://github.com/haselnuts/Hofra-Bed-Breakfast" target="_blank"><img src="assets/images/logo.png"></a>
</h1><a href="

<div text-align="center">
[View website in Github pages](https://github.com/haselnuts/Hofra-Bed-Breakfast)
</div>

## Testing
The developer used the below services to check the validity of the webside code
  - [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/#validate_by_input)
  - [W3C Markup Validation Servive](https://validator.w3.org/#validate_by_input)

### W3C validation
 1. stylesheet.css
    - Check that the stylesheet.css passes the W3C CSS validation without issues.
  
 2. index.html
    - Check that the index.html passes the W3C Markup validation without errors.
      1. Error: The element a must not appear as a descendant of the button element, line 135 to 137. *Button element was removed. Stylesheet.css was adjusted.*

 3. the-rooms.html
   - Check that the the-rooms.html passes the W3C Markup validation without errors.
      1. Error: The element a must not appear as a descendant of the button element, line 137 to 139.*

 4. the-barn.html
   - Check that the the-barn.html passes the W3C Markup validation without errors.
      1. Error: The element a must not appear as a descendant of the button element, line 175 to 177.*

 5. dellendistrict.html
   - Check that the dellendistrict.html passes the W3C Markup validation without errors.
      1. Error: The element a must not appear as a descendant of the button element, line 158 to 160.*

 6. contact.html
   - Check that the contact.html passes the W3C Markup validation without errors.
      1. Error: The element a must not appear as a descendant of the button element, line 140 to 142. *Button element was removed.
   

### Devices tested on
The following **devices** were used for testing
 - SAMSUNG S8+
 - iPhone 9
 - iPhone 11pro
 - iPad pro
 - HP laptop spectre

## Manual testing
Testing was performed during development of each page. As the project continued changes were
made and issue appeared during this process. 

### Welcome
  1. Logo 
   - **Logo** - Exists in the header and the footer of **every page** and allows the potential guest to easily navigate back 
     to the **Welcome** page.
     1. Click on the logo and verify that the link to the Welcome page works as expected
  
  2. Navigation Bar
   - Exists on **every page** and allows the potential guest to navigate thru the website's pages.
     1. Click on each navigation menu item and verify that it links to the correct page.
     2. During testing it was found that on the Contact page the navitation bar item The rooms was not translated into english. This was corrected.
     3. Hover over each navigation menu item and verify that the color changes as expected.
     4. Change the screen size from desktop to tablet to verify that the navigation bar is responsive and switches from in line menu to burger icon dropdown menu on the right side and 
     the appearing of the telephone number and e-mail adress.
     5. Click on the burger icon and check the dropdown menu is working as expected. 
     6. For tablets and smaller screen sizes: click on email adress/ telephone number and verify that the telephone app/ email app will open.

  3. Welcome/ Introduction
   - A warm welcome to Hofra Bed & Breakfast
     1. Reduce and expand width of window to confirm that the text in this section responds correctly and looks good on all device widths.

  4. Features
   - 3 **main features** with a link to each page 
     1. Click on the images for each feature and verify that the guest will be directed to the correct page. *When testing, the guest was not directed to the correct pages. The images were still linked to the swedish version. The href was corrected*
     2. Reduce and expand width of window to confirm that the features are responsive and change the position from side by side to underneath. *When testing, there were a overflow issue with the images. The column size was changed from col-sm-12 to col-sm-11.*  
     *There were a issue with the space between the features in the index.html, the-rooms.html and dellendistrict.html. The same space was not working for all pages. A new class name feature-space-index was added to seperate the html pages.*

  5. Guest reviews
     1. Reduce and expand width of window to confirm that the review section is responsive and changes the position from side by side to underneath.

  6. Back to top 
   - Will be appearing on the bottom of each page for smaller devices.
     1. Click on the arrow and verify that the guest will be directed to the top of the page. 

  6. Footer
   - The **footer** features an **address** linking to Google maps, **telephone number and e-mail** with a click to call function and 
   **social media icons** linking to Hofra B&B's 2 social media pages.
     1. Hover over the address, telephone number/ e-mail address and social icon and verify that the color changes as expected. 
     2. Click on the address and verify that the link to Google maps is working as expected.
     3. Click on email adress/ telephone number and verify that the telephone app/ email app will open.
     4. Click on each social icon and verify that the link to the Hofra B&B social side works as expected.


### The rooms
  1. Logo 
   - **Logo** - Exists in the header and the footer of **every page** and allows the potential guest to easily navigate back 
     to the **Welcome** page.
     1. Logo code is identical on all html pages. Testing already completed.
  
  2. Navigation Bar
   - Exists on **every page** and allows the potential guest to navigate thru the website's pages.
     1. Navbar code is identical on all html pages. Testing already completed.

  3. Introduction
   - A description of the B&B house and services
     1. Reduce and expand width of window to confirm that the text in this section responds correctly and looks good on all device widths.

  4. Features
   - The **3 rooms** featured with a picture and a short description
     1. Change the screen size from desktop to tablet and smaller screen sizes to verify that the features are responsive and description will be hidden and
     3 dots appear. 
     2. Click on the 3 dots and verify that room description re-appears and can be hidden again. *When testing, the room description for all 3 features appear and disapear at the same time.* 
     *Each feature got it's own ID for data-target, aria-controls and reference ID in the paragraph.*

  5. Call to action Button
   - Exist on **The rooms** and **The barn** pages and guides the potential guest to the **contact page**.
     1. Click on the button and verify that the link to the contact page works as expected. *When testing the button did not work as expected. The button linked to the swedish contact page, not the*
     *english contact page. The link was corrected.*

  5. Footer
   - The **footer** features an **address** linking to Google maps, **telephone number and e-mail** with a click to call function and 
   **social media icons** linking to Hofra B&B's 2 social media pages.
     1. Footer code is identical on all html pages. Testing already completed.


### The barn
  1. Logo 
   - **Logo** - Exists in the header and the footer of **every page** and allows the potential guest to easily navigate back 
     to the **Welcome** page.
     1. Logo code is identical on all html pages. Testing already completed.
  
  2. Navigation Bar
   - Exists on **every page** and allows the potential guest to navigate thru the website's pages.
     1. Navbar code is identical on all html pages. Testing already completed.

  3. Introduction
   - A description of the barn
     1. Reduce and expand width of window to confirm that the text in this section responds correctly and looks good on all device widths.

  4. The gallery
   - A gallery with images of the barn
     1. Reduce and expand width of window to confirm that the images in this section respond correctly and look good on all device widths.

  5. Packages
   - Description of the packages and prices
     1. Change the screen size from desktop to tablet and smaller screen sizes to verify that the packages are responsive and will change position form side by side to underneath.

  6. Call to action Button
   - Exist on **The rooms** and **The barn** pages and guides the potential guest to the **contact page**.
     1. Click on the button and verify that the link to the contact page works as expected. *When testing the button did not work as expected. The button linked to the swedish contact page, not the*
     *english contact page. The link was corrected.*

  7. Footer
   - The **footer** features an **address** linking to Google maps, **telephone number and e-mail** with a click to call function and 
   **social media icons** linking to Hofra B&B's 2 social media pages.
     1. Footer code is identical on all html pages. Testing already completed.   


### Dellendistrict
  1. Logo 
   - **Logo** - Exists in the header and the footer of **every page** and allows the potential guest to easily navigate back 
     to the **Welcome** page.
     1. Logo code is identical on all html pages. Testing already completed.
  
  2. Navigation Bar
   - Exists on **every page** and allows the potential guest to navigate thru the website's pages.
     1. Navbar code is identical on all html pages. Testing already completed.

  3. Introduction
   - A description of the dellendistrict
     1. Reduce and expand width of window to confirm that the text in this section responds correctly and looks good on all device widths.

  5. Features
   - Events, Hiking and Winter time
     1. Change the screen size from desktop to tablet and smaller screen sizes to verify that the features are responsive and description will be hidden and
     3 dots appear. 
     2. Click on the 3 dots and verify that room description re-appears and can be hidden again. *When testing, the room description for all 3 features appear and disapear at the same time. Each feature got it's own ID for data-target, aria-controls and reference ID in the paragraph.*
     3. Reduce and expand width of window to confirm that the features are responsive and change the position from side by side to underneath. *When testing, there were a overflow issue with the images. The column size was changed from col-sm-12 to col-sm-11.*

  6. Footer
   - The **footer** features an **address** linking to Google maps, **telephone number and e-mail** with a click to call function and 
   **social media icons** linking to Hofra B&B's 2 social media pages.
     1. Footer code is identical on all html pages. Testing already completed.


### Contact
  1. Logo 
   - **Logo** - Exists in the header and the footer of **every page** and allows the potential guest to easily navigate back 
     to the **Welcome** page.
     1. Logo code is identical on all html pages. Testing already completed.
  
  2. Navigation Bar
   - Exists on **every page** and allows the potential guest to navigate thru the website's pages.
     1. Navbar code is identical on all html pages. Testing already completed.

  3. Call us/ E-mail us
   - Shows telephone number and e-mail adress
     1. Click on email adress/ telephone number and verify that the telephone app/ email app will open.

  4. Visit us
   - Shows address
     2. Click on the address/ map and verify that the link to Google maps is working as expected.

  5. Write us
   - Features a contact form
     1. Reduce and expand width of window to confirm that the review section is responsive and changes the position from side by side to underneath.

  6. Footer
   - The **footer** features an **address** linking to Google maps, **telephone number and e-mail** with a click to call function and 
   **social media icons** linking to Hofra B&B's 2 social media pages.
     1. Hover over the address, telephone number/ e-mail address and social icon and verify that the color changes as expected. 
     2. Click on the address and verify that the link to Google maps is working as expected.
     3. Click on email adress/ telephone number and verify that the telephone app/ email app will open.
     4. Click on each social icon and verify that the link to the Hofra B&B social side works as expected.



