![FWL company logo](documentation/fwl-black.png)


# Testing Methods & Results

## Manual Testing
### User Stories
  
| **User Story**                | **Has the objective been met? (Y/N)**              | **How has the objective been met?** |
| --------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------- | ---------- |
| As a visitor, I want to browse available fitness programs that are free and easily accessible   | Y | The FWL website offers a range of fitness programs that are easily accessible to the user by the implementation of the Bootstrap Dropdown menu component. The programs are split into 3 training areas, each offering 4 different training programs to the user.  |
| As a visitor, I want to easily understand what services and/or products are provided by FWL  |   Y  | The FWL home page presents the user with a clear and concise message about what services/products they offer, who their target audience is, and how they can help their target
t audience get fitter, healthier and more confident.   |
| As a user, I want to be able to book an online personal training session so that I can have some guidance along my fitness journey   |  Y   | The FWL website provides a contact form where the user can fill in their personal information and select the from the dropdown menu that they would like to book a personal training session |
| As a user, I want access to meal plans and nutritional advice so that I can support my fitness goals with proper diet |  Y   | The FWL website provides the user with free nutritional advice and juicing ideas, these cna be found of the *Nutrition page* . Meal planning is a service provided by FWL, who have a nutritionist who consults with the user to create a bespoke meal plan that is individual to the user. This service in included with online personal training which is a paid for service.  |
| As a visitor, I want to see how the trainers teach so that I can choose a trainer who matches my goals |  Y   | The FWL website provides a range in free online classes, these can be found on the *Classes page* . Classes are taught by the trainers giving the view (online user) some insight into how the trainers teach and if theyd'e potentially be a great fit. |
|As a user, I want access to video demonstrations of exercises so that I can perform them correctly and avoid injury|  Y   | The FWL website provides a range in free online classes, these can be found on the *Classes page* . The classes are instructor led and offer style of teaching that focuses on good form and technique, this way the user remains well informed throughout the class and is less likely to get injured. |
|As a user, I want to be able to register my details and have a member of FWL reach out to me to discuss their products and services in further detail | Y|    The FWL website has many clickable elements that drive the user to a contact form where they can fill in their personal information and a personal message to the FWL team. The form has required elements and uses form validation to elliminate errors and ensure the data is clean and valid before entering the database.  |
|As a user, I would like to find health and wellbeing events | Y|  The FWL website provides information on their upcoming events, this can be found on the home page. To make it easier for the user I have inserted an **Events** tab in thr navigation bar on the *home page* . This will take the user to the direct part of the page where the events information is located.    |
|As a user, I would like to have access to juicing ideas like ingredients lists | Y| The *Nutrition page* is where the user can gain access to  nutritional content including a carousel of juices with their ingredients list. This format is super easy for the user and helps to maintain simplicity throughout the website.   |
|As a user, I would like to easily find and follow FWL on all of their social media platforms | Y|  Across every page of the FWL website is a footer which contains x3 icons, each representing the social media handles owned by FWL (Facebook, Instagram and X). The user can click on any icon and will be taken to the FWL social page using an external method.    |


### Links & Buttons

Note: All pages include the following;
- Home (index.html)
- Classes (my-gym.html)
- Nutrition
- Contact (bookings.html)
- Confirmation
- 404 Error
  
| **Link/Btn Location**      | **Expected result**   | **Pass or Fail** |
| --------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------- | ---------- |
| Navigation links - All page |  Each link should take the user to a specific webpage      | Pass  |
| Register buttons x6 - Home page  | Each register btn should take the user the bookings page where they will fill out a contact form                     | Pass  |
| Footer links - ALL pages                                                        | Each icon in the footer will link the user to a specific social media page depending on the icon clicked. The user should be taken to an external page so they don't lose their current page on the FWL website.                                                                                                                      | Pass |
| FWL Branding Logo - All pages        | The company logo is used to drive more users to the contact form so FWL can capture the users personal data and grow contacts their database.                                 | Pass  |
|Contact form submit button - Contact page | This button should submit all of the data that has been inserted into the contact form|   Pass |
|Home button - 404Error page | This button should take the user back to the home page|   Pass   |
| Home button - Confirmation page| This button should take the user back to the home page| Pass     |


