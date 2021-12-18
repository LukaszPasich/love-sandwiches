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

	The navigation bar features logo on the left-hand side and navigation links on the right-hand side.

	Navigation bar elements:
	- Logo - always links back to the _Home_ page
	- About - links to _About_ page
	- Classes - links to _Classes_ page
	- Shop - links to the e-commerce _Shop_ page
	- Contact - links to _Contact_ page
	- Account - has hidden on click dropdown menu with links:
		- Sign up - visible for non-logged in user
		- Login - visible for non-logged in user
		- My Profile - visible for logged in user
		- Logout - visible for logged in user
		- Products - visible for admin user

	- Join now - links to page with all membership options
	- Bag total - displays current shopping bag value
	
	Navigation links have _underline from center_ hover effect taken from Hover.css website (see [Credits/ Code section](#code)).
	There is no effect for active navigation link, the headline of the header banner is sufficient to indicate the page that the user is in.

	The Navigation bar's position is fixed to allow for quick navigation between pages.
	
	On mobile devices the logo collapses into hamburger menu.

	<img src="assets/images_readme/ms1-readme-features-navbardesktop.png" alt="Anaconda MAA website navbar on desktops">

	<img src="assets/images_readme/ms1-readme-features-navbarphone.png" alt="Anaconda MAA website navbar on phone">
	
<br>

2. Footer

	The footer contains following information:
	- Logo	
	- Contact details - academy's location, phone number and email address
	- Opening times
	- Navigation links - stacked in a column, same navigation links as in navigation bar
	- Social media links - links to Twitter, Pinterest, Facebook, Instagram and Youtube will have to be linked later to the academy's' actual pages in the respective channels.

	<img src="assets/images_readme/ms1-readme-features-footerdesktop.png" alt="Anaconda MAA website footer on desktops">

	<img src="assets/images_readme/ms1-readme-features-footerphone.png" alt="Anaconda MAA website footer on phone">

<br>

3. Home page

	The _Home_ page features a main banner with headline and call to action button to join the Academy. Below the banner is the quick overview of disciplines that the Academy offers classes in: Brazilian Jiu-Jitsu, Kickboxing and Boxing, and an invitation to read more about them on the _About_ page.

	<img src="assets/images_readme/ms1-readme-features-home.png" alt="Anaconda MAA website - Home page">

<br>

4. About page

	The _About_ page, features the main banner on top and below contains couple of paragraphs about Anaconda Martial Arts Academy followed by a small section devoted to each of the martial arts disciplines taught in the school and ending with information about the instructors.

	Each of the martial arts sections has __'Join Our Academy'__ call to action button and an additional link to _Coaches_ section, each of the instructors sections has in turn link back to information about the discipline they are teaching.

	<img src="assets/images_readme/ms1-readme-features-about.png" alt="Anaconda MAA website - About page">

<br>

5. Classes page

	The _Classes_ page, apart from the main banner, features two sections (Kids & Teens Classes and Adults Classes) explaining division of classes into different age and skill level groups. There is also __'Join Our Academy'__ call to action button and an additional link to the Class Timetable with each section. The Class Timetable is the last section on this page.

	<img src="assets/images_readme/ms1-readme-features-classes.png" alt="Anaconda MAA website - Classes page">

<br>

6. Contact page

	The _Contact_ page contains Contact Form to send email to the academy.

	(! email currenty not setup)

	<img src="assets/images_readme/ms1-readme-features-contact.png" alt="Anaconda MAA website - Contact page">

<br>

7. Contact Form

	Contact form contains below fields (* is required):
	- Name *
	- Email address *
	- Phone number
	- The message *
	
	(! the online form is not connected to email or any back-end support at the moment)

	---
	__NOTE:__

	__! The website should not be deployed in the custom hosted environment before the online query form back-end functionality is added.
	If deploying before, the appropriate disclaimer information should be added beside the form or the form should be removed (commented out) for the time being !__
	
	---

	<img src="assets/images_readme/ms1-readme-features-contactform.png" alt="Anaconda MAA website - Contact page online query form">

<br>

8. Membership page

	The _Membership_ page is accessed via __Join Now__ button in the navbar or __Join Our Academy__ call to action button 

4 boxes representing different membership options, one of them had to be a distinctive looking offer of a free introductory class.
Each box has a 'Get Started' button that links to _Contact_ page at the moment, expecting visitors to get in touch with the academy through contact channels given on that page in order to sign up and pay for membership.
In the future, the academy owner would like this button to link directly to online sign up and payment feature. 

<img src="assets/images_readme/ms1-readme-features-prices.png" alt="Anaconda MAA website - Times & Prices page">





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

