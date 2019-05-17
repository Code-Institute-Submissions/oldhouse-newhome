#Old House New Home
*Milestone 1: User-Centric Frontend Development - Code Institute*
Old House New Home has not been designed as a commercial site. It’s aims are twofold: 

**Homeowner**
The homeowner’s purchase of an older house coincided with redundancy. Thrown into the job of project manager, tiler and painter left her with a gap in her cv. This website aims to fill this gap, documenting the extension and renovation.

**Website User**
As part of the desire for lower carbon lifestyles, we are seeing a move to more urban living. In Ireland, this often means older housing stock and/or smaller units. This website aims to help users breathe new life into their older or smaller homes by providing inspiration, practical tips, useful resource links and a point of contact.

##UX
The website is aimed primarily at Irish home buyers or homeowners starting out on an extension or renovation project. It was designed to address some of the problems the homeowner encountered with similar websites when she started her renovation.
1.	**Pinterest** Anyone renovating lives on Pinterest. It’s so much easier to add to your Pinterest page if the pin icon is included on a web page. In this website the icon is included in the header so it’s always visible.
2.	**Suppliers** When you spot something in an online image that’s perfect for your project there’s often no sourcing information. Supplier links are a huge part of this website, both to specific items featured and more general supplier links in the favourites section. 
3.	**Real Life** Some of the interior design sites out there are just that – design sites. The homes featured are not meant to be lived in. This website reflects real life by including reviews and opinions throughout – yes the Smeg looks beautiful but try keeping the surface smudge free!

