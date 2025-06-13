![fwl-black](https://github.com/user-attachments/assets/fccd189c-a850-4ee3-b6c5-9aa0acd4d987)


# Testing methods and results
## Table Of Contents

1. [Manual testing](#manual-testing)
    - [User Stories](#user-stories)
    - [Links & Buttons](#links-buttons)
    - [Hover & Active State](#animation)
    - [Carousels & Dropdowns](#features)
    - [Responsiveness](#responsiveness)
2. [Lighthouse testing](#lighthouse)
3. [Validation testing](#validation)
4. [Broswer Compatibility testing](#browser)


## Manual Testing
### User Stories
### Links & Buttons

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
| Register btns x6 - Home page  | Each register btn should take the user the bookings page where they will fill out a contact form                     | Pass  |
| Footer links - ALL pages                                                        | Each icon in the footer will link the user to a specific social media page depending on the icon clicked. The user should be taken to an external page so they don't lose their current page on the FWL website.                                                                                                                      | Pass |
| FWL Branding Logo - Home page        | The company logo is used to drive more users to the contact form so FWL can capture their data abd grow their database.                                 | Pass  |




### Hover & Active State
| **Hover/Active Elements**                                                                    | **Expected result**                                                                                                 | **Pass or Fail** |
| --------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------- | ---------- |
| Navigation links - Hover                                             |  When a user hovers over a link in the navigation bar it should change colour from white to green (highlight-color) unless the link is in its acitve state, then the colour will be red (primary-color)                                                                                                                       | Pass  |
| Footer Icons - Hover  | When a user hovers over a social media icons in the footbar they should change colour from green to red                | Pass  |
| Navigation link - Active | When the user is on a web page the name of the oage will be coloured red to highlight its active state | Pass |
| Buttons - Hover        | When a user hovers over a button is changes colour from it's base colour (booking-button-color) to a lighter green (highlight-color) | Pass  |
| Carousel - Active   | For the carousel to work it must contain an image/video that has been assigned active, this willenable to user to swipe through the carousle content | Pass  |

### Carousels & Dropdowns
- There are x2 carousels in the FWL website, one containing iframes to share fitness content and the other contains images and listed ingredients. Both carousels have been tested and are working as expected.
- There are x12 dropdown menus on the classes page, each dropdown should open up and present the user with a class fitness program for the user to follow. All dropdown elements have been tested and are working correctly.

### Responsiveness



## Lighthouse Performance
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
I followed the same approach for the rest of the web pages until the performance was at a optimal level.
<br>


<details>
<Summary>Classes page</summary>

</details>

<details>
<Summary>Nutrition page</summary>

</details>

<details>
<Summary>Contact page</summary>
<img width="1280" alt="contact-99percent" src="https://github.com/user-attachments/assets/79dfdbe7-1e30-4e62-97df-81ded5a85452" />
</details>

<details>
<Summary>Confirmation page</summary>

</details>
<details>
<Summary>404Error page</summary>

</details>



## Code Validation
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
<img width="1186" alt="nutrition-79percent" src="https://github.com/user-attachments/assets/773ce84e-ff81-4bbc-a8b6-4f5bc647934a" />
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






## Browser Compatibility
