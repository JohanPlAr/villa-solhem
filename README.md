![Villa Solhem logo](documentation/villa-solhem-logo.png)

---

# _Villa Solhem_

The Villa Solhem website allows users to learn about the vacation house to rent "Villa Solhem" find information about the facilities, browse through images and make a booking reservation request. The visitors of the website could quickly contact the hosts and announce their interest.

The site can be accessed by this [link](https://johanplar.github.io/villa-solhem/)

![Responsive Mockup](documentation/responsive-mockup.png)

---

## User Stories

### First Time Visitor Goals:

- As a First Time Visitor, I want to easily understand the main purpose of the site, so I can learn more about the house to rent.
- As a First Time Visitor, I want to be able to easily navigate through the website, so I can find the content.
- As a First Time Visitor, I want to see inspiring vacation images.

### Returning Visitor Goals:

- As a Returning Visitor, I want to learn about house features, so I can see whether the property matches my vacation needs.
- As a Returning Visitor, I want to learn about things to do close to the rental house, so that I can start planning my vaction activities.
- As a Returning Visitor, I want to learn the best way to travel to the house.
- As a Returning Visitor, I want to find a way to get in contact with the hosts, so that I can ask additional questions or send a booking request.
- As a Returning Visitor, I want to find community links, so that I can learn more about the organization.

### Frequent Visitor Goals:

- As a Frequent User, I want to check whether there are any changes with house features and possible activities, so I can update my vacation plans.
- As a Frequent User, I want to have options to contact the hosts not only through booking requests, so I can get an answer to my email questions.

## Features

- ### Navbar

- ##### Navigation

  - Positioned at the top of the page.
  - Contains logo of the company on the left side.
  - Contains navigation links on the right side:
    - Home - leads to the home page where users can learn about Villa Solhem.
    - Gallery - leads to the gallery page where users can see inspirational vacation photos.
    - Book Here - leads to the booking request form page where users can fill out the form in order to send a booking reservation request.
  - The links have animated hover effect.
  - The navigation is clear and easy to understand for the user.
    ![NavBar desktop](documentation/navbar-desktop.png)

  - The navigation bar is responsive:

    - On tablets and mobile devices: the logo size is still to the left but smaller and a hamburger menu is implemented on the right side of the navigation bar.

      - navigation bar filled with the logo to the left and a hamburger menu implemented on the right side of the navigation bar.  
        ![NavBar Mobile Closed](documentation/navbar-tablet-mobile-closed.png)

      - When the hamburger menu is clicked, there is dropdown menu with the links in the same order aligned to the right.
        ![NavBar Mobile Open](documentation/navbar-tablet-mobile-open.png)

---

- ### Home Page

  - Represent:

    - the main idea of the vacation house to rent.
    - Emphasize the strong points of the house.
    - Invites to fill out the booking form.

  ![Home Page](documentation/home-page.png)

---

- #### Hero Section

  - Hero section have a fixed background image.

  - Hero section have a info card placed near the right bottom corner:

    - Motivational text to chose the house the rent.
    - Short description of the area features.
    - Short description of the web page features.

  ![Hero Section](documentation/hero-section.png)

---

- #### Vacation Details

  - Vacation Details Section has 2 cards with descriptive characteristics of the house and a button to link to booking page.

  - The Book Now button is animated uppon hovering.

  - Tells website visitors about house features and distance to nearby activities.

  - Icons from Fontawesome added to each feature to add readability and attractivity.

  - Attracts viewers to do a booking reservation.

  ![Vacation Details Section](documentation/main-vacation-details.png)

  ***

- #### Map Section

  - The Map Section has an iframe containing a map over Gotland.

  - The map shows a starting and an end point showing the way from the ferry to the vacation house.

  - The map shows the distance between the start and the end point.

​![Map Section](documentation/main-map.png)

---

- #### Footer

  - Footer contains email and social media links that open in a new tab.

  ![Footer](documentation/footer.png)

---

- ### Gallery Page

  - Gallery page contains a mosaic of images that aims to inspire a visit.

  - It has a hover function that scales up the image hovered so that the user gets a better look at the images of interest.

  - The photos represent possible vacation experiences at Gotland.

    - The gallery is responsive: the size of the photo depends on the user's screen.

  - It has a footer and nav identical to the home page's.

​![Gallery page](documentation/gallery-page.png)

---

- ### Booking page

  - Booking page has a booking request form:

    - All text input fields are customized.

      - All inputs are set to be required to fill out.
      - It has a reset form button to helps users who want to start over.

    - The form has all the neccessary details for an intitial booking request.

      - The submit and the reset button is animated on hover.

    - The page is responsive on all common screen sizes.

    - The submit button leads to the thank you page.

    - It has a footer and nav identical to the home page's.

  ​
  ![Booking page](documentation/booking-page.png)

---

- ### Thank You page

  - The Thank You Response page appears after submitting the booking form.
  - It contains the thank you message and the promise to get in touch with the applicant.
  - It will automatically direct the user to the main page in 15 seconds.

  - It has a footer and nav identical to the home page's.

  ![Thank You page](documentation/thank-you-page.png)

---

## Technologies Used

- [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML) was used as the foundation of the site.
- [CSS](https://developer.mozilla.org/en-US/docs/Web/css) - was used to add the styles and layout of the site.
- [CSS Flexbox](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_flexible_box_layout) - was used to arrange items simmetrically on the pages.
- [CSS Grid](https://developer.mozilla.org/en-US/docs/Web/CSS/grid) - was used to make "gallery" page responsive.
- [CSS roots](https://developer.mozilla.org/en-US/docs/Web/CSS/:root) was used to declaring global CSS variables and apply them throughout the project.
- [Balsamiq](https://balsamiq.com/) was used to make wireframes for the website.
- [Codeanywhere](https://app.codeanywhere.com/) was used as the main tool to write and edit code.
- [Git](https://git-scm.com/) was used for the version control of the website.
- [GitHub](https://github.com/) was used to host the code of the website.
- [GIMP](https://www.gimp.org/) was used to make and resize images for the README file.

---

## Design

### Color Scheme

![Color pallet](documentation/color-pallet.png)

- Blue color was used as the main color of the website to represent the evening the ocean.

- Light Blue Color was used as a contrast to the darker blue to resemble clear blue mid day sky.

- Sandybrown is used as a contrast color and was picked from the setting sun present in the hero-image and used as font-color.

- Limestone white was picked to represent the limestone house colors of Villa Solhem also present at the many Gotland beaches.

### Typography

![Main Font](documentation/primary-font.png)

- Zen Kaku Gothic Antique was used as the main font and Logo text of the website in order to increase readability.

![Accent Font](documentation/accent-font.png)

- IBM Plex Serif was used to contrast headlines on cards from the main font to accentuate info cards.

### Wireframes

#### Mobile devices

- [Home Page. Mobile Screen](documentation/mobile-home-page.png)
- [Gallery Page. Mobile Screen](documentation/mobile-gallery-page.png)
- [Booking Page. Mobile Screen](documentation/mobile-booking-page.png)
- [Thank You Page. Mobile Screen](documentation/mobile-thank-you-page.png)

#### Tablets

- [Home Page. Tablet Screen](documentation/tablet_home_page.png)
- [Gallery Page. Tablet Screen](documentation/tablet-gallery-page.png)
- [Booking Page. Tablet Screen](documentation/tablet-booking-page.png)
- [Thank You Page. Tablet Screen](documentation/tablet-thank-you-page.png)

#### Desktop

- [Home Page. Desktop Screen](documentation/desktop-home-page.png)
- [Gallery Page. Desktop Screen](documentation/desktop-gallery-page.png)
- [Booking Page. Desktop Screen](documentation/desktop-booking-page.png)
- [Thank You Page. Desktop Screen](documentation/desktop-thank-you-page.png)

---

## Testing

In order to confirm the correct functionality, responsiveness, and appearance:

- The website was tested on the following browsers: Chrome, Firefox, Edge.

  - Chrome:

  ![Chrome](documentation/browsers-chrome.gif)

  - FireFox:

  ![FireFox](documentation/browsers-firefox.gif)

  - Edge:

  ![Edge](documentation/browsers-edge.gif)

- The website was checked by devtools implemented in Edge and Chrome browsers.

  - Main Page:

  ![Main Page](documentation/responsiveness-main-page.gif)

  - Gallery Page:

  ![Gallery Page](documentation/responsiveness-gallery-page.gif)

  - Booking Page:

  ![Booking Page](documentation/responsiveness-booking-page.gif)

  - Thank You Page:

  ![Thank You Page](documentation/responsiveness-thank-you-page.gif)