###User Stories
User stories for potential visitors to the website include:
1.**Extending** *I’m looking to extend an existing property.*
I need to come up with a brief for my architect detailing my needs and design preferences. I visit the *extend* section of the website and see a clear list of design considerations, sample drawings and supplier links. I add a selection of images to my Pinterest page using the *Pinterest save icon* which I can share with my architect. I download and print the drawings using the *download drawings button* to sketch my ideas over. I visit one of the *supplier links*, Resicrete, as I have not considered resin flooring and the homeowner notes it as budget friendly.
2.**Downsizing** *I’m looking to downsize to a smaller space.*
As retired empty nesters we are looking to downsize but are unsure how to make the best use of space in a smaller home. We visit the *small spaces* section of the website. We watch the *embedded video* on sleeping lofts and visit the suppliers site using the *source button*. We save the image of the loft to our Pinterest page using the *Pinterest save icon* as this is something our grandchildren would love. We complete the *contact form* asking the homeowner for more information on her experiences purchasing and installing the loft.
3.**Kitchen Remodel** *I’m looking to remodel my kitchen.*
Having lived in the house for a number of years I’ve saved up to remodel my kitchen. I visit the *kitchen* section of the website. I view the *carousel* of kitchen images. The cooker catches my eye. I see the homeowner gave the cooker 3 stars. I click the *review button* to see a breakdown of the review. I then click the *source button* on the review to visit the brands website as I’m interested in a wider 90cm model.
4.**Renovation** *I’m preparing for a renovation.*
After recently closing on a house purchase, I’m looking to plan the renovations. I’m particularly interested in light fittings. I save the light fitting images to my Pinterest page using the *Pinterest save icon*. I visit lighting in the *favourites* section of the website, read the *cards* and visit the supplier links using the *source button*. I complete the *contact form* asking the homeowner where they would recommend sourcing interesting bathroom light fittings.
5.**House Hunting** *I’m currently house hunting.*
I need some inspiration to help me see the potential in the properties I’m viewing. I visit all sections of the website. I save several images to my Pinterest page using the *Pinterest save icon*. I download the drawings using *download drawings* button. I visit some of the supplier links using the *source buttons*.
###Design
The look and feel of the website was designed to reflect the look of the home. 
1.**Hero Image** The hero image of ivy on roofing slates represents an older, maybe forgotten, house.
2.**Colour Palette** A very limited colour palette was used with colours either taken from the hero image or chosen to complement it. Blue-black, white and stone are repeated throughout.
3.**Fonts** The fonts used are chosen to give a feeling of an older time with handwriting and typewriter fonts.
4.**Preparation** Pinterest was used to collect design ideas. Balsamiq and Microsoft Powerpoint were used to generate wireframes and mockups. [Wireframe]( https://github.com/coderbeez/oldhouse-newhome/blob/master/wireframes/wireframes.pdf) [Mood Board]( https://github.com/coderbeez/oldhouse-newhome/blob/master/wireframes/moodboards.pdf) [Pinterest Board](https://www.pinterest.ie/sullivanedel/milestone1/)
##Features
###Existing Features- Structure
1.**Navigation** – This single page website is navigated using a [Bootstrap]( https://getbootstrap.com/docs/4.3/components/navbar/) navbar in a nav element. The home and contact links within the navbar are represented by [FontAwesome]( https://fontawesome.com/) icons to help differentiate menu items. A [Bootstrap](https://getbootstrap.com/docs/4.3/utilities/position/#fixed-top) fixed top class means the navbar is always visible.
2.**Header** The website header element contains a hero image, h1 and tagline text. The [Bootstrap](https://getbootstrap.com/docs/4.3/utilities/flex/) flex utility is used to position the text over the hero image. This tagline text moves to the main element on small screens.
3.**Main** The main element consists of some introductory text followed by 5 section elements: 
  *Extension*: drawing images, design dilemma text and icons, aside element with supplier links, link to pdf of drawings, lightbox library.
  *Small Spaces*: images and related text, embedded YouTube video.
  *Kitchen* - carousel of images, introductory text, 6 product images with star ratings displayed using cards, links to review modals, links within modals to suppliers.
  *Favourites*: introductory text, 6 cards showing product images, text and supplier links.
  *Contact*: tagline text, contact form with name, email and query fields.
4.**Footer**The footer contains social links represented by [Font Awesome](https://fontawesome.com/) icons and a link to the developers GitHub profile. 

###Existing Features- Components 
1.**Images** A [Fancy Box](https://fancyapps.com/fancybox/3/) lightbox library and [Bootstrap](https://getbootstrap.com/docs/4.3/components/carousel/) carousel allow users view multiple images without scrolling. A [Pinterest] save icon allows users easily add images to their boards. The [Bootstrap]( https://getbootstrap.com/docs/4.3/utilities/borders/) classes of img-thumbnail, rounded-circle and shadow are used to style images throughout the website.
2.**Video** A [Bootstrap](https://getbootstrap.com/docs/4.3/utilities/embed/) embed utility for iframe allows users view a YouTube video without leaving the website. The video can also be easily added to users Pinterest boards using the Pinterest save icon. 
3.**Cards** The [Bootstrap](https://getbootstrap.com/docs/4.3/components/card/) card component, used in both the kitchen and favourites sections, neatly presents information to users. 
4.**Modals** [Bootstrap]( https://getbootstrap.com/docs/4.3/components/modal/) modals allow users view kitchen reviews without having to scroll or leave the page.
5.**Form** A [Bootstrap](https://getbootstrap.com/docs/4.3/components/forms/) contact form allows users send queries directly to the homeowner.
6.**Links** Prominent source [Bootstrap]( https://getbootstrap.com/docs/4.3/components/buttons/) buttons and text links allow users readily access supplier websites, social links and a pdf of drawings. 
###Existing Features- Responsiveness 
The website was designed using a mobile first approach. While no information is added or deleted depending on screen size, the order and orientation of some elements changes. Media queries together with the Bootstrap grid system and display classes are used to facilitate this responsiveness.

1.**Viewport Width** Using the [Bootstrap](https://getbootstrap.com/docs/4.3/layout/grid/) grid system, the percentage of viewport width used to display content varies from 100% on small screens to 83% (10 Bootstrap columns) on medium screens and 66% (8 Bootstrap columns).
2. **Element Width & Position** The [Bootstrap](https://getbootstrap.com/docs/4.3/layout/grid/) grid system is also used to change the width and position of elements on small, medium and large screens to better display content. 
3. **Navbar** A centred and partially collapsed navbar on small screens, expands and changes alignment on medium and large screens. The [Boostrap]( https://getbootstrap.com/docs/4.3/components/collapse/) collapse component facilitates the expand and collapse. Media queries are used to alter the navbar margins for medium and large screens. 
4. **Tagline** Using [Bootstrap]( https://getbootstrap.com/docs/4.3/utilities/display/) display classes, the tagline positioned under the hero images on small screens, is positioned over the hero image on medium and large screens.
5. **Floor Plan Image** Using [Bootstrap]( https://getbootstrap.com/docs/4.3/utilities/display/) display classes, the floor plan drawing viewed in portrait on small screens, is viewed in landscape on medium and large screens. 
6. **Resources Aside** Using [Bootstrap]( https://getbootstrap.com/docs/4.3/utilities/display/) display classes, the resources aside positioned under the FancyBox lightbox library on small screens, is positioned above and to the right on medium and large screens..
7. **Video & Images** [Bootstrap] class are used to make the images responsive Bootstrap embed utilities are used to make the video responsive.
8. **Margins & Padding** Bootstrap]( https://getbootstrap.com/docs/4.3/utilities/spacing/) spacing utilities are used to throughout this website to vary margins and padding by breakpoints.
9.**Font Size** Media queries are used to change font sizes depending on screen size.
10. **REM** REM sizes are used throughout the website to be more responsive.

###Future Features 
1.	Projects section to document future diy, e.g. garden, child’s playhouse.
2.	More product reviews – using Modals requires javascript

##Technologies Used
1.[Balsamiq](https://balsamiq.com/)  A web based gui mockup and website wireframe building application, Balsamiq was used to develop wireframes for the website.
2.[Microsoft Powerpoint]( https://office.live.com/start/PowerPoint.aspx) – A presentation programme, Microsoft PowerPoint was used to develop mockups and mood boards for the website.
3.[Microsoft Publisher]( https://www.microsoft.com/en-ie/p/publisher/cfq7ttc0k7c3?=&OCID=AID737190_SEM_et3dNWB5&MarinID=set3dNWB5|340720498529|microsoft+publisher|e|c||62634787164|aud-312771920869:kwd-11150981&lnkd=Google_O365SMB_Mixed&gclid=EAIaIQobChMIrN6k04Kh4gIVxrDtCh0N7QGzEAAYASAAEgJqDfD_BwE&activetab=pivot%3Aoverviewtab) – A desktop publishing application, Microsoft Publisher was used to create the wireframe and drawings pdfs for the website.
4.[Pinterest](https://www.pinterest.ie/) A social media web based software system designed to enable collecting images and videos, Pinterest was used to collect design inspiration for the website.
5.[Adobe Photoshop Elements](https://www.adobe.com/ie/) A graphics editor, Adobe Photoshop Elements was used to edit the website images and identify the hex colours in the hero image used for fonts and backgrounds.
6.[Cloud9](https://c9.io/login) An online integrated development environment, Cloud9 was the IDE used for this website.  
7.[Git](https://git-scm.com/) A distributed version-control system for tracking changes in source code during software development, Git was used to track changes locally in Cloud for this website.
8.[GitHub](https://github.com/) A web-based hosting service for version control using Git, GitHub was used to host ????
9.[HTML5](https://www.w3.org/) a software solution stack that defines the properties and behaviours of web page content by implementing a markup based pattern to it, HTML was the language used to write????
10.[CSS3](https://www.w3.org/) a style sheet language used for describing the presentation of a document written in HTML, CSS was used to apply styles to this websites HTML.
11.[Bootstrap4](https://getbootstrap.com/) a CSS framework directed at responsive, mobile-first front-end web development, Bootstrap was used extensively in this website for layout, styling and adding functionality.
12.[Google Fonts](https://fonts.google.com/) a library of free licensed fonts, Google Fonts was used for all fonts on this website.
13.[Font Awesome](https://fontawesome.com/) a font and icon toolkit, Font Awesome was used to source icons for the navbar menu items, list icons and social icons on this website.
14.[JQuery](https://jquery.com/) a JavaScript library designed to simplify HTML DOM tree traversal and manipulation, as well as event handling, CSS animation, and Ajax
15.[JPopper]
16.[FancyApps Fancybox]( https://fancyapps.com/fancybox/3/) a JavaScript lightbox library for presenting various types of media,  Fancybox was used to display a gallery if images on this website.
17.[Pinterest Widget](https://developers.pinterest.com/docs/widgets/save/?)**
**Technology explanations from [Wikipedia](https://en.wikipedia.org/wiki/Main_Page)**

##Testing
9.[Chrome Developer Tools](https://developers.google.com/web/tools/chrome-devtools/)
allow web developers to test and debug their code

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.
Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.
For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:
1.	Contact form: 
i.	Go to the "Contact Us" page
ii.	Try to submit the empty form and verify that an error message about the required fields appears
iii.	Try to submit the form with an invalid email address and verify that a relevant error message appears
iv.	Try to submit the form with all inputs valid and verify that a success message appears.
In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.
You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.
Background-attachment fixed- whiskey drop
[Stack Overflow](https://stackoverflow.com)
If this section grows too long, you may want to split it off into a separate file and link to it from here.
Deployment
This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).
In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:
•	Different values for environment variables (Heroku Config Vars)?
•	Different configuration files?
•	Separate git branch?
In addition, if it is not obvious, you should also describe how to run your code locally.
##Credits
###Content
  *All text created by the homeowner and edited by [Enzo Consulting]( https://www.enzoconsultancy.com/).
  *Architectural drawings provided by Colette O’Sullivan (Architectural Technician and Interior Architect).
###Media
  *Hero image from [Drew Beamer - Unsplash](https://unsplash.com/@drew_beamer?utm_medium=referral&utm_campaign=photographer-credit&utm_content=creditBadge)
  *Favicon image from [Pixabay](https://pixabay.com/photos/ivy-ivy-leaf-green-leaf-green-2866933/)
  *Kitchen product photos from supplier websites:
[Silestone Worktop](https://www.silestone.com/ie/)
[Aarke Carbonator](https://www.aarke.com/)
[Fisher Paykal Fridge](https://www.fisherpaykel.com/ie/)
[Smeg Cooker](https://www.smeg.ie/)
[Bosch Microwave](https://www.bosch-home.ie/)
[Ikea Sink](https://www.ikea.com/ie/en/)
  *Embedded YouTube video from [TecroStar Channel]( https://www.youtube.com/channel/UCm5nGcJY7yw18J1YCWqRAYw) 
  *Home photographs taken by the homeowner.
###Code
  *Shadow code from [CodePen](Shadow code from https://codepen.io/sdthornton/pen/wBZdXq
gradients)
  *Linear-gradient code from [w3schools](https://www.w3schools.com/css/css3_gradients.asp)
  *Double border css from [Stack Overflow](https://stackoverflow.com/questions/21074202/create-a-button-with-a-double-border)
###Acknowledgements
  *This project has been brought to you by Slack. Thanks to all my fellow Slack students! Eternal gratitude to our channel lead Anna, Mother of Zeus, and her mentor Simene, for clearing the fog and pointing us all in the right direction.
  *A special thanks to Jack for giving up some of his laptop time so mam could work on her project.

###Disclaimer
  *This site is for educational purposes only.
