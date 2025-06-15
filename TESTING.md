![fwl-black](https://github.com/user-attachments/assets/fccd189c-a850-4ee3-b6c5-9aa0acd4d987)


# Testing methods and results
## Table Of Contents

1. [Manual Testing](#manual-testing)
    - [User Stories](#user-stories)
    - [Links and Buttons](#links-and-buttons)
    - [Hover and Active State](#hover-and-active-state)
    - [Form Validation](#form-validation)
    - [Carousels and Dropdowns](#carousels-and-dropdowns)
    - [Responsiveness](#responsiveness)
2. [Lighthouse Performance Testing](#lighthouse-performance-testing)
3. [Validation Testing](#validation-testing)
4. [Broswer Compatibility Testing](#browser-compatibility-testing)


## Manual Testing
### User Stories
  
| **User Story**                | **Has the objective been met? (Y/N)**              | **How has the objective been met?** |
| --------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------- | ---------- |
| As a visitor, I want to browse available fitness programs that are free and easily accessible   | Y | The FWL website offers a range of fitness programs that are easily accessible to the user by the implementation of the Bootstrap Dropdown menu component. The programs are split into 3 training areas, each offering 4 different training programs to the user.  |
| As a visitor, I want to easily undestand what services and/or produducts are provided by FWL    |   Y  | The FWL home page presents the user with a clear and consice message about what services/products they offer, who their target audience is, and how they can help their tagert audience to get fitter, healther and more confident.   |
| As a user, I want to be able to book an online personal training session so that I can have some guidance along my fitness journy   |  Y   | The FWL website provides a contact form where the user can fill in their personal information and select the from the dropdown menu that they would like to book a personal training session |
| As a user, I want access to meal plans and nutritional advice so that I can support my fitness goals with proper diet |  Y   | The FWL website provides the user with free nutritional advice and juicing ideas, these cna be found of the *Nutrition page* . Meal planning is a service provided by FWL, who have a nutritionist who consults with the user to create a bespoke meal plan that is individual to the user. This service in included with online personal training which is a paid for service.  |
| As a visitor, I want to see how the trainers teach so that I can choose a trainer who matches my goals |  Y   | The FWL website provides a range in free online classes, these can be found on the *Classes page* . Classes are taught by the trainers giving the view (online user) some insigth as the how the trainer coaches and if theyd'e potentially be a great fit. |
|As a user, I want access to video demonstrations of exercises so that I can perform them correctly and avoid injury|  Y   | The FWL website provides a range in free online classes, these can be found on the *Classes page* . The classes are instructor led and offer style of teaching that focuses on good form and technique, this way the user remains well informed throuhout the class and is less likely to get injured. |
|As a user, I want to be able to register my details and have a member of FWL reach out to me to discuss their products and services in further detail | Y|    The FWL website has many clickable elements that drive the user to a contact form where they can fill in thier personla information and a personal message to the FWL team. The form is validated to elliminate errors and ensure the data is clean and valid before entering the database.  |
|As a user, I would like to find health and wellbeing events | Y|   The FWL website provides information on their upcoming events, this can be found on the home page. To make it easier for the user I have iserted an **Events** tab in thr navigation bar on the *home page* . This will take the user to the direct part of the page where the events information is located.    |
|As a user, I would like to have access to juicing ideas like ingredients lists | Y| The *Nutrition page* is where the user can gain access to  nutrtional content including a carousel of juices with their ingredients list. This format is super easy for the user and helps to maintain simplicity throughout the website.   |
|As a user, I would like to easily find and follow FWL on all of their social media platforms | Y|  Across every page of the FWL website is a footbar which contains x3 icons, each respsenting the soial media accounts owned by FWL, these are Facebook, Instgram and X. The user can click on any icon and will be taken to the FWL social page using an external method.    |


### Links and Buttons

Note: All pages include the following;
- Home (index.html)
- Classes (my-gym.html)
- Nutrition
- Contact (bookings.html)
- Confirmation
- 404 Error
  
| **Link/Btn Location**                                                                    | **Expected result**                                                                                                 | **Pass or Fail** |
| --------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------- | ---------- |
| Navigation links - All pages                                             |  Each link should take the user to a specific webpage                                                                                                                       | Pass  |
| Register buttons x6 - Home page  | Each register btn should take the user the bookings page where they will fill out a contact form                     | Pass  |
| Footer links - ALL pages                                                        | Each icon in the footer will link the user to a specific social media page depending on the icon clicked. The user should be taken to an external page so they don't lose their current page on the FWL website.                                                                                                                      | Pass |
| FWL Branding Logo - All pages        | The company logo is used to drive more users to the contact form so FWL can capture their data abd grow their database.                                 | Pass  |
|Contact form submit bottun - Contact page | This button should submit all of the data that has been inserted into the contact form|   Pass |
|Home button - 404Error page | This button should take the user back to the home page|   Pass   |
| Home button - Confirmation page| This button should take the user back to the home page| Pass     |




### Hover and Active State
| **Hover/Active Elements**                                                                    | **Expected result**                                                                                                 | **Pass or Fail** |
| --------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------- | ---------- |
| Navigation links - Hover                                             |  When a user hovers over a link in the navigation bar it should change colour from white to green (highlight-color) unless the link is in its acitve state, then the colour will be red (primary-color)                                                                                                                       | Pass  |
| Footer Icons - Hover  | When a user hovers over a social media icons in the footbar they should change colour from green to red                | Pass  |
| Navigation link - Active | When the user is on a web page the name of the oage will be coloured red to highlight its active state | Pass |
| Buttons - Hover        | When a user hovers over a button is changes colour from it's base colour (booking-button-color) to a lighter green (highlight-color) | Pass  |
| Carousel - Active   | For the carousel to work it must contain an image/video that has been assigned active, this willenable to user to swipe through the carousle content | Pass  |

### Form Validation
The Contact page provides a form which enables users to communicate their interests with FWL. The form is a Bootstrap component that I have slightly customermised to meet the requirements of the project. I have ensured that key input fields have a been set to required which means the user will be unable to submit the form without this infomration. Please see code example below;

<details>
    <summary>Required code example</summary>
    <img width="1179" alt="Screenshot 2025-06-15 at 12 14 45" src="https://github.com/user-attachments/assets/49858306-36be-4dbc-a130-17bdfd371ae1" />
</details>

The Phone and Email input fields are a little more restricted as they have specific requirements. The **phone input field** will only take a number value (0-9) and the **email input field** is even more restricted as it not only ensures that the user has entered an @ symbol, it also requires the input to be constructed in a certain way, prompting the user to enter more infomration after the @ sign.

<details>
    <summary>Email validation</summary>

   <img width="1280" alt="form-email1" src="https://github.com/user-attachments/assets/905b346f-4c2e-4c5c-8219-e0ea26a06280" />

<img width="1280" alt="form-email2" src="https://github.com/user-attachments/assets/dd69e986-fb7a-4964-a80d-867edacc4d18" />
</details>

<details>
    <summary>Form submitted</summary>
 <img width="1280" alt="form-confirmed" src="https://github.com/user-attachments/assets/af0c586d-1483-4c6a-88a0-60a7d97ff9aa" />
</details>


### Carousels and Dropdowns
- There are x2 carousels in the FWL website, one containing iframes to share fitness content and the other contains images and listed ingredients. Both carousels have been tested and are working as expected.
- There are x12 dropdown menus on the classes page, each dropdown should open up and present the user with a class fitness program for the user to follow. All dropdown elements have been tested and are working correctly.

### Responsiveness

Throughout the development of this project I have utilised the tools and features in Google Chrome Developer specifically when **responsiveness** has been the focus. I followed a "mobile first" apraoch whcih meant the devloper tool was perfect as it enabled me to view each page of the site from different screen dimentions. The main dimentions I gave attention to were Mobile, Tablet, Laptop and Desktop. Note: The following screen shots are different responses of the home page which are based off of the Google Chrome Deveoper tool.

<details>
<Summary>Mobile</summary>
<img width="1280" alt="Screenshot 2025-06-15 at 14 39 30" src="https://github.com/user-attachments/assets/57f6d807-809f-4d1f-8df7-9f75f6d2b7bf" />
<img width="1280" alt="Screenshot 2025-06-15 at 14 43 36" src="https://github.com/user-attachments/assets/5a6d843e-97d8-4234-aecf-9d0679770c59" /> 
</details>

<details>
<Summary>Tablet</summary>
<img width="1280" alt="Screenshot 2025-06-15 at 14 39 25" src="https://github.com/user-attachments/assets/9f8aea05-7595-424e-9f7e-2a776edb31d0" />
</details>

<details>
<Summary>Laptop</summary>
<img width="1280" alt="Screenshot 2025-06-15 at 14 39 20" src="https://github.com/user-attachments/assets/d85eff08-ad21-4842-8b8e-9d011fbfa9dd" />
</details>

I used my mobile device a lot during the deveopment of this project to check how the web pages looked after each commit (my handset Apple iPhone 14). Below are screen shots from mobile device;

<details>
<Summary>Home page</summary>
![mobile-home1](https://github.com/user-attachments/assets/a616d79c-382f-4baf-a3fd-cf40e1733047)
![mobile-home2](https://github.com/user-attachments/assets/ec6af7de-d9ac-4a1f-9da0-a88e77feb8dd)
![mobile-home3](https://github.com/user-attachments/assets/d129d6bd-3945-420b-83c4-c10a4dbace7e)
</details>

<details>
<Summary>Classes page</summary>
    ![mobile-classes1](https://github.com/user-attachments/assets/50ec13cb-a709-4a2c-8fb3-d4aafb47361f)
![mobile-classes2](https://github.com/user-attachments/assets/8f633306-9146-43fc-898e-457e6b97207c)
![mobile-classes3](https://github.com/user-attachments/assets/327d295a-8e0c-4ea1-b70b-9106cf8df905)
![mobile-classes4](https://github.com/user-attachments/assets/f8a2e7d5-2b5d-427c-88c9-7a1ecd9d5c88)

</details>

<details>
<Summary>Nutrition page</summary>
![mobile-nutrition1](https://github.com/user-attachments/assets/3ad4540c-e66f-40a3-bf63-a4051b024404)
   ![mobile-nutrition2](https://github.com/user-attachments/assets/b9574cdf-e5b2-496f-8c58-15a608e7c7b1)
     ![mobile-nutrition3](https://github.com/user-attachments/assets/666856a2-d7ae-4552-b122-210b7bd0e900)
</details>
<details>
<Summary>Contact page</summary>
![mobile-contact-form](https://github.com/user-attachments/assets/1f47f33a-8e36-4e66-adc0-9e8d74b891d2)

</details>
<details>
<Summary>Confirmation page</summary>
![mobile-confirmation](https://github.com/user-attachments/assets/25fa3038-a417-4d7b-91aa-93eb02c564b7)

</details>

## Lighthouse Performance Testing
I used Google Chrome deveopment tools to develop and test each page within the FWL project, this is due to is expansive features including the Lighthouse Performance tool.

<details>
<Summary>Home page</summary>
<details>
<Summary>Before</summary>

**Performance at 44%**  
   <img width="1280" alt="home-44percent" src="https://github.com/user-attachments/assets/5c2c7380-20bc-4307-9c5d-fa0de02795a7" />
**Performance at 62%**  
<img width="1280" alt="home-errors1" src="https://github.com/user-attachments/assets/fd3082ac-ee1f-46b3-8aac-77a4e9c25aa3" />

**Examples of some of the errors that needed fixing**
<img width="1280" alt="home-errors1" src="https://github.com/user-attachments/assets/ce6912f4-2532-4b4a-a379-15457b32855f" />

</details>
<details>
<Summary>After</summary>
The image below shows that the home page performance has increased to **94%** . This was made possible by working through each of the errors until they were resolved and passed the Lighthouse performance checks. 
    <br>
  <img width="1280" alt="home-94percent" src="https://github.com/user-attachments/assets/e3ece2dd-2b6d-45ce-8870-03b270dfcf92" />
</details>
</details>
<br>
I followed the same approach for the rest of the web pages until the performance was at an optimal level. Click on the links below to view the Lighthouse performance for each page.
<br>


<details>
<Summary>Classes page</summary>
<img width="1280" alt="classes-70percent" src="https://github.com/user-attachments/assets/af62ec4c-d9df-40a7-be2e-6d5b09094a9a" />
</details>

<details>
<Summary>Nutrition page</summary>
<img width="1186" alt="nutrition-79percent" src="https://github.com/user-attachments/assets/773ce84e-ff81-4bbc-a8b6-4f5bc647934a" />
</details>

<details>
<Summary>Contact page</summary>
<img width="1280" alt="contact-99percent" src="https://github.com/user-attachments/assets/79dfdbe7-1e30-4e62-97df-81ded5a85452" />
</details>

<details>
<Summary>Confirmation page</summary>
<img width="1119" alt="confirmation-98percent" src="https://github.com/user-attachments/assets/f1ab08e9-a5dc-492d-a881-af951dc3a48b" />
</details>

<details>
<Summary>404Error page</summary>
<img width="1132" alt="Screenshot 2025-06-13 at 14 31 30" src="https://github.com/user-attachments/assets/c1964287-68b6-42aa-9f16-e62217dbf356" />
</details>


## Validation Testing
### HTML Files
<details>
<Summary>Homepage</summary>
   <img width="1241" alt="home-valid" src="https://github.com/user-attachments/assets/22eb59a4-020a-41b9-9b04-4e5a7f57ba8f" /> 
</details>
<details>
<Summary>Classes</summary>
    <img width="1222" alt="classes-valid" src="https://github.com/user-attachments/assets/5ade1f04-f2c6-4ce2-8382-f7bbd428171e" />
</details>
<details>
<Summary>Nutrition page</summary>
<img width="1213" alt="nutrition-valid" src="https://github.com/user-attachments/assets/8044bf45-49a8-4dbd-8cbb-58f478985e7f" />

</details>
<details>
<Summary>Contact</summary>
    <img width="1233" alt="bookings-valid" src="https://github.com/user-attachments/assets/9a0d7e33-d4bb-4c8e-99a1-01b893acc3a3" />
</details>

<details>
<Summary>Confirmation</summary>
 
</details>

<details>
<Summary>404 Error</summary>
    <img width="1054" alt="Screenshot 2025-06-11 at 14 04 38" src="https://github.com/user-attachments/assets/bbe421c3-04e5-4b36-b518-f88b6f2dfed6" />
</details>


### CSS Files
<details>
<Summary>CSS Stylesheet</summary>
    
    <img width="1280" alt="css-valid" src="https://github.com/user-attachments/assets/b57a7946-218a-4e6b-a693-0da71aea27a3" />
</details>

## Browser Compatibility Testing
All links, carousels, dropdown menus and responsive settings have been tested, resulting in the FWL website being compatible across the following three browsers. 
  <details>
<Summary>Chrome Compatible</summary>
  <img width="1209" alt="Screenshot 2025-06-13 at 20 17 04" src="https://github.com/user-attachments/assets/e2d75fea-859d-44db-824e-255ddebac60e" />
</details>

<details>
<Summary>Safari Compatible</summary>
    <img width="1280" alt="safari-compatible" src="https://github.com/user-attachments/assets/533cae4e-2465-47ed-9bb8-cb7dece172fa" />
</details>

<details>
<Summary>Firefox Compatible</summary>
    <img width="1280" alt="Screenshot 2025-06-13 at 20 11 46" src="https://github.com/user-attachments/assets/0b3ca1d2-3560-49ca-a495-6c2644239cb6" />
</details>