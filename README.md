# Old House New Home
*Milestone 1: User-Centric Frontend Development - Code Institute*

**[Old House New Home](https://coderbeez.github.io/oldhouse-newhome/)** has not been designed as a commercial site. It’s aims are twofold: 

**Homeowner**
The homeowner’s purchase of an older house coincided with redundancy. Thrown into the role of building project manager, she now has a gap in her cv. This website aims to fill this gap by documenting the extension and renovation.

**Website User**
A move to lower carbon lifestyles and more urban living in Ireland, often means older housing stock and/or smaller units. This website aims to help users breathe new life into their older or smaller homes by providing inspiration, practical tips, useful resource links and a point of contact.


## UX

The website is aimed primarily at Irish home buyers or homeowners starting out on an extension or renovation project. It was designed to address some of the problems the homeowner encountered with similar websites when she started her renovation.

1. **Pinterest** Anyone renovating lives on Pinterest. It’s so much easier to add to your Pinterest board if a pin icon is included. On this website the icon is included in the header so it’s always visible.

2. **Suppliers** When you spot something in an online image that’s perfect for your project, there’s often no sourcing information. Supplier links are a huge part of this website, both to specific items featured and more general supplier links in the favourites section. 

3. **Real Life** Some interior design websites are just that – design sites. The homes featured are not meant to be lived in. This website reflects real life by including reviews and opinions throughout – yes the Smeg looks beautiful but try keeping the surface smudge free!


### User Stories

User stories for potential visitors to the website include:

1. **Extending** *I’m looking to extend an existing property.*

I need to come up with a brief for my architect detailing my needs and design preferences. I visit the *extend* section of the website and see a clear list of design considerations, sample drawings and supplier links. I open the lightbox and view images in a larger format as I’m on a mobile. I add a selection of images to my Pinterest page using the *Pinterest save icon* which I can share with my architect. I download and print the drawings using the *download drawings button* to sketch my ideas over. I visit one of the *supplier links*, Resicrete, as I have not considered resin flooring and the homeowner notes it as budget friendly.


2. **Downsizing** *I’m looking to downsize to a smaller space.*

As retired empty nesters we are looking to downsize but are unsure how to make the best use of space in a smaller home. We visit the *small spaces* section of the website. We watch the *embedded video* on sleeping lofts and visit the suppliers site using the *source button*. We save the video to our Pinterest page using the *Pinterest save icon* as this is something our grandchildren would love. We complete the *contact form* asking the homeowner for more information on her experiences purchasing and installing the loft.


3. **Kitchen Remodel** *I’m looking to remodel my kitchen.*

Having lived in the house for a number of years I’ve saved up to remodel my kitchen. I visit the *kitchen* section of the website. I view the *carousel* of kitchen images. The cooker catches my eye. I see the homeowner gave the cooker 3 stars. I click the *review button* to see a breakdown of the review. I then click the *source button* on the review to visit the brands website as I’m interested in a wider 90cm model.


4. **Renovation** *I’m preparing for a renovation.*

After recently closing on a house purchase, I’m looking to plan the renovations. I’m particularly interested in light fittings. I save the light fitting images to my Pinterest page using the *Pinterest save icon*. I visit lighting in the *favourites* section of the website, read the *cards* and visit the supplier links using the *source button*. I complete the *contact form* asking the homeowner where they would recommend sourcing interesting bathroom light fittings.


5. **House Hunting** *I’m currently house hunting.*

I need some inspiration to help me see the potential in the properties I’m viewing. I visit all sections of the website. I save several images to my Pinterest page using the *Pinterest save icon*. I download the drawings using *download drawings* button. I visit some of the supplier links using the *source buttons* in the favourites section. I click on the *Pinterest social icon* to view the homeowners boards.


### Design

The look and feel of the website is designed to reflect the look of the home. 

1. **Hero Image** The hero image of ivy on roofing slates represents an older, maybe forgotten, home.

2. **Colour Palette** A very limited colour palette is used with colours taken from the hero image or chosen to complement it. Blue-black, white and stone are repeated throughout.

3. **Fonts** The fonts chosen, including handwriting and typewriter fonts, reflect the age of the home.

4. **Preparation** Pinterest was used to collect initial design ideas. Balsamiq and Microsoft PowerPoint were used to generate wireframes mock-ups and design mood boards.
   [Wireframe]( https://github.com/coderbeez/oldhouse-newhome/blob/master/wireframes/wireframes.pdf) 
   [Mood Board]( https://github.com/coderbeez/oldhouse-newhome/blob/master/wireframes/moodboards.pdf)
   [Pinterest Board](https://www.pinterest.ie/sullivanedel/milestone1/)


## Features

### Existing Features *Structure*

1. **Navigation Element** This single page website is navigated using a fixed navbar which partially collapses on small screens. The home and contact links within the navbar are represented by icons to help differentiate the menu items. A Pinterest save icon is also included as a menu item. 

2. **Header Element** The website header element contains a hero image, the website name as a h1, and some tagline text. This tagline text moves to the main element on small screens.

3. **Main Element** The main element contains some introductory text followed by five section elements: 
  * *Extension:* The extension section contains drawing images, a list of design dilemmas, an aside element with supplier links, a link to a pdf of drawings, and a lightbox library of six images.
  * *Small Spaces:* The small spaces section contains images and related text under five headings. A YouTube video is embedded under one of the headings. 
  * *Kitchen:* The kitchen section contains a carousel of four images, some introductory text and six product images with star ratings. A review button under each product opens a modal with reviews and a supplier link.
  * *Favourites:* The favourites section contains some introductory text followed by six cards showing product images, text and supplier links.
  * *Contact:* The header hero image and tagline formatting are repeated in the contacts section. The contact form itself contains name, email and query fields followed by a submit button. All fields are required.

4. **Footer Element** The footer element contains social links represented by icons and a link to the developers GitHub profile. 


### Existing Features *Components & Utilities*

1. **Navbar** The [Bootstrap]( https://getbootstrap.com/docs/4.3/components/navbar/) navbar component with [fixed top](https://getbootstrap.com/docs/4.3/utilities/position/#fixed-top) and [collapse](https://getbootstrap.com/docs/4.3/components/collapse/) utilities allow users to always see the navbar best suited to their screen size.

2. **Images** A [Fancy Box](https://fancyapps.com/fancybox/3/) lightbox library and [Bootstrap](https://getbootstrap.com/docs/4.3/components/carousel/) carousel allow users view multiple images without scrolling. A [Pinterest](https://developers.pinterest.com/docs/widgets/save/?) save icon allows users easily add images to their boards. The [Bootstrap]( https://getbootstrap.com/docs/4.3/utilities/borders/) classes of img-thumbnail, rounded-circle and shadow are used to style images throughout the website.

3. **Video** A [Bootstrap](https://getbootstrap.com/docs/4.3/utilities/embed/) embed utility for iframe allows users view a YouTube video. The video can also be easily added to users Pinterest boards using the [Pinterest](https://developers.pinterest.com/docs/widgets/save/?) save icon. 

4. **Cards** The [Bootstrap](https://getbootstrap.com/docs/4.3/components/card/) card component is used in both the kitchen and favourites sections, neatly presenting information to users. 

5. **Modals** [Bootstrap]( https://getbootstrap.com/docs/4.3/components/modal/) modals allow users view kitchen reviews without having to scroll or leave the page.

6. **Progress** The [Bootstrap](https://getbootstrap.com/docs/4.3/components/progress/) progress component allows review information to be represented graphically in modals.

7. **Form** A [Bootstrap](https://getbootstrap.com/docs/4.3/components/forms/) form allows users send queries directly to the homeowner.

8. **Links** [Bootstrap](https://getbootstrap.com/docs/4.3/components/buttons/) buttons and css formatted text links, allow users readily access supplier websites, social links and a pdf of drawings. 

9. **Positioning** The [Bootstrap](https://etbootstrap.com/docs/4.3/utilities/flex/) flex utility is used to position text.

### Existing Features *Responsiveness*

The website was designed using a mobile first approach. While no information is added or deleted depending on screen size, the order and orientation of some elements does change. Media queries together with the Bootstrap grid system and display classes are used to facilitate this responsiveness.

1. **Viewport Width** Using the [Bootstrap](https://getbootstrap.com/docs/4.3/layout/grid/) grid system, the percentage of viewport width used to display content varies from 100% on small screens to 83% (10 Bootstrap columns) on medium screens and 66% (8 Bootstrap columns) on large screens.

2. **Element Width & Position** The [Bootstrap](https://getbootstrap.com/docs/4.3/layout/grid/) grid system is also used to change the width and position of elements on small, medium and large screens to better display content. 

3. **Navbar** A centred and partially collapsed navbar on small screens, expands and changes alignment on medium and large screens. The [Boostrap](https://getbootstrap.com/docs/4.3/components/collapse/) collapse component facilitates the expand and collapse. Media queries are used to alter the navbar margins for medium and large screens and align it with screen contents. 

4. **Display** Using [Bootstrap](https://getbootstrap.com/docs/4.3/utilities/display/) display classes:
   A h1 element with 3 break elements on small screens, is replaced with 2 breaks on medium and large screens.
   A tagline positioned under the hero images on small screens, is positioned over the hero image on medium and large screens.
    A floor plan drawing viewed in portrait on small screens, is viewed in landscape on medium and large screens. 
   A resources aside positioned under the FancyBox lightbox library on small screens, is positioned above and to the right on medium and large screens..

5. **Video & Images** [Bootstrap](https://getbootstrap.com/docs/4.3/utilities/embed/#about) utilities of embed-responsive and img-fluid are used to make both images and embedded iframe responsive.

6. **Margins & Padding** [Bootstrap](https://getbootstrap.com/docs/4.3/utilities/spacing/) spacing utilities are used throughout this website to vary margins and padding by breakpoints.

7. **Font Size** Media queries are used to change font sizes depending on screen size.

8. **REM** REM sizes are used throughout the website to improve responsiveness.


### Future Features 

1. **Projects Page** Creating a separate projects page to document upcoming d.i.y. projects, e.g. building a child’s playhouse in the garden, would encourage repeat visits.
2. **Product Reviews** Creating more product reviews but using a single modal and varying content by button clicked requires jquery (referenced on Bootstrap).


## Technologies Used

1. [Balsamiq](https://balsamiq.com/)  A web based gui mock-up and website wireframe building application, Balsamiq was used to develop wireframes for the website.
2. [Microsoft Powerpoint]( https://office.live.com/start/PowerPoint.aspx) A presentation programme, Microsoft PowerPoint was used to develop mock-ups and mood boards for the website.
3. [Microsoft Publisher]( https://www.microsoft.com/en-ie/p/publisher/cfq7ttc0k7c3?=&OCID=AID737190_SEM_et3dNWB5&MarinID=set3dNWB5|340720498529|microsoft+publisher|e|c||62634787164|aud-312771920869:kwd-11150981&lnkd=Google_O365SMB_Mixed&gclid=EAIaIQobChMIrN6k04Kh4gIVxrDtCh0N7QGzEAAYASAAEgJqDfD_BwE&activetab=pivot%3Aoverviewtab) A desktop publishing application, Microsoft Publisher was used to create the wireframe and drawings pdfs for the website.
4. [Pinterest](https://www.pinterest.ie/) A social media web-based software system designed to enable collecting images and videos, Pinterest was used to collect design inspiration for the website. The Pinterest [Pin](https://developers.pinterest.com/docs/widgets/save/?) save icon is included on this website to assist users collect images from Old House New Home.
5. [Adobe Photoshop Elements](https://www.adobe.com/ie/) A graphics editor, Adobe Photoshop Elements was used to edit website images and identify hero image hex colours for fonts and backgrounds.
6. [Cloud9](https://c9.io/login) An online integrated development environment, Cloud9 was the IDE used for this website.  
7. [Git](https://git-scm.com/) A distributed version-control system for tracking changes in code during development, Git was used to track changes in Cloud9 for this website.
8. [GitHub](https://github.com/) A web-based hosting service for version control using Git, GitHub was used to host the version control system and website content.
9. [HTML5](https://www.w3.org/) A document mark-up language, HTML was the language used to for this website.
10. [CSS3](https://www.w3.org/) A style sheet language, CSS was the style sheet used for this website.
11. [Bootstrap4](https://getbootstrap.com/) A CSS framework directed at responsive, mobile-first front-end web development, Bootstrap is used extensively in this website for layout, styling and adding functionality.
12. [Google Fonts](https://fonts.google.com/) A library of free licensed fonts, Google Fonts is used for all fonts on this website.
13. [Font Awesome](https://fontawesome.com/) A font and icon toolkit, Font Awesome is used to source icons for the navbar menu items, lists and social links on this website.
14. [JQuery](https://jquery.com/) A JavaScript library designed to manipulate HTML documents, JQuery is used by Bootstrap, FancyBox and Pinterest on this website.
15. [JPopper](https://popper.js.org/) A JavaScript library designed to display content from HTML documents, JPopper is used by Bootstrap on this website.
16. [FancyApps Fancybox]( https://fancyapps.com/fancybox/3/) A JavaScript lightbox library for presenting various types of media, Fancybox is used to display a gallery of images on this website.

**Technology explanations from [Wikipedia](https://en.wikipedia.org/wiki/Main_Page)**


## Testing

### Validation

**HTML** 
[W3C Validation Service](https://validator.w3.org/) Used to test the validity of HTML – no errors found.

**CSS**
[W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/) Used to test the validity of CSS – no errors found.


### User Stories

Each of the user stores detailed in UX were tested using various browsers and screens sizes as follows:

| **BROWSER** | **Android** | **iOS** | **iOS** | **Explorer** | **Edge** | **Chrome** | **Firefox** | **Safari** |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| **SCREEN SIZE** | **Small** | **Small** | **Medium** | **Large** | **Large** | **Large** | **Large** | **Large** |
| **USER STORY** | --- | --- | --- | --- | --- | --- | --- | --- |
| **Extending** | --- | --- | --- | --- | --- | --- | --- | --- |
| Extend Menu Item | Y | Y | Y | Y | Y | Y | Y | Y |
| Lightbox Gallery | 1 | 1 | 1 | 1 | 1 | 1 | 1 | 1 |
| Pinterest Save Icon | Y | Y | Y | Y | Y | Y | Y | Y |
| Download Drawings Button | Y | Y | Y | Y | Y | Y | Y | Y |
| Resicrete Supplier Link | Y | Y | Y | Y | Y | Y | Y | Y |
| **Downsizing** | --- | --- | --- | --- | --- | --- | ---| --- |
| Small Spaces Menu Item | Y | Y | Y | Y | Y | Y | Y | Y |
| YouTube Video | Y | Y | Y | Y | Y | Y | Y | Y |
| Small Spaces Source Button | Y | Y | Y | Y | Y | Y | Y | Y |
| Pinterest Save Icon | Y | Y | Y | Y | Y | Y | Y | Y |
| Contact Form | Y | Y | 4 | Y | Y | Y | Y | Y |
| **Kitchen Remodel** | --- | --- | --- | --- | --- | --- | ---| --- |
| Kitchen Menu Item | Y | Y | Y | Y | Y | Y | Y | Y |
| Carousel | Y | Y | Y | Y | Y | Y | Y | Y |
| Review Button | Y | Y | Y | 2| Y | Y | Y | Y |
| Modal Source Button | Y | Y | Y | Y | Y | Y | Y | Y |
| **Renovation** | --- | --- | --- | --- | --- | --- | ---| --- |
| Pinterest Save Icon | Y | Y | Y | Y | Y | Y | Y | Y |
| Favourites Menu Item | Y | Y | Y | Y | Y | Y | Y | Y |
| Favourites Source Button | Y | Y | Y | Y | Y | Y | Y | Y |
| Contact Form | Y | Y | 4 | Y | Y | Y | Y | Y |
| **House Hunter** | --- | --- | --- | --- | --- | --- | ---| --- |
| Small Spaces Menu Item | Y | Y | Y | Y | Y | Y | Y | Y |
| Kitchen Menu Item | Y | Y | Y | Y | Y | Y | Y | Y |
| Favourites Menu Item | Y | Y | Y | Y | Y | Y | Y | Y |
| Contact Menu Item | Y | Y | Y | Y | Y | Y | Y | Y |
| Pinterest Save Icon | Y | Y | Y | Y | Y | Y | Y | Y |
| Download Drawings Button | Y | Y | Y | Y | Y | Y | Y | Y |
| Favourites Source Button | Y | Y | Y | Y | Y | Y | Y | Y |
| Pinterest Social Link | Y | Y | Y | Y | Y | Y | Y | Y |

Y - Passed

1 2 3 4 - Please see **Bugs**


### Manual Site Testing

Throughout the development process, [Chrome Developer Tools]( https://developers.google.com/web/tools/chrome-devtools/) were used to test for responsiveness on various screen sizes. The site was distributed to friends and family for testing on a range of devices. The site has also been reviewed on the Slack Peer Review channel. 

Structured testing of the site was carried out as follows:

| **BROWSER** | **Android** | **iOS** | **Chrome** | 
| --- | --- | --- | --- | 
| **SCREEN SIZE** | **Small** | **Medium** | **Large** | 
| Favicon | Y | N/A | Y | 
| Navbar Hover | N/A | N/A | Y | 
| Navbar Collapse | Y | N/A | N/A | 
| Navbar Links | Y | Y | Y | 
| Navbar Pinterest| Y | Y | Y |
| Header H1 Font Size | Y | Y | Y | 
| Header H1 Breaks | Y | Y | Y | 
| Header Tagline Position | N/A | Y | Y | 
| Header Tagline Font Size | N/A | Y | Y | 
| Intro Tagline Position| Y | N/A | N/A | 
| Intro Tagline Font Size| Y | N/A | N/A | 
| Extend H2 Font Size  | Y | Y | Y |
| Extend Floor Plan Orientation  | Y | Y | Y |
| Extend Design Dilema H3 Font Size  | Y | Y | Y |
| Extend Lightbox | 1 | 1 | 1 | 
| Extend Resources Position | Y | Y | Y |
| Extend Resources Links Hover | Y | Y | Y |
| Extend Resources Links | Y | Y | Y |
| Extend Resources Download Drawings Button Hover | Y | Y | Y | 
| Extend Resources Download Drawings Button | Y | Y | Y | 
| Small Spaces Layout | Y | Y | Y |
| Small Spaces Source Buttons | Y | Y | Y | 
| Small Spaces Video  | Y | Y | Y |
| Kitchen Carousel | Y | Y | Y | 
| Kitchen Cards Layout | Y | Y | Y | 
| Kitchen Cards | Y | Y | Y | 
| Kitchen Cards Review Buttons | Y | Y | Y | 
| Kitchen Modals | Y | Y | Y | 
| Kitchen Modal Source Buttons | Y | Y | Y | 
| Kitchen Modal Close Buttons | Y | Y | Y | 
| Favourites Cards Layout | Y | Y | Y |
| Favourites Cards | Y | Y | Y |
| Favourites Cards Source Buttons | Y | Y | Y |
| Contact Us Layout | Y | Y | Y | 
| Contact Us Form Input Types | Y | Y | Y | 
| Contact Us Form Inputs Required | Y | 4 | Y | 
| Contact Us Form Submit Button | Y | Y | Y | 
| Footer Layout | Y | Y | Y | 
| Footer Social Links Hover | Y | Y | Y | 
| Footer Social Links | Y | Y | Y | 
| Footer CoderBeez Link Hover | Y | Y | Y | 
| Footer CoderBeez Link | Y | Y | Y | 


Y - Passed

1 2 3 4 - Please see **Bugs**


### Bugs

1. **Fancybox** On all browsers and screen sizes, Fancybox does not always work properly if you try to swipe rather than use the Fancybox arrows. As this bug could not be fixed, text was added to advise users to use the arrows.

2. **Internet Explorer** When initially tested on Explorer, kitchen cards had additional heights and favourites cards were out of position. Although amending Bootstrap col classes in favourites cards from “col” to “col-12” fixed the position problem, no fix has been found for the kitchen cards.

3. **Background-Attachment: Fixed** Initially the hero image had both background-attachment: fixed and background-size: cover attributes set. Unfortunately, on any iOS device, the image was distorted. The site [CanIUse](https://caniuse.com/#search=background-attachment), recommended by Code Institute tutor support, confirmed the issue. The only fix available did not work on this website so the background-attachment attribute was removed from the hero image.

4. **Contact Form – Email Field** During testing it was noted the error message on the email field is covered by the keyboard on a ipad in landscape view. No fix has been found.


## Deployment

The website was developed in Cloud9, ??? using Git and pushed to the hosting platform GitHub.
To following steps were taken to deploy to GitHub:
1. Opened the oldhouse-newhome *repository*.
2. Ensured the *master branch* was present.
3. Ensured the *html page* was named *index.html*.
4. Ensured the *readme.md* had some text.
5. Clicked the *settings* tab.
3. Under *github pages* selected *master branch* as *source*.
5. *”Your site is published at (https://coderbeez.github.io/oldhouse-newhome/)”* became visible in the *github pages* header after approximately 5 minutes.

### Cloning 

As this is not something covered to date, the following instructions were taken from [GitHib Help]( https://help.github.com/en/articles/cloning-a-repository).
1. Open the [oldhouse-newhome](https://github.com/coderbeez/oldhouse-newhome) repository.
2. Click the *clone or download* button.
3. In the *clone with HTTPs* pop-up, click copy icon.
4. Open *git bash*.
5. Change the current working directory to where you want the cloned directory to be made.
6. Type *git clone* and paste the URL copied earlier.
7. Press *enter*. 


## Credits

### Content

  * All text created by the homeowner.
  * Extension design and architectural drawings by [Colette O’Sullivan (Architectural Technician & Interior Designer)](https://www.linkedin.com/in/colette-o-sullivan-983662a2/).

### Media

  * Hero image from [Drew Beamer - Unsplash](https://unsplash.com/@drew_beamer?utm_medium=referral&utm_campaign=photographer-credit&utm_content=creditBadge)
  * Favicon image from [Pixabay](https://pixabay.com/photos/ivy-ivy-leaf-green-leaf-green-2866933/)
  * Kitchen product photos from supplier websites:
   [Silestone](https://www.silestone.com/ie/)
   [Aarke](https://www.aarke.com/)
   [Fisher Paykal](https://www.fisherpaykel.com/ie/)
   [Smeg](https://www.smeg.ie/)
   [Bosch](https://www.bosch-home.ie/)
   [Ikea](https://www.ikea.com/ie/en/)
  * Embedded YouTube video from [TecroStar](https://www.youtube.com/channel/UCm5nGcJY7yw18J1YCWqRAYw) 
  * Home photographs taken by the homeowner.

### Code
  * Shadow css from [CodePen](Shadow code from https://codepen.io/sdthornton/pen/wBZdXq
gradients)
  * Linear-gradient css from [w3schools](https://www.w3schools.com/css/css3_gradients.asp)
  * Double border css from [Stack Overflow](https://stackoverflow.com/questions/21074202/create-a-button-with-a-double-border)
  * CSS to remove outline from [Stack Overflow](https://stackoverflow.com/questions/50668594/removing-the-border-color-of-the-navbar-toggler-hamburger-icon-bootstrap-4/50668740*/)

### Acknowledgements
  * This project has been brought to you by Slack. Thanks to all my fellow Slack students! Eternally grateful to our channel lead Anna, and her mentor Simen, for clearing the fog and pointing us all in the right direction.
  * A special thanks to Jack for giving up some of his laptop time so mam could work on her project.

### Disclaimer
  * This site is for educational purposes only.
