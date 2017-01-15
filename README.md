
# HTML-Email-Template
## ALL EMAILS MUST BE INLINED PRIOR PUSHING TO PRODUCTION
If you do not inline the email it will not render properly in email clients upon sending.
I highly recommend you use [Zurb Foundation inliner tool](http://foundation.zurb.com/emails/inliner.html). I do not use their code because in the past it didn't render across enough browsers. You can also use webpack or gulp inliners if you wish, there are probably many others out there as well.

This template is a great source to start developing emails with, this code will render properly in almost ALL email clients minus:

 - Lotus notes
 - Microsoft Exchange

*Renders in almost every single email client*


### Email rendered in full for reference
 [Email Template Example - Actual HTML format](http://new.jpankiewicz.com/email_template/ "Email Template Example")

 [Full Width - image of the template in full width](http://www.new.jpankiewicz.com/email_template/Full_Width_Master_Template.png "Full Width template")

 [Mobile Version - image of the template in mobile size ](http://new.jpankiewicz.com/email_template/Mobile_Responsive_Width_Master_Template.png "Mobile responsive size")

 [Download the screenshot results of a Litmus test](http://www.new.jpankiewicz.com/images/Email%20Client%20snap%20shots.zip "Litmus screenshot test results")


## Tips and tricks

- If you place an 1px png, over a background image you can make a section with a responsive background image clickable
- note, export the png with 1% transparency on a desired color, I find black enhances the image quality and white will light up the image, these changes are really only noticeable by designers. Users wont pick up on it.
- ...(I haven't written them all down yet)


## SUBLIME SNIPPET SHORT HAND
If you do not know what snippets are and your building emails you need to learn, it will save you hours of coding by using snippets.
I have to convert these over for atom, that will occur at a later date.

*snippets are set to be used when the doc type is html*

###Snippet Commands
+ `trt` - single table row for text

+ `email` - email body and frame

+ `spacer` - creates a table row with a fixed height and 100% width, be sure to check for use of multiple cells,(colspan="##")

+ `section1` - `section23` - the sections are labeled in the master email - what you see visually in what will be brought in via snippet(exampel: section1, section2, section14, etc..)

+ `emailround` - calls for an email button with round corners, using MSO code this button will render with round corners in outlook as well

+ `emailbutton` - calls for an email button, using MSO code this button will render properly in outlook as well

+ `textLink` - paragraph hyperlink - will render an 'a' element with a class of textLink which is a globally styled color and fits font-size and line-height of all standard copy

+ `dotCom` - paragraph dotcoms, this is a hyperlink 'a' element that will wrap urls in paragraphs and style it the same color as the paragraph, this is to resolve styling differences of paragraph links from being auto highlighted by email clients. also great for dates and times.



## FULL WIDTH TEMPLATE RENDERING
![Full Width Render](http://new.jpankiewicz.com/images/Full%20Width%20Master%20Template.png "Full width render")


## MOBILE RESPONSIVE WIDTH TEMPLATE RENDERING
![Full Width Render](http://new.jpankiewicz.com/images/Mobile%20Responsive%20Width%20Master%20Template.png "Mobile Responsive")
=======
# HTML-Email-Library
This master file of layout variations is base to start from. For quick and easy email development for developers and even designers. This code gives a structured frame to start with move on from there.
>>>>>>> fc0352e1eb9f7c27c8fb9d8e4d816239c371b367
