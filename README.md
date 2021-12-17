# _Anaconda_ Martial Arts Academy

_Anaconda_ Martial Arts Academy is a local school of martial arts located in Dublin 15, that teaches a combination of disciplines necessary to become a Mixed Martial Artist.
The goal of the academy however is not to train competition ready athletes but to help their members to get active and fit and receive all benefits of martial arts training, including building self-esteem and confidence.
The classes tought in the academy are: Brazilian Jiu-Jitsu, Kickboxing and Boxing and also Mixed Martial Arts for the more advanced students.
Members can practice one chosen discipline or get involved with the whole MMA suite of disciplines.
The school accepts new members across all ages (in BJJ classes, kids can start as early as the age of 4) and various skill levels from Beginners to Advanced.
As 'Anaconda' academy is growing in members, they would like to automatise the process of signing up for memberships to and they would like to add a small e-commerce on their website to sell their branded merchandise.

<img src="images_readme/ms1-readme-overview.png" alt="Anaconda MAA website overview">

# Link to live project - [CLICK HERE](https://anacondamaa2.herokuapp.com/)

---

#### Contents
1. [UX](#ux)
	- [Strategy](#strategy)
		- [User Goals](#user-goals)
		- [Stakeholder Goals](#stakeholder-goals)
		- [User Stories](#user-stories)
	- [Scope](#scope)
		- [Features included](#features-included)
	- [Structure](#structure)
	- [Skeleton](#skeleton)
	- [Surface](#surface)
2. [Features](#features)
	- [Navigation Bar](#navigation-bar)
	- [Footer](#footer)
	- ['Join Academy' call to action button](#'join-academy'-call-to-action-button)
	- [Home Page](#home-page)
	- [About Page](#about-page)
	- [Classes Page](#classes-page)
	- [Times & Prices Page](#times-and-prices-page)
	- [Coaches Page](#coaches-page)
	- [Contact Page](#contact-page)
	- [Contact Form](#contact-form)
	- [Google Maps Location Map](#google-maps-location-map)
	- [Favicon](#favicon)
	- [Features to Implement in the Future](#features-to-implement-in-the-future)
3. [Technologies](#technologies)
	- [Tools](#tools)
	- [Libraries](#libraries)
	- [Languages](#languages)
4. [Testing](#testing)
	- [Automated Testing](#automated-testing)
	- [UX Testing](#ux-testing)
	- [Manual Testing](#manual-testing)
	- [Bugs](#bugs)
5. [Deployment](#deployment)
6. [Credits](#credits)
	- [Content](#content)
	- [Media](#media)
	- [Code](#code)
    - [Resources](#resources)
	- [Acknowledgements](#acknowledgements)
7. [Contact](#contact)


---
---
<br>

## UX

### Strategy

<br>

#### User Goals
- Find out information about the academy, it's procedures, different classes provided and instructors teaching the classes.
- Find out information about different age groups and skill levels that classes are divided into and timetable for classes.
- Find out membership prices.
- Sign up for membership. 
- Find information on how to get in touch with the school and start the training.
- Buy training equipment on the website

#### Stakeholder Goals
- Attract new members to join the academy and retain existing members.
- Provide comprehensive information about the academy and classes provided.
- Increase online presence as a tool of advertising and promotion.
- Process membership sign ups on the website.
- Sell Anaconda branded merchandise.
- Process online payments easily and without a hassle.
- Be able to easily update information on the website.

#### User Stories
- Link to User Stories - [CLICK HERE](https://docs.google.com/spreadsheets/d/1CIi1zBifp5aBSsgi96vp9oLkrAsZ-a9Hyv3Tw9sNon4/edit?usp=sharing)

<br>
<br>

### Scope

<br>

####  Features included:
1. Navigation bar

	The navigation bar features logo on the left-hand side and navigation links on the right-hand side. On mobile devices the logo collapses into hamburger menu.

	Navigation bar elements:
	- Logo - always links back to the _Home_ page
	- About
	- Classes
	- Shop
	- Contact
	
Navigation links have _underline from center_ hover effect taken from Hover.css website (see [Credits/ Code section](#code)).
There is no effect for active navigation link, I decided that the headline of the header banner was sufficient to indicate the page that the visitor was in.
Hover effect on links on the other hand was important from the perspective of good UX.

The Navigation bar's position is fixed to allow for quick navigation between pages and to avoid using _back to top_ button.
The bar's opacity is set to 75% (0.75), so that any content that might be obscured by it can be still visible (or at least possible to make out).

For narrow screens/ viewport sizes, the navigation links change from inline to stacked formation.

<img src="assets/images_readme/ms1-readme-features-navbardesktop.png" alt="Anaconda MAA website navbar on desktops">

<img src="assets/images_readme/ms1-readme-features-navbarphone.png" alt="Anaconda MAA website navbar on phone">
	
### Footer
The footer contains information (starting from the left):
- Logo - a black & white reversed version; appears right beside contact details (where it would be normally expected) but only on the widest screen size (over 1400px) as the space allows for it.
The logo disappears on the smaller screen/ viewport sizes to allow for other elements of the footer to create a nicer and more organised structure.
Because the logo is also always present on the screen in the fixed position Navbar, the disappearance of the logo from the footer is not really an issue.
- Contact details - a physical address, phone number and email address of the business.
- Opening times
- Navigation links - stacked in a column, links are repeated for an added comfort of browsing between pages without having to move mouse to the top of the screen.
This also gives visitors a total view of all pages that the website has.
- Social media links - links to Twitter, Pinterest, Facebook, Instagram and Youtube will have to be linked later to the business' actual pages in the respective channels.

<img src="assets/images_readme/ms1-readme-features-footerdesktop.png" alt="Anaconda MAA website footer on desktops">

<img src="assets/images_readme/ms1-readme-features-footerphone.png" alt="Anaconda MAA website footer on phone">

### 'Join Academy' call to action button
The business owner has asked to have a prominent and distinctive __'Join Our Academy'__ button repeated in few places across the whole website, on all or almost all of the pages.
The button also appears as __'Get Started'__ in the _Membership Prices_ section of the _Times & Prices_ page, it links at the moment to the contact form in _Contact_ page, but in the future the owner would like at least for the __'Get Started'__ button to link to the online payment feature of the website.
At the moment payments need to be processed over the phone or at the Academy. The button should always be accompanied by the invitation to 'take a free trial class'. 

<img src="assets/images_readme/ms1-readme-features-joinacademy.png" alt="Anaconda MAA website join the academy call to action button">

### Home Page
The _Home_ page features a big welcome banner showing an image of one of the classes at the Academy with the big headline and call to action to join the Academy at the center of it.
Below is the quick overview of disciplines that the Academy offers classes in: Brazilian Jiu-Jitsu, Kickboxing and Boxing, and an invitation to read more about them (each discipline links to a specific related section of the _About_ page).
Returning to the _Home_ page is only possible via clicking on the logo or the navigation link in the footer.

<img src="assets/images_readme/ms1-readme-features-home.png" alt="Anaconda MAA website - Home page">

### About Page
The _About_ page, features smaller than _Home_ page main banner (smaller size banner also features on the rest of the pages). The page contains couple of paragraphs about Anaconda Martial Arts Academy and a small section devoted to each of the martial arts disciplines taught at the school.
Each of those sections has __'Join Our Academy'__ call to action button and an additional link to _Coaches_ page inviting visitors to get some information about the Instructor for the particular discipline.

<img src="assets/images_readme/ms1-readme-features-about.png" alt="Anaconda MAA website - About page">

### Classes Page
The _Classes_ page, apart from the main banner, features sections explaining division of classes into different age and skill level groups.
Two sections - Kids & Teens Classes and Adults Classes - have each a responsive diagram of different age/skill levels per discipline and also __'Join Our Academy'__ call to action button and an additional link to the Classes Schedule in the _Times & Prices_ page.
This makes the user flow of checking the suitable age group/ skill level and immediately finding out the times for the suitable classes more fluent.

<img src="assets/images_readme/ms1-readme-features-classes.png" alt="Anaconda MAA website - Classes page">

### Times and Prices Page
This pages' main section is a diagram of (nearly) full week (Monday to Saturday), with classes put in the appropriate day of the week by hour slots - 6 day columns by 8 hour rows.
This diagram presented a bit of a challenge for the responsive design. The full week diagram (6 columns and 8 rows ) can be displayed only on wide screen sizes.
Once the screen/ viewport size goes below 992px (Bootstrap's grid column large screen size breakpoint), the day columns get stacked on top of each other and empty hour slots (no class taking place at that time) also disappear.
There is a possibility here for future development, creating a filter that highlights only and all classes in the category determined by the filter.

<img src="assets/images_readme/ms1-readme-features-times.png" alt="Anaconda MAA website - Times & Prices page">


The bottom section of the _Times & Prices_ page is 4 boxes representing different membership options, one of them had to be a distinctive looking offer of a free introductory class.
Each box has a 'Get Started' button that links to _Contact_ page at the moment, expecting visitors to get in touch with the academy through contact channels given on that page in order to sign up and pay for membership.
In the future, the academy owner would like this button to link directly to online sign up and payment feature. 

<img src="assets/images_readme/ms1-readme-features-prices.png" alt="Anaconda MAA website - Times & Prices page">

### Coaches Page
The _Coaches_ page, offers short bios on three academy instructors, each of the instructors is a specialist in one of the three martial arts taught in the academy.
The link from each instructor to the corresponding martial art description on _About_ page (and the link back from a martial art to the corresponding instructor) create an easy user flow where visitors by checking the info about the martial art can quickly find out who is teaching it (and vice-versa).
There are 'About (Discipline)...' obvious links created with hover effects, but there are also same links created on the red names of each discipline (no hover effect), underneath the names of instructors. I decided to turn those red names into links, when I realised that I felt like clicking on those words in my own user testing.

<img src="assets/images_readme/ms1-readme-features-coaches.png" alt="Anaconda MAA website - Coaches page">

### Contact Page
The _Contact_ page is a destination page for all the __'Join Our Academy'__ call to action buttons.
It contains the two main features:
- Contact Form
- Google Maps Location Map

<img src="assets/images_readme/ms1-readme-features-contact.png" alt="Anaconda MAA website - Contact page">

### Contact Form
The business owner expects the following entries in the contact form:
- Radio buttons to state one of the three reasons for getting in touch with the Academy (in order to be able to prioritise potential new members over general queries in times of high volume of incoming messages):
	- Book free trial class
	- Membership queries
	- General queries
- Name
- Email address
- Phone number
- The message

All entry fields except for the phone number are required in order to submit the query.

The online form is not connected to email or any back-end support at the moment (due to unskilled developer).
The 'Submit' button takes the visitor to another page, confirming (unjustifiably) the receipt of the email by the academy and making (baseless) promise of the prompt response.
Completing the back-end support for the form would be an urgent priority needed very soon.
In fact it would be probably problematic to release the website with not functional online form.

__NOTE:__

__! The website should not be deployed in the custom hosted environment before the online query form back-end functionality is added.
If deploying before, the appropriate disclaimer information should be added beside the form or the form should be removed (commented out) for the time being !__

<img src="assets/images_readme/ms1-readme-features-contactform.png" alt="Anaconda MAA website - Contact page online query form">

### Google Maps Location Map
The map feature at the moment is an embedded \<iframe>, code generated on [www.maps.ie](https://www.maps.ie/create-google-map/) website and doesn't include the business marker yet.
The proper map with the location marker will have to be added in the next round of development (requires JavaScript and API technologies is what I'm hearing).

<img src="assets/images_readme/ms1-readme-features-map.png" alt="Anaconda MAA website - Contact page google maps">

### Favicon
Favicon won't let the the Anaconda MAA website get lost in the sea of open web browser tabs.

<img src="assets/images_readme/ms1-readme-features-favicon.png" alt="Anaconda MAA website - favicon">


### Features to Implement in the Future
- Definitely needed in the near future.
	- Full back-end functionality of the contact form.
	- Google maps with a marker.
	- Online Membership Signup & Payment feature - as a direct link from the Membership Prices boxes on the _Times & Prices_ page.
	- Navbar hidden in the hamburger menu icon - to reduce the size of the real estate taken by the current Navbar.
	- Members testimonials page - currently there are testimonials posted on social media, _"but it would be nice to have them on the website as well"_ (business owner's quote).
- Potentially something to look at in the future.
	- Online Free Trial Class booking - a feature allowing users to pick the class date and time in the online calendar and have the class automatically booked, with confirmation email automatically sent to user.
	- Filters that highlight the selected classes on the Class Schedule calendar - for quick and easy preview.
	Filter classes:
		- filter by discipline
		- filter by age group
		- filter by skill level
		- filter by class time
	- Video Gallery