### Hover & Active State
| **Hover/Active Elements**                                                                    | **Expected result**                                                                                                 | **Pass or Fail** |
| --------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------- | ---------- |
| Navigation links - Hover                                             |  When a user hovers over a link in the navigation bar it should change colour from white to green (highlight-color) unless the link is in its active state, then the colour will be red (primary-color)                                                                                                                       | Pass  |
| Footer Icons - Hover  | When a user hovers over a social media icons in the footer they should change colour from green to red                | Pass  |
| Navigation link - Active | When the user is on a web page the name of the page will be coloured red to highlight its active state | Pass |
| Buttons - Hover        | When a user hovers over a button is changes colour from it's base colour (booking-button-color) to a lighter green (highlight-color) | Pass  |
| Carousel - Active   | For the carousel to work it must contain an image/video that has been assigned active, this will enable the user to click through the carousel content | Pass  |

### Form Validation
The Contact page provides a form which enables users to communicate their interests with FWL. The form is a Bootstrap component that I have slightly customised to meet the requirements of the project. I have ensured that key input fields have a been set to "required" which means the user will be unable to submit the form without this information. Please see code example below;

<details>
    <summary>The "required" attribute</summary>
 
  ![html code screenshot](documentation/testing/form-validation/form-validation.png)
</details>

The Phone and Email input fields are a little more restricted as they have specific requirements. The **phone input field** will only take a number datatype and the **email input field** is even more restricted as it not only ensures that the user has entered an @ symbol, but also requires the input to be constructed in a certain way, prompting the user to enter more infomration after the @ sign.

<details>
    <summary>Email validation</summary>

 ![email validatiton1](documentation/testing/form-validation/email-validation.png)

 ![email validatiton2](documentation/testing/form-validation/email-validation2.png)

</details>

<details>
    <summary>Form submitted</summary>

  ![form-submitted](documentation/testing/form-validation/form-submitted.png)

</details>



### Carousels & Dropdowns
- There are x2 carousels in the FWL website, one containing iframes to share fitness content and the other contains images and listed ingredients. Both carousels have been tested and are working as expected.
- There are x12 dropdown menus on the classes page, each dropdown should open up and present the user with a training program for the user to follow. All dropdown elements have been tested and are working correctly.

   **NUTRITION**
 ![carousel-classes](documentation/readme/features/feature-carousel2.png)

  **CLASSES**
 ![carousel-nutrition](documentation/readme/features/feature-carousel1.png)
 
### Responsiveness

Throughout the development of this project I have utilised the tools and features in Google Chrome Developer specifically when **responsiveness** has been the focus. For the development of this project I followed a "mobile first" approach, finding the Chrome developer tool very effective for responsive styling and trouble shooting. It enabled me to view each html page from different screen dimensions such as Mobile, Tablet, Laptop and Desktop. Note: The following screen shots are different responses of the home page which are based off of the Google Chrome developer tool.

#### Chrome Developer Responsive Designs
<details>
<Summary>Mobile-responsive Screenshots</summary>

  **NAVIGATION TOGGLE COLLAPSE**
  
  ![mobile-home1](documentation/testing/responsiveness/mobile/home-collapse.png)

  **NAVIGATION TOGGLE EXPAND**

  ![mobile-home2](documentation/testing/responsiveness/mobile/home-toggle.png)

   **CLASSES PAGE - DROPDOWN MENU**

  ![mobile-classes](documentation/testing/responsiveness/mobile/classes.png)

   **NUTRITION PAGE - TABLE**

  ![mobile-nutrition](documentation/testing/responsiveness/mobile/nutrition.png)
 
</details>

<details>
<Summary>Tablet</summary>

![footer](documentation/testing/responsiveness/tablet/footer.png)
  <br>

  ![classes page](documentation/testing/responsiveness/tablet/tablet-classes.png)
   <br>

  ![home page](documentation/testing/responsiveness/tablet/tablet-home.png)
   <br>

  ![nutrition page](documentation/testing/responsiveness/tablet/tablet-nutrition.png)
  
</details>

<details>
<Summary>Laptop</summary>
  
  **CLASSES**
  
  ![mobile-home1](documentation/testing/responsiveness/laptop/classes.png)
    **NUTRITION** 
  
   ![mobile-home1](documentation/testing/responsiveness/laptop/nutrition.png)
  
</details>

#### Mobile Device Screenshots
During the development of this project I used my mobile device to check frequently check the style and responsiveness of each web page. This enabled me to focus on a mobile first approach, the handset I used was an Apple iPhone 14. Below are screen shots from mobile device;

