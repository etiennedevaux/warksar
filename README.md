README.md

# Website Title: Warwickshire Search and Rescue

## Version Details
HTML Version: 0418;
CSS Version: 0748;
JavaScript Version: 0039;

## 1  The Warwickshire Search and Rescue User Experience

**NB The video recordings may not reflect the exact screens as text, images and configuration may have had minor changes in response to user feedback.  No changes have been made that alter the four key user journeys.**

The key purpose of the Warwickshire Search and Rescue (Warksar) site it to reach out to the public in general.  The team members will mainly communicate and interact with each other via internal online services.  

The agreed strategic goals for the site are to Inform, Communicate and Engage.  Engagement will include support, participation and donations.

The user journey is based on four personae, people coming to the site, who simply, at this stage want to find out more information, but need to nurtured as potential future contributors, members, donors or maybe all three.

This leads us to 4 critical user journeys, all of which start from the Home Page

### 1.1 The Home Page
[**Home Page Demonstration**](https://youtu.be/bswPg6mYZAc)

### 1.2 Information Seekers
[*Demonstration for Users Seeking Information*](https://youtu.be/nghCxQIYFRs)

For most of the public in general they may have had little reason to have come across Warksar, but have now heard about it and would like to know more.  These people are potential donors, members and collaborators - but for now need to be nurtured rather than directed.

The Call to Action gives these people a prompt to the About - What We Do section.  All navigation remains either directly visible, or within a single click on a dropdown.  At most this user is two clicks from any part of the site.

### 1.3 Queries
[*Demonstration for Users with Specific Queries*](https://youtu.be/7ZZaQi35YWU)

If somebody wants to get in touch they are potentially valuable to the organisation.  They probably already know something about the organisation already and want to discuss something specific.  They need rapid access to contact information, balancing the need to get to the right person with the need to have the information without any complex navigation.

This user is immediately prompted to the Contact section.  The navigation bar keeps these users within two clicks of a relevant contact person.

### 1.4 Potential Members, Supporters and Collaborators
[*Demonstration for Potential Members*](https://youtu.be/NUyK1Wbc-iU)

These people may be ready and willing to make substantial contributions and to bring their own time and expertise.  They are likely to want specific information about key activities, and to understand how they could best contribute.

It is important that this group understand waht is involved before signing up.  Therefore the Join Us page is always a single click, with the sign-up button being a click at the bottom of the information page.

This group are also likely to be future donors.

### 1.5 Donors
[*Demonstration for Donors*](https://youtu.be/fKmlrB2n-PU)

These are people comning to the site with the specific intention of making a donation.  These people need rapid links to the dontation information that supports their preferred donation method. At all times users will be within two clicks of a donation option.

It may also be desirable to keep a GDPR compliant record of these people, so that they can be supported and thanked.  Such information is easy to gather - but managing it on an ongoing basis does need to considered.

## 2 Wireframe Designs

The Wireframe Designs were created using [Justinmind 9.2.2](https://etiennedevaux.github.io/warksar/ProjectDocuments/wireframes/Justinmind.jpg)

Each page was prototyped in order to get concensus from the Warwickshire Search and Rescue Team.  Once finalised the designs were implemented in html, using CSS and Javascript.  

*In some cases there are minor interface changes from the original wireframe.*

### 2.1 [Home](https://etiennedevaux.github.io/warksar/ProjectDocuments/wireframes/Home.png)

### 2.2 [About - History](https://etiennedevaux.github.io/warksar/ProjectDocuments/wireframes/About%20-%20History.png)

### 2.3 [About - What We Do](https://etiennedevaux.github.io/warksar/ProjectDocuments/wireframes/About%20-%20What%20We%20Do.png)

### 2.4 [The Team](https://github.com/etiennedevaux/warksar/blob/Draft4forReview/ProjectDocuments/wireframes/The%20Team.png)

### 2.5 [Join Us](https://github.com/etiennedevaux/warksar/blob/Draft4forReview/ProjectDocuments/wireframes/Join%20Us.png)

### 2.6 [Gallery](https://github.com/etiennedevaux/warksar/blob/Draft4forReview/ProjectDocuments/wireframes/Gallery.png)

### 2.7 [Contact](https://github.com/etiennedevaux/warksar/blob/Draft4forReview/ProjectDocuments/wireframes/Contact.png)

### 2.8 [Donate](https://github.com/etiennedevaux/warksar/blob/Draft4forReview/ProjectDocuments/wireframes/Donate.png)

Perhaps most importantly the wireframe designs will be used for workshopping future developments, ensuring clear specifications before development work starts.

This approach will also allow creative free-thinking and discussion, whilst ensure the production website remains stable.


## 3 Responsive Design

### 3.1 [Responsive Design Demo](https://youtu.be/e96WzABQF0c)
With a wide range of screen sizes for all potential users it is important to design for responsiveness, based on horizontal and vertical resolution changes.

Also see README section 10.6 for examles of responsive design testing.

## 4 Accessible Design

### 4.1 Accessible Design Principles
Accessible design is about maximising accessibility for as wide a range of users as possible, over a wide range of browsers in a wide range of contexts.

To ensure this use of semantic markup, such as section, heading, navigation and other semantic tools is maximised.

The aria set of attributes are also widely used.

### 4.2 Testing Process
[Web Accessibility](https://www.webaccessibility.com/)

The initial testing identified 4 issues and a score of 92%, those being the 4 social media links in the footer.  The source of the issue was having a fontawesome icon and no text label.

To overcome this aria-label attributes were added to all of anchor elements, in accordance with the [W3C Guidelines](https://www.w3.org/TR/wai-aria/#aria-label)

The above tool still showed these as an issue, but the links are compliant so they can be deployed whilst the discrepancy is further investigated.

## 5 Features
Features for the Warwickshire Search and Rescue Website

### 5.1 Home Page
The home page is designed to give an eye-catching experience with a clear Call to Action (CTA).

The top menu is static, ensuring a familiar navitation interface from any part of the site.  The menu includes drop downs, but the client preference is generally for a fairly flat structure and pages with general information, rather than deeper menu links.  Both are available and will be used.

The footer is also static, keeping key information and links readily available at all times when on the site.  This information includes social media links, registered charity number and email contact.

The CTA can be animated, some people love animation some hate it.  At present the css is available but disabled.

### 5.2 About - What We Do
The What We Do page is desgigned, using Bootstrap, to provide clear, factual information with supporting media, in the form of photos, audio and video.

The page is navigated by the user simply scrolling down.  The page is designed to be responsive for different screen sizes and orientations.

### 5.3 About - Our History
This page uses a timeline layout.  This is based on the template provided [Here](https://www.w3schools.com/howto/howto_css_timeline.asp)

The timeline has had minor adaptations to improve how the top item displays, and more subtantial extensions to make it fully responsive.

### 5.4 The Team
This section was based on the Bootstrap carousel example [Here](https://www.w3schools.com/bootstrap4/bootstrap_carousel.asp) but with adaptations to allow for easier display of a range of image shapes, sizes and orientations on a range of screen sizes.  

The aim is to provide a simple, informal narrative on the type of work done by Warwickshire Search and Rescue

### 5.5 Join Us
The Join Us page is fairly low key as there is no currently active recruitment campaign.  However, it is still a key part of the site.

The main aim is to ensure that before people express an interest that they understand the scale of commitment that is required, hence the page has a scrollable section describing the work, with a button at the bottom, at least implying that people have read the text before they make contact.

#### 5.5.1  Join Us Modal Form
For this deployment the contact button triggers a modal form.  This form captures information from the user, who then submits.  At present the submission triggers a JavaScript that hides the submit button and an external PHP file that stores the submission on a SQL Server database and returns a confirmation message to the user.  This will need to be considered in the context of GDPR, so is not part of the initial deployment.

### 5.6 Gallery Page
The Gallery Page, taken from the Code Institute Love Running exercise, is an important and informal way of engaging end users in the wide variety of activities undertaken by Warwickshire Search and Rescue.  The masonry board effect enables users to see a wide range in a single view and focus on the areas of interest to them, sometimes with internal or external links to articles or multimedia.  The photos come from a wide range of sources and on 4k screens did initially show pixelation.  The standard Bootstrap breakpoints do not cover screens that large, so an additional breakpoint at 2,400 px width has been created.  The extra column minimised pixelation issues.

### 5.7 Contact
The contact page deploys standard Bootstrap cards.  The Police card links to an external site, using _blank for a separate tab, thereby maintaining navigation etc.

The other cards use mailto: at present, this may be developed to use automatic emails and databsae storage of data (as elsewhere on the site) but for the initial deployment the mailto: options is considered sufficient.

### 5.8 Donate
Currently there are three preferred donation methods on this page.  A fourth one is in the specification for a future deployment, and will follow the same pattern.

The PayPal and Easyfunding options point to embedded pages, that open in a new tab.

The banking details for works slightly differently.  For security reasons it is not felt to be appropriate to have full banking details directly on the website.  It is also the case that the other options have some inherent recording of donations etc.  People submitting donations online needs some additional recording and tracking.  The workflow is as follows

1.  User clicks on the button to request details

2.  A modal form requests a name and email address

3.  The user submits, and the modal form changes to show that they have submitted.

4.  An automatic email is generated from emailjs and is sent to the user with a copy to the relevant person in Warwickshire Search and Rescue

5.  A PHP routine is called on a separate server that creates a record in a separate SQL Server.  This records the form data alongside a date.

#### 5.8.1 Donation Modal Form
When submitting a donation via an online transfer the workflow involves sending an automated email to the benefactor, with a copy to the fund raising co-ordinator and a record being made in a remote database of the request for details.

This is achieved by using a Bootstrap Modal, in which there is an embedded form with a submit button.

The submit button runs a JS routine and also posts the form to a PHP routine that securely accesses the database.

In the initial implementation the output from the PHP routing goes to a hidden iframe, future deployments will use the iframe to give a message to the user.

At present the form button label changes to show that the submission has been completed.

### 5.9 Site Wide Features

#### 5.9.1 JavaScript 'Virtual Pages'

LO2 - 2.1 States *Create a website of at least 3 pages, or (if using a single scrolling page) at least 3 separate page areas, to match the design and to meet its stated purpose*

This site is designed as a single scrolling html file, index.html, that contains all of the pages.  Some simple Javascript is then used to manipulate the DOM and to show the selected page and hide others, giving an enhanced user experience over the simple use of scrolling to navigate.

This approach has advantages and disadvantages

**Advantages**
Global changes, such as to the footer and navigation bar, only need to be made in one place
Navigation between parts of the site is rapid, as all html has always been downloaded
Functionality is maintained on the downloaded site even when connectivity is lost or poor
Future aspirations for site searches are easier to implement
Once entered the same content can be shown on multiple pages, particularly in search results

**Disadvantages**
Some knowledge of Javascript is required to build and develop the site (not for content editing)
The browser navigation trail has to be created via Javascript
Initial page loading can be slower as hidden elements are being downloaded

**Conclusions**
In this case the virtual page approach was agreed to be optimal for
1.  Future developments
2.  Performance, particularly in low and variable bandwidth remote environments
3.  Future maintenance

#### 5.9.2 Navigation Bar
The Navigation bar, based on a Bootstrap Navigation bar, but with some local customisation, is visible in the same place at all times.  This gives a simple, unobtrusive and always easily available navigation experience.

The element has 0.9 opacity, so that it is always clear when there is content behind it, inviting the user to scroll to that content, but without obscuring the text.

#### 5.9.3 Footer
The Footer bar is visible in the same place at all times.  This gives simple, unobtrusive and always easily available information, such as contact and charity number, as well as links to related external social media sites.

The element has 0.8 opacity, so that it is always clear when there is content behind it, inviting the user to scroll to that content, but without obscuring the text.  The opacity is lower than the header for two reasons, firstly it shows content that the user may not yet have seen, secondly it is primarily a reference feature rather than an active part of the naviation experience.

The footer also contains information about the precise code versions the user is seeing.  This helps to match the user experience to precise versions of html, css and Javascript code.

Date and ownership information are also held here.  This information is generally of low importance, but on occasions can be an important reference.

#### 5.9.4 Background Images
This site is using a single page of html, with sections being hidden and shown via a simple JavaScript routine.  This approach provides many advantages, particularly around performance and re-use of content.  

Some of the user feedback is for the site background image to only appear in the 'Call to Action' home section.  Having the background image as a separate div keeps it out of the content flow, so making other changes easier.  

To provide the user requirement the div now has an additional class that makes it easy to switch it off and on with a small change to the existing Javascript.

#### 5.9.5 Multimedia
Multimedia is a growing part of the Warwickshire Search and Rescue site.  The images have some animation and additional effects.  The gallery contains a number of pictures and an item of streamed video.

The What We Do section contains downloaded audio and video.  The video has been recorded and edited at a low resolution to make the file small enough to go on GitHub.  The video content has not been approved for YouTube, once approved it can be uploaded to a streaming service and be delivered that way instead.

One of the multimedia challenges is that all media are contributed by members of the team, this means that the items come in highly variable levels of quality and format.  CSS is used to adjust media, often at an individual level, to optimise appearance.

## 6 External Libraries

This project uses a number of external libraries, as listed below

### 6.1 [Bootstrap](https://getbootstrap.com/)
https://maxcdn.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css
https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js

### 6.2 [Font Awesome](https://fontawesome.com/)
https://use.fontawesome.com/releases/v5.6.1/css/all.css

### 6.3 [Google Fonts](https://fonts.google.com/)
https://fonts.googleapis.com/

### 6.4 [JQuery](https://jquery.com/)
https://code.jquery.com/jquery-3.3.1.slim.min.js

### 6.6 [EmailJS](https://www.emailjs.com/)
https://cdn.jsdelivr.net/npm/emailjs-com@2/dist/email.min.js

### 6.7 [Microsoft Azure](https://azure.microsoft.com/)
In addition the SQL Server and PHP Server are held on Microsoft Azure

## 7 Key Issues

### 7.1 Handling different sizes and shapes of images
Keeping images fresh and relevant is important for the work of the organisation.  However, images come from a wide range of non-specialist contributors, and therefore in a wide range of shapes, sizes and resolutions.

Multiple approaches have been tried.  The two key approaches are:

1.  Using the traditional img tag

2.  Using the background-image css property

So far approach 1 would seem easier to manage and maintain, although approach 2 is likely to work better with small video clips.  Approach 1 will be deployed for now.

By default all images and image boxes are given an ID.  This may not be strictly necessary, but if the id is in place it makes it easier to use CSS to target individual images.

Many images will be assigned an id so that they can be individually manipulated from CSS.

### 7.2 Logo Text Link
Changed logo text link to point to an internal anchor, ensuring that the link does not need to change if the root domain is changed with deployment to different services.

### 7.3 Browser Back Button
The site is a single file, divided into virutal pages, each of which is a div that is hidden or shown by a JavaScript routine.  THis approach has many benefits that are discussed elsewhere, but was leaving the browser back button empty.  This has been resolved by adding a Javascript line of code to insert an address to the back button, adding anchors at the top of each virtual page and detecting 'onhashchange' events.

### 7.4 Carousel Headings and Captions
User feedback suggested that the captions and headings for the carousel should blend more seamlessley into the background photos.  A gradient background colour was used to achieve this.

### 7.5 Bootstrap Burger menu opening dropdown at breakpoint
The core bootstrap does this as toggle.  Occasionally that can get out of sync, so the body element has an onload option to ensure that it remains synced when the page is loaded or reloaded.

### 7.6  Items going over header and footer when scrolled
The header and footer were originally set with a z-index of 2.  However some other content items had z-index values that were higher.  The z-index of footer and header were set to 10, so that all other items can come below them as they scroll.  This approach also enables a user to see when there are items beneath the translucent header and footer, inviting them to scroll.

### 7.7 Bottom row of Gallery images
The bottom row of gallery images end at different points as the images are, by design, of different lengths.  The overall mosaic effect is effective and provides a different perspective of hte work of the organisation.  But the bottom layer looked untidy. Two key things have been done, firstly the background imaged was switched from a blurred image to one that comes from a blur into focus.  Secondly the external margin to ensure that other pages can scroll clear of the translucent footer, was removed.  The overall effect is now far more aesthetic.

### 7.8 Additional Breakpoints
Three additional breakpoints have been added:

1.  Screens over 2000px in width
2.  Screens over 2400px in width
3.  Screens under 600px in height, this particularly targets mobile devices in landscape

### 7.9 Size of media files
GitHub has an upper file limit of 100Mb.  This is generous for code, and adequate for audio and images.  However, for video this is limiting.  Video files for the site are therefore either streamed from a third-party (Y0uTube or Facebook) or reduced in resolution to be stored on GitHub.

The are examples of all three on this site.

## 8 Code Structure

### 8.1 HTML

The HTML code has natural structure from the use of semantic elements such as header, navigation, footer and section.

Additional structure is provided with extensive annotations in comment lines.

Major sections are labelled with a start and end comment.

Elements are indented to help identify nesting and to ensure that elements are closed and do not cross.

### 8.2 CSS
There is, at present, a single css file within the assets sub-folder of the site.  
The CSS file has frequent comments and annotations.  
To provide structure the CSS file uses annotations to divide into sections that correspond to the parts of the website, plus other universal elements, such as the header, the footer, animations and media queries.

CSS classes follow a consistent pattern.  Classes created for the Warwickshire Search and Rescue site start with a wsr- prefix, other parts of the class given context.  This approach helps to distinguish classes specific to this site from those that are imported for other sites and those that serve to customise classes from external libraries, such as Bootstrap.

### 8.3 JavaScript
There is very little Javascript, but the Javascript routines are stored in a separate js file within the assets subfolder of the site.

Code is indented for clarity.

## 9 Deployment

### 9.1 Development and Testing

Development and testing is run on a local machine as a set of files on the hard drive.

The PHP and SQL Server elements are run on an Azure server and are called from the html, so the local files are fully operational.

The local respository is created using GitHub Desktop.

#### 9.1.1 Installing GitHub Desktop

GitHub Desktop can be accessed from http://desktop.github.com

1. Dowload the version for your local machine

2. Run the installation program

3. Run the program and sign-in to your GitHub account (to create a GitHub account go to http://www.github.com/join)

4.  Choose FILE then CLONE REPOSITORY

5.  Enter the URL https://github.com/etiennedevaux/warksar

6.  The repository will then be downloaded to your local machine in the directory shown in the CLONE REPOSITORY dialogue

7.  File can be edited using your preferred editor, in my case I have used Visual Studio Code, but any common editor will work.

8.  See the documentation at https://docs.github.com/en/desktop

### 9.2 Running the Code

### 9.3 Editing the Code

### 9.4 Commits

### 9.5 Push to Origin

### 9.3 GitHub Branches
Once tested the code is deployed on GitHub, using Github Desktop.  The code can be deployed to various branches to allow for testing and staging of changes and additions, whilst maintaining the integrity of the core.

### 9.3 Github Main Branch

The deployment goal at this stage is to be available for assessment on the Github platform.  Once tested locally it can then be deployed to a branch on GitHub, and when tested in that environment merged back into the main branch and left unchanged for assessment.



### 9.4 Live Deployment

Ultimately the site will, once approved by Warwickshire Search and Resuce, be deployed to a different server.  To make this deployment as simple as possible the site has been designed to for easy copying and using relative file paths to assets such as CSS, images and Javascript.

## 10 Testing and Quality Assurance

### 10.1 Systematic Testing
Systematic testing involves checking each menu option from left to right, including drop-down options.  The left to right pattern helps to reduce the risk of options being overlooked.

For each option the page is then checked from top to bottom.  Key checks include, but are not limited to, formating, spelling, links, colouring and shading.

For layout and look and feel consistency, usability and aesthetics are considered.

### 10.2 Browser Testing
The site needs to be systematically checked against a range of common browsers.  These include, but are not limited to, Google Chrome, Firefox, Microsoft Edge, Safari and Internet Explorer.

Errors corrected include, not use of auto-fit in css and careful use of flex display options.

### 10.3 Device Testing
Ideally the site would be checked on the full range of devices and operating systems.  For practical reasons in the context of a learning project it may not be possible to test against all options.

The web developer tools allow testing against common devices, particularly mobile devices.

The site has been developed on a Windows 10 Platform with Chrome.

### 10.4 End User Testing

In this case there is a client organisation, so there will be extensive end user testing from a range of stakeholders, focusing on a range of personae.

There will also be a range of end users asked to review and comment on the site.  Beyond the context of a learning project this would need to be more extensive, more formal and more structured.

### 10.5 Scenario Testing

There are four key user experience scenarios against which the site will be tested, a user seeking further information, a user wishing to get in touch with the organisation, a user wishing to join the organisation and a user wishing to donate to the organisation.  

### 10.6 Responsive Design Testing

The site is based on the Bootstrap breakpoints, testing has been conducted against each of these.  The following test record shows the logical transition from 4k desktop screens to small mobile devices, that may be in portrait or landscape orientation.

#### 10.6.1 Extra Extra Large (XXL) >= 1400px

>**Navigation Bar** - OK
>
>**Home Page** - OK
>
>**What We Do Page** - OK
>
>**Our History** - OK
>
>**Team Carousel**  
>Adjust width for first item.
>
>**Join Us** - OK
>
>**Gallery** - OK  
>4 columns
>
>**Contact** - OK  
>4 Bootstrap Cards Across
>
>**Donate** - OK  
>3 Bootstrap Cards Across

#### 10.6.2 Extra Large xl 1200px - 1400px

>**Home Page**  
>Remove min-width and min-height for CTA-text frame
>Reduce size of central logo
>Reduce font size of CTA text
>
>**What We Do Page** - OK
>
>**Team Carousel** - OK
>
>**Join Us** - OK
>
>**Gallery** - OK  
>3 columns
>
>**Contact** - OK    
>4 Bootstrap Cards Across
>
>**Donate** - OK  
>3 Bootstrap Cards Across

#### 10.6.3 Large lg 992px - 1200px

>**Navigation Bar** - OK
>
>**Home Page**  
>Further reduce size of central logo  
>Further reduce font size of CTA text
>
>**What We Do Page** - OK
>
>**Team Carousel** - OK
>
>**Join Us**  
>Reduce font sizes
>
>**Gallery** - OK  
>3 columns
>
>**Contact** - OK  
>3 Bootstrap Cards Across  
>1 on next row, all centred
>
>**Donate** - OK  
>**3 Bootstrap Cards Across

#### 10.6.4 Medium md 768px to 992px

>**Navigation Bar** - OK  
>
>**Home Page**  
>Hide central logo  
>
>**What We Do Page**  
>Add element ids so that individual elements can be targeted, and Bootstrap customised, without affecting other parts of the site  
>Use Bootstrap set images to go vertically above text
>
>**Team Carousel** - OK
>
>**Join Us**  
>Align image title and text vertically using Bootstrap
>
>**Gallery** - OK  
>3 columns
>
>**Contact** - OK  
>3 Bootstrap Cards Across  
>1 on next row, all centred
>
>**Donate** - OK  
>3 Bootstrap Cards Across

#### 10.6.5 Small 576px to 768px

>**Navigation Bar**  
>Menu background being transparent makes text difficult to read with burger menu.  
>Set background to green, with padding and rounded corners
>
>**Home Page**  
>Move buttons below central main text
>Re-align buttons for horizontal display
>
>**Team Carousel** - OK
>
>**Join Us**  
>Hide image using Bootstrap
>
>**Gallery** - OK  
>3 columns
>
>**Contact** - OK  
>2 Bootstrap Cards Across  
>2 on next row, all centred
>
>**Donate** - OK  
>2 Bootstrap Cards Across  
>1 on next row, all centred

#### 10.6.6 Extra Small 0px to 576px

>**Navigation Bar**  
>Menu background being transparent makes text difficult to read with burger menu.  Set background to green, with padding and rounded corners
>
>**Home Page**  
>Move buttons below central main text  
>Re-align buttons for horizontal display
>
>**Team Carousel** - OK
>
>**Join Us**
>Hide image using Bootstrap
>
>**Gallery** - OK  
>3 columns
>
>**Contact** - OK  
>2 Bootstrap Cards Across  
>2 on next row, all centred
>
>**Donate** - OK  
>2 Bootstrap Cards Across  
>1 on next row, all centred

#### 10.6.7 Landscape Mobile
>**Footer Bar**  
>Set to disappear when height is below 400px.
>
## 10.7 W3C HTML Validation Report
The report was the initial report for the index.html page (which includes all html pages as Javascript is used to hide and show page components).

The report also shows the actions taken to obtain an error free report.

A check will now be run before each commit and any errors adressed at that stage, or soon after.

*NB: src=  urls have been modified to prevent images from cluttering the README file when viewed online

**Report 001**
>**1**	Error: No space between attributes.  
>**Issue**  
>At line 16, column 31  
>ext/javascript"src="https://cd  
>**Actions**  
>Space added
>
>**2**	Warning: The type attribute is unnecessary for JavaScript resources.  
>**Issue**  
>From line 16, column 1; to line 16, column 97
></script>?<script type="text/javascript"src=""https://cdn.jsdelivr.net/npm/emailjs-com@2/dist/email.min.js></scri  
>**Actions**  
>Type attribute removed
>
>**3**	Error: An img element must have an alt attribute, except under certain conditions. For details, consult guidance on providing text alternatives for images.
>**Issue**  
>From line 28, column 1; to line 28, column 51
>logoleft'>?<img class='logoleft' src=''assets/images/logo.png>?</div
>**Actions**  
>Add ALT tag
>
>**4**	Error: An img element must have an alt attribute, except under certain conditions. For details, consult guidance on providing text alternatives for images.  
>**Issue**  
>From line 73, column 1; to line 73, column 34  
>cta-img">?<img src=""assets/images/logo.png">?</div  
>**Actions**  
>Add ALT tag
>
>**5**	Warning: Section lacks heading. Consider using h2-h6 elements to add identifying headings to all sections.  
>**Issue**  
>From line 69, column 1; to line 69, column 43  
>d='Home'>?<section id='wsr-home' class='wsr-content'>?<!--   
>**Actions**  
>Add section heading, hide if appropriate
>
>**6**	Error: Duplicate ID WhatWeDo.  
>**Issue**  
>From line 98, column 1; to line 98, column 43  
>ntainer"><section id='WhatWeDo'class='wsr-content'><div    
>**Actions**  
>Change ID to avoid duplication
>
>**7**	Warning: The first occurrence of ID WhatWeDo was here.  
>**Issue**  
>From line 93, column 1; to line 93, column 64  
>div style=display: none; class='MenuComponent' id='WhatWeDo'><head  
>**Actions**  
>Change ID to avoid duplication
>
>**8**	Error: An img element must have an alt attribute, except under certain conditions. For details, consult guidance on providing text alternatives for images.  
>**Issue**  
>From line 108, column 1; to line 108, column 116  
>ol-lg-4">?<img id="alsar-logo" src='' class="wsr-content-img">?</div  
>**Actions**  
>Add ALT tag
>
>**9**	Error: An img element must have an alt attribute, except under certain conditions. For details, consult guidance on providing text alternatives for images.  
>**Issue**  
>From line 118, column 1; to line 118, column 67  
>ol-lg-4">?<img src="" class="wsr-content-img">?</div  
>**Actions**  
>Add ALT tag
>
>**10**	Warning: Section lacks heading. Consider using h2-h6 elements to add identifying headings to all sections.  
>**Issue**
>From line 98, column 1; to line 98, column 43
>ntainer">?<section id='WhatWeDo' class='wsr-content'>?<div   
>**Actions**  
>Add heading, hide if appropriate
>
>**11**	Error: An img element must have an alt attribute, except under certain conditions. For details, consult guidance on providing text alternatives for images.  
>**Issue**  
>From line 282, column 1; to line 282, column 89
>m-block">?<img id="imgwarksar030-02" src="" class="wsr-content-img">?</div  
>**Actions**  
>Add ALT tag
>
>**12**	Error: An img element must have an alt attribute, except under certain conditions. For details, consult guidance on providing text alternatives for images.  
>**Issue**  
>From line 297, column 1; to line 297, column 89  
>m-block">?<img id="imgwarksar021-02" src="" class="wsr-content-img">?</div  
>**Actions**  
>Add ALT tag  
>
>**13**	Error: An img element must have an alt attribute, except under certain conditions. For details, consult guidance on providing text alternatives for images.  
>**Issue**  
>From line 312, column 1; to line 312, column 89  
>m-block">?<img id="imgwarksar028-02" src="" class="wsr-content-img">?</div
>**Actions**  
>Add ALT tag
>
>**14**	Error: An img element must have an alt attribute, except under certain conditions. For details, consult guidance on providing text alternatives for images.  
>**Issue**  
>From line 327, column 1; to line 327, column 89  
>m-block">img id="imgwarksar011-02" src="" class="wsr-content-img"></div  
>**Actions**  
>Add ALT tag
>
>**15**	Error: An img element must have an alt attribute, except under certain conditions. For details, consult guidance on providing text alternatives for images.  
>**Issue**  
>From line 342, column 1; to line 342, column 100  
>img id="imgwarksar027-searchmanager" src="assets/images/imgwarksar027.jpg" class="wsr-content-img">?</div  
>**Actions**  
>Add ALT tag
>
>**16**	Error: Bad value mailto: support@warksar.org.uk for attribute href on element a: Illegal character in scheme data: space is not allowed.  
>**Issue**  
>From line 360, column 1; to line 360, column 78   
>a class="btn btn-primary wsr-text-btn" href=mailto: support@warksar.org.uk">Contac  
>**Actions**   
>Remove space
>
>**17**	Warning: Section lacks heading. Consider using h2-h6 elements to add identifying headings to all sections.  
>**Issue**  
>From line 272, column 1; to line 272, column 47
>ntainer">?<section id='warksarroles' class='wsr-content'>?<div 
>
>**Actions**  
>Add heading, hide if appropriate  
>
>**18**	Error: The frameborder attribute on the iframe element is obsolete. Use CSS instead.  
>**Issue**  
>From line 375, column 1; to line 375, column 211  
>her"></a>?<iframe width="1280" height="720" src="https://www.youtube.com/embed/qDnTAo1rHks" frameborder="0" al�rometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></ifra  
>**Actions**  
>Remove frameborder and use CSS  
>
>**19**	Warning: Section lacks heading. Consider using h2-h6 elements to add identifying headings to all sections.   
>**Issue**  
>From line 371, column 1; to line 371, column 20  
>/header>?<section id=''photo'  
>**Actions**  
>Add heading, hide if appropriate
>
>**20**	Error: Bad value for attribute id on element div: An ID must not be the empty string.  
>**Issue**  
>From line 441, column 1; to line 441, column 46  
>ation -->?<div id="" class="card" style="width: 18rem;"? <im  
>**Actions**  
>Put in unique, non-null, ID  
>
>**21**	Error: Duplicate ID  
>**Issue**  
>From line 442 column3 toline 442  
>img id=""src=class="card-img-top"  
>**Actions**  
>Put in unique, non-null, ID
>
>**22**	Warning: The first occurrence of ID
>**Issue**  
>From line 441, column 1; to line 441  
>ation --> div id="" class="card"  
>**Actions**  
>Put in unique, non-null, ID  
>
>**23**	Error: Bad value for attribute id on element img: An ID must not be the empty string.  
>**Issue**  
>From line 442, column 3; to line 442, column 82  
>8rem;">? <img id="" src= class="card-img-top" alt="...">? <di  
>**Actions**  
>Put in unique, non-null, ID
>
>**24**	Error: Duplicate ID  
>**Issue**  
>From line 455, column 1; to line 455, column 46  ation -->?div id="" class="card" style="width: 18rem;"? <im  
>**Actions**
>Put in unique, non-null, ID
>
>**25**	Warning: The first occurrence of ID was here.  
>**Issue**  
>From line 441, column 1; to line 441, column 46
>ation -->?div id="" class="card" style="width: 18rem;"? <im  
>**Actions**    
>Put in unique, non-null, ID
>
>**26**	Error: Bad value for attribute id on element div: An ID must not be the empty string.  
>**Issue**  
>From line 455, column 1; to line 455, column 46  
>ation -->?div id="" class="card" style="width: 18rem;"? <im  
>**Actions**  
>Put in unique, non-null, ID
>
>**27**	Error: End tag div seen, but there were open elements.  
>**Issue**  
>From line 507, column 1; to line 507, column 6  
>ize="50">?/div?   
>**Actions**  
>Re-arrange html to avoid crossing elements
>
>**28**	Error: Unclosed element form.  
>**Issue**  
>From line 498, column 1; to line 498, column 131  
>transfer?form id="query-form" class="signup-form" method="POST" action="https://devauxphp.azurewebsites.net/warksar_log.php" target="null"   
>**Actions**  
>Form and div are both closed, but cross.  Adjust html to avoid
>
>**29**	Error: Attribute form_id not allowed on element input at this point.
>**Issue**  
>From line 510, column 9; to line 510, column 135  
>? input form_id="query_form" id="donationmodal-button" type="submit" class="btn btn-primary" onclick="formSubmit('query-form')"?   
>**Actions**  
>Remove attribute
>
>**30**	Error: Stray end tag form.  
>**Issue**
>From line 512, column 1; to line 512, column 7  > <  
>**Actions**
>Form and div are both closed, but cross, this makes the tag appear stray.  Adjust html to avoid
>
>**31**	Error: The value of the for attribute of the label element must be the ID of a non-hidden form control.  
>**Issue**  
>From line 503, column 1; to line 503, column 19  
>/iframe>??label for="fname"   
>**Actions**  
>Adjust for attribute  
>
>Full Document checking completed.
>Used the HTML parser.
>Total execution time 127 milliseconds.
>
>About this checker � Report an issue � Version: 21.2.17

### 10.8 W3C CSS Validator results for warwickshiresearchandrescue.css 
(CSS level 3 + SVG)
Sorry! We found the following errors (13)
URI : warwickshiresearchandrescue.css

>**6**	:root  
>**Error**  
>Parse Error %  
>**Actions**  
>Line is now redundanct, removed.
>
>**241**	.Content-Container  
>**Error**  
>Value Error : border collapse is not a color value : collapse  
>**Actions**  
>Redundant line, removed
>
>**316**	.wsr-content-text-fc  
>**Error**  
>Value Error : font-weight 1000 is not a font-weight value : 1000  
>**Actions**  
>Set to max value, 900  
>
>**425**	.wsr-cta-actions  
>**Error**  
>Value Error : font-weight 1000 is not a font-weight value : 1000  
>**Actions**  
>Set to max value, 900
>
>**583**	#imgwarksar029-01  
>**Error**     
>Property max-wdith doesn't exist. The closest matching property name is max-width : 300px  
>**Actions**  
>Remove section as the img is no longer in use
>
>**622**	#imgitem005  
>**Error**  
>is an incorrect operator : cover / contain / px  
>**Actions**  
>Remove section as the img is no longer in use
>
>**630**	#imgitem010	  
>**Error**  
>is an incorrect operator : cover / contain / px  
>**Actions**  
>Remove section as the img is no longer in use  
>
>**638**	#imgitem006	  
>**Error**  
>is an incorrect operator : cover / contain / px  
>**Actions**  
>Remove section as the img is no longer in use  
>
>**647**	#btn_donateCC_LG-01  
>**Error**  
>Property image-fit doesn't exist : contain  
>**Actions**  
>Corrected to object-fit  
>
>**690**	#img-carousel-5  
>**Error**  
>Property object-align doesn't exist : center center  
>**Actions**  
>Correct to object-position
>
>**753**	.wsr-carousel-caption h5  
>**Error**  
>Property backdrop-filter doesn't exist : blur(10px)  
>**Actions**  
>Vaidated that the property works with Chrome.  For other browsers it degrades gracefully.  Decision to leave in place  
>
>**761**	.wsr-carousel-indicator  
>**Error**  
>Value Error : bottom revert is not a bottom value : revert  
>**Actions**  
>Change to top: 100px;  
>
>**785**	.wsr-carousel-caption p  
>**Error**  
>Property backdrop-filter doesn't exist : blur(10px)  
>**Actions**  
>Vaidated that the property works with Chrome.  For other browsers it degrades gracefully.  Decision to leave in place
>
>**Warnings**  
>Warnings (6)  
>URI : warwickshiresearchandrescue.css  
>7		--cssfileversion is an unknown vendor extension  
>8		--lightgrey is an unknown vendor extension  
>9		--darkgrey is an unknown vendor extension  
>10		--bgroundshade is an unknown vendor extension  
>**Actions**  
>All warnings refer to variables that have been created to enable global management of the colurs of certain features so that they remain consistent across the site.

## 11 Credits

The text content, images, audio and video is provided courtesy of [Warwickshire Search and Rescue](http://www.warksar.org.uk) 

A number of external libraries and services are used, listed in 

Code blocks that are taken, and often adapted, from third-parties are individually attributed.

Third party sources and services are

[The Code Institute](https://codeinstitute.net/)  
[Bootstrap](https://getbootstrap.com/)  
[Google Fonts](https://fonts.google.com/)  
[FontAwesome](https://fontawesome.com/)  
[World Wide Web Consortium](https://www.w3.org/)  
[W3schools](https://www.w3schools.com/)  
[Stack Overflow](https://stackoverflow.com/)  
[EMailJS](https://www.emailjs.com/)  
[GitHub](https://github.com/)  
[Azure](https://azure.microsoft.com/)  


