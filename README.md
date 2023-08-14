# CoderOnline
CoderOnline is an online programming school that highlights the benefits of pursuing education within its institution through its website. These advantages include a team of experienced instructors, constructive student feedback, and a curriculum that revolves around the most popular programming languages (as demonstrated by a table on the website). Furthermore, the website lists the courses that are offered, providing detailed descriptions for each course and offering individuals the opportunity to enroll.

![Responsive website on different devices](./README/images/responsive_web_img.png)

## Planning & Development
- __Target audience__
  - People who are beginning to study programming from scratch.
  - Individuals looking to deepen their knowledge.
  - Experienced developers who want to change their programming language.

- __Site Objectives__
  - The website should be convenient to navigate.
  - To higlight advantages of the school.
  - To offer statements from experienced instructors that demonstrate their expertise and passion for programming
  - To provide users with the ability to enroll to a course.

- __Wireframes__
  -[Wireframes PDF file](./README/wireframes/CoderOnline_Wireframes.pdf)

- __Fonts__
  - Open Sans
  - Raleway

- __Colors__
  - main color: #d6cccc
  - highlight color: #eded10
  - dark color: #000000;
  - light color: #ffffff;

- __Technologies__
  - HTML
  - CSS

## Features

### Navigation Menu

- The Navigation Menu comprises four pages: Home, Courses, Our Instructors, and Enroll.
- It's designed to be responsive, appearing differently on mobile devices.
- Depending on the selected page, the corresponding menu item is highlighted.

- __Mobile__
  - A burger menu is displayed on screens with a width of 1200px or less.
  - When the burger icon is clicked, an overlay, a cancel icon, and a navigation menu appear, while the burger icon itself disappears.
  - Both the burger and cancel icons are positioned at the top right corner of the screen, maintaining their location even when the screen is scrolled.
  - When the cancel icon is clicked, the navigation menu is closed, causing the cancel icon to disappear, and in its place, the burger menu icon reappears.
  - The navigation menu is situated at the bottom of the screen.
  - The navigation menu is organized in a column layout.

- __Desktop__
  - If the screen width exceeds 1200px, the navigation menu is shown instead of the burger menu.
  - The navigation menu is aligned in a row layout and is consistently positioned at the top of the screen.
  - When a navigation item is hovered over, the text changes its color and increases in size.

### Navigation Headings

Each section with substantial content begins with an interactive heading. Clicking on this heading will cause the page to scroll to its corresponding content.

![Example of Interactive Heading](./README/images/heading-1.png) ![Example of Interactive Heading](./README/images/heading-2.png)

### Why Choose Us Section
- The "Why Choose Us" Section highlights the benefits of studying at the school.
- Each point within this section is interactive. Clicking on a point reveals more detailed information.
- There is also an advertisement encouraging enrollment, accompanied by a link with a black background that directs users to the Enroll page.

![Why Choose Us section](./README/images/why-choose-us-sestion.png)

### Courses Page
- The "Courses Page" displays a list of courses along with their respective descriptions.
- To access the description of a course you're interested in, simply click on the respective course.
- The course whose description is currently open is highlighted.

![Courses Page](./README/images/courses-page.png)

### Enroll Page
- On the Enroll Page, there is a form present. This form cannot be submitted unless all required fields are completely filled out.
- Two buttons are provided: one for submitting the form and the other for resetting the form to its initial state.
- The required fields that must be completed include: Name, Surname, Email, Phone, Your reasons for learning programming, and Upload CV.
- For the "Upload CV", a file upload is necessary to submit the CV.
- Once submitted, the "Submit Page" opens, displaying a message confirming the successful submission of the form.

![Submit Page](./README/images/submit.png)

### 404 Page

If you enter an incorrect URL, the 404 Page will appear.

![Submit Page](./README/images/404.png)

### Footer
- In the footer, there are social icons (Facebook, Twitter, YouTube) as well as a phone icon.
- When a social icon is clicked, it opens in a new tab.
- Clicking on the phone icon triggers the application to initiate a call.

### Responsiveness
The website's appearance varies based on the screen size, leading to adjustments in font sizes, layout, and background images resolution to accommodate different devices

![Cards layout on different devices.](./README/images/responsive_web_cards_img.png)

## Content

### Home Page
- The 'Why Choose Us' section showcases a list of advantages associated with studying at the school, accompanied by descriptions that elaborate on each of these advantages.
- Table of Top Programming Languages According to PYPL and Stack Overflow for 2022.
- Cards containing students' feedback.

### Courses Page
- Courses' names
- Course Description

### Instructors Page
- Cards containing information about the school's instructors.

### Enroll Page
- Enrollment form.

### Submit Page
- Submit Page confirms successful form submission.

### 404 Page
- The 404 Page informs that an incorrect URL has been entered and provides a recommendation to verify the URL or use the Navigation menu.

## Testing 

### Validator Testing 
- __W3C HTML Validator__
  - All HTML files have been validated using the W3C HTML Validator, with no errors or warnings found.
  ![index.html validated](./README/images/html_validator.png)

- __W3C CSS Validator (Jigsaw)__
  - The CSS code has been validated using the W3C CSS Validator (Jigsaw), and no errors were found.
  ![style.css validated](./README/images/css_validator.png)

  - The only warning that was found pertains to the imported Google fonts, which are an external link and therefore cannot be validated.
  ![style.css google fonts link warning](./README/images/css_validator_warning.png)

### Lighthouse

Lighthouse reports flawless scores of 100% for SEO, Best Practices, and Accessibility. The only area of concern was Performance, with scores ranging from 80 to 90 due to varying internet speeds. To address this, optimizations were made to the background and avatar images. Additionally, by using an overlay, I could significantly reduce the quality of all background images without compromising the website's visual appearance. This led to an improvement in Performance, resulting in scores ranging from 90 to 99 for mobile and 98-100 for desktop.

- Lighthouse results for desktop
![Lighthouse report for desktop](./README/images/lighthouse_desktop.png)

- Lighthouse results for desktop (Perfect Score)
![Lighthouse report for desktop perfect Score](./README/images/lighthouse_desktop_persfect_score.png)

- Lighthouse results for mobile
![Lighthouse report for mobile (Perfomance 99)](./README/images/lighthouse_mobile.png)

### Unfixed Bugs
- Currently, there is no visible indication when a file is uploaded through the file input in the Enroll form. This problem can be resolved by employing JavaScript. Since I am exclusively using HTML and CSS for this project, I decided to leave this issue unresolved for now.

![Upload CV image](./README/images/file_input.png)

- The textarea on the Enroll page doesn't have any limitations on the amount of text you can input. This can be resolved with JavaScript as well.

## Deployment
- __The site has been deployed to GitHub Pages. The deployment process involves the following steps:__
    - Navigate to the Settings tab within this project's repository.
    - Select 'Pages' from the left-hand menu.
    - From the 'Source' section drop-down menu, choose the main branch.
    - After saving the main branch a link to the live project will be provided.

The link to the live project - https://oleksiyla.github.io/Project_1/

## Credits

### Content
- PYPL index provides ratings for the most popular programming languages (Aug 2023): https://pypl.github.io/PYPL.html
- TIOBE index provides ratings for the most popular programming languages (Aug 2023): https://www.tiobe.com/tiobe-index/
- The text content was composed with the assistance of ChatGPT: https://chat.openai.com
- The Raleway and Open Sans fonts were obtained from Google Fonts: https://fonts.google.com

### Media
- Background images and avatar images were sourced from Unsplash: https://unsplash.com
- All SVG icons, including the favicon, were sourced from FontAwesome: https://fontawesome.com