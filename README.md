# Wales Marathi Society Website
###### Code Institute / User-Centric Front-End Development / Milestone Project 1
------------
[View Live Project Here][def42]

As a part of Milestone Project 1 to demonstrate an understanding of user-centric Front-End Development, I have designed and deployed this website for a local public group for the Marathi Society residing in Wales. 
Wales Marathi Society is a site that serves as a point of contact for people residing wales from Marathi speaking community of India. We are a social, non-political, community-driven organisation for all Marathi speaking population who are also residents of Wales. We are run by the members of our community coming together to celebrate our cultural traditions. This site is advertises the available benefits of being a memeber and the events organised by the Wales Marathi Society. This site targets first time visitors to feel excited about joining the society and partake in activities Organised which are promotes Marathi culture and also to returning users to be able to acess photographs from previous events and to find out about upcoming events.

![Screenshot][def24]

## **Index - Table of Contents**
------------

+ [User Experience (UX)](#-user-experience-ux)
	* [User Stories](#user-stories)
		- [First Time Visitor Goals](#a-first-time-visitor-goals)
		- [Returning Visitor Goals](#b-returning-visitor-goals)
		- [Frequent User Goals][def2]		
+ [UX Planes](#ux-planes)
	* [Strategy](#strategy)
		- [Project Goals](#project-goals) 
		- [Customer Goals](#customer-goals)
		- [Company Goals](#company-goals)
		- [Future Implementations][def3]
	* [Scope](#scope)
	* [Structure](#structure)
	* [Skeleton](#skeleton)		
	* [Surface](#surface)
		- [Colour Scheme](#colour-scheme)
		- [Typography](#typography)
		- [Imagery](#imagery)
+ [Structure and Features](#structure)
	* [Home Page](#home-page)
		- [Features](#home-page-features)
			- [F1.1 Navigation Bar](f11-navigation-bar)
			- [F1.2 Landing Page](f22-landing-page)
			- [F1.3 Information Cards](f13-information-cards)
			- [F1.4 Footer](f14-footer)
	* [Events Page](#events-page)
		- [Features](#events-page-features)
			- [F2.1 Navigation Bar](f21-navigation-bar)
			- [F2.2 Event Details](f22-event-1)
			- [F2.3 Event Details](f23-event-2)
			- [F2.4 Footer](f24-footer)
	* [Gallery Page](#gallery-page)
		-  [Features](#gallery-page-features)
			- [F3.1 Navigation Bar](f31-navigation-bar)
			- [F3.2 Event Title](f32-event-title)
			- [F3.3 Photograph Grid](f33-photograph-grid)
			- [F3.4 Event Title](f34-event-title)
			- [F3.5 Photograph Grid](f35-photograph-grid)
			- [F3.6 Event Title](f36-event-title)
			- [F3.7 Photograph Grid](f37-photograph-grid)
			- [F3.8 Footer](f38-footer)
	* [Contact Page](#contact-page)
		- [Features](#contact-page-features)
			- [F4.1 Navigation Bar](f41-navigation-bar)
			- [F4.2 Contact Form](f42-contact-form)
			- [F4.3 Flipped Hero Image](f43-flipped-hero-image)
			- [F4.4 Footer](f44-footer)
	* [Thank You Page](#thank-you-page)
		- [Features](#thank-you-page-features)
			- [F5.1 Navigation Bar](#f51-navigation-bar)
			- [F5.2 Confirmation Message](#f52-confirmation-message)
			- [F5.3 Flipped Hero Image](#f53-flipped-hero-image)
			- [F5.4 Footer](#f54-footer)
	* [How These Features Support the User Stories](#how-these-features-support-the-user-stories)
+ [Technologies Used](#technologies-used)
	* [Languages Used](#languages-used)
	* [Frameworks, Libraries and Programs Used](#frameworks-libraries-and-programs-used)
+ [Testing](#testing)
	* [Validator Testing](#validator-testing)
		 - [HTML Validator](#html-validator)
			- [HTML Results index.html](#html-results-indexhtml)
			- [HTML Results events.html](#html-results-eventshtml)
			- [HTML Results gallery.html](#html-results-galleryhtml)
			- [HTML Results contact.html](#html-results-contacthtml)
			- [HTML thankyou.html](#html-results-thankyouhtml)
		 - [CSS Validator](#css-validator)
			- [CSS Results](#css-results)
	* [Lighthouse Testing](#lighthouse-testing)
		- [Results](#results)
		- [Repairs to Optimize](#repairs-to-optimize)
+ [Browser Compatibility](#browser-compatibility)
+ [Known Bugs](#known-bugs) 
+ [Deployment and Cloning](#deployment-and-cloning)
+ [Credits](#credits)
+ [Gratitude](#gratitude)

## **User Experience (UX)**
------------

- ### User stories
As a User from all different age groups and technical abilities I want the website not to be complicted and too busy.
- #### A. First Time Visitor Goals
	1. As a First Time Visitor, I want to feel at home and find cultural references to gain assurance of what the name of society promotes.
	2. As a First Time Visitor, I want to be able to easily find out about activities run by the organisation.
	3. As a First Time Visitor, I want to be able to easily show my interest in becoming a member.
	4. As a First Time Visitor, I want to be able to easily navigate through the website to access various pages and return to homepage.
	5. As a First Time Visitor, I want to be able to put up my questions to the organisation (whilst knowning that my query has been sent) to help me settle in foreign country far from home.
	6. As a First Time Visitor, I want to be able to see photographs of previous events organised.
	7. As a First Time Visitor, I want to be able to join social media groups of the society easily.

-   #### B. Returning Visitor Goals
	1. As a returning visitor, I want to be able to access and view the upcoming event details, photographs and query pages quickly.
	2. As a Returning Visitor, I want to be able to submit a query for renewing my membership whilst be assured that by query has been received.
	3. As a Returning Visitor, I want to be able to keep track of upcoming events.

-   #### C. Frequent User Goals
	1. As a Frequent User, I want to be able to easily find out about upcoming events and submit any queries.
## **UX Planes**
------------
- ### **Strategy**
	* Wales Marathi Society is a site that serves as a point of contact for people residing wales from Marathi speaking community of India.
	* Keep it simple yet smart and accessible to audience of all ages and technical abilities.
+ #### Project Goals
	* As a User from all different age groups and technical abilities I want the website not to be complicted and too busy.
+ #### Customer Goals
	* Being able to access all devices
+ #### Company Goals
	* To have an online presence.
	* Is to increase membership and retain members and be able to market upcoming events.
	* Provide a point of contact for existing memebers and new users to post their queries and interest to the organisation.
	* Flaunt all event photographs.
	* In order to retain membership advertise upcoming events.
	* Increase our social media presence via social media links (Facebook and Instagram).
+ #### Future Implementations
	* Add a full detailed membership link with options for payment.
	* Add an option to register and pay for events.
	* Add FAQ section under contacts.
	* Add Javascript to add collapsible event categories on the Gallery page.
	* Use Javascript to implement a thank you page redirect and return values to an email address.
	* Change Image formats to WebP.
	* Better understand image formats so the pages load quicker and Lighthouse results are most optimised.
- ### Scope
	* Due to constraints of using HTML5 and CSS3, only ensure a simple but accessible layout.
	* The website to be static yet responsive to be available to be accessed on various devices.
	* Continuity is maintained thourghout all pages for better user experience.
	* Navigation links to be made available on all pages for ease.
	* Ensure the website does not exceed more than 5 pages.
	* Due to short time constraint ensure similar structure throughout all pages.
- ### Structure
	* A default home-page that navigates all the pages and provides relevant information about the institution.
	* Categorise pages based on the variety of content that is to be made available to users, as if it were a table of content.
	* Ensure a portal is made available for contact to be made with the administration without having to open another mail agent.
	* User experience to be paramount to outcomes.
- ### Skeleton
	+ #### Wireframes
		* ##### Home Page Wireframes
			![Home Page Wireframe][def4]
		* ##### Events Page Wireframe
			![Events Page Wireframe][def5]
		* ##### Gallery Page Wireframe
			![Gallery Page Wireframe][def6]
		* ##### Contact Page Wireframe
			![Contact Page Wireframe][def7]
		* ##### Thank You Page Wireframe
			![Thank You Page Wireframe][def8]				
- ### Surface
	+ #### Colour Scheme
		* I have used a saffron/rufous palette which is consistent with the cultural representation of the website users and company.
		* Black and red-orange font color plays a good contrast to the chosen colour palette.

		![Colour Scheme][def]

	+ #### Typography
		* The Samarkan font is representative of the Marathi Devnagri script therefore this font was chosen for the logo  text. As this was not available on Google Fonts library, Cdnfonts has been used to import Samarkan font into style.css.
		![samarkan][def43]
		* Google Fonts has been used to import Karma and Playfair fonts into style.css. These have been chosen as they are readable in all font weights and have a simple and modern feel. These fonts also match the mandala hero images used well due to their angled edges.
		**Karma**
		![karma][def45]
		**Playfair**
		![playfair][def44]
	+ #### Imagery
		![heroimage][def46]
		* The chosen Hero image for backgrounds all pages is consistent with the feel of an Indian origin society due to the Mandala patterns.
		* These images have been chosen due to their large clear space of two-thirds area of the image while flaunting a Mandala design on one-third area. The clear space makes all the text aganist it readable while the Mandala design adds aesthetics.
		![footerimage][def48]
		* The Image chosen for footer has a skyline of Mumbai, which is the capital city of Maharashtra. This skyline is set on a saffron background which is consistent to the colour scheme.		
		* ![favicon][def49] The favicon was designed using an online favicon generator. This has been designed with a saffron background with the initials of the organisation 'WMS'
		* All the images used are license free or been used with owners consent. The sources are listed in the Credits section.
		* Images used were compressed using tinyfy tool on the first instance, however, this did not suffice (as reflected in lighthouse testing) Therefore Shrink.media online tool was used to futher compress for better performance and user experience.

## **Structure**
------------
![Home Page][def24]
- ### Home Page
	+ #### Features
		* ##### F1.1 Navigation Bar
			- The navigation....
			![F1.1][def41]
		* ##### F1.2 Landing Page
			- Landing Page image and call to action		
			- Hero section with an image 
			- Each page displays the site Logo, with the page title below - it is for easy user navigation.
			- Below this, there is an animated call-to-action button to view more.
			![F1.2][def47]
		* ##### F1.3 Information Cards
			- 
			- 
			![F1.3][def50]
			![F1.3.][def51]
			![F1.3responsive][def54]
		* ##### F1.4 Footer
			- 
			![F1.4][def53]
![Events Page][def25]
- ### Events Page
	+ #### Features
		* ##### F2.1 Navigation Bar
			- Repeats the same on all pages for consistency in UX.
		* ##### F2.2 Event 1
			- 
			![F2.2][def52]
		* ##### F2.3 Event 2
			- 
			![F2.3][def55]
		* ##### F2.4 Footer
			- Repeats the same on all pages for consistency in UX.
![Gallery Page][def26]
- ### Gallery Page
	+ #### Features
		* ##### F3.1 Navigation Bar
			- Repeats the same on all pages for consistency in UX.
		* ##### F3.2 Event Title
			- 
			![F3.2][def56]
		* ##### F3.3 Photograph Grid
			- 
			![F3.3][def57]
		* ##### F3.4 Event Title
			- 
			![F3.4][def58]
		* ##### F3.5 Photograph Grid
			- 
			![F3.5][def59]
		* ##### F3.6 Event Title
			- 
			![F3.6][def61]
		* ##### F3.7 Photograph Grid
			- 
			![F3.7][def60]
		* ##### F3.8 Footer
			- Repeats the same on all pages for consistency in UX.
![Contact Page][def27]
- ### Contact Page
	+ #### Features
		* ##### F4.1 Navigation Bar
			- Repeats the same on all pages for consistency in UX.
		* ##### F4.2 Contact Form Call-out
			- 
			![F4.2][def62]
		* ##### F4.3 Flipped Hero Image
			- Second image for aesthetically pleasing page and also helps push the footer to the bottom of the page.
			![F4.3][def63]
		* ##### F4.4 Footer
			- Repeats the same on all pages for consistency in UX.
![Thank You Page][def28]
- ### Thank you Page
	+ #### Features
		* ##### F5.1 Navigation Bar
			- Repeats the same on all pages for consistency in UX.
		* ##### F5.2 Confirmation Message
			- 
			![F5.2][def64]
		* ##### F5.3 Flipped Hero Image
			- Second image for aesthetically pleasing page and also helps push the footer to the bottom of the page.
		* ##### F5.4 Footer
			- Repeats the same on all pages for consistency in UX.
- ### How these features support the User Stories
	![Table][def74]
	
- ## **Technologies Used**
------------
+ ### Languages
	* #### HTML5
	* #### CSS3
	* #### Javascript (not by the student but code embedded in libraries used)
+ ### Frameworks, Libraries and Programs Used
	* #### [Cdnfonts][Cdnfonts] : was used to import Samarkan fonts into style.css file which has been used in the Main Logo title.
	* #### [Font Awesome][def9] : was used to add icons for aesthetic and UX purposes. Icons have been used to for social media links which can be easily identified by users regarless of their English language level. Icons have also been used on events page to depict type of event.
	* #### [Git][def10]: was used for version control by utilising the Gitpod terminal to commit to Git and Push to GitHub.
	* #### [GitHub][def11] : It is used as the repository for the project's code after being pushed from Git.
	* #### [Powerpoint][def12] : was used for resizing images and editing photos and screenshots for Readme. It is also used for designing flyers for event pages.
	* #### [Balsamiq][def13] : was used to create the wireframes during the design process.
	* #### [Coolors][def14] : was used to find complimenting colors to saffron for the website color palette.
	* #### [TinyPng][def15] : was used to compress the images that are used in the website, especially on the gallery page.
	* #### [ShrinkMedia by PixelBin.io][def16] : has been used to compress further and resize the images used on the website.
	* #### [Bootstrap][def17] : codes from Bootsrap grid html and Css library has been used in the events.html page to align the coontent in columns and rows.
	* #### [Autoprefixer CSS online][def18] : has been used to parse the CSS in style.css to add different browser prefixes to ensure the CSS works on all browsers.
	* #### [favicon.io][def19] : was used to generate the favicon for the website.
	* #### [W3C Markup Validation Service][def20] : has been used to validate the code on all pages and style.css.
	* #### [UI.Dev][def22] : was used to generate Mockup Screenshots.
	* #### [Free Formatter][def23] : was used to ensure proper indentation in the HTML and CSS codes.
	
- ## **Testing**
------------
+ ### Validating Testing
	* #### HTML Validator
		- HTML Results index.html <br>
		[HTML Full Results - index.html][def65]
		![e][def71]
		- HTML Results events.html <br>
		[HTML Full Results - events.html][def66]
		![e][def72]
		- HTML Results gallery.html <br>
		[HTML Full Results - gallery.html][def67]
		![e][def73]
		- HTML Results contact.html <br>
		[HTML Full Results - contact.html][def68]
		![e][def71]
		- HTML Results thankyou.html <br>
		[HTML Full Results - thankyou.html][def69]
		![e][def71]
	* #### CSS Validator
		- CSS Results : [CSS Full Result][def70]
		![e][def71]
	* #### Lighthouse Testing
	At the first instance the results for performance were very low. Thereafter, on further analysis of it was identified that the image sizes were causing the issue therefore I used Shrink Media website to further compress the images used which resulted in better results.
	Following are screen shots of Lighthouse analysis outcomes before repairs and after repairs
	- #### First Results 
		+ **Home Page Result**
		![**Home Page Result**][def29]
		+ **Events Page Result**
		![**Events Page Result**][def32]	
		+ **Gallery Page Result**
		![**Gallery Page Result**][def31]		 
		+ **Contact Page Result**
		![**Contact Page Result**][def30]
		+ **Thank You Page Result**
		![**Thank You Page Result**][def33]
	- #### Results After Image Were Further Compressed
		+ **Home Page Result**
		![**Home Page Result**][def35]
		+ **Events Page Result**
		![**Events Page Result**][def34]	
		+ **Gallery Page Result**
		![**Gallery Page Result**][def36]
		**Gallery Page Diagnostics to demonstrate the issue are images**
				[!1][def37]
				[!2][def38] 
		+ **Contact Page Result**
		![**Contact Page Result**][def39]
		+ **Thank You Page Result**
		![**Thank You Page Result**][def40]

- ## Browser Compatibility
------------

- ## Known Bugs
------------

- ## Deployment and Cloning
------------- 
+ Deployment:

	* 	In the GitHub repository, navigate to the Settings tab, then choose Pages from the left hand menu

	* Ensure the source section drop down menu is set to the Main Branch

	* Refresh the page and a link to access the page will appear at the top with an option next to it that says "visit page"

	* Any changes pushed to the master branch will take effect on the live project

+ Cloning:

	* visit url - https://github.com/ashwinsel/Milestone-1 this will open the repository on Github
	* Click on the "Code" green coloured button to the right of the screen, click HTTPs and copy the link there
	* Open a GitBash terminal and navigate to the directory where you want to locate the clone
	* On the command line, type "git clone" then paste in the copied url and press the Enter key to begin the clone process


- ## Credits
------------
- ### Content
	* Some of my content on the main page such as 'About Us' is roughly based on Maharashtra Mandal London website.
	* All other content has been drafted by the developer.
- ### Code
	* Code on how to present a 'Call-out' text in front of the Hero Image (on home page, Contact us page) and has been adapted from the Thrive project by Elaine Broche.
	* Code for the hover effect on info cards on Home page was an play around with some examples from  [Codepen][def75]
	* I have used Bootstrap grid classes to implement structure on Events page.
	* Responsive Photo gallery has been created using a tutorial on [Buy me a cofee][def76]
	* Hover effects on throughout has been created by using tutorials on [W3schools](https://www.w3schools.com/cssref/sel_hover.php)

- ### Media
	* [The back-ground Mandal image](./documentation/himage2.png) a vector art by [Matt Cole][def77]
	* [Flyer 1 image on Events Page](./assets/images/flyer1.jpg) a vector art by [Simran Singh](https://www.vecteezy.com/members/firststyles)
	* [Flyer 2 on events page](./assets/images/flyer2.jpg) was created using [Freepik](https://www.freepik.com/)
	All images on Gallery page has been downloaded from [Unsplash](https://unsplash.com/)
	* [Idol of Hindu god Ganesh decorated with flowers](./assets/images/gallery-images/image1.jpg) by [Bhumil Chheda](https://unsplash.com/@bhumil15)
	* [A collection of idols of Hindu god Ganesh ready for sale](./assets/images/gallery-images/image2.jpg) by [Sonika Agarwal](https://unsplash.com/@sonika_agarwal)
	* [Bid idol of Hindu god Ganesh surrounded in red coloured powder flying](./assets/images/gallery-images/image4.jpg) by [Sudarshan Poojary](https://unsplash.com/@sudarshan__poojary)
	* [People carrying decorated idol of Hindu god Ganesh](./assets/images/gallery-images/image3.jpg) by [MA](https://unsplash.com/@miguelalcantara)
	* [A collection of tiny idols of Hindu god Ganesh ready for sale](./assets/images/gallery-images/image5.jpg) by [Mohnish Landge](https://unsplash.com/@mohnishlandge)
	* [Woman in traditional attire holding an idol of Hindu god Ganesh in her palm](./assets/images/gallery-images/image6.jpg) by [RDNE STock Project](https://www.pexels.com/@rdne/)
	* [People in procession coloured in red surrounding a large idol of Hindu god Ganesh](./assets/images/gallery-images/image7.jpg) by [Vishal](https://unsplash.com/@agmt)
	* [Women welcomes Hindu god Ganesh with open arms in air while people carry an idol in a procession on street](./assets/images/gallery-images/image8.jpg) by [Miguel Alcantra](https://unsplash.com/photos/a-person-holding-a-colorful-umbrella--1v0UYGdlaM)
	* [Hindu god Ganesh placed in a beautifully decorated altar](./assets/images/gallery-images/image9.jpg) by [Shubham Bombarde](https://unsplash.com/photos/a-statue-of-an-elephant-in-front-of-a-stage-5TwYdsWlvWg)
	* [Golden bangles, flowers and red coth set on desk ready for Sankranti celebration](./assets/images/gallery-images/image10.jpg) by [Sonika](https://unsplash.com/photos/gold-and-silver-bracelet-on-white-table-m4dagsplsKA)
	* [Indian sweet made of sesame and jaggery aesthetically placed with flowers around](./assets/images/gallery-images/image13.jpg) by [Prchi Palwe](https://unsplash.com/photos/brown-stone-on-black-surface-yK5YeELbbGw)
	* [People gathered around in a hall and some sat around a table to celebrate Sankranti](./assets/images/gallery-images/image14.jpg) by [Wonderlane](https://unsplash.com/photos/woman-sitting-at-table-AwhZjiqNt1U)
	* [Two woman contestants posing and taking a selfie with their phone](./assets/images/gallery-images/image17.jpg) by [Amit Ranjan](https://unsplash.com/photos/woman-in-green-and-black-dress-smiling-xr56_THM_lc)
	* [Hands flaunting freshly applied henna designs](./assets/images/gallery-images/image18.jpg) by [Vitaliy Lyubezhanin](https://unsplash.com/photos/people-hands-with-tattoes-gfVofr15ICc)
	* [Hands with rufous coloured henna designs](./assets/images/gallery-images/image11.jpg) by [Ravi Sharma](https://unsplash.com/photos/women-with-mendhi-tattoos-NNWeEUR88gw)
	* [People gathered on street dressed in white and red traditional attire, ready for a procession](./assets/images/gallery-images/image12.jpg) by [Akash Gurle](https://unsplash.com/photos/a-man-and-woman-in-a-crowd-fZPqUN3QPFY)
	* [Indian savoury cakes made of sago and potato](./assets/images/gallery-images/image16.jpg) by [Prchi Palwe](https://unsplash.com/photos/person-holding-red-raspberry-fruit-mZaW4oV3tnA)
	* 



- ## Gratitude




[Cdnfonts]: https://www.cdnfonts.com/samarkan.font
[def2]: #c-frequent-user-goals
[def3]: future-implementations
[def4]: ./documentation/homepagewireframe.png
[def5]: ./documentation/eventspagewireframe.png
[def6]: ./documentation/gallerypagewireframe.png
[def7]: ./documentation/contactpagewireframe.png
[def8]: ./documentation/thankyoupagewireframe.png
[def9]: https://fontawesome.com/
[def10]: https://ashwinsel-milestone1-shxwdq7nqt6.ws-eu107.gitpod.io/
[def11]: https://github.com/ashwinsel/Milestone-1.git
[def12]: https://www.microsoft.com/en-gb/microsoft-365/powerpoint
[def13]: https://balsamiq.com/
[def14]: https://coolors.co/
[def15]: https://tinypng.com/
[def16]: https://www.shrink.media/upload
[def17]: https://getbootstrap.com/
[def18]: https://autoprefixer.github.io/
[def19]: https://favicon.io/
[def20]: https://validator.w3.org/
[def21]: ./documentation/homepagewireframe.png
[def22]: https://ui.dev/amiresponsive?url=https://ashwinsel.github.io/Milestone-1/index.html
[def23]: https://www.freeformatter.com/html-formatter.html
[def24]: ./documentation/screenshot.png
[def25]: ./documentation/eventsscreenshot.png
[def26]: ./documentation/galleryscreenshot.png
[def27]: ./documentation/contactscreenshot.png
[def28]: ./documentation/thankyouscreenshot.png
[def29]: ./documentation/1lhhome.png
[def30]: ./documentation/1lhcontact.png
[def31]: ./documentation/1lhgallery.png
[def32]: ./documentation/1lhevent.png
[def33]: ./documentation/1lhthankyou.png
[def34]: ./documentation/lheventpage.png
[def35]: ./documentation/lhhomepage.png
[def36]: ./documentation/lhgallerypage.png
[def37]: ./documentary/lhgallerypage1.png
[def38]: ./documentary/lhgallerypage2.png
[def39]: ./documentation/lhcontactpage.png
[def40]: ./documentation/lhthankyoupage.png
[def41]: ./documentation/thankyouscreenshot.png
[def]: ./documentation/colorsch.png
[def42]: https://ashwinsel.github.io/Milestone-1/ "View Live Project Here"
[def43]: ./documentation/samarkan.png
[def44]: ./documentation/playfair.png
[def45]: ./documentation/karma.png
[def46]: ./assets/images/heroimg3.jpg
[def47]: (./documentation/heroimgcallout.pn
[def48]: ./assets/images/footer.jpg
[def49]: ./assets/images/favicon.png
[def50]: ./documentation/cards.png
[def51]: ./documentation/homefeat.png
[def52]: ./documentation/events1.png
[def53]: ./documentation/footerss.png
[def54]: ./documentation/homefeat1.png
[def55]: ./documentation/events2.png
[def56]: ./documentation/eventtitle1.png
[def57]: ./documentation/photogrid1.png
[def58]: ./documentation/eventtitle2.png
[def59]: ./documentation/photogrid2.png
[def60]: ./documentation/photogrid3.png
[def61]: ./documentation/eventtitle3.png
[def62]: ./documentation/contactcallout.png
[def63]: ./documentation/himage2.png
[def64]: ./documentation/thankyoucallout.png
[def65]: https://validator.w3.org/nu/?showsource=yes&showoutline=yes&showimagereport=yes&doc=https%3A%2F%2Fashwinsel.github.io%2FMilestone-1%2F#textarea
[def66]: https://validator.w3.org/nu/?showsource=yes&showoutline=yes&showimagereport=yes&doc=https%3A%2F%2Fashwinsel.github.io%2FMilestone-1%2F#textarea
[def67]: https://validator.w3.org/nu/?showsource=yes&showoutline=yes&showimagereport=yes&doc=https%3A%2F%2Fashwinsel.github.io%2FMilestone-1%2F#textarea
[def68]: https://validator.w3.org/nu/?showsource=yes&showoutline=yes&showimagereport=yes&doc=https%3A%2F%2Fashwinsel.github.io%2FMilestone-1%2F#textarea
[def69]: https://validator.w3.org/nu/?showsource=yes&showoutline=yes&showimagereport=yes&doc=https%3A%2F%2Fashwinsel.github.io%2FMilestone-1%2F#textarea
[def70]: https://validator.w3.org/nu/?showsource=yes&showoutline=yes&showimagereport=yes&doc=https%3A%2F%2Fashwinsel.github.io%2FMilestone-1%2F#textarea
[def71]: ./documentation/homevalresult.jpg
[def72]: ./documentation/eventvalresult.png
[def73]: ./documentation/galleryvalresult.png
[def74]: ./documentation/table1.png
[def75]: https://codepen.io/wikyware-net/pen/abwVORa
[def76]: https://www.buymeacoffee.com/tech2etc
[def77]: https://www.vecteezy.com/members/graphicsrf
