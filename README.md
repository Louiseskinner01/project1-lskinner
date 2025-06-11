 ![fwl-black](https://github.com/user-attachments/assets/10bc44ec-2069-42d8-a564-cf9a5752369a)
# FWL online fitness classes and nutritional advice
## About
FWL (Fitness with Louise) is a company offering free online fitness classes and nutritional advice through their website. Their target audience are those who want to improve their health and wellbeing and build their inner confidence. The FWL website offers a clean and simple astheitc, using the FWL company colours as a base for the deisgn theme. Visitors to the site can expect an great user experience as they can easily navigate their way through the website using internal and external links, buttons and social icons, enabling them to register their details for events, watch videos and read ingredients for healthy juices.

[View Live Site.](https://louiseskinner01.github.io/project1-lskinner/) Hosted on GitHub Pages.
## Key Features
- Home page: Presents the user with motivational and encouraging content, as well as a list of up coming events that the user can register for.
- Classes page: Presents the user with a carousel of fitness videos. The user can also choose from a range a fitness programs and utilise the tips and techniques listed.
- Contact page: Presents the user with a booking form that ensures the users input is validated before it can be submitted (ficticiusly), using the submit button.
- Nutrition page: Offers the user nutriional advice and a carousel of Juice ingredients.


## Table Of Contents

1. [Design & Planning](#design)
   - [User Stories](#user-stories)
   - [Wireframes](#wireframes)
   - [Colour Scheme](#colour-scheme)
   - [Typography](#typography)
2. [Features](#features)
   - [Navigation](#navigation)
   - [Footer](#footbar)
   - [Video Carousel](#carousel)
   - [Dropdown Menus](#dropdowns)
3. [Technologies Utilised](#technologies)
4. [Testing](#testing)
5. [Deployment](#deployment)
8. [Referencing & Credits](#referencing)

## Design
### User-stories
### Wireframes
<details>
 <summary>Home</summary>
 <img width="100%" alt="wireframe-index-lg" src="https://github.com/user-attachments/assets/ca60df66-2cc4-4aba-8c30-78f4323474a3" />

</details>
<details>
  <summary>Classes</summary>
  World!
</details>
<details>
  <summary>Nutrition</summary>
  World!
</details>
<details>
  <summary>Bookings</summary>
  World!
</details>
<details>
  <summary>404</summary>
  Error
</details>

### Colour-scheme
To make the brand stand out I used the branding colours as the base colour theme for the design, this was a simple red, black and white. To make the design pop I added two additonal greens and a pink that would be assigned to a specific typography.  

- **Primary colour – Red:** This acts as an active colour and also acts as a highlight colour for the footbar icons.
- **Secondary colour - Dusky Pink rgba(221, 137, 203, 0.681):** This is used on conjunction with the variable "Header font" (Pacifico). It is used to draw attention to things like events, online classes and juicing ingredients.
- **Highlight colour:** This has been applied to the navigation bar to highlight when the user is hovering over a tab. It has also been used as the base colour for the footerbar prior to them being hovered over.
- Booking-button colour: This colour has been applied to all buttons throughout the website.

- Navigation font: Base = White, Active = --primary-color (red), Highlight = --highlight-color (green).
<img width="100%" alt="colour-scheme" src="https://github.com/user-attachments/assets/be362d88-4f7f-4129-801a-e79afeef3a5a"/>

### Typography
For the development of this project I have chosen to utilise Google fonts as they provide font styles that meet the design requirements for accessibility and user-experience. I imported the following fonts into my css stylesheet, each font having a a back-up font incase the browser doesn't support the gogole font. 
- "Pacifico",  Cursive;
- "Monserrat", Sans-serif; 
- "Outift", Serif;

<img width="100%" alt="typography" src="https://github.com/user-attachments/assets/a9b32530-5b1f-4e8c-ad53-02d2a76296a6"/>

- **Monseratte:** Has been assigned as primary font which is the main font for the body.
- **Pacifico:** Has been used for special headings to draw attention to partocular peices of content.
- **Outfit:** Has been assigned as a secondary font for all other content.
## Features
### Navigation
The FWL website has a responsive navigation bar that utilises Boostrap 5 components. It has been customised to using the branding colours of FWL (which are Red, Black & White) to ensure the branding logo pops. The navbar has a simplistic approach, leaning into a clean and modernised look. The FWL company logo links to the bookings form where users can fill in their details and select from a list of reasons for contact. The booking form also features a text-box where the user can write additional information to be acompany the form.
Due to the naviation bar being deveoped using a "mobile first" approach, there is a toggle feature when the user is browsing from a mobile devise, this enables the user a better experience as the can easily naviagte through the tabs. The toggle feature can be identified by the "burger-icon" (another bootstrap component) used to enhance the users experience.
Another feature the navigation bar has is the data-bs-theme="dark" to enable a better user experience when browsing in nightmode. 
#### Other features
Features a hover effect where the nav link chnages colour from it's base white to a green (highlight color). If the nav link is in an "active" state then the link will remain red (primary colour) and the font weight will become bold.

<details>
 <summary>Navbar Mobile</summary>
 <img width="100%" alt="navbar-collaps" src="https://github.com/user-attachments/assets/699c6e68-50dd-4b5b-a76d-21e4e09bbe54" />
</details>
<details>
  <summary>Navbar Expand</summary>
<img width="100%" alt="navbar-expand" src="https://github.com/user-attachments/assets/fa56a72f-c265-49e4-be3a-c297fe2e236b"/>
</details>

### Footbar
The footbar is very clean and simple, containing only 1 heading and 3 icons. Each icon has been customised to be slightly larger than their original aspect and a different colour. They are coloured green (highlight colour) and when hovered upon they turn red (primary colour), this highlights the interactiveness the user experiences and brings life to the footbar bar.
 To enhance the users experience I have also applied the targe="_blank" attribute so when the user clicks on the icon they are taken to an external page and won't be lose their current page on the FWL website.
<details>
<Summary>Footbar</summary>
<img width="100%" alt="footer" src="https://github.com/user-attachments/assets/bbbe307f-4f04-4d1c-a6f5-4a4fe1f6ce80" />
</details>
<details>
<Summary>Footbar Hover</summary>
<img width="100%" alt="footbar-hover" src="https://github.com/user-attachments/assets/3cf6cd26-03b5-4396-a144-fa9de36c28bb" />
</details>

### Carousel
FWL wanted to provide free online classes for the website visitors to help promote health and wellbeing and grow a fitness community. To maintain a minimal look across the site I decided to implement a video carousel for website users to easily browse the online classes.
This appaoch is based on utilising iframe tags over video tags because it saves space in the developers assets folder and is faster to load in the browser.
<img width="100%" alt="carousel-1" src="https://github.com/user-attachments/assets/a018cc08-664e-445b-a09a-c90a9637ef25" />

<img width="100%" alt="carousel-2" src="https://github.com/user-attachments/assets/2d7a1591-ecdd-4ce8-9359-b7352f722686" />

### Dropdowns 
FWL provide free fitness programs and wanted this to be something that looked clean and was a simple procress for the web user. I decided to use a series of dropdown menus, setting the menu-item to an auto hight so content was presented nicely and didn't take up too much space.
The dropdown menus are segregated into 3 blocks, each reflecting a different type of training, these are;
- Strength
- Conditioning
- Stretch & Mobility

<img width="100%" alt="dropdown-new1" src="https://github.com/user-attachments/assets/6b3125bd-d18f-4479-8002-7918653d9ff4" />
<img width="100%" alt="dropdown-new2" src="https://github.com/user-attachments/assets/16949a5a-5e4c-4c4d-a73b-b712160808f2" />

## Testing
The FWL website has been put through a serious of vigourus testing methods to ensure that the site is responsive on mobile, tablet, laptop and desktop screens. Methods of testing include utilising the lighthouse feature on Chrome development tools, manual testing all links, buttons and dropdowns features, and validating html and css code through online validation tools. To see the testing process and results in more detail please click the link below.
 [TESTING.md](TESTING.md)

## Deployment
To deploy the FWL website I used the Github-pages feature, this generates a link that can be shared so people can view the website with only the use of only a device and an internet connection. To use github-pages I had to create a repository and connect it to my VS Code (IDE), this is the development environment where the webiste would be coded and any changes would be commited to the Github repository.
## Referencing

## Technologies
### Languages
- HTML
- CSS
### Frameworks
- **Bootstrap:** I utilised Bootstrap version so I could develop the FWL website to be responsive, accessible and inline with web developement trends. Boostrap offers a range of components to allow for a faster development and a modern result.

### Tools
#### Development Tools

- **GitHub:** I have used Github as it supports version control by tracking all changes made throughout the development of the project. Github provides many features that have helped with the development of the FWL website such as project board that can be utilised as a project management tool allowing developers to create milestones and label them with priority tags. It offers stages of deveopment such as to do, in progress and done (completed).
Github isn't just a configuration management tool it provides a special feature than allows deveopers to deploy their project so they are hosted live. This feature is perfect as developers can share their work with peers and future employers with just one simple link.
- **Visual Studio Code:** I downloaded and installed Visual Studio Code which is an IDE (Intergrated Deveopment Environment), this was for the purpose of coding my HTML and CSS docs. VS Code is very useful for deveopers as it connects directly to my Github repository making commits a simple process.
- **Chrome Developer Tools:** I utilised Chrome deveoper to design the FWL website using amobile first approach. The deveopment tool enabled me to view the web pages using different screen sizes which helped me to make a responsive website. I aso used the tool to inspect elements so I could see what elements were causing unwanted effects across the site.
#### Design & UI
- **Balsamiq Wireframes:** I used this online tool to create wireframes for each page oof the site. A wireframe has also been cteated for mobile, tablet and laptop screen sizes.
- **Google Fonts:** I have imported 3 different Google font styles into my CSS file to style the FWL website, helping to draw attention to specific content areas.
- **Font Awesome:** Provides scalable icons used for social media links and other design elements.
- **Favicon Generator:** I used this online tool to create an icon that can sit in the title tabe of the web pages.

#### Testing & Validation
**W3C Validator:** I used this online tool to validate my CSS and HTML code. It's a great tool as it higghlighted many issues I had in my code and I was able to make amendments to ensure all my code clean and valid. 
The screenshots below show some of the errors I had and confirm that the code is validated.

<details>
  <summary>Home</summary>
  <img width="1000" alt="home-valid" src="https://github.com/user-attachments/assets/70a3344d-e74a-429b-8ad8-e0abe5b53b4a" />
</details>
<details>
  <summary>Classes</summary>
 <img width="1000" alt="classes-valid" src="https://github.com/user-attachments/assets/bb2c63af-beeb-4ee8-9d77-143b14c6ef7d" />
</details>
<details>
  <summary>Nutrition</summary>
 <img width="1000" alt="nutrition-valid" src="https://github.com/user-attachments/assets/016af93d-0928-4baf-8dd7-cee604ce6d9b" />
</details>
<details>
  <summary>Bookings</summary>
<img width="1233" alt="bookings-valid" src="https://github.com/user-attachments/assets/ad301ac9-6f38-45fc-a8a7-6d7b02a6b4e1" />
</details>
<details>
<summary>404</summary>
<img width="1000" alt="Screenshot 2025-06-11 at 14 04 38" src="https://github.com/user-attachments/assets/582b4918-0586-439d-b32e-134751d02aaf" />
</details>




#### Other tools utlised

- **Notepad:** I utilised notepad to write my content and program ideas.
- **TinyPNG:** I utilised TinyPNG to make my image sizes smaller as they were too large and causing the FWL webpages to laod at a slow pace, this in turn was causing my Lighthouse testing result to be poor.
- **Favcon Converter:** I used an online converter to make the FWL company logo into a favcon so the logo would be visible in the browser tab.





