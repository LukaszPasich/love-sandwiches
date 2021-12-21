# _Anaconda_ Martial Arts Academy

_Anaconda_ Martial Arts Academy is a local school of martial arts located in Dublin 15, that teaches a combination of disciplines necessary to become a Mixed Martial Artist.
The goal of the academy however is not to train competition ready athletes but to help their members to get active and fit and receive all benefits of martial arts training, including building self-esteem and confidence.
The classes tought in the academy are: Brazilian Jiu-Jitsu, Kickboxing and Boxing and also Mixed Martial Arts for the more advanced students.
Members can practice one chosen discipline or get involved with the whole MMA suite of disciplines.
The school accepts new members across all ages (in BJJ classes, kids can start as early as the age of 4) and various skill levels from Beginners to Advanced.
As 'Anaconda' academy is growing in members, they would like to automatise the process of signing up for memberships to and they would like to add a small e-commerce on their website to sell their branded merchandise.

<img src="images_readme/ms1-readme-overview.png" alt="Anaconda MAA website overview">

# Link to live project - [CLICK HERE](https://anacondamaa2.herokuapp.com/)

<br>

#### Contents
1. [UX](#ux)
	- [Strategy](#strategy)
		- [User Goals](#user-goals)
		- [Stakeholder Goals](#stakeholder-goals)
		- [User Stories](#user-stories)
	- [Scope](#scope)
		- [Features included](#features-included)
		- [Features to implement in the future](#features-to-implement-in-the-future)
	- [Structure](#structure)
	- [Skeleton](#skeleton)
		- [Wireframes (low fidelity wireframes)](#wireframes-(low-fidelity))
		- [Prototype (high fidelity wireframes)](#prototype-(high-fidelity))
	- [Surface](#surface)
2. [Technologies](#technologies)
	- [Tools](#tools)
	- [Libraries](#libraries)
	- [Languages](#languages)
3. [Testing](README_testing.md#testing)
	- [Automated Testing](#automated-testing)
	- [UX Testing](#ux-testing)
	- [Manual Testing](#manual-testing)
	- [Bugs](#bugs)
4. [Deployment](#deployment)
5. [Credits](#credits)
	- [Content](#content)
	- [Media](#media)
	- [Code](#code)
    - [Resources](#resources)
	- [Acknowledgements](#acknowledgements)
6. [Contact](#contact)


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

	_Shopping Bag_ page contains the list of products that have been added to the bag in the single continued session (not ended with payment). The products are subtotalled individually and the grand total is calculated at the bottom of the page. 

	_Shopping Bag_ page can be accessed via the link in the navbar - the current euro value of the bag link - and it can be also accessed by clicking on _Go to secure checkout_ button on the 'SUCCESS!' toast, which always appears on the occasion of adding product to the _Shopping Bag_ or updating the quantity. 

	---
	__NOTE!__

	There is 10% Delivery charge calculated on orders under 50EUR, this hasn't been communicated very well, I decided to communicate more strongly 10% Discount for Academy members, but connecting memberships to users didn't happen at the end. It should be a featured considered at the next round of website updates.  

	---

	<img src="assets/images_readme/ms1-readme-features-prices.png" alt="Anaconda MAA website - Times & Prices page">


<br>

20. _Checkout_ page and functionality

	_Checkout_ page is the last step before confirming the payment in the Anaconda academy shop. The page contains the summary overview of the shopping bag with the grand total and a form with personal, delivery and payment details.

	The form contains below fields (* fields are required):
	- Full name *
	- Email *
	- Phone number *
	- Street address 1 *
	- Street address 2 *
	- Town or City *
	- County, State or Locality
	- Postal code
	- Country * (select from dropdown menu)
	- Credit Card number *
	- Save delivery info to my profile (checkbox)

	On submitting the form (Complete Order), the payment is being processed through Stripe, the 'Success!' toast pops up and the user is taken to the _Thank You_ page with full details order confirmation.

	---
	__NOTE!__

	The order confirmation email is currently not being sent. This needs to be fixed at the soonest opportunity.

	---

	<img src="assets/images_readme/ms1-readme-features-prices.png" alt="Anaconda MAA website - Times & Prices page">

<br>

21. Order confirmation _Thank You_ page

	This page contains full order summary of the order just processed.
	- Order info:
		- Order number
		- Order date
	- Order details
	- Delivering to info:
		- Full name
		- Phone number
		- Street address 1
		- Street address 2
		- Town or City
		- County, State or Locality
		- Postal code
		- Country
	- Billing info:
		- Order total
		- Delivery
		- Grand total


	<img src="assets/images_readme/ms1-readme-features-prices.png" alt="Anaconda MAA website - Times & Prices page">

<br>

22. _Stripe_ payment functionality

	_Stripe_ is setup for processing the payment on the website. Webhooks are connected to ensure that the order is accounted for at the point of clicking on _Complete Order_ button on _Checkout_ page and is going to be processed even if the connection with website is broken suddenly.

<br>

23. Toasts

	Toasts are connected to _messages_ in views and they pass on the messages of success, info, warnings and errors.
	
	Check the full list of toasts in the [Manual testing section](README_testing.md#manual-testing).

<br>

24. Toasts

	Toasts are connected to _messages_ in views and they pass on the messages of success, info, warnings and errors.

	<img src="assets/images_readme/ms1-readme-features-favicon.png" alt="Anaconda MAA website - favicon">

<br>
<br>

#### Features to implement in the future
- Online Membership Signup & Payment feature.
- Connect Memberships to Users.
- Connect 10% discount in the shop to users with academy membership.
- Add more products and categories to the shop.
- Connect Order Confirmation email.
- Add confirmation or cancel delete (defensive design) to _Delete Product_ button.
- Connect the contact form to some emailing service (EmailJS etc...)
- Add Google maps with a marker on contact page.
- Add members testimonials page.
- Online Free Trial Class booking - a feature allowing users to pick the class date and time in the online calendar and have the class automatically booked, with confirmation email automatically sent to user.


<br>

[Back to top](#contents)


---
<br>

### Structure

<br>

[Back to top](#contents)

---
<br>

### Skeleton

<br>

#### Wireframes (low fidelity)
Wireframes created for 4 screen/ device sizes: desktop, tablet-landscape, tablet-portrait and phone.
- [Wireframes for all pages AVAILABLE HERE](https://indd.adobe.com/view/d9db8027-1cdd-4de5-86b2-efcc73aef2eb)

	---
	__NOTE__

	Ultimately, I didn't have time/skills to implement the membership purchase functionality that is presented in the wireframes. 

	---

<br>

#### Prototype (high fidelity)
Prototype for desktop only created.
- [Prototype - desktop version of the website AVAILABLE HERE](https://xd.adobe.com/view/3225eceb-21c6-4e20-9318-36ec8daf1735-6776/)

	---
	__NOTE__

	Ultimately, I didn't have time/skills to implement the membership purchase functionality that is presented in the wireframes. 

	---

<br>

[Back to top](#contents)

---
<br>

### Surface

<br>

-	The Name - Why Anaconda?

	The martial art of Brazilian Jiu-Jitsu - one of the staples of the academy - is in essence the skill of grappling, holding and taking down the opponent to then force them into submission via joint lock or chokehold.
	This very much resembles the actions of a constrictor snake and one of the submissions in BJJ is even called an _Anaconda Choke_. As grappling has become one of the key weapons in Mixed Martial Artist's arsenal, Brazilian Jiu-Jitsu became near synonymous with MMA and that's why I thought it was a good name for this Martial Arts Academy.

<br>

- Logo

	With the logo I was trying to emulate the classic idea of the Martial Arts Club badge which seems to have always evolved around some related image or an Asian symbol enclosed in a circle (or lately popular octagon), with the club name and all the necessary text wrapped around that circle.

	Reference images:

	<img src="assets/images_readme/ms1-readme-ux-logoref.jpg" alt="Anaconda MAA website logo reference">

	Anaconda MAA final logo:

	<img src="assets/images_readme/ms1-readme-ux-logo.jpg" alt="Anaconda MAA logo">

<br>

- Colours

	Principally white, red and black colour palette.
	With black and white representing the concept of dualism, describing how seemingly opposite or contrary forces may actually be complementary, interconnected, and interdependent in the natural world, and the red colour being universally seen as a sign of both life and aggression - the 3 colours have always been used in martial arts themes.

	In my research of the competitor's websites, I discovered that these were the prevalent colours on all of those websites and the similar colour theme would also be possibly expected by the website user/ visitor. Meeting this expectation adds credibility to the brand, company and the website. 


	<img src="assets/images_readme/ms1-readme-ux-colours.jpg" alt="Anaconda MAA website colours">

<br>

- Typography

	Raleway: Semi-Bold, Bold and Extra Bold - for headlines and sub-headlines.

	_Raleway_ because it is a nice and clean display typeface and also geometric sans-serif fonts (as _Raleway_ being geometric inspired) tend to have more neutral feel about them.
	As Anaconda MAA aims at attracting a diverse audience, I didn't want to use font with too strong personality, because I wanted to convey an 'everybody is welcome' academy's approach to attracting it's new members.

	Roboto: Regular - for body text.

	_Roboto_ has forms that are largely geometric, but at the same time, the font features friendly and open curves - it is an excellent body text font and a good compliment to Raleway.
	Allowing letters to be settled into their natural width and with slab-serifs clearly defining the text baseline _Roboto_ creates an easy and more natural reading rhythm.


	Both fonts and also their combination has been tried and is well established and widely popular on the web.

<br>

- Images - Why black and white photography?

	Black and white photography removes any distraction of color and helps the viewer focus on other aspects of the photo, such as the subject, the textures, shapes and patterns, and the composition.
	It can convey remarkable purity of emotion and action and therefore works perfect for martial arts.


[Back to top](#contents)

---
---

<br>

## Technologies
### Tools
- [GitHub](https://github.com) was an IDE used for the project.
- [GitPod](https://gitpod.io/workspaces/) was used for version control.
- [Balsamiq](https://balsamiq.com) was used to create low fidelity wireframes.
- [Adobe XD](https://www.adobe.com/ie/products/xd.html) was used to build the high fidelity prototype.
- [Adobe Illustrator](https://www.adobe.com/ie/products/illustrator.html) was used to create the logo and also create/manipulate vector illustration icons and for saving vectors in .svg format.
- [Adobe Photoshop](https://www.adobe.com/ie/products/photoshop.html) was used to edit, crop and save images.
- [Adobe InDesign](https://www.adobe.com/ie/products/indesign.html) was used to create some visuals for this _Readme_ file and InDesign's online publish feature was used to store some of those visuals.
- [Am I Responsive](http://ami.responsivedesign.is) was used to create the images of each page displayed on different screen sizes in this _Readme_ file.

### Libraries
- [Bootstrap](https://getbootstrap.com/) grids were used in particular to create and maintain the design layout across different screen/viewport sizes and make the website responsive easily.
- [Google Fonts](https://fonts.google.com) was used for linking _Raleway_ and _Roboto Slab_ fonts to the website.
- [Font Awesome](https://fontawesome.com) was used for icons in the footer.

### Languages
- HTML
- CSS

<br>

[Back to top](#contents)

---
---

<br>

## Credits
### Content
The textual content was influenced by or taken from the websites:
- [JS Brazilian Jiu-Jitsu](https://www.jsbjj.ie "JS Brazilian Jiu-Jitsu")
- [Evolve Daily blog](https://evolve-mma.com/blog/4-reasons-boxing-will-make-you-obsessed-to-working-out/ "Evolve Daily blog")
- [Club Solutions Magazine](https://clubsolutionsmagazine.com/2018/11/7-reasons-kickboxing-classes-schedule/ "Club Solutions Magazine")
- [Satori BJJ Dublin](https://www.satoribjj.com "Satori BJJ Dublin")
- [Royal Grappling Academy](https://rga.ie "Royal Grappling Academy")

### Media
- Home page main banner - by Nathan Dumlao, downloaded from [www.unsplash.com](https://unsplash.com/photos/DT3bb-KDAus "www.unsplash.com")
- Home page BJJ white image - by Nathan Dumlao, downloaded from [www.unsplash.com](https://unsplash.com/photos/NdCixEBtTf0 "www.unsplash.com")
- Home page kickboxing white image - bu Justin Ng, downloaded from [www.unsplash.com](https://unsplash.com/photos/45tcVh0M3kw "www.unsplash.com")
- Home page kickboxing icon - by Miguel Angel, downloaded from [www.vecteezy.com](https://www.vecteezy.com/vector-art/93089-woman-and-man-fighting-silhouettes "www.vecteezy.com")
- Home page boxing white image - by Anastase Maragos, downloaded from [www.unsplash.com](https://unsplash.com/photos/ZUBNPRZsQvk "www.unsplash.com")
- Home page boxing icon - by yoosillyone, downloaded from [www.vecteezy.com](https://www.vecteezy.com/vector-art/166423-muay-thai-silhouette "www.vecteezy.com")
- About page main banner - by Nathan Dumlao, downloaded from [www.unsplash.com](https://unsplash.com/photos/NdCixEBtTf0 "www.unsplash.com")
- About page boxing bag image - by Milo Bunnik, downloaded from [www.unsplash.com](https://unsplash.com/photos/lp9GQiQNHqc "www.unsplash.com")
- About page BJJ image - by Nathan Dumlao, downloaded from [www.unsplash.com](https://unsplash.com/photos/YmNIHXdTfPg "www.unsplash.com")
- About page kickboxing image - by cottonbro, downloaded from [www.pexels.com](https://www.pexels.com/photo/woman-in-black-shirt-and-black-shorts-carrying-black-leather-shoulder-bag-4754146/ "www.pexels.com")
- About page boxing image - by Logan Weaver, downloaded from [www.unsplash.com](https://unsplash.com/photos/9D_rUDe7xvA "www.unsplash.com")
- Classes page main banner - by Nathan Dumlao, downloaded from [www.unsplash.com](https://unsplash.com/photos/AsCCBr7J-XM "www.unsplash.com")
- Classes page kids & teens classes image - by Microgen, downloaded from [www.stock.adobe.com](https://stock.adobe.com/ie/images/martial-arts-training-class-for-children/176854174 "Adobe Stock")
- Classes page adults classes image - by Nathan Dumlao, downloaded from [www.unsplash.com](https://unsplash.com/photos/YQg2wxJAINQ "www.unsplash.com")
- Times & Prices page main banner - by Nathan Dumlao, downloaded from [www.unsplash.com](https://unsplash.com/photos/QMhc3D_zwJ0 "www.unsplash.com")
- Coaches page main banner - by Gantas Vaičiulėnas, downloaded from [www.unsplash.com](https://unsplash.com/photos/rvAcZMqFIkY "www.unsplash.com")
- Coaches page BJJ coach image - by Jahir Martinez, downloaded from [www.unsplash.com](https://unsplash.com/photos/cVLOqm8sSXc "www.unsplash.com")
- Coaches page kickboxing coach image - by Michael Uebler, downloaded from [www.unsplash.com](https://unsplash.com/photos/EwnkEPhVym4 "www.unsplash.com")
- Coaches page boxing coach image - by John Fornander, downloaded from [www.unsplash.com](https://unsplash.com/photos/r79IYSMpu_M "www.unsplash.com")
- Contact page main banner - by Thao Le Hoang, downloaded from [www.unsplash.com](https://unsplash.com/photos/XeBk0qF77_4 "www.unsplash.com")

### Code
- Navigation links hover effect (underline from center) styling - code found on Hover.css website [https://ianlunn.github.io/Hover/#effects](https://ianlunn.github.io/Hover/#effects), (style.css file lines 213-241). 
- _Home_ page - overlay hover effect on 3 images (BJJ, Kickboxing and Boxing) styling - code found on [www.w3schools.com](https://www.w3schools.com/howto/howto_css_image_overlay_title.asp), (style.css file lines 331-357).
- _Coaches_ page - zoom effect on hover over coaches images styling - code found on [www.w3bits.com](https://w3bits.com/css-image-hover-zoom/) website, (style.css file lines 535-551).
- _Contact_ page - Google Maps location map code generated on [www.maps.ie](https://www.maps.ie/create-google-map/) Google Maps generator, (contact.html file lines 128-137).

### Resources
Websites I have accessed for solutions/ questions and extra resources:
- [www.w3schools.com](https://www.w3schools.com)
- [www.stackoverflow.com](https://stackoverflow.com)
- [www.developer.mozilla.org](https://developer.mozilla.org/en-US/)
- [www.css.tricks.com](https://css-tricks.com)
- [How to add a favicon to your website](https://www.digitalocean.com/community/tutorials/how-to-add-a-favicon-to-your-website-with-html)
- [Code Institute course content](https://codeinstitute.net/)

### Acknowledgements
- Thank you to my mentor __Nishant Kumar__ for his guidance, support and continuous helpful feedback throughout this project.
- Tutor Support at Code Institute and the Slack Community for a solution to any question at any time.

<br>

[Back to top](#contents)

---
---

<br>

## Contact
For any queries related to this project, you can contact me at:

lukas (dot) zed81 (at) gmail (dot) com.

<br>

[Back to top](#contents)

---
---
---

<br>

### THANK YOU FOR TAKING TIME TO VIEW THIS PROJECT!