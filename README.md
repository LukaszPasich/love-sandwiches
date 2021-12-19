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

	Contact form contains below fields (* fields are required):
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

	The _Membership_ page is accessed via __Join Now__ button in the navbar or __Join Our Academy__ call to action button anywhere else in the website. The page has 4 boxes representing different membership options, one of them is a distinctive looking offer of a free introductory class. Each box has a __Get Started__ button that links to _Contact_ page at the moment, expecting visitors to get in touch with the academy through contact channels given on that page in order to sign up and pay for membership.

	<img src="assets/images_readme/ms1-readme-features-prices.png" alt="Anaconda MAA website - Times & Prices page">

<br>

9. Account - Sign up page

	The _Sign up_ page is accessible from the navbar _Account_ dropdown menu, if no user is currently signed in. The page contains the sign up form with the following fields (* fields are required):
	- Email address *
	- Email address confirmation *
	- Username *
	- Password *
	- Password confirmation *

	On submitting the form (Sign up) the user is taken to _Verify your email_ page, with the toast 'Alert!' being displayed informing user that the email has been sent to the submited email address with the link to verify the user's email address.

	<img src="assets/images_readme/ms1-readme-features-prices.png" alt="Anaconda MAA website - Times & Prices page">
	
<br>

10. Account - Login page

	The _Login_ page is accessible from the navbar _Account_ dropdown menu, if no user is currently signed in. The page contains the sign up form with the following fields (* fields are required):

	- Username *
	- Password *
	- Remember me (tickbox)

	On submitting the form (Sign in), the user is taken to the _Home_ page and a 'Success!' toast is displayed to confirm the successful login. Furthermore, a user icon is displayed above the _Account_ link in the navbar, indicating that a user is currently signed in.

	Below the the _login_ form a link to retrieve the _forgotten password_ is provided.

	<img src="assets/images_readme/ms1-readme-features-prices.png" alt="Anaconda MAA website - Times & Prices page">

<br>

11. Account - Logout page

	The _Logout_ page is accessible from the navbar _Account_ dropdown menu, if user is currently signed in. On successful sign out the 'Success!' toast is displayed and the user is taken to the _Home_ page.

	<img src="assets/images_readme/ms1-readme-features-prices.png" alt="Anaconda MAA website - Times & Prices page">

<br>

12. Account - Profile page

	The _My Profile_ page is accessible from the navbar _Account_ dropdown menu, if user is currently signed in. The page contains the form with user's delivery details and the history of purchases made on the website.

	Delivery Information form has fields:
	- Phone number
	- Street Address 1
	- Street Address 2
	- Town or City
	- County, State or Locality
	- Postal Code
	- Country (dropdown)

	On submitting this form, the 'Success!' toast pops up and the page reloads with the information updated.

	Order history contains the following information:
	- Order number - links to the order confirmation originally generated, with more details of the order (a toast 'Alert!' informs user that this os the past order)
	- Order date
	- Items purchased
	- Order total

	<img src="assets/images_readme/ms1-readme-features-prices.png" alt="Anaconda MAA website - Times & Prices page">


<br>

12. Account - Add Products page

	The _Add Product_ page allows admin user to add new products to the database and is accessible from the navbar _Account_ dropdown menu, only by admin user who is currently signed in. The page contains the form with the following product details to fill in (* fields are required):
	- Category (Choose from dropdown)
	- SKU
	- Name *
	- Description
	- Price *
	- Rating
	- Image URL (opens select from your computer web browser box)

	On submitting this form, the 'Success!' toast pops - the new product has been added to the database and the admin user is redirected to the _Product View_ page with the preview of the newly added product.

	<img src="assets/images_readme/ms1-readme-features-prices.png" alt="Anaconda MAA website - Times & Prices page">

<br>

13. Shop page

	Displays all products in the website's database on a responsive grid. Each product is represented by a box containing below details:
	
	- Image
	- Category
	- Name
	- Price
	- Rating
	- Edit button (available only to admin user)
	- Delete button (available only to admin user)

	Clicking on one of the products takes user to the individual _Product View_ page.

	There are tabs with different categories above the products allowing user to select all products or only products in the chosen category.

	---
	__NOTE:__

	More categories and more products should be added to complete the full offer.
	___

	<img src="assets/images_readme/ms1-readme-features-prices.png" alt="Anaconda MAA website - Times & Prices page">

<br>

14. Product search bar

	Product search bar appears on the _Shop_ page. It allows for searching for products based on the keyword(s) entered into the search bar (keywords searched in the category, name and description of the products).
	An 'Error!' toast pops up if search is performed with no search criteria entered or the search criteria was not found.

<br>

15. Sort by...

	_Sort by_ box appears on the _Shop_ page. It allows for sorting of the current selection of the products on the page (can be all products or products filtered by keyword or category).
	
	Current sorting criteria are:
	- Price (low to high, high to low)
	- Rating (low to high, high to low)
	- Name (A-Z, Z-A)
	- Category (A-Z, Z-A)

<br>

16. Product View page

	Individual _Product View_ page is accessed from the _Shop_ page after clicking on any product. This page contains similar details to the _Shop_ page with some expansions:
	- Image (bigger than on the _Shop_ page)
	- Category
	- Name
	- Price
	- Rating
	- Description
	- Quantity Selector
	- Edit button (available only to admin user)
	- Delete button (available only to admin user)

	_Add to Bag_ button ads the currently viewed product and it's selected quantity to the shopping bag. The 'Success!' toast with full current details of the shopping bag is displayed.

	<img src="assets/images_readme/ms1-readme-features-favicon.png" alt="Anaconda MAA website - favicon">

<br>

17. Edit Product page

	The _Edit Product_ page is available only to admin user and allows admin user to edit existing products and update these edits in database. Editing the product is available from the _Shop_ page or _Product View_ page. The page contains the same form as the _Add Product_ page, with all the fields populated with current product information.

	When accesing the _Edit Product_ page an 'Alert!' toast pops up to remind the user that this action will change product information.

	On submitting this form (Update product), the 'Success!' toast pops - the product has been updated in the database and the admin user is redirected to the _Product View_ page with the preview of the updated product.

	<img src="assets/images_readme/ms1-readme-features-prices.png" alt="Anaconda MAA website - Times & Prices page">

<br>

18. _Delete Product_ functionality

	_Delete Product_ functionality is available only to admin user and allows admin user to delete existing product from the database.
	Deleting the product is available from the _Shop_ page or _Product View_ page.
	
	---
	__WARNING!__
	
	Currently there is no confirmation of deleting the product required, so once the _Delete_ button is clicked on, the product is instantly erased from database. This will need to be corrected at the soonest opportunity.

	---

	On successful _Delete_ a 'Success!' toast pops up.

<br>

19. _Shopping Bag_ page and functionality

	_Delete Product_ functionality is available only to admin user and allows admin user to delete existing product from the database.
	Deleting the product is available from the _Shop_ page or _Product View_ page.




<br>
<br>
<br>

---
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

