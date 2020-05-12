<p align="center"><img src="assets/images/cflogosmall.jpg" /></p>

# Counterpoint Fitness | Private Personal Training Studio | Blackrock

## User-centric Frontend Development Milestone Project

<hr>

This is a single page website for a private personal training studio. The website is intended to help the business owner generate new business, inform potential clients of the services provided, provide directions to the studio and social media links. It should be noted that I am actually the owner of this business - it is a real and fully operational business.

The goals for the **business owner** are as follows:

- Generate new leads
- Show potential clients how this studio and service provided are different to the vast majority of gyms
- Establish a more professional online presence

The business owner has observed that there are three categories of visitor to the studio's existing website. This website is designed to serve all three visitor types with the use of only one page in an effort to reduce loading times, bounce rate and the effort required for each of the three types of visitor to acheive the goal of their visit.

The three types of **visitor** are as follows:

1. A person who is ready to trial/sign up to the service straight away
2. Someone who is possibly interested in personal training but needs further information before committing to anything
3. A person who is looking for information such as directions and contact details but isn't interested in personal training

Each type of visitor will have a slightly different user experience, and their profile and goals are detailed below.

<hr>

### Visitor type one

This site visitor likely has the following profile:

- They already understand the value of personal training
- They have already made the decision that personal training is for them
- They might have previous experience of personal training or gyms
- They are highly likely to become a paying client and know there will be a significant financial cost

This visitor/potential client's goals are as follows:

- They would like to quickly get in touch with a view to booking in a consultation as soon as possible
- Their decision is already made and they don't want to be jumping through hoops or filling out long forms - they're ready to go

### Visitor type two

This person is a few steps behind visitor type one in their journey:

- They don't fully understand what personal training is and how it can benefit them - they might also have a negative perception of personal trainers or even the whole fitness industry
- They would like to learn more about what personal training is and how Counterpoint Fitness is different
- They likely have minimal experience of gyms or fitness classes
- They are less likely to become a paying client and might not have any idea of typical personal training costs

Their goals are:

- Enquire via the contact form or phone number to get further information about how it can benefit them personally
- Compare the website of Counterpoint Fitness with its competitors before perhaps getting in touch

### Visitor type three

This person is very different to the first two types:

- They are not interested in becoming a client

Their goal is likely: 

- To sell a product or service

<hr>

## User experience

The site aims to give each of the three visitor profiles a smooth and fuss-free experience by using a simple and intuitive design.

Each of the five planes of UX was considered carefully.

### Strategy

The strategy of keeping the website as a single page was to help reduce loading times and bounce rate.

### Scope

The website exists to help potential clients learn about the studio, the service provided and get in contact quickly. 

### Structure

The structure is designed to prompt visitor types one and two to get in contact quickly. The two parts of the website that prompt this are the first two seen after scrolling down, to minimise the effort required to make contact.

### Skeleton

The skeleton of the site was sketched out using Balsamiq:

1. [Callout wireframe](https://github.com/allyporwal/uc-frontend-milestone/blob/master/wireframes/Callout.png?raw=true)
2. [Personal training wireframe](https://github.com/allyporwal/uc-frontend-milestone/blob/master/wireframes/PersonalTraining.png?raw=true)
3. [About wireframe](https://github.com/allyporwal/uc-frontend-milestone/blob/master/wireframes/About.png?raw=true)
4. [Gallery wireframe](https://github.com/allyporwal/uc-frontend-milestone/blob/master/wireframes/Gallery.png?raw=true)
5. [Contact wireframe](https://github.com/allyporwal/uc-frontend-milestone/blob/master/wireframes/Contact.png?raw=true)

### Surface

The colour scheme chosen matches the studio and branding. This is to ensure a consistent experience from the website to the first trip to the studio. Calls to action are highlighted by large buttons in a bright and contrasting colour.

<hr>

## Current features

1. Fixed navbar that collapses into hamburger button on smaller devices
2. "Callout" section with hero image and contact form that appears in a modal on tapping button
3. "Personal Training" section with information on services provided and a contact form
4. "About" section with a brief story on why the studio exists and a video embedded from Youtube - this section serves to put a human face to the business
5. "Gallery" section showing a few photos of the facilities
6. "Contact" section with a form aimed at visitor type three and an embedded Google Map to show location of studio
7. Footer section with a clickable logo that returns the user to the top, a phone number and address and social links

The callout, about and contact sections have fixed backgrounds showing images of the studio through a tinted overlay. This helps clearly mark each section of the website and also adds visual interest. On mobile devices the backgrounds scoll with the page; the intended parallax effect does not work so the background is not fixed.

## Future features

- In future a more interesting gallery design with more up to date photos and pictures of clients training will be added
- Background images are currently static on mobile devices; in the future the images will display in a static/parallax effect like the desktop site while scrolling (using CSS and Javascript)

<hr>

## Deployment

The project was deployed by:

1. Going to the [repository on Github](https://github.com/allyporwal/uc-frontend-milestone)
2. Clicking on the settings button at the top right
3. Scrolling down to the Github Pages section
4. Selecting "master branch" from the Source dropdown menu
5. The link to the site was be displayed once the page automatically refreshed
6. The site can be accessed on [Github Pages](https://allyporwal.github.io/uc-frontend-milestone/) and it will update automatically with every new commit to the master branch 

The repository can be cloned by:

1. Going to the [repository on Github](https://github.com/allyporwal/uc-frontend-milestone)
2. Clicking on the "Clone or download" button
3. Copying the link that is then displayed
4. In your IDE, ensure that you are in the directory that you would like the clone to appear in
5. Type "git clone" into the terminal and paste the link
6. Press enter and the repository will be cloned into your chosen directory

<hr>

## Technologies used 

- HTML and CSS 
- [Bootstrap 4](https://getbootstrap.com/) was used to create key elements of the site (jumbotron, navbar, animations and more) and to ensure a responsive layout
- [Font Awesome](https://www.fontawesome.com/) was used for the social link icons at the bottom of the site
- [Gitpod](https://www/gitpod.io/) was the IDE used for the project
- [Google Fonts](https://fonts.google.com) provided the fonts chosen for the project
- The video was embedded from [Youtube](https://www.youtube.com/)

<hr>

## Tests perfomed

The HTML and CSS was checked using [W3C Validation](https://validator.w3.org/). All code passed without errors.

All the navbar links and the collapsable navbar function as intended. Tapping on a link in the navbar makes the page jump instantly to the corresponding section. The user can return to the top of the page by clicking the logo in the footer. 

The modal in the callout section appears as intended and disappears on tapping the "x" button in the top right. 

Each form has correct inline validation. If a user tries to submit a form with an invalid email address the form will not submit and there must also be an entry into the "name" field.

The footer links open in a new browser tab and take the user to the correct web address.

The website has been tested on a variety of different devices.

1. iPhone XR
   - The website was tested on Safari and Chrome and perfomed as intended in both vertical and horizontal orientations

2. iPad Pro
   - The website was tested on Safari and performed as intended in both orientations

3. Acer Laptop with touchscreen
   - The website was tested on Firefox and Chrome and performed as intended in touchscreen mode (fixed background images) and, on attaching the detatchable keyboard/trackpad, also performed as expected (parallax effect started working without refreshing the page)

4. 21.5 inch iMac with 1080p display
   - The website performed as intended on Chrome and Safari

5. iPhone 5, 6/7/8, 6/7/8 plus, iPad, various android phones, laptops and a 4K monitor were all simulated in Chrome Developer Tools to check for responsiveness
   - All performed as intended

<hr>

## Credits

The CSS code to create the clickable logos with the animated change in colour was taken from a [Code Institute tutorial.](https://github.com/Code-Institute-Org/ucd-resume/blob/master/assets/css/style.css)

The CSS code to create the background, overlay and parallax effect on the backgrounds is a tweaked version of the code in this [Code Institute tutorial.](https://github.com/Code-Institute-Solutions/BootstrappingYourNextBigIdea-BS4/blob/master/04-BeyondBootstrap/01-updating_our_callout/css/style.css)

The code to ensure the full width Bootstrap buttons scale properly on different devices was based on the work of [Travis Horn.](https://travishorn.com/responsive-buttons-with-bootstrap-7c2a7c144308)

Thanks to my mentor, Brian Macharia, for his help in this module.