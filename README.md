README.md

# Website Title: Warwickshire Search and Rescue

# Version Details: Warwickshire Search and Rescue
README Version: ;
HTML Version: 0295;
CSS Version: 0489;
JavaScript Version: 0024;

## User Experience

## Personae

The key purpose of the Warwickshire Search and Rescue (Warksar) site it to reach out to the public in general.  The team members will mainly communicate and interact with each other via internal online services.  The agreed strategic goals for the site are to Inform, Communicate and Engage.  Engagement will include support, participation and donations.

This leads us to 4 critical personae

### Information Seekers

For most of the public in general they may have had little reason to have come across Warksar, but have now heard about it and would like to know more.  These people are potential donors, members and collaborators - but for now need to be nurtured rather than directed.

### Queries

If somebody wants to get in touch they are potentially valuable to the organisation.  They probably already know something about the organisation already and want to discuss something specific.  They need rapid access to contact information, balancing the need to get to the right person with the need to have the information without any complex navigation.

### Potential Members, Supporters and Collaborators

These people may be ready and willing to make substantial contributions and to bring their own time and expertise.  They are likely to want specific information about key activities, and to understand how they could best contribute.

This group are also likely to be future donors.

### Intentional Donors

These are people comning to the site with the specific intention of making a donation.  These people need rapid links to the dontation information that supports their preferred donation method. 

It may also be desirable to keep a GDPR compliant record of these people, so that they can be supported and thanked.  Such information is easy to gather - but managing it on an ongoing basis does need to considered.

Features for the Warwickshire Search and Rescue Website

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



##Deployment

##Credits

