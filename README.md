README.md

# Website Title: Warwickshire Search and Rescue

## Version Details
README Version: ;
HTML Version: 0398;
CSS Version: 0693;
JavaScript Version: 0029;

## User Experience

**[The User Experience Introduction]**(https://youtu.be/bswPg6mYZAc)
The user journey is based on four personae

[*Users Seeking Information*](https://youtu.be/nghCxQIYFRs)
People coming to the site, who simply, at this stage want to find out more information, but need to nurtured as potential future contributors, members, donors or maybe all three.

## Personae


The user journey is based on four personae


People coming to the site, who simply, at this stage want to find out more information, but need to nurtured as potential future contributors, members, donors or maybe all three.The key purpose of the Warwickshire Search and Rescue (Warksar) site it to reach out to the public in general.  The team members will mainly communicate and interact with each other via internal online services.  The agreed strategic goals for the site are to Inform, Communicate and Engage.  Engagement will include support, participation and donations.

This leads us to 4 critical personae

[**Home Page Demonstration**](https://youtu.be/bswPg6mYZAc)

### Information Seekers

[*Demonstration for Users Seeking Information*](https://youtu.be/nghCxQIYFRs)

For most of the public in general they may have had little reason to have come across Warksar, but have now heard about it and would like to know more.  These people are potential donors, members and collaborators - but for now need to be nurtured rather than directed.

The Call to Action gives these people a prompt to the About - What We Do section.  All navigation remains either directly visible, or within a single click on a dropdown.  At most this user is two clicks from any part of the site.

### Queries

[*Demonstration for Users with Specific Queries*](https://youtu.be/7ZZaQi35YWU)


If somebody wants to get in touch they are potentially valuable to the organisation.  They probably already know something about the organisation already and want to discuss something specific.  They need rapid access to contact information, balancing the need to get to the right person with the need to have the information without any complex navigation.

This user is immediately prompted to the Contact section.  The navigation bar keeps these users within two clicks of a relevant contact person.

### Potential Members, Supporters and Collaborators

[*Demonstration for Potential Members*](https://youtu.be/NUyK1Wbc-iU)

These people may be ready and willing to make substantial contributions and to bring their own time and expertise.  They are likely to want specific information about key activities, and to understand how they could best contribute.

It is important that this group understand waht is involved before signing up.  Therefore the Join Us page is always a single click, with the sign-up button being a click at the bottom of the information page.

This group are also likely to be future donors.

### Donors

[*Demonstration for Donors*](https://youtu.be/fKmlrB2n-PU)

These are people comning to the site with the specific intention of making a donation.  These people need rapid links to the dontation information that supports their preferred donation method. At all times users will be within two clicks of a donation option.

It may also be desirable to keep a GDPR compliant record of these people, so that they can be supported and thanked.  Such information is easy to gather - but managing it on an ongoing basis does need to considered.

### Responsive Design

[Responsive Design Demo](https://youtu.be/e96WzABQF0c)

With a wide range of screen sizes for all potential users it is important to design for responsiveness, based on horizontal and vertical resolution changes.

## Features

Features for the Warwickshire Search and Rescue Website

### Multimedia

Multimedia is a growing part of the Warwickshire Search and Rescue site.  The images have some animation and additional effects.  The gallery contains a number of pictures and an item of streamed video.

The What We Do section contains downloaded audio and video.  The video has been recorded and edited at a low resolution to make the file small enough to go on GitHub.  The video content has not been approved for YouTube, once approved it can be uploaded to a streaming service and be delivered that way instead.

One of the multimedia challenges is that all media are contributed by members of the team, this means that the items come in highly variable levels of quality and format.  CSS is used to adjust media, often at an individual level, to optimise appearance.


### Gallery Page

The Gallery Page, taken from the Code Institute Love Running exercise, is an important and informal way engaging end users in the wide variety of activities undertaken by Warwickshire Search and Rescue.  The masonry board effect enables users to see a wide range in a single view and focus on the areas of interest to them, sometimes with internal or external links to articles or multimedia.  The photos come from a wide range of sources and on 4k screens some will show pixelation.  The standard Bootstrap breakpoints do not cover screens that large, so an additional breakpoint at 2,400 px width has been created.  The extra column minimised pixelation issues.

## Home Page and Call to Action

The home page is designed to give an eye-catching experience with a clear Call to Action (CTA).

The top menu is static, ensuring a familiar navitation interface from any part of the site.  The menu includes drop downs, but the client preference is generally for a fairly flat structure and pages with general information, rather than deeper menu links.  Both are available and will be used.

The footer is also static, keeping key information and links readily available at all times when on the site.  This information includes social media links, registered charity number and email contact.

The CTA can be animated, some people love animation some hate it.  At present the css is available but disabled.

The Navigation bar, based on a Bootstrap Navigation bar, but with some local customisation, is visible in the same place at all times.  This gives a simple, unobtrusive and always easily available navigation experience.

The element has 0.9 opacity, so that it is always clear when there is content behind it, inviting the user to scroll to that content, but without obscuring the text.

The Footer bar is visible in the same place at all times.  This gives simple, unobtrusive and always easily available information, such as contact and charity number, as well as links to related external social media sites.

The element has 0.8 opacity, so that it is always clear when there is content behind it, inviting the user to scroll to that content, but without obscuring the text.  The opacity is lower than the header for two reasons, firstly it shows content that the user may not yet have seen, secondly it is primarily a reference feature rather than an active part of the naviation experience.

The footer also contains information about the precise code versions the user is seeing.  This helps to match the user experience to precise versions of html, css and Javascript code.

Date and ownership information are also held here.  This information is generally of low importance, but on occasions can be an important reference.

### Donation Modal Form
When submitting a donation via an online transfer the workflow involves sending an automated email to the benefactor, with a copy to the fund raising co-ordinator and a record being made in a remote database of the request for details.

This is achieved by using a Bootstrap Modal, in which there is an embedded form with a submit button.

The submit button runs a JS routine and also posts the form to a PHP routine that securely accesses the database.

In the initial implementation the output from the PHP routing goes to a hidden iframe, future deployments will use the iframe to give a message to the user.

At present the form button label changes to show that the submission has been completed.

## External Libraries

## Key Issues

### Image and Media Management and Manipulation

Keeping images fresh and relevant is important for the work of the organisation.  However, images come from a wide range of non-specialist contributors, and therefore in a wide range of shapes, sizes and resolutions.

Multiple approaches have been tried.  The two key approaches are:

1.  Using the traditional img tag

2.  Using the background-image css property

So far approach 1 would seem easier to manage and maintain, although approach 2 is likely to work better with small video clips.  Approach 1 will be deployed for now.

By default all images and image boxes are given an ID.  This may not be strictly necessary, but if the id is in place it makes it easier to use CSS to target individual images.

Many images will be assigned an id so that they can be individually manipulated from CSS.

### Background Image

This site is using a single page of html, with sections being hidden and shown via a simple JavaScript routine.  This approach provides many advantages, particularly around performance and re-use of content.  

Some of the user feedback is for the site background image to only appear in the 'Call to Action' home section.  Having the background image as a separate div keeps it out of the content flow, so making other changes easier.  

To provide the user requirement the div now has an additional class that makes it easy to switch it off and on with a small change to the existing Javascript.

### Donate images

The existing donation page images will not produce an elegant page, even as placeholders.  It will be necessary to source or create some appropriate placeholder images.

## Testing and Quality Assurance

### Systematic Testing

Systematic testing involves checking each menu option from left to right, including drop-down options.  The left to right pattern helps to reduce the risk of options being overlooked.

For each option the page is then checked from top to bottom.  Key checks include, but are not limited to, formating, spelling, links, colouring and shading.

For layout and look and feel consistency, usability and aesthetics are considered.

### Browser Testing

The site needs to be systematically checked against a range of common browsers.  These include, but are not limited to, Google Chrome, Firefox, Microsoft Edge, Safari and Internet Explorer.

Errors corrected include, not use of auto-fit in css and careful use of flex display options.

### Device Testing

Ideally the site would be checked on the full range of devices and operating systems.  For practical reasons in the context of a learning project it may not be possible to test against all options.

The web developer tools allow testing against common devices, particularly mobile devices.

The site has been developed on a Windows 10 Platform with Chrome.

### End User Testing

In this case there is a client organisation, so there will be extensive end user testing from a range of stakeholders, focusing on a range of personae.

There will also be a range of end users asked to review and comment on the site.  Beyond the context of a learning project this would need to be more extensive, more formal and more structured.

### Scenario Testing

There are four key user experience scenarios against which the site will be tested, a user seeking further information, a user wishing to get in touch with the organisation, a user wishing to join the organisation and a user wishing to donate to the organisation.  

### Responsive Design

The site is based on the Bootstrap breakpoints, testing has been conducted against each of these.  The following test record shows the logical transition from 4k desktop screens to small mobile devices, that may be in portrait or landscape orientation.

#### Extra Extra Large (XXL) >= 1400px

##### Navigation Bar - OK

##### Home Page - **OK**

##### What We Do Page - *OK*

##### Our History - *OK*

##### Team Carousel
Adjust width for first item.

##### Join Us - *OK*

##### Gallery - *OK*
4 columns

##### Contact - *OK*
4 Bootstrap Cards Across

##### Donate - *OK*
3 Bootstrap Cards Across

#### Extra Large xl 1200px - 1400px

##### Home Page
Remove min-width and min-height for CTA-text frame
Reduce size of central logo
Reduce font size of CTA text

##### What We Do Page - *OK*

##### Team Carousel - *OK*

##### Join Us - *OK*

##### Gallery - *OK*
3 columns

##### Contact - *OK*
4 Bootstrap Cards Across

##### Donate - *OK*
3 Bootstrap Cards Across

#### Large lg 992px - 1200px

##### Navigation Bar - OK

##### Home Page
Further educe size of central logo
Further educe font size of CTA text

##### What We Do Page - *OK*

##### Team Carousel - *OK*

##### Join Us
Reduce font sizes

#### Gallery - *OK*
3 columns

##### Contact - *OK*
3 Bootstrap Cards Across
1 on next row, all centred

##### Donate - *OK*
3 Bootstrap Cards Across


#### Medium md 768px to 992px

##### Navigation Bar - OK

##### Home Page
Hide central logo

##### What We Do Page
Add element ids so that individual elements can be targeted, and Bootstrap customised, without affecting other parts of the site
Use Bootstrap set images to go vertically above text

##### Team Carousel - *OK*

##### Join Us
Align image title and text vertically using Bootstrap

#### Gallery - *OK*
3 columns

##### Contact - *OK*
3 Bootstrap Cards Across
1 on next row, all centred

##### Donate - *OK*
3 Bootstrap Cards Across



#### Small 576px to 768px

##### Navigation Bar
Menu background being transparent makes text difficult to read with burger menu.  Set background to green, with padding and rounded corners

##### Home Page
Move buttons below central main text
Re-align buttons for horizontal display

##### Team Carousel - *OK*

##### Join Us
Hide image using Bootstrap

#### Gallery - *OK*
3 columns

##### Contact - *OK*
2 Bootstrap Cards Across
2 on next row, all centred

##### Donate - *OK*
2 Bootstrap Cards Across
1 on next row, all centred




#### Extra Small 0px to 576px

##### Home Page

##### Navigation Bar
Menu background being transparent makes text difficult to read with burger menu.  Set background to green, with padding and rounded corners

##### Home Page
Move buttons below central main text
Re-align buttons for horizontal display

##### Team Carousel - *OK*

##### Join Us
Hide image using Bootstrap

#### Gallery - *OK*
3 columns

##### Contact - *OK*
2 Bootstrap Cards Across
2 on next row, all centred

##### Donate - *OK*
2 Bootstrap Cards Across
1 on next row, all centred




#### Landscape Mobile

##### Footer Bar
Disappears when height is below 400px.





### Accessibility

The will be checked against the W3C validator validator.w3.org

# W3C HTML Validation Report

The report was the initial report for the index.html page (which includes all html pages as Javascript is used to hide and show page components).

The report also shows the actions taken to obtain an error free report.

A check will now be run before each commit and any errors adressed at that stage, or soon after.

**Report 001**

## 1.	Error: No space between attributes.

### Error
At line 16, column 31
ext/javascript"src="https://cd

### Actions
Space added


## 2.	Warning: The type attribute is unnecessary for JavaScript resources.

### Error
From line 16, column 1; to line 16, column 97
</script>?<script type="text/javascript"src="https://cdn.jsdelivr.net/npm/emailjs-com@2/dist/email.min.js"></scri

### Actions
Type attribute removed


## 3.	Error: An img element must have an alt attribute, except under certain conditions. For details, consult guidance on providing text alternatives for images.

### Error
From line 28, column 1; to line 28, column 51
ogoleft'>?<img class='logoleft' src='assets/images/logo.png'>?</div

### Actions
Add ALT tag


## 4.	Error: An img element must have an alt attribute, except under certain conditions. For details, consult guidance on providing text alternatives for images.
From line 73, column 1; to line 73, column 34
cta-img">?<img src="assets/images/logo.png">?</div

### Actions
Add ALT tag


## 5.	Warning: Section lacks heading. Consider using h2-h6 elements to add identifying headings to all sections.

### Error
From line 69, column 1; to line 69, column 43
d='Home'>?<section id='wsr-home' class='wsr-content'>?<!-- 

### Actions
Add section heading, hide if appropriate

## 6.	Error: Duplicate ID WhatWeDo.

### Error
From line 98, column 1; to line 98, column 43
ntainer">?<section id='WhatWeDo' class='wsr-content'>?<div 

### Actions
Change ID to avoid duplication


## 7.	Warning: The first occurrence of ID WhatWeDo was here.

### Error
From line 93, column 1; to line 93, column 64
'>?</div>?<div style='display: none;' class='MenuComponent' id='WhatWeDo'>?<head

### Actions
Change ID to avoid duplication



## 8.	Error: An img element must have an alt attribute, except under certain conditions. For details, consult guidance on providing text alternatives for images.

### Error
From line 108, column 1; to line 108, column 116
ol-lg-4">?<img id="alsar-logo" src="https://www.lowlandrescue.org/images/lowland-rescue-lozenge1.png" class="wsr-content-img">?</div

### Actions
Add ALT tag


## 9.	Error: An img element must have an alt attribute, except under certain conditions. For details, consult guidance on providing text alternatives for images.

### Error
From line 118, column 1; to line 118, column 67
ol-lg-4">?<img src="assets/images/imgwarksar002.jpg" class="wsr-content-img">?</div

### Actions
Add ALT tag


## 10.	Warning: Section lacks heading. Consider using h2-h6 elements to add identifying headings to all sections.

### Error
From line 98, column 1; to line 98, column 43
ntainer">?<section id='WhatWeDo' class='wsr-content'>?<div 

### Actions
Add heading, hide if appropriate



## 11.	Error: An img element must have an alt attribute, except under certain conditions. For details, consult guidance on providing text alternatives for images.

### Error
From line 282, column 1; to line 282, column 89
m-block">?<img id="imgwarksar030-02" src="assets/images/imgwarksar030.jpg" class="wsr-content-img">?</div

### Actions
Add ALT tag



## 12.	Error: An img element must have an alt attribute, except under certain conditions. For details, consult guidance on providing text alternatives for images.

### Error
From line 297, column 1; to line 297, column 89
m-block">?<img id="imgwarksar021-02" src="assets/images/imgwarksar021.jpg" class="wsr-content-img">?</div

### Actions
Add ALT tag



## 13.	Error: An img element must have an alt attribute, except under certain conditions. For details, consult guidance on providing text alternatives for images.

### Error
From line 312, column 1; to line 312, column 89
m-block">?<img id="imgwarksar028-02" src="assets/images/imgwarksar028.jpg" class="wsr-content-img">?</div

### Actions
Add ALT tag


## 14.	Error: An img element must have an alt attribute, except under certain conditions. For details, consult guidance on providing text alternatives for images.

### Error
From line 327, column 1; to line 327, column 89
m-block">?<img id="imgwarksar011-02" src="assets/images/imgwarksar011.jpg" class="wsr-content-img">?</div

### Actions
Add ALT tag


## 15.	Error: An img element must have an alt attribute, except under certain conditions. For details, consult guidance on providing text alternatives for images.

### Error
From line 342, column 1; to line 342, column 100
m-block">?<img id="imgwarksar027-searchmanager" src="assets/images/imgwarksar027.jpg" class="wsr-content-img">?</div

### Actions
Add ALT tag


## 16.	Error: Bad value mailto: support@warksar.org.uk for attribute href on element a: Illegal character in scheme data: space is not allowed.

### Error
From line 360, column 1; to line 360, column 78
.</p>?<p>?<a class="btn btn-primary wsr-text-btn" href="mailto: support@warksar.org.uk">Contac

### Actions
Remove space

## 17.	Warning: Section lacks heading. Consider using h2-h6 elements to add identifying headings to all sections.

### Error
From line 272, column 1; to line 272, column 47
ntainer">?<section id='warksarroles' class='wsr-content'>?<div 

### Actions
Add heading, hide if appropriate


## 18.	Error: The frameborder attribute on the iframe element is obsolete. Use CSS instead.

### Error
From line 375, column 1; to line 375, column 211
her"></a>?<iframe width="1280" height="720" src="https://www.youtube.com/embed/qDnTAo1rHks" frameborder="0" al…rometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></ifra

### Actions
Remove frameborder and use CSS


## 19.	Warning: Section lacks heading. Consider using h2-h6 elements to add identifying headings to all sections.

### Error
From line 371, column 1; to line 371, column 20
</header>?<section id='photo'>?<!-- 

### Actions
Add heading, hide if appropriate



## 20.	Error: Bad value for attribute id on element div: An ID must not be the empty string.

### Error
From line 441, column 1; to line 441, column 46
ation -->?<div id="" class="card" style="width: 18rem;">? <im

### Actions
Put in unique, non-null, ID


##21.	Error: Duplicate ID .

### Error
From line 442, column 3; to line 442, column 82
8rem;">? <img id="" src="assets/images/imgwarksar011.jpg" class="card-img-top" alt="...">? <di

### Actions
Put in unique, non-null, ID


## 22.	Warning: The first occurrence of ID was here.

### Error
From line 441, column 1; to line 441, column 46
ation -->?<div id="" class="card" style="width: 18rem;">? <im

### Actions
Put in unique, non-null, ID


## 23.	Error: Bad value for attribute id on element img: An ID must not be the empty string.

### Error
From line 442, column 3; to line 442, column 82
8rem;">? <img id="" src="assets/images/imgwarksar011.jpg" class="card-img-top" alt="...">? <di

### Actions
Put in unique, non-null, ID


## 24.	Error: Duplicate ID .

### Error
From line 455, column 1; to line 455, column 46
ation -->?<div id="" class="card" style="width: 18rem;">? <im

### Actions
Put in unique, non-null, ID


## 25.	Warning: The first occurrence of ID was here.

### Error
From line 441, column 1; to line 441, column 46
ation -->?<div id="" class="card" style="width: 18rem;">? <im

### Actions
Put in unique, non-null, ID


## 26.	Error: Bad value for attribute id on element div: An ID must not be the empty string.

### Error
From line 455, column 1; to line 455, column 46
ation -->?<div id="" class="card" style="width: 18rem;">? <im
27.	Error: End tag div seen, but there were open elements.
From line 507, column 1; to line 507, column 6
ize="50">?</div>? 

### Actions
Put in unique, non-null, ID


## 28.	Error: Unclosed element form.

### Error
From line 498, column 1; to line 498, column 131
transfer?<form id="query-form" class="signup-form" method="POST" action="https://devauxphp.azurewebsites.net/warksar_log.php" target="null">??<!--

### Actions
Form and div are both closed, but cross.  Adjust html to avoid



## 29.	Error: Attribute form_id not allowed on element input at this point.

### Error
From line 510, column 9; to line 510, column 135
>? <input form_id="query_form" id="donationmodal-button" type="submit" class="btn btn-primary" onclick="formSubmit('query-form')">? 
Attributes for element input:
Global attributes
acceptwhen type is file
altwhen type is image
autocompletewhen type is text, search, url, tel, email, password, date, month, week, time, datetime-local, number, range, or color
autofocus
checkedwhen type is checkbox or radio
dirnamewhen type is text or search
disabled
form
formactionwhen type is submit or image
formenctypewhen type is submit or image
formmethodwhen type is submit or image
formnovalidatewhen type is submit or image
formtargetwhen type is submit or image
heightwhen type is image
listwhen type is text, search, url, tel, email, date, month, week, time, datetime-local, number, range, or color
maxwhen type is date, month, week, time, datetime-local, number, or range
maxlengthwhen type is text, search, url, tel, email, or password
minwhen type is date, month, week, time, datetime-local, number, or range
multiplewhen type is email or file
name
patternwhen type is text, search, url, tel, email, or password
placeholderwhen type is text, search, url, tel, email, password, or number
readonlywhen type is text, search, url, tel, email, password, date, month, week, time, datetime-local, or number
requiredwhen type is text, search, url, tel, email, password, date, month, week, time, datetime-local, number, checkbox, radio, or file
sizewhen type is text, search, url, tel, email, or password
srcwhen type is image
stepwhen type is date, month, week, time, datetime-local, number, or range
type
valuewhen type is not file or image
widthwhen type is image

### Actions
Remove attribute



## 30.	Error: Stray end tag form.

### Error
From line 512, column 1; to line 512, column 7
</div>?</form>? <

### Actions
Form and div are both closed, but cross, this makes the tag appear stray.  Adjust html to avoid



## 31.	Error: The value of the for attribute of the label element must be the ID of a non-hidden form control.

### Error
From line 503, column 1; to line 503, column 19
/iframe>??<label for="fname"> 

### Actions
Adjust for attribute



Full Document checking completed.
Used the HTML parser.
Total execution time 127 milliseconds.
________________________________________
About this checker • Report an issue • Version: 21.2.17

##Deployment

##Credits

