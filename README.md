# 'Bristol Charity Coffee Collective (B3C)' Website

For my first project I decided to create a website for a fictional collective of independent coffee shops in Bristol.  Their unique selling point would be that they donate 20% of all profits from each sale to local charities.  Bristol is very near to my home, and has a great community spirit, along with a lovely independent food and coffee scene.  I was also inspired by local charities for the homeless.

I decided that as I am limited to HTML and CSS, that I would avoid creating any kind of online store or membership program, and stick to advertising the business.
 
## UX
 
My fictional brief involved the business looking to improve their web presence in an effort to:

1. Drive additional revenue
2. Allow customers to gain a greater understanding of their ethos
3. Improve customer interaction by providing multiple methods of contact

Aside from the obvious requirement of a 'landing' page (which I felt should have a full screen hero image and inviting navigation links), I wanted to create an online sample food and drinks menu, a page detailing the location of each shop, and an about page with information about the collective.  Finally I wanted to include a contact form.

I approached the design utilising the following user stories:

1. As a customer I need to be able to locate my closest shop
2. As a customer I need to be able to view a sample menu
3. As a customer I need to be able to contact the business
4. As a customer I need to be able to view the site on mobile devices, tablets, laptops and desktops

5. As the proprietor I need to increase awareness of my business and drive sales to facilitate charitable donations
6. As the proprietor I need to improve understanding of our charitable efforts amongst our customer base to generate opportunities for outreach
7. As the proprietor I need to provide additional contact points for our customers to drive active customer feedback

### Wireframes

I originally created my wireframes on paper, then recreated them in Balsamiq, which I have exported to /Wireframes/MP1-B3C-Wireframes.pdf

### Differences between the Wireframes and Final Design