<details>
<Summary>Home page</summary>
  
  ![mobile-home1](documentation/testing/responsiveness/mobile-device/home1.png)

  ![mobile-home2](documentation/testing/responsiveness/mobile-device/home2.png) 

   ![mobile-home3](documentation/testing/responsiveness/mobile-device/home3.png)

</details>

<details>
<Summary>Classes page</summary>
  
  ![mobile-classes1](documentation/testing/responsiveness/mobile-device/classes1.png) 
    
  ![mobile-classes2](documentation/testing/responsiveness/mobile-device/classes1.png) 
    
  ![mobile-classes3](documentation/testing/responsiveness/mobile-device/classes3.png)

</details>

<details>
<Summary>Nutrition page</summary>
  
![mobile-nutrition1](documentation/testing/responsiveness/mobile-device/nutrition1.png) 
![mobile-nutrition2](documentation/testing/responsiveness/mobile-device/nutrition2.png) 
![mobile-nutrition3](documentation/testing/responsiveness/mobile-device/nutrition3.png)
     
</details>

<details>
<Summary>Contact page</summary>
  
  ![mobile-contact-form](documentation/testing/responsiveness/mobile-device/contact.png)

</details>
<details>
<Summary>Confirmation page</summary>
  
  ![mobile-confirmation](documentation/testing/responsiveness/mobile-device/confirmation.png)

</details>

--- 

## Lighthouse Performance Testing
I used the Google Chrome development tools to develop and test each page within the FWL project, this is due to is expansive features including the Lighthouse Performance tool.

  
<details>
<Summary>Initial lighthouse testing results on the Home page</summary>

**Performance at 44%**  
     ![Home page performance 44%](documentation/testing/lighthouse-performance/home-44percent.png)

**Performance at 62%**  
 ![Home page performance 62%](documentation/testing/lighthouse-performance/home-62percent.png)

</details>

<details open>
<Summary>Increased performance once the errors had been resolved</summary>
The image below shows that the home page performance has increased to 94%. This was made possible by working through each of the errors until they were resolved and passed the Lighthouse performance checks. 

  ![Home page performance 94%](documentation/testing/lighthouse-performance/home-94percent.png)

</details>

<br>
I followed the same approach for the rest of the web pages until the performance was at an optimal level. Click on the links below to view the Lighthouse performance for each page.
<br>

<details>
<Summary>Classes page</summary>
  
![Classes page](documentation/testing/lighthouse-performance/classes-85percent.png)

</details>

<details>
<Summary>Nutrition page</summary>
  
![Nutrition page](documentation/testing/lighthouse-performance/nutrition-97percent.png)

</details>

<details>
<Summary>Contact page</summary>

  ![Contact page](documentation/testing/lighthouse-performance/contact.png)

</details>

<details>
<Summary>Confirmation page</summary>

![Confirmation page](documentation/testing/lighthouse-performance/confirmation.png)

</details>

<details>
<Summary>404Error page</summary>
  
![404Error page](documentation/testing/lighthouse-performance/404.png)

</details>

---

## Validation Testing
### HTML Files
<details open>
<Summary>Homepage</summary>

   ![](documentation/readme/validations/home-validation.png)
</details>

<details>
<Summary>Classes</summary>

  ![](documentation/readme/validations/classes-validation.png)

</details>

<details>
<Summary>Nutrition page</summary>
   
  ![](documentation/readme/validations/nutrition-validation.png)

</details>
<details>
<Summary>Contact</summary>
      
  ![](documentation/readme/validations/bookings-validation.png)
</details>

<details>
<Summary>Confirmation</summary>
   
  ![](documentation/readme/validations/confirmation-validation.png)
</details>

<details>
<Summary>404 Error</summary>

  ![](documentation/readme/validations/404-validation.png)</details>


### CSS Files
<details open>
<Summary>CSS Stylesheet</summary>
      
  ![](documentation/readme/validations/css-validation.png)
</details>

---

## Browser Compatibility Testing
All links, carousels, dropdown menus and responsive settings have been tested, resulting in the FWL website being compatible across the following three browsers. 

  <details open>
<Summary>Chrome Compatible</summary>

  ![](documentation/testing/browser-compatibility/chrome.png)
     
  </details>

<details>
<Summary>Safari Compatible</summary>

  ![](documentation/testing/browser-compatibility/safari.png)
  
</details>

<details>
<Summary>Firefox Compatible</summary>

   ![](documentation/testing/browser-compatibility/firefox.png)
   </details>