The 'Inspiring Quote' on index.html, was replaced with information regarding the 20% charity donation from each sale, and membership of the [Suspended Coffees](https://www.suspendedcoffees.com/) movement.  This was also moved from being offset and right aligned at large breakpoints, to simply being centered on all breakpoints.  I made these changes late during the build process, as I felt that the charity information was more relevant, and that the centered design simply looked better.  I had originally planned for the site to have a second quote on the about.html page.  The original homepage quote was reused here instead.

## Features

1. Fully responsive mobile first design allows users to view the site on mobile, tablet, laptop, and desktop with design considerations for screen widths from 280px (Galaxy Fold) up to full 4k screens.
2. Welcoming images and text encourage users to explore the site
3. Menu carousel allows the display of food and drink menus without excessive scrolling
4. Tooltips on icons on the Locations page allow users to understand the available facilities at each shop
5. Contact modals for each shop allow users to tap/click to call the store directly, or open a new email
6. Directions button for each shop allow users to tap/click to open a google map in a new tab with directions from their current location (assuming active location services) to the selected shop
7. Contact Us modal + form allows users to submit a name, email address and comments
 
### Existing Features

I believe that I have met the needs of each of the User Story requirements within the confines of HTML and CSS:

1. As a customer I need to be able to locate my closest shop
	- locations.html provides the address for each shop, and a button which links to directions to the shop in google maps.
	- This could be improved by including a post code search, or a current location search, but these are outside the scope of the project.

    <br><img src="/README-Images/UserStory1.png">
	
2. As a customer I need to be able to view a sample menu
	- menu.html provides sample food and drink menus

    <br><img src="/README-Images/UserStory2.png">
	
3. As a customer I need to be able to contact the business / As the proprietor I need to provide additional contact points for our customers to drive active customer feedback
	- Each page provides access to the 'Contact Us' modal via links in the header and footer.
	- Additionally, locations.html provides a modal for each location that includes functional email and tel links
	
    <br><img src="/README-Images/UserStory3.png"><img src="/README-Images/UserStory7.png">

4. As a customer I need to be able to view the site on mobile devices, tablets, laptops and desktops
	- Each page is fully responsive between 280px wide to 4k+
	
5. As the proprietor I need to increase awareness of my business and drive sales to facilitate charitable donations
	- The site has a modern design, and includes plenty of indexible text
	- Images are served via img tags rather than background-images to ensure that they are also indexed

    <br><img src="/README-Images/UserStory5.png">

6. As the proprietor I need to improve understanding of our charitable efforts amongst our customer base to generate opportunities for outreach
	- index.html clearly states that the business donates 20% of each purchase to charity, and that they are members of Suspended Coffees.
	- about.html describes how the business makes it's donations in more detail, and encourages customers to report charitable endeavours for considerations

    <br><img src="/README-Images/UserStory6.png">

### Features Left to Implement

1. Validation Feedback Messages:
	- I did not have time available to implement validation feedback messages, opting for a simple red border/exclamation response for failure and green border/tick for validated entries.  With more time I would like to implement screen reader enabled descriptive responses.
2. Postcode Search:
	- I would like to implement a postcode based search and/or current location based search, (accessible via Locations.html and the Footer on each page), to enable users to locate and obtain directions to the closest shop.  (I do not believe that this can be accomplished without at least JS and a JSON so was not suitable for this project).
3. Membership:
	- I would like to implement a membership scheme, with user login and points based reward system for purchases etc.  This would not be possible at this stage of my course as it would require far greater back-end functionality.

## Technologies Used

The project is hosted on [Github](https://github.com/), and was developed using the [Gitpod](https://www.gitpod.io/) IDE.

Once the CSS files were complete, they were processed by [Autoprefixer](https://autoprefixer.github.io/) to add browser vendor prefixes

Images (sans Favicon and Logo) were processed by [TinyJPG](https://tinyjpg.com/) to reduce image sizes and improve loading times

The project was built using: 

* [HTML5](https://en.wikipedia.org/wiki/HTML5/)
* [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets/)
* [Bootstrap](https://getbootstrap.com/)
* [Font Awesome](https://fontawesome.com/)
* [Google Fonts](https://fonts.google.com/)
	
Contact Form Validation is provided by a sample [JavaScript](https://en.wikipedia.org/wiki/JavaScript) from [Bootstrap](https://getbootstrap.com/docs/4.5/components/forms/#validation).  This approach allows for screen reader interaction with validation feedback.


## Testing

All testing was conducted manually.<br><br>
Devices tested in browser dev tools include:
- Galaxy Fold
- iPhone 5/SE
- Pixel 2
- Galaxy S5
- Moto G4
- iPhone 6/7/8
- Surface Duo
- iPhone 6/7/8 Plus
- Galaxy S9/S9+/S10e
- iPhone X/XS
- Pixel 2 XL
- Bootstrap SM, MD, LG and XL Breakpoints
- 720p Screens
- 1080p Screens
- 4k Screens
											
Devices physically tested include:
- Galaxy S8
- Galaxy S10/S10e
- Galaxy Tab A 10.1 2019
- iPhone XR
- P20 Pro
- 1080p Screens
- 4k Screens
		
### User Story Testing

* As a customer I need to be able to view the site on mobile devices, tablets, laptops and desktops
	- Complete all tests in the Test Plan on each page at all tested resolutions
	- In Dev tools, choose 'responsive' and manually adjust the dimensions from a min of 280px through to 4k resolutions

### Test Plan

1. All Pages
	- Minimum supported width is 280px
	- View page in Firefox/Chrome/Edge at (Portrait and Landscape):
		1. All Standard device breakpoints in browser dev tools
		2. 768px
		3. 992px
		4. 1200px
		5. 720p
		6. 1080p
		7. 4k
																
	- At each breakpoint:
		- Header logo should be visible in the top left corner
			- Header logo should link to index.html
		- Burger Button/Navbar should display as appropriate:
			-  (0px-767px) Burger Button (Top right corner)
				- Ensure Nav dropdown displays correctly below the button along the right edge
				- Nav link icons should have a width of 1.25em
			-  (768px+) Expanded Nav (Right aligned)
				- The expanded Nav should have no visible border, background or box-shadow
				- (992px+) 
					- Nav link icons should have a font-size of 1.25em and a right margin of 5px
					- Nav link text should have a font-size of 1.4em
				
		- Nav Icon/Text spacing should be consistent, with Icons to the left of the Text
		- With the exception of the Active page (which should already be underlined), Nav text elements should underline on hover
		- All Nav links should function and link to the correct page
		- Contact Us link should display the Contact Us Modal and Form, which will transition down from the top center of the screen
			- The Modal X button should close the Modal
			- Clicking/tapping off the Modal should close the Modal
			- The Close button should close the Modal
			- The Submit button should validate the fields from the Contact Form, and submit the data to the CI server if validated.
				- If not validated, the invalid entries should gain a red border and a red exclamation mark icon on the right side of the field.
				- Invalid entries should validate 'on the fly' as they are corrected
				- Once all invalid entries are correct, the form should validate and submit
				- The success page will be displayed in a new tab

		- Contact Us Modal:
			- (992px+) 
				- Modal Title should increase to 1.5em
				- Modal button text should increase to 1em
			- (1200px+)
				- Modal button text should increase to 1.25em
																
																	
		- Footer should display Social Media Icons for:
			1. Facebook
			2. Instagram
			3. Twitter
			- All Icons should link to the appropriate Social Media Network
		
		- Footer should display Contact Us Icon
			- Contact Us Icon should load the Contact Us Modal and Form, which will transition down from the top center of the screen
				- The Modal X button should close the Modal
				- Clicking/tapping off the Modal should close the Modal
				- The Close button should close the Modal
				- The Submit button should validate the fields from the Contact Form, and submit the data to the CI server if validated.
					- If not validated, the invalid entries should gain a red border and a red exclamation mark icon on the right side of the field.
					- Invalid entries should validate 'on the fly' as they are corrected
					- Once all invalid entries are correct, the form should validate and submit
					- The success page will be displayed in a new tab
		
		- Footer should display Logo in the bottom left corner at 768px+
			- Footer logo should link to index.html		

2. Index.html
	- 'Home' Nav element should be Active in the Navbar and on the dropdown
	- The Hero Image should display full screen
	- Large logo should be displayed centrally over the Hero Image
		- (768px+) Large Logo should increase in height to 75px (width will scale) 
	- Welcome message should be visible:
		- (0px-1999px) above and below centralised logo
		- (1200px+) above centralised logo
			- size should increase to 4em
	- Charity message should display centrally below the Welcome message and Logo
		- URL to SuspendedCoffees.com should underline on hover and link to the correct site
		- (768px-1199px) Charity info text should increase to 1em
		- (1200px+) Charity info text should increase to 1.4em
	- CTA Elements (Menu, Locations, About, Contact) Should display:
		- (0px-767px) As Images with overlaid link (button)
			- Button will have a blue border (.btn-outline-info), and an rgba(0,0,0,0.5) background.
			-  On any tested resolution, any single given CTA Image should always fit within the confines of the screen (portrait or landscape)
		- (768px-1919px) As alternating left/right Images/Text (per wireframe)
			<br><img src="/README-Images/CTA-Elements-768-1919.png">
			
			- On any tested resolution, any single given CTA Image + Text Block should always fit within the confines of the screen (portrait or landscape) in a single row (no flex wrapping)
			
			- On Laptop/Desktop:
				- CTA Images should darken and show the appropriate Button on hover
					- At these resolutions the CTA Image buttons will have no styling and will appear as standard links
					- (1920px)
						- CTA Image Button text should increase to 1.75em
						- CTA Image Button icons should increase to 1.65em
				- CTA Buttons should darken on hover
				
			- (992px+)
				- H4 headers should increase to 1.5em
				- P and Span text and icons should increase to 1em
			
			- (1200px+)
				- p and span text should increase to 1.25em
				- icons should increase to 1.1em													
													
		- (1200px+) As a block of 4 images flanked by text in the following order (per wireframe)
            <br><img src="/README-Images/CTA-Elements-1200.png">

			- On Laptop/Desktop:
				- CTA Images should darken and show an appropriate URL on hover
				- CTA Buttons should darken on hover

		- (1920px+) the CTA Block should be full width(-20px), with a max width of 2140px
	
		- Regardless of resolution:
			- All CTA buttons/links should function and link to the correct page
			- CTA Images/Text should resize responsively to fit tested display resolutions (portrait and landscape).																														

3. Menu.html
	- 'Menu' Nav element should be Active in the Navbar and on the dropdown
	- Menu title should be displayed centrally at the top of the page (below the Navbar)
	- (0px-451px) The 'Food' and 'Drinks' carousel indicators will stack with their respective icons, increasing their height.  Alignment of lower carousel items should adjust to maintain spacing.
	- At all breakpoints, on both 'Food' and 'Drinks' carousel items:
		- All headings should be underlined
		- Menu Availability Notice should have a darker background
		- Menu Availability Notice text will be centered
		- Menu Availability Notice will extend to the full width of the rows preceeding it
	- 'Food' Carousel Indicator should be active (Opacity 1, 'Food' menu visible):
        - (0px-767px) Food menu should display centered, in a single column in the following order:
            <br><img src="/README-Images/Food-Menu-Single-Column.png">
		    - (411px) Menu items should increase in size to 1em
																																				
		- (768px-1199px) Food menu should display left aligned, in 2 columns offset by a full height left sidebar displaying an image of Pastries and Coffee, in the following order:
            <br><img src="/README-Images/Food-Menu-Double-Column.png">			
		
		- (1200px+) Food menu should display left aligned, in 4 columns offset by a full height left sidebar displaying an image of Pastries and Coffee, in the following order (note the addition of multi column dividers):
			<br><img src="/README-Images/Food-Menu-Quadruple-Column.png">

	- 'Drinks' Carousel Indicator should be inactive (Opacity .5, 'Food' menu visible)
	- 'Drinks' Carousel Indicator should become Active when tapped/clicked:
		- Opacity changes to 1
		- 'Drinks' menu slides onto the screen from the right
																
		- (0px-767px) Drinks menu should display centered, in a single column in the following order:
            <br><img src="/README-Images/Drinks-Menu-Single-Column.png">
			- (411px) Menu items should increase in size to 1em
									
		- (768px-1199px) Drinks menu should display left aligned, in 2 columns offset by a full height right sidebar displaying an image of 2 Coffee Cups and Green Leaves, in the following order (note the addition of multi column dividers):
            <br><img src="/README-Images/Drinks-Menu-Double-Column.png">

		- (1200px+) Drinks menu should display left aligned, in 4 columns offset by a full height right sidebar displaying an image of 2 Coffee Cups and Green Leaves, in the following order (note the addition of multi column dividers):
			<br><img src="/README-Images/Drinks-Menu-Quadruple-Column.png">

	- 'Food' Carousel Indicator should be inactive (Opacity .5, 'Drinks' menu visible)
	- 'Food' Carousel Indicator should become Active when tapped/clicked:
	  - Opacity changes to 1
	  - 'Food' menu slides onto the screen from the left
	
	- On a mobile device, swiping left or right should change the Active Indicator and display the appropriate menu.  The side that the menu slides on from will depend on the direction of the swipe (this is built in bootstrap carousel functionality)

	### User Story Testing
	
	* As a customer I need to be able to view a sample menu
		- Open menu.html
		- Scroll to review the food menu
		- Swipe left/right or tap/click the Carousel Indicators to switch between Food and Drinks menus
	
4. Locations.html
	- 'Locations' Nav element should be Active in the Navbar and on the dropdown
	- Locations title should be displayed centrally at the top of the page (below the Navbar)
	- At all resolutions:
		- Each locations title should be underlined
		- Each locations facilities icon should have an appropriate tooltip displayed below that icon on tap/hover
		- Each locations Contact button should:
			- display an icon to the left of the button text
			- Open the location modal for that location, which will transition down from the top center of the screen
				- The Modal X button should close the Modal
				- Tapping/Clicking off the Modal should close the Modal
				- The Close button should close the Modal
				- Tapping/Clicking the displayed telephone number should prompt for an application to call that number/start a call to the appropriate number
				- Tapping/Clicking the email should prompt for an application to create an email/open a new email addressed appropriately
		- Each locations Contact button should:
			- display an icon to the left of the button text
			- Open Google Maps in a new tab with directions to the appropriate address from the current location (assuming location services are active and available to the browser as normal for Google Maps)
	- (0px-767px):
		- On any tested resolution, any single given Location Image should always fit within the confines of the screen (landscape)
		- On any tested resolution, any single given Location Image + Address Block should always fit within the confines of the screen (portrait)
		- Each location should display in a single column, in the following element order (Note the Divider at the bottom):
			<br><img src="/README-Images/Location-Card-Single-Column-Element-Order.png">

		- Each location should display in the following order:
            <br><img src="/README-Images/Location-Card-Order.png">

	- (768px+)
		- Each location should display in a single row, in the following, alternating element order (per wireframe) (No dividers should be visible at these resolutions):
            <br><img src="/README-Images/Location-Card-Alternating-Element-Order.png">
			
			- The Address elements and buttons should vertically fit within the height of the image
			- (992px+)
				- the Contact and Directions buttons will stack vertically (Contact, then Directions).
					- The Address elements and buttons should still vertically fit within the height of the image
				- Location Modal Titles should increase to 1.5em
				- Modal text and button text should increase to 1em
			- (1200px+)
				- Modal text and button text should increase to 1.25em
				- Modal icons should increase to 1.1em
			- (1440px+)
				- the Location elements will stop sizing with the browser until 1920px, when they will maintain a width of 75% of the browser window, with a max of 2140px.
			
	### User Story Testing
	
	* As a customer I need to be able to locate my closest shop
		- Open Locations.html
		- Review the Addresses of each location
		- Utilise the Directions buttons to open google maps and locate the chosen location
		
	* As a customer I need to be able to contact the business
		- Open Locations.html
		- Utilise the Contact buttons to open the location modals
		- Tap/Click the Telephone number to call the shop
		- Tap/Click the Email address to begin a new email to the shop
		
		- On Each page
			- Choose 'Contact Us' from the dropdown menu (0px-767px), Navbar (768px+) or Footer Icon (any resolution)
			- The Contact Us Modal and Form, will transition down from the top center of the screen
				- The Modal X button should close the Modal
				- Clicking/tapping off the Modal should close the Modal
				- The Close button should close the Modal
				- The Submit button should validate the fields from the Contact Form, and submit the data to the CI server if validated.
					- If not validated, the invalid entries should gain a red border and a red exclamation mark icon on the right side of the field.
					- Invalid entries should validate 'on the fly' as they are corrected
					- Once all invalid entries are correct, the form should validate and submit
					- The success page will be displayed in a new tab

5. About.html
	- 'About' Nav element should be Active in the Navbar and on the dropdown
	- About title should be displayed centrally at the top of the page (below the Navbar)
	- Hero Image should display below the title, at full width(-30px)
		- At any tested resolution the hero image should fit within the confines of the screen (landscape)
			- At most tested resolutions, the title should *also* fit within the confines of the screen (landscape) (notable exceptions are outliers such as the Galaxy Fold)
	- Logo should display centrally over the Hero image
	- Logo will maintain relative size and width to the Hero as it resizes
	- Quote appears below the hero image, centered
	- About text (4 sections, separated by dividers) appear below the quote
	- Round 'Coffee Heart' image appears below the About text		
	- All <section> elements will resize appropriately to a max of 2140px
	
	- (411px+)
		- Paragraph text should increase in size to 1em
		- H4 text (quote) should increase in size to 1.5em
		- H5 text (quote attribution) should increase in size to 1.25em
		
	
### Notable Challenge

Due to wanting to avoid overlapping media queries wherever possible, it was difficult to ensure that CTA Images did not exceed the height of the screen (in landscape) on certain devices.  The only way to achieve the desired result was to sparingly include some height restrictions.  Of my 19 media queries, only 3 are based on a combination of width+height.  The rest rely soley on width.  I believe I could solve this issue more appropriately once I have learned and am able to include JavaScript.

## Deployment

The project was deployed to GitHub Pages using the following method:
1. Open the [Code Institute Gitpod Template](https://github.com/Code-Institute-Org/gitpod-full-template/)
2. Click [Use this template](https://github.com/Code-Institute-Org/gitpod-full-template/generate/)
3. Provide a Name
4. Provide a Description
5. Choose Public
6. Click 'Create Repository from template'.  GitHub will create the repository and open it.
7. Click 'Settings'
8. Scroll down to 'GitHub Pages'
9. Change Source from 'none' to 'master' and click 'Save'
	
The project was developed using [Gitpod](https://gitpod.io/).  There are no differences between the developed and deployed versions.
	
Running the code locally would involve installing a webhost, downloading the latest [commit](https://github.com/BWeeks101/MP1-B3C/archive/master.zip), then extracting that zip to an appropriate folder to be hosted by the local webhost.
There are far too many potential applications and configurations to list them here in detail.  The site contains HTML, CSS, and JavaScript so should not be complex to host, however I would recommend sticking to the hosted site on [Github Pages](https://bweeks101.github.io/MP1-B3C/).

## Credits

### Content

Much of the menu text was copied from various coffee shop websites, such as
* [Coffee #1](https://www.coffee1.co.uk/menu/)
* [Cafe Nero](https://caffenero.com/uk/menu/coffee/)
* [Starbucks](https://www.starbucks.co.uk/menu)
* [Costa](https://www.costa.co.uk/menu/)
		
All additional text was written from scratch by myself.

### Code
		
During creation of the project, I utilised the following resources to gather example code, then modified it for use on this site:

* CI 'WhiskeyDrop' project (rgba overlay)
* CI 'Resume' project (Form)
* [Bootstrap Navbar Toggler](https://getbootstrap.com/docs/4.5/components/navbar/#toggler)
* [Bootstrap Grid System](https://getbootstrap.com/docs/4.5/layout/grid/#how-it-works)
* [Bootstrap Carousel](https://getbootstrap.com/docs/4.5/components/carousel/) with [Controls](https://getbootstrap.com/docs/4.5/components/carousel/#with-controls/) and [Indicators](https://getbootstrap.com/docs/4.5/components/carousel/#with-indicators/)
* [Bootstrap Live Demo Modal](https://getbootstrap.com/docs/4.5/components/modal/#live-demo/)
		
Rather than rely on in browser form validation (I was not happy with the default response), I utilised the following:
* [Bootstrap Sample Form Validation JavaScript](https://getbootstrap.com/docs/4.5/components/forms/#validation)

		// Example starter JavaScript for disabling form submissions if there are invalid fields
		(function() {
		  'use strict';
		  window.addEventListener('load', function() {
			// Fetch all the forms we want to apply custom Bootstrap validation styles to
			var forms = document.getElementsByClassName('needs-validation');
			// Loop over them and prevent submission
			var validation = Array.prototype.filter.call(forms, function(form) {
			  form.addEventListener('submit', function(event) {
				if (form.checkValidity() === false) {
				  event.preventDefault();
				  event.stopPropagation();
				}
				form.classList.add('was-validated');
			  }, false);
			});
		  }, false);
		})();
						
* NB: GitPod returned a warning with this script, as the 'validation' variable is created, but never read.
	- As this variable is unnecessary for my project, I adjusted line 8 from:
					
			var forms = document.getElementsByClassName('needs-validation');
								
	- to:
								
			document.getElementsByClassName('needs-validation');
							
* Rather than embed the script directly within each html page, I created and included /scripts/bootstrap-form-validation.js

### Media

* Logo Images obtained via Free Trial at [TailorBrands.com](https://www.tailorbrands.com/)
	- logo-size-invert.jpg (Favicon)
	- logotest.png (Logos)
		
* All other Images obtained from [Unsplash](https://unsplash.com/)
	- <span>Photo by <a href="https://unsplash.com/@brookecagle?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Brooke Cagle</a> on <a href="https://unsplash.com/s/photos/barista?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Unsplash</a></span> (Search: Barista)
		- Index.html (Hero Image), Locations.html (Southville Location Image)
			- brooke-cagle-8jp-6SjVibM-unsplash.jpg
			
	- <span>Photo by <a href="https://unsplash.com/@zanbaldwin?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Zan Baldwin</a> on <a href="https://unsplash.com/s/photos/bristol?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Unsplash</a></span> (Search: Bristol)
		- Index.html (CTA Menu Image)
			- zan-baldwin-C64YvmXO_QA-unsplash.jpg

	- <span>Photo by <a href="https://unsplash.com/@samueloakes?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Samuel Oakes</a> on <a href="https://unsplash.com/s/photos/bristol?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Unsplash</a></span> (Search: Bristol)
		- Index.html (CTA Locations Image)
			- samuel-oakes-Fr_XUMvQ9AU-unsplash.jpg
			
	- <span>Photo by <a href="https://unsplash.com/@mikeyharris?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Mikey Harris</a> on <a href="https://unsplash.com/s/photos/bristol?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Unsplash</a></span> (Search: Bristol)
		- Index.html (CTA Contact Us Image)
			- mikey-harris-zasPTUnrWnI-unsplash.jpg
	
	- <span>Photo by <a href="https://unsplash.com/@thisismatthew?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Matthew Gerrard</a> on <a href="https://unsplash.com/s/photos/bristol-homeless?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Unsplash</a></span> (Search: Bristol Homeless)
		- Index.html (CTA About Image), About.html (Hero Image)
			- matthew-gerrard-JQpe01ira0s-unsplash
	
	- <span>Photo by <a href="https://unsplash.com/@ibrahimboran?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Ibrahim Boran</a> on <a href="https://unsplash.com/s/photos/muffin-coffee?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Unsplash</a></span> (Search: Muffin Coffee)
		-  Menu.html (Cakes Menu Image)
			- ibrahim-boran-weg93vRGgGk-unsplash

	- <span>Photo by <a href="https://unsplash.com/@nate_dumlao?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Nathan Dumlao</a> on <a href="https://unsplash.com/s/photos/cake-and-coffee?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Unsplash</a></span> (Search: Cake and Coffee)
		- Menu.html (Carousel Left Sidebar Image (above 767px), First food menu image (below 768px))
			- nathan-dumlao-z3em1GBRhvY-unsplash
	
	- <span>Photos by <a href="https://unsplash.com/@nate_dumlao?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Nathan Dumlao</a> on <a href="https://unsplash.com/s/photos/coffee?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Unsplash</a></span> (Search: Coffee)
		- Menu.html (Coffee image)
			- nathan-dumlao-KixfBEdyp64-unsplash
		- About.html (Coffee Heart image)
			- nathan-dumlao-ikU3J1nr52w-unsplash 
		- Menu.html (Carousel Right Sidebar Image (above 767px), First drink menu image (below 768px))
			- nathan-dumlao-c2Y16tC3yO8-unsplash
			
	- <span>Photo by <a href="https://unsplash.com/@nhillier?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Nick Hillier</a> on <a href="https://unsplash.com/s/photos/coffee-shop?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Unsplash</a></span> (Search: Coffee Shop)
		- Locations.html(Clifton Village Location Image)
			- nick-hillier-xBXF9pr6LQo-unsplash
			
	- <span>Photo by <a href="https://unsplash.com/@jcrod?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Joshua Rodriguez</a> on <a href="https://unsplash.com/s/photos/coffee-shop?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Unsplash</a></span> (Search: Coffee Shop)
		- Locations.html(Horfield Location Image)
			- joshua-rodriguez-f7zm5TDOi4g-unsplash
			
	- <span>Photo by <a href="https://unsplash.com/@wadeaustinellis?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Wade Austin Ellis</a> on <a href="https://unsplash.com/s/photos/coffee-shop?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Unsplash</a></span> (Search: Coffee Shop)
		- Locations.html(Totterdown Location Image)
			- wade-austin-ellis-4YApsoSaNKA-unsplash
			
### Acknowledgements

* Site Design inspired in part by [Coffee #1](https://www.coffee1.co.uk/)
		
* The CI Slack Community
	- Bim Williams (`@Mr_Bim_alumni`) and Anthony O'Brien (`@Anthony`) for pointers regarding images resizing and maintaining aspect ratio, general advice and feedback
	- Jim Morel (`@JimLynx_Lead`) for general advice and feedback
	- Igor Basuga (`@igor_ci`) for advice regarding code comments in conjunction with readme credits
	- Everyone who responded to my requests for code review and silly questions!!
		
### Research:

* CI Course Material and example projects
* W3C Schools [CSS](https://www.w3schools.com/css/default.asp/) and [HTML](https://www.w3schools.com/html/default.asp/) Documentation
* [Bootstrap](https://getbootstrap.com/docs/4.5/getting-started/introduction/) Documentation
* MDN web docs ([CSS](https://developer.mozilla.org/en-US/docs/Web/CSS/), [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML/), [Colour Picker](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Colors/Color_picker_tool))
* [Adobe Colour Wheel](https://color.adobe.com/create/color-wheel/)
* [Canva.com Colour Wheel](https://www.canva.com/colors/color-wheel/)
* Flex based Sticky Footer Method
	- [CSS-Tricks.com](https://css-tricks.com/couple-takes-sticky-footer/)
	- [philipwalton.github.io](https://philipwalton.github.io/solved-by-flexbox/demos/sticky-footer/)
* [Stack Overflow](https://stackoverflow.com/)*
			
	*It is almost impossible to search for any coding related issue online without encountering Stack Overflow links towards the top of the results.  Whilst I certainly read Stack Overflow when researching solutions to challenges, I have not (to the best of my recollection or per my notes) utilised any code directly, in whole or in part.
